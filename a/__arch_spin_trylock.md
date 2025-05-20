# Function: <code>__arch_spin_trylock</code>

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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/traps.c (c00000000002c89c)
Location: arch/powerpc/include/asm/spinlock.h:66
Inline: True
Inline callers:
  - arch/powerpc/kernel/traps.c:oops_begin
  - arch/powerpc/kernel/traps.c:oops_begin
```
```
In arch/powerpc/kernel/rtas.c (c00000000003f6ec)
Location: arch/powerpc/include/asm/spinlock.h:66
Inline: True
Inline callers:
  - arch/powerpc/kernel/rtas.c:rtas_take_timebase
  - arch/powerpc/kernel/rtas.c:rtas_give_timebase
  - arch/powerpc/kernel/rtas.c:__se_sys_rtas
  - arch/powerpc/kernel/rtas.c:rtas_call
```
```
In arch/powerpc/kvm/book3s_hv_rm_xics.c (c000000000122bcc)
Location: arch/powerpc/include/asm/spinlock.h:66
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:icp_rm_deliver_irq
```
```
In arch/powerpc/kvm/book3s_hv_rm_xive.c (c000000000124c10)
Location: arch/powerpc/include/asm/spinlock.h:66
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_xive.c:xive_rm_h_eoi
```
```
In kernel/locking/spinlock.c (c000000000eea510)
Location: arch/powerpc/include/asm/spinlock.h:66
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/trace/trace_clock.c (c00000000028d5a8)
Location: arch/powerpc/include/asm/spinlock.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (c00000000029e6dc)
Location: arch/powerpc/include/asm/spinlock.h:66
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (c0000000002b0048)
Location: arch/powerpc/include/asm/spinlock.h:66
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
In kernel/trace/trace_sched_wakeup.c (c0000000002bade0)
Location: arch/powerpc/include/asm/spinlock.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (c0000000002bd1cc)
Location: arch/powerpc/include/asm/spinlock.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
```
</details>
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
