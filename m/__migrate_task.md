# Function: <code>__migrate_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct rq *__migrate_task(struct rq *rq, struct task_struct *p, int dest_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ab740)
Location: kernel/sched/core.c:1104
Inline: False
Direct callers:
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_call
```
**Symbols:**

```
ffffffff810ab740-ffffffff810ab779: __migrate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct rq *__migrate_task(struct rq *rq, struct task_struct *p, int dest_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ae3a0)
Location: kernel/sched/core.c:1022
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:migration_cpu_stop
```
**Symbols:**

```
ffffffff810ae3a0-ffffffff810ae3cb: __migrate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct rq *__migrate_task(struct rq *rq, struct task_struct *p, int dest_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b4500)
Location: kernel/sched/core.c:1029
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:migration_cpu_stop
```
**Symbols:**

```
ffffffff810b4500-ffffffff810b452b: __migrate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct rq *__migrate_task(struct rq *rq, struct rq_flags *rf, struct task_struct *p, int dest_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b0500)
Location: kernel/sched/core.c:951
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:migration_cpu_stop
```
**Symbols:**

```
ffffffff810b0500-ffffffff810b0558: __migrate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct rq *__migrate_task(struct rq *rq, struct rq_flags *rf, struct task_struct *p, int dest_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b7930)
Location: kernel/sched/core.c:961
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:migration_cpu_stop
```
**Symbols:**

```
ffffffff810b7930-ffffffff810b799a: __migrate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct rq *__migrate_task(struct rq *rq, struct rq_flags *rf, struct task_struct *p, int dest_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bf4a0)
Location: kernel/sched/core.c:966
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:migration_cpu_stop
```
**Symbols:**

```
ffffffff810bf4a0-ffffffff810bf51a: __migrate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct rq *__migrate_task(struct rq *rq, struct rq_flags *rf, struct task_struct *p, int dest_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c87a0)
Location: kernel/sched/core.c:961
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:migration_cpu_stop
```
**Symbols:**

```
ffffffff810c87a0-ffffffff810c881a: __migrate_task (STB_LOCAL)
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
In kernel/sched/core.c (ffffffff810d3877)
Location: kernel/sched/core.c:1404
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
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
In kernel/sched/core.c (ffffffff810dde65)
Location: kernel/sched/core.c:1524
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
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
In kernel/sched/core.c (ffffffff810e30c9)
Location: kernel/sched/core.c:1589
Inline: True
Inline callers:
  - kernel/sched/core.c:migrate_tasks
  - kernel/sched/core.c:migrate_tasks
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
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
In kernel/sched/core.c (ffffffff810e0914)
Location: kernel/sched/core.c:1886
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
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
In kernel/sched/core.c (ffffffff810e2734)
Location: kernel/sched/core.c:1894
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f8d45)
Location: kernel/sched/core.c:2272
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81115130)
Location: kernel/sched/core.c:2371
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113c4d0)
Location: kernel/sched/core.c:2367
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8115012a)
Location: kernel/sched/core.c:2542
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8115bffa)
Location: kernel/sched/core.c:2568
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
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
In kernel/sched/core.c (ffff80001013d7d8)
Location: kernel/sched/core.c:1524
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
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
In kernel/sched/core.c (c038d80c)
Location: kernel/sched/core.c:1524
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
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
In kernel/sched/core.c (c00000000018c6bc)
Location: kernel/sched/core.c:1524
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
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
In kernel/sched/core.c (ffffffe0000ea42a)
Location: kernel/sched/core.c:1524
Inline: True
Inline callers:
  - kernel/sched/core.c:migration_cpu_stop
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
In kernel/sched/core.c (ffffffff810d8055)
Location: kernel/sched/core.c:1524
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
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
In kernel/sched/core.c (ffffffff810c6a24)
Location: kernel/sched/core.c:1524
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
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
In kernel/sched/core.c (ffffffff810d4845)
Location: kernel/sched/core.c:1524
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dfc4d)
Location: kernel/sched/core.c:1524
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
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
<code>rq, p, dest_cpu</code> ➡️ <code>rq, rf, p, dest_cpu</code>
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
</ul>
