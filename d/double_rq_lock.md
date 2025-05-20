# Function: <code>double_rq_lock</code>

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
In kernel/sched/core.c (ffffffff818204b4)
Location: kernel/sched/sched.h:1619
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:migrate_swap_stop
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
In kernel/sched/core.c (ffffffff8189a918)
Location: kernel/sched/sched.h:1602
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:migrate_swap_stop
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
In kernel/sched/core.c (ffffffff818cef35)
Location: kernel/sched/sched.h:1641
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:migrate_swap_stop
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
In kernel/sched/core.c (ffffffff81906487)
Location: kernel/sched/sched.h:1874
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:migrate_swap_stop
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
In kernel/sched/core.c (ffffffff81990511)
Location: kernel/sched/sched.h:1913
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:migrate_swap_stop
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
In kernel/sched/core.c (ffffffff819ecd41)
Location: kernel/sched/sched.h:1957
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:migrate_swap_stop
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
In kernel/sched/core.c (ffffffff81a27f81)
Location: kernel/sched/sched.h:1992
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
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
In kernel/sched/core.c (ffffffff81a98701)
Location: kernel/sched/sched.h:2054
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81ad0051)
Location: kernel/sched/sched.h:2097
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81bc8a6e)
Location: kernel/sched/sched.h:2137
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81c4183e)
Location: kernel/sched/sched.h:2260
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81c337ad)
Location: kernel/sched/sched.h:2296
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void double_rq_lock(struct rq *rq1, struct rq *rq2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f3210)
Location: kernel/sched/core.c:525
Inline: False
Direct callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:find_lock_lowest_rq
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
```
**Symbols:**

```
ffffffff810f3210-ffffffff810f32a0: double_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void double_rq_lock(struct rq *rq1, struct rq *rq2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8110f1d0)
Location: kernel/sched/core.c:595
Inline: False
Direct callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:find_lock_lowest_rq
```
**Symbols:**

```
ffffffff8110f1d0-ffffffff8110f281: double_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void double_rq_lock(struct rq *rq1, struct rq *rq2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81136000)
Location: kernel/sched/core.c:588
Inline: False
Direct callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:find_lock_lowest_rq
```
**Symbols:**

```
ffffffff81136000-ffffffff811360b1: double_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void double_rq_lock(struct rq *rq1, struct rq *rq2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81145000)
Location: kernel/sched/core.c:609
Inline: False
Direct callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:find_lock_lowest_rq
```
**Symbols:**

```
ffffffff81145000-ffffffff811450b1: double_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void double_rq_lock(struct rq *rq1, struct rq *rq2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81150520)
Location: kernel/sched/core.c:610
Inline: False
Direct callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:find_lock_lowest_rq
```
**Symbols:**

```
ffffffff81150520-ffffffff811505d1: double_rq_lock (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010da1d74)
Location: kernel/sched/sched.h:2097
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0e99e70)
Location: kernel/sched/sched.h:2097
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000ee2fe0)
Location: kernel/sched/sched.h:2097
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:migrate_swap_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0008c545c)
Location: kernel/sched/sched.h:2097
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81a6eec1)
Location: kernel/sched/sched.h:2097
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81a2b294)
Location: kernel/sched/sched.h:2097
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81adb2d1)
Location: kernel/sched/sched.h:2097
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81ae77b6)
Location: kernel/sched/sched.h:2097
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
```
```
In kernel/sched/rt.c (ffffffff810efe56)
Location: kernel/sched/sched.h:2097
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810f280c)
Location: kernel/sched/sched.h:2097
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
