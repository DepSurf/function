# Function: <code>pv_queued_spin_lock_slowpath</code>

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
Location: arch/x86/include/asm/paravirt.h:693
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81052954)
Location: arch/x86/include/asm/paravirt.h:693
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff81824005)
Location: arch/x86/include/asm/paravirt.h:693
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
```
```
In kernel/locking/lglock.c (ffffffff810ca4e5)
Location: arch/x86/include/asm/paravirt.h:693
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
Location: arch/x86/include/asm/paravirt.h:693
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/trace_clock.c (ffffffff8113fe66)
Location: arch/x86/include/asm/paravirt.h:693
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff811464e3)
Location: arch/x86/include/asm/paravirt.h:693
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_start
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
```
```
In kernel/trace/trace.c (ffffffff8114aa8b)
Location: arch/x86/include/asm/paravirt.h:693
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
Location: arch/x86/include/asm/paravirt.h:693
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff81157e71)
Location: arch/x86/include/asm/paravirt.h:693
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
Location: arch/x86/include/asm/paravirt.h:666
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81052a74)
Location: arch/x86/include/asm/paravirt.h:666
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff8189efc0)
Location: arch/x86/include/asm/paravirt.h:666
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/lglock.c (ffffffff810cef16)
Location: arch/x86/include/asm/paravirt.h:666
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
Location: arch/x86/include/asm/paravirt.h:666
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/trace_clock.c (ffffffff811484d6)
Location: arch/x86/include/asm/paravirt.h:666
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff8114f5df)
Location: arch/x86/include/asm/paravirt.h:666
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_start
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff81155870)
Location: arch/x86/include/asm/paravirt.h:666
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
Location: arch/x86/include/asm/paravirt.h:666
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff811626ee)
Location: arch/x86/include/asm/paravirt.h:666
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
Location: arch/x86/include/asm/paravirt.h:655
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81055393)
Location: arch/x86/include/asm/paravirt.h:655
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff818d4480)
Location: arch/x86/include/asm/paravirt.h:655
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff810d7326)
Location: arch/x86/include/asm/paravirt.h:655
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/trace_clock.c (ffffffff81152386)
Location: arch/x86/include/asm/paravirt.h:655
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff81159772)
Location: arch/x86/include/asm/paravirt.h:655
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_start
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff8115fd40)
Location: arch/x86/include/asm/paravirt.h:655
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
Location: arch/x86/include/asm/paravirt.h:655
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff8116da28)
Location: arch/x86/include/asm/paravirt.h:655
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
Location: arch/x86/include/asm/paravirt.h:702
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81054cb6)
Location: arch/x86/include/asm/paravirt.h:702
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff8190b5f0)
Location: arch/x86/include/asm/paravirt.h:702
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff810d6366)
Location: arch/x86/include/asm/paravirt.h:702
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/trace_clock.c (ffffffff81154966)
Location: arch/x86/include/asm/paravirt.h:702
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff8115ef23)
Location: arch/x86/include/asm/paravirt.h:702
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811631d8)
Location: arch/x86/include/asm/paravirt.h:702
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
Location: arch/x86/include/asm/paravirt.h:702
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff81170d87)
Location: arch/x86/include/asm/paravirt.h:702
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In lib/nmi_backtrace.c (ffffffff818efd98)
Location: arch/x86/include/asm/paravirt.h:702
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
Location: arch/x86/include/asm/paravirt.h:666
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81058a76)
Location: arch/x86/include/asm/paravirt.h:666
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff81995760)
Location: arch/x86/include/asm/paravirt.h:666
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff810de318)
Location: arch/x86/include/asm/paravirt.h:666
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/trace_clock.c (ffffffff81161186)
Location: arch/x86/include/asm/paravirt.h:666
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff81169265)
Location: arch/x86/include/asm/paravirt.h:666
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff81170198)
Location: arch/x86/include/asm/paravirt.h:666
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
Location: arch/x86/include/asm/paravirt.h:666
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff8117df47)
Location: arch/x86/include/asm/paravirt.h:666
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In lib/nmi_backtrace.c (ffffffff819761d8)
Location: arch/x86/include/asm/paravirt.h:666
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
Location: arch/x86/include/asm/paravirt.h:671
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8105b996)
Location: arch/x86/include/asm/paravirt.h:671
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff819f1ca0)
Location: arch/x86/include/asm/paravirt.h:671
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff810e69f8)
Location: arch/x86/include/asm/paravirt.h:671
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/trace_clock.c (ffffffff811700b6)
Location: arch/x86/include/asm/paravirt.h:671
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff8117b405)
Location: arch/x86/include/asm/paravirt.h:671
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff8117f918)
Location: arch/x86/include/asm/paravirt.h:671
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
Location: arch/x86/include/asm/paravirt.h:671
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff8118d06a)
Location: arch/x86/include/asm/paravirt.h:671
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
Location: arch/x86/include/asm/paravirt.h:650
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81061614)
Location: arch/x86/include/asm/paravirt.h:650
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff81a2d2ce)
Location: arch/x86/include/asm/paravirt.h:650
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff810f1ff6)
Location: arch/x86/include/asm/paravirt.h:650
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/trace_clock.c (ffffffff8117dc64)
Location: arch/x86/include/asm/paravirt.h:650
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff81185743)
Location: arch/x86/include/asm/paravirt.h:650
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff8118d1f6)
Location: arch/x86/include/asm/paravirt.h:650
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
Location: arch/x86/include/asm/paravirt.h:650
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff8119a9e8)
Location: arch/x86/include/asm/paravirt.h:650
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
Location: arch/x86/include/asm/paravirt.h:651
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81064d04)
Location: arch/x86/include/asm/paravirt.h:651
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff81a9d5b0)
Location: arch/x86/include/asm/paravirt.h:651
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff810fa456)
Location: arch/x86/include/asm/paravirt.h:651
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/trace_clock.c (ffffffff8118ab64)
Location: arch/x86/include/asm/paravirt.h:651
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff81192a83)
Location: arch/x86/include/asm/paravirt.h:651
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811a0600)
Location: arch/x86/include/asm/paravirt.h:651
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
Location: arch/x86/include/asm/paravirt.h:651
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff811a8675)
Location: arch/x86/include/asm/paravirt.h:651
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/bpf/helpers.c (ffffffff811e67fb)
Location: arch/x86/include/asm/paravirt.h:651
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
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81065374)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff81ad4d90)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff81106236)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/trace_clock.c (ffffffff81196a54)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff8119e703)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811ac030)
Location: arch/x86/include/asm/paravirt.h:639
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
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff811b3e85)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/bpf/helpers.c (ffffffff811f2f4b)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
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
In arch/x86/kernel/dumpstack.c (ffffffff8103750e)
Location: arch/x86/include/asm/paravirt.h:653
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106bcd4)
Location: arch/x86/include/asm/paravirt.h:653
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff81bccb32)
Location: arch/x86/include/asm/paravirt.h:653
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff81111265)
Location: arch/x86/include/asm/paravirt.h:653
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/trace_clock.c (ffffffff811abd84)
Location: arch/x86/include/asm/paravirt.h:653
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff811b5c73)
Location: arch/x86/include/asm/paravirt.h:653
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811c1abd)
Location: arch/x86/include/asm/paravirt.h:653
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
Location: arch/x86/include/asm/paravirt.h:653
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff811ccbe5)
Location: arch/x86/include/asm/paravirt.h:653
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/bpf/helpers.c (ffffffff81214f0b)
Location: arch/x86/include/asm/paravirt.h:653
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
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
In arch/x86/kernel/dumpstack.c (ffffffff810385ce)
Location: arch/x86/include/asm/paravirt.h:551
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106d5b4)
Location: arch/x86/include/asm/paravirt.h:551
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff81c45692)
Location: arch/x86/include/asm/paravirt.h:551
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff8110e3e5)
Location: arch/x86/include/asm/paravirt.h:551
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/trace_clock.c (ffffffff811a9644)
Location: arch/x86/include/asm/paravirt.h:551
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff811b3553)
Location: arch/x86/include/asm/paravirt.h:551
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811bf6ca)
Location: arch/x86/include/asm/paravirt.h:551
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
Location: arch/x86/include/asm/paravirt.h:551
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff811ca125)
Location: arch/x86/include/asm/paravirt.h:551
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/bpf/helpers.c (ffffffff81216afb)
Location: arch/x86/include/asm/paravirt.h:551
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
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
In arch/x86/kernel/dumpstack.c (ffffffff8103a10e)
Location: arch/x86/include/asm/paravirt.h:582
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106e024)
Location: arch/x86/include/asm/paravirt.h:582
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff81c38922)
Location: arch/x86/include/asm/paravirt.h:582
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff8110eef0)
Location: arch/x86/include/asm/paravirt.h:582
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/ring_buffer.c (ffffffff811b5759)
Location: arch/x86/include/asm/paravirt.h:582
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811bdfeb)
Location: arch/x86/include/asm/paravirt.h:582
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
Location: arch/x86/include/asm/paravirt.h:582
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff811cb4e5)
Location: arch/x86/include/asm/paravirt.h:582
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/bpf/helpers.c (ffffffff8121984b)
Location: arch/x86/include/asm/paravirt.h:582
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
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
In arch/x86/kernel/dumpstack.c (ffffffff8103faaf)
Location: arch/x86/include/asm/paravirt.h:582
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81079844)
Location: arch/x86/include/asm/paravirt.h:582
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff81d57202)
Location: arch/x86/include/asm/paravirt.h:582
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff8112e790)
Location: arch/x86/include/asm/paravirt.h:582
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/ring_buffer.c (ffffffff811df879)
Location: arch/x86/include/asm/paravirt.h:582
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811ee10c)
Location: arch/x86/include/asm/paravirt.h:582
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
Location: arch/x86/include/asm/paravirt.h:582
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff811f7975)
Location: arch/x86/include/asm/paravirt.h:582
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/bpf/helpers.c (ffffffff8124f971)
Location: arch/x86/include/asm/paravirt.h:582
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:__bpf_spin_lock_irqsave
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
In arch/x86/kernel/dumpstack.c (ffffffff81047235)
Location: arch/x86/include/asm/paravirt.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810885d1)
Location: arch/x86/include/asm/paravirt.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff8114ec89)
Location: arch/x86/include/asm/paravirt.h:588
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:__raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff8114fb58)
Location: arch/x86/include/asm/paravirt.h:588
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff81180129)
Location: arch/x86/include/asm/paravirt.h:588
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_gp_init
```
```
In kernel/trace/ring_buffer.c (ffffffff8121366d)
Location: arch/x86/include/asm/paravirt.h:588
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff8122645c)
Location: arch/x86/include/asm/paravirt.h:588
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
Location: arch/x86/include/asm/paravirt.h:588
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff81231532)
Location: arch/x86/include/asm/paravirt.h:588
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/bpf/helpers.c (ffffffff81296be9)
Location: arch/x86/include/asm/paravirt.h:588
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:__bpf_spin_lock_irqsave
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
In arch/x86/kernel/dumpstack.c (ffffffff81051495)
Location: arch/x86/include/asm/paravirt.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109c084)
Location: arch/x86/include/asm/paravirt.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/mm/kmmio.c (ffffffff810d200e)
Location: arch/x86/include/asm/paravirt.h:588
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/locking/spinlock.c (ffffffff8117de5d)
Location: arch/x86/include/asm/paravirt.h:588
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:__raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff820d6eb8)
Location: arch/x86/include/asm/paravirt.h:588
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff811ba5fe)
Location: arch/x86/include/asm/paravirt.h:588
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_gp_init
```
```
In kernel/trace/ring_buffer.c (ffffffff8125ce3e)
Location: arch/x86/include/asm/paravirt.h:588
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff812716ff)
Location: arch/x86/include/asm/paravirt.h:588
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
Location: arch/x86/include/asm/paravirt.h:588
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff8127dab2)
Location: arch/x86/include/asm/paravirt.h:588
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/bpf/helpers.c (ffffffff812f1b5d)
Location: arch/x86/include/asm/paravirt.h:588
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:__bpf_spin_lock_irqsave
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
In arch/x86/kernel/dumpstack.c (ffffffff810521f5)
Location: arch/x86/include/asm/paravirt.h:583
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109efe4)
Location: arch/x86/include/asm/paravirt.h:583
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/mm/kmmio.c (ffffffff810d547e)
Location: arch/x86/include/asm/paravirt.h:583
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/locking/spinlock.c (ffffffff8118eafd)
Location: arch/x86/include/asm/paravirt.h:583
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:__raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff8215a248)
Location: arch/x86/include/asm/paravirt.h:583
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff811ccf3e)
Location: arch/x86/include/asm/paravirt.h:583
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_gp_init
```
```
In kernel/trace/ring_buffer.c (ffffffff81273e2e)
Location: arch/x86/include/asm/paravirt.h:583
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff81288a0c)
Location: arch/x86/include/asm/paravirt.h:583
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
Location: arch/x86/include/asm/paravirt.h:583
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff8129a532)
Location: arch/x86/include/asm/paravirt.h:583
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/bpf/helpers.c (ffffffff8131e73d)
Location: arch/x86/include/asm/paravirt.h:583
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:__bpf_spin_lock_irqsave
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
In arch/x86/kernel/dumpstack.c (ffffffff81059415)
Location: arch/x86/include/asm/paravirt.h:581
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810a6464)
Location: arch/x86/include/asm/paravirt.h:581
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/mm/kmmio.c (ffffffff810ddc4e)
Location: arch/x86/include/asm/paravirt.h:581
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/locking/spinlock.c (ffffffff8119d4ad)
Location: arch/x86/include/asm/paravirt.h:581
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:__raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff8223dac8)
Location: arch/x86/include/asm/paravirt.h:581
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff811e192a)
Location: arch/x86/include/asm/paravirt.h:581
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_report_cpu_dead
  - kernel/rcu/tree.c:rcutree_report_cpu_starting
  - kernel/rcu/tree.c:rcu_gp_init
```
```
In kernel/trace/ring_buffer.c (ffffffff8128e457)
Location: arch/x86/include/asm/paravirt.h:581
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff812a3d6e)
Location: arch/x86/include/asm/paravirt.h:581
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
Location: arch/x86/include/asm/paravirt.h:581
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff812b5bf2)
Location: arch/x86/include/asm/paravirt.h:581
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/bpf/helpers.c (ffffffff81340b64)
Location: arch/x86/include/asm/paravirt.h:581
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:__bpf_spin_lock_irqsave
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8103568e)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81064e64)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff81a73c00)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff810ff546)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/trace_clock.c (ffffffff8118f074)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff81196d23)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811a4650)
Location: arch/x86/include/asm/paravirt.h:639
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
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff811ac4a5)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/bpf/helpers.c (ffffffff811eb56b)
Location: arch/x86/include/asm/paravirt.h:639
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
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81055134)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff81a2fe73)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff810ef736)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/trace_clock.c (ffffffff811821de)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff81189ffd)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff8119763d)
Location: arch/x86/include/asm/paravirt.h:639
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
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff8119f35f)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/bpf/helpers.c (ffffffff811de306)
Location: arch/x86/include/asm/paravirt.h:639
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
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81065314)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff81ae0010)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff810fc706)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/trace_clock.c (ffffffff8118ce44)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff81194af3)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811a2420)
Location: arch/x86/include/asm/paravirt.h:639
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
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff811aa275)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/bpf/helpers.c (ffffffff811e933b)
Location: arch/x86/include/asm/paravirt.h:639
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
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810668f4)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In kernel/locking/spinlock.c (ffffffff81aec9c7)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qrwlock.c (ffffffff81107936)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/trace/trace_clock.c (ffffffff8119a984)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff811a2703)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811b01b0)
Location: arch/x86/include/asm/paravirt.h:639
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
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff811b80b5)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/bpf/helpers.c (ffffffff811f76fb)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
```
</details>
</li>
</ul>

## Differences
