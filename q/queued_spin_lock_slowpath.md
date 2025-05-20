# Function: <code>queued_spin_lock_slowpath</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81031b42)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81052954)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff81824005)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
```
```
In kernel/locking/lglock.c (ffffffff810ca4e5)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - kernel/locking/lglock.c:lg_local_lock
  - kernel/locking/lglock.c:lg_local_lock_cpu
  - kernel/locking/lglock.c:lg_global_lock
  - kernel/locking/lglock.c:lg_double_lock
  - kernel/locking/lglock.c:lg_double_lock
```
```
In kernel/locking/qrwlock.c (ffffffff810cbda6)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/trace_clock.c (ffffffff8113fe66)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff811464e3)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_start
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
```
```
In kernel/trace/trace.c (ffffffff8114aa8b)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:trace_find_cmdline
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81157547)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff81157e71)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81030c52)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81052a74)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff8189efc0)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/lglock.c (ffffffff810cef16)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - kernel/locking/lglock.c:lg_global_lock
  - kernel/locking/lglock.c:lg_double_lock
  - kernel/locking/lglock.c:lg_double_lock
  - kernel/locking/lglock.c:lg_local_lock_cpu
  - kernel/locking/lglock.c:lg_local_lock
```
```
In kernel/locking/qrwlock.c (ffffffff810d08b6)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/trace_clock.c (ffffffff811484d6)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff8114f5df)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_start
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff81155870)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81161dc7)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff811626ee)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81030832)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81055393)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff818d4480)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff810d7326)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/trace_clock.c (ffffffff81152386)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff81159772)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_start
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff8115fd40)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8116c921)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff8116da28)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8102eb02)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81054cb6)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff8190b5f0)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff810d6366)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/trace_clock.c (ffffffff81154966)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff8115ef23)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811631d8)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8116fcce)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff81170d87)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In lib/nmi_backtrace.c (ffffffff818efd98)
Location: arch/x86/include/asm/qspinlock.h:26
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810309d2)
Location: arch/x86/include/asm/qspinlock.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81058a76)
Location: arch/x86/include/asm/qspinlock.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff81995760)
Location: arch/x86/include/asm/qspinlock.h:28
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff810de318)
Location: arch/x86/include/asm/qspinlock.h:28
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/trace_clock.c (ffffffff81161186)
Location: arch/x86/include/asm/qspinlock.h:28
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff81169265)
Location: arch/x86/include/asm/qspinlock.h:28
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff81170198)
Location: arch/x86/include/asm/qspinlock.h:28
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8117ce29)
Location: arch/x86/include/asm/qspinlock.h:28
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff8117df47)
Location: arch/x86/include/asm/qspinlock.h:28
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In lib/nmi_backtrace.c (ffffffff819761d8)
Location: arch/x86/include/asm/qspinlock.h:28
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
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
In arch/x86/kernel/dumpstack.c (ffffffff81031be2)
Location: arch/x86/include/asm/qspinlock.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8105b996)
Location: arch/x86/include/asm/qspinlock.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff819f1ca0)
Location: arch/x86/include/asm/qspinlock.h:30
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff810e69f8)
Location: arch/x86/include/asm/qspinlock.h:30
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/trace_clock.c (ffffffff811700b6)
Location: arch/x86/include/asm/qspinlock.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff8117b405)
Location: arch/x86/include/asm/qspinlock.h:30
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff8117f918)
Location: arch/x86/include/asm/qspinlock.h:30
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8118be6a)
Location: arch/x86/include/asm/qspinlock.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff8118d06a)
Location: arch/x86/include/asm/qspinlock.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81032eee)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81061614)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff81a2d2ce)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff810f1ff6)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/trace_clock.c (ffffffff8117dc64)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff81185743)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff8118d1f6)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81199888)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff8119a9e8)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81034cfe)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81064d04)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff81a9d5b0)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff810fa456)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/trace_clock.c (ffffffff8118ab64)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff81192a83)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811a0600)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a74cd)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff811a8675)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/bpf/helpers.c (ffffffff811e67fb)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
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
In arch/x86/kernel/dumpstack.c (ffffffff8103552e)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81065374)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff81ad4d90)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff81106236)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/trace_clock.c (ffffffff81196a54)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff8119e703)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811ac030)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b2cbd)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff811b3e85)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/bpf/helpers.c (ffffffff811f2f4b)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8103750e)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106bcd4)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff81bccb32)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff81111265)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/trace_clock.c (ffffffff811abd84)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff811b5c73)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811c1abd)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_resize_saved_cmdlines
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811cb207)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_stack.c (ffffffff811ccbe5)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/bpf/helpers.c (ffffffff81214f0b)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
```
**Symbols:**

```
ffffffff811caed0-ffffffff811caee6: queued_spin_lock_slowpath.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810385ce)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106d5b4)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff81c45692)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff8110e3e5)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/trace_clock.c (ffffffff811a9644)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff811b3553)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811bf6ca)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_resize_saved_cmdlines
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c88e7)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_stack.c (ffffffff811ca125)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/bpf/helpers.c (ffffffff81216afb)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
```
**Symbols:**

```
ffffffff811c85b0-ffffffff811c85c6: queued_spin_lock_slowpath.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8103a10e)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106e024)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff81c38922)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff8110eef0)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/ring_buffer.c (ffffffff811b5759)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811bdfeb)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c9f1e)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_stack.c (ffffffff811cb4e5)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/bpf/helpers.c (ffffffff8121984b)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
```
**Symbols:**

```
ffffffff811c9850-ffffffff811c9866: queued_spin_lock_slowpath.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8103faaf)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81079844)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff81d57202)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff8112e790)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/ring_buffer.c (ffffffff811df879)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811ee10c)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811f5aae)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_stack.c (ffffffff811f7975)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/bpf/helpers.c (ffffffff8124f971)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:__bpf_spin_lock_irqsave
```
**Symbols:**

```
ffffffff811f52e0-ffffffff811f52f6: queued_spin_lock_slowpath.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81047235)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810885d1)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff8114ec89)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:__raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff8114fb58)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff81180129)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_gp_init
```
```
In kernel/trace/ring_buffer.c (ffffffff8121366d)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff8122645c)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8122f05f)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_stack.c (ffffffff81231532)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/bpf/helpers.c (ffffffff81296be9)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:__bpf_spin_lock_irqsave
```
**Symbols:**

```
ffffffff8122eb20-ffffffff8122eb4f: queued_spin_lock_slowpath.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81051495)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109c084)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/mm/kmmio.c (ffffffff810d200e)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/locking/spinlock.c (ffffffff8117de5d)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:__raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff820d6eb8)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff811ba5fe)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_gp_init
```
```
In kernel/trace/ring_buffer.c (ffffffff8125ce3e)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff812716ff)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8127b0a3)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_stack.c (ffffffff8127dab2)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/bpf/helpers.c (ffffffff812f1b5d)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:__bpf_spin_lock_irqsave
```
**Symbols:**

```
ffffffff8127ab30-ffffffff8127ab5f: queued_spin_lock_slowpath.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810521f5)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109efe4)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/mm/kmmio.c (ffffffff810d547e)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/locking/spinlock.c (ffffffff8118eafd)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:__raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff8215a248)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff811ccf3e)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_gp_init
```
```
In kernel/trace/ring_buffer.c (ffffffff81273e2e)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff81288a0c)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81292bc3)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_stack.c (ffffffff8129a532)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/bpf/helpers.c (ffffffff8131e73d)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:__bpf_spin_lock_irqsave
```
**Symbols:**

```
ffffffff812925a0-ffffffff812925cf: queued_spin_lock_slowpath.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81059415)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810a6464)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/mm/kmmio.c (ffffffff810ddc4e)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/locking/spinlock.c (ffffffff8119d4ad)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:__raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff8223dac8)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff811e192a)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_report_cpu_dead
  - kernel/rcu/tree.c:rcutree_report_cpu_starting
  - kernel/rcu/tree.c:rcu_gp_init
```
```
In kernel/trace/ring_buffer.c (ffffffff8128e457)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff812a3d6e)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop_tr
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812ae6f3)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_stack.c (ffffffff812b5bf2)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/bpf/helpers.c (ffffffff81340b64)
Location: arch/x86/include/asm/qspinlock.h:49
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:__bpf_spin_lock_irqsave
```
**Symbols:**

```
ffffffff812adbe0-ffffffff812adc0f: queued_spin_lock_slowpath.constprop.0 (STB_LOCAL)
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
void queued_spin_lock_slowpath(struct qspinlock *lock, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qspinlock.c (ffff80001016a8e8)
Location: kernel/locking/qspinlock.c:314
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - arch/arm64/kernel/debug-monitors.c:register_kernel_break_hook
  - arch/arm64/kernel/debug-monitors.c:register_user_break_hook
  - arch/arm64/kernel/debug-monitors.c:register_kernel_step_hook
  - arch/arm64/kernel/debug-monitors.c:register_user_step_hook
  - arch/arm64/kernel/debug-monitors.c:unregister_debug_hook
  - arch/arm64/kernel/traps.c:call_undef_hook
  - arch/arm64/kernel/traps.c:unregister_undef_hook
  - arch/arm64/kernel/traps.c:register_undef_hook
  - arch/arm64/kernel/traps.c:die
  - arch/arm64/kernel/insn.c:__aarch64_insn_write
  - arch/arm64/kernel/perf_event.c:armv8pmu_stop
  - arch/arm64/kernel/perf_event.c:armv8pmu_start
  - arch/arm64/kernel/perf_event.c:armv8pmu_disable_event
  - arch/arm64/kernel/perf_event.c:armv8pmu_enable_event
  - arch/arm64/kernel/armv8_deprecated.c:run_all_insn_set_hw_mode
  - arch/arm64/mm/mmu.c:set_swapper_pgd
  - arch/arm64/mm/context.c:check_and_switch_context
  - virt/kvm/kvm_main.c:hardware_disable_all
  - virt/kvm/kvm_main.c:kvm_dying_cpu
  - virt/kvm/kvm_main.c:kvm_starting_cpu
  - virt/kvm/kvm_main.c:kvm_clear_dirty_log_protect
  - virt/kvm/kvm_main.c:kvm_get_dirty_log_protect
  - virt/kvm/kvm_main.c:kvm_create_vm
  - virt/kvm/kvm_main.c:kvm_mmu_notifier_test_young
  - virt/kvm/kvm_main.c:kvm_mmu_notifier_clear_young
  - virt/kvm/kvm_main.c:kvm_mmu_notifier_clear_flush_young
  - virt/kvm/kvm_main.c:kvm_mmu_notifier_invalidate_range_start
  - virt/kvm/kvm_main.c:kvm_mmu_notifier_change_pte
  - virt/kvm/coalesced_mmio.c:coalesced_mmio_write
  - virt/kvm/eventfd.c:kvm_irq_routing_update
  - virt/kvm/eventfd.c:kvm_irqfd_release
  - virt/kvm/eventfd.c:kvm_irqfd
  - virt/kvm/eventfd.c:kvm_irqfd_assign
  - virt/kvm/eventfd.c:irqfd_wakeup
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
  - virt/kvm/arm/mmu.c:kvm_arch_flush_shadow_memslot
  - virt/kvm/arm/mmu.c:kvm_arch_prepare_memory_region
  - virt/kvm/arm/mmu.c:kvm_handle_guest_abort
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:kvm_mmu_wp_memory_region
  - virt/kvm/arm/mmu.c:kvm_phys_addr_ioremap
  - virt/kvm/arm/mmu.c:kvm_free_stage2_pgd
  - virt/kvm/arm/mmu.c:stage2_unmap_vm
  - virt/kvm/arm/mmu.c:stage2_flush_vm
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_map_is_active
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_flush_hwstate
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_flush_hwstate
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_flush_hwstate
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_sync_hwstate
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_sync_hwstate
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_sync_hwstate
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_sync_hwstate
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_sync_hwstate
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_set_owner
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_unmap_phys_irq
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_reset_mapped_irq
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_map_phys_irq
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_inject_irq
  - virt/kvm/arm/vgic/vgic.c:vgic_queue_irq_unlock
  - virt/kvm/arm/vgic/vgic.c:vgic_queue_irq_unlock
  - virt/kvm/arm/vgic/vgic.c:vgic_queue_irq_unlock
  - virt/kvm/arm/vgic/vgic.c:vgic_irq_cmp
  - virt/kvm/arm/vgic/vgic.c:vgic_irq_cmp
  - virt/kvm/arm/vgic/vgic.c:vgic_flush_pending_lpis
  - virt/kvm/arm/vgic/vgic.c:vgic_flush_pending_lpis
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_fold_lr_state
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_lpi_sync_pending_status
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_fold_lr_state
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_write_irq_line_level_info
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_config
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_priority
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_cpending
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_spending
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_read_pending
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_cenable
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_senable
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_group
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_sgipends
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_sgipendc
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_target
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_sgir
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_v3_dispatch_sgi
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_v3_uaccess_write_pending
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_mmio_write_irouter
  - virt/kvm/arm/vgic/vgic-its.c:vgic_enable_lpis
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_inject_cached_translation
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_inject_cached_translation
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_trigger_msi
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_resolve_lpi
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_invalidate_cache
  - virt/kvm/arm/vgic/vgic-its.c:vgic_copy_lpi_list
  - virt/kvm/arm/vgic/vgic-its.c:update_lpi_config
  - virt/kvm/arm/vgic/vgic-debug.c:vgic_debug_show
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:mm_release
  - kernel/fork.c:get_task_mm
  - kernel/fork.c:get_task_exe_file
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:find_user
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:do_sigpending
  - kernel/signal.c:__set_current_blocked
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:force_sigsegv
  - kernel/signal.c:__lock_task_sighand
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:flush_itimer_signals
  - kernel/signal.c:flush_signals
  - kernel/signal.c:calculate_sigpending
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:do_prlimit
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:drain_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/pid.c:disable_pid_allocation
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:free_pid
  - kernel/task_work.c:task_work_run
  - kernel/task_work.c:task_work_cancel
  - kernel/params.c:param_set_charp
  - kernel/params.c:maybe_kfree_parameter
  - kernel/kthread.c:__kthread_cancel_work_sync
  - kernel/kthread.c:__kthread_cancel_work_sync
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread_queue_delayed_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_queue_work
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/kthread.c:__kthread_parkme
  - kernel/nsproxy.c:switch_task_namespaces
  - kernel/notifier.c:atomic_notifier_chain_unregister
  - kernel/notifier.c:atomic_notifier_chain_register
  - kernel/async.c:async_unregister_domain
  - kernel/async.c:async_schedule_node_domain
  - kernel/async.c:async_schedule_node_domain
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:lowest_in_progress
  - kernel/ucount.c:put_ucounts
  - kernel/ucount.c:get_ucounts
  - kernel/ucount.c:get_ucounts
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/sched/core.c:sched_offline_group
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:__balance_callback
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/cputime.c:cputime_adjust
  - kernel/sched/cputime.c:thread_group_cputime
  - kernel/sched/idle.c:dequeue_task_idle
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:rq_online_fair
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:remove_entity_load_avg
  - kernel/sched/fair.c:task_numa_free
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/rt.c:tg_set_rt_bandwidth
  - kernel/sched/rt.c:tg_set_rt_bandwidth
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:dl_clear_root_domain
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:init_dl_bw
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/wait.c:finish_wait
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait_exclusive
  - kernel/sched/wait.c:prepare_to_wait
  - kernel/sched/wait.c:__wake_up_common_lock
  - kernel/sched/wait.c:remove_wait_queue
  - kernel/sched/wait.c:add_wait_queue_exclusive
  - kernel/sched/wait.c:add_wait_queue
  - kernel/sched/swait.c:finish_swait
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:prepare_to_swait_exclusive
  - kernel/sched/swait.c:swake_up_all
  - kernel/sched/swait.c:swake_up_all
  - kernel/sched/swait.c:swake_up_one
  - kernel/sched/completion.c:__wait_for_common
  - kernel/sched/completion.c:__wait_for_common
  - kernel/sched/completion.c:complete_all
  - kernel/sched/completion.c:complete
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_clear
  - kernel/sched/topology.c:rq_attach_root
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/cpufreq_schedutil.c:sugov_work
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
  - kernel/locking/semaphore.c:up
  - kernel/locking/semaphore.c:down_timeout
  - kernel/locking/semaphore.c:down_trylock
  - kernel/locking/semaphore.c:down_killable
  - kernel/locking/semaphore.c:down_interruptible
  - kernel/locking/semaphore.c:down
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
  - kernel/power/suspend.c:s2idle_wake
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:kmsg_dump
  - kernel/printk/printk.c:kmsg_dump_unregister
  - kernel/printk/printk.c:kmsg_dump_register
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
  - kernel/irq/irqdesc.c:actions_show
  - kernel/irq/irqdesc.c:name_show
  - kernel/irq/irqdesc.c:wakeup_show
  - kernel/irq/irqdesc.c:type_show
  - kernel/irq/irqdesc.c:hwirq_show
  - kernel/irq/irqdesc.c:chip_name_show
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:irq_wake_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/manage.c:__synchronize_hardirq
  - kernel/irq/spurious.c:__report_bad_irq
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
  - kernel/irq/chip.c:handle_fasteoi_mask_irq
  - kernel/irq/chip.c:handle_fasteoi_ack_irq
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_gc_set_wake
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_dtor
  - kernel/rcu/sync.c:rcu_sync_exit
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/sync.c:rcu_sync_func
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
  - kernel/rcu/tree.c:sync_rcu_preempt_exp_done_unlocked
  - kernel/rcu/tree.c:rcu_iw_handler
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcutree_offline_cpu
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_force_quiescent_state
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/dma/coherent.c:__dma_release_from_coherent
  - kernel/dma/coherent.c:__dma_alloc_from_coherent
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/kcmp.c:kcmp_epoll_target
  - kernel/kcmp.c:get_file_raw_ptr
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:get_next_timer_interrupt
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:lock_timer_base
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:hrtimer_get_next_event
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:retrigger_next_event
  - kernel/time/hrtimer.c:lock_hrtimer_base
  - kernel/time/timekeeping.c:xtime_update
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - kernel/time/timer_list.c:print_active_timers
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_handle_timer
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/alarmtimer.c:alarmtimer_get_rtcdev
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:__arm64_sys_timer_delete
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:sysfs_show_current_tick_dev
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:tick_offline_cpu
  - kernel/time/clockevents.c:clockevents_register_device
  - kernel/time/clockevents.c:__clockevents_unbind
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_periodic
  - kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull
  - kernel/time/tick-broadcast.c:tick_broadcast_switch_to_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_suspend_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_update_freq
  - kernel/time/tick-sched.c:tick_init_jiffy_update
  - kernel/futex.c:futex_cleanup_begin
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_state
  - kernel/acct.c:acct_collect
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_file_notify
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_task_count
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_hold
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe
  - kernel/cgroup/rstat.c:cgroup_rstat_flush
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_enter_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/cpuset.c:__cpuset_memory_pressure_bump
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_read_u64
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/utsname.c:utsns_get
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_should_run
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_get_tty
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:__audit_getname
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/delayacct.c:__delayacct_blkio_ticks
  - kernel/delayacct.c:__delayacct_add_tsk
  - kernel/delayacct.c:delayacct_end
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/trace/trace_clock.c:trace_clock_global
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_iter_peek
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_events.c:remove_event_file_dir
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_id
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_push
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_push_elem
  - kernel/bpf/queue_stack_maps.c:__stack_map_get
  - kernel/bpf/queue_stack_maps.c:__queue_map_get
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/xskmap.c:xsk_map_try_sock_delete
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:perf_unpin_context
  - kernel/events/core.c:perf_lock_task_context
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:event_function_call
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:vma_has_uprobes
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:__uprobe_unregister
  - kernel/events/uprobes.c:find_uprobe
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_find_next
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:wake_up_page_bit
  - mm/filemap.c:wake_up_page_bit
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/mempool.c:mempool_free
  - mm/mempool.c:mempool_alloc
  - mm/mempool.c:mempool_resize
  - mm/mempool.c:mempool_resize
  - mm/mempool.c:mempool_resize
  - mm/mempool.c:mempool_resize
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:find_lock_task_mm
  - mm/fadvise.c:generic_fadvise
  - mm/fadvise.c:generic_fadvise
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:domain_update_bandwidth
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
  - mm/swap.c:release_pages
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_final
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_getattr
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_free_swap
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_free_inode
  - mm/shmem.c:shmem_reserve_inode
  - mm/util.c:get_cmdline
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/backing-dev.c:bdi_put
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_blkcg_offline
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_congested_get_create
  - mm/backing-dev.c:wb_wakeup_delayed
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_cache_shutdown
  - mm/compaction.c:compact_zone
  - mm/compaction.c:fast_isolate_freepages
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_one_irq
  - mm/list_lru.c:list_lru_walk_one
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
  - mm/workingset.c:shadow_lru_isolate
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/mincore.c:mincore_pte_range
  - mm/mlock.c:user_shm_unlock
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mmap.c:expand_downwards
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:s_start
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:find_vmap_area
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:si_swapinfo
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:has_usable_swap
  - mm/swapfile.c:enable_swap_info
  - mm/swapfile.c:enable_swap_info
  - mm/swapfile.c:enable_swap_info
  - mm/swapfile.c:enable_swap_info
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:scan_swap_map_try_ssd_cluster
  - mm/swapfile.c:swap_discard_work
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swap_slots.c:free_swap_slot
  - mm/frontswap.c:frontswap_curr_pages
  - mm/frontswap.c:frontswap_shrink
  - mm/frontswap.c:frontswap_register_ops
  - mm/frontswap.c:frontswap_register_ops
  - mm/zswap.c:zswap_frontswap_invalidate_area
  - mm/zswap.c:zswap_frontswap_invalidate_page
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_pool_put
  - mm/dmapool.c:dma_pool_free
  - mm/dmapool.c:dma_pool_alloc
  - mm/dmapool.c:dma_pool_alloc
  - mm/dmapool.c:show_pools
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__vma_reservation_common
  - mm/hugetlb.c:__vma_reservation_common
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:alloc_gigantic_page
  - mm/hugetlb.c:alloc_gigantic_page
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_chg
  - mm/hugetlb.c:region_chg
  - mm/hugetlb.c:region_add
  - mm/hugetlb.c:hugepage_put_subpool
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mempolicy_nodemask_intersects
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:mmu_notifier_get_locked
  - mm/mmu_notifier.c:__mmu_notifier_register
  - mm/mmu_notifier.c:__mmu_notifier_release
  - mm/ksm.c:run_store
  - mm/ksm.c:run_store
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/slub.c:validate_store
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:count_partial
  - mm/slub.c:free_debug_processing
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:__migration_entry_wait
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:free_transhuge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
  - mm/memcontrol.c:mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_oom_unregister_event
  - mm/memcontrol.c:mem_cgroup_oom_register_event
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/vmpressure.c:vmpressure
  - mm/vmpressure.c:vmpressure
  - mm/vmpressure.c:vmpressure_work_fn
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/memory-failure.c:memory_failure_work_func
  - mm/memory-failure.c:memory_failure_queue
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/zpool.c:zpool_destroy_pool
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_get_driver
  - mm/zpool.c:zpool_unregister_driver
  - mm/zpool.c:zpool_register_driver
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
  - mm/zbud.c:zbud_alloc
  - mm/zbud.c:zbud_alloc
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
  - mm/balloon_compaction.c:balloon_page_putback
  - mm/balloon_compaction.c:balloon_page_isolate
  - mm/balloon_compaction.c:balloon_page_enqueue
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_list_enqueue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic_pte
  - mm/page_idle.c:page_idle_get_page
  - mm/hmm.c:hmm_range_unregister
  - mm/hmm.c:hmm_range_register
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_invalidate_range_start
  - mm/hmm.c:notifiers_decrement
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/super.c:user_get_super
  - fs/super.c:user_get_super
  - fs/super.c:get_active_super
  - fs/super.c:__get_super_thawed
  - fs/super.c:get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/super.c:generic_shutdown_super
  - fs/super.c:put_super
  - fs/char_dev.c:cdev_purge
  - fs/char_dev.c:cd_forget
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/stat.c:inode_get_bytes
  - fs/stat.c:inode_sub_bytes
  - fs/stat.c:inode_add_bytes
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/pipe.c:fifo_open
  - fs/pipe.c:fifo_open
  - fs/pipe.c:put_pipe_info
  - fs/namei.c:vfs_readlink
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:path_init
  - fs/namei.c:__lookup_slow
  - fs/namei.c:follow_up
  - fs/namei.c:set_root
  - fs/namei.c:inode_permission
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:setfl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:d_add
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_rehash
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_instantiate_new
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:d_set_fallthru
  - fs/dcache.c:d_alloc
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:d_find_any_alias
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:__lock_parent
  - fs/dcache.c:__lock_parent
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
  - fs/dcache.c:take_dentry_name_snapshot
  - fs/inode.c:__wait_on_freeing_inode
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_nowait
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:iunique
  - fs/inode.c:iunique
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:inode_insert5
  - fs/inode.c:discard_new_inode
  - fs/inode.c:unlock_new_inode
  - fs/inode.c:new_inode_pseudo
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict
  - fs/inode.c:evict
  - fs/inode.c:clear_inode
  - fs/inode.c:__remove_inode_hash
  - fs/inode.c:__remove_inode_hash
  - fs/inode.c:__insert_inode_hash
  - fs/inode.c:__insert_inode_hash
  - fs/inode.c:inode_sb_list_add
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
  - fs/file.c:expand_files
  - fs/namespace.c:mntns_get
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:__arm64_sys_open_tree
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:sb_prepare_remount_readonly
  - fs/xattr.c:simple_xattr_list_add
  - fs/xattr.c:simple_xattr_list
  - fs/xattr.c:simple_xattr_set
  - fs/xattr.c:simple_xattr_get
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:simple_release_fs
  - fs/libfs.c:simple_pin_fs
  - fs/libfs.c:simple_pin_fs
  - fs/libfs.c:simple_empty
  - fs/libfs.c:simple_empty
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
  - fs/libfs.c:scan_positives
  - fs/libfs.c:scan_positives
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:inode_wait_for_writeback
  - fs/fs-writeback.c:__inode_wait_for_writeback
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:sb_mark_inode_writeback
  - fs/fs-writeback.c:inode_io_list_del
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
  - fs/pnode.c:propagate_mnt
  - fs/d_path.c:__dentry_path
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/fs_pin.c:pin_kill
  - fs/fs_pin.c:pin_kill
  - fs/fs_pin.c:pin_insert
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__bforget
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:bd_abort_claiming
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_forget
  - fs/block_dev.c:bd_acquire
  - fs/block_dev.c:bd_acquire
  - fs/block_dev.c:nr_blockdev_pages
  - fs/block_dev.c:bdget
  - fs/block_dev.c:bdev_evict_inode
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_bio_end_io
  - fs/direct-io.c:dio_bio_end_aio
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_add_event
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_free_mark
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/notify/mark.c:fsnotify_connector_destroy_workfn
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_poll
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_ioctl
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
  - fs/eventpoll.c:ep_remove
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_poll
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_show
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_poll
  - fs/timerfd.c:timerfd_release
  - fs/timerfd.c:timerfd_release
  - fs/timerfd.c:timerfd_clock_was_set
  - fs/timerfd.c:timerfd_triggered
  - fs/eventfd.c:eventfd_show_fdinfo
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
  - fs/userfaultfd.c:userfaultfd_show_fdinfo
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/aio.c:__arm64_sys_io_cancel
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_cancel
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_complete
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:aio_nr_sub
  - fs/aio.c:free_ioctx_users
  - fs/aio.c:kiocb_set_cancel_fn
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_ring_mremap
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_send_recvmsg
  - fs/io_uring.c:io_cqring_add_event
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:get_unlocked_entry
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/locks.c:locks_start
  - fs/locks.c:show_fd_locks
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:lease_get_mtime
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_locked
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:posix_test_lock
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:locks_insert_global_locks
  - fs/locks.c:locks_move_blocks
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_create
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/fhandle.c:do_handle_open
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:do_get_dqblk
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:unregister_quota_format
  - fs/quota/dquot.c:register_quota_format
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/inode.c:proc_reg_release
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_entry_rundown
  - fs/proc/inode.c:proc_entry_rundown
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/array.c:task_state
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:seq_show
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:sysctl_follow_link
  - fs/proc/proc_sysctl.c:proc_sys_compare
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_net.c:get_proc_task_net
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/kernfs/dir.c:kernfs_get_parent
  - fs/kernfs/dir.c:pr_cont_kernfs_path
  - fs/kernfs/dir.c:pr_cont_kernfs_name
  - fs/kernfs/dir.c:kernfs_path_from_node
  - fs/kernfs/dir.c:kernfs_name
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/sysfs/dir.c:sysfs_remove_dir
  - fs/sysfs/symlink.c:sysfs_delete_link
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/configfs/inode.c:configfs_hash_and_remove
  - fs/configfs/inode.c:configfs_drop_dentry
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_lseek
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_do_depend_item
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
  - fs/dcookies.c:dcookie_unregister
  - fs/dcookies.c:get_dcookie
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:ext4_journal_commit_callback
  - fs/ext4/super.c:ext4_journal_commit_callback
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_file_inode
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
  - fs/jbd2/commit.c:journal_submit_data_buffers
  - fs/jbd2/checkpoint.c:jbd2_journal_destroy_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_seq_info_open
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/squashfs/cache.c:squashfs_cache_put
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_cache_inval_inode
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/fatent.c:fat12_ent_get
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
  - fs/nls/nls_base.c:find_nls
  - fs/nls/nls_base.c:unregister_nls
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_dev_poll
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:flush_bg_queue
  - fs/fuse/dev.c:fuse_queue_forget
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_settime
  - fs/fuse/file.c:fuse_notify_poll_wakeup
  - fs/fuse/file.c:fuse_file_poll
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_async_req_send
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_range_is_writeback
  - fs/fuse/file.c:fuse_prepare_release
  - fs/fuse/file.c:fuse_prepare_release
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_link_write_file
  - fs/fuse/inode.c:fuse_dev_free
  - fs/fuse/inode.c:fuse_dev_install
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:fuse_emit
  - fs/fuse/readdir.c:fuse_emit
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_evict_inode
  - fs/pstore/platform.c:pstore_register
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:freeary
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_poll_file
  - ipc/mqueue.c:mqueue_flush_file
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_get_inode
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:free_ipcs
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_lookup
  - security/keys/key.c:key_payload_reserve
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_start
  - security/selinux/avc.c:avc_compute_av
  - security/selinux/avc.c:avc_compute_av
  - security/selinux/avc.c:avc_ss_reset
  - security/selinux/avc.c:avc_flush
  - security/selinux/hooks.c:selinux_inode_invalidate_secctx
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/ibpkey.c:sel_ib_pkey_flush
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/smack/smack_lsm.c:smack_netlabel
  - security/tomoyo/audit.c:tomoyo_read_log
  - security/tomoyo/audit.c:tomoyo_write_log2
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_answer
  - security/tomoyo/common.c:tomoyo_write_answer
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/secid.c:aa_alloc_secid
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/yama/yama_lsm.c:yama_ptracer_add
  - security/yama/yama_lsm.c:yama_relation_cleanup
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/jitterentropy-kcapi.c:jent_kcapi_random
  - crypto/jitterentropy-kcapi.c:jent_kcapi_cleanup
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:bio_alloc_rescue
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elevator_init_mq
  - block/elevator.c:elv_register
  - block/blk-sysfs.c:queue_max_sectors_store
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:ioc_clear_queue
  - block/blk-ioc.c:ioc_clear_queue
  - block/blk-ioc.c:exit_io_context
  - block/blk-ioc.c:ioc_release_fn
  - block/blk-ioc.c:ioc_release_fn
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_request_bypass_insert
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:flush_busy_ctx
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-stat.c:blk_stat_enable_accounting
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
  - block/genhd.c:disk_check_events
  - block/genhd.c:disk_clear_events
  - block/genhd.c:disk_clear_events
  - block/genhd.c:disk_flush_events
  - block/genhd.c:__disk_unblock_events
  - block/genhd.c:disk_block_events
  - block/genhd.c:get_gendisk
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
  - block/bsg.c:bsg_ioctl
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkcg_can_attach
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkcg_destroy_blkgs
  - block/blk-cgroup.c:blkcg_destroy_blkgs
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkcg_print_blkgs
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_destroy_all
  - block/blk-cgroup.c:blkg_destroy_all
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_async_bio_workfn
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_exit
  - block/blk-iocost.c:ioc_rqos_queue_depth_changed
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
  - block/mq-deadline.c:deadline_dispatch_start
  - block/mq-deadline.c:deadline_write_fifo_start
  - block/mq-deadline.c:deadline_read_fifo_start
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_bio_merge
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
  - block/blk-mq-debugfs.c:ctx_poll_rq_list_start
  - block/blk-mq-debugfs.c:ctx_read_rq_list_start
  - block/blk-mq-debugfs.c:ctx_default_rq_list_start
  - block/blk-mq-debugfs.c:hctx_dispatch_start
  - block/blk-mq-debugfs.c:queue_requeue_list_start
  - block/blk-pm.c:blk_pre_runtime_suspend
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_percpu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/rhashtable.c:rhashtable_walk_stop
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_exit
  - lib/rhashtable.c:rhashtable_walk_enter
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/once.c:__do_once_start
  - lib/genalloc.c:gen_pool_add_owner
  - lib/textsearch.c:textsearch_unregister
  - lib/textsearch.c:textsearch_register
  - lib/percpu_counter.c:percpu_counter_cpu_dead
  - lib/percpu_counter.c:percpu_counter_cpu_dead
  - lib/percpu_counter.c:__percpu_counter_init
  - lib/percpu_counter.c:__percpu_counter_sum
  - lib/percpu_counter.c:percpu_counter_add_batch
  - lib/percpu_counter.c:percpu_counter_set
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_set_type
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_resume
  - drivers/irqchip/irq-sunxi-nmi.c:sunxi_sc_nmi_set_type
  - drivers/irqchip/irq-gic-common.c:gic_configure_irq
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
  - drivers/irqchip/irq-gic-v3-its.c:its_restore_enable
  - drivers/irqchip/irq-gic-v3-its.c:its_save_disable
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_free
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_send_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_free
  - drivers/irqchip/irq-gic-v3-its.c:its_msi_prepare
  - drivers/irqchip/irq-gic-v3-its.c:its_create_device
  - drivers/irqchip/irq-gic-v3-its.c:its_send_single_vcommand
  - drivers/irqchip/irq-gic-v3-its.c:its_send_single_command
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_set_affinity
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_mask
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_unmask
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_irq_handle
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_resume
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_suspend
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_irq_handle
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_mask_and_ack
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_set_type
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irq_mask
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irq_unmask
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irq_set_wake
  - drivers/irqchip/irq-mvebu-gicp.c:gicp_irq_domain_free
  - drivers/irqchip/irq-mvebu-gicp.c:gicp_irq_domain_alloc
  - drivers/irqchip/irq-mvebu-gicp.c:gicp_irq_domain_alloc
  - drivers/irqchip/irq-mvebu-odmi.c:odmi_irq_domain_free
  - drivers/irqchip/irq-mvebu-odmi.c:odmi_irq_domain_alloc
  - drivers/irqchip/irq-mvebu-odmi.c:odmi_irq_domain_alloc
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_unmask_irq
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_mask_irq
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_domain_irq_free
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_domain_irq_alloc
  - drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_domain_alloc
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_mask
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_unmask
  - drivers/bus/hisi_lpc.c:hisi_lpc_target_out
  - drivers/bus/hisi_lpc.c:hisi_lpc_target_in
  - drivers/bus/fsl-mc/mc-sys.c:mc_send_command
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_direction
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_set_config
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_set
  - drivers/pinctrl/pinctrl-rockchip.c:_rockchip_pmx_gpio_set_direction
  - drivers/pinctrl/pinctrl-single.c:pcs_irq_handle
  - drivers/pinctrl/pinctrl-single.c:pcs_set_mux
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_ack
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_unmask
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_mask
  - drivers/pinctrl/actions/pinctrl-owl.c:irq_set_type
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_output
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_input
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_set
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_get
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_free
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_request
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_group_config_set
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pin_config_set
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_set_mux
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_set_type
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_disable
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_enable
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_pin_config_set
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_pin_config_get
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_get_pull
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_set_pull
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_set
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_direction_output
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_direction_input
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_set_type
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_unmask
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_mask
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_config_get
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_config_get
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_config_get
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_get_pull
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_set_pull
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pinmux_enable
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_set_type
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_set_wake
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_unmask
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_mask
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_ack
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_wake
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_type
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_ack
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_clear_unmask
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_mask
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_set
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_direction_output
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_direction_input
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_set
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_set
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinmux_set_mux
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_set
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_set
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_set
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_get
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_get
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_get
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_gpio_set_direction
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_gpio_disable_free
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_gpio_request_enable
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_func_set_mux
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_unmask
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_mask
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_set_type
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_gpio_set
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_request
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_set
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pconf_set
  - drivers/gpio/gpiolib.c:gpiolib_seq_next
  - drivers/gpio/gpiolib.c:gpiolib_seq_start
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_find
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpio-mmio.c:bgpio_dir_out
  - drivers/gpio/gpio-mmio.c:bgpio_dir_in
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple_single_reg
  - drivers/gpio/gpio-mmio.c:bgpio_set_set
  - drivers/gpio/gpio-mmio.c:bgpio_set
  - drivers/gpio/gpio-davinci.c:davinci_direction_out
  - drivers/gpio/gpio-davinci.c:davinci_direction_in
  - drivers/gpio/gpio-mpc8xxx.c:mpc512x_irq_set_type
  - drivers/gpio/gpio-mpc8xxx.c:mpc512x_irq_set_type
  - drivers/gpio/gpio-mpc8xxx.c:mpc512x_irq_set_type
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_irq_set_type
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_irq_set_type
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_irq_mask
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_irq_unmask
  - drivers/gpio/gpio-mpc8xxx.c:ls1028a_gpio_dir_in_init
  - drivers/gpio/gpio-mvebu.c:mvebu_pwm_apply
  - drivers/gpio/gpio-mvebu.c:mvebu_pwm_get_state
  - drivers/gpio/gpio-mvebu.c:mvebu_pwm_free
  - drivers/gpio/gpio-mvebu.c:mvebu_pwm_request
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_level_irq_unmask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_level_irq_mask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_edge_irq_unmask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_edge_irq_mask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_ack
  - drivers/gpio/gpio-pl061.c:pl061_irq_ack
  - drivers/gpio/gpio-pl061.c:pl061_irq_unmask
  - drivers/gpio/gpio-pl061.c:pl061_irq_mask
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
  - drivers/gpio/gpio-pl061.c:pl061_direction_output
  - drivers/gpio/gpio-pl061.c:pl061_direction_input
  - drivers/gpio/gpio-xgene.c:xgene_gpio_dir_out
  - drivers/gpio/gpio-xgene.c:xgene_gpio_dir_in
  - drivers/gpio/gpio-xgene.c:xgene_gpio_set
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_out
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_in
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
  - drivers/gpio/gpio-xilinx.c:xgpio_set
  - drivers/pci/access.c:pci_cfg_access_unlock
  - drivers/pci/access.c:pci_cfg_access_trylock
  - drivers/pci/access.c:pci_cfg_access_lock
  - drivers/pci/access.c:pci_user_write_config_dword
  - drivers/pci/access.c:pci_user_write_config_word
  - drivers/pci/access.c:pci_user_write_config_byte
  - drivers/pci/access.c:pci_user_read_config_dword
  - drivers/pci/access.c:pci_user_read_config_word
  - drivers/pci/access.c:pci_user_read_config_byte
  - drivers/pci/access.c:pci_wait_cfg
  - drivers/pci/access.c:pci_bus_set_ops
  - drivers/pci/access.c:pci_bus_write_config_dword
  - drivers/pci/access.c:pci_bus_write_config_word
  - drivers/pci/access.c:pci_bus_write_config_byte
  - drivers/pci/access.c:pci_bus_read_config_dword
  - drivers/pci/access.c:pci_bus_read_config_word
  - drivers/pci/access.c:pci_bus_read_config_byte
  - drivers/pci/pci.c:resource_alignment_store
  - drivers/pci/pci.c:resource_alignment_show
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_dev_complete_resume
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci-driver.c:pci_unregister_driver
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:remove_id_store
  - drivers/pci/pci-driver.c:pci_add_dynid
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_linkup
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_bar
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msix
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_unmask_leg_irq
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_mask_leg_irq
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_unmask_intx_irq
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_mask_intx_irq
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_unmask
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_mask
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_msi_unmask
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_msi_mask
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/rapidio/rio.c:rio_get_asm
  - drivers/rapidio/rio.c:rio_get_comptag
  - drivers/rapidio/rio.c:rio_map_outb_region
  - drivers/rapidio/rio.c:rio_map_inb_region
  - drivers/rapidio/rio.c:rio_release_inb_pwrite
  - drivers/rapidio/rio.c:rio_request_inb_pwrite
  - drivers/rapidio/rio.c:rio_del_device
  - drivers/rapidio/rio.c:rio_free_net
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/mx3fb.c:sdc_disable_channel
  - drivers/video/fbdev/mx3fb.c:sdc_enable_channel
  - drivers/acpi/osl.c:acpi_os_acquire_lock
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_enter_noirq
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_stopped
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/ec.c:ec_transaction_completed
  - drivers/acpi/ec.c:acpi_ec_enable_event
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/acpi/apei/erst.c:erst_get_record_count
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_sdei_critical_callback
  - drivers/acpi/apei/ghes.c:ghes_sdei_normal_callback
  - drivers/acpi/apei/ghes.c:ghes_notify_sea
  - drivers/acpi/apei/ghes.c:ghes_notify_hed
  - drivers/acpi/apei/ghes.c:ghes_irq_func
  - drivers/acpi/apei/ghes.c:ghes_poll_func
  - drivers/acpi/arm64/iort.c:iort_iommu_msi_get_resv_regions
  - drivers/acpi/arm64/iort.c:iort_iommu_msi_get_resv_regions
  - drivers/acpi/arm64/iort.c:iort_find_domain_token
  - drivers/acpi/arm64/iort.c:iort_deregister_domain_token
  - drivers/acpi/arm64/iort.c:iort_register_domain_token
  - drivers/clk/clk.c:clk_enable_lock
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate
  - drivers/clk/clk-xgene.c:xgene_clk_set_rate
  - drivers/clk/clk-xgene.c:xgene_clk_disable
  - drivers/clk/clk-xgene.c:xgene_clk_enable
  - drivers/clk/clk-xgene.c:xgene_clk_pmd_set_rate
  - drivers/clk/clk-xgene.c:xgene_clk_pmd_recalc_rate
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_clock_set_rate
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_clock_on
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_clock_off
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_divider_on
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_divider_off
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_set_rate
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_on
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_off
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_recalc_rate
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_get_parent
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_set_parent
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_disable
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_enable
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_is_enabled
  - drivers/clk/hisilicon/clkgate-separated.c:clkgate_separated_disable
  - drivers/clk/hisilicon/clkgate-separated.c:clkgate_separated_enable
  - drivers/clk/hisilicon/clkdivider-hi6220.c:hi6220_clkdiv_set_rate
  - drivers/clk/hisilicon/clk-hisi-phase.c:hisi_clk_set_phase
  - drivers/clk/hisilicon/reset.c:hisi_reset_deassert
  - drivers/clk/hisilicon/reset.c:hisi_reset_assert
  - drivers/clk/imx/clk-composite-8m.c:imx8m_clk_composite_divider_set_rate
  - drivers/clk/imx/clk-divider-gate.c:clk_divider_disable
  - drivers/clk/imx/clk-divider-gate.c:clk_divider_gate_set_rate
  - drivers/clk/imx/clk-divider-gate.c:clk_divider_gate_recalc_rate
  - drivers/clk/imx/clk-fixup-div.c:clk_fixup_div_set_rate
  - drivers/clk/imx/clk-fixup-mux.c:clk_fixup_mux_set_parent
  - drivers/clk/imx/clk-gate2.c:clk_gate2_disable_unused
  - drivers/clk/imx/clk-gate2.c:clk_gate2_disable
  - drivers/clk/imx/clk-gate2.c:clk_gate2_enable
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_set_rate
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_disable
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_enable
  - drivers/clk/imx/clk-lpcg-scu.c:clk_lpcg_scu_disable
  - drivers/clk/imx/clk-lpcg-scu.c:clk_lpcg_scu_enable
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_set_parent_setclr_lock
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_set_parent_lock
  - drivers/clk/meson/clk-mpll.c:mpll_set_rate
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_gate_set
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_gate_set
  - drivers/clk/renesas/rcar-gen3-cpg.c:cpg_reg_modify
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_endisable
  - drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_notifier_cb
  - drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_notifier_cb
  - drivers/clk/rockchip/clk-half-divider.c:clk_half_divider_set_rate
  - drivers/clk/rockchip/clk-inverter.c:rockchip_inv_set_phase
  - drivers/clk/rockchip/clk-ddr.c:rockchip_ddrclk_sip_set_rate
  - drivers/clk/rockchip/softrst.c:rockchip_softrst_deassert
  - drivers/clk/rockchip/softrst.c:rockchip_softrst_assert
  - drivers/clk/sunxi/clk-factors.c:clk_factors_set_rate
  - drivers/clk/sunxi/clk-a10-ve.c:sunxi_ve_reset_deassert
  - drivers/clk/sunxi/clk-a10-ve.c:sunxi_ve_reset_assert
  - drivers/clk/sunxi/clk-mod0.c:mmc_set_phase
  - drivers/clk/sunxi/clk-sun4i-display.c:sun4i_a10_display_deassert
  - drivers/clk/sunxi/clk-sun4i-display.c:sun4i_a10_display_assert
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_set_rate
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_set_parent
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_enable
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_disable
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_deassert
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_assert
  - drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_deassert
  - drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_assert
  - drivers/clk/sunxi/clk-sun9i-cpus.c:sun9i_a80_cpus_clk_set_rate
  - drivers/clk/sunxi-ng/ccu_mmc_timing.c:sunxi_ccu_set_mmc_timing_mode
  - drivers/clk/sunxi-ng/ccu_reset.c:ccu_reset_deassert
  - drivers/clk/sunxi-ng/ccu_reset.c:ccu_reset_assert
  - drivers/clk/sunxi-ng/ccu_div.c:ccu_div_set_rate
  - drivers/clk/sunxi-ng/ccu_frac.c:ccu_frac_helper_set_rate
  - drivers/clk/sunxi-ng/ccu_frac.c:ccu_frac_helper_disable
  - drivers/clk/sunxi-ng/ccu_frac.c:ccu_frac_helper_enable
  - drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_helper_set_parent
  - drivers/clk/sunxi-ng/ccu_mult.c:ccu_mult_set_rate
  - drivers/clk/sunxi-ng/ccu_phase.c:ccu_phase_set_phase
  - drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_disable
  - drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_disable
  - drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_enable
  - drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_enable
  - drivers/clk/sunxi-ng/ccu_nk.c:ccu_nk_set_rate
  - drivers/clk/sunxi-ng/ccu_nkm.c:ccu_nkm_set_rate
  - drivers/clk/sunxi-ng/ccu_nkmp.c:ccu_nkmp_set_rate
  - drivers/clk/sunxi-ng/ccu_nm.c:ccu_nm_set_rate
  - drivers/clk/sunxi-ng/ccu_nm.c:ccu_nm_set_rate
  - drivers/clk/sunxi-ng/ccu_mp.c:ccu_mp_set_rate
  - drivers/clk/versatile/clk-sp810.c:clk_sp810_timerclken_set_parent
  - drivers/dma/dmaengine.c:dma_run_dependencies
  - drivers/dma/virt-dma.c:vchan_complete
  - drivers/dma/virt-dma.c:vchan_tx_desc_free
  - drivers/dma/virt-dma.c:vchan_tx_submit
  - drivers/dma/amba-pl08x.c:pl08x_debugfs_show
  - drivers/dma/amba-pl08x.c:pl08x_irq
  - drivers/dma/amba-pl08x.c:pl08x_resume
  - drivers/dma/amba-pl08x.c:pl08x_pause
  - drivers/dma/amba-pl08x.c:pl08x_synchronize
  - drivers/dma/amba-pl08x.c:pl08x_terminate_all
  - drivers/dma/amba-pl08x.c:pl08x_prep_dma_cyclic
  - drivers/dma/amba-pl08x.c:pl08x_prep_slave_sg
  - drivers/dma/amba-pl08x.c:pl08x_prep_dma_memcpy
  - drivers/dma/amba-pl08x.c:pl08x_issue_pending
  - drivers/dma/amba-pl08x.c:pl08x_issue_pending
  - drivers/dma/amba-pl08x.c:pl08x_free_chan_resources
  - drivers/dma/amba-pl08x.c:pl08x_phy_free
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_synchronize
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_terminate_all
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_prep_dma_cyclic
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_prep_slave_sg
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_prep_dma_memcpy
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_issue_pending
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_callback
  - drivers/dma/mv_xor.c:mv_xor_status
  - drivers/dma/mv_xor.c:mv_xor_free_chan_resources
  - drivers/dma/mv_xor.c:mv_xor_prep_dma_xor
  - drivers/dma/mv_xor.c:mv_xor_alloc_chan_resources
  - drivers/dma/mv_xor.c:mv_xor_tx_submit
  - drivers/dma/mv_xor.c:mv_xor_tasklet
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_tasklet
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_issue_pending
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_prep_sw_desc
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_tx_submit
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_handler
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_handler
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_unmap
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_map
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_status
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_ack
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_mask
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_unmask
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:__idmac_terminate_all
  - drivers/dma/ipu/ipu_idmac.c:idmac_pause
  - drivers/dma/ipu/ipu_idmac.c:idmac_issue_pending
  - drivers/dma/ipu/ipu_idmac.c:idmac_prep_slave_sg
  - drivers/dma/ipu/ipu_idmac.c:ipu_gc_tasklet
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:ipu_uninit_channel
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer
  - drivers/soc/fsl/qbman/bman_portal.c:bman_portal_probe
  - drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe
  - drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe
  - drivers/soc/fsl/qbman/bman.c:bman_create_affine_portal
  - drivers/soc/fsl/qbman/qman.c:qman_delete_cgr
  - drivers/soc/fsl/qbman/qman.c:qman_create_cgr
  - drivers/soc/fsl/qbman/qman.c:qm_congestion_task
  - drivers/soc/fsl/qbman/qman.c:qman_destroy_affine_portal
  - drivers/soc/fsl/qbman/qman.c:qman_create_affine_portal
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_write_ctrl_data
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_send_data
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_send_data
  - drivers/soc/qcom/rpmh-rsc.c:tcs_tx_done
  - drivers/soc/qcom/rpmh-rsc.c:tcs_invalidate
  - drivers/soc/qcom/rpmh.c:rpmh_invalidate
  - drivers/soc/qcom/rpmh.c:rpmh_flush
  - drivers/soc/qcom/rpmh.c:rpmh_write_batch
  - drivers/soc/qcom/rpmh.c:__rpmh_write
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/sunxi/sunxi_sram.c:sunxi_sram_release
  - drivers/soc/sunxi/sunxi_sram.c:sunxi_sram_claim
  - drivers/virtio/virtio.c:virtio_device_freeze
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_config_enable
  - drivers/virtio/virtio.c:virtio_config_changed
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_mmio.c:vm_interrupt
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_setup_vq
  - drivers/virtio/virtio_pci_common.c:vp_vring_interrupt
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
  - drivers/virtio/virtio_balloon.c:stats_request
  - drivers/xen/grant-table.c:gnttab_cancel_free_callback
  - drivers/xen/grant-table.c:gnttab_request_free_callback
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/xen/grant-table.c:put_free_entry
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
  - drivers/xen/xenbus/xenbus_xs.c:xs_request_exit
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend_exit
  - drivers/reset/reset-meson.c:meson_reset_level
  - drivers/reset/reset-simple.c:reset_simple_update
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:redirected_tty_write
  - drivers/tty/tty_io.c:start_tty
  - drivers/tty/tty_io.c:stop_tty
  - drivers/tty/tty_io.c:check_tty_count
  - drivers/tty/tty_io.c:tty_add_file
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_ldisc.c:get_ldops
  - drivers/tty/tty_ldisc.c:tty_unregister_ldisc
  - drivers/tty/tty_ldisc.c:tty_register_ldisc
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_wake
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:proc_clear_tty
  - drivers/tty/pty.c:pty_set_termios
  - drivers/tty/pty.c:pty_flush_buffer
  - drivers/tty/pty.c:pty_set_pktmode
  - drivers/tty/pty.c:pty_write
  - drivers/tty/pty.c:pty_close
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:__vt_event_dequeue
  - drivers/tty/vt/vt_ioctl.c:__vt_event_queue
  - drivers/tty/vt/keyboard.c:vt_clr_kbd_mode_bit
  - drivers/tty/vt/keyboard.c:vt_set_kbd_mode_bit
  - drivers/tty/vt/keyboard.c:vt_reset_keyboard
  - drivers/tty/vt/keyboard.c:vt_reset_keyboard
  - drivers/tty/vt/keyboard.c:vt_reset_unicode
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdskbmeta
  - drivers/tty/vt/keyboard.c:vt_do_kdskbmode
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_bh
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_get_leds
  - drivers/tty/vt/keyboard.c:setledstate
  - drivers/tty/vt/keyboard.c:fn_spawn_con
  - drivers/tty/vt/keyboard.c:compute_shiftstate
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_hangup
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_port_destruct
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/hvc/hvc_xen.c:xen_pv_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_tiocmget
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_change_speed
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_update_mctrl
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
  - drivers/tty/serial/8250/8250_core.c:serial_8250_overrun_backoff_work
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial_do_unlink
  - drivers/tty/serial/8250/8250_core.c:serial8250_interrupt
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/tty/serial/8250/8250_pci.c:f815xxa_mem_serial_out
  - drivers/tty/serial/8250/8250_fsl.c:fsl8250_handle_irq
  - drivers/tty/serial/8250/8250_dw.c:dw8250_handle_irq
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_console_write
  - drivers/tty/serial/amba-pl011.c:sbsa_uart_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_disable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_enable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_break_ctl
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_callback
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_chars
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_callback
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_suspend_noirq
  - drivers/tty/serial/imx.c:imx_uart_console_write
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_timeout
  - drivers/tty/serial/imx.c:imx_uart_break_ctl
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_rxint
  - drivers/tty/serial/imx.c:imx_uart_txint
  - drivers/tty/serial/imx.c:imx_uart_rtsint
  - drivers/tty/serial/imx.c:imx_uart_dma_tx_callback
  - drivers/tty/serial/meson_uart.c:meson_serial_port_write
  - drivers/tty/serial/meson_uart.c:meson_uart_set_termios
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_console_write
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_get_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_tx_empty
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_ist
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
  - drivers/tty/serial/msm_serial.c:__msm_console_write
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_tx_dma
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_set_termios
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_break_ctl
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_tx_empty
  - drivers/tty/serial/owl-uart.c:owl_uart_port_write
  - drivers/tty/serial/owl-uart.c:owl_uart_set_termios
  - drivers/tty/serial/owl-uart.c:owl_uart_shutdown
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_tx_empty
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle
  - drivers/char/random.c:invalidate_batched_entropy
  - drivers/char/random.c:invalidate_batched_entropy
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:proc_do_uuid
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:del_random_ready_callback
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:_crng_backtrack_protect
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:mix_pool_bytes
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_close
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
  - drivers/char/virtio_console.c:port_fops_release
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:port_has_data
  - drivers/char/virtio_console.c:reclaim_dma_bufs
  - drivers/char/virtio_console.c:find_port_by_vq
  - drivers/char/virtio_console.c:find_port_by_id
  - drivers/char/virtio_console.c:find_port_by_vtermno
  - drivers/iommu/iommu.c:iommu_ops_from_fwnode
  - drivers/iommu/iommu.c:iommu_device_unregister
  - drivers/iommu/iommu.c:iommu_device_register
  - drivers/iommu/iova.c:free_cpu_cached_iovas
  - drivers/iommu/iova.c:iova_rcache_get
  - drivers/iommu/iova.c:iova_rcache_get
  - drivers/iommu/iova.c:iova_rcache_insert
  - drivers/iommu/iova.c:iova_rcache_insert
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:fq_flush_timeout
  - drivers/iommu/iova.c:__free_iova
  - drivers/iommu/iova.c:find_iova
  - drivers/iommu/iova.c:alloc_iova
  - drivers/iommu/arm-smmu.c:arm_smmu_iova_to_phys_hard
  - drivers/iommu/arm-smmu.c:arm_smmu_tlb_sync_context
  - drivers/iommu/arm-smmu.c:arm_smmu_tlb_sync_global
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_attach_dev
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_detach_dev
  - drivers/iommu/rockchip-iommu.c:rk_iommu_attach_device
  - drivers/iommu/rockchip-iommu.c:rk_iommu_detach_device
  - drivers/iommu/rockchip-iommu.c:rk_iommu_unmap
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
  - drivers/iommu/rockchip-iommu.c:rk_iommu_zap_iova
  - drivers/iommu/rockchip-iommu.c:rk_iommu_iova_to_phys
  - drivers/iommu/qcom_iommu.c:qcom_iommu_iova_to_phys
  - drivers/iommu/qcom_iommu.c:qcom_iommu_unmap
  - drivers/iommu/qcom_iommu.c:qcom_iommu_map
  - drivers/iommu/virtio-iommu.c:viommu_iotlb_sync
  - drivers/iommu/virtio-iommu.c:viommu_iova_to_phys
  - drivers/iommu/virtio-iommu.c:viommu_unmap
  - drivers/iommu/virtio-iommu.c:viommu_map
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/iommu/virtio-iommu.c:viommu_del_mappings
  - drivers/iommu/virtio-iommu.c:viommu_send_req_sync
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:devices_kset_move_last
  - drivers/base/bus.c:bus_sort_breadthfirst
  - drivers/base/dd.c:driver_detach
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/base/devres.c:devres_release_group
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_close_group
  - drivers/base/devres.c:devres_open_group
  - drivers/base/devres.c:devres_release_all
  - drivers/base/devres.c:devres_remove
  - drivers/base/devres.c:devres_get
  - drivers/base/devres.c:devres_find
  - drivers/base/devres.c:devres_add
  - drivers/base/attribute_container.c:attribute_container_unregister
  - drivers/base/swnode.c:software_node_find_by_name
  - drivers/base/swnode.c:software_node_to_swnode
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/base/power/common.c:dev_pm_put_subsys_data
  - drivers/base/power/common.c:dev_pm_get_subsys_data
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_flags
  - drivers/base/power/runtime.c:pm_runtime_drop_link
  - drivers/base/power/runtime.c:pm_runtime_new_link
  - drivers/base/power/runtime.c:__pm_runtime_use_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_set_autosuspend_delay
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:pm_runtime_no_callbacks
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_forbid
  - drivers/base/power/runtime.c:pm_runtime_enable
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_get_if_in_use
  - drivers/base/power/runtime.c:__pm_runtime_resume
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:pm_suspend_timer_fn
  - drivers/base/power/runtime.c:pm_runtime_work
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
  - drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq
  - drivers/base/power/main.c:device_pm_check_callbacks
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_propagate_wakeup_to_parent
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:pm_save_wakeup_count
  - drivers/base/power/wakeup.c:pm_wakeup_pending
  - drivers/base/power/wakeup.c:pm_wakeup_timer_fn
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/base/power/wakeup.c:wakeup_source_add
  - drivers/base/power/wakeup.c:wakeup_source_record
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/domain.c:genpd_free_dev_data
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:genpd_lock_interruptible_spin
  - drivers/base/power/domain.c:genpd_lock_nested_spin
  - drivers/base/power/domain.c:genpd_lock_spin
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:pm_clk_suspend
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
  - drivers/base/firmware_loader/main.c:free_fw_priv
  - drivers/base/regmap/regmap.c:regmap_async_is_done
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:regmap_lock_spinlock
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_attr_do_show_backing_file
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:kick_pending_request_queues
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:xlbd_release_minors
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/ezx-pcap.c:pcap_adc_async
  - drivers/mfd/ezx-pcap.c:pcap_adc_irq
  - drivers/mfd/ezx-pcap.c:pcap_adc_trigger
  - drivers/mfd/ezx-pcap.c:pcap_set_ts_bits
  - drivers/mfd/ezx-pcap.c:ezx_pcap_set_bits
  - drivers/mfd/ezx-pcap.c:ezx_pcap_read
  - drivers/mfd/ezx-pcap.c:ezx_pcap_write
  - drivers/mfd/syscon.c:device_node_get_regmap
  - drivers/mfd/syscon.c:of_syscon_register
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/region_devs.c:nd_region_acquire_lane
  - drivers/nvdimm/badrange.c:badrange_forget
  - drivers/nvdimm/badrange.c:badrange_add
  - drivers/nvdimm/badrange.c:badrange_add
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:alloc_dax
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_cb
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_remove_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_signal
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_file_debug_remove
  - drivers/dma-buf/sync_debug.c:sync_file_debug_add
  - drivers/dma-buf/sync_debug.c:sync_timeline_debug_remove
  - drivers/dma-buf/sync_debug.c:sync_timeline_debug_add
  - drivers/scsi/scsi.c:scsi_device_lookup
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__scsi_iterate_devices
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_try_target_reset
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_eh_inc_host_failed
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_lib.c:sdev_evt_send
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_add_cmd_to_list
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
  - drivers/scsi/scsi_scan.c:scsi_forget_host
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
  - drivers/scsi/scsi_dh.c:__scsi_dh_lookup
  - drivers/scsi/sr.c:sr_kref_release
  - drivers/scsi/sr.c:sr_probe
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:__ata_port_probe
  - drivers/ata/libata-core.c:ata_finalize_port_ops
  - drivers/ata/libata-core.c:ata_dev_init
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_about_to_do
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_error
  - drivers/ata/libata-sff.c:ata_bmdma_post_internal_cmd
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_error_handler
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libahci.c:ahci_single_level_irq_intr
  - drivers/ata/libahci.c:ahci_multi_irqs_intr_hard
  - drivers/ata/libahci.c:ahci_transmit_led_message
  - drivers/ata/libahci.c:ahci_sw_activity_blink
  - drivers/ata/libahci.c:ahci_store_em_buffer
  - drivers/ata/libahci.c:ahci_read_em_buffer
  - drivers/gpu/vga/vgaarb.c:vga_arb_release
  - drivers/gpu/vga/vgaarb.c:vga_arb_open
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
  - drivers/gpu/vga/vgaarb.c:vga_client_register
  - drivers/gpu/vga/vgaarb.c:__vga_set_legacy_decoding
  - drivers/gpu/vga/vgaarb.c:vga_put
  - drivers/gpu/vga/vgaarb.c:vga_tryget
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/spi/spi.c:spi_bus_lock
  - drivers/spi/spi.c:spi_async_locked
  - drivers/spi/spi.c:spi_async
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_split_transfers_maxsize
  - drivers/spi/spi.c:spi_split_transfers_maxsize
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/spi/spi.c:spi_start_queue
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_get_next_queued_message
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
  - drivers/spi/spi.c:spi_statistics_transfers_split_maxsize_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo16_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo15_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo14_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo13_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo12_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo11_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo10_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo9_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo8_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo7_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo6_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo5_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo4_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo3_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo2_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo1_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo0_show
  - drivers/spi/spi.c:spi_statistics_bytes_tx_show
  - drivers/spi/spi.c:spi_statistics_bytes_rx_show
  - drivers/spi/spi.c:spi_statistics_bytes_show
  - drivers/spi/spi.c:spi_statistics_spi_async_show
  - drivers/spi/spi.c:spi_statistics_spi_sync_immediate_show
  - drivers/spi/spi.c:spi_statistics_spi_sync_show
  - drivers/spi/spi.c:spi_statistics_timedout_show
  - drivers/spi/spi.c:spi_statistics_errors_show
  - drivers/spi/spi.c:spi_statistics_transfers_show
  - drivers/spi/spi.c:spi_statistics_messages_show
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/tun.c:tun_flow_flush
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_suspend
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_close
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_hwtstamp
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_time_keep
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_settime
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_gettime
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_adjtime
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_adjfreq
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_start_cyclecounter
  - drivers/net/ethernet/freescale/fman/fman.c:fman_set_port_params
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_nwayreset
  - drivers/net/ethernet/smsc/smc91x.c:smc_open
  - drivers/net/ethernet/smsc/smc91x.c:smc_set_multicast_list
  - drivers/net/ethernet/smsc/smc91x.c:smc_timeout
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_configure
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_configure
  - drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit
  - drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/ethernet/smsc/smc91x.c:smc_shutdown
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:find_compressor
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_compressor
  - drivers/net/ppp/ppp_generic.c:ppp_register_compressor
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_tx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_set_device_state
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hub.c:usb_hub_clear_tt_buffer
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/hcd.c:usb_hcd_synchronize_unlinks
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_link_urb_to_ep
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/urb.c:usb_get_from_anchor
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_unanchor_urb
  - drivers/usb/core/urb.c:usb_anchor_urb
  - drivers/usb/core/message.c:usb_driver_set_configuration
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/driver.c:usb_deregister
  - drivers/usb/core/driver.c:usb_match_dynamic_id
  - drivers/usb/core/driver.c:remove_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:destroy_async_on_interface
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:async_getcompleted
  - drivers/usb/core/devio.c:usbdev_mmap
  - drivers/usb/core/devio.c:usbdev_vm_open
  - drivers/usb/core/devio.c:dec_usb_memory_use_count
  - drivers/usb/phy/phy.c:usb_remove_phy
  - drivers/usb/phy/phy.c:devm_usb_get_phy_by_node
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_reset
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_remove_device
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_silence_controller
  - drivers/usb/host/ehci-hcd.c:ehci_silence_controller
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
  - drivers/usb/host/ehci-hcd.c:set_owner
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ohci-hcd.c:fill_async_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/uhci-hcd.c:uhci_rh_resume
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_fsbr_timeout
  - drivers/usb/host/uhci-hcd.c:uhci_debug_open
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/usb/host/xhci-dbgcap.c:xhci_do_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
  - drivers/usb/host/xhci-dbgtty.c:dbc_port_activate
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_chars_in_buffer
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_write_room
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_flush_chars
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_put_char
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_write
  - drivers/usb/host/xhci-dbgtty.c:dbc_write_complete
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_rx
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_tx
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/input/serio/serio.c:serio_interrupt
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_remove_pending_events
  - drivers/input/serio/serio.c:serio_queue_event
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/serio/serio.c:serio_remove_duplicate_events
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/input.c:__input_unregister_device
  - drivers/input/input.c:input_dev_poweroff
  - drivers/input/input.c:input_dev_freeze
  - drivers/input/input.c:input_dev_resume
  - drivers/input/input.c:input_dev_suspend
  - drivers/input/input.c:input_reset_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_get_keycode
  - drivers/input/input.c:input_inject_event
  - drivers/input/input.c:input_repeat_key
  - drivers/input/ff-core.c:erase_effect
  - drivers/input/ff-core.c:erase_effect
  - drivers/input/ff-core.c:input_ff_upload
  - drivers/input/mousedev.c:mousedev_cleanup
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
  - drivers/input/mousedev.c:mousedev_notify_readers
  - drivers/input/evdev.c:evdev_cleanup
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
  - drivers/input/evdev.c:evdev_handle_get_val
  - drivers/input/evdev.c:evdev_handle_get_val
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/input/keyboard/atkbd.c:atkbd_cleanup
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_destroy_device
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/rtc/interface.c:rtc_handle_legacy_irq
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/rtc/dev.c:rtc_dev_open
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_getalarm
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_setaie
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_alarmirq
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_osc_set_parent
  - drivers/i2c/i2c-dev.c:put_i2c_dev
  - drivers/i2c/i2c-dev.c:i2c_dev_get_by_minor
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/kapi.c:pps_event
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
  - drivers/power/supply/power_supply_core.c:power_supply_changed
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - drivers/thermal/thermal_sysfs.c:reset_store
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:total_trans_show
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_unregister_pretimeout
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_pretimeout
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_unregister_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_notify_pretimeout
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_get
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:unregister_md_cluster_operations
  - drivers/md/md.c:register_md_cluster_operations
  - drivers/md/md.c:unregister_md_personality
  - drivers/md/md.c:register_md_personality
  - drivers/md/md.c:md_seq_next
  - drivers/md/md.c:md_unregister_thread
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:md_attr_store
  - drivers/md/md.c:md_attr_show
  - drivers/md/md.c:max_sync_store
  - drivers/md/md.c:min_sync_store
  - drivers/md/md.c:level_show
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_find
  - drivers/md/md.c:md_flush_request
  - drivers/md/md-bitmap.c:behind_writes_used_show
  - drivers/md/md-bitmap.c:can_clear_show
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_destroy
  - drivers/md/md-bitmap.c:md_bitmap_set_memory_bits
  - drivers/md/md-bitmap.c:md_bitmap_start_sync
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_checkpage
  - drivers/md/dm.c:dm_get_from_kobject
  - drivers/md/dm.c:dm_uevent_add
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_hold
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:event_callback
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:free_minor
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:queue_io
  - drivers/md/dm.c:dm_cancel_deferred_remove
  - drivers/md/dm.c:dm_lock_for_deletion
  - drivers/md/dm.c:dm_blk_close
  - drivers/md/dm.c:dm_blk_open
  - drivers/md/dm-kcopyd.c:do_work
  - drivers/md/dm-kcopyd.c:process_jobs
  - drivers/md/dm-kcopyd.c:process_jobs
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/md/dm-kcopyd.c:complete_io
  - drivers/md/dm-kcopyd.c:push
  - drivers/md/dm-stats.c:dm_kvzalloc
  - drivers/md/dm-stats.c:free_shared_memory
  - drivers/edac/ghes_edac.c:ghes_edac_unregister
  - drivers/edac/ghes_edac.c:ghes_edac_register
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:store_reset
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
  - drivers/cpuidle/driver.c:cpuidle_driver_unref
  - drivers/cpuidle/driver.c:cpuidle_driver_ref
  - drivers/cpuidle/sysfs.c:show_driver_name
  - drivers/cpuidle/sysfs.c:show_current_driver
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_detach_bus
  - drivers/mmc/core/core.c:mmc_detach_bus
  - drivers/mmc/core/core.c:mmc_attach_bus
  - drivers/mmc/core/core.c:mmc_release_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/block.c:mmc_blk_rw_wait_cond
  - drivers/mmc/core/block.c:mmc_blk_mq_req_done
  - drivers/mmc/core/block.c:mmc_blk_mq_req_done
  - drivers/mmc/core/block.c:mmc_blk_mq_post_req
  - drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq
  - drivers/mmc/core/queue.c:mmc_mq_queue_rq
  - drivers/mmc/core/queue.c:mmc_mq_queue_rq
  - drivers/mmc/core/queue.c:mmc_mq_recovery_handler
  - drivers/mmc/core/queue.c:mmc_mq_timed_out
  - drivers/mmc/core/queue.c:mmc_cqe_recovery_notifier
  - drivers/mmc/host/mmci.c:mmci_runtime_resume
  - drivers/mmc/host/mmci.c:mmci_runtime_suspend
  - drivers/mmc/host/mmci.c:mmci_set_ios
  - drivers/mmc/host/mmci.c:mmci_request
  - drivers/mmc/host/mmci.c:mmci_irq
  - drivers/mmc/host/mmci.c:mmci_card_busy
  - drivers/firmware/arm_sdei.c:sdei_device_thaw
  - drivers/firmware/arm_sdei.c:sdei_device_freeze
  - drivers/firmware/arm_sdei.c:sdei_cpuhp_up
  - drivers/firmware/arm_sdei.c:sdei_cpuhp_down
  - drivers/firmware/arm_sdei.c:sdei_event_register
  - drivers/firmware/arm_sdei.c:sdei_event_disable
  - drivers/firmware/arm_sdei.c:sdei_event_enable
  - drivers/firmware/arm_sdei.c:sdei_event_destroy
  - drivers/firmware/arm_sdei.c:sdei_event_find
  - drivers/firmware/memmap.c:do_raw_spin_lock
  - drivers/firmware/ti_sci.c:ti_sci_release_resource
  - drivers/firmware/ti_sci.c:ti_sci_get_free_resource
  - drivers/firmware/arm_scmi/bus.c:scmi_protocol_unregister
  - drivers/firmware/arm_scmi/bus.c:scmi_protocol_register
  - drivers/firmware/arm_scmi/driver.c:scmi_xfer_get_init
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/clocksource/sh_cmt.c:sh_cmt_clocksource_read
  - drivers/clocksource/sh_cmt.c:sh_cmt_stop
  - drivers/clocksource/sh_cmt.c:sh_cmt_start
  - drivers/clocksource/sh_cmt.c:sh_cmt_set_next
  - drivers/clocksource/sh_cmt.c:sh_cmt_start_stop_ch
  - drivers/clocksource/sh_tmu.c:sh_tmu_start_stop_ch
  - drivers/of/base.c:of_update_property
  - drivers/of/base.c:of_remove_property
  - drivers/of/base.c:of_add_property
  - drivers/of/base.c:of_find_node_by_phandle
  - drivers/of/base.c:of_find_matching_node_and_match
  - drivers/of/base.c:of_match_node
  - drivers/of/base.c:of_find_node_with_property
  - drivers/of/base.c:of_find_compatible_node
  - drivers/of/base.c:of_find_node_by_type
  - drivers/of/base.c:of_find_node_by_name
  - drivers/of/base.c:of_find_node_opts_by_path
  - drivers/of/base.c:of_get_next_cpu_node
  - drivers/of/base.c:of_get_next_available_child
  - drivers/of/base.c:of_get_next_child
  - drivers/of/base.c:of_get_next_parent
  - drivers/of/base.c:of_get_parent
  - drivers/of/base.c:of_device_is_available
  - drivers/of/base.c:of_device_is_compatible
  - drivers/of/base.c:of_find_all_nodes
  - drivers/of/base.c:of_find_property
  - drivers/of/base.c:of_populate_phandle_cache
  - drivers/of/base.c:of_free_phandle_cache
  - drivers/of/dynamic.c:__of_changeset_entry_apply
  - drivers/of/dynamic.c:of_detach_node
  - drivers/of/dynamic.c:of_attach_node
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/mailbox/mailbox.c:mbox_request_channel
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/mailbox/mailbox.c:msg_submit
  - drivers/mailbox/pcc.c:pcc_mbox_free_channel
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
  - drivers/mailbox/bcm2835-mailbox.c:bcm2835_last_tx_done
  - drivers/mailbox/bcm2835-mailbox.c:bcm2835_send_data
  - drivers/extcon/extcon.c:extcon_unregister_notifier_all
  - drivers/extcon/extcon.c:extcon_register_notifier_all
  - drivers/extcon/extcon.c:extcon_unregister_notifier
  - drivers/extcon/extcon.c:extcon_register_notifier
  - drivers/extcon/extcon.c:extcon_set_property
  - drivers/extcon/extcon.c:extcon_get_property
  - drivers/extcon/extcon.c:extcon_set_state
  - drivers/extcon/extcon.c:extcon_get_state
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/memory/fsl_ifc.c:check_nand_stat
  - drivers/vme/vme.c:vme_master_free
  - drivers/vme/vme.c:vme_master_request
  - drivers/perf/arm-cci.c:cci_pmu_start
  - drivers/perf/arm-cci.c:cci_pmu_disable
  - drivers/perf/arm-cci.c:cci_pmu_enable
  - drivers/perf/arm-cci.c:pmu_handle_irq
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_xp_dt_config
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_start
  - drivers/perf/qcom_l2_pmu.c:get_l2_indirect_reg
  - drivers/perf/qcom_l2_pmu.c:set_l2_indirect_reg
  - drivers/perf/xgene_pmu.c:xgene_pmu_isr
  - net/socket.c:sock_register
  - net/core/sock.c:release_sock
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_unlink
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:skb_queue_head
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:skb_dequeue
  - net/core/skbuff.c:sock_zerocopy_callback
  - net/core/datagram.c:__sk_queue_drop_skb
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_fetch_counters
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:__dev_remove_pack
  - net/core/dev.c:dev_add_pack
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_mc_sync_multiple
  - net/core/dev_addr_lists.c:dev_mc_sync
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_sync_multiple
  - net/core/dev_addr_lists.c:dev_uc_sync
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
  - net/core/link_watch.c:linkwatch_fire_event
  - net/core/link_watch.c:linkwatch_forget_dev
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
  - net/core/net-sysfs.c:tx_timeout_show
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_pages
  - net/core/skmsg.c:sk_psock_link_pop
  - net/core/netpoll.c:refill_skbs
  - net/core/netpoll.c:queue_process
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_register
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netprio_cgroup.c:update_netprio
  - net/core/netclassid_cgroup.c:update_classid_task
  - net/core/netclassid_cgroup.c:update_classid_sock
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:__sock_map_delete
  - net/core/sock_map.c:sock_map_unref
  - net/core/devlink.c:devlink_trap_report
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:__sk_storage_lookup
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
  - net/core/bpf_sk_storage.c:selem_unlink_sk
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_get_next_proto
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_add
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_output.c:tcp_tsq_handler
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_destroy
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
  - net/ipv4/raw.c:raw_ioctl
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/icmp.c:icmp_global_allow
  - net/ipv4/af_inet.c:inet_register_protosw
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:ip_mc_clear_src
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:ip_fib_check_default
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_if_register_cb
  - net/xfrm/xfrm_policy.c:xfrm_policy_register_afinfo
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_state_register_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_register_km
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_state_walk
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_find_acq_byseq
  - net/xfrm/xfrm_state.c:xfrm_find_acq
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_sad_getinfo
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_inq_len
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_listen
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
  - net/unix/af_unix.c:unix_dgram_peer_wake_disconnect
  - net/unix/af_unix.c:unix_peer_get
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:scan_inflight
  - net/unix/scm.c:unix_notinflight
  - net/unix/scm.c:unix_inflight
  - net/ipv6/af_inet6.c:inet6_register_protosw
  - net/ipv6/anycast.c:ipv6_anycast_cleanup
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_del_acaddr_hash
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_run
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_start
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:fib6_nh_flush_exceptions
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:__ip6_ins_rt
  - net/ipv6/route.c:rt6_uncached_list_add
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
  - net/ipv6/raw.c:rawv6_ioctl
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_timer_handler
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_renew
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:fl_release
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
  - net/ipv6/calipso.c:calipso_cache_invalidate
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:__fanout_set_data_bpf
  - net/packet/af_packet.c:__fanout_link
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
  - net/rfkill/core.c:rfkill_blocked
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_init_sw_state
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_fill_event
  - net/rfkill/input.c:rfkill_start
  - net/rfkill/input.c:rfkill_schedule_global_op
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
  - net/dcb/dcbnl.c:dcb_ieee_getapp_default_prio_mask
  - net/dcb/dcbnl.c:dcb_ieee_getapp_dscp_prio_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_getapp_prio_dscp_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/switchdev/switchdev.c:switchdev_deferred_process
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_stop_dev
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_alloc_request
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_add_package
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_start_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_report_link
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_destruct_skb
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xdp_umem.c:xdp_del_sk_umem
  - net/xdp/xdp_umem.c:xdp_add_sk_umem
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_remove
  - lib/klist.c:klist_put
  - lib/klist.c:klist_release
  - lib/klist.c:klist_add_before
  - lib/klist.c:klist_add_behind
  - lib/klist.c:klist_add_tail
  - lib/klist.c:klist_add_head
  - lib/kobject.c:kobj_ns_drop
  - lib/kobject.c:kobj_ns_initial
  - lib/kobject.c:kobj_ns_netlink
  - lib/kobject.c:kobj_ns_grab_current
  - lib/kobject.c:kobj_ns_current_may_mount
  - lib/kobject.c:kobj_ns_type_register
  - lib/kobject.c:kset_find_obj
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobj_kset_leave
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_clear_mark
  - lib/xarray.c:xa_set_mark
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store
  - lib/xarray.c:xa_erase
  - lib/xarray.c:__xas_nomem
```
**Symbols:**

```
ffff80001016a8e8-ffff80001016ac38: queued_spin_lock_slowpath (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8103568e)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81064e64)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff81a73c00)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff810ff546)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/trace_clock.c (ffffffff8118f074)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff81196d23)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811a4650)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811ab2dd)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff811ac4a5)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/bpf/helpers.c (ffffffff811eb56b)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
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
In arch/x86/kernel/dumpstack.c (ffffffff81024fe1)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81055134)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff81a2fe73)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff810ef736)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/trace_clock.c (ffffffff811821de)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff81189ffd)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff8119763d)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8119e5e6)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff8119f35f)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/bpf/helpers.c (ffffffff811de306)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
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
In arch/x86/kernel/dumpstack.c (ffffffff810354ee)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81065314)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff81ae0010)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff810fc706)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/trace_clock.c (ffffffff8118ce44)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff81194af3)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811a2420)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a90ad)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff811aa275)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/bpf/helpers.c (ffffffff811e933b)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
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
In arch/x86/kernel/dumpstack.c (ffffffff810364ce)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810668f4)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff81aec9c7)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff81107936)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/trace_clock.c (ffffffff8119a984)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff811a2703)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811b01b0)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b6eed)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff811b80b5)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/bpf/helpers.c (ffffffff811f76fb)
Location: arch/x86/include/asm/qspinlock.h:48
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
