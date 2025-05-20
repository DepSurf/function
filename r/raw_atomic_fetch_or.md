# Function: <code>raw_atomic_fetch_or</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
Location: include/linux/atomic/atomic-arch-fallback.h:1678
Inline: True
Inline callers:
  - kernel/sched/fair.c:kick_ilb
```
```
In kernel/irq_work.c (ffffffff812e4d00)
Location: include/linux/atomic/atomic-arch-fallback.h:1678
Inline: True
```
```
In io_uring/io_uring.c (ffffffff817c8f04)
Location: include/linux/atomic/atomic-arch-fallback.h:1678
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_eventfd_unregister
  - io_uring/io_uring.c:io_eventfd_signal
```
```
In io_uring/poll.c (ffffffff817dd775)
Location: include/linux/atomic/atomic-arch-fallback.h:1678
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
Location: include/linux/atomic/atomic-arch-fallback.h:1687
Inline: True
Inline callers:
  - kernel/sched/fair.c:kick_ilb
```
```
In kernel/time/tick-sched.c (ffffffff8121c91a)
Location: include/linux/atomic/atomic-arch-fallback.h:1687
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_dep_set_signal
  - kernel/time/tick-sched.c:tick_nohz_dep_set_task
  - kernel/time/tick-sched.c:tick_nohz_dep_set_cpu
  - kernel/time/tick-sched.c:tick_nohz_dep_set
```
```
In kernel/irq_work.c (ffffffff81302db0)
Location: include/linux/atomic/atomic-arch-fallback.h:1687
Inline: True
```
```
In io_uring/io_uring.c (ffffffff8180dc44)
Location: include/linux/atomic/atomic-arch-fallback.h:1687
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_eventfd_signal
```
```
In io_uring/poll.c (ffffffff81821ac5)
Location: include/linux/atomic/atomic-arch-fallback.h:1687
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_get_ownership_slowpath
```
```
In io_uring/register.c (ffffffff8182b744)
Location: include/linux/atomic/atomic-arch-fallback.h:1687
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
