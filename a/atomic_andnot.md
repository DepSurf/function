# Function: <code>atomic_andnot</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f2337)
Location: include/linux/atomic.h:544
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
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
In kernel/rcu/tree.c (ffffffff810fc0b7)
Location: include/linux/atomic.h:548
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c01e3)
Location: include/linux/atomic.h:548
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (ffffffff810d0c0f)
Location: include/linux/atomic.h:548
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/rcu/tree.c (ffffffff81104697)
Location: include/linux/atomic.h:548
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d1183)
Location: include/linux/atomic-fallback.h:650
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (ffffffff810e1767)
Location: include/linux/atomic-fallback.h:650
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/rcu/tree.c (ffffffff811198ca)
Location: include/linux/atomic-fallback.h:650
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810db133)
Location: include/linux/atomic-fallback.h:650
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (ffffffff810ebe07)
Location: include/linux/atomic-fallback.h:650
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/rcu/tree.c (ffffffff81125c5a)
Location: include/linux/atomic-fallback.h:650
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
</details>
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
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d942a)
Location: include/linux/atomic/atomic-instrumented.h:359
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
Location: include/linux/atomic/atomic-instrumented.h:359
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_run_local_work
  - io_uring/io_uring.c:ctx_flush_and_put
  - io_uring/io_uring.c:__io_cqring_overflow_flush
```
```
In io_uring/sqpoll.c (ffffffff8179a8da)
Location: include/linux/atomic/atomic-instrumented.h:359
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
```
```
In io_uring/poll.c (ffffffff8179cee9)
Location: include/linux/atomic/atomic-instrumented.h:359
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_check_events
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
In io_uring/io_uring.c (ffffffff817d047d)
Location: include/linux/atomic/atomic-instrumented.h:840
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_run_local_work
  - io_uring/io_uring.c:ctx_flush_and_put
  - io_uring/io_uring.c:__io_cqring_overflow_flush
```
```
In io_uring/sqpoll.c (ffffffff817db980)
Location: include/linux/atomic/atomic-instrumented.h:840
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
```
```
In io_uring/poll.c (ffffffff817de113)
Location: include/linux/atomic/atomic-instrumented.h:840
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_check_events
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
In kernel/time/tick-sched.c (ffffffff8121c9ac)
Location: include/linux/atomic/atomic-instrumented.h:840
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_dep_clear_signal
  - kernel/time/tick-sched.c:tick_nohz_dep_clear_task
  - kernel/time/tick-sched.c:tick_nohz_dep_clear_cpu
  - kernel/time/tick-sched.c:tick_nohz_dep_clear
```
```
In io_uring/io_uring.c (ffffffff818136bd)
Location: include/linux/atomic/atomic-instrumented.h:840
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_run_local_work
  - io_uring/io_uring.c:ctx_flush_and_put
  - io_uring/io_uring.c:__io_cqring_overflow_flush
```
```
In io_uring/sqpoll.c (ffffffff8181fcf6)
Location: include/linux/atomic/atomic-instrumented.h:840
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
```
```
In io_uring/poll.c (ffffffff818224b4)
Location: include/linux/atomic/atomic-instrumented.h:840
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_check_events
```
</details>
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
Location: include/asm-generic/atomic-instrumented.h:465
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (ffff80001014c12c)
Location: include/asm-generic/atomic-instrumented.h:465
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/rcu/tree.c (ffff80001018c6f8)
Location: include/asm-generic/atomic-instrumented.h:465
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038a804)
Location: arch/arm/include/asm/atomic.h:236
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (c0399da8)
Location: arch/arm/include/asm/atomic.h:236
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/locking/mutex.c (c0e9bdd0)
Location: arch/arm/include/asm/atomic.h:236
Inline: True
```
```
In kernel/locking/rwsem.c (c03b5890)
Location: arch/arm/include/asm/atomic.h:236
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/rcu/tree.c (c03d9d98)
Location: arch/arm/include/asm/atomic.h:236
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000018895c)
Location: include/linux/atomic-fallback.h:650
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (c00000000019ea20)
Location: include/linux/atomic-fallback.h:650
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/rcu/tree.c (c0000000001e63e8)
Location: include/linux/atomic-fallback.h:650
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000ea50a)
Location: include/linux/atomic-fallback.h:650
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (ffffffe0000f573a)
Location: include/linux/atomic-fallback.h:650
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/rcu/tree.c (ffffffe000124180)
Location: include/linux/atomic-fallback.h:650
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_irq_enter
  - kernel/rcu/tree.c:rcu_idle_exit
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d55e3)
Location: include/linux/atomic-fallback.h:650
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (ffffffff810e5f67)
Location: include/linux/atomic-fallback.h:650
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/rcu/tree.c (ffffffff8111e23a)
Location: include/linux/atomic-fallback.h:650
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
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
In kernel/sched/core.c (ffffffff810c3c33)
Location: include/linux/atomic-fallback.h:650
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (ffffffff810d5107)
Location: include/linux/atomic-fallback.h:650
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/rcu/tree.c (ffffffff8110f29a)
Location: include/linux/atomic-fallback.h:650
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
```
In kernel/time/tick-sched.c (ffffffff811348c5)
Location: include/linux/atomic-fallback.h:650
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_dep_clear_signal
  - kernel/time/tick-sched.c:tick_nohz_dep_clear_task
  - kernel/time/tick-sched.c:tick_nohz_dep_clear_cpu
  - kernel/time/tick-sched.c:tick_nohz_dep_clear
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d2423)
Location: include/linux/atomic-fallback.h:650
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (ffffffff810e2337)
Location: include/linux/atomic-fallback.h:650
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/rcu/tree.c (ffffffff8111c12a)
Location: include/linux/atomic-fallback.h:650
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
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
In kernel/sched/core.c (ffffffff810dceb3)
Location: include/linux/atomic-fallback.h:650
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (ffffffff810eded7)
Location: include/linux/atomic-fallback.h:650
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/rcu/tree.c (ffffffff8112785a)
Location: include/linux/atomic-fallback.h:650
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
</details>
</li>
</ul>

## Differences
