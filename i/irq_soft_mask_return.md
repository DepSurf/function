# Function: <code>irq_soft_mask_return</code>

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
In init/main.c (c00000000001019c)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/powerpc/kernel/irq.c (c00000000001b7d8)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - arch/powerpc/kernel/irq.c:force_external_irq_replay
  - arch/powerpc/kernel/irq.c:prep_irq_for_idle_irqsoff
  - arch/powerpc/kernel/irq.c:restore_interrupts
```
```
In arch/powerpc/kernel/process.c (c0000000000217a8)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - arch/powerpc/kernel/process.c:__switch_to
```
```
In arch/powerpc/kernel/idle.c (c0000000000234d4)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - arch/powerpc/kernel/idle.c:arch_cpu_idle
```
```
In arch/powerpc/kernel/time.c (c00000000002bbf0)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - arch/powerpc/kernel/time.c:arch_irq_work_raise
```
```
In arch/powerpc/kernel/traps.c (c00000000002dabc)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - arch/powerpc/kernel/traps.c:_exception
  - arch/powerpc/kernel/traps.c:_exception_pkey
```
```
In arch/powerpc/kernel/rtasd.c (c000000000040748)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
```
```
In arch/powerpc/mm/book3s64/slb.c (c00000000008f324)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/slb.c:preload_new_slb_context
  - arch/powerpc/mm/book3s64/slb.c:slb_setup_new_exec
  - arch/powerpc/mm/book3s64/slb.c:slb_flush_and_restore_bolted
```
```
In arch/powerpc/sysdev/xive/common.c (c0000000000bdfb0)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
```
```
In arch/powerpc/platforms/powernv/opal-call.c (c0000000000c21dc)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-call.c:opal_call
```
```
In arch/powerpc/platforms/powernv/opal-nvram.c (c0000000000c8dac)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-nvram.c:opal_nvram_write
  - arch/powerpc/platforms/powernv/opal-nvram.c:opal_nvram_write
```
```
In arch/powerpc/platforms/powernv/opal-irqchip.c (c0000000000cd1e4)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_shutdown
```
```
In arch/powerpc/platforms/powernv/smp.c (c0000000000cdf8c)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/smp.c:pnv_smp_cpu_kill_self
```
```
In kernel/params.c (c000000000171080)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - kernel/params.c:parse_args
  - kernel/params.c:parse_args
```
```
In kernel/sched/core.c (c000000000ee2fe0)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:__schedule_bug
  - kernel/sched/core.c:migrate_swap_stop
```
```
In kernel/sched/idle.c (c00000000018ee1c)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (c00000000019ad2c)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/rt.c (c0000000001a1f44)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (c0000000001a6974)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/locking/spinlock.c (c000000000ee9f60)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
```
```
In kernel/power/suspend.c (c0000000001c8ad4)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/irq/handle.c (c0000000001d25f4)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/dma/mapping.c (c0000000001f3fd0)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_attrs
```
```
In kernel/smp.c (c0000000002235a0)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/stop_machine.c (c000000000258f14)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/trace/ftrace.c (c000000000292de8)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
```
In kernel/trace/trace.c (c0000000002a7274)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (c0000000002b9494)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (c0000000002baea4)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_hwlat.c (c0000000002bc5f0)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/trace/trace_functions_graph.c (c0000000002bdbcc)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
```
```
In kernel/trace/trace_events.c (c0000000002c54f0)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_syscalls.c (c0000000002cd8b4)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_event_perf.c (c0000000002cdf0c)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/trace_kprobe.c (c0000000002eea10)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/irq_work.c (c0000000002febf8)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
```
```
In kernel/bpf/stackmap.c (c000000000337a30)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/hw_breakpoint.c (c000000000357294)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
```
In mm/slub.c (c00000000042b0ac)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
```
```
In fs/buffer.c (c0000000004dec38)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
```
```
In block/blk-core.c (c000000000775380)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-exec.c (c00000000077e7cc)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq_nowait
```
```
In drivers/tty/hvc/hvsi_lib.c (c00000000091cc1c)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
```
```
In drivers/base/syscore.c (c000000000982f00)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/scsi/scsi_lib.c (c000000000a30db0)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/i2c/i2c-core-base.c (c000000000b94114)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (c000000000b98604)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (c000000000c110b0)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (c000000000c1df00)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In net/core/skbuff.c (c000000000c8bfc4)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/dev.c (c000000000ca4e54)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/netpoll.c (c000000000cfe104)
Location: arch/powerpc/include/asm/hw_irq.h:66
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_skb_on_dev
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
