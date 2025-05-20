# Function: <code>native_save_fl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int native_save_fl();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81040d22)
Location: arch/x86/include/asm/irqflags.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff810645a0)
Location: arch/x86/include/asm/irqflags.h:11
Inline: False
```
```
In arch/x86/kernel/vsmp_64.c (ffffffff81068779)
Location: arch/x86/include/asm/irqflags.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/vsmp_64.c:vsmp_save_fl
  - arch/x86/kernel/vsmp_64.c:vsmp_irq_disable
  - arch/x86/kernel/vsmp_64.c:vsmp_irq_enable
```
**Symbols:**

```
ffffffff810645a0-ffffffff810645a8: native_save_fl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int native_save_fl();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81040bef)
Location: arch/x86/include/asm/irqflags.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff810641f0)
Location: arch/x86/include/asm/irqflags.h:11
Inline: False
```
```
In arch/x86/kernel/vsmp_64.c (ffffffff810684f9)
Location: arch/x86/include/asm/irqflags.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/vsmp_64.c:vsmp_irq_enable
  - arch/x86/kernel/vsmp_64.c:vsmp_irq_disable
  - arch/x86/kernel/vsmp_64.c:vsmp_save_fl
```
**Symbols:**

```
ffffffff810641f0-ffffffff810641f8: native_save_fl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int native_save_fl();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81040633)
Location: arch/x86/include/asm/irqflags.h:15
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff810676e0)
Location: arch/x86/include/asm/irqflags.h:15
Inline: False
```
```
In arch/x86/kernel/vsmp_64.c (ffffffff8106c179)
Location: arch/x86/include/asm/irqflags.h:15
Inline: True
Inline callers:
  - arch/x86/kernel/vsmp_64.c:vsmp_irq_enable
  - arch/x86/kernel/vsmp_64.c:vsmp_irq_disable
  - arch/x86/kernel/vsmp_64.c:vsmp_save_fl
```
**Symbols:**

```
ffffffff810676e0-ffffffff810676e8: native_save_fl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int native_save_fl();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8103e5c6)
Location: arch/x86/include/asm/irqflags.h:15
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff810669a0)
Location: arch/x86/include/asm/irqflags.h:15
Inline: False
```
```
In arch/x86/kernel/vsmp_64.c (ffffffff8106b589)
Location: arch/x86/include/asm/irqflags.h:15
Inline: True
Inline callers:
  - arch/x86/kernel/vsmp_64.c:vsmp_irq_enable
  - arch/x86/kernel/vsmp_64.c:vsmp_irq_disable
  - arch/x86/kernel/vsmp_64.c:vsmp_save_fl
```
**Symbols:**

```
ffffffff810669a0-ffffffff810669a8: native_save_fl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int native_save_fl();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81041157)
Location: arch/x86/include/asm/irqflags.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106ab60)
Location: arch/x86/include/asm/irqflags.h:16
Inline: False
```
```
In arch/x86/kernel/vsmp_64.c (ffffffff8106fe19)
Location: arch/x86/include/asm/irqflags.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/vsmp_64.c:vsmp_irq_enable
  - arch/x86/kernel/vsmp_64.c:vsmp_irq_disable
  - arch/x86/kernel/vsmp_64.c:vsmp_save_fl
```
**Symbols:**

```
ffffffff8106ab60-ffffffff8106ab68: native_save_fl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long unsigned int native_save_fl();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81042ac6)
Location: arch/x86/include/asm/irqflags.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/vsmp_64.c:vsmp_irq_enable
  - arch/x86/kernel/vsmp_64.c:vsmp_irq_disable
  - arch/x86/kernel/vsmp_64.c:vsmp_save_fl
```
**Symbols:**

```
ffffffff810390c0-ffffffff810390c3: native_save_fl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long unsigned int native_save_fl();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810440e3)
Location: arch/x86/include/asm/irqflags.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff8103a2d0-ffffffff8103a2d3: native_save_fl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long unsigned int native_save_fl();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104666f)
Location: arch/x86/include/asm/irqflags.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff8103c890-ffffffff8103c893: native_save_fl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int native_save_fl();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81046dcf)
Location: arch/x86/include/asm/irqflags.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff8103d050-ffffffff8103d053: native_save_fl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int native_save_fl();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104ac5e)
Location: arch/x86/include/asm/irqflags.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff8103fed0-ffffffff8103fed3: native_save_fl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long unsigned int native_save_fl();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104a10e)
Location: arch/x86/include/asm/irqflags.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff8103fd10-ffffffff8103fd13: native_save_fl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int native_save_fl();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104b9c0)
Location: arch/x86/include/asm/irqflags.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff810416b0-ffffffff810416b3: native_save_fl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int native_save_fl();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810529e2)
Location: arch/x86/include/asm/irqflags.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff81047940-ffffffff81047943: native_save_fl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void native_save_fl();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irqflags.S (ffffffff81f15650)
Location: arch/x86/kernel/irqflags.S
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff81f15650-ffffffff81f15657: native_save_fl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void native_save_fl();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irqflags.S (ffffffff820bcc20)
Location: arch/x86/kernel/irqflags.S
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff820bcc20-ffffffff820bcc27: native_save_fl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void native_save_fl();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irqflags.S (ffffffff8213e5e0)
Location: arch/x86/kernel/irqflags.S
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff8213e5e0-ffffffff8213e5e7: native_save_fl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void native_save_fl();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irqflags.S (ffffffff822205d0)
Location: arch/x86/kernel/irqflags.S
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff822205d0-ffffffff822205d7: native_save_fl (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
long unsigned int native_save_fl();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81046f4f)
Location: arch/x86/include/asm/irqflags.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff8103d1d0-ffffffff8103d1d3: native_save_fl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long unsigned int native_save_fl();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff828891fe)
Location: arch/x86/include/asm/irqflags.h:20
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:do_one_initcall
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_mtrr
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_bp_pat_init
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
  - arch/x86/kernel/apic/apic.c:native_apic_icr_write
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask
  - arch/x86/kernel/ftrace.c:run_sync
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/kgdb.c:kgdb_notify
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
  - arch/x86/mm/init.c:cr4_set_bits
  - arch/x86/mm/pageattr.c:cpa_flush
  - arch/x86/mm/tlb.c:leave_mm
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
  - kernel/params.c:parse_args
  - kernel/params.c:parse_args
  - kernel/kthread.c:kthreadd
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:__schedule_bug
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/cputime.c:vtime_init_idle
  - kernel/sched/idle.c:do_idle
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/debug.c:sched_debug_header
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:kmsg_dump
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:setup_log_buf
  - kernel/irq/handle.c:__handle_irq_event_percpu
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/tree.c:do_nocb_deferred_wakeup_common
  - kernel/rcu/tree.c:rcu_nocb_cb_kthread
  - kernel/rcu/tree.c:rcu_nocb_cb_kthread
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:do_nocb_bypass_wakeup_timer
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:rcu_irq_enter_irqson
  - kernel/rcu/tree.c:rcu_idle_exit
  - kernel/rcu/tree.c:rcu_irq_exit_irqson
  - kernel/dma/mapping.c:dma_free_attrs
  - kernel/time/clockevents.c:clockevents_update_freq
  - kernel/time/tick-oneshot.c:tick_oneshot_mode_active
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_task_switch
  - kernel/smp.c:on_each_cpu_mask
  - kernel/smp.c:on_each_cpu
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:generic_exec_single
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/relay.c:relay_late_setup_files
  - kernel/tsacct.c:acct_update_integrals
  - kernel/trace/trace_clock.c:trace_clock_global
  - kernel/trace/ftrace.c:ftrace_init
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:profile_graph_return
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__trace_note_message
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:perf_lock_task_context
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
  - mm/filemap.c:filemap_fault
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:wb_writeout_inc
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:rotate_reclaimable_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_swapin_page
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/gup.c:__get_user_pages_fast
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:drain_pages_zone
  - mm/page_alloc.c:drain_zone_pages
  - mm/page_alloc.c:__free_pages_ok
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:put_cpu_partial
  - mm/slub.c:put_cpu_partial
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:drain_local_stock
  - mm/memcontrol.c:mod_memcg_obj_state
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:__get_reqs_available
  - fs/aio.c:put_reqs_available
  - fs/io_uring.c:io_poll_wake
  - fs/ext4/page-io.c:ext4_finish_bio
  - security/selinux/avc.c:avc_alloc_node
  - block/blk-core.c:generic_make_request_checks
  - block/blk-exec.c:blk_execute_rq_nowait
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-softirq.c:trigger_softirq
  - lib/random32.c:__prandom_reseed
  - lib/irq_poll.c:irq_poll_complete
  - drivers/acpi/osl.c:acpi_os_create_semaphore
  - drivers/acpi/utils.c:acpi_extract_package
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evgpeblk.c:acpi_os_allocate_zeroed
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/exconfig.c:acpi_os_allocate
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_os_allocate_zeroed
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsnames.c:acpi_os_allocate_zeroed
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsutils.c:acpi_os_allocate_zeroed
  - drivers/acpi/acpica/nsxfeval.c:acpi_os_allocate_zeroed
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
  - drivers/acpi/acpica/utalloc.c:acpi_os_allocate
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate_zeroed
  - drivers/acpi/acpica/utcopy.c:acpi_os_allocate
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utids.c:acpi_os_allocate_zeroed
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_os_allocate_zeroed
  - drivers/acpi/acpica/utosi.c:acpi_os_allocate_zeroed
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/acpi/nfit/core.c:acpi_label_write
  - drivers/clk/clk.c:clk_enable_lock
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_fast_load
  - drivers/char/hpet.c:hpet_alloc
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:__dev_kfree_skb_any
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__netif_schedule
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:queue_process
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tasklet_func
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - lib/dump_stack.c:dump_stack
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
ffffffff8102c860-ffffffff8102c863: native_save_fl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long unsigned int native_save_fl();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81046d8f)
Location: arch/x86/include/asm/irqflags.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff8103d010-ffffffff8103d013: native_save_fl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long unsigned int native_save_fl();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104818f)
Location: arch/x86/include/asm/irqflags.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff8103e0a0-ffffffff8103e0a3: native_save_fl (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>long unsigned int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
