# Function: <code>raw_atomic_try_cmpxchg_acquire</code>

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
In arch/x86/kernel/dumpstack.c (ffffffff81052191)
Location: include/linux/atomic/atomic-arch-fallback.h:2146
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109efd7)
Location: include/linux/atomic/atomic-arch-fallback.h:2146
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/hpet.c (ffffffff810b7882)
Location: include/linux/atomic/atomic-arch-fallback.h:2146
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:read_hpet
```
```
In arch/x86/mm/kmmio.c (ffffffff810d53e2)
Location: include/linux/atomic/atomic-arch-fallback.h:2146
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/locking/spinlock.c (ffffffff8118ebde)
Location: include/linux/atomic/atomic-arch-fallback.h:2146
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:__raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_trylock
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock_nested
  - kernel/locking/spinlock.c:_raw_write_lock
  - kernel/locking/spinlock.c:__raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qspinlock.c (ffffffff821599c8)
Location: include/linux/atomic/atomic-arch-fallback.h:2146
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/locking/qrwlock.c (ffffffff8215a128)
Location: include/linux/atomic/atomic-arch-fallback.h:2146
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff811cce4d)
Location: include/linux/atomic/atomic-arch-fallback.h:2146
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_gp_init
```
```
In kernel/trace/trace_clock.c (ffffffff81268128)
Location: include/linux/atomic/atomic-arch-fallback.h:2146
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff81273dc8)
Location: include/linux/atomic/atomic-arch-fallback.h:2146
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff81288862)
Location: include/linux/atomic/atomic-arch-fallback.h:2146
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:trace_save_cmdline
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812927b8)
Location: include/linux/atomic/atomic-arch-fallback.h:2146
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff8129a4c1)
Location: include/linux/atomic/atomic-arch-fallback.h:2146
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/rethook.c (ffffffff812deb33)
Location: include/linux/atomic/atomic-arch-fallback.h:2146
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_try_get
```
```
In kernel/bpf/helpers.c (ffffffff8131e709)
Location: include/linux/atomic/atomic-arch-fallback.h:2146
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
In arch/x86/kernel/dumpstack.c (ffffffff810593b1)
Location: include/linux/atomic/atomic-arch-fallback.h:2155
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810a6457)
Location: include/linux/atomic/atomic-arch-fallback.h:2155
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/hpet.c (ffffffff810becc2)
Location: include/linux/atomic/atomic-arch-fallback.h:2155
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:read_hpet
```
```
In arch/x86/mm/kmmio.c (ffffffff810ddbb2)
Location: include/linux/atomic/atomic-arch-fallback.h:2155
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/locking/spinlock.c (ffffffff8119d58e)
Location: include/linux/atomic/atomic-arch-fallback.h:2155
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:__raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_trylock
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock_nested
  - kernel/locking/spinlock.c:_raw_write_lock
  - kernel/locking/spinlock.c:__raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qspinlock.c (ffffffff8223d248)
Location: include/linux/atomic/atomic-arch-fallback.h:2155
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/locking/qrwlock.c (ffffffff8223d9a8)
Location: include/linux/atomic/atomic-arch-fallback.h:2155
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff811e184b)
Location: include/linux/atomic/atomic-arch-fallback.h:2155
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_report_cpu_dead
  - kernel/rcu/tree.c:rcutree_report_cpu_starting
  - kernel/rcu/tree.c:rcu_gp_init
```
```
In kernel/trace/trace_clock.c (ffffffff81282398)
Location: include/linux/atomic/atomic-arch-fallback.h:2155
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff8128e3e6)
Location: include/linux/atomic/atomic-arch-fallback.h:2155
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff812a3bc5)
Location: include/linux/atomic/atomic-arch-fallback.h:2155
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:trace_save_cmdline
  - kernel/trace/trace.c:tracing_stop_tr
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812ade9e)
Location: include/linux/atomic/atomic-arch-fallback.h:2155
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff812b5b81)
Location: include/linux/atomic/atomic-arch-fallback.h:2155
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/bpf/helpers.c (ffffffff81340b30)
Location: include/linux/atomic/atomic-arch-fallback.h:2155
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
