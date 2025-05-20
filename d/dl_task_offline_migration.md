# Function: <code>dl_task_offline_migration</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c2987)
Location: kernel/sched/deadline.c:237
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_timer
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c630f)
Location: kernel/sched/deadline.c:243
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_timer
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810cc2df)
Location: kernel/sched/deadline.c:243
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_timer
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c863c)
Location: kernel/sched/deadline.c:496
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_timer
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
In kernel/sched/deadline.c (ffffffff810cfd66)
Location: kernel/sched/deadline.c:495
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_timer
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810d6fa9)
Location: kernel/sched/deadline.c:529
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_timer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e14f9)
Location: kernel/sched/deadline.c:530
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_timer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e7f9d)
Location: kernel/sched/deadline.c:529
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_timer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct rq *dl_task_offline_migration(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f3ab0)
Location: kernel/sched/deadline.c:529
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810f3ab0-ffffffff810f40c1: dl_task_offline_migration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rq *dl_task_offline_migration(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fd4a0)
Location: kernel/sched/deadline.c:531
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810fd4a0-ffffffff810fda8b: dl_task_offline_migration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rq *dl_task_offline_migration(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fba60)
Location: kernel/sched/deadline.c:608
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810fba60-ffffffff810fc04b: dl_task_offline_migration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rq *dl_task_offline_migration(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fdd80)
Location: kernel/sched/deadline.c:594
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810fdd80-ffffffff810fe360: dl_task_offline_migration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct rq *dl_task_offline_migration(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/deadline.c (0)
Location: kernel/sched/deadline.c:594
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff81117200-ffffffff811179f3: dl_task_offline_migration (STB_LOCAL)
ffffffff81ca6a66-ffffffff81ca6b7d: dl_task_offline_migration.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct rq *dl_task_offline_migration(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/deadline.c:666
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:dl_task_timer
```
**Symbols:**

```
ffffffff811341f0-ffffffff81134940: dl_task_offline_migration (STB_LOCAL)
ffffffff81e56462-ffffffff81e5657b: dl_task_offline_migration.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct rq *dl_task_offline_migration(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/deadline.c:668
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:dl_task_timer
```
**Symbols:**

```
ffffffff8115e6e0-ffffffff8115ee46: dl_task_offline_migration (STB_LOCAL)
ffffffff8205768c-ffffffff820577a5: dl_task_offline_migration.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct rq *dl_task_offline_migration(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/deadline.c:663
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:dl_task_timer
```
**Symbols:**

```
ffffffff8116edd0-ffffffff8116f53f: dl_task_offline_migration (STB_LOCAL)
ffffffff820d5eb2-ffffffff820d5fcb: dl_task_offline_migration.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct rq *dl_task_offline_migration(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/deadline.c:662
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:dl_task_timer
```
**Symbols:**

```
ffffffff8117c650-ffffffff8117cdbf: dl_task_offline_migration (STB_LOCAL)
ffffffff821b0fc1-ffffffff821b10da: dl_task_offline_migration.cold (STB_LOCAL)
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
struct rq *dl_task_offline_migration(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffff800010155d48)
Location: kernel/sched/deadline.c:529
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffff800010155d48-ffff800010156494: dl_task_offline_migration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct rq *dl_task_offline_migration(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c03a383c)
Location: kernel/sched/deadline.c:529
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
c03a383c-c03a40f8: dl_task_offline_migration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct rq *dl_task_offline_migration(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c0000000001aa440)
Location: kernel/sched/deadline.c:529
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
c0000000001aa440-c0000000001aacc4: dl_task_offline_migration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct rq *dl_task_offline_migration(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffe0000fbc6c)
Location: kernel/sched/deadline.c:529
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffe0000fbc6c-ffffffe0000fc20c: dl_task_offline_migration (STB_LOCAL)
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
struct rq *dl_task_offline_migration(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810eceb0)
Location: kernel/sched/deadline.c:529
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810eceb0-ffffffff810ed4c1: dl_task_offline_migration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct rq *dl_task_offline_migration(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810dcf50)
Location: kernel/sched/deadline.c:529
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810dcf50-ffffffff810dd55c: dl_task_offline_migration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct rq *dl_task_offline_migration(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e9fe0)
Location: kernel/sched/deadline.c:529
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810e9fe0-ffffffff810ea5f1: dl_task_offline_migration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct rq *dl_task_offline_migration(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f4fa0)
Location: kernel/sched/deadline.c:529
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810f4fa0-ffffffff810f55af: dl_task_offline_migration (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
