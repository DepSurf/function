# Function: <code>wq_worker_waking_up</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void wq_worker_waking_up(struct task_struct *task, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109b310)
Location: kernel/workqueue.c:830
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff8109b310-ffffffff8109b374: wq_worker_waking_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void wq_worker_waking_up(struct task_struct *task, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109e910)
Location: kernel/workqueue.c:850
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:ttwu_do_activate
```
**Symbols:**

```
ffffffff8109e910-ffffffff8109e974: wq_worker_waking_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void wq_worker_waking_up(struct task_struct *task, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a3640)
Location: kernel/workqueue.c:852
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:ttwu_do_activate
```
**Symbols:**

```
ffffffff810a3640-ffffffff810a36a4: wq_worker_waking_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void wq_worker_waking_up(struct task_struct *task, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a0950)
Location: kernel/workqueue.c:852
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:ttwu_do_activate
```
**Symbols:**

```
ffffffff810a0950-ffffffff810a0981: wq_worker_waking_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void wq_worker_waking_up(struct task_struct *task, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a71e0)
Location: kernel/workqueue.c:854
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:ttwu_do_activate
```
**Symbols:**

```
ffffffff810a71e0-ffffffff810a7211: wq_worker_waking_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void wq_worker_waking_up(struct task_struct *task, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810adda0)
Location: kernel/workqueue.c:852
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:ttwu_do_activate
```
**Symbols:**

```
ffffffff810adda0-ffffffff810addd1: wq_worker_waking_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void wq_worker_waking_up(struct task_struct *task, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b6e90)
Location: kernel/workqueue.c:852
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:ttwu_do_activate
```
**Symbols:**

```
ffffffff810b6e90-ffffffff810b6ec1: wq_worker_waking_up (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
