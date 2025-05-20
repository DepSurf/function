# Function: <code>update_rt_rq_load_avg</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int update_rt_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff810e75a0)
Location: kernel/sched/pelt.c:318
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff810e75a0-ffffffff810e77b7: update_rt_rq_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int update_rt_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff810ee3e0)
Location: kernel/sched/pelt.c:317
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff810ee3e0-ffffffff810ee695: update_rt_rq_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int update_rt_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff810f9fc0)
Location: kernel/sched/pelt.c:317
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff810f9fc0-ffffffff810fa275: update_rt_rq_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int update_rt_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff811041f0)
Location: kernel/sched/pelt.c:354
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff811041f0-ffffffff8110455c: update_rt_rq_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int update_rt_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff81102890)
Location: kernel/sched/pelt.c:350
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff81102890-ffffffff81102be4: update_rt_rq_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int update_rt_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff81104bf0)
Location: kernel/sched/pelt.c:350
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff81104bf0-ffffffff81104f31: update_rt_rq_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int update_rt_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff81122360)
Location: kernel/sched/pelt.c:350
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff81122360-ffffffff81122926: update_rt_rq_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int update_rt_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff811377d0)
Location: kernel/sched/pelt.c:346
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/build_policy.c:task_tick_rt
  - kernel/sched/build_policy.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff811377d0-ffffffff81137da6: update_rt_rq_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int update_rt_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81161e70)
Location: kernel/sched/pelt.c:346
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/build_policy.c:task_tick_rt
  - kernel/sched/build_policy.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff81161e70-ffffffff81162446: update_rt_rq_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int update_rt_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff811725a0)
Location: kernel/sched/pelt.c:346
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/build_policy.c:task_tick_rt
  - kernel/sched/build_policy.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff811725a0-ffffffff81172bc5: update_rt_rq_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int update_rt_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8117feb0)
Location: kernel/sched/pelt.c:346
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/build_policy.c:task_tick_rt
  - kernel/sched/build_policy.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff8117feb0-ffffffff811804d5: update_rt_rq_load_avg (STB_GLOBAL)
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
int update_rt_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffff80001015e9a8)
Location: kernel/sched/pelt.c:317
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
ffff80001015e9a8-ffff80001015ec60: update_rt_rq_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int update_rt_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (c03aae68)
Location: kernel/sched/pelt.c:317
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
c03aae68-c03ab32c: update_rt_rq_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int update_rt_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (c0000000001b3a60)
Location: kernel/sched/pelt.c:317
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
c0000000001b3a60-c0000000001b3e74: update_rt_rq_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int update_rt_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffe000102d94)
Location: kernel/sched/pelt.c:317
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
ffffffe000102d94-ffffffe00010301a: update_rt_rq_load_avg (STB_GLOBAL)
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
int update_rt_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff810f33c0)
Location: kernel/sched/pelt.c:317
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff810f33c0-ffffffff810f3675: update_rt_rq_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int update_rt_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff810e34d0)
Location: kernel/sched/pelt.c:317
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff810e34d0-ffffffff810e3785: update_rt_rq_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int update_rt_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff810f04f0)
Location: kernel/sched/pelt.c:317
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff810f04f0-ffffffff810f07a5: update_rt_rq_load_avg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int update_rt_rq_load_avg(u64 now, struct rq *rq, int running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/pelt.c (ffffffff810fb580)
Location: kernel/sched/pelt.c:317
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff810fb580-ffffffff810fb844: update_rt_rq_load_avg (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
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
