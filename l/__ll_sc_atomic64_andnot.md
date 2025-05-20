# Function: <code>__ll_sc_atomic64_andnot</code>

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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/debug-monitors.c (ffff800010085fd4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - arch/arm64/kernel/debug-monitors.c:user_disable_single_step
```
```
In arch/arm64/kernel/fpsimd.c (ffff8000100881a8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - arch/arm64/kernel/fpsimd.c:fpsimd_update_current_state
  - arch/arm64/kernel/fpsimd.c:fpsimd_restore_current_state
  - arch/arm64/kernel/fpsimd.c:fpsimd_flush_thread
  - arch/arm64/kernel/fpsimd.c:fpsimd_thread_switch
  - arch/arm64/kernel/fpsimd.c:sve_set_vector_length
```
```
In arch/arm64/kernel/process.c (ffff80001008989c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - arch/arm64/kernel/process.c:set_tagged_addr_ctrl
  - arch/arm64/kernel/process.c:arch_dup_task_struct
  - arch/arm64/kernel/process.c:flush_thread
```
```
In arch/arm64/kernel/ptrace.c (ffff80001008d544)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:sve_set
```
```
In arch/arm64/kernel/signal.c (ffff800010093320)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - arch/arm64/kernel/signal.c:do_notify_resume
  - arch/arm64/kernel/signal.c:do_notify_resume
  - arch/arm64/kernel/signal.c:restore_fpsimd_context
```
```
In arch/arm64/kernel/smp.c (ffff80001009d1ac)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:smp_send_stop
```
```
In arch/arm64/kernel/syscall.c (ffff80001009db6c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - arch/arm64/kernel/syscall.c:el0_svc_handler
```
```
In arch/arm64/kernel/perf_event.c (ffff8000100a47ac)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - arch/arm64/kernel/perf_event.c:armv8pmu_clear_event_idx
  - arch/arm64/kernel/perf_event.c:armv8pmu_clear_event_idx
  - arch/arm64/kernel/perf_event.c:armv8pmu_get_event_idx
```
```
In arch/arm64/kernel/ssbd.c (ffff8000100ac0f4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - arch/arm64/kernel/ssbd.c:arch_prctl_spec_ctrl_set
  - arch/arm64/kernel/ssbd.c:arch_prctl_spec_ctrl_set
```
```
In arch/arm64/mm/flush.c (ffff8000100adbf4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - arch/arm64/mm/flush.c:flush_dcache_page
```
```
In arch/arm64/mm/numa.c (ffff8000100b2194)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - arch/arm64/mm/numa.c:numa_update_cpu
```
```
In virt/kvm/kvm_main.c (ffff8000100b8b08)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:hardware_disable_nolock
  - virt/kvm/kvm_main.c:hardware_enable_nolock
```
```
In virt/kvm/arm/arm.c (ffff8000100c702c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
```
```
In virt/kvm/arm/psci.c (ffff8000100ce2d4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - virt/kvm/arm/psci.c:kvm_psci_0_2_call
```
```
In arch/arm64/kvm/handle_exit.c (ffff8000100d161c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - arch/arm64/kvm/handle_exit.c:kvm_handle_wfx
```
```
In arch/arm64/kvm/fpsimd.c (ffff8000100dae30)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - arch/arm64/kvm/fpsimd.c:kvm_arch_vcpu_put_fp
  - arch/arm64/kvm/fpsimd.c:kvm_arch_vcpu_ctxsync_fp
  - arch/arm64/kvm/fpsimd.c:kvm_arch_vcpu_ctxsync_fp
```
```
In virt/kvm/arm/pmu.c (ffff8000100ef26c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - virt/kvm/arm/pmu.c:kvm_pmu_set_counter_event_type
```
```
In kernel/fork.c (ffff8000100f4aa0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_task_struct
```
```
In kernel/cpu.c (ffff8000100f98dc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (ffff8000100fad64)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/softirq.c (ffff8000100fea08)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/ptrace.c (ffff8000101098f0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffff800010110c7c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
```
```
In kernel/sys.c (ffff80001011a4e8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/sys.c:__arm64_sys_prctl
```
```
In kernel/workqueue.c (ffff80001011d93c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
```
```
In kernel/kthread.c (ffff8000101284cc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unpark
```
```
In kernel/sched/core.c (ffff80001013d3e0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffff800010147e28)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
```
```
In kernel/sched/rt.c (ffff8000101502d4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffff800010152bf8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffff800010159fb8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffff80001015a850)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
```
```
In kernel/sched/topology.c (ffff80001015d09c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_clear
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/locking/mutex.c (ffff800010da310c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
```
```
In kernel/locking/rwsem.c (ffff800010169864)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/irq/resend.c (ffff80001017d578)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/irq/resend.c:resend_irqs
```
```
In kernel/irq/chip.c (ffff80001017f844)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/generic-chip.c (ffff800010181400)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
```
In kernel/irq/affinity.c (ffff800010187f6c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/profile.c (ffff800010198968)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/tick-broadcast.c (ffff8000101b26cc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
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
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/kexec_core.c (ffff8000101c9b38)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101daf74)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
```
```
In kernel/cgroup/freezer.c (ffff8000101dd514)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In kernel/cgroup/cpuset.c (ffff8000101e356c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:cpuset_update_task_spread_flag
  - kernel/cgroup/cpuset.c:cpuset_update_task_spread_flag
```
```
In kernel/pid_namespace.c (ffff8000101e7bd4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffff8000101f192c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/watchdog.c (ffff800010207524)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/tracepoint.c (ffff80001020edf8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/trace/trace.c (ffff800010224058)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
```
```
In kernel/trace/trace_events.c (ffff80001023b24c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
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
In kernel/trace/trace_syscalls.c (ffff80001023d558)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (ffff80001024222c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger
  - kernel/trace/trace_events_trigger.c:update_cond_flag
```
```
In kernel/events/core.c (ffff8000102953d8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In kernel/events/ring_buffer.c (ffff8000102a2010)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
```
```
In kernel/events/uprobes.c (ffff8000102a8068)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/padata.c (ffff8000102aa57c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_remove_cpu
```
```
In mm/filemap.c (ffff8000102b293c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
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
In mm/oom_kill.c (ffff8000102b8824)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/page-writeback.c (ffff8000102be6cc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/readahead.c (ffff8000102bf9a0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
```
```
In mm/swap.c (ffff8000102c13b0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_anon
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
```
```
In mm/truncate.c (ffff8000102c3a98)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffff8000102ce7b4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
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
In mm/shmem.c (ffff8000102d347c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/vmstat.c (ffff8000102dbf3c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/gup.c (ffff8000102f0ea0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
```
```
In mm/mlock.c (ffff8000102fd884)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
```
```
In mm/rmap.c (ffff800010309128)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/page_alloc.c (ffff800010319c4c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (ffff80001031f0d8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffff800010320758)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In mm/swap_state.c (ffff800010321448)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/frontswap.c (ffff80001032a4cc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/hugetlb.c (ffff8000103360bc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
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
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffff8000103377cc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
```
```
In mm/sparse.c (ffff80001033cbe0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/ksm.c (ffff80001033fc3c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/memory_hotplug.c (ffff80001034de40)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/migrate.c (ffff800010351a5c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffff800010354acc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
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
In mm/khugepaged.c (ffff80001035dd04)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffff80001036b7c0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:drain_local_stock
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memory-failure.c (ffff80001036e7ac)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffff8000103744b4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
  - mm/zsmalloc.c:reset_page
```
```
In mm/userfaultfd.c (ffff800010378928)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffff8000103796f8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/fs-writeback.c (ffff8000103cb4cc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
```
```
In fs/buffer.c (ffff8000103daf68)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
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
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/mpage.c (ffff8000103e6d8c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/crypto/crypto.c (ffff80001040ab00)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
```
```
In fs/binfmt_elf.c (ffff80001041f4b0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/coredump.c (ffff800010428d14)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffff80001042b104)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/quota/dquot.c (ffff80001043089c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
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
In fs/proc/task_mmu.c (ffff80001043abf8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/proc/base.c (ffff80001043ecf0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - fs/proc/base.c:proc_coredump_filter_write
```
```
In fs/ext4/balloc.c (ffff80001045ff80)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
```
```
In fs/ext4/dir.c (ffff8000104631c8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffff800010464bc0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
```
```
In fs/ext4/extents_status.c (ffff8000104700a0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
```
```
In fs/ext4/file.c (ffff800010471230)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
```
```
In fs/ext4/fsync.c (ffff800010472ccc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffff80001047cc30)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
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
In fs/ext4/inode.c (ffff8000104893dc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_journalled_invalidatepage
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/ioctl.c (ffff80001048acec)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffff800010496874)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/migrate.c (ffff800010498c88)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/mmp.c (ffff800010499110)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/namei.c (ffff8000104a1c7c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
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
In fs/ext4/page-io.c (ffff8000104a4090)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
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
In fs/ext4/readpage.c (ffff8000104a473c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/ext4/super.c (ffff8000104b9020)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffff8000104c5ff8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
```
In fs/ext4/verity.c (ffff8000104c88c0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In fs/jbd2/transaction.c (ffff8000104cc500)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffff8000104ceb8c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/revoke.c (ffff8000104d27a0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffff8000104d8edc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
```
```
In fs/hugetlbfs/inode.c (ffff8000104e1b44)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_huge_page
  - fs/hugetlbfs/inode.c:remove_huge_page
```
```
In fs/ecryptfs/mmap.c (ffff8000104f5aa0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/fuse/dev.c (ffff800010502b84)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/dir.c (ffff800010509570)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffff80001050e964)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_perform_write
```
```
In security/keys/gc.c (ffff80001052d80c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/tomoyo/common.c (ffff80001057c3dc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/integrity/ima/ima_fs.c (ffff8000105ada54)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_release_policy
```
```
In security/integrity/ima/ima_appraise.c (ffff8000105b4bbc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In security/integrity/evm/evm_crypto.c (ffff8000105b61a4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
```
```
In block/blk-core.c (ffff8000105e0cd8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_clear
```
```
In block/blk-mq.c (ffff8000105ef590)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_start_stopped_hw_queues
  - block/blk-mq.c:blk_mq_start_hw_queues
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:flush_busy_ctx
```
```
In block/blk-mq-sched.c (ffff8000105f6b7c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_restart
```
```
In lib/irq_poll.c (ffff800010667c30)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800010673ea0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_free
```
```
In drivers/irqchip/irq-bcm7038-l1.c (ffff80001067726c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_cpu_offline
```
```
In drivers/irqchip/irq-imx-gpcv2.c (ffff800011475e58)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init
```
```
In drivers/irqchip/irq-mvebu-sei.c (ffff80001067aad4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_cp_release_irq
```
```
In drivers/irqchip/qcom-irq-combiner.c (ffff80001067beb4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/irqchip/qcom-irq-combiner.c:combiner_irq_chip_mask_irq
```
```
In drivers/irqchip/irq-meson-gpio.c (ffff80001067c834)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_domain_free
  - drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_domain_alloc
```
```
In drivers/irqchip/irq-ti-sci-inta.c (ffff80001067e990)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_release_resources
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_request_resources
```
```
In drivers/pinctrl/bcm/pinctrl-bcm2835.c (ffff8000106a4288)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_disable
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (ffff8000106af060)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_type
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_mask
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_init_valid_mask
```
```
In drivers/gpio/gpiolib.c (ffff8000106c0328)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
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
In drivers/gpio/gpiolib-sysfs.c (ffff8000106c9798)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
```
```
In drivers/gpio/gpio-stmpe.c (ffff8000106d4b94)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_init_irq_valid_mask
```
```
In drivers/pwm/sysfs.c (ffff8000106d9d8c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:export_store
```
```
In drivers/pci/bus.c (0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
```
```
In drivers/pci/remove.c (ffff8000106e1660)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffff80001071ac00)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffff80001071e050)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_unmap_addr
```
```
In drivers/pci/controller/pcie-rcar.c (ffff8000107216b0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_free
```
```
In drivers/pci/controller/pcie-xilinx.c (ffff800010723530)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_msi_teardown_irq
```
```
In drivers/pci/controller/pcie-rockchip-ep.c (ffff800010729220)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_unmap_addr
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffff80001072f6e4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_unmap_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
```
```
In drivers/acpi/ec.c (ffff800010771508)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/hmat/hmat.c (ffff8000107a6264)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
```
```
In drivers/acpi/battery.c (ffff8000107a7c2c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
```
```
In drivers/clk/clk-fixed-factor.c (ffff8000107c4ec4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-factor.c:_of_fixed_factor_clk_setup
```
```
In drivers/clk/hisilicon/clk-hi3660.c (ffff80001148551c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_crgctrl_of_clk_init_driver
```
```
In drivers/clk/hisilicon/clk-hi6220.c (ffff8000107d1278)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
```
```
In drivers/clk/mediatek/clk-mt6797.c (ffff800011485dd0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/clk/mediatek/clk-mt6797.c:mtk_infra_of_clk_init_driver
```
```
In drivers/clk/mediatek/clk-mt2712.c (ffff800011485f78)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/clk/mediatek/clk-mt2712.c:mt2712_topckgen_of_clk_init_driver
```
```
In drivers/clk/mediatek/clk-mt8183.c (ffff800011486914)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/clk/mediatek/clk-mt8183.c:mt8183_topckgen_of_clk_init_driver
```
```
In drivers/clk/sunxi/clk-mod0.c (ffff80001148cd3c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-mod0.c:sun4i_a10_mod0_of_clk_init_driver
```
```
In drivers/clk/sunxi/clk-sun8i-apb0.c (ffff80001148e4f0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun8i-apb0.c:sun8i_a23_apb0_of_clk_init_driver
```
```
In drivers/dma/dmaengine.c (ffff8000107fd820)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_release_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/soc/fsl/qbman/qman.c (ffff800010816a18)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman.c:qman_destroy_affine_portal
```
```
In drivers/soc/qcom/rpmh-rsc.c (ffff80001081c1ec)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/soc/qcom/rpmh-rsc.c:tcs_tx_done
```
```
In drivers/xen/cpu_hotplug.c (ffff80001082b658)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/xen/grant-table.c (ffff80001082caf0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_pages_clear_private
```
```
In drivers/xen/balloon.c (ffff80001082ee4c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/events/events_2l.c (ffff800010832d78)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_clear_pending
  - drivers/xen/events/events_2l.c:evtchn_2l_bind_to_cpu
```
```
In drivers/xen/events/events_fifo.c (ffff800010833f90)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/xen/events/events_fifo.c:evtchn_fifo_clear_pending
```
```
In drivers/tty/tty_io.c (ffff800010852b74)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kclose
```
```
In drivers/tty/n_tty.c (ffff800010856bb0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_write_wakeup
```
```
In drivers/tty/tty_ioctl.c (ffff80001085bbf0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
```
```
In drivers/tty/tty_ldisc.c (ffff80001085c82c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
```
```
In drivers/tty/tty_port.c (ffff80001085ef9c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/pty.c (ffff800010861aa4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_open
  - drivers/tty/pty.c:pty_open
  - drivers/tty/pty.c:pty_set_lock
```
```
In drivers/tty/sysrq.c (ffff800010864934)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/vt/keyboard.c (ffff80001086beb4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffff8000108810a8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
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
In drivers/tty/serial/max310x.c (ffff8000108994e0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffff8000108aa754)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
```
In drivers/char/misc.c (ffff8000108b2620)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_deregister
  - drivers/char/misc.c:misc_register
```
```
In drivers/char/tpm/tpm-dev.c (ffff8000108b9068)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_release
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/char/tpm/tpm_tis_core.c (ffff8000108c1040)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/iommu/arm-smmu.c (ffff8000108d15d4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_attach_dev
  - drivers/iommu/arm-smmu.c:arm_smmu_domain_free
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d4448)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_domain_finalise_s1
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_domain_free
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_domain_free
```
```
In drivers/lightnvm/core.c (ffff8000108e13e0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/base/cacheinfo.c (ffff8000108f43b8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
```
```
In drivers/base/power/domain.c (ffff800010909a4c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
```
```
In drivers/base/arch_topology.c (ffff800010920908)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:remove_cpu_topology
  - drivers/base/arch_topology.c:remove_cpu_topology
  - drivers/base/arch_topology.c:remove_cpu_topology
```
```
In drivers/nvdimm/dimm_devs.c (ffff800010954614)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
```
```
In drivers/nvdimm/label.c (ffff80001095d7e8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_alloc_slot
```
```
In drivers/nvdimm/security.c (ffff800010961dcc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/dax/super.c (ffff8000109637b0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_write_cache
```
```
In drivers/scsi/scsi_lib.c (ffff80001097925c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/scsi/scsi_sysfs.c (ffff80001097f0cc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
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
In drivers/scsi/sr.c (ffff80001098cec8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_kref_release
```
```
In drivers/ata/libata-scsi.c (ffff8000109a6cbc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_free_tag
```
```
In drivers/spi/spi.c (ffff8000109c4084)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unregister_device
```
```
In drivers/net/tun.c (ffff8000109db5dc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e47d0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_suspend
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_chip_reset
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109ea8e0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fad64)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_open
```
```
In drivers/net/xen-netfront.c (ffff800010a07ca0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:xennet_open
```
```
In drivers/usb/core/hub.c (ffff800010a19454)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffff800010a1f220)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
```
```
In drivers/usb/core/sysfs.c (ffff800010a2b5b8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
```
```
In drivers/usb/core/devio.c (ffff800010a2cd4c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/dwc2/hcd.c (ffff800010a41e38)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
```
```
In drivers/usb/host/ehci-hcd.c (ffff800010a5d738)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:companion_store
```
```
In drivers/usb/host/ohci-hcd.c (ffff800010a65adc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/uhci-hcd.c (ffff800010a6ab9c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
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
In drivers/usb/host/xhci.c (ffff800010a70cb0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
```
```
In drivers/usb/host/xhci-hub.c (ffff800010a87138)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
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
In drivers/input/mousedev.c (ffff800010a9cf08)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/rtc/rtc-sun6i.c (ffff800010aade40)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffff800010ab0310)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
```
```
In drivers/i2c/i2c-core-of.c (ffff800010ab6eb8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
```
```
In drivers/i2c/busses/i2c-sprd.c (ffff800010abc9d0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_resume_noirq
```
```
In drivers/media/cec/cec-core.c (ffff800010abe130)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/media/cec/cec-core.c:cec_devnode_release
```
```
In drivers/watchdog/watchdog_dev.c (ffff800010adfbd4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/watchdog/watchdog_dev.c:watchdog_write
```
```
In drivers/md/md.c (ffff800010ae9a9c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:super_written
```
```
In drivers/md/md-bitmap.c (ffff800010af9c3c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
```
```
In drivers/md/dm.c (ffff800010afcfdc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_queue_flush
  - drivers/md/dm.c:dm_cancel_deferred_remove
```
```
In drivers/md/dm-kcopyd.c (ffff800010b0be7c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
```
In drivers/cpufreq/cpufreq.c (ffff800010b1ff3c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In drivers/leds/led-core.c (ffff800010b48db8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/firmware/ti_sci.c (ffff800010b519dc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/firmware/ti_sci.c:ti_sci_release_resource
```
```
In drivers/firmware/arm_scmi/driver.c (ffff800010b56800)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
```
```
In drivers/firmware/efi/efi.c (ffff8000114a56d0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
```
In drivers/firmware/efi/memmap.c (ffff8000114a6910)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
```
In drivers/clocksource/arm_arch_timer.c (ffff800010b678f0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_dying_cpu
```
```
In drivers/of/platform.c (ffff800010b6dc4c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_bus_create
  - drivers/of/platform.c:of_platform_device_create_pdata
```
```
In drivers/of/dynamic.c (ffff800010b70858)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/of/dynamic.c:__of_attach_node
```
```
In drivers/of/irq.c (ffff8000114ac1b0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/of/irq.c:of_irq_init
```
```
In drivers/perf/arm-cci.c (ffff800010b91528)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_del
```
```
In drivers/perf/arm-ccn.c (ffff800010b9369c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_event_del
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_event_del
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_event_del
```
```
In drivers/perf/hisilicon/hisi_uncore_pmu.c (ffff800010b968f0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_del
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b99ba8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:l2cache_pmu_offline_cpu
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_del
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_del
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9c274)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - drivers/perf/xgene_pmu.c:xgene_perf_del
```
```
In net/core/sock.c (ffff800010bac3d8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/stream.c (ffff800010bbd7e0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_write_space
```
```
In net/core/dev.c (ffff800010bcb354)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
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
In net/core/link_watch.c (ffff800010bf3c78)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/skmsg.c (ffff800010c100cc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/netpoll.c (ffff800010c11158)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/core/gro_cells.c (ffff800010c30e04)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
```
```
In net/sched/sch_generic.c (ffff800010c3a2d0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/netlink/af_netlink.c (ffff800010c4d738)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
```
```
In net/netlink/genetlink.c (ffff800010c52614)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_unregister_family
```
```
In net/ipv4/tcp.c (ffff800010c74f00)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_output.c (ffff800010c875a8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd44cc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffff800010cf2528)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/ncsi/ncsi-rsp.c (ffff800010d76d70)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
```
```
In net/ncsi/ncsi-manage.c (ffff800010d7accc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
```
In lib/vsprintf.c (ffff800010d98904)
Location: arch/arm64/include/asm/atomic_ll_sc.h:229
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
