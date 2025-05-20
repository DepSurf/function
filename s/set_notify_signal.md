# Function: <code>set_notify_signal</code>

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
In <code>5.0</code>: Absent ⚠️
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
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff810c907f)
Location: include/linux/tracehook.h:218
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff810caa7b)
Location: include/linux/tracehook.h:218
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff81137e7d)
Location: include/linux/tracehook.h:218
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In fs/io-wq.c (ffffffff813a1fc8)
Location: include/linux/tracehook.h:218
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_worker_cancel
  - fs/io-wq.c:io_wq_worker_cancel
  - fs/io-wq.c:io_wq_worker_wake
  - fs/io-wq.c:io_wq_worker_wake
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff810ddbfb)
Location: include/linux/tracehook.h:220
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff8115abd0)
Location: include/linux/tracehook.h:220
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In fs/io-wq.c (ffffffff813f1373)
Location: include/linux/tracehook.h:220
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_worker_cancel
  - fs/io-wq.c:io_wq_worker_cancel
  - fs/io-wq.c:io_wq_worker_wake
  - fs/io-wq.c:io_wq_worker_wake
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff810f777f)
Location: include/linux/sched/signal.h:374
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff81184497)
Location: include/linux/sched/signal.h:374
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff81119f08)
Location: include/linux/sched/signal.h:375
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In kernel/livepatch/transition.c (ffffffff811bf741)
Location: include/linux/sched/signal.h:375
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff8112718f)
Location: include/linux/sched/signal.h:375
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In kernel/livepatch/transition.c (ffffffff811d2221)
Location: include/linux/sched/signal.h:375
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff8113176f)
Location: include/linux/sched/signal.h:367
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In kernel/livepatch/transition.c (ffffffff811e6ea1)
Location: include/linux/sched/signal.h:367
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
</details>
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
