# Function: <code>__set_notify_signal</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff810f776b)
Location: include/linux/sched/signal.h:364
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff81184497)
Location: include/linux/sched/signal.h:364
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In io_uring/io-wq.c (ffffffff816da1a4)
Location: include/linux/sched/signal.h:364
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker_cancel
  - io_uring/io-wq.c:io_wq_worker_wake
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
In kernel/task_work.c (ffffffff81119ef4)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
  - kernel/task_work.c:task_work_add
```
```
In kernel/livepatch/transition.c (ffffffff811bf741)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In io_uring/io-wq.c (ffffffff817a6234)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker_cancel
  - io_uring/io-wq.c:io_wq_worker_wake
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
In kernel/task_work.c (ffffffff81127169)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
  - kernel/task_work.c:task_work_add
```
```
In kernel/livepatch/transition.c (ffffffff811d2221)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In io_uring/io-wq.c (ffffffff817e7194)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker_cancel
  - io_uring/io-wq.c:io_wq_worker_wake
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
In kernel/task_work.c (ffffffff81131749)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
  - kernel/task_work.c:task_work_add
```
```
In kernel/livepatch/transition.c (ffffffff811e6ea1)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In io_uring/io-wq.c (ffffffff8182cf54)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker_cancel
  - io_uring/io-wq.c:io_wq_worker_wake
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
