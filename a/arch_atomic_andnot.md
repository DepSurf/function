# Function: <code>arch_atomic_andnot</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81bbf891)
Location: include/linux/atomic-arch-fallback.h:652
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
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
In kernel/rcu/tree.c (ffffffff81c38671)
Location: include/linux/atomic-arch-fallback.h:722
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
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
In kernel/rcu/tree.c (ffffffff81c2aa81)
Location: include/linux/atomic-arch-fallback.h:722
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d942a)
Location: include/linux/atomic/atomic-arch-fallback.h:806
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_sq_thread
  - io_uring/io_uring.c:ctx_flush_and_put
  - io_uring/io_uring.c:__io_cqring_overflow_flush
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
In io_uring/io_uring.c (ffffffff8178f08b)
Location: include/linux/atomic/atomic-arch-fallback.h:806
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_run_local_work
  - io_uring/io_uring.c:ctx_flush_and_put
  - io_uring/io_uring.c:__io_cqring_overflow_flush
```
```
In io_uring/sqpoll.c (ffffffff8179a8da)
Location: include/linux/atomic/atomic-arch-fallback.h:806
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
```
```
In io_uring/poll.c (ffffffff8179cee9)
Location: include/linux/atomic/atomic-arch-fallback.h:806
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_check_events
```
</details>
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013add0)
Location: arch/arm64/include/asm/atomic.h:25
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (ffff80001014c12c)
Location: arch/arm64/include/asm/atomic.h:25
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/rcu/tree.c (ffff80001018c6f8)
Location: arch/arm64/include/asm/atomic.h:25
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
</details>
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
