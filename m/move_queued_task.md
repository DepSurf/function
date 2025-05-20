# Function: <code>move_queued_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct rq *move_queued_task(struct rq *rq, struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ab3e0)
Location: kernel/sched/core.c:1070
Inline: False
Direct callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__migrate_task
```
**Symbols:**

```
ffffffff810ab3e0-ffffffff810ab4f7: move_queued_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct rq *move_queued_task(struct rq *rq, struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ae080)
Location: kernel/sched/core.c:988
Inline: False
Direct callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__migrate_task
```
**Symbols:**

```
ffffffff810ae080-ffffffff810ae192: move_queued_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct rq *move_queued_task(struct rq *rq, struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b41f0)
Location: kernel/sched/core.c:995
Inline: False
Direct callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__migrate_task
```
**Symbols:**

```
ffffffff810b41f0-ffffffff810b42fe: move_queued_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct rq *move_queued_task(struct rq *rq, struct rq_flags *rf, struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b0140)
Location: kernel/sched/core.c:916
Inline: False
Direct callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
**Symbols:**

```
ffffffff810b0140-ffffffff810b02c5: move_queued_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct rq *move_queued_task(struct rq *rq, struct rq_flags *rf, struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b7560)
Location: kernel/sched/core.c:926
Inline: True
Direct callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
**Symbols:**

```
ffffffff810b7560-ffffffff810b76f1: move_queued_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct rq *move_queued_task(struct rq *rq, struct rq_flags *rf, struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bf100)
Location: kernel/sched/core.c:931
Inline: True
Direct callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
**Symbols:**

```
ffffffff810bf100-ffffffff810bf285: move_queued_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct rq *move_queued_task(struct rq *rq, struct rq_flags *rf, struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c8390)
Location: kernel/sched/core.c:926
Inline: True
Direct callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
**Symbols:**

```
ffffffff810c8390-ffffffff810c8582: move_queued_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct rq *move_queued_task(struct rq *rq, struct rq_flags *rf, struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cfa10)
Location: kernel/sched/core.c:1369
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
```
**Symbols:**

```
ffffffff810cfa10-ffffffff810cff90: move_queued_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct rq *move_queued_task(struct rq *rq, struct rq_flags *rf, struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d98d0)
Location: kernel/sched/core.c:1489
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
```
**Symbols:**

```
ffffffff810d98d0-ffffffff810d9f0e: move_queued_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rq *move_queued_task(struct rq *rq, struct rq_flags *rf, struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e2b10)
Location: kernel/sched/core.c:1554
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_tasks
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
```
**Symbols:**

```
ffffffff810e2b10-ffffffff810e2bc9: move_queued_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rq *move_queued_task(struct rq *rq, struct rq_flags *rf, struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dfcc0)
Location: kernel/sched/core.c:1840
Inline: False
Direct callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
```
**Symbols:**

```
ffffffff810dfcc0-ffffffff810dfdae: move_queued_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rq *move_queued_task(struct rq *rq, struct rq_flags *rf, struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e1aa0)
Location: kernel/sched/core.c:1848
Inline: False
Direct callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
```
**Symbols:**

```
ffffffff810e1aa0-ffffffff810e1b8e: move_queued_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct rq *move_queued_task(struct rq *rq, struct rq_flags *rf, struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:2226
Inline: False
Direct callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
```
**Symbols:**

```
ffffffff810f7cc0-ffffffff810f7de3: move_queued_task (STB_LOCAL)
ffffffff81ca5d76-ffffffff81ca5d8b: move_queued_task.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct rq *move_queued_task(struct rq *rq, struct rq_flags *rf, struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:2325
Inline: False
Direct callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
```
**Symbols:**

```
ffffffff81113f80-ffffffff811140b6: move_queued_task (STB_LOCAL)
ffffffff81e556b3-ffffffff81e556c8: move_queued_task.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct rq *move_queued_task(struct rq *rq, struct rq_flags *rf, struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:2321
Inline: False
Direct callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
```
**Symbols:**

```
ffffffff8113b2b0-ffffffff8113b3e8: move_queued_task (STB_LOCAL)
ffffffff82056b25-ffffffff82056b3a: move_queued_task.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct rq *move_queued_task(struct rq *rq, struct rq_flags *rf, struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:2496
Inline: False
Direct callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
```
**Symbols:**

```
ffffffff8114e6a0-ffffffff8114e80c: move_queued_task (STB_LOCAL)
ffffffff820d52c4-ffffffff820d52d9: move_queued_task.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct rq *move_queued_task(struct rq *rq, struct rq_flags *rf, struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:2522
Inline: False
Direct callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
```
**Symbols:**

```
ffffffff8115a500-ffffffff8115a66c: move_queued_task (STB_LOCAL)
ffffffff821b023c-ffffffff821b0251: move_queued_task.cold (STB_LOCAL)
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
struct rq *move_queued_task(struct rq *rq, struct rq_flags *rf, struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010139800)
Location: kernel/sched/core.c:1489
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
```
**Symbols:**

```
ffff800010139800-ffff8000101398e4: move_queued_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct rq *move_queued_task(struct rq *rq, struct rq_flags *rf, struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038906c)
Location: kernel/sched/core.c:1489
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
```
**Symbols:**

```
c038906c-c03896c4: move_queued_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct rq *move_queued_task(struct rq *rq, struct rq_flags *rf, struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0000000001865d0)
Location: kernel/sched/core.c:1489
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
```
**Symbols:**

```
c0000000001865d0-c000000000186d3c: move_queued_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct rq *move_queued_task(struct rq *rq, struct rq_flags *rf, struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e92be)
Location: kernel/sched/core.c:1489
Inline: False
Direct callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
```
**Symbols:**

```
ffffffe0000e92be-ffffffe0000e94da: move_queued_task (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct rq *move_queued_task(struct rq *rq, struct rq_flags *rf, struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d3d80)
Location: kernel/sched/core.c:1489
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
```
**Symbols:**

```
ffffffff810d3d80-ffffffff810d43c0: move_queued_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct rq *move_queued_task(struct rq *rq, struct rq_flags *rf, struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c23d0)
Location: kernel/sched/core.c:1489
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
```
**Symbols:**

```
ffffffff810c23d0-ffffffff810c2a0e: move_queued_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct rq *move_queued_task(struct rq *rq, struct rq_flags *rf, struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d1000)
Location: kernel/sched/core.c:1489
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
```
**Symbols:**

```
ffffffff810d1000-ffffffff810d1200: move_queued_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct rq *move_queued_task(struct rq *rq, struct rq_flags *rf, struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810db530)
Location: kernel/sched/core.c:1489
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
```
**Symbols:**

```
ffffffff810db530-ffffffff810dbb6e: move_queued_task (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct rq_flags *rf</code>
</li>
<li>
<b>Param reordered. </b>
<code>rq, p, new_cpu</code> ➡️ <code>rq, rf, p, new_cpu</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
