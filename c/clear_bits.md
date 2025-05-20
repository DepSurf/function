# Function: <code>clear_bits</code>

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
In arch/powerpc/kernel/ptrace.c (c000000000018a18)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - arch/powerpc/kernel/ptrace.c:ptrace_disable
```
```
In arch/powerpc/kernel/process.c (c00000000002238c)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - arch/powerpc/kernel/process.c:copy_thread_tls
  - arch/powerpc/kernel/process.c:restore_tm_state
```
```
In arch/powerpc/kernel/signal.c (c000000000023708)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - arch/powerpc/kernel/signal.c:do_notify_resume
  - arch/powerpc/kernel/signal.c:do_notify_resume
```
```
In arch/powerpc/kernel/cacheinfo.c (c00000000002b278)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - arch/powerpc/kernel/cacheinfo.c:cacheinfo_cpu_offline
```
```
In arch/powerpc/kernel/setup-common.c (c00000000134a33c)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps
```
```
In arch/powerpc/kernel/watchdog.c (c000000000037508)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - arch/powerpc/kernel/watchdog.c:stop_watchdog
  - arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending
  - arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending
```
```
In arch/powerpc/kernel/rtas.c (c00000000003cdd0)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - arch/powerpc/kernel/rtas.c:rtas_cpu_state_change_mask
```
```
In arch/powerpc/kernel/crash_dump.c (c00000000004be1c)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - arch/powerpc/kernel/crash_dump.c:crash_free_reserved_phys_range
```
```
In arch/powerpc/kernel/fadump.c (c00000000004c16c)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - arch/powerpc/kernel/fadump.c:fadump_release_reserved_area
```
```
In arch/powerpc/kernel/iommu.c (c000000000050f58)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - arch/powerpc/kernel/iommu.c:iommu_table_release_pages
  - arch/powerpc/kernel/iommu.c:iommu_table_release_pages
```
```
In arch/powerpc/kernel/smp.c (c000000000053f9c)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - arch/powerpc/kernel/smp.c:set_cpus_unrelated
  - arch/powerpc/kernel/smp.c:set_cpus_unrelated
  - arch/powerpc/kernel/smp.c:__smp_send_nmi_ipi
  - arch/powerpc/kernel/smp.c:smp_handle_nmi_ipi
```
```
In arch/powerpc/kernel/stacktrace.c (c000000000069620)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
```
```
In arch/powerpc/kernel/pci-common.c (c00000000006bd30)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_free_controller
```
```
In arch/powerpc/mm/mem.c (0)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
```
```
In arch/powerpc/mm/init_64.c (c000000000088e68)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - arch/powerpc/mm/init_64.c:vmemmap_free
```
```
In arch/powerpc/mm/numa.c (c0000000000a3784)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:numa_update_cpu_topology
  - arch/powerpc/mm/numa.c:unmap_cpu_from_node
```
```
In arch/powerpc/sysdev/xive/spapr.c (c0000000000c09d0)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/spapr.c:xive_spapr_put_ipi
```
```
In arch/powerpc/platforms/powernv/idle.c (c0000000000c72a8)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/idle.c:power9_idle_stop
```
```
In arch/powerpc/platforms/powernv/opal-flash.c (c0000000000ca02c)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-flash.c:image_data_write
```
```
In arch/powerpc/platforms/powernv/opal-irqchip.c (c0000000000ccd10)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_mask
```
```
In arch/powerpc/platforms/powernv/pci-ioda.c (c000000001360388)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_init_ioda_phb
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_vf_release_m64
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_free_pe
```
```
In arch/powerpc/platforms/pseries/smp.c (c0000000013639c8)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/smp.c:smp_init_pseries
  - arch/powerpc/platforms/pseries/smp.c:smp_setup_cpu
```
```
In arch/powerpc/platforms/pseries/hotplug-cpu.c (c0000000000fa360)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
```
```
In arch/powerpc/xmon/xmon.c (c000000000110d40)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:xmon_core
```
```
In arch/powerpc/kvm/book3s_hv_rm_mmu.c (c00000000011c7d0)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
```
```
In arch/powerpc/kvm/book3s_hv_ras.c (c000000000120d30)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_ras.c:kvmppc_realmode_hmi_handler
```
```
In arch/powerpc/kvm/book3s_hv_builtin.c (c000000000120ed0)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmppc_check_need_tlb_flush
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmppc_rm_h_confer
```
```
In arch/powerpc/kvm/book3s_hv_rm_xics.c (c0000000001238ec)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:xics_rm_h_cppr
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:xics_rm_h_xirr
```
```
In kernel/fork.c (c0000000001393e4)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (c000000000140790)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (c000000000142024)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/softirq.c (c000000000145bdc)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/ptrace.c (c00000000014ecb4)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (c000000000159290)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/sys.c (c000000000161df4)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_prctl
```
```
In kernel/workqueue.c (c000000000167b88)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
```
```
In kernel/kthread.c (c0000000001730b8)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unpark
```
```
In kernel/sched/core.c (c00000000018c180)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/idle.c (c00000000018ee84)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:call_cpuidle
  - kernel/sched/idle.c:default_idle_call
```
```
In kernel/sched/fair.c (c000000000193e00)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
```
```
In kernel/sched/rt.c (c0000000001a3fe4)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (c0000000001a6504)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (c0000000001ae234)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (c0000000001aeaec)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
```
```
In kernel/sched/topology.c (c0000000001b1b44)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_clear
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/resend.c (c0000000001d8090)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/irq/resend.c:resend_irqs
```
```
In kernel/irq/chip.c (c0000000001da324)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/generic-chip.c (c0000000001db9fc)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
```
In kernel/irq/affinity.c (c0000000001e1bf0)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/livepatch/transition.c (c0000000001f3884)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/profile.c (c0000000001f8ef8)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/tick-broadcast.c (c000000000217d24)
Location: arch/powerpc/include/asm/bitops.h:85
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
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/kexec_core.c (c000000000232580)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
```
```
In kernel/cgroup/cgroup-v1.c (c000000000247f10)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
```
```
In kernel/cgroup/freezer.c (c00000000024b200)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In kernel/cgroup/cpuset.c (c000000000254134)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/pid_namespace.c (c000000000258480)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (c000000000265b3c)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/watchdog.c (c000000000283b24)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/tracepoint.c (c00000000028d404)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/trace/trace.c (c0000000002a8e60)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
```
```
In kernel/trace/trace_events.c (c0000000002c8774)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_count_probe
  - kernel/trace/trace_events.c:event_enable_probe
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
In kernel/trace/trace_syscalls.c (c0000000002ccac0)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (c0000000002d29d8)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_count_trigger
```
```
In kernel/events/core.c (c00000000033eca0)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In kernel/events/ring_buffer.c (c000000000353efc)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
```
```
In kernel/events/uprobes.c (c00000000035be34)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/padata.c (c00000000035dec4)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_remove_cpu
```
```
In mm/filemap.c (c0000000003689b0)
Location: arch/powerpc/include/asm/bitops.h:85
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
In mm/oom_kill.c (c000000000370a1c)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/page-writeback.c (c00000000037504c)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/readahead.c (c000000000378850)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
```
```
In mm/swap.c (c00000000037c130)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_file
  - mm/swap.c:lru_cache_add_anon
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
```
```
In mm/truncate.c (c00000000037dedc)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (c00000000038c590)
Location: arch/powerpc/include/asm/bitops.h:85
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
In mm/shmem.c (c000000000391d6c)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/vmstat.c (c00000000039bad8)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/gup.c (c0000000003b5a28)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
```
```
In mm/mlock.c (c0000000003c8a3c)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
```
```
In mm/rmap.c (c0000000003d8368)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/page_alloc.c (c0000000003ecc64)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (c0000000003f3438)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (c0000000003f587c)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/swap_state.c (c0000000003f6944)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/frontswap.c (c0000000004010d4)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/hugetlb.c (c000000000410818)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (c000000000412688)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
```
```
In mm/sparse.c (c000000000417d3c)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/ksm.c (c00000000041c45c)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
```
```
In mm/memory_hotplug.c (c00000000042d5d4)
Location: arch/powerpc/include/asm/bitops.h:85
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
In mm/migrate.c (c000000000437ce0)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (c00000000043b9e4)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
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
In mm/khugepaged.c (c000000000448fa4)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (c00000000045b2f8)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:drain_local_stock
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memory-failure.c (c00000000045fc40)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (c00000000046657c)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
  - mm/zsmalloc.c:reset_page
```
```
In mm/userfaultfd.c (c00000000046b570)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (c00000000046c48c)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/fs-writeback.c (c0000000004cce40)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
```
```
In fs/buffer.c (c0000000004de948)
Location: arch/powerpc/include/asm/bitops.h:85
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
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/mpage.c (c0000000004ecf40)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/crypto/crypto.c (c0000000005175e8)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
```
```
In fs/binfmt_elf.c (c00000000052dcec)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (c000000000531964)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/coredump.c (c00000000053902c)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (c00000000053aaf0)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/quota/dquot.c (c000000000542b9c)
Location: arch/powerpc/include/asm/bitops.h:85
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
In fs/proc/task_mmu.c (c00000000054e54c)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/proc/base.c (c000000000554840)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/proc/base.c:proc_coredump_filter_write
```
```
In fs/ext4/balloc.c (c00000000057c298)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
```
```
In fs/ext4/dir.c (c0000000005800e0)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (c000000000582764)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
```
```
In fs/ext4/extents_status.c (c000000000590698)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
```
```
In fs/ext4/file.c (c000000000590e88)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/fsync.c (c000000000593994)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (c0000000005a073c)
Location: arch/powerpc/include/asm/bitops.h:85
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
In fs/ext4/inode.c (c0000000005b0348)
Location: arch/powerpc/include/asm/bitops.h:85
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
In fs/ext4/ioctl.c (c0000000005b150c)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (c0000000005c07b4)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/migrate.c (c0000000005c3020)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/mmp.c (c0000000005c3150)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (c0000000005ce5fc)
Location: arch/powerpc/include/asm/bitops.h:85
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
In fs/ext4/page-io.c (c0000000005d0f30)
Location: arch/powerpc/include/asm/bitops.h:85
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
In fs/ext4/readpage.c (c0000000005d16c0)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/ext4/super.c (c0000000005ee158)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (c0000000005fe354)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
```
In fs/ext4/verity.c (c000000000600f34)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In fs/jbd2/transaction.c (c0000000006057d8)
Location: arch/powerpc/include/asm/bitops.h:85
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
In fs/jbd2/commit.c (c000000000607158)
Location: arch/powerpc/include/asm/bitops.h:85
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
```
```
In fs/jbd2/revoke.c (c00000000060bf54)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (c000000000613e8c)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/hugetlbfs/inode.c (c00000000061d230)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
  - fs/hugetlbfs/inode.c:remove_huge_page
```
```
In fs/ecryptfs/mmap.c (c000000000636a60)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/fuse/dev.c (c000000000646a5c)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/dir.c (c00000000064f08c)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (c000000000655b64)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_perform_write
```
```
In security/keys/gc.c (c000000000679a44)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/tomoyo/common.c (c0000000006e3110)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/integrity/ima/ima_fs.c (c00000000072be38)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
```
```
In security/integrity/ima/ima_appraise.c (c0000000007378c8)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In security/integrity/evm/evm_crypto.c (c00000000073a160)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
```
```
In block/blk-core.c (c00000000077171c)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_clear
```
```
In block/blk-mq.c (c000000000786088)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_start_stopped_hw_queues
  - block/blk-mq.c:blk_mq_start_hw_queues
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:flush_busy_ctx
```
```
In block/blk-mq-sched.c (c00000000078ef60)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_restart
```
```
In lib/irq_poll.c (c00000000081d008)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In drivers/gpio/gpiolib.c (c000000000839b14)
Location: arch/powerpc/include/asm/bitops.h:85
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
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-sysfs.c (c000000000847344)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
```
```
In drivers/gpio/gpio-stmpe.c (c00000000084b3b8)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_init_irq_valid_mask
```
```
In drivers/pwm/sysfs.c (c000000000851870)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:export_store
```
```
In drivers/pci/bus.c (0)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
```
```
In drivers/pci/remove.c (c00000000085a7a8)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (c000000000889fac)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c00000000088f1c4)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_unmap_addr
```
```
In drivers/pci/controller/pcie-xilinx.c (c000000000891ac4)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_msi_teardown_irq
```
```
In drivers/dma/dmaengine.c (c0000000008c8064)
Location: arch/powerpc/include/asm/bitops.h:85
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
In drivers/tty/tty_io.c (c0000000008f1368)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kclose
```
```
In drivers/tty/n_tty.c (c0000000008f8144)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_write_wakeup
```
```
In drivers/tty/tty_ioctl.c (c0000000008fa984)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
```
```
In drivers/tty/tty_ldisc.c (c0000000008fb804)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
```
```
In drivers/tty/tty_port.c (c0000000008fe594)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/pty.c (c000000000900528)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_open
  - drivers/tty/pty.c:pty_open
  - drivers/tty/pty.c:pty_set_lock
```
```
In drivers/tty/sysrq.c (c000000000903b28)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/vt/keyboard.c (c00000000090c1b0)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
```
In drivers/tty/serial/serial_core.c (c00000000092a1b4)
Location: arch/powerpc/include/asm/bitops.h:85
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
In drivers/tty/serial/max310x.c (c00000000093bee4)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
```
```
In drivers/tty/serdev/serdev-ttyport.c (c000000000941d28)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
```
In drivers/char/misc.c (c00000000094af60)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_deregister
  - drivers/char/misc.c:misc_register
```
```
In drivers/char/agp/frontend.c (c00000000095377c)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_release
  - drivers/char/agp/frontend.c:agp_release
```
```
In drivers/char/agp/generic.c (c000000000955290)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/tpm/tpm-dev.c (c000000000959e10)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_release
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/char/tpm/tpm_tis_core.c (c000000000962ee4)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/lightnvm/core.c (c0000000009751c4)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/base/cacheinfo.c (c00000000098e278)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
```
```
In drivers/base/power/domain.c (c0000000009a6e50)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (c000000000a01c00)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
```
```
In drivers/nvdimm/label.c (c000000000a0f10c)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_alloc_slot
```
```
In drivers/nvdimm/security.c (c000000000a17b28)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/dax/super.c (c000000000a19930)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/dax/super.c:write_cache_store
```
```
In drivers/scsi/scsi_lib.c (c000000000a33864)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/scsi/scsi_sysfs.c (c000000000a39b20)
Location: arch/powerpc/include/asm/bitops.h:85
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
In drivers/scsi/sr.c (c000000000a4d360)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_kref_release
```
```
In drivers/ata/libata-scsi.c (c000000000a6d1cc)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_free_tag
```
```
In drivers/spi/spi.c (c000000000a88a50)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_unregister_device
```
```
In drivers/net/tun.c (c000000000a9c750)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_attach
```
```
In drivers/usb/core/hub.c (c000000000ad2680)
Location: arch/powerpc/include/asm/bitops.h:85
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
In drivers/usb/core/hcd.c (c000000000ad9c80)
Location: arch/powerpc/include/asm/bitops.h:85
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
In drivers/usb/core/sysfs.c (c000000000ae7e20)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
```
```
In drivers/usb/core/devio.c (c000000000ae93fc)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/dwc2/hcd.c (c000000000b044f8)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
```
```
In drivers/usb/host/ehci-hcd.c (c0000000013cdfa8)
Location: arch/powerpc/include/asm/bitops.h:85
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
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
```
```
In drivers/usb/host/ohci-hcd.c (c0000000013ce02c)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/uhci-hcd.c (c0000000013ce0e0)
Location: arch/powerpc/include/asm/bitops.h:85
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
In drivers/usb/host/xhci.c (c000000000b44e4c)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
```
```
In drivers/usb/host/xhci-hub.c (c000000000b61108)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
```
In drivers/input/mousedev.c (c000000000b7cae8)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/i2c/i2c-core-base.c (c000000000b93234)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
```
```
In drivers/i2c/i2c-core-of.c (c000000000b99e60)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-of.c:of_i2c_register_devices
```
```
In drivers/media/cec/cec-core.c (c000000000b9f3f8)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/media/cec/cec-core.c:cec_devnode_release
```
```
In drivers/watchdog/watchdog_dev.c (c000000000bc7d44)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/watchdog/watchdog_dev.c:watchdog_write
```
```
In drivers/md/md.c (c000000000bd72bc)
Location: arch/powerpc/include/asm/bitops.h:85
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
In drivers/md/md-bitmap.c (c000000000be67a4)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
```
```
In drivers/md/dm.c (c000000000bec43c)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_queue_flush
  - drivers/md/dm.c:dm_cancel_deferred_remove
```
```
In drivers/md/dm-kcopyd.c (c000000000bfd9a4)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
```
In drivers/cpufreq/cpufreq.c (c000000000c136a0)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In drivers/cpuidle/cpuidle-pseries.c (c000000000c224bc)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle-pseries.c:snooze_loop
  - drivers/cpuidle/cpuidle-pseries.c:snooze_loop
```
```
In drivers/cpuidle/cpuidle-powernv.c (c000000000c22b80)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle-powernv.c:snooze_loop
  - drivers/cpuidle/cpuidle-powernv.c:snooze_loop
```
```
In drivers/leds/led-core.c (c000000000c3d760)
Location: arch/powerpc/include/asm/bitops.h:85
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
In drivers/of/platform.c (c000000000c47f78)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_device_create_pdata
```
```
In drivers/of/dynamic.c (c000000000c4bed4)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/of/dynamic.c:__of_attach_node
```
```
In drivers/of/irq.c (c0000000013bc584)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/of/irq.c:of_irq_init
```
```
In net/core/sock.c (c000000000c814d8)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/stream.c (c000000000c96758)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_write_space
```
```
In net/core/dev.c (c000000000ca533c)
Location: arch/powerpc/include/asm/bitops.h:85
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
In net/core/link_watch.c (c000000000cd8dbc)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/skmsg.c (c000000000cfc394)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/netpoll.c (c000000000cfd550)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/core/gro_cells.c (c000000000d29c60)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
```
```
In net/sched/sch_generic.c (c000000000d33150)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/netlink/af_netlink.c (c000000000d4a2e8)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
```
```
In net/netlink/genetlink.c (c000000000d50b94)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
```
```
In net/ipv4/tcp.c (c000000000d7bc50)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_output.c (c000000000d94060)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/ipv4/tcp_bpf.c (c000000000df24c4)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (c000000000e188b4)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/ncsi/ncsi-rsp.c (c000000000eb58a0)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
```
```
In net/ncsi/ncsi-manage.c (c000000000eba260)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
```
In lib/nmi_backtrace.c (c000000000ecf05c)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In lib/vsprintf.c (c000000000edbf30)
Location: arch/powerpc/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
