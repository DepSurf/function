# Function: <code>atomic_fetch_or</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c4c2e)
Location: include/asm-generic/atomic-instrumented.h:304
Inline: True
Inline callers:
  - kernel/sched/fair.c:kick_ilb
```
```
In kernel/locking/qspinlock.c (ffffffff810e536b)
Location: include/asm-generic/atomic-instrumented.h:304
Inline: True
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
In kernel/sched/fair.c (ffffffff810cdffe)
Location: include/asm-generic/atomic-instrumented.h:351
Inline: True
Inline callers:
  - kernel/sched/fair.c:kick_ilb
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
In kernel/sched/fair.c (ffffffff810d6411)
Location: include/asm-generic/atomic-instrumented.h:523
Inline: True
Inline callers:
  - kernel/sched/fair.c:kick_ilb
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
In kernel/sched/fair.c (ffffffff810e0b11)
Location: include/asm-generic/atomic-instrumented.h:523
Inline: True
Inline callers:
  - kernel/sched/fair.c:kick_ilb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e9013)
Location: include/asm-generic/atomic-instrumented.h:524
Inline: True
Inline callers:
  - kernel/sched/fair.c:kick_ilb
```
```
In kernel/irq_work.c (ffffffff811f7350)
Location: include/asm-generic/atomic-instrumented.h:524
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e6dc8)
Location: include/asm-generic/atomic-instrumented.h:524
Inline: True
Inline callers:
  - kernel/sched/fair.c:kick_ilb
```
```
In kernel/irq_work.c (ffffffff811f5ec0)
Location: include/asm-generic/atomic-instrumented.h:524
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
In kernel/sched/fair.c (ffffffff810f675c)
Location: include/asm-generic/atomic-instrumented.h:524
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balancer_kick
```
```
In kernel/irq_work.c (ffffffff811f6db0)
Location: include/asm-generic/atomic-instrumented.h:524
Inline: True
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
In kernel/sched/fair.c (ffffffff8111073b)
Location: include/linux/atomic/atomic-instrumented.h:382
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balancer_kick
```
```
In kernel/irq_work.c (ffffffff81228380)
Location: include/linux/atomic/atomic-instrumented.h:382
Inline: True
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
In kernel/sched/fair.c (ffffffff8112c77b)
Location: include/linux/atomic/atomic-instrumented.h:403
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balancer_kick
```
```
In kernel/irq_work.c (ffffffff81269310)
Location: include/linux/atomic/atomic-instrumented.h:403
Inline: True
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
In kernel/sched/fair.c (ffffffff81156421)
Location: include/linux/atomic/atomic-instrumented.h:403
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balancer_kick
```
```
In kernel/irq_work.c (ffffffff812be140)
Location: include/linux/atomic/atomic-instrumented.h:403
Inline: True
```
```
In io_uring/io_uring.c (ffffffff81788824)
Location: include/linux/atomic/atomic-instrumented.h:403
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_eventfd_unregister
  - io_uring/io_uring.c:io_eventfd_signal
```
```
In io_uring/poll.c (ffffffff8179c545)
Location: include/linux/atomic/atomic-instrumented.h:403
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_get_ownership_slowpath
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
In kernel/sched/fair.c (ffffffff811538c4)
Location: include/linux/atomic/atomic-instrumented.h:950
Inline: True
Inline callers:
  - kernel/sched/fair.c:kick_ilb
```
```
In kernel/irq_work.c (ffffffff812e4d00)
Location: include/linux/atomic/atomic-instrumented.h:950
Inline: True
```
```
In io_uring/io_uring.c (ffffffff817c8f04)
Location: include/linux/atomic/atomic-instrumented.h:950
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_eventfd_unregister
  - io_uring/io_uring.c:io_eventfd_signal
```
```
In io_uring/poll.c (ffffffff817dd775)
Location: include/linux/atomic/atomic-instrumented.h:950
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_get_ownership_slowpath
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
In kernel/sched/fair.c (ffffffff8115f948)
Location: include/linux/atomic/atomic-instrumented.h:950
Inline: True
Inline callers:
  - kernel/sched/fair.c:kick_ilb
```
```
In kernel/time/tick-sched.c (ffffffff8121c91a)
Location: include/linux/atomic/atomic-instrumented.h:950
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_dep_set_signal
  - kernel/time/tick-sched.c:tick_nohz_dep_set_task
  - kernel/time/tick-sched.c:tick_nohz_dep_set_cpu
  - kernel/time/tick-sched.c:tick_nohz_dep_set
```
```
In kernel/irq_work.c (ffffffff81302db0)
Location: include/linux/atomic/atomic-instrumented.h:950
Inline: True
```
```
In io_uring/io_uring.c (ffffffff8180dc44)
Location: include/linux/atomic/atomic-instrumented.h:950
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_eventfd_signal
```
```
In io_uring/poll.c (ffffffff81821ac5)
Location: include/linux/atomic/atomic-instrumented.h:950
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_get_ownership_slowpath
```
```
In io_uring/register.c (ffffffff8182b744)
Location: include/linux/atomic/atomic-instrumented.h:950
Inline: True
Inline callers:
  - io_uring/register.c:io_eventfd_unregister
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
In kernel/sched/fair.c (ffff8000101424a0)
Location: include/asm-generic/atomic-instrumented.h:523
Inline: True
Inline callers:
  - kernel/sched/fair.c:kick_ilb
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
In kernel/sched/fair.c (c0391018)
Location: include/linux/atomic-fallback.h:767
Inline: True
Inline callers:
  - kernel/sched/fair.c:kick_ilb
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
In kernel/sched/fair.c (c000000000190a8c)
Location: include/linux/atomic-fallback.h:767
Inline: True
Inline callers:
  - kernel/sched/fair.c:kick_ilb
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
In kernel/sched/fair.c (ffffffe0000eef26)
Location: arch/riscv/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/sched/fair.c:kick_ilb
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
In kernel/sched/fair.c (ffffffff810dacc1)
Location: include/asm-generic/atomic-instrumented.h:523
Inline: True
Inline callers:
  - kernel/sched/fair.c:kick_ilb
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c9cd1)
Location: include/asm-generic/atomic-instrumented.h:523
Inline: True
Inline callers:
  - kernel/sched/fair.c:kick_ilb
```
```
In kernel/time/tick-sched.c (ffffffff811347eb)
Location: include/asm-generic/atomic-instrumented.h:523
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_dep_set_cpu
  - kernel/time/tick-sched.c:tick_nohz_dep_set_all
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
In kernel/sched/fair.c (ffffffff810d7041)
Location: include/asm-generic/atomic-instrumented.h:523
Inline: True
Inline callers:
  - kernel/sched/fair.c:kick_ilb
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
In kernel/sched/fair.c (ffffffff810e29f1)
Location: include/asm-generic/atomic-instrumented.h:523
Inline: True
Inline callers:
  - kernel/sched/fair.c:kick_ilb
```
</details>
</li>
</ul>

## Differences
