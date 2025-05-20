# Function: <code>__update_load_avg_cfs_rq</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c266a)
Location: kernel/sched/fair.c:3008
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c9a5f)
Location: kernel/sched/fair.c:3310
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c5110)
Location: kernel/sched/fair.c:3361
Inline: True
Direct callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
```
**Symbols:**

```
ffffffff810c5110-ffffffff810c52b4: __update_load_avg_cfs_rq.isra.46 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __update_load_avg_cfs_rq(u64 now, int cpu, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff810e7370)
Location: kernel/sched/pelt.c:293
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
```
**Symbols:**

```
ffffffff810e7370-ffffffff810e759b: __update_load_avg_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff810ee120)
Location: kernel/sched/pelt.c:291
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
ffffffff810ee120-ffffffff810ee3de: __update_load_avg_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff810f9d00)
Location: kernel/sched/pelt.c:291
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
ffffffff810f9d00-ffffffff810f9fbe: __update_load_avg_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff81103e50)
Location: kernel/sched/pelt.c:328
Inline: False
Direct callers:
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:__update_blocked_fair
```
**Symbols:**

```
ffffffff81103e50-ffffffff811041e6: __update_load_avg_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff81102510)
Location: kernel/sched/pelt.c:324
Inline: False
Direct callers:
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:__update_blocked_fair
```
**Symbols:**

```
ffffffff81102510-ffffffff81102885: __update_load_avg_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff81104890)
Location: kernel/sched/pelt.c:324
Inline: False
Direct callers:
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:__update_blocked_fair
```
**Symbols:**

```
ffffffff81104890-ffffffff81104be9: __update_load_avg_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff81121d70)
Location: kernel/sched/pelt.c:324
Inline: False
Direct callers:
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:__update_blocked_fair
```
**Symbols:**

```
ffffffff81121d70-ffffffff8112235e: __update_load_avg_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff811371f0)
Location: kernel/sched/pelt.c:320
Inline: False
Direct callers:
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:__update_blocked_fair
```
**Symbols:**

```
ffffffff811371f0-ffffffff811377ce: __update_load_avg_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81161880)
Location: kernel/sched/pelt.c:320
Inline: False
Direct callers:
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:__update_blocked_fair
```
**Symbols:**

```
ffffffff81161880-ffffffff81161e60: __update_load_avg_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81171f90)
Location: kernel/sched/pelt.c:320
Inline: False
Direct callers:
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:__update_blocked_fair
```
**Symbols:**

```
ffffffff81171f90-ffffffff8117258a: __update_load_avg_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8117f8a0)
Location: kernel/sched/pelt.c:320
Inline: False
Direct callers:
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:__update_blocked_fair
```
**Symbols:**

```
ffffffff8117f8a0-ffffffff8117fe9a: __update_load_avg_cfs_rq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffff80001015e6e0)
Location: kernel/sched/pelt.c:291
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
ffff80001015e6e0-ffff80001015e9a8: __update_load_avg_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (c03aa994)
Location: kernel/sched/pelt.c:291
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
c03aa994-c03aae68: __update_load_avg_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (c0000000001b3630)
Location: kernel/sched/pelt.c:291
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
c0000000001b3630-c0000000001b3a54: __update_load_avg_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffe000102b36)
Location: kernel/sched/pelt.c:291
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
ffffffe000102b36-ffffffe000102d94: __update_load_avg_cfs_rq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff810f3100)
Location: kernel/sched/pelt.c:291
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
ffffffff810f3100-ffffffff810f33be: __update_load_avg_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff810e3210)
Location: kernel/sched/pelt.c:291
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
ffffffff810e3210-ffffffff810e34ce: __update_load_avg_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff810f0230)
Location: kernel/sched/pelt.c:291
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
ffffffff810f0230-ffffffff810f04ee: __update_load_avg_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff810fb2b0)
Location: kernel/sched/pelt.c:291
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
ffffffff810fb2b0-ffffffff810fb57d: __update_load_avg_cfs_rq (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int cpu</code>
</li>
<li>
<b>Param reordered. </b>
<code>now, cpu, cfs_rq</code> ➡️ <code>now, cfs_rq</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
