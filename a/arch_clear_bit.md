# Function: <code>arch_clear_bit</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810047c5)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
```
In arch/x86/events/core.c (ffffffff810060b9)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_assign_events
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009bdc)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_dead
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a2f7)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102659f)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102c380)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102ee43)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
```
```
In arch/x86/kernel/process_64.c (ffffffff8102f15c)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff810312c7)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff81a9cbac)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:exit_thread
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103de44)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f792)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff810418d0)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81043297)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81047c47)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8104821d)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c59b)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104f867)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81058a9e)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105d7e2)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff810610ae)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:release_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:release_perfctr_nmi
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81061989)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a9cd60)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff810644cc)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/mpparse.c (ffffffff828b41af)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:MP_bus_info
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106c93e)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff81076a3e)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/init_64.c (ffffffff81a93c7b)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In arch/x86/mm/tlb.c (ffffffff810878c5)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108be55)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In arch/x86/mm/numa.c (ffffffff8108c3e9)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In arch/x86/platform/efi/quirks.c (ffffffff8109104f)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault
```
```
In arch/x86/platform/efi/efi.c (ffffffff828c118f)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
```
In kernel/fork.c (ffffffff8109843a)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff8109d8e6)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (ffffffff8109e860)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/softirq.c (ffffffff810a1144)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/ptrace.c (ffffffff810a7452)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810aefd3)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/sys.c (ffffffff810b732e)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
```
In kernel/workqueue.c (ffffffff810ba902)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
```
```
In kernel/kthread.c (ffffffff810c2988)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unpark
```
```
In kernel/sched/core.c (ffffffff81a98057)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/idle.c (ffffffff810d5a35)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:call_cpuidle
  - kernel/sched/idle.c:default_idle_call
```
```
In kernel/sched/fair.c (ffffffff810d85c1)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/sched/rt.c (ffffffff810e3f45)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810e5b75)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810ea862)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff810eadac)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
```
```
In kernel/sched/topology.c (ffffffff810ecf6d)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_clear
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/power/snapshot.c (ffffffff811007e5)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
```
```
In kernel/irq/chip.c (ffffffff8110f49f)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/generic-chip.c (ffffffff81110393)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
```
In kernel/irq/affinity.c (ffffffff8111587c)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/irq/matrix.c (ffffffff81116fa2)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_free
  - kernel/irq/matrix.c:irq_matrix_remove_managed
```
```
In kernel/livepatch/transition.c (ffffffff81121ddc)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/profile.c (ffffffff811257e0)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff8113b844)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/kexec_core.c (ffffffff8114e75b)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115c29d)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
```
```
In kernel/cgroup/freezer.c (ffffffff8115e153)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In kernel/cgroup/cpuset.c (ffffffff811647bc)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/pid_namespace.c (ffffffff811678c8)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffffffff81170b49)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/watchdog.c (ffffffff811845f8)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/tracepoint.c (ffffffff8118a9e1)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/trace/trace.c (ffffffff8119c095)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
```
```
In kernel/trace/trace_events.c (ffffffff811b048a)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:trace_event_enable_tgid_record
  - kernel/trace/trace_events.c:trace_event_enable_cmd_record
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b2ad0)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811b682d)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger
```
```
In kernel/bpf/offload.c (ffffffff811f4e98)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/events/core.c (ffffffff811fac08)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In kernel/events/ring_buffer.c (ffffffff8120a47c)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff8120f48f)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/user-return-notifier.c (ffffffff8120f8a5)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
```
```
In kernel/padata.c (ffffffff81210b7a)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:__padata_remove_cpu
  - kernel/padata.c:__padata_remove_cpu
```
```
In mm/filemap.c (ffffffff812177d2)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:wake_up_page_bit
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/oom_kill.c (ffffffff8121cd3e)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/page-writeback.c (ffffffff81221896)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/readahead.c (ffffffff81222677)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
```
```
In mm/swap.c (ffffffff8122462e)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_file
  - mm/swap.c:lru_cache_add_anon
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
```
```
In mm/truncate.c (ffffffff8122566b)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff8122f1cc)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/shmem.c (ffffffff81231ea8)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/vmstat.c (ffffffff8123970c)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/gup.c (ffffffff8124a96b)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
```
```
In mm/memory.c (ffffffff8125063a)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
```
```
In mm/mlock.c (ffffffff8125822b)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
```
```
In mm/rmap.c (ffffffff81264bf5)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/page_alloc.c (ffffffff812728e9)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (ffffffff81275a6b)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff81276685)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/swap_state.c (ffffffff8127707d)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/frontswap.c (ffffffff8127e53d)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/hugetlb.c (ffffffff81288099)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff81289335)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
```
```
In mm/sparse.c (ffffffff8128dd44)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/ksm.c (ffffffff812905ec)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/memory_hotplug.c (ffffffff81a92431)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/migrate.c (ffffffff8129fde6)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812a2423)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:single_hugepage_flag_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
```
```
In mm/khugepaged.c (ffffffff812aad5f)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff812b69a0)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:drain_local_stock
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memory-failure.c (ffffffff812b9448)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffffffff812be179)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:reset_page
  - mm/zsmalloc.c:reset_page
```
```
In mm/userfaultfd.c (ffffffff812c0ce4)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812c1523)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/fs-writeback.c (ffffffff81301fa1)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
```
```
In fs/buffer.c (ffffffff8130f276)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bforget
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
  - fs/buffer.c:unlock_buffer
```
```
In fs/mpage.c (ffffffff813186e0)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/crypto/crypto.c (ffffffff813369ae)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
```
```
In fs/coredump.c (ffffffff8134a3e9)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff8134b68a)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/quota/dquot.c (ffffffff81350ef9)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_decr_space
  - fs/quota/dquot.c:dquot_decr_inodes
  - fs/quota/dquot.c:dquot_release
```
```
In fs/proc/task_mmu.c (ffffffff813586ed)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/proc/base.c (ffffffff8135ca6a)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - fs/proc/base.c:proc_coredump_filter_write
```
```
In fs/ext4/balloc.c (ffffffff81375be2)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
```
```
In fs/ext4/dir.c (ffffffff8137843f)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff81379e2a)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
```
```
In fs/ext4/file.c (ffffffff813851f6)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
```
```
In fs/ext4/fsync.c (ffffffff81386d70)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff813908b0)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff8139c11d)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:__ext4_journalled_invalidatepage
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff8139cf07)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff813a6c08)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/migrate.c (ffffffff813a8839)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/mmp.c (ffffffff813a8958)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813b10ec)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/page-io.c (ffffffff813b2c46)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff813b322c)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - fs/ext4/readpage.c:mpage_end_io
```
```
In fs/ext4/resize.c (ffffffff813b6950)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/ext4/super.c (ffffffff813c6bd5)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffffffff813d3b91)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
```
In fs/jbd2/transaction.c (ffffffff813d821b)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813d8d4b)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/revoke.c (ffffffff813dc579)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff813e163e)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff813e83c8)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
  - fs/hugetlbfs/inode.c:remove_huge_page
```
```
In fs/ecryptfs/mmap.c (ffffffff813fade8)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/fuse/dev.c (ffffffff81408a98)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:request_end
```
```
In fs/fuse/dir.c (ffffffff8140c2a0)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff81410ddf)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_perform_write
```
```
In ipc/util.c (ffffffff8141cfe6)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/keys/gc.c (ffffffff8142ae36)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/tomoyo/common.c (ffffffff8146cc96)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/apparmor/policy_unpack.c (ffffffff81488e0b)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff8149b50f)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814a17e5)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814a26a8)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
```
```
In block/blk-core.c (ffffffff814c9238)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_clear
```
```
In block/blk-mq.c (ffffffff814d7584)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_start_hw_queue
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:flush_busy_ctx
```
```
In block/blk-mq-sched.c (ffffffff814dd16e)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_restart
```
```
In lib/rhashtable.c (ffffffff8150d6af)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff8153983e)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81546938)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8154845b)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff815492b9)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81550c35)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
```
```
In drivers/pwm/sysfs.c (ffffffff81556aff)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:export_store
```
```
In drivers/pci/bus.c (0)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
```
```
In drivers/pci/remove.c (ffffffff8155dad0)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff8158d9ed)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81590684)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff815b3b6d)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/ec.c (ffffffff815c3654)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/hmat/hmat.c (ffffffff828f41b0)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
```
```
In drivers/acpi/battery.c (ffffffff8161b11d)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81635dc1)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_release_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
```
```
In drivers/xen/cpu_hotplug.c (ffffffff8163fcde)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/xen/grant-table.c (ffffffff81641760)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_pages_clear_private
```
```
In drivers/xen/balloon.c (ffffffff81642a75)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/events/events_2l.c (ffffffff81646655)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_bind_to_cpu
```
```
In drivers/xen/events/events_fifo.c (ffffffff8164714b)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
```
In drivers/tty/tty_io.c (ffffffff8166272c)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kclose
```
```
In drivers/tty/n_tty.c (ffffffff81666cfe)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_write_wakeup
```
```
In drivers/tty/tty_ioctl.c (ffffffff816693d1)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
```
```
In drivers/tty/tty_ldisc.c (ffffffff81669bd5)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
```
```
In drivers/tty/tty_port.c (ffffffff8166b7fe)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/pty.c (ffffffff8166cdc0)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_open
  - drivers/tty/pty.c:pty_open
```
```
In drivers/tty/sysrq.c (ffffffff8166eca1)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/vt/keyboard.c (ffffffff81674713)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
```
In drivers/tty/serial/serial_core.c (ffffffff81686c7e)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
```
In drivers/tty/serial/max310x.c (ffffffff816938f1)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff8169796c)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
```
In drivers/char/misc.c (ffffffff8169d728)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_deregister
  - drivers/char/misc.c:misc_register
```
```
In drivers/char/agp/frontend.c (ffffffff816a3a57)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_release
  - drivers/char/agp/frontend.c:agp_release
```
```
In drivers/char/agp/generic.c (ffffffff816a4f7c)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff816abe91)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_release
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816b326d)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/iommu/dmar.c (ffffffff816c3ab5)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_free_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff816c7769)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_detach_iommu
```
```
In drivers/lightnvm/core.c (ffffffff816d3d92)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/base/cacheinfo.c (ffffffff816e2c5a)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff816f1c9a)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8172f75b)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
```
```
In drivers/nvdimm/label.c (ffffffff817383e2)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_alloc_slot
```
```
In drivers/nvdimm/security.c (ffffffff8173e7c3)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/dax/super.c (ffffffff8173edf8)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81750cb3)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff817550d2)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
```
```
In drivers/scsi/sr.c (ffffffff81761eab)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_kref_release
```
```
In drivers/ata/libata-scsi.c (ffffffff81777ff8)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_free_tag
```
```
In drivers/net/tun.c (ffffffff8179c5d6)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_attach
```
```
In drivers/net/xen-netfront.c (ffffffff817ab042)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_create_queues
```
```
In drivers/usb/core/hub.c (ffffffff817b9241)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff817bef4a)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
```
```
In drivers/usb/core/sysfs.c (ffffffff817c921f)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
```
```
In drivers/usb/core/devio.c (ffffffff817c9f1f)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817d895c)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff82b04c23)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff82b04c61)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff82b04cc3)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In drivers/usb/host/xhci.c (ffffffff8180283f)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81816bc8)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
```
In drivers/input/mousedev.c (ffffffff8182abc0)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/rtc/dev.c (ffffffff81837264)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/media/cec/cec-core.c (ffffffff81844e50)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/media/cec/cec-core.c:cec_devnode_release
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8185cfbd)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/watchdog/watchdog_dev.c:watchdog_write
```
```
In drivers/md/md.c (ffffffff8186479a)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_written
```
```
In drivers/md/md-bitmap.c (ffffffff81872530)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
```
```
In drivers/md/dm.c (ffffffff81875b3a)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_queue_flush
  - drivers/md/dm.c:dm_cancel_deferred_remove
```
```
In drivers/md/dm-kcopyd.c (ffffffff81881e51)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81890e6d)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a9d1e8)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In drivers/leds/led-core.c (ffffffff818b1abc)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_stop_software_blink
  - drivers/leds/led-core.c:led_blink_set_oneshot
  - drivers/leds/led-core.c:led_blink_set_oneshot
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/firmware/efi/efi.c (ffffffff8290d559)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
```
In drivers/firmware/efi/memmap.c (ffffffff8290e588)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
```
In drivers/soundwire/bus.c (ffffffff818c10aa)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - drivers/soundwire/bus.c:sdw_delete_slave
```
```
In net/core/sock.c (ffffffff818e13d6)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/stream.c (ffffffff818f0941)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_write_space
```
```
In net/core/dev.c (ffffffff818fa375)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - net/core/dev.c:napi_disable
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
```
```
In net/core/link_watch.c (ffffffff8191f9bc)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/xdp.c (ffffffff819307f0)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
```
```
In net/core/skmsg.c (ffffffff81936f15)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/netpoll.c (ffffffff81937bf9)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/core/gro_cells.c (ffffffff81952888)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81958327)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/sched/cls_api.c (ffffffff81962a43)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
  - net/sched/cls_api.c:__tc_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81967edc)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netlink/genetlink.c (ffffffff8196c284)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_unregister_family
```
```
In net/ipv4/tcp.c (ffffffff8198b26b)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_output.c (ffffffff8199dee5)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfb1d)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819dbbc1)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e1982)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e994e)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (ffffffff819fc018)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/ipv6/ip6mr.c (ffffffff81a443d7)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f628)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81a6e0ba)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
```
```
In net/ncsi/ncsi-manage.c (ffffffff81a70dfd)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
```
In lib/nmi_backtrace.c (ffffffff81a7ba17)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In lib/vsprintf.c (ffffffff81a84740)
Location: arch/x86/include/asm/bitops.h:73
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In arch/x86/entry/common.c (ffffffff81004825)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009fcc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_dead
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a6d7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810265af)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102d45d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:clear_bit
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f753)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/kernel/process_64.c (ffffffff8102fabc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff81031b87)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff81ad43fc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:exit_thread
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e604)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103fec8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff81042050)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff810439f7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81048497)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81048acd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104cf5b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810501e7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105936e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e092)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff8106191e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:release_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:release_perfctr_nmi
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81062219)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81ad45b0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064b4c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/mpparse.c (ffffffff828b7606)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:MP_bus_info
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106e093)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff81077aae)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/init_64.c (ffffffff81acb55b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In arch/x86/mm/tlb.c (ffffffff810885b5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108cac5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In arch/x86/mm/numa.c (ffffffff8108d049)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In arch/x86/platform/efi/quirks.c (ffffffff81091d4f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault
```
```
In arch/x86/platform/efi/efi.c (ffffffff828c7616)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff81099af9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/fork.c (ffffffff8109ea14)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff810a3e22)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (ffffffff810a4e05)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/softirq.c (ffffffff810a7704)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/ptrace.c (ffffffff810ada76)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810b55ea)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/sys.c (ffffffff810bd885)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
```
In kernel/workqueue.c (ffffffff810c0d52)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/kthread.c (ffffffff810c8dc2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unpark
```
```
In kernel/sched/core.c (ffffffff81acf92d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/idle.c (ffffffff810e0045)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:call_cpuidle
  - kernel/sched/idle.c:default_idle_call
```
```
In kernel/sched/fair.c (ffffffff810e2ec1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/sched/rt.c (ffffffff810eebc8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810f0fa5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810f6232)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff810f677c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
```
```
In kernel/sched/topology.c (ffffffff810f8a0d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_clear
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/power/snapshot.c (ffffffff8110cc45)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
```
```
In kernel/irq/chip.c (ffffffff8111b75f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/generic-chip.c (ffffffff8111c5f3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
```
In kernel/irq/affinity.c (ffffffff81121cce)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/irq/matrix.c (ffffffff81123372)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_free
  - kernel/irq/matrix.c:irq_matrix_remove_managed
```
```
In kernel/livepatch/transition.c (ffffffff8112e3fc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/profile.c (ffffffff811317b0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff81147454)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/kexec_core.c (ffffffff8115a46b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116823d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/cgroup/freezer.c (ffffffff81169d49)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In kernel/cgroup/cpuset.c (ffffffff81170611)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/pid_namespace.c (ffffffff81173788)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffffffff8117c9c9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/watchdog.c (ffffffff81190478)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/tracepoint.c (ffffffff811968f1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/trace/trace.c (ffffffff811a7a85)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
```
```
In kernel/trace/trace_events.c (ffffffff811bb95a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:trace_event_enable_tgid_record
  - kernel/trace/trace_events.c:trace_event_enable_cmd_record
```
```
In kernel/trace/trace_syscalls.c (ffffffff811be610)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811c1e6d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger
```
```
In kernel/bpf/offload.c (ffffffff81201ea8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/events/core.c (ffffffff81207cd8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In kernel/events/ring_buffer.c (ffffffff8121775c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff8121cb3f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/user-return-notifier.c (ffffffff8121ced5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/padata.c (ffffffff8121df7a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_remove_cpu
```
```
In mm/filemap.c (ffffffff8122511d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:wake_up_page_bit
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/oom_kill.c (ffffffff8122a71e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/page-writeback.c (ffffffff8122f346)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/readahead.c (ffffffff81230127)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/swap.c (ffffffff812323be)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_file
  - mm/swap.c:lru_cache_add_anon
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
```
```
In mm/truncate.c (ffffffff812334bb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff8123d35c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/shmem.c (ffffffff8123ff68)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/vmstat.c (ffffffff81247a0c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/gup.c (ffffffff81258e3b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
```
```
In mm/memory.c (ffffffff8125ebea)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/mlock.c (ffffffff812666fb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/rmap.c (ffffffff81273485)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/page_alloc.c (ffffffff81281749)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (ffffffff81284a3b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff81286175)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/swap_state.c (ffffffff81286b5d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/frontswap.c (ffffffff8128df9d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/hugetlb.c (ffffffff81297c99)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffffffff81298ec5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/sparse.c (ffffffff8129da43)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/ksm.c (ffffffff812a036c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/memory_hotplug.c (ffffffff812abce4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/migrate.c (ffffffff812b1186)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812b37de)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:single_hugepage_flag_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
```
```
In mm/khugepaged.c (ffffffff812bc330)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff812c8870)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:drain_local_stock
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memory-failure.c (ffffffff812cb338)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffffffff812d0069)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:reset_page
  - mm/zsmalloc.c:reset_page
```
```
In mm/userfaultfd.c (ffffffff812d2c3c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812d3453)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/fs-writeback.c (ffffffff813150a1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
```
```
In fs/buffer.c (ffffffff8132138d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bforget
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
  - fs/buffer.c:unlock_buffer
```
```
In fs/mpage.c (ffffffff8132b53e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/crypto/crypto.c (ffffffff8134a52e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/coredump.c (ffffffff81362689)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff8136394a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/quota/dquot.c (ffffffff81369279)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_decr_space
  - fs/quota/dquot.c:dquot_decr_inodes
  - fs/quota/dquot.c:dquot_release
```
```
In fs/proc/task_mmu.c (ffffffff8137093d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/proc/base.c (ffffffff8137529a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/proc/base.c:proc_coredump_filter_write
```
```
In fs/ext4/balloc.c (ffffffff8138de52)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/ext4/dir.c (ffffffff81390804)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8139234a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/ext4/extents_status.c (ffffffff8139cfca)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
```
```
In fs/ext4/file.c (ffffffff8139dc96)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/ext4/fsync.c (ffffffff8139f7c0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff813a9310)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff813b4c2d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:__ext4_journalled_invalidatepage
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff813b5987)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff813bfa8b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/migrate.c (ffffffff813c173f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/mmp.c (ffffffff813c1868)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813c9f11)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/page-io.c (ffffffff813cbcb5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff813cc2a6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/ext4/resize.c (ffffffff813cf870)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/ext4/super.c (ffffffff813dff95)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffffffff813ed271)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
```
In fs/ext4/verity.c (ffffffff813ef398)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In fs/jbd2/transaction.c (ffffffff813f22fb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813f2d3b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/revoke.c (ffffffff813f65c9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff813fb68e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff81402468)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
  - fs/hugetlbfs/inode.c:remove_huge_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81414cb8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/fuse/dev.c (ffffffff8142039e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/dir.c (ffffffff81425b3d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff8142a9e5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_perform_write
```
```
In ipc/util.c (ffffffff81436e36)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/keys/gc.c (ffffffff81444b86)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/tomoyo/common.c (ffffffff81486a76)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/apparmor/policy_unpack.c (ffffffff814a2cbb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff814b574f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814bc285)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814bd378)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In block/blk-core.c (ffffffff814e2418)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_clear
```
```
In block/blk-mq.c (ffffffff814f0904)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_start_hw_queue
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:flush_busy_ctx
```
```
In block/blk-mq-sched.c (ffffffff814f65de)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_restart
```
```
In lib/rhashtable.c (ffffffff8152b4ff)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff8155a65e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81567738)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81569201)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_init_irq_valid_mask
```
```
In drivers/gpio/gpiolib.c (ffffffff8156a195)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff815720d5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
```
```
In drivers/pwm/sysfs.c (ffffffff8157811f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:export_store
```
```
In drivers/pci/bus.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/pci/remove.c (ffffffff8157eb40)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff815af60d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815b23b4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff815d4dad)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/ec.c (ffffffff815e4894)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/hmat/hmat.c (ffffffff8163af75)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
```
```
In drivers/acpi/battery.c (ffffffff8163cb8d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81657ae1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_release_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
```
```
In drivers/xen/cpu_hotplug.c (ffffffff8166229e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/xen/grant-table.c (ffffffff81662900)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_pages_clear_private
```
```
In drivers/xen/balloon.c (ffffffff8166501d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/events/events_2l.c (ffffffff81668af5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_bind_to_cpu
```
```
In drivers/xen/events/events_fifo.c (ffffffff816695eb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
```
In drivers/tty/tty_io.c (ffffffff81684d9c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kclose
```
```
In drivers/tty/n_tty.c (ffffffff8168907f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_write_wakeup
```
```
In drivers/tty/tty_ioctl.c (ffffffff8168bb21)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
```
```
In drivers/tty/tty_ldisc.c (ffffffff8168c305)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
```
```
In drivers/tty/tty_port.c (ffffffff8168de9e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/pty.c (ffffffff8168f430)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_open
  - drivers/tty/pty.c:pty_open
```
```
In drivers/tty/sysrq.c (ffffffff816912b1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/vt/keyboard.c (ffffffff81696e73)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
```
In drivers/tty/serial/serial_core.c (ffffffff816a938e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
```
In drivers/tty/serial/max310x.c (ffffffff816b6491)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff816ba4fc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
```
In drivers/char/misc.c (ffffffff816c04c4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_deregister
  - drivers/char/misc.c:misc_register
```
```
In drivers/char/agp/frontend.c (ffffffff816c67e7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_release
  - drivers/char/agp/frontend.c:agp_release
```
```
In drivers/char/agp/generic.c (ffffffff816c7cac)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff816cec11)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_release
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816d5f4d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/iommu/dmar.c (ffffffff816e6a05)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_free_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff816ea6d9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_detach_iommu
```
```
In drivers/lightnvm/core.c (ffffffff816f7c64)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/base/cacheinfo.c (ffffffff81706e0a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff8171641a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81753c17)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
```
```
In drivers/nvdimm/label.c (ffffffff8175c0b2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_alloc_slot
```
```
In drivers/nvdimm/security.c (ffffffff81761e05)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/dax/super.c (ffffffff81762fd8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81774f02)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81779352)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
```
```
In drivers/scsi/sr.c (ffffffff81785e9b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_kref_release
```
```
In drivers/ata/libata-scsi.c (ffffffff8179bf38)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_free_tag
```
```
In drivers/net/tun.c (ffffffff817c0086)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_attach
```
```
In drivers/net/xen-netfront.c (ffffffff817cea82)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_create_queues
```
```
In drivers/usb/core/hub.c (ffffffff817e9a91)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff817ef8ca)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
```
```
In drivers/usb/core/sysfs.c (ffffffff817f9d5f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
```
```
In drivers/usb/core/devio.c (ffffffff817faa3f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818097ec)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff82b13b9b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff82b13bd9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff82b13c3b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In drivers/usb/host/xhci.c (ffffffff8183373f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81847ef8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
```
In drivers/input/mousedev.c (ffffffff8185c550)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/rtc/dev.c (ffffffff81868bd4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/media/cec/cec-core.c (ffffffff818767b0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/media/cec/cec-core.c:cec_devnode_release
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8188ecef)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/watchdog/watchdog_dev.c:watchdog_write
```
```
In drivers/md/md.c (ffffffff818964da)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_written
```
```
In drivers/md/md-bitmap.c (ffffffff818a4330)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
```
```
In drivers/md/dm.c (ffffffff818a792a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_queue_flush
  - drivers/md/dm.c:dm_cancel_deferred_remove
```
```
In drivers/md/dm-kcopyd.c (ffffffff818b3cf1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818c2f4d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In drivers/cpuidle/poll_state.c (ffffffff81ad49f0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In drivers/leds/led-core.c (ffffffff818e3f4c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_stop_software_blink
  - drivers/leds/led-core.c:led_blink_set_oneshot
  - drivers/leds/led-core.c:led_blink_set_oneshot
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/firmware/efi/efi.c (ffffffff829170e6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
```
In drivers/firmware/efi/memmap.c (ffffffff82917f63)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
```
In net/core/sock.c (ffffffff81913596)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/stream.c (ffffffff81922893)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_write_space
```
```
In net/core/dev.c (ffffffff8192c4b5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/dev.c:napi_disable
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
```
```
In net/core/link_watch.c (ffffffff81951bfc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/xdp.c (ffffffff81962d03)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81963f3f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/skmsg.c (ffffffff81969e1e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/netpoll.c (ffffffff8196aab9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/core/gro_cells.c (ffffffff81988bd8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff8198e7d7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/netlink/af_netlink.c (ffffffff8199e97c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netlink/genetlink.c (ffffffff819a2c34)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_unregister_family
```
```
In net/ipv4/tcp.c (ffffffff819c1aee)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_output.c (ffffffff819d49a5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/ipv4/inet_fragment.c (ffffffff81a066ad)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a12af1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a1898f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a21676)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (ffffffff81a32ca8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/ipv6/ip6mr.c (ffffffff81a7afc7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a862b8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81aa4a8a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
```
```
In net/ncsi/ncsi-manage.c (ffffffff81aa761c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
```
In lib/nmi_backtrace.c (ffffffff81ab2d77)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In lib/vsprintf.c (ffffffff81abb9a4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In arch/x86/entry/common.c (ffffffff81005181)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/entry/common.c:__prepare_exit_to_usermode
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
```
In arch/x86/events/amd/uncore.c (ffffffff8100b1aa)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_dead
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100bb23)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102920f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102f56d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:clear_bit
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81031bc3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/kernel/process_64.c (ffffffff810322f7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__set_personality_ia32
  - arch/x86/kernel/process_64.c:__set_personality_x32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff810343bf)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:handle_debug
```
```
In arch/x86/kernel/ioport.c (ffffffff81036f8f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81bcc4f1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8104177d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81043152)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff81044bac)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81047297)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:set_task_blockstep
  - arch/x86/kernel/step.c:enable_single_step
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104c037)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8104cbfd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81052476)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_apply_quirks
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810546bd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105e588)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81063df2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff81067405)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:release_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:release_perfctr_nmi
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff810681c9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81068ad2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106b4a4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/mpparse.c (ffffffff82cdc289)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:MP_bus_info
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075543)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff8107ed80)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/init_64.c (ffffffff81bc3a5d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In arch/x86/mm/tlb.c (ffffffff8108afe8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093ced)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/mm/numa.c (ffffffff81094689)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In arch/x86/platform/efi/quirks.c (ffffffff810975ff)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault
```
```
In arch/x86/platform/efi/efi.c (ffffffff81097800)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109ebdc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_cleanup_mask
```
```
In kernel/fork.c (ffffffff810a7139)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/cpu.c (ffffffff810aaec3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (ffffffff810ac09c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
```
```
In kernel/softirq.c (ffffffff810aee14)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/ptrace.c (ffffffff810b5496)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810be2a8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/sys.c (ffffffff810c4d11)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/workqueue.c (ffffffff810c84ba)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
```
```
In kernel/kthread.c (ffffffff810d0832)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unpark
```
```
In kernel/sched/core.c (ffffffff81bc83a6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/idle.c (ffffffff810e848f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:default_idle_call
```
```
In kernel/sched/fair.c (ffffffff810f64eb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_exit_idle
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/sched/rt.c (ffffffff810f8bfc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810fa3f8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810ffb82)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
  - kernel/sched/cpupri.c:cpupri_find_fitness
```
```
In kernel/sched/cpudeadline.c (ffffffff8110010c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
```
```
In kernel/sched/topology.c (ffffffff811028bd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_clear
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/power/snapshot.c (ffffffff811173c5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
```
```
In kernel/irq/resend.c (ffffffff81126112)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/resend.c:resend_irqs
```
```
In kernel/irq/chip.c (ffffffff81127a0f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/generic-chip.c (ffffffff81128f58)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
```
In kernel/irq/affinity.c (ffffffff8112df9f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/irq/matrix.c (ffffffff8112f9c2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_free
  - kernel/irq/matrix.c:irq_matrix_remove_managed
```
```
In kernel/livepatch/transition.c (ffffffff8113ccef)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/profile.c (ffffffff81140b21)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff811575c4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/kexec_core.c (ffffffff8116b23b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811799ad)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/cgroup/freezer.c (ffffffff8117b8b3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/cgroup/cpuset.c (ffffffff81181961)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:cpuset_update_task_spread_flag
  - kernel/cgroup/cpuset.c:cpuset_update_task_spread_flag
```
```
In kernel/pid_namespace.c (ffffffff811856a8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffffffff8118f5dc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/watchdog.c (ffffffff811a4ff0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/tracepoint.c (ffffffff811abc21)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/trace/trace.c (ffffffff811bfdf6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
```
```
In kernel/trace/trace_events.c (ffffffff811d4bc1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:trace_event_enable_tgid_record
  - kernel/trace/trace_events.c:trace_event_enable_cmd_record
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d7ff1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811dc2f2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_count_trigger
  - kernel/trace/trace_events_trigger.c:update_cond_flag
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/bpf/offload.c (ffffffff8122936e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/events/core.c (ffffffff81230a28)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In kernel/events/ring_buffer.c (ffffffff81242fbc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:__rb_free_aux
```
```
In kernel/events/uprobes.c (ffffffff81248ecf)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/user-return-notifier.c (ffffffff81249255)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/filemap.c (ffffffff81252fb4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:page_endio
  - mm/filemap.c:end_page_writeback
  - mm/filemap.c:wake_up_page_bit
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/oom_kill.c (ffffffff8125752e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/page-writeback.c (ffffffff8125c3f6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/readahead.c (ffffffff8125d367)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/swap.c (ffffffff8125f480)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
```
```
In mm/truncate.c (ffffffff81260c9b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff81265922)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:shrink_slab_memcg
```
```
In mm/shmem.c (ffffffff8126e6be)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
```
```
In mm/vmstat.c (ffffffff81275bf6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/gup.c (ffffffff81287bc5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
```
```
In mm/memory.c (ffffffff81291b1b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:copy_one_pte
```
```
In mm/mlock.c (ffffffff812967cb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/rmap.c (ffffffff812a42b5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/page_alloc.c (ffffffff812b3c33)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (ffffffff812b6c28)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff812b847f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/swap_state.c (ffffffff812b90de)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/frontswap.c (ffffffff812c0c16)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/hugetlb.c (ffffffff812cb359)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffffffff812cd014)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/sparse.c (ffffffff812d16d7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/ksm.c (ffffffff812d6bfe)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/memory_hotplug.c (ffffffff812e05e4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:node_states_clear_node
  - mm/memory_hotplug.c:node_states_clear_node
  - mm/memory_hotplug.c:node_states_clear_node
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:put_page_bootmem
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/migrate.c (ffffffff812e65dd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812e91a1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:use_zero_page_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
```
```
In mm/khugepaged.c (ffffffff812f186c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff812f8764)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memcontrol.c:drain_local_stock
```
```
In mm/memory-failure.c (ffffffff81301658)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffffffff8130706e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:reset_page
  - mm/zsmalloc.c:reset_page
```
```
In mm/userfaultfd.c (ffffffff81308a8e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff8130945d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/fs-writeback.c (ffffffff8134dc80)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_check_start_all
```
```
In fs/buffer.c (ffffffff8135bac0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:page_zero_new_buffers
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bforget
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/mpage.c (ffffffff813651d4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/io_uring.c (ffffffff81385fae)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_cancel_files
  - fs/io_uring.c:io_uring_cancel_files
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_cqring_overflow_flush
  - fs/io_uring.c:io_cqring_overflow_flush
```
```
In fs/crypto/crypto.c (ffffffff8139024b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/coredump.c (ffffffff813a7d50)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/coredump.c:zap_threads
```
```
In fs/iomap/buffered-io.c (ffffffff813ab94d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/quota/dquot.c (ffffffff813af8d1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_decr_space
  - fs/quota/dquot.c:dquot_decr_inodes
  - fs/quota/dquot.c:dquot_release
```
```
In fs/proc/task_mmu.c (ffffffff813b8e00)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/proc/base.c (ffffffff813bda5a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/proc/base.c:proc_coredump_filter_write
```
```
In fs/ext4/balloc.c (ffffffff813d9352)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/ext4/dir.c (ffffffff813dbdd2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents_status.c (ffffffff813e870a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
```
```
In fs/ext4/file.c (ffffffff813e9768)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff813eb385)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_parent
```
```
In fs/ext4/ialloc.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/ext4/inline.c (ffffffff813f5244)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff814000d4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_journalled_invalidatepage
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:mpage_process_page
  - fs/ext4/inode.c:mpage_process_page
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:do_journal_get_write_access
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff814011f4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff8140bbd7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/migrate.c (ffffffff8140da34)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/mmp.c (ffffffff8140dbc5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffffffff81415879)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/page-io.c (ffffffff81418219)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff81418357)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/ext4/resize.c (ffffffff8141c4c0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/ext4/super.c (ffffffff8142c847)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffffffff8143a29f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
```
In fs/ext4/verity.c (ffffffff8143c147)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In fs/jbd2/transaction.c (ffffffff8143f256)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff8144088a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/revoke.c (ffffffff81443b59)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff81448de7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:__journal_remove_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/hugetlbfs/inode.c (ffffffff81450bb8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
  - fs/hugetlbfs/inode.c:remove_huge_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81462f53)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/fuse/dev.c (ffffffff8146f0e0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/dir.c (ffffffff814752a2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff8147abb9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_perform_write
```
```
In ipc/util.c (ffffffff814869ee)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/keys/gc.c (ffffffff81495bc5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/tomoyo/common.c (ffffffff814dd456)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/apparmor/policy_unpack.c (ffffffff814fcfa3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff81514d5f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
```
```
In security/integrity/ima/ima_appraise.c (ffffffff8151c736)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/ima/ima_appraise.c:xattr_verify
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8151d738)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_set_key
```
```
In block/blk-core.c (ffffffff815410d8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_clear
```
```
In block/blk-mq.c (ffffffff815515b0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_online
  - block/blk-mq.c:blk_mq_start_stopped_hw_queues
  - block/blk-mq.c:blk_mq_start_hw_queues
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:flush_busy_ctx
```
```
In block/blk-mq-sched.c (ffffffff815571ae)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_restart
```
```
In lib/rhashtable.c (ffffffff8158ea87)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_chain
```
```
In lib/irq_poll.c (ffffffff815e3f9e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In lib/nmi_backtrace.c (ffffffff815ed622)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In lib/vsprintf.c (ffffffff815f74f7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8160932d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8160b2e3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_init_irq_valid_mask
```
```
In drivers/gpio/gpiolib.c (ffffffff8160e377)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_set_config
  - drivers/gpio/gpiolib.c:linehandle_set_config
  - drivers/gpio/gpiolib.c:linehandle_set_config
  - drivers/gpio/gpiolib.c:linehandle_set_config
  - drivers/gpio/gpiolib.c:linehandle_set_config
  - drivers/gpio/gpiolib.c:linehandle_set_config
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff816160d5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
```
```
In drivers/pwm/sysfs.c (ffffffff8161cdbc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pwm/sysfs.c:pwm_export_child
```
```
In drivers/pci/bus.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/pci/remove.c (ffffffff816241d0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81659411)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8165beed)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff8167e8f4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff8168fdc5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/numa/hmat.c (ffffffff816e7f04)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
```
In drivers/acpi/battery.c (ffffffff816e9c89)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff817076e6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_release_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/xen/cpu_hotplug.c (ffffffff817116a7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
```
```
In drivers/xen/grant-table.c (ffffffff81711deb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_pages_clear_private
```
```
In drivers/xen/balloon.c (ffffffff81713fc4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/balloon.c:increase_reservation
```
```
In drivers/xen/events/events_2l.c (ffffffff81718bc5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_bind_to_cpu
```
```
In drivers/xen/events/events_fifo.c (ffffffff81719a67)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:consume_one_event
```
```
In drivers/tty/tty_io.c (ffffffff817362f6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kclose
```
```
In drivers/tty/n_tty.c (ffffffff8173a4de)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_write_wakeup
```
```
In drivers/tty/tty_ioctl.c (ffffffff8173db61)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
```
```
In drivers/tty/tty_ldisc.c (ffffffff8173dfa1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_close
  - drivers/tty/tty_ldisc.c:tty_ldisc_open
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
```
```
In drivers/tty/tty_port.c (ffffffff817401be)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/pty.c (ffffffff817428cc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_unix98_ioctl
  - drivers/tty/pty.c:pty_bsd_ioctl
  - drivers/tty/pty.c:pty_open
  - drivers/tty/pty.c:pty_open
```
```
In drivers/tty/sysrq.c (ffffffff81743b36)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/vt/keyboard.c (ffffffff81748d3e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8175475b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_close
```
```
In drivers/tty/serial/serial_core.c (ffffffff8175b5ce)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
```
In drivers/tty/serial/max310x.c (ffffffff8176843b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff8176e7ac)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
```
In drivers/char/misc.c (ffffffff817743d4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_deregister
  - drivers/char/misc.c:misc_register
```
```
In drivers/char/agp/frontend.c (ffffffff8177a8b5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_controller_release_current
  - drivers/char/agp/frontend.c:agp_controller_release_current
```
```
In drivers/char/agp/generic.c (ffffffff8177c9df)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff81783bb1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_release
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8178a48d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/iommu/intel/dmar.c (ffffffff8179cd03)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_free_seq_id
```
```
In drivers/iommu/intel/iommu.c (ffffffff817a1f94)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff817b07e9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/base/cacheinfo.c (ffffffff817c1b84)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
```
```
In drivers/base/power/domain.c (ffffffff817d204a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff818126a3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
```
```
In drivers/nvdimm/label.c (ffffffff8181b8d5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_alloc_slot
```
```
In drivers/nvdimm/security.c (ffffffff818223a4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/dax/super.c (ffffffff81822ea8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_write_cache
```
```
In drivers/scsi/scsi_lib.c (ffffffff818381b5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8183cc36)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
```
```
In drivers/scsi/sr.c (ffffffff8184a6ab)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_kref_release
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/ata/libata-sata.c (ffffffff81868bb8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_sas_free_tag
```
```
In drivers/net/tun.c (ffffffff8188b016)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/xen-netfront.c (ffffffff81898623)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:xennet_open
```
```
In drivers/usb/core/hub.c (ffffffff818b90b2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect_change
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff818be871)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
```
```
In drivers/usb/core/sysfs.c (ffffffff818c9f3f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
```
```
In drivers/usb/core/devio.c (ffffffff818cacdf)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818db595)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818f1de3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff82f25693)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81901455)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In drivers/usb/host/xhci.c (ffffffff819067c4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
```
```
In drivers/usb/host/xhci-hub.c (ffffffff8191a5d7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
```
In drivers/input/mousedev.c (ffffffff8192f07b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/rtc/dev.c (ffffffff8193c7c4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/watchdog/watchdog_core.c (ffffffff8195cafd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8195d98f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/watchdog/watchdog_dev.c:watchdog_write
```
```
In drivers/md/md.c (ffffffff81963e4b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_written
```
```
In drivers/md/md-bitmap.c (ffffffff81974ebf)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
```
```
In drivers/md/dm.c (ffffffff81977a6c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:dm_cancel_deferred_remove
```
```
In drivers/md/dm-kcopyd.c (ffffffff81984bee)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8199531d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
```
```
In drivers/cpuidle/poll_state.c (ffffffff81bcc973)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In drivers/leds/led-core.c (ffffffff819b7674)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/firmware/efi/efi.c (ffffffff82d29667)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
```
In drivers/firmware/efi/memmap.c (ffffffff82d2a309)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
```
In net/core/sock.c (ffffffff819e5336)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_wait_for_wmem
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/stream.c (ffffffff819f6435)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_write_space
```
```
In net/core/dev.c (ffffffff81a01cd5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/dev.c:napi_disable
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
```
```
In net/core/link_watch.c (ffffffff81a22a7b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/xdp.c (ffffffff81a360be)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/core/skmsg.c (ffffffff81a3d91c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/netpoll.c (ffffffff81a3e4b1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
```
```
In net/core/gro_cells.c (ffffffff81a6082f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81a6658b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/netlink/af_netlink.c (ffffffff81a7861d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/netlink/genetlink.c (ffffffff81a7d100)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_unregister_mc_groups
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
```
```
In net/ethtool/linkmodes.c (ffffffff81a88cfc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_auto_linkmodes
```
```
In net/ipv4/tcp.c (ffffffff81aad339)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_output.c (ffffffff81ac1345)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5fae)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b01d9a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b08763)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b10957)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81b24892)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
```
```
In net/ipv6/ip6mr.c (ffffffff81b7532a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b8151e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81ba06c8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
```
```
In net/ncsi/ncsi-manage.c (ffffffff81ba1613)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81bac5a4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_wait_data
  - net/mptcp/protocol.c:ssk_check_wmem
  - net/mptcp/protocol.c:mptcp_subflow_get_send
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
In arch/x86/events/amd/uncore.c (ffffffff8100a13a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_dead
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a9c3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81029b06)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
```
```
In arch/x86/xen/smp_pv.c (ffffffff81bd2d1d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:clear_bit
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff810328a3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/kernel/process_64.c (ffffffff810336ff)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff81c35f1d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
```
```
In arch/x86/kernel/ioport.c (ffffffff8103804f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81c451b4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8104189d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81043129)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104463c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81046ae7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:set_task_blockstep
  - arch/x86/kernel/step.c:enable_single_step
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104b577)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8104c05d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81051656)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_apply_quirks
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810535fd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105cab5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81062222)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066405)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81067c2b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff81069045)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:release_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:release_perfctr_nmi
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81069ec9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106a772)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106d114)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/mpparse.c (ffffffff82fc86e0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:MP_bus_info
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075b83)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff8107e9b0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/init_64.c (ffffffff81c3c988)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In arch/x86/mm/tlb.c (ffffffff8108b0f8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8109323d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/mm/numa.c (ffffffff81093a89)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In arch/x86/platform/efi/quirks.c (ffffffff81096850)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault
```
```
In arch/x86/platform/efi/efi.c (ffffffff81bda372)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109a73c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_cleanup_mask
```
```
In kernel/fork.c (ffffffff810a2bef)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/cpu.c (ffffffff810a6753)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (ffffffff810a773c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
```
```
In kernel/softirq.c (ffffffff810aa5e4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/ptrace.c (ffffffff810b0696)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810b959c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/sys.c (ffffffff810c011a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/workqueue.c (ffffffff810c360c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
```
```
In kernel/kthread.c (ffffffff810cb252)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_set_per_cpu
```
```
In kernel/sched/core.c (ffffffff810e40d4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/idle.c (ffffffff810e607f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:default_idle_call
```
```
In kernel/sched/fair.c (ffffffff810f465b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_exit_idle
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/sched/rt.c (ffffffff810f6e0c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810f884f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810fe65b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
  - kernel/sched/cpupri.c:cpupri_find_fitness
```
```
In kernel/sched/cpudeadline.c (ffffffff810fec6c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff811014dd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_clear
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/power/snapshot.c (ffffffff81113805)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
```
```
In kernel/irq/resend.c (ffffffff81121cf2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/resend.c:resend_irqs
```
```
In kernel/irq/chip.c (ffffffff8112360f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/generic-chip.c (ffffffff81124828)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
```
In kernel/irq/affinity.c (ffffffff81129b8f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/irq/matrix.c (ffffffff8112b827)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_free
  - kernel/irq/matrix.c:irq_matrix_remove_managed
```
```
In kernel/livepatch/transition.c (ffffffff811373ff)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/entry/common.c (ffffffff8113babc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
  - kernel/entry/common.c:exit_to_user_mode_loop
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff8113bddd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:set_syscall_user_dispatch
```
```
In kernel/entry/kvm.c (ffffffff8113be65)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_work
  - kernel/entry/kvm.c:xfer_to_guest_mode_work
```
```
In kernel/profile.c (ffffffff8113ce51)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff81153694)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/kexec_core.c (ffffffff8116797b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117671d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/cgroup/freezer.c (ffffffff8117871f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/cgroup/cpuset.c (ffffffff8117e871)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:cpuset_update_task_spread_flag
  - kernel/cgroup/cpuset.c:cpuset_update_task_spread_flag
```
```
In kernel/pid_namespace.c (ffffffff811827b8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffffffff8118c851)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/watchdog.c (ffffffff81be4f97)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/tracepoint.c (ffffffff811a9521)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/trace/trace.c (ffffffff811bda26)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
```
```
In kernel/trace/trace_events.c (ffffffff811d1d51)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:trace_event_enable_tgid_record
  - kernel/trace/trace_events.c:trace_event_enable_cmd_record
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d50b1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811d9422)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_count_trigger
  - kernel/trace/trace_events_trigger.c:update_cond_flag
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/bpf/offload.c (ffffffff81230efe)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/events/core.c (ffffffff8123a658)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In kernel/events/ring_buffer.c (ffffffff8124d65c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:__rb_free_aux
```
```
In kernel/events/uprobes.c (ffffffff812535df)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/user-return-notifier.c (ffffffff812537d5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/filemap.c (ffffffff8125db78)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read_readpage
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:page_endio
  - mm/filemap.c:end_page_writeback
  - mm/filemap.c:wake_up_page_bit
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/oom_kill.c (ffffffff8126210e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/page-writeback.c (ffffffff81266766)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/readahead.c (ffffffff812676f8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/swap.c (ffffffff81269a83)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
```
```
In mm/truncate.c (ffffffff8126b07f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff812702fe)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:shrink_slab_memcg
```
```
In mm/shmem.c (ffffffff812790bc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
```
```
In mm/vmstat.c (ffffffff812804d6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/gup.c (ffffffff81291b7f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
```
```
In mm/memory.c (ffffffff8129c41c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (ffffffff812afd75)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/page_alloc.c (ffffffff812bf6e7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (ffffffff812c2f1f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff812c3b4c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/swap_state.c (ffffffff812c488f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/frontswap.c (ffffffff812cc636)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/hugetlb.c (ffffffff812d6f92)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffffffff812d98aa)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/sparse.c (ffffffff812dd1f7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/ksm.c (ffffffff812e2751)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/memory_hotplug.c (ffffffff812ebdc4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:node_states_clear_node
  - mm/memory_hotplug.c:node_states_clear_node
  - mm/memory_hotplug.c:node_states_clear_node
  - mm/memory_hotplug.c:put_page_bootmem
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/migrate.c (ffffffff812f19f1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812f462c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:use_zero_page_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
```
```
In mm/khugepaged.c (ffffffff812fddc1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff8130456c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memcontrol.c:drain_local_stock
```
```
In mm/memory-failure.c (ffffffff8130e7bf)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffffffff81312dae)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:reset_page
  - mm/zsmalloc.c:reset_page
```
```
In mm/userfaultfd.c (ffffffff8131487f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff8131526d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/exec.c (ffffffff81329b88)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/fs-writeback.c (ffffffff8135ab19)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_check_start_all
```
```
In fs/buffer.c (ffffffff8136a070)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:page_zero_new_buffers
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bforget
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/block_dev.c (ffffffff8136c886)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_disk_changed
```
```
In fs/mpage.c (ffffffff8137213a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/io_uring.c (ffffffff8139033a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:__io_cqring_overflow_flush
  - fs/io_uring.c:__io_cqring_overflow_flush
```
```
In fs/crypto/crypto.c (ffffffff813a188b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/coredump.c (ffffffff813b8bdd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/coredump.c:zap_threads
```
```
In fs/iomap/buffered-io.c (ffffffff813bc3dc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_read_page_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/quota/dquot.c (ffffffff813c0ed1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_decr_space
  - fs/quota/dquot.c:dquot_decr_inodes
  - fs/quota/dquot.c:dquot_release
```
```
In fs/proc/task_mmu.c (ffffffff813ca848)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/proc/base.c (ffffffff813cf7aa)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/proc/base.c:proc_coredump_filter_write
```
```
In fs/ext4/balloc.c (ffffffff813eafe2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/ext4/dir.c (ffffffff813ed318)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents_status.c (ffffffff813fa9ba)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
```
```
In fs/ext4/file.c (ffffffff813fb418)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff813fd5b5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_parent
```
```
In fs/ext4/ialloc.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/ext4/inline.c (ffffffff814079e4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff81412852)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_journalled_invalidatepage
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:mpage_process_page
  - fs/ext4/inode.c:mpage_process_page
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:do_journal_get_write_access
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff81413ab4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff8141f00d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/migrate.c (ffffffff81420e80)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/mmp.c (ffffffff81421037)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffffffff81429293)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/page-io.c (ffffffff8142bccc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff8142beb7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/ext4/resize.c (ffffffff81430270)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/ext4/super.c (ffffffff81445561)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffffffff81452dce)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
```
In fs/ext4/fast_commit.c (ffffffff81455c2c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_init_inode
  - fs/ext4/fast_commit.c:ext4_end_buffer_io_sync
```
```
In fs/ext4/verity.c (ffffffff814584b2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In fs/jbd2/transaction.c (ffffffff8145b4b6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff8145cab7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/revoke.c (ffffffff8145fc39)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff81465987)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:__journal_remove_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/hugetlbfs/inode.c (ffffffff8146d0c8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
  - fs/hugetlbfs/inode.c:remove_huge_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81bee44f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/fuse/dev.c (ffffffff81489840)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/dir.c (ffffffff8148fdf0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff81495842)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_perform_write
```
```
In ipc/util.c (ffffffff814a409e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/keys/gc.c (ffffffff814b3625)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/tomoyo/common.c (ffffffff814fa876)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/apparmor/policy_unpack.c (ffffffff8151a1b3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff81bf1a9a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
```
```
In security/integrity/ima/ima_appraise.c (ffffffff815395a6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/ima/ima_appraise.c:xattr_verify
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8153a5a8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_set_key
```
```
In block/blk-core.c (ffffffff8155dd68)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_clear
```
```
In block/blk-mq.c (ffffffff8156d6f0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_online
  - block/blk-mq.c:blk_mq_start_stopped_hw_queues
  - block/blk-mq.c:blk_mq_start_hw_queues
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:flush_busy_ctx
```
```
In block/blk-mq-sched.c (ffffffff8157383e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_restart
```
```
In lib/rhashtable.c (ffffffff815ab5e7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_chain
```
```
In lib/irq_poll.c (ffffffff816084ce)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In lib/nmi_backtrace.c (ffffffff81611de2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In lib/vsprintf.c (ffffffff8161b94b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8162da3d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8162fa4b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_init_irq_valid_mask
```
```
In drivers/gpio/gpiolib.c (ffffffff81634e4a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163a11a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8163ca65)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
```
```
In drivers/pwm/sysfs.c (ffffffff816434ec)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pwm/sysfs.c:pwm_export_child
```
```
In drivers/pci/bus.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/pci/remove.c (ffffffff81649d90)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81679811)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8167c910)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_unmap_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
```
```
In drivers/idle/intel_idle.c (ffffffff8169d5f4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff816ada95)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/numa/hmat.c (ffffffff817055ff)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
```
In drivers/acpi/battery.c (ffffffff81707479)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81724936)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_release_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/xen/cpu_hotplug.c (ffffffff8172e3d7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
```
```
In drivers/xen/grant-table.c (ffffffff81730028)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
```
```
In drivers/xen/balloon.c (ffffffff81730f94)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/balloon.c:increase_reservation
```
```
In drivers/xen/events/events_2l.c (ffffffff8173618f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_bind_to_cpu
  - drivers/xen/events/events_2l.c:evtchn_2l_remove
```
```
In drivers/xen/events/events_fifo.c (ffffffff81736cb3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:consume_one_event
```
```
In drivers/tty/tty_io.c (ffffffff81752e44)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kclose
```
```
In drivers/tty/n_tty.c (ffffffff817558ae)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_write_wakeup
```
```
In drivers/tty/tty_ioctl.c (ffffffff81759ac1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
```
```
In drivers/tty/tty_ldisc.c (ffffffff81759f01)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_close
  - drivers/tty/tty_ldisc.c:tty_ldisc_open
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
```
```
In drivers/tty/tty_port.c (ffffffff8175c0ee)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/pty.c (ffffffff8175e76c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_unix98_ioctl
  - drivers/tty/pty.c:pty_bsd_ioctl
  - drivers/tty/pty.c:pty_open
  - drivers/tty/pty.c:pty_open
```
```
In drivers/tty/sysrq.c (ffffffff8175fa77)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/vt/keyboard.c (ffffffff81764b3b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8176f9cb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_close
```
```
In drivers/tty/serial/serial_core.c (ffffffff817766ae)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
```
In drivers/tty/serial/max310x.c (ffffffff8178319b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff817890ac)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
```
In drivers/char/misc.c (ffffffff8178f154)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_deregister
  - drivers/char/misc.c:misc_register
```
```
In drivers/char/agp/generic.c (ffffffff81795b2f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff8179b101)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_release
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff817a140d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/iommu/intel/dmar.c (ffffffff817aa9d3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_free_seq_id
```
```
In drivers/iommu/intel/iommu.c (ffffffff817b0154)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff81c0d9f6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/base/cacheinfo.c (ffffffff817d6da4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
```
```
In drivers/base/power/domain.c (ffffffff817e685a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff818218f3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
```
```
In drivers/nvdimm/label.c (ffffffff8182a935)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_alloc_slot
```
```
In drivers/nvdimm/security.c (ffffffff818310b4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/dax/super.c (ffffffff81831be8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_write_cache
```
```
In drivers/scsi/scsi_lib.c (ffffffff818488b8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8184d436)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
```
```
In drivers/scsi/sr.c (ffffffff8185abab)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_kref_release
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/ata/libata-sata.c (ffffffff818779c8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_sas_free_tag
```
```
In drivers/net/tun.c (ffffffff818991b6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/xen-netfront.c (ffffffff818a69fb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:xennet_open
```
```
In drivers/usb/core/hub.c (ffffffff818c7992)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect_change
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff818cb471)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
```
```
In drivers/usb/core/sysfs.c (ffffffff818d508f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
```
```
In drivers/usb/core/devio.c (ffffffff818d5dcf)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818e5449)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818fad03)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8321dc00)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81909d25)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In drivers/usb/host/xhci.c (ffffffff8190ef82)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81920f1e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
```
In drivers/input/mousedev.c (ffffffff8193641b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/rtc/dev.c (ffffffff819427b4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/watchdog/watchdog_core.c (ffffffff819635e3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8196438f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/watchdog/watchdog_dev.c:watchdog_write
```
```
In drivers/md/md.c (ffffffff8196a73b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_written
```
```
In drivers/md/md-bitmap.c (ffffffff81979dbf)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
```
```
In drivers/md/dm.c (ffffffff8197c6fc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:dm_cancel_deferred_remove
```
```
In drivers/md/dm-kcopyd.c (ffffffff81988c8b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
```
In drivers/cpufreq/cpufreq.c (ffffffff819999cd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
```
```
In drivers/cpuidle/poll_state.c (ffffffff81c454d3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In drivers/leds/led-core.c (ffffffff819b9b74)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/firmware/efi/efi.c (ffffffff83017d7f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
```
In drivers/firmware/efi/memmap.c (ffffffff83018a20)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
```
In net/core/sock.c (ffffffff819e4c36)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_wait_for_wmem
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/stream.c (ffffffff819f6096)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_write_space
```
```
In net/core/dev.c (ffffffff81a02fd5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
```
```
In net/core/link_watch.c (ffffffff81a22ddb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/xdp.c (ffffffff81a3848e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/core/skmsg.c (ffffffff81a404fc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/netpoll.c (ffffffff81a41260)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
```
```
In net/core/gro_cells.c (ffffffff81a690cf)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81a6e66b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/netlink/af_netlink.c (ffffffff81a81434)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/netlink/genetlink.c (ffffffff81a866b6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_unregister_mc_groups
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
```
```
In net/ethtool/linkmodes.c (ffffffff81a925dc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_auto_linkmodes
```
```
In net/ipv4/tcp.c (ffffffff81ab4709)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_output.c (ffffffff81accdb5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02e1e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b0fe7a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b16903)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1ec47)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81b33302)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
```
```
In net/ipv6/ip6mr.c (ffffffff81b8409a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b90d5e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81bb00a8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
```
```
In net/ncsi/ncsi-manage.c (ffffffff81bb0eb3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81bbe284)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_wait_data
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
In arch/x86/events/amd/uncore.c (ffffffff8100a8ba)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_dead
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100b469)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/intel/core.c (ffffffff81010505)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dead
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102aa52)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
```
```
In arch/x86/xen/smp_pv.c (ffffffff81bc506c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:clear_bit
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81033d03)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/kernel/process_64.c (ffffffff8103529f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff81c2839e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
```
```
In arch/x86/kernel/ioport.c (ffffffff81039b8f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81c38431)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8104329d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81044a39)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104628c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81048517)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104cf07)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8104db9d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81052ec6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_apply_quirks
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81054eca)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105d415)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81062880)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066ac5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810680e0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff81069b3d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:release_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:release_perfctr_nmi
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff8106a999)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106b239)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106dbb4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/mpparse.c (ffffffff831d2f6e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:MP_bus_info
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81076633)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff8107fe80)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/init_64.c (ffffffff81c2ee64)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In arch/x86/mm/tlb.c (ffffffff8108bc3a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093c3d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/mm/numa.c (ffffffff81094449)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In arch/x86/platform/efi/quirks.c (ffffffff81097171)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
```
```
In arch/x86/platform/efi/efi.c (ffffffff81bcc49a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109b584)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/fork.c (ffffffff810a2ff6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/cpu.c (ffffffff810a747c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:bringup_cpu
```
```
In kernel/exit.c (ffffffff810a87cc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
```
```
In kernel/softirq.c (ffffffff810ab59a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/ptrace.c (ffffffff810b1c16)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810bad41)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/sys.c (ffffffff810c1b1c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/workqueue.c (ffffffff810c4388)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
```
```
In kernel/kthread.c (ffffffff810ccbc2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_set_per_cpu
```
```
In kernel/sched/core.c (ffffffff810e60ac)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/idle.c (ffffffff810e8049)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:default_idle_call
```
```
In kernel/sched/fair.c (ffffffff810f661b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_exit_idle
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/sched/rt.c (ffffffff810f895c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810fab4f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff81100a40)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
  - kernel/sched/cpupri.c:cpupri_find_fitness
```
```
In kernel/sched/cpudeadline.c (ffffffff8110104c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff8110386d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_clear
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/power/snapshot.c (ffffffff81112d20)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/irq/resend.c (ffffffff81122070)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/resend.c:resend_irqs
```
```
In kernel/irq/chip.c (ffffffff8112396f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/generic-chip.c (ffffffff81124b88)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
```
In kernel/irq/affinity.c (ffffffff81129e29)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/irq/matrix.c (ffffffff8112b575)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_remove_managed
```
```
In kernel/livepatch/transition.c (ffffffff811381af)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/entry/common.c (ffffffff8113cd8c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
  - kernel/entry/common.c:exit_to_user_mode_loop
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff8113d0cc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:set_syscall_user_dispatch
```
```
In kernel/entry/kvm.c (ffffffff8113d142)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
```
```
In kernel/profile.c (ffffffff8113e091)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff81154818)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/kexec_core.c (ffffffff8116870b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117728d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/cgroup/freezer.c (ffffffff8117928f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/cgroup/cpuset.c (ffffffff8117e881)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:cpuset_update_task_spread_flag
  - kernel/cgroup/cpuset.c:cpuset_update_task_spread_flag
```
```
In kernel/pid_namespace.c (ffffffff81183918)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffffffff8118d581)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/watchdog.c (ffffffff811a25d3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/tracepoint.c (ffffffff811aa0d1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/trace/trace.c (ffffffff811bd526)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
```
```
In kernel/trace/trace_events.c (ffffffff811d2b6b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:trace_event_enable_tgid_record
  - kernel/trace/trace_events.c:trace_event_enable_cmd_record
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d6390)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811da992)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_count_trigger
  - kernel/trace/trace_events_trigger.c:update_cond_flag
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/bpf/offload.c (ffffffff81235094)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/events/core.c (ffffffff8123eea8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In kernel/events/ring_buffer.c (ffffffff81251f99)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:__rb_free_aux
```
```
In kernel/events/uprobes.c (ffffffff81257bff)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/user-return-notifier.c (ffffffff81257df5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/filemap.c (ffffffff8126091f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:page_endio
  - mm/filemap.c:end_page_writeback
  - mm/filemap.c:end_page_private_2
  - mm/filemap.c:wake_up_page_bit
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/oom_kill.c (ffffffff81266b9e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/page-writeback.c (ffffffff8126b276)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/readahead.c (ffffffff8126c305)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/swap.c (ffffffff8126d86c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
```
```
In mm/truncate.c (ffffffff812701b3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff812761e2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:shrink_slab_memcg
```
```
In mm/shmem.c (ffffffff8127e06a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
```
```
In mm/vmstat.c (ffffffff812855d6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/percpu.c (ffffffff831f0397)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/gup.c (ffffffff8129746f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
```
```
In mm/memory.c (ffffffff8129ed63)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (ffffffff812b5355)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/page_alloc.c (ffffffff812c4d67)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/memory_hotplug.c (ffffffff812c673c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:put_page_bootmem
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/madvise.c (ffffffff812c9d98)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff812ca903)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/swap_state.c (ffffffff812cb52d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/frontswap.c (ffffffff812d3066)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/hugetlb.c (ffffffff812de79d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:restore_reserve_on_error
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff812e1129)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/sparse.c (ffffffff812e4a4d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/ksm.c (ffffffff812e9ede)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/slub.c (ffffffff812f290d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
```
```
In mm/migrate.c (ffffffff812f7d7e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812fabac)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:use_zero_page_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
```
```
In mm/khugepaged.c (ffffffff81304f30)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff8130b55c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memcontrol.c:drain_local_stock
```
```
In mm/memory-failure.c (ffffffff81314c53)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffffffff813180fd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:reset_page
  - mm/zsmalloc.c:reset_page
```
```
In mm/userfaultfd.c (ffffffff8131b3c4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff8131b93d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/exec.c (ffffffff8132fa8a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/fs-writeback.c (ffffffff813616f6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_do_writeback
```
```
In fs/buffer.c (ffffffff81371d67)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:page_zero_new_buffers
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bforget
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/block_dev.c (ffffffff813740e4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_disk_changed
```
```
In fs/mpage.c (ffffffff81378243)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/io_uring.c (ffffffff8139ee86)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_sq_thread_unpark
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_req_task_work_add
  - fs/io_uring.c:tctx_task_work
  - fs/io_uring.c:__io_cqring_overflow_flush
  - fs/io_uring.c:__io_cqring_overflow_flush
```
```
In fs/io-wq.c (ffffffff813a336b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_worker
  - fs/io-wq.c:io_worker_handle_work
  - fs/io-wq.c:io_worker_handle_work
  - fs/io-wq.c:io_worker_handle_work
```
```
In fs/crypto/crypto.c (ffffffff813a8a2b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/coredump.c (ffffffff813bfcda)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/coredump.c:zap_threads
```
```
In fs/iomap/buffered-io.c (ffffffff813c38ba)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/quota/dquot.c (ffffffff813c7ab1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_decr_space
  - fs/quota/dquot.c:dquot_decr_inodes
  - fs/quota/dquot.c:dquot_release
```
```
In fs/proc/task_mmu.c (ffffffff813d18b3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/proc/base.c (ffffffff813d5a2a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/proc/base.c:proc_coredump_filter_write
```
```
In fs/ext4/balloc.c (ffffffff813f152a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/ext4/dir.c (ffffffff813f397b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents_status.c (ffffffff81400d7a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
```
```
In fs/ext4/file.c (ffffffff814018e8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff81403c13)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8140de54)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff81418cb2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_journalled_invalidatepage
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:do_journal_get_write_access
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff81419d4e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff814259bb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/migrate.c (ffffffff81427639)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/mmp.c (ffffffff814277e7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8142fd96)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/page-io.c (ffffffff81432998)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff81432b77)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/ext4/resize.c (ffffffff81436e70)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/ext4/super.c (ffffffff8144aeb8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:flush_stashed_error_work
```
```
In fs/ext4/xattr.c (ffffffff814585fe)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
```
In fs/ext4/fast_commit.c (ffffffff8145b849)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_init_inode
  - fs/ext4/fast_commit.c:ext4_end_buffer_io_sync
```
```
In fs/ext4/verity.c (ffffffff8145de54)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In fs/jbd2/transaction.c (ffffffff81460df6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff8146214c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/revoke.c (ffffffff81465319)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff8146b137)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:__journal_remove_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/hugetlbfs/inode.c (ffffffff814727b8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
  - fs/hugetlbfs/inode.c:remove_huge_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81be04af)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/fuse/dev.c (ffffffff8148f0c3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/dir.c (ffffffff81495828)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff8149a89f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
```
```
In ipc/util.c (ffffffff814a9fc5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/keys/gc.c (ffffffff814b945e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/tomoyo/common.c (ffffffff8150147c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/apparmor/policy_unpack.c (ffffffff81520ac1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff81be3ab8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
```
```
In security/integrity/ima/ima_appraise.c (ffffffff81541ca7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/ima/ima_appraise.c:xattr_verify
```
```
In security/integrity/evm/evm_crypto.c (ffffffff81542c68)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_set_key
```
```
In block/blk-core.c (ffffffff815665c8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_clear
```
```
In block/blk-mq.c (ffffffff81575550)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_online
  - block/blk-mq.c:blk_mq_start_stopped_hw_queues
  - block/blk-mq.c:blk_mq_start_hw_queues
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:flush_busy_ctx
```
```
In block/blk-mq-sched.c (ffffffff8157b8ce)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_restart
```
```
In lib/rhashtable.c (ffffffff815b644a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff815eb12e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In lib/nmi_backtrace.c (ffffffff815f54c2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In lib/vsprintf.c (ffffffff815fcf8c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff816116bd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff816136ea)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_init_irq_valid_mask
```
```
In drivers/gpio/gpiolib.c (ffffffff8161872a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161dd6a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81620595)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
```
```
In drivers/pwm/sysfs.c (ffffffff8162630c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pwm/sysfs.c:pwm_export_child
```
```
In drivers/pci/bus.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/pci/remove.c (ffffffff8162c949)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/pci/pcie/dpc.c (ffffffff81646df0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8165c1e4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8165f780)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_unmap_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
```
```
In drivers/idle/intel_idle.c (ffffffff8168037b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff81690067)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/numa/hmat.c (ffffffff816e6c9d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
```
In drivers/acpi/battery.c (ffffffff816e8a79)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81705bfa)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_release_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81712077)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
```
```
In drivers/xen/grant-table.c (ffffffff81713a77)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
```
```
In drivers/xen/balloon.c (ffffffff81714c98)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/events/events_2l.c (ffffffff81719c1f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_bind_to_cpu
  - drivers/xen/events/events_2l.c:evtchn_2l_remove
```
```
In drivers/xen/events/events_fifo.c (ffffffff8171a7cc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
```
In drivers/tty/tty_io.c (ffffffff81736e2c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kclose
```
```
In drivers/tty/n_tty.c (ffffffff81739967)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_write_wakeup
```
```
In drivers/tty/tty_ioctl.c (ffffffff8173d961)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
```
```
In drivers/tty/tty_ldisc.c (ffffffff8173dda1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_close
  - drivers/tty/tty_ldisc.c:tty_ldisc_open
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
```
```
In drivers/tty/tty_port.c (ffffffff8173ff8e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/pty.c (ffffffff81741d99)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_open
  - drivers/tty/pty.c:pty_open
  - drivers/tty/pty.c:pty_set_lock
```
```
In drivers/tty/sysrq.c (ffffffff817438d7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/vt/keyboard.c (ffffffff81748342)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817534ab)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_close
```
```
In drivers/tty/serial/serial_core.c (ffffffff8175a28e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
```
In drivers/tty/serial/max310x.c (ffffffff81766a3b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff8176c98c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
```
In drivers/char/misc.c (ffffffff81771f44)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_deregister
  - drivers/char/misc.c:misc_register
```
```
In drivers/char/agp/generic.c (ffffffff817787ef)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff8177dc47)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_release
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81783f9d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/iommu/intel/dmar.c (ffffffff8178d3c3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_free_seq_id
```
```
In drivers/iommu/intel/iommu.c (ffffffff81791f54)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff81bffcd3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/base/cacheinfo.c (ffffffff817ba7b4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
```
```
In drivers/base/power/domain.c (ffffffff817cac59)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81804c13)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
```
```
In drivers/nvdimm/label.c (ffffffff8180dc08)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_alloc_slot
```
```
In drivers/nvdimm/security.c (ffffffff81814174)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/dax/super.c (ffffffff81814e18)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_write_cache
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182bc5d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81830806)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
```
```
In drivers/scsi/sr.c (ffffffff8183db9b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_kref_release
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/ata/libata-sata.c (ffffffff8185a1a8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_sas_free_tag
```
```
In drivers/net/tun.c (ffffffff8187a5d6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81887d35)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_port_txon
```
```
In drivers/net/xen-netfront.c (ffffffff8188add3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_open
```
```
In drivers/usb/core/hub.c (ffffffff818aadfc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect_change
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff818aea91)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
```
```
In drivers/usb/core/sysfs.c (ffffffff818b864f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
```
```
In drivers/usb/core/devio.c (ffffffff818b930f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818cc5f1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818df5f2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff83451bdd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818ee445)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In drivers/usb/host/xhci.c (ffffffff818f24ce)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
```
```
In drivers/usb/host/xhci-hub.c (ffffffff819045f2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
```
In drivers/input/mousedev.c (ffffffff81919480)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_key_event
  - drivers/input/mousedev.c:mousedev_key_event
```
```
In drivers/rtc/class.c (ffffffff81922619)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
```
```
In drivers/rtc/dev.c (ffffffff81925fe4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/rtc/rtc-cmos.c (ffffffff819289ee)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/watchdog/watchdog_core.c (ffffffff81947a04)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff819487af)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/watchdog/watchdog_dev.c:watchdog_write
```
```
In drivers/md/md.c (ffffffff8194e54b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_written
```
```
In drivers/md/md-bitmap.c (ffffffff8195d39f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
```
```
In drivers/md/dm.c (ffffffff819602cc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:dm_cancel_deferred_remove
```
```
In drivers/md/dm-kcopyd.c (ffffffff8196d36b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8197e4ed)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
```
```
In drivers/cpuidle/poll_state.c (ffffffff81c38753)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In drivers/leds/led-core.c (ffffffff8199e464)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/firmware/efi/efi.c (ffffffff83222c57)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
```
In drivers/firmware/efi/memmap.c (ffffffff83223a0d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
```
In drivers/powercap/dtpm.c (ffffffff819baa01)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/core/sock.c (ffffffff819caa96)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/stream.c (ffffffff819dc109)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_write_space
```
```
In net/core/dev.c (ffffffff819e8c15)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/dev.c:dev_set_threaded
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
```
```
In net/core/link_watch.c (ffffffff81a0a0fb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/xdp.c (ffffffff81a1f2c5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/core/netpoll.c (ffffffff81a25ec0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
```
```
In net/core/skmsg.c (ffffffff81a4ed7f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_stop
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_wait_data
```
```
In net/sched/sch_generic.c (ffffffff81a56efb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:qdisc_maybe_clear_missed
```
```
In net/netlink/af_netlink.c (ffffffff81a69bad)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/netlink/genetlink.c (ffffffff81a6f91a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
```
```
In net/ethtool/linkmodes.c (ffffffff81a7be4b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_auto_linkmodes
```
```
In net/ipv4/tcp.c (ffffffff81a9f86d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_output.c (ffffffff81ab7f74)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee715)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81afda6a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0c8d2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81b2103e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
```
```
In net/ipv6/ip6mr.c (ffffffff81b72d1a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b7ff65)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81b9f1a8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
```
```
In net/ncsi/ncsi-manage.c (ffffffff81ba1d68)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
```
In net/mptcp/protocol.c (ffffffff81bada14)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_wait_data
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
In arch/x86/events/amd/ibs.c (ffffffff8100b959)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/intel/core.c (ffffffff8101110c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dead
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102f07c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
```
```
In arch/x86/xen/smp_pv.c (ffffffff81c97bbb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:clear_bit
```
```
In arch/x86/kernel/process_64.c (ffffffff8103a57f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff81d4650e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
```
```
In arch/x86/kernel/ioport.c (ffffffff8103f53f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81d56cbe)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8104960a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104acd3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104c96c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff8104ee57)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810549bf)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8105536d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105b40c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_apply_quirks
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105d832)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81066b15)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8106c720)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81070d85)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81072560)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff8107424d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:release_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:release_perfctr_nmi
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81075264)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81075d56)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smpboot.c (ffffffff810793c4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/mpparse.c (ffffffff832b58c6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:MP_bus_info
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81083cde)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff8108ecc0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/init_64.c (ffffffff81d4d565)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In arch/x86/mm/tlb.c (ffffffff8109b297)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810a3a1d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/mm/numa.c (ffffffff810a437b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In arch/x86/platform/efi/quirks.c (ffffffff810a70dd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
```
```
In arch/x86/platform/efi/efi.c (ffffffff81ca25ed)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810ab79e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/fork.c (ffffffff810b4fac)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/cpu.c (ffffffff810b8eb8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:cpuhp_reset_state
```
```
In kernel/exit.c (ffffffff810ba2ac)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
```
```
In kernel/softirq.c (ffffffff810bd0ba)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/ptrace.c (ffffffff810c3de6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810cd5ad)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/sys.c (ffffffff810d48d1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/workqueue.c (ffffffff810d6f7a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
```
```
In kernel/kthread.c (ffffffff810df9a2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_set_per_cpu
```
```
In kernel/sched/core.c (ffffffff810fd2d2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/idle.c (ffffffff810ff709)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:default_idle_call
```
```
In kernel/sched/fair.c (ffffffff8111044b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_exit_idle
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/sched/rt.c (ffffffff81113f3c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff81115b8f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff8111cae9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
  - kernel/sched/cpupri.c:cpupri_find_fitness
```
```
In kernel/sched/cpudeadline.c (ffffffff8111d1ec)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff8112085d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_clear
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/power/snapshot.c (ffffffff81132d20)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_clear_bit
```
```
In kernel/irq/resend.c (ffffffff81142620)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/resend.c:resend_irqs
```
```
In kernel/irq/chip.c (ffffffff81143f3f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/generic-chip.c (ffffffff81145218)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
```
In kernel/irq/affinity.c (ffffffff8114a761)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/irq/matrix.c (ffffffff8114bf8f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_remove_managed
```
```
In kernel/livepatch/transition.c (ffffffff8115af39)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/entry/common.c (ffffffff8115feac)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
  - kernel/entry/common.c:exit_to_user_mode_loop
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff811601fc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:set_syscall_user_dispatch
```
```
In kernel/entry/kvm.c (ffffffff8116026c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_work
  - kernel/entry/kvm.c:xfer_to_guest_mode_work
```
```
In kernel/profile.c (ffffffff81161365)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/clocksource.c (ffffffff8116d864)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-broadcast.c (ffffffff81179268)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/kexec_core.c (ffffffff8118e43b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
```
```
In kernel/cgroup/cgroup.c (ffffffff8119bc42)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_kill
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8119e9fd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/cgroup/freezer.c (ffffffff811a0bac)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/cgroup/cpuset.c (ffffffff811a659e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:cpuset_update_task_spread_flag
  - kernel/cgroup/cpuset.c:cpuset_update_task_spread_flag
```
```
In kernel/pid_namespace.c (ffffffff811ab9f8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffffffff811b6272)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/watchdog.c (ffffffff811cbdb3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/tracepoint.c (ffffffff811d3c41)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/trace/trace.c (ffffffff811e8016)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
```
```
In kernel/trace/trace_events.c (ffffffff811ff91b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:trace_event_enable_tgid_record
  - kernel/trace/trace_events.c:trace_event_enable_cmd_record
```
```
In kernel/trace/trace_syscalls.c (ffffffff812031ee)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81208a1e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:update_cond_flag
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/bpf/offload.c (ffffffff8126f1c4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/events/core.c (ffffffff812798c1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In kernel/events/ring_buffer.c (ffffffff8128d839)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81293501)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/user-return-notifier.c (ffffffff81293965)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/filemap.c (ffffffff8129d30b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:page_endio
  - mm/filemap.c:end_page_writeback
  - mm/filemap.c:end_page_private_2
  - mm/filemap.c:wake_up_page_bit
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/oom_kill.c (ffffffff812a339e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/page-writeback.c (ffffffff812a7d56)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/readahead.c (ffffffff812a9015)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/swap.c (ffffffff812a9ede)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
```
```
In mm/truncate.c (ffffffff812ad443)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff812b2859)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:shrink_slab_memcg
```
```
In mm/shmem.c (ffffffff812bfdec)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/vmstat.c (ffffffff812c3f8a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/percpu.c (ffffffff832d5bdb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/gup.c (ffffffff812d7e1f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
```
```
In mm/memory.c (ffffffff812e0054)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (ffffffff812f6f95)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/page_alloc.c (ffffffff81309217)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/memory_hotplug.c (ffffffff8130b1a2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/madvise.c (ffffffff8130edb8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff8130f906)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/swap_state.c (ffffffff813105c6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/frontswap.c (ffffffff81318a76)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/hugetlb.c (ffffffff81325b3a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:restore_reserve_on_error
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/hugetlb_vmemmap.c (ffffffff81325e85)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:alloc_huge_page_vmemmap
```
```
In mm/mempolicy.c (ffffffff813283f9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/sparse.c (ffffffff8132bccd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/ksm.c (ffffffff81331e05)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/slub.c (ffffffff8133a355)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
```
```
In mm/migrate.c (ffffffff813423ee)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff813449c2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:use_zero_page_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
```
```
In mm/khugepaged.c (ffffffff8134ecc3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff8135678b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memcontrol.c:drain_local_stock
```
```
In mm/memory-failure.c (ffffffff81360cd3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffffffff81364605)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:reset_page
  - mm/zsmalloc.c:reset_page
```
```
In mm/page_idle.c (ffffffff81368c0d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In mm/bootmem_info.c (ffffffff8136cb53)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/exec.c (ffffffff8137d2b1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/fs-writeback.c (ffffffff813afd56)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_do_writeback
```
```
In fs/buffer.c (ffffffff813c0d87)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bforget
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/mpage.c (ffffffff813c4a22)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/io_uring.c (ffffffff813ef165)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_sq_thread_unpark
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:__io_cqring_overflow_flush
```
```
In fs/io-wq.c (ffffffff813f2034)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_enqueue
  - fs/io-wq.c:create_worker_cont
  - fs/io-wq.c:io_wqe_worker
  - fs/io-wq.c:io_worker_handle_work
  - fs/io-wq.c:io_worker_handle_work
  - fs/io-wq.c:io_worker_handle_work
  - fs/io-wq.c:io_worker_handle_work
  - fs/io-wq.c:io_queue_worker_create
  - fs/io-wq.c:create_worker_cb
  - fs/io-wq.c:io_worker_cancel_cb
```
```
In fs/crypto/crypto.c (ffffffff813f8185)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/coredump.c (ffffffff8140fb0a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/coredump.c:zap_threads
```
```
In fs/iomap/buffered-io.c (ffffffff81413ef1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/quota/dquot.c (ffffffff814180c2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_decr_space
  - fs/quota/dquot.c:dquot_decr_inodes
  - fs/quota/dquot.c:dquot_release
```
```
In fs/proc/task_mmu.c (ffffffff81422db3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/proc/base.c (ffffffff8142737a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/proc/base.c:proc_coredump_filter_write
```
```
In fs/ext4/balloc.c (ffffffff8144352a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/ext4/dir.c (ffffffff81445a3e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff814477ba)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/ext4/extents_status.c (ffffffff8145338a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
```
```
In fs/ext4/file.c (ffffffff81453e78)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff81456495)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/ext4/inline.c (ffffffff81460d14)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff8146bed9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_journalled_invalidatepage
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:mpage_process_page
  - fs/ext4/inode.c:mpage_process_page
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:do_journal_get_write_access
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff8146cf3e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff81479654)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/migrate.c (ffffffff8147b2b6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/mmp.c (ffffffff8147b438)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffffffff814843e6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/page-io.c (ffffffff81486260)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff81486347)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/ext4/resize.c (ffffffff8148aae0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/ext4/super.c (ffffffff8149edc8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/ext4/xattr.c (ffffffff814ac705)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
```
In fs/ext4/fast_commit.c (ffffffff814af114)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_init_inode
  - fs/ext4/fast_commit.c:ext4_end_buffer_io_sync
```
```
In fs/ext4/orphan.c (ffffffff814b17d9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
```
```
In fs/ext4/verity.c (ffffffff814b3371)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In fs/jbd2/transaction.c (ffffffff814b62d9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff814b7642)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/revoke.c (ffffffff814bac99)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff814c1845)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/hugetlbfs/inode.c (ffffffff814c9038)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
  - fs/hugetlbfs/inode.c:remove_huge_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81cd0c10)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/fuse/dev.c (ffffffff814e6b33)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/dir.c (ffffffff814ed2bb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff814f22f3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
```
```
In ipc/util.c (ffffffff81502475)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/keys/gc.c (ffffffff81511c8e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/tomoyo/common.c (ffffffff8155ca9f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/apparmor/policy_unpack.c (ffffffff8157ec61)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff81cd6c7c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
```
```
In security/integrity/ima/ima_appraise.c (ffffffff815a1a67)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/ima/ima_appraise.c:xattr_verify
```
```
In security/integrity/evm/evm_crypto.c (ffffffff815a3188)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_set_key
```
```
In block/blk-core.c (ffffffff815ca9e8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_clear
```
```
In block/blk-mq.c (ffffffff815d9b64)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_online
  - block/blk-mq.c:blk_mq_start_stopped_hw_queues
  - block/blk-mq.c:blk_mq_start_hw_queues
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:flush_busy_ctx
```
```
In block/blk-mq-sched.c (ffffffff815e0c2e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_restart
```
```
In block/partitions/core.c (ffffffff815e6aab)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In lib/rhashtable.c (ffffffff8161c98d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff816576d8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_enable
  - lib/irq_poll.c:irq_poll_disable
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In lib/nmi_backtrace.c (ffffffff81662932)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In lib/vsprintf.c (ffffffff8166ac27)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8168096d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff816827ca)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_init_irq_valid_mask
```
```
In drivers/gpio/gpiolib.c (ffffffff816879ca)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168d38a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8168fb45)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
```
```
In drivers/pwm/sysfs.c (ffffffff81695b4c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pwm/sysfs.c:pwm_export_child
```
```
In drivers/pci/bus.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/pci/remove.c (ffffffff8169be10)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/pci/pcie/dpc.c (ffffffff816b86a0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff816ce804)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff816cf11c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff816d2370)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_unmap_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
```
```
In drivers/idle/intel_idle.c (ffffffff816f50e8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff81705a17)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/numa/hmat.c (ffffffff81760276)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
```
In drivers/acpi/battery.c (ffffffff817620b9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81781579)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_release_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/xen/cpu_hotplug.c (ffffffff8178eae7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
```
```
In drivers/xen/grant-table.c (ffffffff81790489)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
```
```
In drivers/xen/balloon.c (ffffffff81791bbe)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
```
```
In drivers/xen/events/events_2l.c (ffffffff81797ea5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_bind_to_cpu
  - drivers/xen/events/events_2l.c:evtchn_2l_remove
```
```
In drivers/xen/events/events_fifo.c (ffffffff81798fa3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
```
In drivers/tty/tty_io.c (ffffffff817b7805)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kclose
```
```
In drivers/tty/n_tty.c (ffffffff817ba416)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_write_wakeup
```
```
In drivers/tty/tty_ioctl.c (ffffffff817be001)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
```
```
In drivers/tty/tty_ldisc.c (ffffffff817be291)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_close
  - drivers/tty/tty_ldisc.c:tty_ldisc_open
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
```
```
In drivers/tty/tty_port.c (ffffffff817c072e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/pty.c (ffffffff817c2859)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_open
  - drivers/tty/pty.c:pty_open
  - drivers/tty/pty.c:pty_set_lock
```
```
In drivers/tty/sysrq.c (ffffffff817c4570)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/vt/keyboard.c (ffffffff817c99ff)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817d689b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_close
```
```
In drivers/tty/serial/serial_core.c (ffffffff817dd7dd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
```
In drivers/tty/serial/max310x.c (ffffffff817eb40b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff817f20dc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
```
In drivers/char/misc.c (ffffffff817f7ce4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_deregister
  - drivers/char/misc.c:misc_register
```
```
In drivers/char/agp/generic.c (ffffffff817fe6b2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff81803e37)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_release
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8180a9d6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/iommu/intel/dmar.c (ffffffff81814bb3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_free_seq_id
```
```
In drivers/iommu/intel/iommu.c (ffffffff818197cd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domain_detach_iommu
```
```
In drivers/base/cacheinfo.c (ffffffff81844573)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
```
```
In drivers/base/power/domain.c (ffffffff81854d29)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8188f243)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
```
```
In drivers/nvdimm/label.c (ffffffff818981f8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_alloc_slot
```
```
In drivers/nvdimm/security.c (ffffffff8189e814)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/dax/super.c (ffffffff8189f588)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_write_cache
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b7811)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff818bc7d6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
```
```
In drivers/scsi/sr.c (ffffffff818ca65b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_kref_release
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/ata/libata-sata.c (ffffffff818e8c98)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_sas_free_tag
```
```
In drivers/net/tun.c (ffffffff8190baf6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/wwan/wwan_core.c (ffffffff819197f5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_port_txon
```
```
In drivers/net/xen-netfront.c (ffffffff8191f3f0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_resume
  - drivers/net/xen-netfront.c:xennet_open
```
```
In drivers/usb/core/hub.c (ffffffff8193fd7c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect_change
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff81943c01)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
```
```
In drivers/usb/core/sysfs.c (ffffffff8194e230)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
```
```
In drivers/usb/core/devio.c (ffffffff8194edef)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81966206)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8197afc2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8354521a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8198ac12)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In drivers/usb/host/xhci.c (ffffffff8198f726)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
```
```
In drivers/usb/host/xhci-hub.c (ffffffff819a4d03)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
```
In drivers/input/mousedev.c (ffffffff819bb840)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_key_event
  - drivers/input/mousedev.c:mousedev_key_event
```
```
In drivers/rtc/class.c (ffffffff819c55d5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
```
```
In drivers/rtc/dev.c (ffffffff819c8f54)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/rtc/rtc-cmos.c (ffffffff819cb30b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/watchdog/watchdog_core.c (ffffffff819ec91f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff819ed7af)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/watchdog/watchdog_dev.c:watchdog_write
```
```
In drivers/md/md.c (ffffffff819f394b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_written
```
```
In drivers/md/md-bitmap.c (ffffffff81a02bff)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
```
```
In drivers/md/dm-zone.c (ffffffff81a06220)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
```
```
In drivers/md/dm.c (ffffffff81a0858c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_cancel_deferred_remove
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81a27642)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
```
```
In drivers/cpuidle/poll_state.c (ffffffff81d57033)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In drivers/leds/led-core.c (ffffffff81a4b0e4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/firmware/efi/efi.c (ffffffff8330c9bb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
```
In drivers/firmware/efi/memmap.c (ffffffff8330d813)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
```
In drivers/powercap/dtpm.c (ffffffff81a69b0b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/core/sock.c (ffffffff81a7a0c6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/stream.c (ffffffff81a8c349)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_write_space
```
```
In net/core/dev.c (ffffffff81a99b85)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/dev.c:dev_set_threaded
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
```
```
In net/core/link_watch.c (ffffffff81abc60b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/xdp.c (ffffffff81ad3555)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/core/netpoll.c (ffffffff81adac1f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
```
```
In net/core/skmsg.c (ffffffff81b078ef)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_stop
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/sched/sch_generic.c (ffffffff81b0fd30)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:qdisc_maybe_clear_missed
```
```
In net/netlink/af_netlink.c (ffffffff81b23183)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/netlink/genetlink.c (ffffffff81b28f9a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
```
```
In net/ethtool/linkmodes.c (ffffffff81b361cb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_auto_linkmodes
```
```
In net/ipv4/tcp.c (ffffffff81b5b626)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_output.c (ffffffff81b75134)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/ipv4/inet_fragment.c (ffffffff81baeac5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81bbfb6a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc6fba)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
```
```
In net/ipv4/udp_bpf.c (ffffffff81bc88b9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcfac2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81be60fe)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
```
```
In net/unix/unix_bpf.c (ffffffff81beb656)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_msg_wait_data
```
```
In net/ipv6/ioam6.c (ffffffff81c3a200)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:__rhashtable_remove_fast_one
  - net/ipv6/ioam6.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/ip6mr.c (ffffffff81c3d25a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b805)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81c6c86d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
```
```
In net/ncsi/ncsi-manage.c (ffffffff81c6f7c2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
```
In net/mptcp/protocol.c (ffffffff81c7a451)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
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
In arch/x86/events/amd/ibs.c (ffffffff8100c509)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/intel/core.c (ffffffff81012846)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dead
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81034525)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
```
```
In arch/x86/xen/smp_pv.c (ffffffff8103b827)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/process_64.c (ffffffff810415ff)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff81f147dc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
```
```
In arch/x86/kernel/ioport.c (ffffffff81046bb5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81f28f36)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810539ca)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81054887)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpregs_restore_userregs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810555d7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpregs_restore_userregs
```
```
In arch/x86/kernel/ptrace.c (ffffffff81057a3c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff8105a0a7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8106070f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff810612ad)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810672fe)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_apply_quirks
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81069d57)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81073845)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81079ad4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107ebd9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_free_va_slot
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81080718)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff81082ab5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:release_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:release_perfctr_nmi
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81083c14)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8108479f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smpboot.c (ffffffff8108822f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/mpparse.c (ffffffff83466cb3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:MP_bus_info
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81093d3e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff8109f805)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/init_64.c (ffffffff81f1d26f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In arch/x86/mm/tlb.c (ffffffff810ae75b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810b80fc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/mm/numa.c (ffffffff810b8b4b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In arch/x86/platform/efi/quirks.c (ffffffff810bc43f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
```
```
In arch/x86/platform/efi/efi.c (ffffffff83478d1f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810c13dd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/fork.c (ffffffff810cac62)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/cpu.c (ffffffff810cf816)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_reset_state
```
```
In kernel/exit.c (ffffffff810d0d5b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
```
```
In kernel/softirq.c (ffffffff810d41aa)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/ptrace.c (ffffffff810dc3e4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810e551b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/sys.c (ffffffff810ed72d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/workqueue.c (ffffffff810f3786)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
```
```
In kernel/platform-feature.c (ffffffff810f9498)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/platform-feature.c:platform_clear
```
```
In kernel/kthread.c (ffffffff810f9b84)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_set_per_cpu
```
```
In kernel/sched/core.c (ffffffff81119ca0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffffffff8112c57e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_exit_idle
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/sched/build_policy.c (ffffffff8113676d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:rq_offline_dl
  - kernel/sched/build_policy.c:cpudl_clear_freecpu
  - kernel/sched/build_policy.c:cpudl_set
  - kernel/sched/build_policy.c:cpudl_find
  - kernel/sched/build_policy.c:rq_offline_rt
  - kernel/sched/build_policy.c:do_idle
  - kernel/sched/build_policy.c:cpuidle_idle_call
  - kernel/sched/build_policy.c:default_idle_call
```
```
In kernel/sched/build_utility.c (ffffffff8114ab32)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_domains_numa_masks_clear
  - kernel/sched/build_utility.c:rq_attach_root
  - kernel/sched/build_utility.c:cpupri_set
  - kernel/sched/build_utility.c:cpupri_find_fitness
```
```
In kernel/power/snapshot.c (ffffffff81154d8f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_clear_bit
```
```
In kernel/irq/resend.c (ffffffff8116616a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/resend.c:resend_irqs
```
```
In kernel/irq/chip.c (ffffffff811679ef)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/generic-chip.c (ffffffff81169376)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
```
In kernel/irq/irq_sim.c (ffffffff8116c2c9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:irq_sim_handle_irq
  - kernel/irq/irq_sim.c:irq_sim_set_irqchip_state
```
```
In kernel/irq/affinity.c (ffffffff8116fbd2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/irq/matrix.c (ffffffff81171881)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_remove_managed
```
```
In kernel/livepatch/transition.c (ffffffff81184843)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/entry/common.c (ffffffff8118a34f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff8118a6ee)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:set_syscall_user_dispatch
```
```
In kernel/entry/kvm.c (ffffffff8118a772)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
```
```
In kernel/profile.c (ffffffff81194175)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/clocksource.c (ffffffff811a1957)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-broadcast.c (ffffffff811ae407)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/kexec_core.c (ffffffff811bd9eb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
```
```
In kernel/cgroup/cgroup.c (ffffffff811cbeaf)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_kill
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811cf185)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/cgroup/freezer.c (ffffffff811d137b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/cgroup/cpuset.c (ffffffff811d7a0e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:cpuset_update_task_spread_flag
  - kernel/cgroup/cpuset.c:cpuset_update_task_spread_flag
```
```
In kernel/pid_namespace.c (ffffffff811dd16c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffffffff811e995a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/watchdog.c (ffffffff811ffb5e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/tracepoint.c (ffffffff8120876f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/trace/pid_list.c (ffffffff8122b6fe)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/pid_list.c:trace_pid_list_clear
```
```
In kernel/trace/trace_events.c (ffffffff81239f5d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:trace_event_enable_tgid_record
  - kernel/trace/trace_events.c:trace_event_enable_cmd_record
```
```
In kernel/trace/trace_syscalls.c (ffffffff8123e4ca)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81243363)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger
  - kernel/trace/trace_events_trigger.c:update_cond_flag
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/bpf/offload.c (ffffffff812be089)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/events/core.c (ffffffff812cca96)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In kernel/events/ring_buffer.c (ffffffff812e25e9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff812e8fd1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/user-return-notifier.c (ffffffff812e943f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/filemap.c (ffffffff812f431d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:page_endio
  - mm/filemap.c:folio_end_writeback
  - mm/filemap.c:folio_end_private_2
  - mm/filemap.c:folio_wake_bit
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/oom_kill.c (ffffffff812fb2ae)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/page-writeback.c (ffffffff81300389)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_cancel_dirty
  - mm/page-writeback.c:folio_mark_dirty
```
```
In mm/readahead.c (ffffffff8130247d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/swap.c (ffffffff8130328d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:pagevec_move_tail_fn
```
```
In mm/truncate.c (ffffffff81307bb8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_folio
```
```
In mm/vmscan.c (ffffffff8130f5aa)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:prepare_kswapd_sleep
  - mm/vmscan.c:prepare_kswapd_sleep
  - mm/vmscan.c:prepare_kswapd_sleep
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:shrink_slab_memcg
```
```
In mm/shmem.c (ffffffff8131c6c9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/vmstat.c (ffffffff813217b5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/percpu.c (ffffffff8348a474)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/gup.c (ffffffff81337954)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
```
```
In mm/memory.c (ffffffff813402e4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
```
```
In mm/mlock.c (ffffffff8134adab)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
```
```
In mm/rmap.c (ffffffff8135e7c4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:folio_referenced_one
```
```
In mm/page_alloc.c (ffffffff81371714)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/memory_hotplug.c (ffffffff81373c2f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/madvise.c (ffffffff813769ab)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff8137903f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:sio_write_complete
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/swap_state.c (ffffffff8137b16d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/frontswap.c (ffffffff81384104)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_store
```
```
In mm/hugetlb.c (ffffffff81394837)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:isolate_hugetlb
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:restore_reserve_on_error
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/hugetlb_vmemmap.c (ffffffff81394d8e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_alloc
```
```
In mm/mempolicy.c (ffffffff813975e2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/ksm.c (ffffffff813a3028)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/slub.c (ffffffff813ac0bf)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
```
```
In mm/migrate.c (ffffffff813b11ba)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/migrate.c:__set_migration_target_nodes
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/migrate_device.c (ffffffff813b7a87)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813c1c4e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:use_zero_page_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
```
```
In mm/khugepaged.c (ffffffff813c58f8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff813cf68f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memcontrol.c:drain_local_stock
```
```
In mm/memory-failure.c (ffffffff813dd777)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory-failure.c:clear_hwpoisoned_pages
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffffffff813e1e36)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/page_idle.c (ffffffff813e63d3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In mm/bootmem_info.c (ffffffff813eaeed)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/exec.c (ffffffff813fcea5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/fs-writeback.c (ffffffff814348cb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_do_writeback
```
```
In fs/buffer.c (ffffffff814447f0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/buffer.c:bh_submit_read
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bforget
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/mpage.c (ffffffff8144b86e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/crypto/crypto.c (ffffffff81e78625)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/coredump.c (ffffffff81484803)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/iomap/buffered-io.c (ffffffff8148af2c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_migrate_page
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/quota/dquot.c (ffffffff8148ee7a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_decr_space
  - fs/quota/dquot.c:dquot_decr_inodes
  - fs/quota/dquot.c:dquot_release
```
```
In fs/proc/task_mmu.c (ffffffff8149ab81)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/proc/base.c (ffffffff814a0f31)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/proc/base.c:proc_coredump_filter_write
```
```
In fs/ext4/balloc.c (ffffffff814bf358)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/ext4/dir.c (ffffffff814c20e3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff814c3518)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_get_access
```
```
In fs/ext4/extents_status.c (ffffffff814d094f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
```
```
In fs/ext4/file.c (ffffffff814d0e5e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff814d3f03)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/ext4/inline.c (ffffffff814df6f8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff814ebd76)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_journalled_invalidate_folio
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_process_page
  - fs/ext4/inode.c:mpage_process_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:do_journal_get_write_access
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff814ec8eb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mballoc.c (ffffffff814f5955)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/migrate.c (ffffffff814fd771)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/mmp.c (ffffffff814fd898)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffffffff81507232)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/page-io.c (ffffffff815098e6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff81509c4b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/ext4/resize.c (ffffffff8150d280)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/ext4/super.c (ffffffff81525508)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/ext4/xattr.c (ffffffff81534666)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
```
In fs/ext4/fast_commit.c (ffffffff815361bf)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_init_inode
  - fs/ext4/fast_commit.c:ext4_end_buffer_io_sync
```
```
In fs/ext4/orphan.c (ffffffff8153a33b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
```
```
In fs/ext4/verity.c (ffffffff8153bf58)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In fs/ext4/crypto.c (ffffffff8153ca0d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_set_context
```
```
In fs/jbd2/transaction.c (ffffffff8153fbc5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81540e0c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/revoke.c (ffffffff81544b56)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff8154c1d9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/hugetlbfs/inode.c (ffffffff81555446)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
  - fs/hugetlbfs/inode.c:remove_huge_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81e83e6e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/fuse/dev.c (ffffffff815748dc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/dir.c (ffffffff8157c135)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff81581b61)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
```
```
In ipc/util.c (ffffffff81593a22)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In security/keys/gc.c (ffffffff815a4039)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/tomoyo/common.c (ffffffff815f7ba6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/apparmor/policy_unpack.c (ffffffff8161d754)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff81e89ecd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
```
```
In security/integrity/ima/ima_appraise.c (ffffffff81647eb5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/ima/ima_appraise.c:xattr_verify
```
```
In security/integrity/evm/evm_crypto.c (ffffffff816499c7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_set_key
```
```
In block/blk-core.c (ffffffff81675f28)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_clear
```
```
In block/blk-mq.c (ffffffff816874d1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_online
  - block/blk-mq.c:blk_mq_start_stopped_hw_queues
  - block/blk-mq.c:blk_mq_start_hw_queues
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:flush_busy_ctx
```
```
In block/blk-mq-sched.c (ffffffff8168f795)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_restart
```
```
In block/partitions/core.c (ffffffff81695c2a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In io_uring/io_uring.c (ffffffff816d8c60)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - io_uring/io_uring.c:__ia32_sys_io_uring_register
  - io_uring/io_uring.c:__x64_sys_io_uring_register
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_sq_thread_unpark
  - io_uring/io_uring.c:io_rsrc_ref_quiesce
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_sq_thread
  - io_uring/io_uring.c:__io_cqring_overflow_flush
```
```
In io_uring/io-wq.c (ffffffff816d970f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker_affinity
  - io_uring/io-wq.c:io_wqe_enqueue
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_wqe_worker
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_worker_cancel_cb
```
```
In lib/rhashtable.c (ffffffff816ea19c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff8176f0d8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_enable
  - lib/irq_poll.c:irq_poll_disable
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In lib/nmi_backtrace.c (ffffffff81ea5c36)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8179c62b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8179e88f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_init_irq_valid_mask
```
```
In drivers/gpio/gpiolib.c (ffffffff817a310a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff817abf3b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff817af333)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
```
```
In drivers/pwm/sysfs.c (ffffffff817b6915)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pwm/sysfs.c:pwm_export_child
```
```
In drivers/pci/bus.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/pci/remove.c (ffffffff817bd72a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/pci/pcie/dpc.c (ffffffff817dc875)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff817f73f4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff817f7dda)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff817fb36e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_unmap_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
```
```
In drivers/idle/intel_idle.c (ffffffff81821a11)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff81833c1e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_stop
```
```
In drivers/acpi/numa/hmat.c (ffffffff81893c72)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
```
In drivers/acpi/battery.c (ffffffff81895ba0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff818b7eb6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_release_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
```
```
In drivers/xen/cpu_hotplug.c (ffffffff818c6b04)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
```
```
In drivers/xen/grant-table.c (ffffffff818c8937)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
```
```
In drivers/xen/balloon.c (ffffffff818ca840)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
```
```
In drivers/xen/events/events_2l.c (ffffffff818d0ea5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_bind_to_cpu
  - drivers/xen/events/events_2l.c:evtchn_2l_remove
```
```
In drivers/xen/events/events_fifo.c (ffffffff818d209f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
```
In drivers/tty/tty_io.c (ffffffff818f2a49)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kclose
```
```
In drivers/tty/n_tty.c (ffffffff818f7518)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_write_wakeup
```
```
In drivers/tty/tty_ioctl.c (ffffffff818fa345)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
```
```
In drivers/tty/tty_ldisc.c (ffffffff818fa4d1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_close
  - drivers/tty/tty_ldisc.c:tty_ldisc_open
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
```
```
In drivers/tty/tty_port.c (ffffffff818fcf50)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/pty.c (ffffffff818fec20)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_open
  - drivers/tty/pty.c:pty_open
  - drivers/tty/pty.c:pty_set_lock
```
```
In drivers/tty/sysrq.c (ffffffff81901311)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/vt/keyboard.c (ffffffff81906eee)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8191495f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_close
```
```
In drivers/tty/serial/serial_core.c (ffffffff8191c1d4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
```
In drivers/tty/serial/max310x.c (ffffffff8192ae32)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff819328bc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
```
In drivers/char/misc.c (ffffffff81936010)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_deregister
  - drivers/char/misc.c:misc_register
```
```
In drivers/char/agp/generic.c (ffffffff8193d315)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff81943665)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_release
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8194a4b4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/iommu/intel/dmar.c (ffffffff81955041)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_free_seq_id
```
```
In drivers/iommu/intel/iommu.c (ffffffff8195b9bb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
```
```
In drivers/base/cacheinfo.c (ffffffff819883f6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
```
```
In drivers/base/power/domain.c (ffffffff8199b446)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/block/loop.c (ffffffff819b8558)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff819d8773)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
```
```
In drivers/nvdimm/label.c (ffffffff819e209a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_alloc_slot
```
```
In drivers/nvdimm/security.c (ffffffff819e82b4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/dax/super.c (ffffffff819e9260)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a02f87)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81a07e02)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
```
```
In drivers/scsi/sr.c (ffffffff81a17d40)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_free_disk
```
```
In drivers/net/tun.c (ffffffff81a5f426)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81a6e9a5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_port_txon
```
```
In drivers/net/xen-netfront.c (ffffffff81a7260e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_open
```
```
In drivers/usb/core/hub.c (ffffffff81a97ec1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect_change
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:release_devnum
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff81edffee)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_stop_hcd
  - drivers/usb/core/hcd.c:usb_stop_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
```
```
In drivers/usb/core/sysfs.c (ffffffff81aa7194)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
```
```
In drivers/usb/core/devio.c (ffffffff81aa7eaf)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81ac0371)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8372361a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8372366c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/ohci-hcd.c:ohci_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff837236e0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In drivers/usb/host/xhci.c (ffffffff81aebc1d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_shutdown
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81b026ea)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_usb2_port_status
```
```
In drivers/input/mousedev.c (ffffffff81b1b86d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_key_event
  - drivers/input/mousedev.c:mousedev_key_event
```
```
In drivers/rtc/class.c (ffffffff81b260db)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
```
```
In drivers/rtc/dev.c (ffffffff81b2a144)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81b2ce87)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81b39af3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81b52c17)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_offline
```
```
In drivers/watchdog/watchdog_core.c (ffffffff81b5305d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81b540b4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/watchdog/watchdog_dev.c:watchdog_write
  - drivers/watchdog/watchdog_dev.c:watchdog_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_stop
```
```
In drivers/md/md.c (ffffffff81b5d5dd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_written
```
```
In drivers/md/md-bitmap.c (ffffffff81b6aa0c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
```
```
In drivers/md/dm-zone.c (ffffffff81b6de92)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
```
```
In drivers/md/dm.c (ffffffff81b71a57)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_cancel_deferred_remove
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81b90774)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
  - drivers/cpufreq/cpufreq.c:remove_cpu_dev_symlink
```
```
In drivers/cpuidle/poll_state.c (ffffffff81f29a02)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In drivers/leds/led-core.c (ffffffff81bb9641)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_blink_set_oneshot
  - drivers/leds/led-core.c:led_blink_set_oneshot
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/firmware/efi/efi.c (ffffffff834c62be)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
```
In drivers/firmware/efi/memmap.c (ffffffff834c754b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
```
In drivers/hte/hte.c (ffffffff81be43f0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_do_cb_work
  - drivers/hte/hte.c:hte_ts_dis_en_common
  - drivers/hte/hte.c:hte_ts_put
```
```
In net/core/sock.c (ffffffff81beda06)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/stream.c (ffffffff81c01be8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_write_space
```
```
In net/core/dev.c (ffffffff81c0d1b2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/dev.c:napi_disable
  - net/core/dev.c:dev_set_threaded
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
```
```
In net/core/link_watch.c (ffffffff81c37016)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/xdp.c (ffffffff81c50e9e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/core/netpoll.c (ffffffff81c5bad2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
```
```
In net/core/skmsg.c (ffffffff81c8d67f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_stop
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/sched/sch_generic.c (ffffffff81c96ec3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_activate
  - net/sched/sch_generic.c:dev_activate
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:qdisc_maybe_clear_missed
```
```
In net/netlink/af_netlink.c (ffffffff81cabc13)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
```
```
In net/netlink/genetlink.c (ffffffff81cb204f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
```
```
In net/ethtool/linkmodes.c (ffffffff81cc1ae0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_auto_linkmodes
```
```
In net/ipv4/tcp.c (ffffffff81cea7c3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_output.c (ffffffff81d04928)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/ipv4/inet_fragment.c (ffffffff81d4194c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81d55f3e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5c104)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
```
```
In net/ipv4/udp_bpf.c (ffffffff81d5e0fe)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d682e1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81d7d2f5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
```
```
In net/unix/unix_bpf.c (ffffffff81d83ad2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
```
In net/ipv6/ioam6.c (ffffffff81dd7f67)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81ddb683)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deae6f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81e0fb0b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
```
```
In net/ncsi/ncsi-manage.c (ffffffff81e13368)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
```
In net/mptcp/protocol.c (ffffffff81e241ce)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
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
In arch/x86/events/amd/ibs.c (ffffffff8100f569)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/intel/core.c (ffffffff810167f6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dead
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103c034)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043ff7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:_get_smp_config
  - arch/x86/xen/smp_pv.c:_get_smp_config
```
```
In arch/x86/kernel/process_64.c (ffffffff8104ad4f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff820bbb5c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
```
```
In arch/x86/kernel/ioport.c (ffffffff81050cc5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff820d4c26)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8106143a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu_clone
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81062cea)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81063920)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpstate_realloc
```
```
In arch/x86/kernel/ptrace.c (ffffffff8106522c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81067ab7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:set_task_blockstep
  - arch/x86/kernel/step.c:enable_single_step
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8106ef5f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8106fc3d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107688e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_apply_quirks
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81079b37)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81083c55)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108ab2e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81090439)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_free_va_slot
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81093053)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff81095565)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:release_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:release_perfctr_nmi
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff810969d4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81097a2f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109bc3f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/mpparse.c (ffffffff83e8af17)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:MP_bus_info
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810a939e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff810b7085)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/init_64.c (ffffffff820c53d5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In arch/x86/mm/tlb.c (ffffffff810c8a0a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d37ee)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/mm/numa.c (ffffffff810d43fb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In arch/x86/platform/efi/quirks.c (ffffffff810d7883)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
```
```
In arch/x86/platform/efi/efi.c (ffffffff83ea2eed)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810dddb3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/fork.c (ffffffff810e81f7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/cpu.c (ffffffff810edbaa)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_reset_state
```
```
In kernel/exit.c (ffffffff810ef73b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
```
```
In kernel/softirq.c (ffffffff810f30da)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/ptrace.c (ffffffff810fc55d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff81105bc3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/sys.c (ffffffff8110eb4d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/workqueue.c (ffffffff811158c6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
```
```
In kernel/kthread.c (ffffffff8111c914)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_set_per_cpu
```
```
In kernel/sched/core.c (ffffffff811415f0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffffffff8115624e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_exit_idle
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/sched/build_policy.c (ffffffff81160d9d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:rq_offline_dl
  - kernel/sched/build_policy.c:cpudl_clear_freecpu
  - kernel/sched/build_policy.c:cpudl_set
  - kernel/sched/build_policy.c:cpudl_find
  - kernel/sched/build_policy.c:rq_offline_rt
  - kernel/sched/build_policy.c:do_idle
  - kernel/sched/build_policy.c:cpuidle_idle_call
  - kernel/sched/build_policy.c:cpuidle_idle_call
  - kernel/sched/build_policy.c:cpuidle_idle_call
  - kernel/sched/build_policy.c:default_idle_call
```
```
In kernel/sched/build_utility.c (ffffffff811794c2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_domains_numa_masks_clear
  - kernel/sched/build_utility.c:rq_attach_root
  - kernel/sched/build_utility.c:cpupri_set
  - kernel/sched/build_utility.c:cpupri_find_fitness
```
```
In kernel/power/snapshot.c (ffffffff81184c2f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_clear_bit
```
```
In kernel/irq/resend.c (ffffffff8119a2ba)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/resend.c:resend_irqs
```
```
In kernel/irq/chip.c (ffffffff8119bdff)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/generic-chip.c (ffffffff8119dc46)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
```
In kernel/irq/irq_sim.c (ffffffff811a1251)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:irq_sim_handle_irq
  - kernel/irq/irq_sim.c:irq_sim_set_irqchip_state
```
```
In kernel/irq/affinity.c (ffffffff811a6006)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/irq/matrix.c (ffffffff811a7ecb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_remove_managed
```
```
In kernel/livepatch/transition.c (ffffffff811bfd8e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_copy_process
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/entry/common.c (ffffffff811c68bf)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff811c6c9e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:set_syscall_user_dispatch
```
```
In kernel/entry/kvm.c (ffffffff811c6d4e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
```
```
In kernel/profile.c (ffffffff811d17e5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/clocksource.c (ffffffff811e0b07)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-broadcast.c (ffffffff811eeb37)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/kexec_core.c (ffffffff811ffb1f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_shrink_memory
  - kernel/kexec_core.c:kimage_free_pages
```
```
In kernel/cgroup/cgroup.c (ffffffff8120f38f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_kill
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81212af5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/cgroup/freezer.c (ffffffff81214f0b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/cgroup/cpuset.c (ffffffff8121c71e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:update_flag
```
```
In kernel/pid_namespace.c (ffffffff81222b2c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffffffff8122f9aa)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/watchdog.c (ffffffff8124758d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/tracepoint.c (ffffffff81250c3f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/trace/pid_list.c (ffffffff812770de)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/pid_list.c:trace_pid_list_clear
```
```
In kernel/trace/trace_events.c (ffffffff8128734a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:trace_event_enable_tgid_record
  - kernel/trace/trace_events.c:trace_event_enable_cmd_record
```
```
In kernel/trace/trace_syscalls.c (ffffffff8128beaa)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81290e73)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger
  - kernel/trace/trace_events_trigger.c:update_cond_flag
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/bpf/offload.c (ffffffff81321807)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/events/core.c (ffffffff81334a81)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In kernel/events/ring_buffer.c (ffffffff8134abb9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134d60f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81352b91)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/user-return-notifier.c (ffffffff813531af)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/filemap.c (ffffffff8135c7c3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/filemap.c:filemap_read_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:page_endio
  - mm/filemap.c:folio_end_writeback
  - mm/filemap.c:folio_end_private_2
  - mm/filemap.c:folio_wake_bit
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/oom_kill.c (ffffffff8136529e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/page-writeback.c (ffffffff8136aca9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_cancel_dirty
  - mm/page-writeback.c:folio_mark_dirty
```
```
In mm/readahead.c (ffffffff8136cc2d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/swap.c (ffffffff8137013d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:lru_add_fn
```
```
In mm/truncate.c (ffffffff81371de0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_folio
```
```
In mm/vmscan.c (ffffffff8137e88c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:prepare_kswapd_sleep
  - mm/vmscan.c:prepare_kswapd_sleep
  - mm/vmscan.c:prepare_kswapd_sleep
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:isolate_folio
  - mm/vmscan.c:isolate_folio
  - mm/vmscan.c:should_skip_mm
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:shrink_slab_memcg
```
```
In mm/shmem.c (ffffffff81390329)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_writepage
```
```
In mm/vmstat.c (ffffffff813957c5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/percpu.c (ffffffff83ebaee7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/gup.c (ffffffff813aeff4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
```
```
In mm/memory.c (ffffffff813b8274)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
```
```
In mm/mlock.c (ffffffff813c39c1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
```
```
In mm/rmap.c (ffffffff813daffa)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:folio_referenced_one
```
```
In mm/page_alloc.c (ffffffff813eee44)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/memory_hotplug.c (ffffffff813f137c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/madvise.c (ffffffff813f42dc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff813f69df)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:sio_write_complete
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/swap_state.c (ffffffff813f8bc8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/frontswap.c (ffffffff81401c07)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_store
```
```
In mm/hugetlb.c (ffffffff814132b1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:isolate_hugetlb
  - mm/hugetlb.c:hugetlb_add_to_page_cache
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:restore_reserve_on_error
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/hugetlb_vmemmap.c (ffffffff81414593)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_restore
```
```
In mm/mempolicy.c (ffffffff814171ba)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/ksm.c (ffffffff81422cc5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/slub.c (ffffffff8142aa5f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
```
```
In mm/migrate.c (ffffffff81435097)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/memory-tiers.c (ffffffff820cc12b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory-tiers.c:memtier_hotplug_callback
```
```
In mm/migrate_device.c (ffffffff8143970a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81443df7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:use_zero_page_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
```
```
In mm/khugepaged.c (ffffffff8144a25a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff8145496f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memcontrol.c:drain_local_stock
```
```
In mm/memory-failure.c (ffffffff81463511)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffffffff81469419)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/page_idle.c (ffffffff8146debe)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In mm/bootmem_info.c (ffffffff814730ed)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/exec.c (ffffffff814869f9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/fs-writeback.c (ffffffff814c28ab)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_io_lists_depopulated
```
```
In fs/buffer.c (ffffffff814d3418)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:__bforget
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/mpage.c (ffffffff814daa29)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/crypto/crypto.c (ffffffff8206a3e3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/mbcache.c (ffffffff81514a72)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/coredump.c (ffffffff81517d03)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/iomap/buffered-io.c (ffffffff8151ef17)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/quota/dquot.c (ffffffff815229da)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_decr_space
  - fs/quota/dquot.c:dquot_decr_inodes
  - fs/quota/dquot.c:dquot_release
```
```
In fs/proc/task_mmu.c (ffffffff8152f0be)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/proc/base.c (ffffffff81535f21)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/proc/base.c:proc_coredump_filter_write
```
```
In fs/ext4/balloc.c (ffffffff81557296)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_wait_block_bitmap
```
```
In fs/ext4/dir.c (ffffffff8155a346)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8155b958)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_get_access
```
```
In fs/ext4/extents_status.c (ffffffff815692ff)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
```
```
In fs/ext4/file.c (ffffffff8156ab43)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff8156cb82)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/ext4/inline.c (ffffffff81578838)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff81585ac6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_journalled_invalidate_folio
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_process_page
  - fs/ext4/inode.c:mpage_process_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:write_end_fn
  - fs/ext4/inode.c:write_end_fn
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:do_journal_get_write_access
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff8158666f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mballoc.c (ffffffff8158fc45)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/migrate.c (ffffffff81597f49)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/mmp.c (ffffffff81598078)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffffffff815a1cf5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/page-io.c (ffffffff815a4591)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff815a48a7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/ext4/resize.c (ffffffff815a7fc2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/ext4/super.c (ffffffff815c2b66)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/ext4/xattr.c (ffffffff815d2b86)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/ext4/fast_commit.c (ffffffff815d46bf)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_init_inode
  - fs/ext4/fast_commit.c:ext4_end_buffer_io_sync
```
```
In fs/ext4/orphan.c (ffffffff815d88ab)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
```
```
In fs/ext4/verity.c (ffffffff815da608)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In fs/ext4/crypto.c (ffffffff815db17e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_set_context
```
```
In fs/jbd2/transaction.c (ffffffff815de735)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff815dff5c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/revoke.c (ffffffff815e3c76)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff815ebfb9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/hugetlbfs/inode.c (ffffffff815f6a79)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff8160cc75)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/fuse/dev.c (ffffffff8161a6e0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/dir.c (ffffffff81621b45)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff816279e1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
```
```
In ipc/util.c (ffffffff8163c6ac)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In security/keys/gc.c (ffffffff8164dcf9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/tomoyo/common.c (ffffffff816a87b6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/apparmor/policy_unpack.c (ffffffff816d1209)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff816f4792)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
```
```
In security/integrity/ima/ima_appraise.c (ffffffff81700705)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/ima/ima_appraise.c:xattr_verify
```
```
In security/integrity/evm/evm_crypto.c (ffffffff817029c8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_set_key
```
```
In block/blk-core.c (ffffffff81731f68)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_clear
```
```
In block/blk-mq.c (ffffffff81745731)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_online
  - block/blk-mq.c:blk_mq_start_stopped_hw_queue
  - block/blk-mq.c:blk_mq_start_hw_queues
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:flush_busy_ctx
```
```
In block/blk-mq-sched.c (ffffffff8174e2c5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_restart
```
```
In block/partitions/core.c (ffffffff81754e92)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In io_uring/io_uring.c (ffffffff8179236f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:__io_cqring_overflow_flush
  - io_uring/io_uring.c:io_cqring_overflow_kill
```
```
In io_uring/sqpoll.c (ffffffff8179a958)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread_unpark
```
```
In io_uring/io-wq.c (ffffffff817a55df)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker_affinity
  - io_uring/io-wq.c:io_wqe_enqueue
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_worker_cancel_cb
```
```
In lib/rhashtable.c (ffffffff817da3ba)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff8189eaa8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_enable
  - lib/irq_poll.c:irq_poll_disable
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818b305b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818b560f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_init_irq_valid_mask
```
```
In drivers/gpio/gpiolib.c (ffffffff818ba57a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c487b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff818c8973)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
```
```
In drivers/pwm/sysfs.c (ffffffff818d1165)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pwm/sysfs.c:pwm_export_child
```
```
In drivers/pci/bus.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/pci/remove.c (ffffffff818d985a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/pci/pcie/dpc.c (ffffffff818fe990)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81922e44)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff8192394a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81927f6b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_unmap_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
```
```
In drivers/idle/intel_idle.c (ffffffff81952701)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff81967245)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_unmask_events
```
```
In drivers/acpi/numa/hmat.c (ffffffff819db801)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
```
In drivers/acpi/battery.c (ffffffff819dd990)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81a05176)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_release_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81a17494)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
```
```
In drivers/xen/grant-table.c (ffffffff81a19397)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
```
```
In drivers/xen/balloon.c (ffffffff81a1b3ec)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
```
```
In drivers/xen/events/events_2l.c (ffffffff81a22835)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_bind_to_cpu
  - drivers/xen/events/events_2l.c:evtchn_2l_remove
```
```
In drivers/xen/events/events_fifo.c (ffffffff81a23bff)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
```
In drivers/tty/tty_io.c (ffffffff81a4b014)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kclose
```
```
In drivers/tty/n_tty.c (ffffffff81a50288)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_write_wakeup
```
```
In drivers/tty/tty_ioctl.c (ffffffff81a527d5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
```
```
In drivers/tty/tty_ldisc.c (ffffffff81a53731)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_close
  - drivers/tty/tty_ldisc.c:tty_ldisc_open
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
```
```
In drivers/tty/tty_port.c (ffffffff81a56630)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/pty.c (ffffffff81a58640)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_open
  - drivers/tty/pty.c:pty_open
  - drivers/tty/pty.c:pty_set_lock
```
```
In drivers/tty/sysrq.c (ffffffff81a5b211)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/vt/keyboard.c (ffffffff81a61717)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81a6fa2f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_close
```
```
In drivers/tty/serial/serial_core.c (ffffffff81a78140)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
```
In drivers/tty/serial/max310x.c (ffffffff81a89c44)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81a9146c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
```
In drivers/char/agp/generic.c (ffffffff81a9e185)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff81aa60e5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_release
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81aadb55)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac4bab)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:domain_detach_iommu
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
```
```
In drivers/base/cacheinfo.c (ffffffff81af726b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
```
```
In drivers/base/power/domain.c (ffffffff81b0c5f6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/block/loop.c (ffffffff81b2d8ca)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81b53693)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
```
```
In drivers/nvdimm/region_devs.c (ffffffff81b579d2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/label.c (ffffffff81b5dcca)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_alloc_slot
```
```
In drivers/nvdimm/security.c (ffffffff81b63e14)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/dax/super.c (ffffffff81b65bbc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/dax/super.c:kill_dax
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b818fe)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81b86fb2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
```
```
In drivers/scsi/sr.c (ffffffff81b98c59)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_free_disk
```
```
In drivers/net/tun.c (ffffffff81bea7f6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c01955)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_port_txon
```
```
In drivers/net/xen-netfront.c (ffffffff81c07cb5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_open
```
```
In drivers/usb/core/hub.c (ffffffff81c1ace1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect_change
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:release_devnum
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff81c1ea69)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_stop_hcd
  - drivers/usb/core/hcd.c:usb_stop_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
```
```
In drivers/usb/core/sysfs.c (ffffffff81c2de84)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
```
```
In drivers/usb/core/devio.c (ffffffff81c2ee9b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81c49df1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff842b20ee)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff842b2180)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/ohci-hcd.c:ohci_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff842b2234)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In drivers/usb/host/xhci.c (ffffffff81c7821d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_shutdown
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81c91711)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_usb2_port_status
```
```
In drivers/input/mousedev.c (ffffffff81cad634)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_key_event
  - drivers/input/mousedev.c:mousedev_key_event
```
```
In drivers/rtc/class.c (ffffffff81cb9807)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
```
```
In drivers/rtc/dev.c (ffffffff81cbdda4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81cc0ff3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ccf483)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81ceae67)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_offline
```
```
In drivers/watchdog/watchdog_core.c (ffffffff81ceba2a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81cecd1c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/watchdog/watchdog_dev.c:watchdog_write
  - drivers/watchdog/watchdog_dev.c:watchdog_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_stop
```
```
In drivers/md/md.c (ffffffff81cf7531)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_written
```
```
In drivers/md/md-bitmap.c (ffffffff81d0686c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_unplug
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
```
```
In drivers/md/dm-zone.c (ffffffff81d0a3b0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
```
```
In drivers/md/dm.c (ffffffff81d0ec87)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:unlock_fs
  - drivers/md/dm.c:dm_cancel_deferred_remove
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d30984)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
  - drivers/cpufreq/cpufreq.c:remove_cpu_dev_symlink
```
```
In drivers/cpuidle/poll_state.c (ffffffff820d5862)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In drivers/leds/led-core.c (ffffffff81d5e951)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_blink_set_oneshot
  - drivers/leds/led-core.c:led_blink_set_oneshot
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/firmware/efi/efi.c (ffffffff83f0737c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
```
In drivers/firmware/efi/memmap.c (ffffffff83f08a24)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
```
In drivers/hte/hte.c (ffffffff81d90410)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_do_cb_work
  - drivers/hte/hte.c:hte_ts_dis_en_common
  - drivers/hte/hte.c:hte_ts_put
```
```
In net/core/sock.c (ffffffff81d9a006)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
```
```
In net/core/stream.c (ffffffff81db0fa8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_write_space
```
```
In net/core/dev.c (ffffffff81dbcdc7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/dev.c:napi_disable
  - net/core/dev.c:dev_set_threaded
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
```
```
In net/core/link_watch.c (ffffffff81dea886)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/xdp.c (ffffffff81e064fc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/core/netpoll.c (ffffffff81e11f02)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
```
```
In net/core/skmsg.c (ffffffff81e4851c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_stop
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/sched/sch_generic.c (ffffffff81e52ca3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_activate
  - net/sched/sch_generic.c:dev_activate
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:qdisc_maybe_clear_missed
```
```
In net/netlink/af_netlink.c (ffffffff81e68a33)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
```
```
In net/netlink/genetlink.c (ffffffff81e70250)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
```
```
In net/ethtool/linkmodes.c (ffffffff81e808b0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_auto_linkmodes
```
```
In net/ipv4/tcp.c (ffffffff81eae6b9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_output.c (ffffffff81ec98eb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/ipv4/tcp_ulp.c (ffffffff81eda764)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0a76f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f2066c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f26851)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
```
```
In net/ipv4/udp_bpf.c (ffffffff81f28645)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f33335)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81f4a62a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
```
```
In net/unix/unix_bpf.c (ffffffff81f516e2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_stream_bpf_update_proto
  - net/unix/unix_bpf.c:unix_stream_bpf_update_proto
  - net/unix/unix_bpf.c:unix_dgram_bpf_update_proto
  - net/unix/unix_bpf.c:unix_dgram_bpf_update_proto
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
```
In net/ipv6/ioam6.c (ffffffff81fa995e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81fae27f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbea52)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81fe64eb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
```
```
In net/ncsi/ncsi-manage.c (ffffffff81fea040)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
```
In net/mptcp/protocol.c (ffffffff81ffbc8e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
```
```
In lib/nmi_backtrace.c (ffffffff82039105)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In arch/x86/events/amd/ibs.c (ffffffff8100eb49)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/intel/core.c (ffffffff81016186)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dead
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103bede)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
```
```
In arch/x86/xen/smp_pv.c (ffffffff8104415f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:_get_smp_config
  - arch/x86/xen/smp_pv.c:_get_smp_config
```
```
In arch/x86/kernel/process_64.c (ffffffff8104b58f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff8213d28c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
```
```
In arch/x86/kernel/ioport.c (ffffffff810519f5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff82143012)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81062d0a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu_clone
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810646e2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81065281)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/kernel/ptrace.c (ffffffff81066a7c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81069367)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:set_task_blockstep
  - arch/x86/kernel/step.c:enable_single_step
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106a2cf)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_ap_offline
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81070831)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81071840)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81078b0e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_apply_quirks
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107bde7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810861f5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108dbce)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81093369)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_free_va_slot
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81096004)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff81098490)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:release_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:release_perfctr_nmi
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81099af4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff82143112)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smp.c (ffffffff8109b8de)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_stop_other_cpus
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109cd27)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
```
```
In arch/x86/kernel/mpparse.c (ffffffff836ae67e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:MP_bus_info
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810ac5fe)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff810ba23b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/init_64.c (ffffffff82149435)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In arch/x86/mm/tlb.c (ffffffff810cc077)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d6bce)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/mm/numa.c (ffffffff810d793b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In arch/x86/platform/efi/quirks.c (ffffffff810e2e13)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
```
```
In arch/x86/platform/efi/efi.c (ffffffff836c713d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e93a8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/fork.c (ffffffff810f3e59)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/cpu.c (ffffffff810f9c95)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_reset_state
```
```
In kernel/exit.c (ffffffff810fb6df)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
```
```
In kernel/softirq.c (ffffffff810ff41a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/ptrace.c (ffffffff81108b80)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff81111e53)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/sys.c (ffffffff8111af3e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/workqueue.c (ffffffff8112249c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
```
```
In kernel/kthread.c (ffffffff81129aa4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_set_per_cpu
```
```
In kernel/vhost_task.c (ffffffff81139298)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/vhost_task.c:vhost_task_fn
```
```
In kernel/sched/core.c (ffffffff81152372)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_mm_cid_before_execve
  - kernel/sched/core.c:sched_mm_cid_remote_clear
  - kernel/sched/core.c:sched_mm_cid_migrate_to
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:mm_cid_get
```
```
In kernel/sched/fair.c (ffffffff81157ce2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/sched/build_policy.c (ffffffff811714ed)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:rq_offline_dl
  - kernel/sched/build_policy.c:cpudl_clear_freecpu
  - kernel/sched/build_policy.c:cpudl_set
  - kernel/sched/build_policy.c:cpudl_find
  - kernel/sched/build_policy.c:rq_offline_rt
  - kernel/sched/build_policy.c:do_idle
  - kernel/sched/build_policy.c:cpuidle_idle_call
  - kernel/sched/build_policy.c:default_idle_call
```
```
In kernel/sched/build_utility.c (ffffffff8118a0b3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_domains_numa_masks_clear
  - kernel/sched/build_utility.c:rq_attach_root
  - kernel/sched/build_utility.c:cpupri_set
  - kernel/sched/build_utility.c:cpupri_find_fitness
```
```
In kernel/power/snapshot.c (ffffffff8119598f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_clear_bit
```
```
In kernel/irq/chip.c (ffffffff811adc5f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/generic-chip.c (ffffffff811afae6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
```
In kernel/irq/irq_sim.c (ffffffff811b3061)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:irq_sim_handle_irq
  - kernel/irq/irq_sim.c:irq_sim_set_irqchip_state
```
```
In kernel/irq/matrix.c (ffffffff811b9ba5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_remove_managed
```
```
In kernel/livepatch/transition.c (ffffffff811d286e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_copy_process
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/entry/common.c (ffffffff811d94df)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff811d9750)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:task_set_syscall_user_dispatch
```
```
In kernel/entry/kvm.c (ffffffff811d9b5f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
```
```
In kernel/profile.c (ffffffff811e5a75)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/clocksource.c (ffffffff811f5067)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-broadcast.c (ffffffff81203267)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/kexec_core.c (ffffffff812138b0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/kexec_core.c:__crash_shrink_memory
  - kernel/kexec_core.c:kimage_free_pages
```
```
In kernel/cgroup/cgroup.c (ffffffff81224d9f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_kill
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812281e5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/cgroup/freezer.c (ffffffff8122a83b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/cgroup/cpuset.c (ffffffff81232b0e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/pid_namespace.c (ffffffff8123918c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffffffff8124649a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/watchdog.c (ffffffff8125e64f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/tracepoint.c (ffffffff81267fcf)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/trace/trace.c (ffffffff8127b195)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace.c:close_pipe_on_cpu
```
```
In kernel/trace/pid_list.c (ffffffff8128eace)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/pid_list.c:trace_pid_list_clear
```
```
In kernel/trace/trace_osnoise.c (ffffffff812974c4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:osnoise_options_write
```
```
In kernel/trace/trace_events.c (ffffffff812a408a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:trace_event_enable_tgid_record
  - kernel/trace/trace_events.c:trace_event_enable_cmd_record
```
```
In kernel/trace/trace_syscalls.c (ffffffff812a8ffa)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812ae0e3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger
  - kernel/trace/trace_events_trigger.c:update_cond_flag
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/trace/trace_events_user.c (ffffffff812c57e0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_enabler_write
  - kernel/trace/trace_events_user.c:user_event_enabler_write
  - kernel/trace/trace_events_user.c:user_event_enabler_fault_fixup
```
```
In kernel/bpf/offload.c (ffffffff813512b9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/bpf/cpumask.c (ffffffff8135d7a3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_clear_cpu
```
```
In kernel/events/core.c (ffffffff813657c1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In kernel/events/ring_buffer.c (ffffffff8137bbf6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137e609)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81383da1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/user-return-notifier.c (ffffffff813843af)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/filemap.c (ffffffff8138e7f3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/filemap.c:filemap_read_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:folio_end_writeback
  - mm/filemap.c:folio_end_private_2
  - mm/filemap.c:folio_wake_bit
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/oom_kill.c (ffffffff8139775e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/page-writeback.c (ffffffff8139ce39)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_cancel_dirty
  - mm/page-writeback.c:folio_mark_dirty
```
```
In mm/readahead.c (ffffffff8139ee8d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/swap.c (ffffffff813a22bd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:lru_add_fn
```
```
In mm/truncate.c (ffffffff813a3f8e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_folio
```
```
In mm/vmscan.c (ffffffff813aff73)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:prepare_kswapd_sleep
  - mm/vmscan.c:prepare_kswapd_sleep
  - mm/vmscan.c:prepare_kswapd_sleep
  - mm/vmscan.c:prepare_kswapd_sleep
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:should_skip_mm
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:shrink_slab_memcg
```
```
In mm/shmem.c (ffffffff813c2c89)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_writepage
```
```
In mm/vmstat.c (ffffffff813c83e5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/percpu.c (ffffffff836e350c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/gup.c (ffffffff813e35d2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
```
```
In mm/memory.c (ffffffff813ecff6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
```
```
In mm/mlock.c (ffffffff813f8c8e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
```
```
In mm/rmap.c (ffffffff8140f752)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:folio_referenced_one
```
```
In mm/page_alloc.c (ffffffff81422c14)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/memory_hotplug.c (ffffffff81424ebc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/madvise.c (ffffffff81427a38)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff8142986f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:sio_write_complete
  - mm/page_io.c:__end_swap_bio_read
  - mm/page_io.c:__end_swap_bio_write
```
```
In mm/swap_state.c (ffffffff8142b987)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/frontswap.c (ffffffff81434b97)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/hugetlb.c (ffffffff81446811)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:isolate_hugetlb
  - mm/hugetlb.c:hugetlb_add_to_page_cache
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:restore_reserve_on_error
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In mm/hugetlb_vmemmap.c (ffffffff81447aef)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_restore
```
```
In mm/mempolicy.c (ffffffff8144a74c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/ksm.c (ffffffff81457d30)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_disable_merge_any
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/slub.c (ffffffff8145fece)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
```
```
In mm/migrate.c (ffffffff8146888e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/memory-tiers.c (ffffffff821503db)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory-tiers.c:memtier_hotplug_callback
```
```
In mm/migrate_device.c (ffffffff8146fb70)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8147933f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:use_zero_page_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
```
```
In mm/khugepaged.c (ffffffff8148049b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff8148a75f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memcontrol.c:drain_local_stock
```
```
In mm/memory-failure.c (ffffffff81499159)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffffffff8149e3a8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/page_idle.c (ffffffff814a29be)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In mm/bootmem_info.c (ffffffff814a785d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/exec.c (ffffffff814bb7cb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/fs-writeback.c (ffffffff814f7c6b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_io_lists_depopulated
```
```
In fs/buffer.c (ffffffff8150a6a8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:folio_zero_new_buffers
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:__bforget
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/mpage.c (ffffffff8150effb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/crypto/crypto.c (ffffffff8153340f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/verity/verify.c (ffffffff8153da77)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/verity/verify.c:is_hash_block_verified
```
```
In fs/mbcache.c (ffffffff8154c481)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/coredump.c (ffffffff8154f60b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/iomap/buffered-io.c (ffffffff8155705f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/quota/dquot.c (ffffffff8155ab12)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_decr_space
  - fs/quota/dquot.c:dquot_decr_inodes
  - fs/quota/dquot.c:dquot_release
```
```
In fs/proc/task_mmu.c (ffffffff81567372)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/proc/base.c (ffffffff8156e0f4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/proc/base.c:proc_coredump_filter_write
```
```
In fs/ext4/balloc.c (ffffffff8158f116)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_wait_block_bitmap
```
```
In fs/ext4/dir.c (ffffffff81592117)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8159377a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_get_access
```
```
In fs/ext4/extents_status.c (ffffffff815a0fb8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
```
```
In fs/ext4/file.c (ffffffff815a29b5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff815a49d2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/ext4/inline.c (ffffffff815afdd8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff815bc457)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_journalled_invalidate_folio
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_process_folio
  - fs/ext4/inode.c:mpage_process_folio
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:write_end_fn
  - fs/ext4/inode.c:write_end_fn
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:do_journal_get_write_access
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff815bcdac)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mballoc.c (ffffffff815c6e76)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/migrate.c (ffffffff815cea00)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/mmp.c (ffffffff815ceb28)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffffffff815d867a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/page-io.c (ffffffff815daed5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff815db0cf)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/ext4/resize.c (ffffffff815de842)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/ext4/super.c (ffffffff815fa2c6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/ext4/xattr.c (ffffffff8160a699)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/ext4/fast_commit.c (ffffffff8160c2af)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_init_inode
  - fs/ext4/fast_commit.c:ext4_end_buffer_io_sync
```
```
In fs/ext4/orphan.c (ffffffff8161039b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
```
```
In fs/ext4/verity.c (ffffffff816123db)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In fs/ext4/crypto.c (ffffffff81612c2e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_set_context
```
```
In fs/jbd2/transaction.c (ffffffff81616199)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81617275)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/revoke.c (ffffffff8161b436)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff81623a99)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/hugetlbfs/inode.c (ffffffff8162eb39)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff81644ada)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/fuse/dev.c (ffffffff816529dc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/dir.c (ffffffff81659f9b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff8165fdb7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
```
```
In ipc/util.c (ffffffff81674a71)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In security/keys/gc.c (ffffffff816864ae)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/tomoyo/common.c (ffffffff816e1202)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/apparmor/policy_unpack.c (ffffffff8170a119)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff8172e8b2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
```
```
In security/integrity/ima/ima_appraise.c (ffffffff8173a7a5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/ima/ima_appraise.c:xattr_verify
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8173c9f8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_set_key
```
```
In block/blk-core.c (ffffffff8176e378)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_clear
```
```
In block/blk-mq.c (ffffffff817816b1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_online
  - block/blk-mq.c:blk_mq_start_stopped_hw_queue
  - block/blk-mq.c:blk_mq_start_hw_queues
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:flush_busy_ctx
```
```
In block/blk-mq-sched.c (ffffffff8178a805)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_restart
```
```
In block/genhd.c (ffffffff8178c9fe)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/genhd.c:disk_scan_partitions
```
```
In block/partitions/core.c (ffffffff81790e8a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_disk_changed
```
```
In io_uring/io_uring.c (ffffffff817d2fcd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:__io_cqring_overflow_flush
  - io_uring/io_uring.c:io_cqring_overflow_kill
```
```
In io_uring/sqpoll.c (ffffffff817dba08)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread_unpark
```
```
In io_uring/io-wq.c (ffffffff817e65bf)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker_affinity
  - io_uring/io-wq.c:io_wq_enqueue
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_worker_cancel_cb
```
```
In lib/rhashtable.c (ffffffff818196c6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff818e1078)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_enable
  - lib/irq_poll.c:irq_poll_disable
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In lib/group_cpus.c (ffffffff818e6a41)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/group_cpus.c:grp_spread_init_one
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818f60ab)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818f86bf)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_init_irq_valid_mask
```
```
In drivers/gpio/gpiolib.c (ffffffff818fd67a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8190794b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8190b923)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
```
```
In drivers/pwm/sysfs.c (ffffffff81914155)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pwm/sysfs.c:pwm_export_child
```
```
In drivers/pci/bus.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/pci/remove.c (ffffffff8191cbaa)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/pci/pcie/dpc.c (ffffffff81941da0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81966b24)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff8196755a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8196c16b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_unmap_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
```
```
In drivers/idle/intel_idle.c (ffffffff82143649)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_xstate
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_irq
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/ec.c (ffffffff819ad815)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_unmask_events
```
```
In drivers/acpi/numa/hmat.c (ffffffff81a234b0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
```
In drivers/acpi/battery.c (ffffffff81a25690)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81a4dfd6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_release_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81a60524)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
```
```
In drivers/xen/grant-table.c (ffffffff81a62707)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
```
```
In drivers/xen/balloon.c (ffffffff81a64580)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
```
```
In drivers/xen/events/events_2l.c (ffffffff81a6bbc5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_bind_to_cpu
  - drivers/xen/events/events_2l.c:evtchn_2l_remove
```
```
In drivers/xen/events/events_fifo.c (ffffffff81a6d0d3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
```
In drivers/tty/tty_io.c (ffffffff81a951ef)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kclose
```
```
In drivers/tty/n_tty.c (ffffffff81a9a598)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_write_wakeup
```
```
In drivers/tty/tty_ioctl.c (ffffffff81a9cad5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
```
```
In drivers/tty/tty_ldisc.c (ffffffff81a9db91)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_close
  - drivers/tty/tty_ldisc.c:tty_ldisc_open
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
```
```
In drivers/tty/tty_port.c (ffffffff81aa0c10)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/pty.c (ffffffff81aa2c60)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_open
  - drivers/tty/pty.c:pty_open
  - drivers/tty/pty.c:pty_set_lock
```
```
In drivers/tty/sysrq.c (ffffffff81aa5856)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/vt/keyboard.c (ffffffff81aabe4b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81aba1df)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_close
```
```
In drivers/tty/serial/serial_core.c (ffffffff81ac2bf0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
```
In drivers/tty/serial/max310x.c (ffffffff81ad5423)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81adccdc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
```
In drivers/char/agp/generic.c (ffffffff81ae9b23)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff81af18e5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_release
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81afab99)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
  - drivers/char/tpm/tpm_tis_core.c:probe_itpm
  - drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b11572)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:domain_detach_iommu
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b1b73a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_del
  - drivers/iommu/intel/perfmon.c:iommu_pmu_assign_event
```
```
In drivers/base/cacheinfo.c (ffffffff81b45540)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
```
```
In drivers/base/power/domain.c (ffffffff81b5a636)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/block/loop.c (ffffffff81b7dbda)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81ba6b93)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
```
```
In drivers/nvdimm/region_devs.c (ffffffff81baaf52)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/label.c (ffffffff81bb128c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_alloc_slot
```
```
In drivers/nvdimm/security.c (ffffffff81bb7414)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/dax/super.c (ffffffff81bb91dc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/dax/super.c:kill_dax
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd5604)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81bdad92)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
```
```
In drivers/scsi/sr.c (ffffffff81bef1f9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_free_disk
```
```
In drivers/net/tun.c (ffffffff81c42c31)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/virtio_net.c (ffffffff81c4f0b6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c66e95)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_port_txon
```
```
In drivers/net/xen-netfront.c (ffffffff81c6d3c9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_open
```
```
In drivers/usb/core/hub.c (ffffffff81c81c11)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect_change
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:release_devnum
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff81c85969)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_stop_hcd
  - drivers/usb/core/hcd.c:usb_stop_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
```
```
In drivers/usb/core/sysfs.c (ffffffff81c95004)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
```
```
In drivers/usb/core/devio.c (ffffffff81c960fb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81cb140c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff83af4dce)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff83af4e60)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/ohci-hcd.c:ohci_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff83af4f14)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In drivers/usb/host/xhci.c (ffffffff81cdf2fd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_shutdown
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81cf7e21)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_usb2_port_status
  - drivers/usb/host/xhci-hub.c:xhci_handle_usb2_port_link_resume
```
```
In drivers/input/mousedev.c (ffffffff81d14c14)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_key_event
  - drivers/input/mousedev.c:mousedev_key_event
```
```
In drivers/rtc/class.c (ffffffff81d20f3e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
```
```
In drivers/rtc/dev.c (ffffffff81d256b4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81d289b3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81d37553)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81d53a77)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_offline
```
```
In drivers/watchdog/watchdog_core.c (ffffffff81d5467a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81d55a3c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/watchdog/watchdog_dev.c:watchdog_write
  - drivers/watchdog/watchdog_dev.c:watchdog_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_stop
```
```
In drivers/md/md.c (ffffffff81d5ee2d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_written
```
```
In drivers/md/md-bitmap.c (ffffffff81d6f94c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
```
```
In drivers/md/dm-zone.c (ffffffff81d734ea)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
```
```
In drivers/md/dm.c (ffffffff81d78267)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:unlock_fs
  - drivers/md/dm.c:dm_cancel_deferred_remove
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d99c04)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
  - drivers/cpufreq/cpufreq.c:remove_cpu_dev_symlink
```
```
In drivers/cpuidle/poll_state.c (ffffffff8214406e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In drivers/leds/led-core.c (ffffffff81dc98c1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_blink_set_oneshot
  - drivers/leds/led-core.c:led_blink_set_oneshot
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/firmware/efi/efi.c (ffffffff8372d442)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
```
In drivers/firmware/efi/memmap.c (ffffffff8372eb64)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
```
In drivers/hte/hte.c (ffffffff81dfe6c0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_do_cb_work
  - drivers/hte/hte.c:hte_ts_dis_en_common
  - drivers/hte/hte.c:hte_ts_put
```
```
In net/core/sock.c (ffffffff81e08736)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
```
```
In net/core/stream.c (ffffffff81e21491)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_write_space
```
```
In net/core/dev.c (ffffffff81e2d5f7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/dev.c:napi_disable
  - net/core/dev.c:dev_set_threaded
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
```
```
In net/core/link_watch.c (ffffffff81e5c066)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/xdp.c (ffffffff81e78d2d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/core/netpoll.c (ffffffff81e85813)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
```
```
In net/core/skmsg.c (ffffffff81ea3cbe)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_stop
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/sched/sch_generic.c (ffffffff81eae53a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_activate
  - net/sched/sch_generic.c:dev_activate
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:qdisc_maybe_clear_missed
```
```
In net/netlink/af_netlink.c (ffffffff81ec488f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
```
```
In net/netlink/genetlink.c (ffffffff81ecc360)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
```
```
In net/ethtool/linkmodes.c (ffffffff81edd0ea)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_auto_linkmodes
```
```
In net/ipv4/tcp.c (ffffffff81f0c752)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff81f2843b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/ipv4/tcp_ulp.c (ffffffff81f39844)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6a29f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f80143)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f86518)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
```
```
In net/ipv4/udp_bpf.c (ffffffff81f881b5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f92663)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81faa2c6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
```
```
In net/unix/unix_bpf.c (ffffffff81fb1062)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_stream_bpf_update_proto
  - net/unix/unix_bpf.c:unix_stream_bpf_update_proto
  - net/unix/unix_bpf.c:unix_dgram_bpf_update_proto
  - net/unix/unix_bpf.c:unix_dgram_bpf_update_proto
```
```
In net/ipv6/ioam6.c (ffffffff8200a2e0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff8200e9d7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201f9e5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8202dd20)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
```
```
In net/ncsi/ncsi-rsp.c (ffffffff820627f3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
```
```
In net/ncsi/ncsi-manage.c (ffffffff820661fa)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
```
In net/mptcp/protocol.c (ffffffff8207805e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
```
```
In net/handshake/request.c (ffffffff82092d19)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In lib/nmi_backtrace.c (ffffffff820b7415)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In arch/x86/events/amd/ibs.c (ffffffff81013fc9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/intel/core.c (ffffffff8101bcc6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dead
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8104239e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
```
```
In arch/x86/xen/smp_pv.c (ffffffff8104a68e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:_get_smp_config
  - arch/x86/xen/smp_pv.c:_get_smp_config
```
```
In arch/x86/kernel/process_64.c (ffffffff810527ff)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff8221f2ac)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
```
```
In arch/x86/kernel/ioport.c (ffffffff81058c15)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff822256ff)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81069ffa)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:fpregs_lock_and_load
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu_clone
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106bba2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106c8ef)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/kernel/ptrace.c (ffffffff8106defc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff810707d7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:set_task_blockstep
  - arch/x86/kernel/step.c:enable_single_step
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8107179f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_ap_offline
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81078111)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81079060)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810800be)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_apply_quirks
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8108329d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_skip_bank
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8108d0d5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81094f5e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a7d9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_free_va_slot
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109d573)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff8109fa30)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:release_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:release_perfctr_nmi
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff810a1321)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff822257fd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smp.c (ffffffff810a2e7e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_stop_other_cpus
```
```
In arch/x86/kernel/smpboot.c (ffffffff810a4267)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
```
```
In arch/x86/kernel/mpparse.c (ffffffff838debfe)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:MP_bus_info
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810b32de)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff810c15eb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/init_64.c (ffffffff8222bef5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In arch/x86/mm/tlb.c (ffffffff810d4707)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810df3fe)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/mm/numa.c (ffffffff810e01bb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In arch/x86/platform/efi/quirks.c (ffffffff810eb662)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
```
```
In arch/x86/platform/efi/efi.c (ffffffff838f7d3d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f15fb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/fork.c (ffffffff810fd228)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/cpu.c (ffffffff811030a5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_reset_state
```
```
In kernel/exit.c (ffffffff81104acd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
```
```
In kernel/softirq.c (ffffffff81108aca)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/ptrace.c (ffffffff81112510)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff8111b7f3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/sys.c (ffffffff81124a01)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/workqueue.c (ffffffff8112c354)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_pod_cpumask
```
```
In kernel/kthread.c (ffffffff811340e4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unpark
  - kernel/kthread.c:kthread_set_per_cpu
```
```
In kernel/vhost_task.c (ffffffff81144058)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/vhost_task.c:vhost_task_fn
```
```
In kernel/sched/core.c (ffffffff8115e224)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_mm_cid_before_execve
  - kernel/sched/core.c:sched_mm_cid_remote_clear
  - kernel/sched/core.c:sched_mm_cid_migrate_to
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:mm_cid_get
```
```
In kernel/sched/fair.c (ffffffff81163f32)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/sched/build_policy.c (ffffffff8117edfd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:rq_offline_dl
  - kernel/sched/build_policy.c:cpudl_clear_freecpu
  - kernel/sched/build_policy.c:cpudl_set
  - kernel/sched/build_policy.c:cpudl_find
  - kernel/sched/build_policy.c:rq_offline_rt
  - kernel/sched/build_policy.c:pick_next_task_rt
  - kernel/sched/build_policy.c:dequeue_task_rt
  - kernel/sched/build_policy.c:do_idle
  - kernel/sched/build_policy.c:cpuidle_idle_call
  - kernel/sched/build_policy.c:default_idle_call
```
```
In kernel/sched/build_utility.c (ffffffff811989b3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_domains_numa_masks_clear
  - kernel/sched/build_utility.c:rq_attach_root
  - kernel/sched/build_utility.c:cpupri_set
  - kernel/sched/build_utility.c:cpupri_find_fitness
```
```
In kernel/power/snapshot.c (ffffffff811a436f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_clear_bit
```
```
In kernel/irq/chip.c (ffffffff811bd85f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/generic-chip.c (ffffffff811bf7c6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
```
In kernel/irq/irq_sim.c (ffffffff811c2e81)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:irq_sim_handle_irq
  - kernel/irq/irq_sim.c:irq_sim_set_irqchip_state
```
```
In kernel/irq/matrix.c (ffffffff811c9a65)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_remove_managed
```
```
In kernel/rcu/tree.c (ffffffff811def99)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_spawn_cpu_nocb_kthread
  - kernel/rcu/tree.c:rcu_nocb_cpu_deoffload
```
```
In kernel/livepatch/transition.c (ffffffff811e74ee)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_copy_process
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/entry/common.c (ffffffff82223fa7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode_work
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff811ef400)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:task_set_syscall_user_dispatch
```
```
In kernel/entry/kvm.c (ffffffff811ef80f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
```
```
In kernel/profile.c (ffffffff811fb7c5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/clocksource.c (ffffffff8120b207)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-broadcast.c (ffffffff81219827)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/time/tick-sched.c (ffffffff839058c4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_init
```
```
In kernel/kexec_core.c (ffffffff8122b80f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/kexec_core.c:__crash_shrink_memory
  - kernel/kexec_core.c:kimage_free_pages
```
```
In kernel/cgroup/cgroup.c (ffffffff8123ca8f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_kill
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8123ffe5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/cgroup/freezer.c (ffffffff812427fb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/cgroup/cpuset.c (ffffffff8124c28e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:reset_partition_data
  - kernel/cgroup/cpuset.c:update_partition_sd_lb
```
```
In kernel/pid_namespace.c (ffffffff81252e5c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffffffff8126032a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/watchdog.c (ffffffff812785db)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_hardlockup_check
```
```
In kernel/tracepoint.c (ffffffff81281f8f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/trace/trace.c (ffffffff81295d75)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace.c:close_pipe_on_cpu
```
```
In kernel/trace/pid_list.c (ffffffff812a9f9e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/pid_list.c:trace_pid_list_clear
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b2b14)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:osnoise_options_write
```
```
In kernel/trace/trace_events.c (ffffffff812bf9ea)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:trace_event_enable_tgid_record
  - kernel/trace/trace_events.c:trace_event_enable_cmd_record
```
```
In kernel/trace/trace_syscalls.c (ffffffff812c4d0a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812ca603)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger
  - kernel/trace/trace_events_trigger.c:update_cond_flag
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/trace/trace_events_user.c (ffffffff812e2022)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_enabler_write
  - kernel/trace/trace_events_user.c:user_event_enabler_write
  - kernel/trace/trace_events_user.c:user_event_enabler_fault_fixup
```
```
In kernel/bpf/offload.c (ffffffff81378719)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/bpf/cpumask.c (ffffffff81386543)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_clear_cpu
```
```
In kernel/events/core.c (ffffffff8138e8e1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In kernel/events/ring_buffer.c (ffffffff813a4e36)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a7869)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff813ad1f1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/user-return-notifier.c (ffffffff813ad7bf)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/filemap.c (ffffffff813b7eb3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/filemap.c:filemap_read_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:folio_end_writeback
  - mm/filemap.c:folio_end_private_2
  - mm/filemap.c:folio_wake_bit
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/oom_kill.c (ffffffff813c158e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/page-writeback.c (ffffffff813c6b29)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_cancel_dirty
  - mm/page-writeback.c:folio_mark_dirty
```
```
In mm/readahead.c (ffffffff813c8aec)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/swap.c (ffffffff813cbf35)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:lru_add_fn
```
```
In mm/truncate.c (ffffffff813cdb0d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_folio
```
```
In mm/vmscan.c (ffffffff813d945e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:prepare_kswapd_sleep
  - mm/vmscan.c:prepare_kswapd_sleep
  - mm/vmscan.c:prepare_kswapd_sleep
  - mm/vmscan.c:prepare_kswapd_sleep
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
```
```
In mm/shrinker.c (ffffffff813e4abb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/shrinker.c:shrink_slab_memcg
  - mm/shrinker.c:shrink_slab_memcg
```
```
In mm/shmem.c (ffffffff813ed922)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_writepage
```
```
In mm/vmstat.c (ffffffff813f2dd5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/percpu.c (ffffffff83915d9c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/shmem_quota.c (ffffffff81408df5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/shmem_quota.c:shmem_release_dquot
```
```
In mm/gup.c (ffffffff8140ddf2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
```
```
In mm/memory.c (ffffffff814185a0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory.c:copy_present_pte
```
```
In mm/mlock.c (ffffffff81424849)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
```
```
In mm/rmap.c (ffffffff8143c0cb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/rmap.c:hugetlb_add_new_anon_rmap
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:folio_referenced_one
```
```
In mm/page_alloc.c (ffffffff8144faf4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:__drain_all_pages
```
```
In mm/memory_hotplug.c (ffffffff814520fc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/slub.c (ffffffff8145d26e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:free_partial
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:___slab_alloc
```
```
In mm/madvise.c (ffffffff8146124c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff814631a4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_io.c:sio_write_complete
  - mm/page_io.c:__end_swap_bio_write
```
```
In mm/swap_state.c (ffffffff814650eb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/hugetlb.c (ffffffff814802b4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:isolate_hugetlb
  - mm/hugetlb.c:hugetlb_add_to_page_cache
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:restore_reserve_on_error
  - mm/hugetlb.c:free_huge_folio
  - mm/hugetlb.c:free_huge_folio
  - mm/hugetlb.c:update_and_free_pages_bulk
  - mm/hugetlb.c:bulk_vmemmap_restore_error
  - mm/hugetlb.c:bulk_vmemmap_restore_error
  - mm/hugetlb.c:__update_and_free_hugetlb_folio
  - mm/hugetlb.c:__remove_hugetlb_folio
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In mm/hugetlb_vmemmap.c (ffffffff81480856)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:__hugetlb_vmemmap_optimize_folio
  - mm/hugetlb_vmemmap.c:__hugetlb_vmemmap_restore_folio
```
```
In mm/mempolicy.c (ffffffff8148419d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/ksm.c (ffffffff81492800)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_disable_merge_any
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/migrate.c (ffffffff81497f7f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/memory-tiers.c (ffffffff8223321b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory-tiers.c:memtier_hotplug_callback
```
```
In mm/migrate_device.c (ffffffff8149e241)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a88a7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:thpsize_enabled_store
  - mm/huge_memory.c:thpsize_enabled_store
  - mm/huge_memory.c:thpsize_enabled_store
  - mm/huge_memory.c:thpsize_enabled_store
  - mm/huge_memory.c:thpsize_enabled_store
  - mm/huge_memory.c:thpsize_enabled_store
  - mm/huge_memory.c:thpsize_enabled_store
  - mm/huge_memory.c:thpsize_enabled_store
  - mm/huge_memory.c:thpsize_enabled_store
  - mm/huge_memory.c:use_zero_page_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
```
```
In mm/khugepaged.c (ffffffff814ae5aa)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff814ba00f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memcontrol.c:drain_local_stock
```
```
In mm/memory-failure.c (ffffffff814c8855)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:folio_clear_hugetlb_hwpoison
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffffffff814cd4d9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/page_idle.c (ffffffff814d385b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In mm/bootmem_info.c (ffffffff814d888d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/exec.c (ffffffff814edd3b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/fs-writeback.c (ffffffff8152c3bb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_io_lists_depopulated
```
```
In fs/buffer.c (ffffffff8153f658)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:__block_commit_write
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:folio_zero_new_buffers
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:__bforget
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/mpage.c (ffffffff81543830)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/crypto/crypto.c (ffffffff81568337)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/verity/verify.c (ffffffff81572ed7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/verity/verify.c:is_hash_block_verified
```
```
In fs/mbcache.c (ffffffff815822b1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/coredump.c (ffffffff8158544b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/iomap/buffered-io.c (ffffffff8158d596)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:ifs_free
```
```
In fs/quota/dquot.c (ffffffff815912d2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:do_set_dqblk
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_decr_space
  - fs/quota/dquot.c:dquot_decr_inodes
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:quota_release_workfn
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/dquot.c:dquot_release
```
```
In fs/proc/task_mmu.c (ffffffff8159d8f2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/proc/base.c (ffffffff815a6a84)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/proc/base.c:proc_coredump_filter_write
```
```
In fs/ext4/balloc.c (ffffffff815c7e26)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_wait_block_bitmap
```
```
In fs/ext4/dir.c (ffffffff815cae87)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff815cc46a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_get_access
```
```
In fs/ext4/extents_status.c (ffffffff815d9d18)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
```
```
In fs/ext4/file.c (ffffffff815db6b2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (ffffffff815dd811)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/ext4/inline.c (ffffffff815e8b88)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff815f5237)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_journalled_invalidate_folio
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_process_folio
  - fs/ext4/inode.c:mpage_process_folio
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:write_end_fn
  - fs/ext4/inode.c:write_end_fn
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:do_journal_get_write_access
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff815f5b85)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mballoc.c (ffffffff81601da8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/migrate.c (ffffffff81607280)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/mmp.c (ffffffff816073a8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffffffff81610cbe)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/page-io.c (ffffffff816136f9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff816172f2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/ext4/super.c (ffffffff81632ec6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:update_super_work
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/ext4/xattr.c (ffffffff8164344e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/ext4/fast_commit.c (ffffffff8164506f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_init_inode
  - fs/ext4/fast_commit.c:ext4_end_buffer_io_sync
```
```
In fs/ext4/orphan.c (ffffffff8164915b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
```
```
In fs/ext4/verity.c (ffffffff8164b0ab)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In fs/ext4/crypto.c (ffffffff8164b9ae)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_set_context
```
```
In fs/jbd2/transaction.c (ffffffff8164efb6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81650090)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/revoke.c (ffffffff81654356)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff8165cb39)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/hugetlbfs/inode.c (ffffffff81667fec)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff8167e007)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/fuse/dev.c (ffffffff8168bfec)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/dir.c (ffffffff81693c1c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff81699c17)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
```
```
In ipc/util.c (ffffffff816b0e31)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In security/keys/gc.c (ffffffff816c28af)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/tomoyo/common.c (ffffffff8171de82)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/apparmor/policy_unpack.c (ffffffff81747c19)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff8176f212)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
```
```
In security/integrity/ima/ima_appraise.c (ffffffff8177b2dd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/ima/ima_appraise.c:xattr_verify
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8177d7f8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_set_key
```
```
In block/blk-core.c (ffffffff817b0598)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_clear
```
```
In block/blk-mq.c (ffffffff817c3691)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_online
  - block/blk-mq.c:blk_mq_start_stopped_hw_queue
  - block/blk-mq.c:blk_mq_start_hw_queues
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:flush_busy_ctx
```
```
In block/blk-mq-sched.c (ffffffff817ccf65)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_restart
```
```
In block/genhd.c (ffffffff817cf1cc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/genhd.c:disk_scan_partitions
```
```
In block/partitions/core.c (ffffffff817d49f4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_disk_changed
```
```
In io_uring/io_uring.c (ffffffff818162eb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:__io_cqring_overflow_flush
  - io_uring/io_uring.c:io_cqring_overflow_kill
```
```
In io_uring/sqpoll.c (ffffffff8181fd88)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread_unpark
```
```
In io_uring/io-wq.c (ffffffff8182c37f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker_affinity
  - io_uring/io-wq.c:io_wq_enqueue
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_worker_cancel_cb
```
```
In lib/rhashtable.c (ffffffff8185ea16)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff81927be8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_enable
  - lib/irq_poll.c:irq_poll_disable
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In lib/group_cpus.c (ffffffff8192da61)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/group_cpus.c:grp_spread_init_one
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8193dd1d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8193f40f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_init_irq_valid_mask
```
```
In drivers/gpio/gpiolib.c (ffffffff81944c11)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81950df1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81953643)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
```
```
In drivers/pwm/sysfs.c (ffffffff8195c0c4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pwm/sysfs.c:pwm_export_child
```
```
In drivers/pci/bus.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/pci/remove.c (ffffffff81964fda)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/pci/pcie/dpc.c (ffffffff8198b030)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/pcie/dpc.c:dpc_reset_link
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff819b0234)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff819b0c8a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff819b59cb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_unmap_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
```
```
In drivers/idle/intel_idle.c (ffffffff82225d59)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_xstate
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_irq
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/ec.c (ffffffff819f7c95)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_unmask_events
```
```
In drivers/acpi/numa/hmat.c (ffffffff81a6e328)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_update_target_attrs
  - drivers/acpi/numa/hmat.c:hmat_update_target_attrs
```
```
In drivers/acpi/battery.c (ffffffff81a704d0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81a99c76)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_release_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
```
```
In drivers/pmdomain/core.c (ffffffff81aa2096)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81ab2d64)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
```
```
In drivers/xen/grant-table.c (ffffffff81ab4f37)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
```
```
In drivers/xen/balloon.c (ffffffff81ab6de0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
```
```
In drivers/xen/events/events_2l.c (ffffffff81abdc65)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_bind_to_cpu
  - drivers/xen/events/events_2l.c:evtchn_2l_remove
```
```
In drivers/xen/events/events_fifo.c (ffffffff81abf19f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
```
In drivers/tty/tty_io.c (ffffffff81ae7bcd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kclose
```
```
In drivers/tty/n_tty.c (ffffffff81aed0bb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_write_wakeup
```
```
In drivers/tty/tty_ioctl.c (ffffffff81aef5a5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
```
```
In drivers/tty/tty_ldisc.c (ffffffff81af0681)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_close
  - drivers/tty/tty_ldisc.c:tty_ldisc_open
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
```
```
In drivers/tty/tty_port.c (ffffffff81af3670)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/pty.c (ffffffff81af55d0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_open
  - drivers/tty/pty.c:pty_open
  - drivers/tty/pty.c:pty_set_lock
```
```
In drivers/tty/sysrq.c (ffffffff81af82a6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/vt/keyboard.c (ffffffff81afe9eb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81b0cf0f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_close
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b14bc4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
```
In drivers/tty/serial/max310x.c (ffffffff81b28772)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81b3009c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
```
In drivers/char/agp/generic.c (ffffffff81b3cfb3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff81b44e45)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_release
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81b4e229)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
  - drivers/char/tpm/tpm_tis_core.c:probe_itpm
  - drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b65935)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:domain_detach_iommu
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b7126a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_del
  - drivers/iommu/intel/perfmon.c:iommu_pmu_assign_event
```
```
In drivers/base/cacheinfo.c (ffffffff81b9d5c0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
```
```
In drivers/block/loop.c (ffffffff81bd1b46)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81bfae43)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
```
```
In drivers/nvdimm/region_devs.c (ffffffff81bff292)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/label.c (ffffffff81c0574c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_alloc_slot
```
```
In drivers/nvdimm/security.c (ffffffff81c0ba64)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/dax/super.c (ffffffff81c0d83f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/dax/super.c:kill_dax
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c2a25c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81c2fac2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
```
```
In drivers/scsi/sr.c (ffffffff81c44998)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_free_disk
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9c1f5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_put_pages
  - drivers/gpu/drm/drm_gem.c:drm_gem_get_pages
```
```
In drivers/gpu/drm/drm_mm.c (ffffffff81ca137b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mm.c:drm_mm_replace_node
  - drivers/gpu/drm/drm_mm.c:drm_mm_remove_node
```
```
In drivers/net/tun.c (ffffffff81cf82ee)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/virtio_net.c (ffffffff81d04dac)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81d21d1a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_open
```
```
In drivers/usb/core/hub.c (ffffffff81d36551)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect_change
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:release_devnum
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff81d3a029)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_stop_hcd
  - drivers/usb/core/hcd.c:usb_stop_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
```
```
In drivers/usb/core/sysfs.c (ffffffff81d49ac4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
```
```
In drivers/usb/core/devio.c (ffffffff81d4abdb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81d6611c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff83d50b7e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff83d50c10)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/ohci-hcd.c:ohci_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff83d50cc4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In drivers/usb/host/xhci.c (ffffffff81d9427d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_shutdown
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81dad751)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_usb2_port_status
  - drivers/usb/host/xhci-hub.c:xhci_handle_usb2_port_link_resume
```
```
In drivers/input/mousedev.c (ffffffff81dca834)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_key_event
  - drivers/input/mousedev.c:mousedev_key_event
```
```
In drivers/rtc/class.c (ffffffff81dd6c6e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
```
```
In drivers/rtc/dev.c (ffffffff81ddb424)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81dde7ec)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ded7d3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81e0a937)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_offline
```
```
In drivers/watchdog/watchdog_core.c (ffffffff81e0b54a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81e0c94c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/watchdog/watchdog_dev.c:watchdog_write
  - drivers/watchdog/watchdog_dev.c:watchdog_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_stop
```
```
In drivers/md/md.c (ffffffff81e1609d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:unregister_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_choose_sync_action
  - drivers/md/md.c:md_choose_sync_action
  - drivers/md/md.c:md_choose_sync_action
  - drivers/md/md.c:md_choose_sync_action
  - drivers/md/md.c:md_choose_sync_action
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:md_add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:analyze_sbs
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_written
```
```
In drivers/md/md-bitmap.c (ffffffff81e26c27)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
```
```
In drivers/md/dm-zone.c (ffffffff81e2a5f0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
```
```
In drivers/md/dm.c (ffffffff81e2f497)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:unlock_fs
  - drivers/md/dm.c:dm_cancel_deferred_remove
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81e51874)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
  - drivers/cpufreq/cpufreq.c:remove_cpu_dev_symlink
```
```
In drivers/cpuidle/poll_state.c (ffffffff8222678e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In drivers/leds/led-core.c (ffffffff81e82371)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_blink_set_oneshot
  - drivers/leds/led-core.c:led_blink_set_oneshot
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/firmware/efi/efi.c (ffffffff8396181c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
```
In drivers/firmware/efi/memmap.c (ffffffff83962f64)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
```
In drivers/hte/hte.c (ffffffff81eb56e0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_do_cb_work
  - drivers/hte/hte.c:hte_ts_dis_en_common
  - drivers/hte/hte.c:hte_ts_put
```
```
In net/core/sock.c (ffffffff81ec51a6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
```
```
In net/core/stream.c (ffffffff81edf229)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_write_space
```
```
In net/core/dev.c (ffffffff81eeb8f7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/dev.c:napi_disable
  - net/core/dev.c:dev_set_threaded
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
```
```
In net/core/link_watch.c (ffffffff81f1b446)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/xdp.c (ffffffff81f38bfd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/core/netpoll.c (ffffffff81f47743)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
```
```
In net/core/skmsg.c (ffffffff81f665be)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_stop
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/sched/sch_generic.c (ffffffff81f70fad)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_activate
  - net/sched/sch_generic.c:dev_activate
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:qdisc_maybe_clear_missed
```
```
In net/netlink/af_netlink.c (ffffffff81f87c57)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
```
```
In net/netlink/genetlink.c (ffffffff81f8f889)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
```
```
In net/ethtool/linkmodes.c (ffffffff81fa0eba)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_auto_linkmodes
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc32a6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
```
```
In net/ipv4/tcp.c (ffffffff81fd47fc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_fastopen
```
```
In net/ipv4/tcp_output.c (ffffffff81fecd2b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/ipv4/tcp_ulp.c (ffffffff81fff934)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
```
```
In net/ipv4/udp.c (ffffffff8200822e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
```
```
In net/ipv4/af_inet.c (ffffffff82019adc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff8203094f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff820467c3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204db18)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
```
```
In net/ipv4/udp_bpf.c (ffffffff8204f8d5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
```
In net/xfrm/xfrm_policy.c (ffffffff820603d3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/unix/af_unix.c (ffffffff820776e6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
```
```
In net/unix/unix_bpf.c (ffffffff8207e71a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_stream_bpf_update_proto
  - net/unix/unix_bpf.c:unix_stream_bpf_update_proto
  - net/unix/unix_bpf.c:unix_dgram_bpf_update_proto
  - net/unix/unix_bpf.c:unix_dgram_bpf_update_proto
```
```
In net/ipv6/af_inet6.c (ffffffff8207f5b9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff820ae6cc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
```
In net/ipv6/ndisc.c (ffffffff820b11d3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
```
```
In net/ipv6/raw.c (ffffffff820bbbaf)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_setsockopt
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff820d5204)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
```
```
In net/ipv6/ioam6.c (ffffffff820d9281)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff820dd967)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff820eeb15)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/packet/af_packet.c (ffffffff820fd7a0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
```
```
In net/ncsi/ncsi-rsp.c (ffffffff82135943)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
```
```
In net/ncsi/ncsi-manage.c (ffffffff821393ae)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
```
In net/mptcp/protocol.c (ffffffff8214d382)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_napi_poll
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_sendmsg
```
```
In net/mptcp/sockopt.c (ffffffff8215da93)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_ip_set
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_ip_set
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_ip_set
  - net/mptcp/sockopt.c:mptcp_setsockopt_v6
  - net/mptcp/sockopt.c:mptcp_setsockopt_v6
```
```
In net/handshake/request.c (ffffffff821695c9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In lib/nmi_backtrace.c (ffffffff821915c5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In arch/x86/entry/common.c (ffffffff81004825)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009fcc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_dead
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a6d7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102670f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102d5bd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:clear_bit
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f8b3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/kernel/process_64.c (ffffffff8102fc1c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff81031ce7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff81a7326c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:exit_thread
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e784)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81040048)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff810421d0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81043b77)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81048607)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81048c3d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d0cb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810502e7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81058eee)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105dc12)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff8106149e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:release_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:release_perfctr_nmi
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81061d99)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a73420)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106463c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/mpparse.c (ffffffff828a560d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:MP_bus_info
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d033)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff81076aae)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/init_64.c (ffffffff81a6a3cb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In arch/x86/mm/tlb.c (ffffffff810875b5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108ba85)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In arch/x86/mm/numa.c (ffffffff8108c009)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In arch/x86/platform/efi/quirks.c (ffffffff81090d0f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault
```
```
In arch/x86/platform/efi/efi.c (ffffffff828b25ae)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
```
In kernel/fork.c (ffffffff81098334)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff8109d742)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (ffffffff8109e725)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/softirq.c (ffffffff810a1024)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/ptrace.c (ffffffff810a7de6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810af95a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/sys.c (ffffffff810b7bf5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
```
In kernel/workqueue.c (ffffffff810bb0c2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/kthread.c (ffffffff810c3142)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unpark
```
```
In kernel/sched/core.c (ffffffff81a6e79d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/idle.c (ffffffff810da228)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:call_cpuidle
  - kernel/sched/idle.c:default_idle_call
```
```
In kernel/sched/fair.c (ffffffff810dd071)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/sched/rt.c (ffffffff810e83d5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810ea3a5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810ef632)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff810efb7c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
```
```
In kernel/sched/topology.c (ffffffff810f1e0d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_clear
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/power/snapshot.c (ffffffff81104e65)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
```
```
In kernel/irq/chip.c (ffffffff81113d3f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/generic-chip.c (ffffffff81114bd3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
```
In kernel/irq/affinity.c (ffffffff8111a2ae)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/irq/matrix.c (ffffffff8111b952)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_free
  - kernel/irq/matrix.c:irq_matrix_remove_managed
```
```
In kernel/livepatch/transition.c (ffffffff811269dc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/profile.c (ffffffff81129f60)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff8113fa74)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/kexec_core.c (ffffffff81152a8b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116085d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/cgroup/freezer.c (ffffffff81162369)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In kernel/cgroup/cpuset.c (ffffffff81168c31)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/pid_namespace.c (ffffffff8116bda8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffffffff81174fe9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/watchdog.c (ffffffff81188a98)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/tracepoint.c (ffffffff8118ef11)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/trace/trace.c (ffffffff811a00a5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
```
```
In kernel/trace/trace_events.c (ffffffff811b3f7a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:trace_event_enable_tgid_record
  - kernel/trace/trace_events.c:trace_event_enable_cmd_record
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b6c30)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811ba48d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger
```
```
In kernel/bpf/offload.c (ffffffff811fa4c8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/events/core.c (ffffffff812002f8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In kernel/events/ring_buffer.c (ffffffff8120fdac)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff8121518f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/user-return-notifier.c (ffffffff81215525)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/padata.c (ffffffff812165ca)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_remove_cpu
```
```
In mm/filemap.c (ffffffff8121d76d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:wake_up_page_bit
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/oom_kill.c (ffffffff81222d6e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/page-writeback.c (ffffffff81227996)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/readahead.c (ffffffff81228777)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/swap.c (ffffffff8122aa0e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_file
  - mm/swap.c:lru_cache_add_anon
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
```
```
In mm/truncate.c (ffffffff8122bb0b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff812359ac)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/shmem.c (ffffffff812385b8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/vmstat.c (ffffffff8124005c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/gup.c (ffffffff8125148b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
```
```
In mm/memory.c (ffffffff8125723a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/mlock.c (ffffffff8125ed4b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/rmap.c (ffffffff8126bad5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/page_alloc.c (ffffffff81279d99)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (ffffffff8127d08b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff8127e7c5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/swap_state.c (ffffffff8127f1ad)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/frontswap.c (ffffffff8128657d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/hugetlb.c (ffffffff81290279)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffffffff812914a5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/sparse.c (ffffffff81296023)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/ksm.c (ffffffff8129894c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/memory_hotplug.c (ffffffff812a42c4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/migrate.c (ffffffff812a9766)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812abdbe)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:single_hugepage_flag_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
```
```
In mm/khugepaged.c (ffffffff812b4910)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff812c0e50)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:drain_local_stock
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memory-failure.c (ffffffff812c3918)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffffffff812c8649)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:reset_page
  - mm/zsmalloc.c:reset_page
```
```
In mm/userfaultfd.c (ffffffff812cb21c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812cba33)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/fs-writeback.c (ffffffff8130d681)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
```
```
In fs/buffer.c (ffffffff8131996d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bforget
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
  - fs/buffer.c:unlock_buffer
```
```
In fs/mpage.c (ffffffff81323b1e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/crypto/crypto.c (ffffffff81342b0e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/coredump.c (ffffffff8135ac69)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff8135bf2a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/quota/dquot.c (ffffffff81361859)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_decr_space
  - fs/quota/dquot.c:dquot_decr_inodes
  - fs/quota/dquot.c:dquot_release
```
```
In fs/proc/task_mmu.c (ffffffff81368f1d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/proc/base.c (ffffffff8136d87a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/proc/base.c:proc_coredump_filter_write
```
```
In fs/ext4/balloc.c (ffffffff81386432)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/ext4/dir.c (ffffffff81388de4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8138a92a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/ext4/extents_status.c (ffffffff813955aa)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
```
```
In fs/ext4/file.c (ffffffff81396276)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/ext4/fsync.c (ffffffff81397da0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff813a18f0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff813ad20d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:__ext4_journalled_invalidatepage
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff813adf67)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff813b806b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/migrate.c (ffffffff813b9d1f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/mmp.c (ffffffff813b9e48)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813c24f1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/page-io.c (ffffffff813c4295)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff813c4886)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/ext4/resize.c (ffffffff813c7e50)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/ext4/super.c (ffffffff813d8575)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffffffff813e5851)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
```
In fs/ext4/verity.c (ffffffff813e7978)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In fs/jbd2/transaction.c (ffffffff813ea8db)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813eb31b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/revoke.c (ffffffff813eeba9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff813f3c6e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff813faa48)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
  - fs/hugetlbfs/inode.c:remove_huge_page
```
```
In fs/ecryptfs/mmap.c (ffffffff8140d298)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/fuse/dev.c (ffffffff8141897e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/dir.c (ffffffff8141e11d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff81422fc5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_perform_write
```
```
In ipc/util.c (ffffffff8142f416)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/keys/gc.c (ffffffff8143d166)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/tomoyo/common.c (ffffffff8147f056)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/apparmor/policy_unpack.c (ffffffff8149b29b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff814add2f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814b4865)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814b5958)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In block/blk-core.c (ffffffff814da9f8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_clear
```
```
In block/blk-mq.c (ffffffff814e8ee4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_start_hw_queue
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:flush_busy_ctx
```
```
In block/blk-mq-sched.c (ffffffff814eebbe)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_restart
```
```
In lib/rhashtable.c (ffffffff81523adf)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff81552c3e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8155ec08)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff8155f955)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81567895)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
```
```
In drivers/pwm/sysfs.c (ffffffff8156cf2f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:export_store
```
```
In drivers/pci/bus.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/pci/remove.c (ffffffff81573060)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff815a2dcd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815a5b74)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff815c8afd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/ec.c (ffffffff815d6784)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/hmat/hmat.c (ffffffff816082d5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
```
```
In drivers/dma/dmaengine.c (ffffffff8161d981)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_release_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
```
```
In drivers/xen/cpu_hotplug.c (ffffffff8162810e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/xen/grant-table.c (ffffffff81628770)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_pages_clear_private
```
```
In drivers/xen/balloon.c (ffffffff8162abb0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/events/events_2l.c (ffffffff8162e965)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_bind_to_cpu
```
```
In drivers/xen/events/events_fifo.c (ffffffff8162f45b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
```
In drivers/tty/tty_io.c (ffffffff8164a81c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kclose
```
```
In drivers/tty/n_tty.c (ffffffff8164eaff)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_write_wakeup
```
```
In drivers/tty/tty_ioctl.c (ffffffff816515a1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
```
```
In drivers/tty/tty_ldisc.c (ffffffff81651d85)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
```
```
In drivers/tty/tty_port.c (ffffffff8165391e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/pty.c (ffffffff81654eb0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_open
  - drivers/tty/pty.c:pty_open
```
```
In drivers/tty/sysrq.c (ffffffff81656d31)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/vt/keyboard.c (ffffffff8165c8d3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
```
In drivers/tty/serial/serial_core.c (ffffffff8166edee)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
```
In drivers/tty/serial/max310x.c (ffffffff8167bef1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff8167ff5c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
```
In drivers/char/misc.c (ffffffff81685f14)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_deregister
  - drivers/char/misc.c:misc_register
```
```
In drivers/char/agp/frontend.c (ffffffff8168c237)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_release
  - drivers/char/agp/frontend.c:agp_release
```
```
In drivers/char/agp/generic.c (ffffffff8168d6fc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff81694661)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_release
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8169b99d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/iommu/dmar.c (ffffffff816ac4e5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_free_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff816b01b9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_detach_iommu
```
```
In drivers/lightnvm/core.c (ffffffff816bd454)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/base/cacheinfo.c (ffffffff816cc55a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff816dc74a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81708307)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
```
```
In drivers/nvdimm/label.c (ffffffff817107a2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_alloc_slot
```
```
In drivers/nvdimm/security.c (ffffffff817164f5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/dax/super.c (ffffffff817176c8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff817295f2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8172da42)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
```
```
In drivers/scsi/sr.c (ffffffff8173a58b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_kref_release
```
```
In drivers/nvme/host/core.c (ffffffff81744b3d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_setup_discard
```
```
In drivers/nvme/host/multipath.c (ffffffff81749972)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvme/host/multipath.c:nvme_update_ns_ana_state
```
```
In drivers/nvme/host/pci.c (ffffffff8174dbc4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_setup_io_queues
  - drivers/nvme/host/pci.c:nvme_setup_io_queues
```
```
In drivers/ata/libata-scsi.c (ffffffff81761028)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_free_tag
```
```
In drivers/net/tun.c (ffffffff81784b56)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_attach
```
```
In drivers/net/xen-netfront.c (ffffffff817936a2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_create_queues
```
```
In drivers/usb/core/hub.c (ffffffff817a1e71)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff817a7caa)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
```
```
In drivers/usb/core/sysfs.c (ffffffff817b213f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
```
```
In drivers/usb/core/devio.c (ffffffff817b2e1f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817c1bcc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff82af3b43)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff82af3b81)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff82af3be3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In drivers/usb/host/xhci.c (ffffffff817ebb17)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
```
```
In drivers/usb/host/xhci-hub.c (ffffffff818002a8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
```
In drivers/input/mousedev.c (ffffffff81811560)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/rtc/dev.c (ffffffff8181b884)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/media/cec/cec-core.c (ffffffff8181ed20)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/media/cec/cec-core.c:cec_devnode_release
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81834b6f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/watchdog/watchdog_dev.c:watchdog_write
```
```
In drivers/md/md.c (ffffffff8183c35a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_written
```
```
In drivers/md/md-bitmap.c (ffffffff8184a1b0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
```
```
In drivers/md/dm.c (ffffffff8184d7aa)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_queue_flush
  - drivers/md/dm.c:dm_cancel_deferred_remove
```
```
In drivers/md/dm-kcopyd.c (ffffffff81859b71)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8186766d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a73860)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In drivers/leds/led-core.c (ffffffff8188790c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_stop_software_blink
  - drivers/leds/led-core.c:led_blink_set_oneshot
  - drivers/leds/led-core.c:led_blink_set_oneshot
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/firmware/efi/efi.c (ffffffff828fc4ec)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
```
In drivers/firmware/efi/memmap.c (ffffffff828fd369)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
```
In net/core/sock.c (ffffffff818b3596)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/stream.c (ffffffff818c2893)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_write_space
```
```
In net/core/dev.c (ffffffff818cc4b5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/dev.c:napi_disable
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
```
```
In net/core/link_watch.c (ffffffff818f1bcc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/xdp.c (ffffffff81902cd3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81903f0f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/skmsg.c (ffffffff81909dee)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/netpoll.c (ffffffff8190aa89)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/core/gro_cells.c (ffffffff81928a48)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff8192e647)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/netlink/af_netlink.c (ffffffff8193e7ec)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netlink/genetlink.c (ffffffff81942aa4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_unregister_family
```
```
In net/ipv4/tcp.c (ffffffff8196195e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_output.c (ffffffff81974815)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/ipv4/inet_fragment.c (ffffffff819a644d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819b23b1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b801f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c0d06)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (ffffffff819d2338)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/ipv6/ip6mr.c (ffffffff81a1a657)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a25948)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81a43e1a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
```
```
In net/ncsi/ncsi-manage.c (ffffffff81a469ac)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
```
In lib/nmi_backtrace.c (ffffffff81a51bc7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In lib/vsprintf.c (ffffffff81a5a7f4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In arch/x86/entry/common.c (ffffffff81002e73)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
```
In arch/x86/events/amd/uncore.c (ffffffff8100858c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_dead
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
```
In arch/x86/events/amd/ibs.c (ffffffff81008fc1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8101f0c3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/kernel/process_64.c (ffffffff8101f63c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff81021ab0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff81a2f62c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:exit_thread
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8102df84)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8102f848)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff81031890)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff810331a7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81037967)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81037fcd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103c54b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8103f772)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810490ee)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8104de94)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff810518fe)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:release_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:release_perfctr_nmi
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81052169)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a2f7d0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105492c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/mpparse.c (ffffffff8289d74f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:MP_bus_info
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105d433)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff81066a8e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/init_64.c (ffffffff81a2688d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In arch/x86/mm/tlb.c (ffffffff81076226)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8107a5a5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In arch/x86/mm/numa.c (ffffffff8107ab39)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In arch/x86/platform/efi/quirks.c (ffffffff8107f81f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault
```
```
In arch/x86/platform/efi/efi.c (ffffffff828aa720)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
```
In kernel/fork.c (ffffffff81086d7a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff8108c162)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (ffffffff8108d13c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/softirq.c (ffffffff8108fa44)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/ptrace.c (ffffffff810967b6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff8109e280)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/sys.c (ffffffff810a6535)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
```
In kernel/workqueue.c (ffffffff810a9bb2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/kthread.c (ffffffff810b1982)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unpark
```
```
In kernel/sched/core.c (ffffffff81a2ab97)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/idle.c (ffffffff810c921a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:call_cpuidle
  - kernel/sched/idle.c:default_idle_call
```
```
In kernel/sched/fair.c (ffffffff810cc081)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/sched/rt.c (ffffffff810d7f88)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810da3d5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810df6a2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff810dfbec)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
```
```
In kernel/sched/topology.c (ffffffff810e1e7d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_clear
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/power/snapshot.c (ffffffff810f6105)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
```
```
In kernel/irq/chip.c (ffffffff81104a4f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/generic-chip.c (ffffffff811058e3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
```
In kernel/irq/irq_sim.c (ffffffff8110892e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:irq_sim_handle_irq
```
```
In kernel/irq/affinity.c (ffffffff8110b31e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/irq/matrix.c (ffffffff8110c9c2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_free
  - kernel/irq/matrix.c:irq_matrix_remove_managed
```
```
In kernel/livepatch/transition.c (ffffffff8111943c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/profile.c (ffffffff8111c7f0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff811327f4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/time/tick-sched.c (ffffffff828b262e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_init
```
```
In kernel/kexec_core.c (ffffffff81145d6b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81153acd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/cgroup/freezer.c (ffffffff811555bd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In kernel/cgroup/cpuset.c (ffffffff8115be41)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/pid_namespace.c (ffffffff8115efa2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffffffff81168189)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/watchdog.c (ffffffff8117bbd8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/tracepoint.c (ffffffff81182091)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/trace/trace.c (ffffffff811930b5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
```
```
In kernel/trace/trace_events.c (ffffffff811a6d7a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:trace_event_enable_tgid_record
  - kernel/trace/trace_events.c:trace_event_enable_cmd_record
```
```
In kernel/trace/trace_syscalls.c (ffffffff811a9a20)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811ad26d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger
```
```
In kernel/bpf/offload.c (ffffffff811ed218)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/events/core.c (ffffffff811f2ef8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In kernel/events/ring_buffer.c (ffffffff81202b3c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81207eff)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/user-return-notifier.c (ffffffff81208285)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/padata.c (ffffffff8120932a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_remove_cpu
```
```
In mm/filemap.c (ffffffff8121093d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:wake_up_page_bit
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/oom_kill.c (ffffffff81215f1e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/page-writeback.c (ffffffff8121aae6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/readahead.c (ffffffff8121b8b7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/swap.c (ffffffff8121db2e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_file
  - mm/swap.c:lru_cache_add_anon
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
```
```
In mm/truncate.c (ffffffff8121ebfb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff81228a16)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/shmem.c (ffffffff8122b5b5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/vmstat.c (ffffffff8123305c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/gup.c (ffffffff8124437b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
```
```
In mm/memory.c (ffffffff81249b11)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff8125117b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/rmap.c (ffffffff8125db75)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/page_alloc.c (ffffffff8126bc89)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (ffffffff8126ef08)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff812705f5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/swap_state.c (ffffffff81270fcd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/frontswap.c (ffffffff812783dd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/hugetlb.c (ffffffff81281f09)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffffffff81283125)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/sparse.c (ffffffff81287c33)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/ksm.c (ffffffff8128a50c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/memory_hotplug.c (ffffffff81295d94)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/migrate.c (ffffffff8129b0c6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8129d92e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:single_hugepage_flag_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
```
```
In mm/khugepaged.c (ffffffff812a5971)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff812b1ea4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:drain_local_stock
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memory-failure.c (ffffffff812b4958)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffffffff812b9689)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:reset_page
  - mm/zsmalloc.c:reset_page
```
```
In mm/userfaultfd.c (ffffffff812bc15f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812bc8b3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/fs-writeback.c (ffffffff812fe291)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
```
```
In fs/buffer.c (ffffffff8130a52d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bforget
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
  - fs/buffer.c:unlock_buffer
```
```
In fs/mpage.c (ffffffff813146be)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/crypto/crypto.c (ffffffff813337ee)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/coredump.c (ffffffff8134b90d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff8134cbca)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/quota/dquot.c (ffffffff813524f9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_decr_space
  - fs/quota/dquot.c:dquot_decr_inodes
  - fs/quota/dquot.c:dquot_release
```
```
In fs/proc/task_mmu.c (ffffffff8135a061)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/proc/base.c (ffffffff8135e30a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/proc/base.c:proc_coredump_filter_write
```
```
In fs/ext4/balloc.c (ffffffff81376ec2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/ext4/dir.c (ffffffff81379874)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8137b3ba)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/ext4/extents_status.c (ffffffff8138603a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
```
```
In fs/ext4/file.c (ffffffff81386d06)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/ext4/fsync.c (ffffffff81388830)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff81392380)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff8139dc9d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:__ext4_journalled_invalidatepage
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff8139e9f7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff813a8afb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/migrate.c (ffffffff813aa7af)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/mmp.c (ffffffff813aa8d8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813b2f81)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/page-io.c (ffffffff813b4d15)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff813b5306)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/ext4/resize.c (ffffffff813b88d0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/ext4/super.c (ffffffff813c8ff5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffffffff813d62d1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
```
In fs/ext4/verity.c (ffffffff813d83f8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In fs/jbd2/transaction.c (ffffffff813db35b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813dbd9b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/revoke.c (ffffffff813df629)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff813e46ee)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff813eb4c8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
  - fs/hugetlbfs/inode.c:remove_huge_page
```
```
In fs/ecryptfs/mmap.c (ffffffff813fdd18)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/fuse/dev.c (ffffffff814093fe)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/dir.c (ffffffff8140eb9d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff81413a45)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_perform_write
```
```
In ipc/util.c (ffffffff8141fe96)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/keys/gc.c (ffffffff8142dbd6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/tomoyo/common.c (ffffffff8146fa76)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/apparmor/policy_unpack.c (ffffffff8148bcbb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff8149e74f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814a5285)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814a6378)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In block/blk-core.c (ffffffff814cb3a8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_clear
```
```
In block/blk-mq.c (ffffffff814d9454)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_start_hw_queue
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:flush_busy_ctx
```
```
In block/blk-mq-sched.c (ffffffff814df0fe)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_restart
```
```
In lib/rhashtable.c (ffffffff81513dbf)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff81542f4e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8154dd48)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8154f811)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_init_irq_valid_mask
```
```
In drivers/gpio/gpiolib.c (ffffffff815507a5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff815586e5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
```
```
In drivers/pci/bus.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/pci/remove.c (ffffffff815617c0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff81591f6d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81594d14)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff815b1b6d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/ec.c (ffffffff815c0344)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/nfit/core.c (ffffffff815f70b5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/acpi/nfit/core.c:acpi_nfit_register_regions
  - drivers/acpi/nfit/core.c:acpi_nfit_register_regions
  - drivers/acpi/nfit/core.c:acpi_nfit_scrub
  - drivers/acpi/nfit/core.c:acpi_nfit_scrub
  - drivers/acpi/nfit/core.c:acpi_nfit_scrub
  - drivers/acpi/nfit/core.c:acpi_nfit_add_dimm
```
```
In drivers/acpi/hmat/hmat.c (ffffffff815fa425)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
```
```
In drivers/dma/dmaengine.c (ffffffff81612071)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_release_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
```
```
In drivers/tty/tty_io.c (ffffffff8162ac6c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kclose
```
```
In drivers/tty/n_tty.c (ffffffff8162ef4f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_write_wakeup
```
```
In drivers/tty/tty_ioctl.c (ffffffff816319e1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
```
```
In drivers/tty/tty_ldisc.c (ffffffff816321c5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
```
```
In drivers/tty/tty_port.c (ffffffff81633d08)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/pty.c (ffffffff81635270)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_open
  - drivers/tty/pty.c:pty_open
```
```
In drivers/tty/sysrq.c (ffffffff816370c1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/vt/keyboard.c (ffffffff8163cc53)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
```
In drivers/tty/serial/serial_core.c (ffffffff8164ddf2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
```
In drivers/tty/serial/max310x.c (ffffffff8165afe1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/misc.c (ffffffff81663bb4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_deregister
  - drivers/char/misc.c:misc_register
```
```
In drivers/char/agp/frontend.c (ffffffff81669c37)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_release
  - drivers/char/agp/frontend.c:agp_release
```
```
In drivers/char/agp/generic.c (ffffffff8166b0ec)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff81672051)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_release
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8167938d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/iommu/dmar.c (ffffffff81689e45)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_free_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff8168db09)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_detach_iommu
```
```
In drivers/base/cacheinfo.c (ffffffff816a788a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff816b6dca)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816dbd87)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
```
```
In drivers/nvdimm/label.c (ffffffff816e4222)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_alloc_slot
```
```
In drivers/nvdimm/security.c (ffffffff816e9f75)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/dax/super.c (ffffffff816efbf8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81702a04)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81706e62)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
```
```
In drivers/scsi/sr.c (ffffffff8171c22b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_kref_release
```
```
In drivers/nvme/host/core.c (ffffffff817267cd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_setup_discard
```
```
In drivers/nvme/host/multipath.c (ffffffff8172b562)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvme/host/multipath.c:nvme_update_ns_ana_state
```
```
In drivers/nvme/host/pci.c (ffffffff8172da64)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_setup_io_queues
  - drivers/nvme/host/pci.c:nvme_setup_io_queues
```
```
In drivers/ata/libata-scsi.c (ffffffff81740e88)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_free_tag
```
```
In drivers/net/tun.c (ffffffff817644a6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_attach
```
```
In drivers/usb/core/hub.c (ffffffff81793cb1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff817996c3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
```
```
In drivers/usb/core/sysfs.c (ffffffff817a3b6f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
```
```
In drivers/usb/core/devio.c (ffffffff817a484f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/host/xhci.c (ffffffff817b0c2f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
```
```
In drivers/usb/host/xhci-hub.c (ffffffff817c5448)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
```
In drivers/input/mousedev.c (ffffffff817d8ca0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/rtc/dev.c (ffffffff817e2f74)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/media/cec/cec-core.c (ffffffff817e63c0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/media/cec/cec-core.c:cec_devnode_release
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817fc1ff)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/watchdog/watchdog_dev.c:watchdog_write
```
```
In drivers/md/md.c (ffffffff818039ba)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_written
```
```
In drivers/md/md-bitmap.c (ffffffff818117f0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
```
```
In drivers/md/dm.c (ffffffff81814dca)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_queue_flush
  - drivers/md/dm.c:dm_cancel_deferred_remove
```
```
In drivers/md/dm-kcopyd.c (ffffffff81821181)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8183031d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a2fbda)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In drivers/leds/led-core.c (ffffffff8183f28c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_stop_software_blink
  - drivers/leds/led-core.c:led_blink_set_oneshot
  - drivers/leds/led-core.c:led_blink_set_oneshot
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/firmware/efi/efi.c (ffffffff828f3d88)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
```
In drivers/firmware/efi/memmap.c (ffffffff828f4c05)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
```
In drivers/hv/channel_mgmt.c (ffffffff81853100)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/hv/channel_mgmt.c:hv_process_channel_removal
```
```
In net/core/sock.c (ffffffff8186d4e6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/stream.c (ffffffff8187c7d3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_write_space
```
```
In net/core/dev.c (ffffffff81886545)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/dev.c:napi_disable
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
```
```
In net/core/link_watch.c (ffffffff818aba0c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/xdp.c (ffffffff818bcb03)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff818bdd3f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/skmsg.c (ffffffff818c3bfe)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/netpoll.c (ffffffff818c4679)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/core/gro_cells.c (ffffffff818e27f8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff818e8147)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/netlink/af_netlink.c (ffffffff818f82ec)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netlink/genetlink.c (ffffffff818fc594)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_unregister_family
```
```
In net/ipv4/tcp.c (ffffffff8191b44e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_output.c (ffffffff8192e2d1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/ipv4/inet_fragment.c (ffffffff8195ff0d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff8196e9e1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/tcp_bpf.c (ffffffff81974e0f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197daf6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (ffffffff8198f0f8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/ipv6/ip6mr.c (ffffffff819d7417)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e2708)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81a00a0a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
```
```
In net/ncsi/ncsi-manage.c (ffffffff81a0359c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
```
In lib/nmi_backtrace.c (ffffffff81a0ecc7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In lib/vsprintf.c (ffffffff81a178d4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In arch/x86/entry/common.c (ffffffff810047e5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009f8c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_dead
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a697)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102656f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102d41d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:clear_bit
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f713)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/kernel/process_64.c (ffffffff8102fa7c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff81031b47)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff81adf67c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:exit_thread
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e5c4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103fe88)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff81042010)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff810439b7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81048447)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81048a7d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104cf0b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81050197)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105931e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e042)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff810618ce)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:release_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:release_perfctr_nmi
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff810621b9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81adf830)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064aec)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/mpparse.c (ffffffff828b851d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:MP_bus_info
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d4e3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff81076a5e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/init_64.c (ffffffff81ad67db)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In arch/x86/mm/tlb.c (ffffffff81087565)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108ba35)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In arch/x86/mm/numa.c (ffffffff8108bfb9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In arch/x86/platform/efi/quirks.c (ffffffff81090cbf)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault
```
```
In arch/x86/platform/efi/efi.c (ffffffff828c54ad)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
```
In kernel/fork.c (ffffffff810982e4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff8109d6f2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (ffffffff8109e6d5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/softirq.c (ffffffff810a0fd4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/ptrace.c (ffffffff810a7346)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810aeeba)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/sys.c (ffffffff810b7155)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
```
In kernel/workqueue.c (ffffffff810ba622)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/kthread.c (ffffffff810c2692)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unpark
```
```
In kernel/sched/core.c (ffffffff81adabad)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/idle.c (ffffffff810d6575)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:call_cpuidle
  - kernel/sched/idle.c:default_idle_call
```
```
In kernel/sched/fair.c (ffffffff810d93f1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/sched/rt.c (ffffffff810e50f8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810e74d5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810ec762)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff810eccac)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
```
```
In kernel/sched/topology.c (ffffffff810eef3d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_clear
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/power/snapshot.c (ffffffff81103115)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
```
```
In kernel/irq/chip.c (ffffffff81111c2f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/generic-chip.c (ffffffff81112ac3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
```
In kernel/irq/affinity.c (ffffffff8111819e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/irq/matrix.c (ffffffff81119842)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_free
  - kernel/irq/matrix.c:irq_matrix_remove_managed
```
```
In kernel/livepatch/transition.c (ffffffff811248cc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/profile.c (ffffffff81127c80)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff8113d924)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/kexec_core.c (ffffffff8115093b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115e62d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/cgroup/freezer.c (ffffffff81160139)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In kernel/cgroup/cpuset.c (ffffffff81166a01)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/pid_namespace.c (ffffffff81169b78)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffffffff81172db9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/watchdog.c (ffffffff81186868)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/tracepoint.c (ffffffff8118cce1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/trace/trace.c (ffffffff8119de75)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
```
```
In kernel/trace/trace_events.c (ffffffff811b1d4a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:trace_event_enable_tgid_record
  - kernel/trace/trace_events.c:trace_event_enable_cmd_record
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b4a00)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811b825d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger
```
```
In kernel/bpf/offload.c (ffffffff811f8298)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/events/core.c (ffffffff811fe0c8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In kernel/events/ring_buffer.c (ffffffff8120db4c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81212f2f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/user-return-notifier.c (ffffffff812132c5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/padata.c (ffffffff8121436a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_remove_cpu
```
```
In mm/filemap.c (ffffffff8121b50d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:wake_up_page_bit
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/oom_kill.c (ffffffff81220b0e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/page-writeback.c (ffffffff81225736)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/readahead.c (ffffffff81226517)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/swap.c (ffffffff812287ae)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_file
  - mm/swap.c:lru_cache_add_anon
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
```
```
In mm/truncate.c (ffffffff812298ab)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff8123374c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/shmem.c (ffffffff81236358)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/vmstat.c (ffffffff8123ddfc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/gup.c (ffffffff8124f22b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
```
```
In mm/memory.c (ffffffff81254fda)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/mlock.c (ffffffff8125caeb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/rmap.c (ffffffff81269875)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/page_alloc.c (ffffffff81277b39)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (ffffffff8127ae2b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff8127c565)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/swap_state.c (ffffffff8127cf4d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/frontswap.c (ffffffff8128438d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/hugetlb.c (ffffffff8128e089)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffffffff8128f2b5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/sparse.c (ffffffff81293e33)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/ksm.c (ffffffff8129675c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/memory_hotplug.c (ffffffff812a20d4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/migrate.c (ffffffff812a7576)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812a9bce)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:single_hugepage_flag_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
```
```
In mm/khugepaged.c (ffffffff812b2720)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff812bec60)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:drain_local_stock
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memory-failure.c (ffffffff812c1728)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffffffff812c6459)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:reset_page
  - mm/zsmalloc.c:reset_page
```
```
In mm/userfaultfd.c (ffffffff812c902c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812c9843)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/fs-writeback.c (ffffffff8130b471)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
```
```
In fs/buffer.c (ffffffff8131743d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bforget
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
  - fs/buffer.c:unlock_buffer
```
```
In fs/mpage.c (ffffffff813215ee)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/crypto/crypto.c (ffffffff813405de)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/coredump.c (ffffffff81358739)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff813599fa)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/quota/dquot.c (ffffffff8135f329)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_decr_space
  - fs/quota/dquot.c:dquot_decr_inodes
  - fs/quota/dquot.c:dquot_release
```
```
In fs/proc/task_mmu.c (ffffffff813669ed)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/proc/base.c (ffffffff8136b34a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/proc/base.c:proc_coredump_filter_write
```
```
In fs/ext4/balloc.c (ffffffff81383f02)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/ext4/dir.c (ffffffff81386744)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8138828a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/ext4/extents_status.c (ffffffff81392f0a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
```
```
In fs/ext4/file.c (ffffffff81393bd6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/ext4/fsync.c (ffffffff81395700)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff8139f150)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff813aaa6d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:__ext4_journalled_invalidatepage
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff813ab7c7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff813b58cb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/migrate.c (ffffffff813b757f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/mmp.c (ffffffff813b76a8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813bf9a1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/page-io.c (ffffffff813c1725)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff813c1d16)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/ext4/resize.c (ffffffff813c52e0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/ext4/super.c (ffffffff813d5a05)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffffffff813e2bd1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
```
In fs/ext4/verity.c (ffffffff813e4cf8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In fs/jbd2/transaction.c (ffffffff813e7c5b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813e869b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/revoke.c (ffffffff813ebf29)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff813f0fee)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff813f7dc8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
  - fs/hugetlbfs/inode.c:remove_huge_page
```
```
In fs/ecryptfs/mmap.c (ffffffff8140a618)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/fuse/dev.c (ffffffff81414b1e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/dir.c (ffffffff8141a2bd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff8141f165)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_perform_write
```
```
In ipc/util.c (ffffffff8142b5b6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/keys/gc.c (ffffffff81439306)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/tomoyo/common.c (ffffffff8147b0f6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/apparmor/policy_unpack.c (ffffffff8149733b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff814a9dcf)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814b08f5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814b19e8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In block/blk-core.c (ffffffff814d6a88)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_clear
```
```
In block/blk-mq.c (ffffffff814e4f74)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_start_hw_queue
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:flush_busy_ctx
```
```
In block/blk-mq-sched.c (ffffffff814eac4e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_restart
```
```
In lib/rhashtable.c (ffffffff8151fb6f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff8154e97e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8155ba68)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8155d531)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_init_irq_valid_mask
```
```
In drivers/gpio/gpiolib.c (ffffffff8155e4c5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81566405)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
```
```
In drivers/pwm/sysfs.c (ffffffff8156be6f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:export_store
```
```
In drivers/pci/bus.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/pci/remove.c (ffffffff81572890)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff815a335d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815a6104)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff815c908d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/ec.c (ffffffff815d8b74)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/battery.c (ffffffff816309cd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff8164b921)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_release_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
```
```
In drivers/xen/cpu_hotplug.c (ffffffff816560de)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/xen/grant-table.c (ffffffff81656740)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_pages_clear_private
```
```
In drivers/xen/balloon.c (ffffffff81658e5d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/events/events_2l.c (ffffffff8165c935)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_bind_to_cpu
```
```
In drivers/xen/events/events_fifo.c (ffffffff8165d42b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
```
In drivers/tty/tty_io.c (ffffffff81678bdc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kclose
```
```
In drivers/tty/n_tty.c (ffffffff8167cebf)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_write_wakeup
```
```
In drivers/tty/tty_ioctl.c (ffffffff8167f961)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
```
```
In drivers/tty/tty_ldisc.c (ffffffff81680145)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
```
```
In drivers/tty/tty_port.c (ffffffff81681cde)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/pty.c (ffffffff81683270)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_open
  - drivers/tty/pty.c:pty_open
```
```
In drivers/tty/sysrq.c (ffffffff816850f1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/vt/keyboard.c (ffffffff8168acb3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
```
In drivers/tty/serial/serial_core.c (ffffffff8169d1ce)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
```
In drivers/tty/serial/max310x.c (ffffffff816aa2d1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff816ae33c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
```
In drivers/char/misc.c (ffffffff816b4304)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_deregister
  - drivers/char/misc.c:misc_register
```
```
In drivers/char/agp/frontend.c (ffffffff816ba4a7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_release
  - drivers/char/agp/frontend.c:agp_release
```
```
In drivers/char/agp/generic.c (ffffffff816bb96c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff816c28d1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_release
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816c9c0d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/iommu/dmar.c (ffffffff816da6c5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_free_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff816de399)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_detach_iommu
```
```
In drivers/lightnvm/core.c (ffffffff816eb924)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/base/cacheinfo.c (ffffffff816faaca)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff8170a0da)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff817470d7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
```
```
In drivers/nvdimm/label.c (ffffffff8174f572)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_alloc_slot
```
```
In drivers/nvdimm/security.c (ffffffff817552c5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/dax/super.c (ffffffff81756498)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff817683c2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8176c812)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
```
```
In drivers/scsi/sr.c (ffffffff8177ad1b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_kref_release
```
```
In drivers/ata/libata-scsi.c (ffffffff81790db8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_free_tag
```
```
In drivers/net/tun.c (ffffffff817b4f06)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_attach
```
```
In drivers/net/xen-netfront.c (ffffffff817c3902)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_create_queues
```
```
In drivers/usb/core/hub.c (ffffffff817de911)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff817e474a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
```
```
In drivers/usb/core/sysfs.c (ffffffff817eebdf)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
```
```
In drivers/usb/core/devio.c (ffffffff817ef8bf)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817fe66c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff82b0eeb1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff82b0eeef)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff82b0ef51)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In drivers/usb/host/xhci.c (ffffffff818285bf)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
```
```
In drivers/usb/host/xhci-hub.c (ffffffff8183cd78)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
```
In drivers/input/mousedev.c (ffffffff818506e0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/rtc/dev.c (ffffffff8185cd64)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/media/cec/cec-core.c (ffffffff8186bc60)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/media/cec/cec-core.c:cec_devnode_release
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8188419f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/watchdog/watchdog_dev.c:watchdog_write
```
```
In drivers/md/md.c (ffffffff8188b98a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_written
```
```
In drivers/md/md-bitmap.c (ffffffff818997e0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
```
```
In drivers/md/dm.c (ffffffff8189cdda)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_queue_flush
  - drivers/md/dm.c:dm_cancel_deferred_remove
```
```
In drivers/md/dm-kcopyd.c (ffffffff818a91a1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818b83fd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In drivers/cpuidle/poll_state.c (ffffffff81adfc70)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In drivers/leds/led-core.c (ffffffff818d8dac)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_stop_software_blink
  - drivers/leds/led-core.c:led_blink_set_oneshot
  - drivers/leds/led-core.c:led_blink_set_oneshot
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/firmware/efi/efi.c (ffffffff8291171b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
```
In drivers/firmware/efi/memmap.c (ffffffff82912598)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
```
In net/core/sock.c (ffffffff81904596)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/stream.c (ffffffff81913893)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_write_space
```
```
In net/core/dev.c (ffffffff8191d4b5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/dev.c:napi_disable
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
```
```
In net/core/link_watch.c (ffffffff81942bfc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/xdp.c (ffffffff81953d03)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81954f3f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/skmsg.c (ffffffff8195ae1e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/netpoll.c (ffffffff8195bab9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/core/gro_cells.c (ffffffff81979bd8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff8197f7d7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/netlink/af_netlink.c (ffffffff8198f97c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netlink/genetlink.c (ffffffff81993c34)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_unregister_family
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819acba1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:__ctnetlink_change_status
```
```
In net/ipv4/tcp.c (ffffffff819cc12e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_output.c (ffffffff819defe5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10ced)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a1cc51)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a22a9f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2b786)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (ffffffff81a3cdb8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/ipv6/ip6mr.c (ffffffff81a850d7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a903c8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81aafcca)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
```
```
In net/ncsi/ncsi-manage.c (ffffffff81ab285c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
```
In lib/nmi_backtrace.c (ffffffff81abdfb7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In lib/vsprintf.c (ffffffff81ac6be4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In arch/x86/entry/common.c (ffffffff81004925)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
```
In arch/x86/events/amd/uncore.c (ffffffff8100a0ec)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_dead
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a7f7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810272f5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102e20d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:clear_bit
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81030563)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/kernel/process_64.c (ffffffff810308cc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/traps.c (ffffffff81032a0e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/process.c (ffffffff81aebe0c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/process.c:exit_thread
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103f754)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104122c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff810433f0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81044db7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81049857)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81049e8d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e31b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810515d7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105a7be)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105f562)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff81062e7e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:release_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:release_perfctr_nmi
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81063779)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81aec000)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff810660cc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/mpparse.c (ffffffff828b861e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:MP_bus_info
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106f763)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff81078bbe)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/init_64.c (ffffffff81ae2c9b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In arch/x86/mm/tlb.c (ffffffff81089695)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108dd95)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In arch/x86/mm/numa.c (ffffffff8108e319)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In arch/x86/platform/efi/quirks.c (ffffffff810930a8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault
```
```
In arch/x86/platform/efi/efi.c (ffffffff828c8653)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109afc7)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/fork.c (ffffffff8109fedb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff810a5578)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (ffffffff810a65ee)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/softirq.c (ffffffff810a8f54)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/ptrace.c (ffffffff810af2d6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810b7192)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/sys.c (ffffffff810bf4d5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
```
In kernel/workqueue.c (ffffffff810c4a12)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/kthread.c (ffffffff810cac52)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unpark
```
```
In kernel/sched/core.c (ffffffff81ae705f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/idle.c (ffffffff810e1e75)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:call_cpuidle
  - kernel/sched/idle.c:default_idle_call
```
```
In kernel/sched/fair.c (ffffffff810e4e21)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/sched/rt.c (ffffffff810f1091)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810f2495)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810f77a2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff810f7cec)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
```
```
In kernel/sched/topology.c (ffffffff810f9f7d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_clear
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/power/snapshot.c (ffffffff8110e505)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
```
```
In kernel/irq/chip.c (ffffffff8111d1ef)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/generic-chip.c (ffffffff8111e253)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
```
In kernel/irq/affinity.c (ffffffff8112382e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/irq/matrix.c (ffffffff81124fa2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_free
  - kernel/irq/matrix.c:irq_matrix_remove_managed
```
```
In kernel/livepatch/transition.c (ffffffff81130f1c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/profile.c (ffffffff81134300)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff8114a434)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/kexec_core.c (ffffffff8115d75b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116ba5d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/cgroup/freezer.c (ffffffff8116d471)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In kernel/cgroup/cpuset.c (ffffffff81174081)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/pid_namespace.c (ffffffff81177298)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffffffff81180623)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/watchdog.c (ffffffff811941b8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/tracepoint.c (ffffffff8119a671)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/trace/trace.c (ffffffff811abb55)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
```
```
In kernel/trace/trace_events.c (ffffffff811bfdea)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:trace_event_enable_tgid_record
  - kernel/trace/trace_events.c:trace_event_enable_cmd_record
```
```
In kernel/trace/trace_syscalls.c (ffffffff811c2aa0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811c62fd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger
```
```
In kernel/bpf/offload.c (ffffffff812065fe)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/events/core.c (ffffffff8120cfd8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In kernel/events/ring_buffer.c (ffffffff8121c9fc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81221ea9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/user-return-notifier.c (ffffffff81222265)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In kernel/padata.c (ffffffff812235aa)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_remove_cpu
```
```
In mm/filemap.c (ffffffff8122a569)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:wake_up_page_bit
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/oom_kill.c (ffffffff8122fcae)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/page-writeback.c (ffffffff81234a36)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/readahead.c (ffffffff8123583e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/swap.c (ffffffff81237b1e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_file
  - mm/swap.c:lru_cache_add_anon
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
```
```
In mm/truncate.c (ffffffff81238cbb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff81242c83)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/shmem.c (ffffffff8124662f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/vmstat.c (ffffffff8124d52c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/gup.c (ffffffff8125eb9b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
```
```
In mm/memory.c (ffffffff81264a96)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/mlock.c (ffffffff8126c4cb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/rmap.c (ffffffff81278b05)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/page_alloc.c (ffffffff81287729)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (ffffffff8128aa04)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff8128c135)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/swap_state.c (ffffffff8128cb0d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/frontswap.c (ffffffff8129436d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/hugetlb.c (ffffffff8129de2b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffffffff8129f735)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In mm/sparse.c (ffffffff812a3c93)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/ksm.c (ffffffff812a6546)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/memory_hotplug.c (ffffffff812b2364)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/migrate.c (ffffffff812b787c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812b9e4e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:single_hugepage_flag_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
```
```
In mm/khugepaged.c (ffffffff812c2e06)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff812cf6e0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:drain_local_stock
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memory-failure.c (ffffffff812d21e8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffffffff812d5d82)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
  - mm/zsmalloc.c:reset_page
  - mm/zsmalloc.c:unpin_tag
```
```
In mm/userfaultfd.c (ffffffff812d9d2d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812da543)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/fs-writeback.c (ffffffff8131cc31)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
```
```
In fs/buffer.c (ffffffff8132902d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bforget
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
  - fs/buffer.c:unlock_buffer
```
```
In fs/mpage.c (ffffffff81333342)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/crypto/crypto.c (ffffffff813538de)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/coredump.c (ffffffff8136b5c8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff8136d0ea)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/quota/dquot.c (ffffffff81372126)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_decr_space
  - fs/quota/dquot.c:dquot_decr_inodes
  - fs/quota/dquot.c:dquot_release
```
```
In fs/proc/task_mmu.c (ffffffff8137a049)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/proc/base.c (ffffffff8137eb9a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/proc/base.c:proc_coredump_filter_write
```
```
In fs/ext4/balloc.c (ffffffff81397a6d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/ext4/dir.c (ffffffff8139a431)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8139bf8a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/ext4/extents_status.c (ffffffff813a6f7f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
```
```
In fs/ext4/file.c (ffffffff813a7c66)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In fs/ext4/fsync.c (ffffffff813a984d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff813b36c0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff813bf3bd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:__ext4_journalled_invalidatepage
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff813c0167)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff813ca564)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/migrate.c (ffffffff813cc28f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/mmp.c (ffffffff813cc3b8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813d4a81)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/page-io.c (ffffffff813d6885)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff813d6e96)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/ext4/resize.c (ffffffff813da510)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/ext4/super.c (ffffffff813eac85)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffffffff813f7fe1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
```
In fs/ext4/verity.c (ffffffff813fa148)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In fs/jbd2/transaction.c (ffffffff813fd462)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813fdec5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/revoke.c (ffffffff814018c9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff81406bb9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff8140db18)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
  - fs/hugetlbfs/inode.c:remove_huge_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81420312)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/fuse/dev.c (ffffffff8142b38b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/dir.c (ffffffff8143101d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff81435ee5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_perform_write
```
```
In ipc/util.c (ffffffff8144254d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/keys/gc.c (ffffffff81450449)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/tomoyo/common.c (ffffffff81492ce6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/apparmor/policy_unpack.c (ffffffff814af41a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff814c281f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814c9375)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814ca468)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In block/blk-core.c (ffffffff814ef698)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_clear
```
```
In block/blk-mq.c (ffffffff814fdda4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_start_hw_queue
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:flush_busy_ctx
```
```
In block/blk-mq-sched.c (ffffffff81503c2e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_restart
```
```
In lib/rhashtable.c (ffffffff8153945b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff815687ce)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81575a88)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81577451)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_init_irq_valid_mask
```
```
In drivers/gpio/gpiolib.c (ffffffff81578355)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81580325)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
```
```
In drivers/pwm/sysfs.c (ffffffff8158636f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:export_store
```
```
In drivers/pci/bus.c (0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/pci/remove.c (ffffffff8158cd70)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff815bd75d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815c0504)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff815e2eed)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/ec.c (ffffffff815f2a34)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/hmat/hmat.c (ffffffff816490f5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
```
```
In drivers/acpi/battery.c (ffffffff8164ad0d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81665ec1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_release_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
```
```
In drivers/xen/cpu_hotplug.c (ffffffff816706be)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/xen/grant-table.c (ffffffff81670d20)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_pages_clear_private
```
```
In drivers/xen/balloon.c (ffffffff8167346d)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/events/events_2l.c (ffffffff81676f25)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_bind_to_cpu
```
```
In drivers/xen/events/events_fifo.c (ffffffff81677a3b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
```
In drivers/tty/tty_io.c (ffffffff81692817)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kclose
```
```
In drivers/tty/n_tty.c (ffffffff8169751c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_write_wakeup
```
```
In drivers/tty/tty_ioctl.c (ffffffff81699fb1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
```
```
In drivers/tty/tty_ldisc.c (ffffffff8169a795)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
```
```
In drivers/tty/tty_port.c (ffffffff8169c325)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/pty.c (ffffffff8169d8a0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_open
  - drivers/tty/pty.c:pty_open
```
```
In drivers/tty/sysrq.c (ffffffff8169f6f1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/vt/keyboard.c (ffffffff816a52b3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
```
In drivers/tty/serial/serial_core.c (ffffffff816b615c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
```
In drivers/tty/serial/max310x.c (ffffffff816c4731)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff816c879c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
```
In drivers/char/misc.c (ffffffff816ce864)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_deregister
  - drivers/char/misc.c:misc_register
```
```
In drivers/char/agp/frontend.c (ffffffff816d4a77)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_release
  - drivers/char/agp/frontend.c:agp_release
```
```
In drivers/char/agp/generic.c (ffffffff816d5f3c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff816dcea1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_release
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816e40e8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/iommu/dmar.c (ffffffff816f4c75)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_free_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff816f89a9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_detach_iommu
```
```
In drivers/lightnvm/core.c (ffffffff81706164)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/base/cacheinfo.c (ffffffff8171536a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff81724c4a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81762517)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
```
```
In drivers/nvdimm/label.c (ffffffff8176a9f2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_alloc_slot
```
```
In drivers/nvdimm/security.c (ffffffff81770735)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/dax/super.c (ffffffff81771b18)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81783ae0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81787fb2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
```
```
In drivers/scsi/sr.c (ffffffff817950bb)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_kref_release
```
```
In drivers/ata/libata-scsi.c (ffffffff817aabf8)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_free_tag
```
```
In drivers/net/tun.c (ffffffff817ceed6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_attach
```
```
In drivers/net/xen-netfront.c (ffffffff817ddbc2)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_create_queues
```
```
In drivers/usb/core/hub.c (ffffffff817f8c01)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff817fe9b6)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
```
```
In drivers/usb/core/sysfs.c (ffffffff81808e1f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
```
```
In drivers/usb/core/devio.c (ffffffff81809aff)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8181877c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff82b039d3)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff82b03a11)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff82b03a73)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In drivers/usb/host/xhci.c (ffffffff8184258f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81857248)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
```
In drivers/input/mousedev.c (ffffffff8186b860)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/rtc/dev.c (ffffffff81877fe4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/media/cec/cec-core.c (ffffffff81885bf0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/media/cec/cec-core.c:cec_devnode_release
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8189fc5f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/watchdog/watchdog_dev.c:watchdog_write
```
```
In drivers/md/md.c (ffffffff818aabfa)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_written
```
```
In drivers/md/md-bitmap.c (ffffffff818b5320)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
```
```
In drivers/md/dm.c (ffffffff818b913a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_queue_flush
  - drivers/md/dm.c:dm_cancel_deferred_remove
```
```
In drivers/md/dm-kcopyd.c (ffffffff818c55b1)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818d46bd)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In drivers/cpuidle/poll_state.c (ffffffff81aec470)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In drivers/leds/led-core.c (ffffffff818f58cc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_stop_software_blink
  - drivers/leds/led-core.c:led_blink_set_oneshot
  - drivers/leds/led-core.c:led_blink_set_oneshot
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/firmware/efi/efi.c (ffffffff82918148)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
```
In drivers/firmware/efi/memmap.c (ffffffff82918fc5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
```
In net/core/sock.c (ffffffff81925616)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/stream.c (ffffffff81934a16)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_write_space
```
```
In net/core/dev.c (ffffffff8193e9cc)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/dev.c:napi_disable
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
```
```
In net/core/link_watch.c (ffffffff8196445c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/xdp.c (ffffffff8197548a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81976f1f)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/skmsg.c (ffffffff8197d03e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/netpoll.c (ffffffff8197dea9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/core/gro_cells.c (ffffffff8199c108)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff819a1d35)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/netlink/af_netlink.c (ffffffff819b225c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netlink/genetlink.c (ffffffff819b673e)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_unregister_family
```
```
In net/ipv4/tcp.c (ffffffff819d5cbe)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_output.c (ffffffff819e8c85)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b5d0)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a27b9c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2de95)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a36dd9)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (ffffffff81a4836b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/ipv6/ip6mr.c (ffffffff81a919e5)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9cfce)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81abc07a)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
```
```
In net/ncsi/ncsi-manage.c (ffffffff81abec0c)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
```
In lib/nmi_backtrace.c (ffffffff81aca44b)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In lib/vsprintf.c (ffffffff81ad30c4)
Location: arch/x86/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
</details>
</li>
</ul>

## Differences
