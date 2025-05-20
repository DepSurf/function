# Function: <code>arch_atomic64_read</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007455)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009547)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a088)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100aa04)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
```
In arch/x86/events/msr.c (ffffffff8100b113)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/bts.c (ffffffff8100e380)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff8100e7ac)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff810126e5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101565e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In arch/x86/kernel/kgdb.c (ffffffff8106a5ff)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
```
```
In arch/x86/kernel/pvclock.c (ffffffff8106e6e3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In arch/x86/mm/tlb.c (ffffffff8107d89b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81088275)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
```
```
In kernel/fork.c (ffffffff8108b823)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/fork.c:copy_mm
  - kernel/fork.c:copy_mm
  - kernel/fork.c:copy_mm
  - kernel/fork.c:copy_mm
  - kernel/fork.c:get_task_exe_file
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In kernel/exit.c (ffffffff81093830)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff810a82b9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/workqueue.c (ffffffff810b04e0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:pwq_activate_delayed_work
  - kernel/workqueue.c:get_work_pool
```
```
In kernel/params.c (ffffffff810b22f1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/params.c:param_array_get
  - kernel/params.c:param_array_set
```
```
In kernel/sched/loadavg.c (ffffffff810c321a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
```
```
In kernel/sched/fair.c (ffffffff810c96d1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
```
```
In kernel/sched/debug.c (ffffffff810dfd8c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
```
```
In kernel/locking/mutex.c (ffffffff819ee0a2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem-xadd.c (ffffffff819efe73)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In kernel/power/snapshot.c (ffffffff810ed749)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In kernel/power/swap.c (ffffffff810ee5eb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81121f1f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
```
```
In kernel/acct.c (ffffffff81136502)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81143875)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811462a5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/cgroup/freezer.c (ffffffff8114698b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff81146b76)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_current_read
```
```
In kernel/cgroup/rdma.c (ffffffff81147a11)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8114c183)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/audit_watch.c (ffffffff811591b3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/seccomp.c (ffffffff8116bd37)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In kernel/tsacct.c (ffffffff8116f252)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In kernel/trace/ring_buffer.c (ffffffff8117b8bd)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_iter_empty
  - kernel/trace/ring_buffer.c:ring_buffer_iter_empty
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:ring_buffer_page_len
```
```
In kernel/trace/trace.c (ffffffff81181f20)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/tracing_map.c (ffffffff81189580)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_cmp_atomic64
  - kernel/trace/tracing_map.c:tracing_map_cmp_atomic64
  - kernel/trace/tracing_map.c:tracing_map_read_var_once
  - kernel/trace/tracing_map.c:tracing_map_read_var
  - kernel/trace/tracing_map.c:tracing_map_read_sum
```
```
In kernel/trace/trace_events_hist.c (ffffffff8119fcbf)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ae6e6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/syscall.c (ffffffff811b537b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_precharge_memlock
```
```
In kernel/events/core.c (ffffffff811e1805)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_swevent_overflow
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:free_event
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_out
```
```
In kernel/events/ring_buffer.c (ffffffff811e287f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - kernel/events/ring_buffer.c:perf_output_put_handle
```
```
In kernel/events/hw_breakpoint.c (ffffffff811e4005)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
```
```
In kernel/memremap.c (ffffffff811e96e9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/memremap.c:get_dev_pagemap
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/oom_kill.c (ffffffff811f3cfe)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
```
```
In mm/page_alloc.c (ffffffff82702446)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:pm_restrict_gfp_mask
  - mm/page_alloc.c:pm_restore_gfp_mask
```
```
In mm/page-writeback.c (ffffffff811fef71)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:__wb_calc_thresh
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/vmscan.c (ffffffff81205ff5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/util.c (ffffffff81214b50)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
```
```
In mm/vmstat.c (ffffffff812173a3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_numa_state
  - mm/vmstat.c:sum_zone_node_page_state
```
```
In mm/backing-dev.c (ffffffff8121907a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/compaction.c (ffffffff8122344a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
```
In mm/workingset.c (ffffffff81225910)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/memory.c (ffffffff8122c673)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffff81238c82)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff8123f77a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81244b6f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/swap_state.c (ffffffff81248486)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swapfile.c (ffffffff8124e359)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swapfile.c:si_swapinfo
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/swap_slots.c (ffffffff8124ec91)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/hugetlb.c (ffffffff81255175)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_report_usage
```
```
In mm/mmu_notifier.c (ffffffff8125e5c5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mm_has_blockable_invalidate_notifiers
```
```
In mm/slub.c (ffffffff8126a712)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:get_slabinfo
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:store_user_store
  - mm/slub.c:poison_store
  - mm/slub.c:red_zone_store
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:list_locations
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:slab_out_of_memory
```
```
In mm/page_counter.c (ffffffff8127e556)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff8127e90c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/hugetlb_cgroup.c (ffffffff81287934)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/zsmalloc.c (ffffffff8128cb55)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_zpool_total_size
```
```
In mm/hmm.c (ffffffff812928a9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_release
```
```
In fs/open.c (ffffffff81294ab5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/open.c:filp_close
```
```
In fs/file_table.c (ffffffff8270b294)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/exec.c (ffffffff812a2359)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/namei.c (ffffffff812a7c74)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/dcache.c (ffffffff812b4db6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/dcache.c:dentry_update_name_case
```
```
In fs/inode.c (ffffffff812b8d79)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:generic_update_time
  - fs/inode.c:__destroy_inode
```
```
In fs/attr.c (ffffffff812bb198)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/file.c (ffffffff812bca06)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/file.c:__fdget_pos
  - fs/file.c:__fget
```
```
In fs/namespace.c (ffffffff812bf345)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/namespace.c:sb_prepare_remount_readonly
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs-writeback.c (ffffffff812cc231)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:get_nr_dirty_pages
  - fs/fs-writeback.c:get_nr_dirty_pages
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/sync.c (ffffffff812d25f5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/nsfs.c (ffffffff812d5ab6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/notify/mark.c (ffffffff812e5b04)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/eventpoll.c (ffffffff812eb9d5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/userfaultfd.c (ffffffff812f12d8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff812f290b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/quota/dquot.c (ffffffff81311d85)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/proc/task_mmu.c (ffffffff81317412)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/array.c (ffffffff813219f8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/meminfo.c (ffffffff81323f91)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/ext4/balloc.c (ffffffff81335944)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/dir.c (ffffffff81337a8f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8134189d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:__ext4_ext_dirty
```
```
In fs/ext4/ialloc.c (ffffffff81346384)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8134e26e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff81355497)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/namei.c (ffffffff8136f59d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/super.c (ffffffff813833ab)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/sysfs.c (ffffffff8138c2d7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In fs/ext4/xattr.c (ffffffff8138e3d5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/jbd2/journal.c (ffffffff8139ce5b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
```
In fs/fat/dir.c (ffffffff813a7fcc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff813aed6a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/namei_vfat.c (ffffffff813b27f4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/ecryptfs/crypto.c (ffffffff813b91e5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
```
In fs/fuse/dir.c (ffffffff813c6eda)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_set_nowrite
```
```
In fs/pstore/inode.c (ffffffff813d3f1d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
```
```
In security/integrity/ima/ima_fs.c (ffffffff81450d3a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
```
```
In security/integrity/ima/ima_main.c (ffffffff81451d1f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In security/integrity/ima/ima_api.c (ffffffff814536a7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-core.c (ffffffff8148472d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-ioc.c (ffffffff81489025)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In block/blk-mq.c (ffffffff8148f22f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq.c:blk_mq_freeze_queue_wait
```
```
In block/blk-cgroup.c (ffffffff814a8407)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:__blkg_prfill_rwstat
  - block/blk-cgroup.c:__blkg_prfill_rwstat
  - block/blk-cgroup.c:__blkg_prfill_rwstat
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
```
```
In block/cfq-iosched.c (ffffffff814afb2e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfqg_prfill_sectors_recursive
  - block/cfq-iosched.c:cfqg_prfill_sectors_recursive
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:blkg_rwstat_total
  - block/cfq-iosched.c:blkg_rwstat_total
```
```
In lib/percpu-refcount.c (ffffffff814cb803)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff814d520f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_avail
  - lib/genalloc.c:gen_pool_alloc_algo
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815f02f0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
```
In drivers/tty/tty_io.c (ffffffff81610d8a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
```
In drivers/tty/n_tty.c (ffffffff81614730)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/char/hw_random/core.c (ffffffff8164eb2b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:add_early_randomness
```
```
In drivers/iommu/iova.c (ffffffff81664db3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/base/component.c (ffffffff8167c215)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
```
In drivers/nvdimm/core.c (ffffffff816d1670)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816e2f9d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff8172d097)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc
```
```
In drivers/net/phy/phy_device.c (ffffffff81736f35)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:__phy_resume
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81739865)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/usb/core/devio.c (ffffffff81767062)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff817f07a5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/md.c:mismatch_cnt_show
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/dm.c (ffffffff81809ca5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_set_md_type
```
```
In drivers/firmware/efi/cper.c (ffffffff818483d5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In drivers/devfreq/devfreq.c (ffffffff8185bea3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:update_devfreq
  - drivers/devfreq/devfreq.c:find_devfreq_governor
```
```
In net/core/sock.c (ffffffff81876646)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/core/skbuff.c (ffffffff8187b631)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/core/dev.c (ffffffff8188bc80)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
```
```
In net/core/rtnetlink.c (ffffffff818ab293)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
```
```
In net/core/sock_diag.c (ffffffff818b8e65)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff818f32cc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f3f46)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff818fb11f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff8190034d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/inet_fragment.c (ffffffff819392cb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/ipv4/proc.c (ffffffff8193e38a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/proc.c:icmpmsg_put
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/unix/af_unix.c (ffffffff81959b51)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff8195d88e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_notinflight
```
```
In net/ipv6/addrconf.c (ffffffff8196611b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/proc.c (ffffffff819a3f64)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:sockstat6_seq_show
```
```
In net/packet/af_packet.c (ffffffff819b245d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff819cd148)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/show_mem.c (ffffffff819d8127)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
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
In arch/x86/events/core.c (ffffffff81007335)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009457)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff81009fb8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100a934)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
```
In arch/x86/events/msr.c (ffffffff8100b073)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/bts.c (ffffffff8100e850)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff8100ec7c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81012de5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015d77)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81052a95)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
```
In arch/x86/kernel/kgdb.c (ffffffff8107038f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
```
```
In arch/x86/kernel/pvclock.c (ffffffff81074703)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In arch/x86/mm/tlb.c (ffffffff810843c4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff8108fad5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
```
```
In kernel/fork.c (ffffffff81096596)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/fork.c:sysctl_max_threads
  - kernel/fork.c:get_mm_exe_file
  - kernel/fork.c:fork_init
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In kernel/exit.c (ffffffff8109baf6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff810b0fc9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/workqueue.c (ffffffff810b9620)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:pwq_activate_delayed_work
  - kernel/workqueue.c:get_work_pool
```
```
In kernel/params.c (ffffffff810baf91)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/params.c:param_array_get
  - kernel/params.c:param_array_set
```
```
In kernel/sched/loadavg.c (ffffffff810cc4ca)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
```
```
In kernel/sched/fair.c (ffffffff810d3ab1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
```
```
In kernel/sched/debug.c (ffffffff810ea50c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
```
```
In kernel/locking/mutex.c (ffffffff81a29312)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_wound
```
```
In kernel/locking/rwsem-xadd.c (ffffffff81a2b8a5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed
```
```
In kernel/power/snapshot.c (ffffffff810f8db1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_image_size_init
```
```
In kernel/power/swap.c (ffffffff810f9c5b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112d63f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
```
```
In kernel/acct.c (ffffffff81141c92)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/kexec_core.c (ffffffff81142641)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In kernel/cgroup/cgroup.c (ffffffff8114f395)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81151e3c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/cgroup/freezer.c (ffffffff8115265a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff811526f6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_current_read
```
```
In kernel/cgroup/rdma.c (ffffffff811532d1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81158dcb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/audit_watch.c (ffffffff81166153)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/seccomp.c (ffffffff81179776)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In kernel/tsacct.c (ffffffff8117cd52)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In kernel/trace/ring_buffer.c (ffffffff811889a4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_iter_empty
  - kernel/trace/ring_buffer.c:ring_buffer_iter_empty
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:ring_buffer_nr_dirty_pages
  - kernel/trace/ring_buffer.c:ring_buffer_nr_dirty_pages
  - kernel/trace/ring_buffer.c:ring_buffer_page_len
```
```
In kernel/trace/trace.c (ffffffff8118f8e0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/tracing_map.c (ffffffff81196e30)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_cmp_atomic64
  - kernel/trace/tracing_map.c:tracing_map_cmp_atomic64
  - kernel/trace/tracing_map.c:tracing_map_read_var_once
  - kernel/trace/tracing_map.c:tracing_map_read_var
  - kernel/trace/tracing_map.c:tracing_map_read_sum
```
```
In kernel/trace/trace_events_hist.c (ffffffff811aedcf)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
```
```
In kernel/trace/trace_uprobe.c (ffffffff811bcd5a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/syscall.c (ffffffff811c324e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_precharge_memlock
```
```
In kernel/events/core.c (ffffffff811f1c75)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_swevent_overflow
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:free_event
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_out
```
```
In kernel/events/ring_buffer.c (ffffffff811f2cef)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - kernel/events/ring_buffer.c:perf_output_put_handle
```
```
In kernel/events/hw_breakpoint.c (ffffffff811f44b5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
```
```
In kernel/memremap.c (ffffffff811fa083)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/memremap.c:get_dev_pagemap
```
```
In mm/oom_kill.c (ffffffff81204992)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
```
```
In mm/page_alloc.c (ffffffff812069b3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:zone_batchsize
  - mm/page_alloc.c:build_zonerefs_node
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo_node
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:pm_restrict_gfp_mask
  - mm/page_alloc.c:pm_restore_gfp_mask
```
```
In mm/page-writeback.c (ffffffff8121182c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:__wb_calc_thresh
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/swap.c (ffffffff828ba043)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/vmscan.c (ffffffff8121b875)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/shmem.c (ffffffff81225809)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_options
```
```
In mm/util.c (ffffffff81227a30)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/util.c:vm_commit_limit
```
```
In mm/vmstat.c (ffffffff8122a2b3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_numa_state
  - mm/vmstat.c:sum_zone_node_page_state
  - mm/vmstat.c:calculate_normal_threshold
```
```
In mm/backing-dev.c (ffffffff8122be3d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/mm_init.c (ffffffff81a253b6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/compaction.c (ffffffff812364aa)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
```
In mm/workingset.c (ffffffff828bd8d6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_refault
```
```
In mm/memory.c (ffffffff8123fcc9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffff8124c642)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff81253e7a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81257639)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap
```
```
In mm/madvise.c (ffffffff81258f25)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/swap_state.c (ffffffff8125ca56)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swapfile.c (ffffffff81262716)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swapfile.c:si_swapinfo
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/swap_slots.c (ffffffff81263173)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff81264b9c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff81269555)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_report_usage
```
```
In mm/sparse.c (ffffffff81272523)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/slub.c (ffffffff8127efa2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:get_slabinfo
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:store_user_store
  - mm/slub.c:poison_store
  - mm/slub.c:red_zone_store
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:list_locations
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:slab_out_of_memory
```
```
In mm/huge_memory.c (ffffffff828c0ae4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In mm/page_counter.c (ffffffff81292c56)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff8129309c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:accumulate_memcg_tree
  - mm/memcontrol.c:accumulate_memcg_tree
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
```
```
In mm/hugetlb_cgroup.c (ffffffff8129c884)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/zsmalloc.c (ffffffff812a1ad5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_zpool_total_size
```
```
In fs/open.c (ffffffff812a9565)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/open.c:filp_close
```
```
In fs/file_table.c (ffffffff828c24ac)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/exec.c (ffffffff812b74ba)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/namei.c (ffffffff812bcd14)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/inode.c (ffffffff812cdeb9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:generic_update_time
  - fs/inode.c:__destroy_inode
```
```
In fs/attr.c (ffffffff812d0388)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/file.c (ffffffff812d1cc6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/file.c:__fdget_pos
  - fs/file.c:__fget
```
```
In fs/namespace.c (ffffffff812d4555)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/namespace.c:sb_prepare_remount_readonly
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs-writeback.c (ffffffff812e1171)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:get_nr_dirty_pages
  - fs/fs-writeback.c:get_nr_dirty_pages
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/sync.c (ffffffff812e79d5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/nsfs.c (ffffffff812eae86)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/notify/fsnotify.c (ffffffff812f972e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/notify/mark.c (ffffffff812fa6fa)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/eventpoll.c (ffffffff812ffc15)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/userfaultfd.c (ffffffff81305c98)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff81306a15)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/quota/dquot.c (ffffffff81328905)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/proc/task_mmu.c (ffffffff8132e887)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/base.c (ffffffff81332915)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/proc/array.c (ffffffff81338b08)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/meminfo.c (ffffffff8133b0e1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/ext4/balloc.c (ffffffff8134cbc4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/dir.c (ffffffff8134ed0f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff81358eed)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:__ext4_ext_dirty
```
```
In fs/ext4/ialloc.c (ffffffff8135eafb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inline.c (ffffffff8136640e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff8136d7c6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/namei.c (ffffffff81387a2d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/super.c (ffffffff8139bdcb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/sysfs.c (ffffffff813a4d27)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In fs/ext4/xattr.c (ffffffff813a699e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/jbd2/journal.c (ffffffff813b5bcb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
```
In fs/fat/dir.c (ffffffff813c0dba)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff813c7f49)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff813c988a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff813cbee5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/ecryptfs/crypto.c (ffffffff813d2755)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
```
In fs/fuse/dir.c (ffffffff813e00ca)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/inode.c (ffffffff828cc8cf)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
```
```
In fs/fuse/readdir.c (ffffffff813ea007)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
```
```
In fs/pstore/inode.c (ffffffff813ee5ad)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
```
```
In security/integrity/ima/ima_fs.c (ffffffff8146dd1a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
```
```
In security/integrity/ima/ima_main.c (ffffffff8146ecdf)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In security/integrity/ima/ima_api.c (ffffffff81470887)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/bio.c (ffffffff81498148)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In block/blk-core.c (ffffffff8149f6f2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-ioc.c (ffffffff814a2f55)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In block/blk-mq.c (ffffffff814a7b3f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq.c:blk_mq_freeze_queue_wait
```
```
In block/blk-mq-tag.c (ffffffff814ad4ac)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/genhd.c (ffffffff814b2076)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/genhd.c:part_in_flight_rw
  - block/genhd.c:part_in_flight_rw
```
```
In block/blk-cgroup.c (ffffffff814c33ac)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:__blkg_prfill_rwstat
  - block/blk-cgroup.c:__blkg_prfill_rwstat
  - block/blk-cgroup.c:__blkg_prfill_rwstat
  - block/blk-cgroup.c:__blkg_prfill_rwstat
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-pm.c (ffffffff814d5f37)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In lib/percpu-refcount.c (ffffffff814e0565)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff814e9c5f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_avail
  - lib/genalloc.c:gen_pool_alloc_algo
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8160a8d0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
```
In drivers/xen/xen-selfballoon.c (ffffffff8161caa7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/xen/xen-selfballoon.c:xen_selfballoon_init
  - drivers/xen/xen-selfballoon.c:selfballoon_process
  - drivers/xen/xen-selfballoon.c:selfballoon_process
```
```
In drivers/tty/tty_io.c (ffffffff8162de76)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
```
In drivers/tty/n_tty.c (ffffffff81631460)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/tty/tty_ldsem.c (ffffffff816379a5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
```
```
In drivers/char/hw_random/core.c (ffffffff8166c5fb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:add_early_randomness
```
```
In drivers/char/agp/backend.c (ffffffff8166cf02)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_add_bridge
```
```
In drivers/iommu/iova.c (ffffffff816833b3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/base/component.c (ffffffff8169bd15)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
```
In drivers/nvdimm/core.c (ffffffff816f2d00)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8170632d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff8174f8a7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc
```
```
In drivers/net/phy/phy.c (ffffffff81758105)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff8175a0e5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:__phy_resume
```
```
In drivers/net/phy/mdio_bus.c (ffffffff8175d395)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/usb/core/devio.c (ffffffff8178b5e2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff8181c695)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/md.c:mismatch_cnt_show
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/dm.c (ffffffff81833ebd)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm.c:dm_set_md_type
```
```
In drivers/md/dm-stats.c (ffffffff81840485)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
```
In drivers/firmware/efi/cper.c (ffffffff81874625)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In drivers/devfreq/devfreq.c (ffffffff8187b9cd)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:find_devfreq_governor
```
```
In net/core/sock.c (ffffffff81896ed6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/core/skbuff.c (ffffffff8189c471)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/core/dev.c (ffffffff818ace60)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
```
```
In net/core/rtnetlink.c (ffffffff818ced1d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
```
```
In net/core/sock_diag.c (ffffffff818dfab5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81920dec)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81921a66)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff8192904d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff8192a75d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_metrics.c (ffffffff8194335f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81968e8b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/ipv4/proc.c (ffffffff8196e22a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/proc.c:icmpmsg_put
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/unix/af_unix.c (ffffffff8198e6d1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff819923ce)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_notinflight
```
```
In net/ipv6/addrconf.c (ffffffff8199b58b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/proc.c (ffffffff819daa74)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:sockstat6_seq_show
```
```
In net/packet/af_packet.c (ffffffff819e965e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81a064ad)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/show_mem.c (ffffffff81a102ed)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
  - lib/show_mem.c:show_mem
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
In arch/x86/events/core.c (ffffffff81007605)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff8100994e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a494)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100ade4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
```
In arch/x86/events/msr.c (ffffffff8100b543)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/bts.c (ffffffff8100f113)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f572)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81014175)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017385)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81055c45)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
```
In arch/x86/kernel/kgdb.c (ffffffff81074416)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
```
```
In arch/x86/kernel/pvclock.c (ffffffff8107825b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In arch/x86/mm/tlb.c (ffffffff81088044)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81093765)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
```
```
In kernel/fork.c (ffffffff8109aad6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/fork.c:sysctl_max_threads
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:get_mm_exe_file
  - kernel/fork.c:fork_init
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In kernel/exit.c (ffffffff810a03ed)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff810b6b06)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/workqueue.c (ffffffff810bf34a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:pwq_activate_delayed_work
  - kernel/workqueue.c:get_work_pool
```
```
In kernel/params.c (ffffffff810c0eb1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/params.c:param_array_get
  - kernel/params.c:param_array_set
```
```
In kernel/sched/loadavg.c (ffffffff810d490a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
```
```
In kernel/sched/fair.c (ffffffff810dafb4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
```
```
In kernel/sched/debug.c (ffffffff810f12f7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
```
```
In kernel/locking/mutex.c (ffffffff81a9a485)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_trylock
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_wound
```
```
In kernel/locking/rwsem.c (ffffffff810f7dab)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/power/snapshot.c (ffffffff8110142b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_image_size_init
```
```
In kernel/power/swap.c (ffffffff8110233f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113808e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
```
```
In kernel/acct.c (ffffffff8114d05f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/kexec_core.c (ffffffff8114da4a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In kernel/cgroup/cgroup.c (ffffffff8115b226)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115db72)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8115ecc0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff8115ed57)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_current_read
```
```
In kernel/cgroup/rdma.c (ffffffff8115fbc3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811654cb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/audit_watch.c (ffffffff81172c78)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/seccomp.c (ffffffff81185f14)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/tsacct.c (ffffffff81189c12)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In kernel/trace/ring_buffer.c (ffffffff81196134)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_iter_empty
  - kernel/trace/ring_buffer.c:ring_buffer_iter_empty
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:ring_buffer_nr_dirty_pages
  - kernel/trace/ring_buffer.c:ring_buffer_nr_dirty_pages
```
```
In kernel/trace/trace.c (ffffffff8119d310)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/tracing_map.c (ffffffff811a4cd0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_cmp_atomic64
  - kernel/trace/tracing_map.c:tracing_map_cmp_atomic64
  - kernel/trace/tracing_map.c:tracing_map_read_var_once
  - kernel/trace/tracing_map.c:tracing_map_read_var
  - kernel/trace/tracing_map.c:tracing_map_read_sum
```
```
In kernel/trace/trace_events_hist.c (ffffffff811bd57e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cc461)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/cgroup.c (ffffffff811f7377)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
```
```
In kernel/events/core.c (ffffffff81209840)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_swevent_overflow
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:free_event
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_out
```
```
In kernel/events/ring_buffer.c (ffffffff8120a9ca)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - kernel/events/ring_buffer.c:perf_output_put_handle
```
```
In kernel/events/hw_breakpoint.c (ffffffff8120c185)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
```
```
In mm/oom_kill.c (ffffffff8121c13e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
```
```
In mm/page-writeback.c (ffffffff81220e4f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:__wb_calc_thresh
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/swap.c (ffffffff828d1464)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/vmscan.c (ffffffff8122b505)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/shmem.c (ffffffff812329c9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_options
```
```
In mm/util.c (ffffffff812377c8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:vm_commit_limit
```
```
In mm/vmstat.c (ffffffff81239f3b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_numa_state
  - mm/vmstat.c:sum_zone_node_page_state
  - mm/vmstat.c:calculate_normal_threshold
```
```
In mm/backing-dev.c (ffffffff8123b803)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/mm_init.c (ffffffff81a9513d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/compaction.c (ffffffff812479af)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
```
In mm/workingset.c (ffffffff828d4ed0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
  - mm/workingset.c:workingset_refault
```
```
In mm/memory.c (ffffffff81251e0f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffff8125ea72)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff8126612a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8126a419)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:vmalloc_nr_pages
```
```
In mm/page_alloc.c (ffffffff8126c9e6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:zone_batchsize
  - mm/page_alloc.c:build_zonerefs_node
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo_node
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:pm_restrict_gfp_mask
  - mm/page_alloc.c:pm_restore_gfp_mask
```
```
In mm/madvise.c (ffffffff8127474d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/swap_state.c (ffffffff81277c4b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swapfile.c (ffffffff8127d602)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swapfile.c:si_swapinfo
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/swap_slots.c (ffffffff8127e0e3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff8127f7bc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff812846d5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_report_usage
```
```
In mm/sparse.c (ffffffff8128dd03)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/slub.c (ffffffff8129ae42)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:get_slabinfo
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:store_user_store
  - mm/slub.c:poison_store
  - mm/slub.c:red_zone_store
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:list_locations
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:alloc_slab_page
```
```
In mm/huge_memory.c (ffffffff828d9e6f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In mm/page_counter.c (ffffffff812ad5e6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff812ad97c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_exact_page_state
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff812b7a43)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/zsmalloc.c (ffffffff812bd057)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_zpool_total_size
```
```
In mm/memremap.c (ffffffff812c24cf)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/open.c (ffffffff812c5cd5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/open.c:filp_close
```
```
In fs/file_table.c (ffffffff828db87a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/exec.c (ffffffff812d4f40)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/namei.c (ffffffff812d9825)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/inode.c (ffffffff812eacf1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:generic_update_time
  - fs/inode.c:__destroy_inode
```
```
In fs/attr.c (ffffffff812ed3a3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/file.c (ffffffff812eecf6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/file.c:__fdget_pos
  - fs/file.c:__fget
```
```
In fs/namespace.c (ffffffff812f1a65)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/namespace.c:sb_prepare_remount_readonly
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs-writeback.c (ffffffff812ff8d1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/sync.c (ffffffff81306285)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/nsfs.c (ffffffff81309907)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/notify/fsnotify.c (ffffffff81319d95)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/notify/mark.c (ffffffff8131b0ea)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/eventpoll.c (ffffffff81320c3a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/userfaultfd.c (ffffffff8132721b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff8132800e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff81330ef7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_submit_sqe
```
```
In fs/quota/dquot.c (ffffffff81350485)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/proc/task_mmu.c (ffffffff8135732a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/base.c (ffffffff8135a8a5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/proc/array.c (ffffffff813611aa)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/meminfo.c (ffffffff813632a1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/ext4/balloc.c (ffffffff813755e4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/dir.c (ffffffff81377abf)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff81381e6d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:__ext4_ext_dirty
```
```
In fs/ext4/ialloc.c (ffffffff81387cd9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inline.c (ffffffff8138f79b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff81396db0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/namei.c (ffffffff813b1a9d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/super.c (ffffffff813c4918)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/sysfs.c (ffffffff813ceeb3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In fs/ext4/xattr.c (ffffffff813d1217)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/jbd2/journal.c (ffffffff813e0b5d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
```
In fs/fat/dir.c (ffffffff813eb60a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff813f2b32)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff813f4428)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff813f66f4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/ecryptfs/crypto.c (ffffffff813fd1f5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
```
In fs/fuse/dir.c (ffffffff8140bcbf)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/file.c (ffffffff8140e5a1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/inode.c (ffffffff828e623e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
```
```
In fs/fuse/readdir.c (ffffffff814168ab)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/pstore/inode.c (ffffffff8141a85d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
```
```
In security/integrity/ima/ima_fs.c (ffffffff8149b3eb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
```
```
In security/integrity/ima/ima_main.c (ffffffff8149c6ec)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In security/integrity/ima/ima_api.c (ffffffff8149e237)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/bio.c (ffffffff814c5fe8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In block/blk-core.c (ffffffff814cd81a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-ioc.c (ffffffff814d1005)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In block/blk-mq.c (ffffffff814d5ba9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq.c:blk_mq_freeze_queue_wait
```
```
In block/blk-mq-tag.c (ffffffff814db73e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/genhd.c (ffffffff814e04be)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/genhd.c:part_in_flight_rw
  - block/genhd.c:part_in_flight_rw
```
```
In block/blk-cgroup.c (ffffffff814f1ab6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-pm.c (ffffffff81501d92)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In lib/percpu-refcount.c (ffffffff8150c505)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff81516880)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_avail
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8163e6d0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
```
In drivers/tty/tty_io.c (ffffffff81661a46)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
```
In drivers/tty/n_tty.c (ffffffff8166543e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/tty/tty_ldsem.c (ffffffff8166bc75)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
```
```
In drivers/char/hw_random/core.c (ffffffff816a2191)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:add_early_randomness
```
```
In drivers/char/agp/backend.c (ffffffff816a2b10)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_add_bridge
```
```
In drivers/iommu/iova.c (ffffffff816ba96c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/base/component.c (ffffffff816d4835)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
```
In drivers/nvdimm/core.c (ffffffff8172c2cf)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/dma-buf/dma-buf.c (ffffffff817409df)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_show_fdinfo
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff8178b6f9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc
```
```
In drivers/net/phy/phy.c (ffffffff81794ae5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff81797dfa)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:__phy_resume
```
```
In drivers/net/phy/mdio_bus.c (ffffffff8179a925)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/usb/core/devio.c (ffffffff817c9bf3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff8185e8f5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/md.c:mismatch_cnt_show
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/dm.c (ffffffff81875ca1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm.c:dm_set_md_type
```
```
In drivers/md/dm-stats.c (ffffffff81883346)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
```
In drivers/firmware/efi/cper.c (ffffffff818b8885)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In drivers/soundwire/stream.c (ffffffff818c4ef4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/soundwire/stream.c:do_bank_switch
```
```
In drivers/devfreq/devfreq.c (ffffffff818c5be5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:try_then_request_governor
  - drivers/devfreq/devfreq.c:find_devfreq_governor
```
```
In net/core/sock.c (ffffffff818e119a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/core/skbuff.c (ffffffff818e6cf1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/core/dev.c (ffffffff818f85e0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
```
```
In net/core/rtnetlink.c (ffffffff8191bad1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
```
```
In net/core/sock_diag.c (ffffffff8192e105)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819837b5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81984420)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff8198bf60)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff8198d9ca)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a7903)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfd6b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/ipv4/proc.c (ffffffff819d79d8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/proc.c:icmpmsg_put
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/unix/af_unix.c (ffffffff819f9e21)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff819fd9ed)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/unix/scm.c (ffffffff819fe01b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/addrconf.c (ffffffff81a074bb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/proc.c (ffffffff81a4970d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:sockstat6_seq_show
```
```
In net/packet/af_packet.c (ffffffff81a57a67)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81a75dd8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/show_mem.c (ffffffff81a7f881)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
  - lib/show_mem.c:show_mem
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
In arch/x86/events/core.c (ffffffff81007785)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009d3e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100aa54)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100b1f4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
```
In arch/x86/events/msr.c (ffffffff8100b953)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/bts.c (ffffffff8100f7c3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fc3a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81014ad5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017d35)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056585)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
```
In arch/x86/kernel/pvclock.c (ffffffff810792cb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In arch/x86/mm/tlb.c (ffffffff81088d04)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109921a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_get_local64
```
```
In kernel/fork.c (ffffffff8109ff7f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:get_mm_exe_file
  - kernel/fork.c:fork_init
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In kernel/exit.c (ffffffff810a640b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff810bd0c6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/workqueue.c (ffffffff810c576b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:pwq_activate_delayed_work
  - kernel/workqueue.c:get_work_pool
```
```
In kernel/sched/loadavg.c (ffffffff810deeca)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
```
```
In kernel/sched/fair.c (ffffffff810e4ec4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
```
```
In kernel/sched/debug.c (ffffffff810fcfa7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
```
```
In kernel/locking/mutex.c (ffffffff81ad1dd5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_wound
  - kernel/locking/mutex.c:mutex_trylock_recursive
  - kernel/locking/mutex.c:mutex_trylock_recursive
  - kernel/locking/mutex.c:mutex_is_locked
```
```
In kernel/locking/rwsem.c (ffffffff81103bdb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/power/snapshot.c (ffffffff8110d85e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_image_size_init
```
```
In kernel/power/swap.c (ffffffff8110e750)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81144181)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
```
```
In kernel/futex.c (ffffffff8114a868)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/acct.c (ffffffff81158d2f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/kexec_core.c (ffffffff8115975a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In kernel/cgroup/cgroup.c (ffffffff81166ee4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81169782)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116a920)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff8116a9b7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_current_read
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/cgroup/rdma.c (ffffffff8116b823)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811713bb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/tsacct.c (ffffffff81195b22)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In kernel/trace/ring_buffer.c (ffffffff811a1b04)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_iter_empty
  - kernel/trace/ring_buffer.c:ring_buffer_iter_empty
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/trace/tracing_map.c (ffffffff811b0500)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_cmp_atomic64
  - kernel/trace/tracing_map.c:tracing_map_cmp_atomic64
  - kernel/trace/tracing_map.c:tracing_map_read_var_once
  - kernel/trace/tracing_map.c:tracing_map_read_var
  - kernel/trace/tracing_map.c:tracing_map_read_sum
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c891e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
```
```
In kernel/bpf/cgroup.c (ffffffff81204337)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
```
```
In kernel/events/core.c (ffffffff81216bb0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_swevent_overflow
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:free_event
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_out
```
```
In kernel/events/ring_buffer.c (ffffffff81217caa)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - kernel/events/ring_buffer.c:perf_output_put_handle
```
```
In mm/oom_kill.c (ffffffff81229ad8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
```
```
In mm/page-writeback.c (ffffffff8122e8ff)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:__wb_calc_thresh
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/swap.c (ffffffff828d98e2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/vmscan.c (ffffffff812393d5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/shmem.c (ffffffff81240a6d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_one
```
```
In mm/util.c (ffffffff81245a18)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:vm_commit_limit
```
```
In mm/vmstat.c (ffffffff8124823b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_numa_state
  - mm/vmstat.c:sum_zone_node_page_state
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/backing-dev.c (ffffffff81248c82)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In mm/mm_init.c (ffffffff81acca1d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/compaction.c (ffffffff81255e0f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
```
In mm/workingset.c (ffffffff828dd35f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
  - mm/workingset.c:workingset_refault
```
```
In mm/memory.c (ffffffff812603bf)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffff81268255)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff81274a4a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81279329)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:vmalloc_nr_pages
```
```
In mm/page_alloc.c (ffffffff8127b7f6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:zone_batchsize
  - mm/page_alloc.c:build_zonerefs_node
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo_node
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__isolate_free_page
```
```
In mm/madvise.c (ffffffff812836dd)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/swap_state.c (ffffffff8128773b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swapfile.c (ffffffff8128d0a2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swapfile.c:si_swapinfo
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/swap_slots.c (ffffffff8128db33)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff8128f5ac)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff81294275)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_report_usage
```
```
In mm/sparse.c (ffffffff8129d9e5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/slub.c (ffffffff812aad02)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:get_slabinfo
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:store_user_store
  - mm/slub.c:poison_store
  - mm/slub.c:red_zone_store
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:list_locations
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:alloc_slab_page
```
```
In mm/huge_memory.c (ffffffff828e2316)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In mm/page_counter.c (ffffffff812bf136)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff812bf4cc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_exact_page_state
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_size
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff812c9923)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/zsmalloc.c (ffffffff812cef47)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_zpool_total_size
```
```
In mm/memremap.c (ffffffff812d43ff)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/open.c (ffffffff812d76e5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/open.c:filp_close
```
```
In fs/file_table.c (ffffffff828e3cb0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/exec.c (ffffffff812e6ac9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/namei.c (ffffffff812eb335)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/inode.c (ffffffff812fc821)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:generic_update_time
  - fs/inode.c:__destroy_inode
```
```
In fs/attr.c (ffffffff812fee07)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/file.c (ffffffff813007b6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/file.c:__fdget_pos
  - fs/file.c:__fget
```
```
In fs/namespace.c (ffffffff81303615)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/namespace.c:sb_prepare_remount_readonly
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs-writeback.c (ffffffff813147f3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/sync.c (ffffffff81319305)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/nsfs.c (ffffffff8131c977)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/notify/fsnotify.c (ffffffff8132cbca)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/eventpoll.c (ffffffff813339da)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/userfaultfd.c (ffffffff81339ffb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff8133adae)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff81344f91)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_get_req
```
```
In fs/quota/dquot.c (ffffffff813687bb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/proc/task_mmu.c (ffffffff8136ee5d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/base.c (ffffffff81372ab5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/proc/array.c (ffffffff8137940a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/meminfo.c (ffffffff8137b501)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/ext4/balloc.c (ffffffff8138d862)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/dir.c (ffffffff8138fe3f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8139a41d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:__ext4_ext_dirty
```
```
In fs/ext4/ialloc.c (ffffffff813a0148)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/ext4/inline.c (ffffffff813a81fb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff813af7e0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/namei.c (ffffffff813caaed)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/super.c (ffffffff813ddc98)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/sysfs.c (ffffffff813e8583)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In fs/ext4/xattr.c (ffffffff813ea8f4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/fat/dir.c (ffffffff81404fba)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff8140caf3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff8140e2f8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff814105c4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/dir.c (ffffffff814240b8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/file.c (ffffffff814273b7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/fuse/inode.c (ffffffff828eed04)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
```
```
In fs/fuse/readdir.c (ffffffff814307cb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/pstore/inode.c (ffffffff814346cd)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
```
```
In security/integrity/ima/ima_fs.c (ffffffff814b562b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
```
```
In security/integrity/ima/ima_main.c (ffffffff814b686c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In security/integrity/ima/ima_api.c (ffffffff814b86d1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/bio.c (ffffffff814de3e8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In block/blk-core.c (ffffffff814e6b0a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-ioc.c (ffffffff814ea3c5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In block/blk-mq.c (ffffffff814eeed9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq.c:blk_mq_freeze_queue_wait
```
```
In block/blk-mq-tag.c (ffffffff814f4b6e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/genhd.c (ffffffff814f98ee)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/genhd.c:part_in_flight_rw
  - block/genhd.c:part_in_flight_rw
```
```
In block/blk-cgroup.c (ffffffff8150b083)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-iocost.c (ffffffff81510ac9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:ioc_now
  - block/blk-iocost.c:ioc_refresh_params
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:trace_event_raw_event_iocost_ioc_vrate_adj
```
```
In block/blk-pm.c (ffffffff8151fcbf)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In lib/percpu-refcount.c (ffffffff8152a355)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff815372c0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_avail
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81660c40)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
```
In drivers/tty/tty_ldsem.c (ffffffff8168e2e5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
```
```
In drivers/char/agp/backend.c (ffffffff816c58a0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_add_bridge
```
```
In drivers/iommu/iova.c (ffffffff816dd7b0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81764bbf)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_show_fdinfo
```
```
In drivers/usb/core/devio.c (ffffffff817fa733)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff81890465)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/md.c:mismatch_cnt_show
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/dm.c (ffffffff818a7aa1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm.c:dm_wait_for_completion
```
```
In drivers/md/dm-stats.c (ffffffff818b51e6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
```
In drivers/firmware/efi/cper.c (ffffffff818eb285)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff8191335a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/core/skbuff.c (ffffffff819190d1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/core/dev.c (ffffffff8192a780)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
```
```
In net/core/sock_diag.c (ffffffff81960395)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819b9fa5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819babd0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff819c28b0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff819c457c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_metrics.c (ffffffff819de993)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81a068fb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/ipv4/proc.c (ffffffff81a0e4c8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/proc.c:icmpmsg_put
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/unix/af_unix.c (ffffffff81a30aa1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81a345dd)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/unix/scm.c (ffffffff81a34c0b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/addrconf.c (ffffffff81a3e02b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/proc.c (ffffffff81a802cd)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:sockstat6_seq_show
```
```
In net/packet/af_packet.c (ffffffff81a8cfc7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81aacb3b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/show_mem.c (ffffffff81ab6a81)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
  - lib/show_mem.c:show_mem
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
In arch/x86/events/core.c (ffffffff810087e5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff8100af10)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100bcce)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/ibs.c:perf_ibs_event_update
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100c4c4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
```
In arch/x86/events/msr.c (ffffffff8100cc63)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/bts.c (ffffffff81010b53)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff8101129a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff8101662a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
```
```
In arch/x86/events/intel/uncore.c (ffffffff810198e5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105b974)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
```
In arch/x86/kernel/pvclock.c (ffffffff810805b1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In arch/x86/mm/tlb.c (ffffffff8108b364)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109e8aa)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_get_local64
```
```
In kernel/fork.c (ffffffff810a7013)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:get_mm_exe_file
  - kernel/fork.c:fork_init
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In kernel/exit.c (ffffffff810ae1ce)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff810c4806)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/workqueue.c (ffffffff810ccf58)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/workqueue.c:show_pwq
  - kernel/workqueue.c:show_pwq
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/loadavg.c (ffffffff810e727a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_nohz
```
```
In kernel/sched/fair.c (ffffffff810ee488)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
```
```
In kernel/sched/debug.c (ffffffff81107749)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
```
```
In kernel/locking/mutex.c (ffffffff81bc9e92)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/mutex.c:mutex_trylock_recursive
  - kernel/locking/mutex.c:mutex_trylock_recursive
  - kernel/locking/mutex.c:mutex_is_locked
```
```
In kernel/locking/rwsem.c (ffffffff8110e76b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/power/snapshot.c (ffffffff81118a05)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_image_size_init
```
```
In kernel/power/swap.c (ffffffff811197db)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:swap_write_page
  - kernel/power/swap.c:swap_write_page
  - kernel/power/swap.c:get_swap_writer
```
```
In kernel/dma/pool.c (ffffffff82cf16eb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_atomic_pool_init
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81153d85)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
```
```
In kernel/futex.c (ffffffff8115b38b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/acct.c (ffffffff8116911c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/acct.c:acct_get
```
```
In kernel/kexec_core.c (ffffffff8116ab12)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In kernel/cgroup/cgroup.c (ffffffff81178557)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117b38d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8117c3de)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff8117c4f7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_current_read
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/cgroup/rdma.c (ffffffff8117d453)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811830cb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/tsacct.c (ffffffff811ab170)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In kernel/trace/ring_buffer.c (ffffffff811b7b1a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_iter_empty
  - kernel/trace/ring_buffer.c:ring_buffer_iter_empty
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_handle_head_page
  - kernel/trace/ring_buffer.c:rb_iter_head_event
  - kernel/trace/ring_buffer.c:rb_iter_head_event
  - kernel/trace/ring_buffer.c:rb_remove_pages
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/trace/tracing_map.c (ffffffff811c8730)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_cmp_atomic64
  - kernel/trace/tracing_map.c:tracing_map_cmp_atomic64
  - kernel/trace/tracing_map.c:tracing_map_read_var_once
  - kernel/trace/tracing_map.c:tracing_map_read_var
  - kernel/trace/tracing_map.c:tracing_map_read_sum
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e2b9b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
```
```
In kernel/bpf/syscall.c (ffffffff81200dbf)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_get_fd_by_id
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
  - kernel/bpf/syscall.c:__bpf_map_inc_not_zero
```
```
In kernel/bpf/task_iter.c (ffffffff812166ed)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In kernel/bpf/cgroup.c (ffffffff8122cdf4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:replace_effective_prog
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
```
```
In kernel/events/core.c (ffffffff81240c2b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:free_event
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:perf_event_context_sched_out
```
```
In kernel/events/ring_buffer.c (ffffffff81243891)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_end
  - kernel/events/ring_buffer.c:perf_output_end
  - kernel/events/ring_buffer.c:perf_output_end
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In mm/oom_kill.c (ffffffff8125692e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reap_task_mm
  - mm/oom_kill.c:oom_reap_task_mm
  - mm/oom_kill.c:oom_reap_task_mm
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/page-writeback.c (ffffffff8125baef)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:__wb_calc_thresh
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/swap.c (ffffffff82cf8934)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
```
```
In mm/vmscan.c (ffffffff8126a975)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/shmem.c (ffffffff81271a2d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_one
```
```
In mm/util.c (ffffffff8127374a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
```
```
In mm/vmstat.c (ffffffff812763bb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_numa_state
  - mm/vmstat.c:sum_zone_node_page_state
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/backing-dev.c (ffffffff81276e82)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In mm/mm_init.c (ffffffff81bc537e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/compaction.c (ffffffff812844ff)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
```
In mm/workingset.c (ffffffff82cfa7e4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/memory.c (ffffffff8129098f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffff81298a05)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff812a5e5a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff812ac558)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:vmalloc_nr_pages
```
```
In mm/page_alloc.c (ffffffff812ad916)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:__setup_per_zone_wmarks
  - mm/page_alloc.c:__setup_per_zone_wmarks
  - mm/page_alloc.c:__setup_per_zone_wmarks
  - mm/page_alloc.c:__setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:zone_batchsize
  - mm/page_alloc.c:build_zonerefs_node
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo_node
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:steal_suitable_fallback
```
```
In mm/madvise.c (ffffffff812b5540)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/swap_state.c (ffffffff812b893d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap_state.c:swap_ra_info
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swapfile.c (ffffffff812bfb3a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swapfile.c:si_swapinfo
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/swap_slots.c (ffffffff812c05f3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff812c224b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff812c7645)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_report_usage
```
```
In mm/sparse.c (ffffffff812d1685)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/slub.c (ffffffff812df4a7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:get_slabinfo
  - mm/slub.c:store_user_store
  - mm/slub.c:poison_store
  - mm/slub.c:red_zone_store
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:list_locations
  - mm/slub.c:validate_slab_node
  - mm/slub.c:validate_slab_node
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:alloc_slab_page
```
```
In mm/huge_memory.c (ffffffff82cff6f0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In mm/page_counter.c (ffffffff812f4446)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff812f47cc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_size
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - mm/memcontrol.c:mem_cgroup_update_tree
```
```
In mm/hugetlb_cgroup.c (ffffffff812fef45)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/zsmalloc.c (ffffffff81305257)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_zpool_total_size
```
```
In mm/memremap.c (ffffffff8130a0b2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/open.c (ffffffff8130d895)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/open.c:filp_close
```
```
In fs/file_table.c (ffffffff82d007f1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/exec.c (ffffffff8131dd4e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
```
```
In fs/namei.c (ffffffff81323fa3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/inode.c (ffffffff81335989)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:__destroy_inode
```
```
In fs/attr.c (ffffffff81337f07)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/file.c (ffffffff813399d6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/file.c:__fdget_pos
  - fs/file.c:__fget_files
```
```
In fs/namespace.c (ffffffff8133d345)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/namespace.c:sb_prepare_remount_readonly
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs-writeback.c (ffffffff8134e2a4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_check_start_all
  - fs/fs-writeback.c:wb_check_start_all
  - fs/fs-writeback.c:wb_check_old_data_flush
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/sync.c (ffffffff813530c5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/nsfs.c (ffffffff813565ff)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/notify/fsnotify.c (ffffffff81366775)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
```
```
In fs/eventpoll.c (ffffffff8136cf16)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_insert
```
```
In fs/aio.c (ffffffff81374ead)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff81385819)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_show_fdinfo
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_submit_sqes
```
```
In fs/quota/dquot.c (ffffffff813b0a7c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/proc/task_mmu.c (ffffffff813b7193)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/base.c (ffffffff813badf5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/proc/array.c (ffffffff813c24b2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/meminfo.c (ffffffff813c4852)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/ext4/balloc.c (ffffffff813d8d22)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/dir.c (ffffffff813db40f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff813e584d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:__ext4_ext_dirty
```
```
In fs/ext4/file.c (ffffffff813e90e3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/ialloc.c (ffffffff813ec158)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/ext4/inline.c (ffffffff813f42ba)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff813fb840)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_break_layouts
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/namei.c (ffffffff81416adb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/super.c (ffffffff814275f8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/sysfs.c (ffffffff814352ab)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In fs/ext4/xattr.c (ffffffff8143688a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/fat/dir.c (ffffffff81452f78)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff8145a15d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff8145c0ec)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff8145e8d1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/dir.c (ffffffff81474e00)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/file.c (ffffffff81477d5e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_send_readpages
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/inode.c (ffffffff8147d2cc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/inode.c:set_global_limit
```
```
In fs/fuse/readdir.c (ffffffff814803bc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/pstore/inode.c (ffffffff81484497)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
```
```
In security/integrity/ima/ima_fs.c (ffffffff8151491b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
```
```
In security/integrity/ima/ima_main.c (ffffffff81515eec)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In security/integrity/ima/ima_api.c (ffffffff81518310)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/bio.c (ffffffff8153d9c2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/bio.c:__bio_associate_blkg
```
```
In block/blk-core.c (ffffffff81544e81)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-ioc.c (ffffffff8154939e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-ioc.c:put_io_context
```
```
In block/blk-mq.c (ffffffff8154f964)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq.c:blk_mq_freeze_queue_wait
```
```
In block/blk-mq-tag.c (ffffffff81555541)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/genhd.c (ffffffff815597d3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/genhd.c:part_inflight_show
  - block/genhd.c:part_inflight_show
  - block/genhd.c:disk_map_sector_rcu
  - block/genhd.c:disk_map_sector_rcu
```
```
In block/blk-cgroup.c (ffffffff8156c004)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_blkg
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-cgroup-rwstat.c (ffffffff8156c41c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
```
```
In block/blk-iocost.c (ffffffff815725b1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:ioc_now
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:trace_event_raw_event_iocost_ioc_vrate_adj
```
```
In block/blk-pm.c (ffffffff81580c4f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In lib/percpu-refcount.c (ffffffff8158da75)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff8159b770)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_avail
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In lib/show_mem.c (ffffffff815f16db)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
  - lib/show_mem.c:show_mem
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8170ffd0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
```
In drivers/tty/tty_ldsem.c (ffffffff817405a5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
```
```
In drivers/char/agp/backend.c (ffffffff8177a095)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_initialize
```
```
In drivers/iommu/iova.c (ffffffff8179458c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:fq_ring_free
```
```
In drivers/iommu/amd/iommu.c (ffffffff8179651b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_set_gcr3
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd/iommu.c:amd_iommu_iova_to_phys
  - drivers/iommu/amd/iommu.c:amd_iommu_unmap
  - drivers/iommu/amd/iommu.c:amd_iommu_map
  - drivers/iommu/amd/iommu.c:protection_domain_free
  - drivers/iommu/amd/iommu.c:update_domain
  - drivers/iommu/amd/iommu.c:do_attach
  - drivers/iommu/amd/iommu.c:fetch_pte
  - drivers/iommu/amd/iommu.c:increase_address_space
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8182548f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_show_fdinfo
```
```
In drivers/net/loopback.c (ffffffff8187e8de)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/net/loopback.c:dev_lstats_read
  - drivers/net/loopback.c:dev_lstats_read
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81886251)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdio_bus_device_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
```
```
In drivers/net/tun.c (ffffffff8188a0c9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_get_stats64
  - drivers/net/tun.c:tun_net_get_stats64
  - drivers/net/tun.c:tun_net_get_stats64
  - drivers/net/tun.c:tun_net_get_stats64
```
```
In drivers/usb/core/devio.c (ffffffff818ca953)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff8195f305)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/md.c:mismatch_cnt_show
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/dm.c (ffffffff819777e2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_bios_completion
  - drivers/md/dm.c:dm_wait_for_bios_completion
```
```
In drivers/md/dm-stats.c (ffffffff81984f32)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:__check_shared_memory
```
```
In drivers/firmware/efi/cper.c (ffffffff819be975)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff819e55f0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/sock.c:proto_seq_printf
  - net/core/sock.c:__sk_mem_reduce_allocated
```
```
In net/core/skbuff.c (ffffffff819ecd3c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/core/net_namespace.c (ffffffff819f9905)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_gen_cookie
```
```
In net/core/dev.c (ffffffff819fe4b0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
```
```
In net/core/sock_diag.c (ffffffff81a338f5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4a25)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa5462)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81aade5d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff81ab32bc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_prune_queue
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acb6c3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81af651d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/ipv4/proc.c (ffffffff81afe9c0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/proc.c:icmp_put
  - net/ipv4/proc.c:icmp_put
  - net/ipv4/proc.c:icmpmsg_put
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/unix/af_unix.c (ffffffff81b24cd1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81b293dd)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/unix/scm.c (ffffffff81b29a4b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/addrconf.c (ffffffff81b33857)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/proc.c (ffffffff81b7b508)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_dev_seq_show
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:sockstat6_seq_show
```
```
In net/packet/af_packet.c (ffffffff81b8a077)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81ba8584)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/mptcp/protocol.c (ffffffff81bab255)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_clean_una
```
```
In net/mptcp/options.c (ffffffff81bb1475)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
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
In arch/x86/events/core.c (ffffffff81007855)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009ea0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100ac7e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/ibs.c:perf_ibs_event_update
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100b424)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
```
In arch/x86/events/msr.c (ffffffff8100bbb3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100e735)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
```
```
In arch/x86/events/intel/bts.c (ffffffff810100b3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff810108ca)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff81016aca)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
```
```
In arch/x86/events/intel/uncore.c (ffffffff81019f55)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105a3c4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
```
In arch/x86/kernel/pvclock.c (ffffffff810801c1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In arch/x86/mm/tlb.c (ffffffff8108b424)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109a48a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_get_local64
```
```
In kernel/fork.c (ffffffff810a2b46)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:get_mm_exe_file
  - kernel/fork.c:fork_init
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In kernel/exit.c (ffffffff810a9881)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff810bfc06)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/workqueue.c (ffffffff81bdbdad)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/workqueue.c:show_pwq
  - kernel/workqueue.c:show_pwq
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/loadavg.c (ffffffff810e4eba)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_nohz
```
```
In kernel/sched/fair.c (ffffffff810ec288)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
```
```
In kernel/sched/debug.c (ffffffff81105f59)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
```
```
In kernel/locking/mutex.c (ffffffff81c42ce2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/mutex.c:mutex_trylock_recursive
  - kernel/locking/mutex.c:mutex_trylock_recursive
  - kernel/locking/mutex.c:mutex_is_locked
```
```
In kernel/locking/rwsem.c (ffffffff8110b9eb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/power/snapshot.c (ffffffff81bdfe9c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_image_size_init
```
```
In kernel/power/swap.c (ffffffff81115024)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:swap_write_page
  - kernel/power/swap.c:swap_write_page
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8111c3ea)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
  - kernel/printk/printk_ringbuffer.c:prb_read
  - kernel/printk/printk_ringbuffer.c:prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
  - kernel/printk/printk_ringbuffer.c:data_realloc
  - kernel/printk/printk_ringbuffer.c:data_alloc
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_push_tail
  - kernel/printk/printk_ringbuffer.c:desc_push_tail
  - kernel/printk/printk_ringbuffer.c:data_make_reusable
  - kernel/printk/printk_ringbuffer.c:data_make_reusable
```
```
In kernel/dma/pool.c (ffffffff82fde13f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_atomic_pool_init
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8115019f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
```
```
In kernel/futex.c (ffffffff811574cc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/acct.c (ffffffff811657ac)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/acct.c:acct_get
```
```
In kernel/kexec_core.c (ffffffff81167252)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In kernel/cgroup/cgroup.c (ffffffff811752bf)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117826b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8117925e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff811793a7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_current_read
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/cgroup/rdma.c (ffffffff8117a2bc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8118005c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/tsacct.c (ffffffff811a8720)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In kernel/trace/ring_buffer.c (ffffffff811b56da)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_iter_empty
  - kernel/trace/ring_buffer.c:ring_buffer_iter_empty
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:rb_add_timestamp
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_handle_head_page
  - kernel/trace/ring_buffer.c:rb_iter_head_event
  - kernel/trace/ring_buffer.c:rb_iter_head_event
  - kernel/trace/ring_buffer.c:rb_remove_pages
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/trace/tracing_map.c (ffffffff811c5e10)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_cmp_atomic64
  - kernel/trace/tracing_map.c:tracing_map_cmp_atomic64
  - kernel/trace/tracing_map.c:tracing_map_read_var_once
  - kernel/trace/tracing_map.c:tracing_map_read_var
  - kernel/trace/tracing_map.c:tracing_map_read_sum
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e07bb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
```
```
In kernel/bpf/syscall.c (ffffffff811fa629)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
  - kernel/bpf/syscall.c:__bpf_map_inc_not_zero
```
```
In kernel/bpf/task_iter.c (ffffffff81218626)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In kernel/events/core.c (ffffffff8124b1dc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:free_event
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:perf_event_context_sched_out
```
```
In kernel/events/ring_buffer.c (ffffffff8124df15)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_end
  - kernel/events/ring_buffer.c:perf_output_end
  - kernel/events/ring_buffer.c:perf_output_end
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In mm/oom_kill.c (ffffffff812614c9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reap_task_mm
  - mm/oom_kill.c:oom_reap_task_mm
  - mm/oom_kill.c:oom_reap_task_mm
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/page-writeback.c (ffffffff81265f0f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:__wb_calc_thresh
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/swap.c (ffffffff82fe562d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
```
```
In mm/vmscan.c (ffffffff812753d5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/shmem.c (ffffffff81278973)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_one
```
```
In mm/util.c (ffffffff8127dfda)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
```
```
In mm/vmstat.c (ffffffff81280d6b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:node_page_state
  - mm/vmstat.c:sum_zone_numa_state
  - mm/vmstat.c:sum_zone_node_page_state
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/backing-dev.c (ffffffff8128175f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In mm/mm_init.c (ffffffff81282b42)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/compaction.c (ffffffff8128e7ff)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
```
In mm/workingset.c (ffffffff82fe74e0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/memory.c (ffffffff8129b41f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffff812a3b85)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff812b12da)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff812b7a88)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:vmalloc_nr_pages
```
```
In mm/page_alloc.c (ffffffff812b92d6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:__setup_per_zone_wmarks
  - mm/page_alloc.c:__setup_per_zone_wmarks
  - mm/page_alloc.c:__setup_per_zone_wmarks
  - mm/page_alloc.c:__setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:zone_batchsize
  - mm/page_alloc.c:build_zonerefs_node
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo_node
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:steal_suitable_fallback
```
```
In mm/madvise.c (ffffffff812c0800)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/swap_state.c (ffffffff812c4e37)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swapfile.c (ffffffff812cb6ea)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swapfile.c:si_swapinfo
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/swap_slots.c (ffffffff812cc016)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff812cdf44)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff812d31b5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_report_usage
```
```
In mm/sparse.c (ffffffff812dd1a5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/slub.c (ffffffff812eb117)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:get_slabinfo
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:list_locations
  - mm/slub.c:validate_slab_node
  - mm/slub.c:validate_slab_node
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:slab_out_of_memory
```
```
In mm/huge_memory.c (ffffffff82fec09c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In mm/page_counter.c (ffffffff812ffd36)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff813000ac)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:get_obj_cgroup_from_current
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_size
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - mm/memcontrol.c:mem_cgroup_update_tree
```
```
In mm/hugetlb_cgroup.c (ffffffff8130b285)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/zsmalloc.c (ffffffff81310fb7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_zpool_total_size
```
```
In mm/memremap.c (ffffffff81315d7a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/open.c (ffffffff81319c95)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/open.c:filp_close
```
```
In fs/file_table.c (ffffffff82fed1b6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/exec.c (ffffffff81329217)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
```
```
In fs/namei.c (ffffffff8132f5a3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/inode.c (ffffffff81341309)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:__destroy_inode
```
```
In fs/attr.c (ffffffff81343871)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/file.c (ffffffff81345706)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/file.c:__fdget_pos
  - fs/file.c:__fget_files
```
```
In fs/namespace.c (ffffffff81349295)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/namespace.c:sb_prepare_remount_readonly
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs-writeback.c (ffffffff8135b154)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_check_start_all
  - fs/fs-writeback.c:wb_check_start_all
  - fs/fs-writeback.c:wb_check_old_data_flush
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/sync.c (ffffffff8135f9a5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/nsfs.c (ffffffff81362f9f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/notify/fsnotify.c (ffffffff813738f0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
```
```
In fs/eventpoll.c (ffffffff8137b161)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/aio.c (ffffffff81382e4b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff8139684d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_show_fdinfo
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_uring_flush
  - fs/io_uring.c:io_buffer_account_pin
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_grab_identity
```
```
In fs/quota/dquot.c (ffffffff813c207c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/proc/task_mmu.c (ffffffff813c8be8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/base.c (ffffffff813cc945)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/proc/array.c (ffffffff813d4640)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/meminfo.c (ffffffff813d67a6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/ext4/balloc.c (ffffffff813ea925)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/dir.c (ffffffff813ece3f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff813f706d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:__ext4_ext_dirty
```
```
In fs/ext4/file.c (ffffffff813faf49)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/ialloc.c (ffffffff813fe362)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/ext4/inline.c (ffffffff81406a4a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff8140dfba)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_break_layouts
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/namei.c (ffffffff8142a04b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/super.c (ffffffff8143f3e8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/sysfs.c (ffffffff8144dcf3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In fs/ext4/xattr.c (ffffffff8144f2aa)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/fat/dir.c (ffffffff8146f428)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff814764ad)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff81477fec)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff8147a5a1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/dir.c (ffffffff8148f910)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/file.c (ffffffff81492602)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_send_readpages
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/inode.c (ffffffff814984dc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/inode.c:set_global_limit
  - fs/fuse/inode.c:fuse_ilookup
```
```
In fs/fuse/readdir.c (ffffffff8149ba9f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/pstore/inode.c (ffffffff814a1ae7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
```
```
In security/integrity/ima/ima_fs.c (ffffffff81531a9b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
```
```
In security/integrity/ima/ima_main.c (ffffffff81532fbc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In security/integrity/ima/ima_api.c (ffffffff815352e0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-core.c (ffffffff81561440)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-ioc.c (ffffffff815651be)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-ioc.c:put_io_context
```
```
In block/blk-mq.c (ffffffff8156bd4c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff81571c0b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/genhd.c (ffffffff81575dd3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/genhd.c:part_inflight_show
  - block/genhd.c:part_inflight_show
  - block/genhd.c:part_in_flight
  - block/genhd.c:part_in_flight
```
```
In block/blk-cgroup.c (ffffffff81586d2c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_blkg
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-cgroup-rwstat.c (ffffffff815871e1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
```
```
In block/blk-iocost.c (ffffffff8158e561)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_lat_stat
  - block/blk-iocost.c:ioc_lat_stat
  - block/blk-iocost.c:ioc_lat_stat
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:__propagate_weights
  - block/blk-iocost.c:ioc_now
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:trace_event_raw_event_iocost_ioc_vrate_adj
```
```
In lib/percpu-refcount.c (ffffffff815aa729)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_exit
```
```
In lib/genalloc.c (ffffffff815b72c6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_avail
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In lib/show_mem.c (ffffffff81bf4d28)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
  - lib/show_mem.c:show_mem
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8172ccd1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
```
In drivers/tty/tty_ldsem.c (ffffffff8175c4d5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
```
```
In drivers/char/agp/backend.c (ffffffff81794755)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_initialize
```
```
In drivers/iommu/amd/iommu.c (ffffffff817a4cfb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_set_gcr3
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd/iommu.c:amd_iommu_iova_to_phys
  - drivers/iommu/amd/iommu.c:amd_iommu_unmap
  - drivers/iommu/amd/iommu.c:amd_iommu_map
  - drivers/iommu/amd/iommu.c:protection_domain_free
  - drivers/iommu/amd/iommu.c:update_domain
  - drivers/iommu/amd/iommu.c:do_attach
  - drivers/iommu/amd/iommu.c:fetch_pte
  - drivers/iommu/amd/iommu.c:increase_address_space
```
```
In drivers/iommu/iova.c (ffffffff817c101c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:fq_ring_free
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81835e6f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_show_fdinfo
```
```
In drivers/net/loopback.c (ffffffff8188ce5e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/net/loopback.c:dev_lstats_read
  - drivers/net/loopback.c:dev_lstats_read
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81894701)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdio_bus_device_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
```
```
In drivers/net/tun.c (ffffffff81898567)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_get_stats64
```
```
In drivers/usb/core/devio.c (ffffffff818d5a63)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff81965bd9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/md.c:mismatch_cnt_show
```
```
In drivers/md/dm.c (ffffffff8197c466)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_bios_completion
  - drivers/md/dm.c:dm_wait_for_bios_completion
```
```
In drivers/md/dm-stats.c (ffffffff81988fd2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:__check_shared_memory
```
```
In drivers/firmware/efi/cper.c (ffffffff819c0325)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff819e4eea)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/sock.c:proto_seq_printf
  - net/core/sock.c:__sk_mem_reduce_allocated
```
```
In net/core/skbuff.c (ffffffff819ec9fc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/core/net_namespace.c (ffffffff819f93f5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/net_namespace.c:__net_gen_cookie
```
```
In net/core/dev.c (ffffffff819fe0a0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
```
```
In net/core/sock_diag.c (ffffffff81a35c65)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/sock_diag.c:__sock_gen_cookie
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf085)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aafa62)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81ab80ed)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff81abe225)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_prune_queue
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad7663)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81b0339d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/ipv4/proc.c (ffffffff81b0ca30)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/proc.c:icmp_put
  - net/ipv4/proc.c:icmp_put
  - net/ipv4/proc.c:icmpmsg_put
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/unix/af_unix.c (ffffffff81b33861)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81b37d0d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/unix/scm.c (ffffffff81b3837b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/addrconf.c (ffffffff81b42197)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/proc.c (ffffffff81b8a548)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_dev_seq_show
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:sockstat6_seq_show
```
```
In net/packet/af_packet.c (ffffffff81b99b97)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81bb82eb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/mptcp/subflow.c (ffffffff81bc37c9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In arch/x86/events/core.c (ffffffff81008035)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff8100aa30)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100b60e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/ibs.c:perf_ibs_event_update
```
```
In arch/x86/events/msr.c (ffffffff8100c543)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100ec35)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
```
```
In arch/x86/events/intel/bts.c (ffffffff81011103)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff8101186a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff81017daa)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101b2d5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105ad64)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
```
In arch/x86/kernel/pvclock.c (ffffffff81081054)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In arch/x86/mm/tlb.c (ffffffff8108bd56)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_func
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109ac4a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_get_local64
```
```
In kernel/fork.c (ffffffff810a3850)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:get_mm_exe_file
  - kernel/fork.c:fork_init
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In kernel/exit.c (ffffffff810aa8bd)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff810c1636)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/workqueue.c (ffffffff81bcde64)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/workqueue.c:show_pwq
  - kernel/workqueue.c:show_pwq
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/loadavg.c (ffffffff810e6d9a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
```
```
In kernel/sched/fair.c (ffffffff810eec15)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
```
```
In kernel/sched/debug.c (ffffffff81107edb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
```
```
In kernel/locking/mutex.c (ffffffff81c35342)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_trylock
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/mutex.c:mutex_is_locked
```
```
In kernel/locking/rwsem.c (ffffffff8110d80b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/power/snapshot.c (ffffffff81bd1ea3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_image_size_init
```
```
In kernel/power/swap.c (ffffffff81115997)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:swap_write_page
  - kernel/power/swap.c:swap_write_page
```
```
In kernel/printk/printk.c (ffffffff81119247)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8111c660)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
  - kernel/printk/printk_ringbuffer.c:prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
  - kernel/printk/printk_ringbuffer.c:data_realloc
  - kernel/printk/printk_ringbuffer.c:data_alloc
```
```
In kernel/dma/pool.c (ffffffff831e8c73)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_atomic_pool_init
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811515cf)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
```
```
In kernel/futex.c (ffffffff811588e0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/acct.c (ffffffff81166df9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/kexec_core.c (ffffffff81167fe2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In kernel/cgroup/cgroup.c (ffffffff81175e25)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81178dde)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81179dce)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff81179f07)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_current_read
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/cgroup/rdma.c (ffffffff8117ae3c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81180b2c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/cgroup/misc.c (ffffffff81180d22)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_current_show
  - kernel/cgroup/misc.c:misc_cg_res_total_usage
```
```
In kernel/tsacct.c (ffffffff811a92b3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In kernel/trace/ring_buffer.c (ffffffff811b6fca)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_iter_empty
  - kernel/trace/ring_buffer.c:ring_buffer_iter_empty
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_handle_head_page
  - kernel/trace/ring_buffer.c:rb_iter_head_event
  - kernel/trace/ring_buffer.c:rb_iter_head_event
  - kernel/trace/ring_buffer.c:rb_remove_pages
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_event_time_stamp
  - kernel/trace/ring_buffer.c:ring_buffer_event_time_stamp
```
```
In kernel/trace/tracing_map.c (ffffffff811c7020)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_cmp_atomic64
  - kernel/trace/tracing_map.c:tracing_map_cmp_atomic64
  - kernel/trace/tracing_map.c:tracing_map_read_var_once
  - kernel/trace/tracing_map.c:tracing_map_read_var
  - kernel/trace/tracing_map.c:tracing_map_read_sum
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e1903)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
```
```
In kernel/bpf/syscall.c (ffffffff811fb589)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
  - kernel/bpf/syscall.c:__bpf_map_inc_not_zero
```
```
In kernel/bpf/task_iter.c (ffffffff8121bdd9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In kernel/events/core.c (ffffffff8124b76d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:free_event
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
```
```
In kernel/events/ring_buffer.c (ffffffff81252855)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_end
  - kernel/events/ring_buffer.c:perf_output_end
  - kernel/events/ring_buffer.c:perf_output_end
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In mm/oom_kill.c (ffffffff81265d05)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/page-writeback.c (ffffffff8126a9f8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:__wb_calc_thresh
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/swap.c (ffffffff831efd06)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
```
```
In mm/vmscan.c (ffffffff8127a6f5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:reparent_shrinker_deferred
```
```
In mm/shmem.c (ffffffff8127d923)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_one
```
```
In mm/util.c (ffffffff8128314a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
```
```
In mm/vmstat.c (ffffffff81285e83)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:node_page_state
  - mm/vmstat.c:sum_zone_numa_state
  - mm/vmstat.c:sum_zone_node_page_state
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/backing-dev.c (ffffffff8128660f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In mm/mm_init.c (ffffffff81287c73)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/compaction.c (ffffffff81293e96)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
```
In mm/workingset.c (ffffffff831f1c02)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/memory.c (ffffffff812a072b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffff812a9395)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff812b69aa)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff812bd4a6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:vmalloc_nr_pages
```
```
In mm/page_alloc.c (ffffffff812be7a6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:zone_batchsize
  - mm/page_alloc.c:build_zonerefs_node
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo_node
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:steal_suitable_fallback
```
```
In mm/madvise.c (ffffffff812c778f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/swap_state.c (ffffffff812cbad6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:show_swap_cache_info
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swapfile.c (ffffffff812d228b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swapfile.c:si_swapinfo
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/swap_slots.c (ffffffff812d2bc6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff812d45e4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff812d9f05)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_report_usage
```
```
In mm/sparse.c (ffffffff812e4a03)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/slub.c (ffffffff812f2be7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:get_slabinfo
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:slab_out_of_memory
```
```
In mm/huge_memory.c (ffffffff831f68fb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In mm/page_counter.c (ffffffff813069d6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff81306eec)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:obj_cgroup_charge_pages
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_size
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff81311ed5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/zsmalloc.c (ffffffff81317087)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_zpool_total_size
```
```
In mm/memremap.c (ffffffff8131bf6d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/open.c (ffffffff8131faa5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/open.c:filp_close
```
```
In fs/file_table.c (ffffffff831f79e7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/exec.c (ffffffff8132f021)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
```
```
In fs/namei.c (ffffffff81334c63)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/inode.c (ffffffff81347649)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:__destroy_inode
```
```
In fs/attr.c (ffffffff81349bd5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/file.c (ffffffff8134baa6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/file.c:__fdget_pos
  - fs/file.c:__fget_files
```
```
In fs/namespace.c (ffffffff8134fc85)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/namespace.c:sb_prepare_remount_readonly
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs-writeback.c (ffffffff81361d54)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/sync.c (ffffffff813661d5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/nsfs.c (ffffffff81369a3f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/notify/fsnotify.c (ffffffff8137a250)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
```
```
In fs/eventpoll.c (ffffffff81382f19)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/aio.c (ffffffff81389ebe)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff8139ecc5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_show_fdinfo
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_buffer_account_pin
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_req_complete_post
```
```
In fs/quota/dquot.c (ffffffff813c8c3c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/proc/task_mmu.c (ffffffff813cfc27)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/base.c (ffffffff813d3905)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/proc/array.c (ffffffff813db47d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/meminfo.c (ffffffff813dd6a8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/ext4/balloc.c (ffffffff813f0e45)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/dir.c (ffffffff813f336f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff813fd51d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:__ext4_ext_dirty
```
```
In fs/ext4/file.c (ffffffff814013e5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/ialloc.c (ffffffff81404856)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8140cedf)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff8141417a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_break_layouts
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/mballoc.c (ffffffff81423bc2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
```
```
In fs/ext4/namei.c (ffffffff81430d4b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/super.c (ffffffff8144a458)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/sysfs.c (ffffffff814537ac)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In fs/ext4/xattr.c (ffffffff81454b6a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/fat/dir.c (ffffffff814748f8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff8147bf1d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff8147da83)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_update_time
```
```
In fs/fat/namei_vfat.c (ffffffff8147ffe1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/dir.c (ffffffff81495340)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/file.c (ffffffff814976e6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/inode.c (ffffffff8149d70c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/inode.c:set_global_limit
  - fs/fuse/inode.c:fuse_ilookup
```
```
In fs/fuse/readdir.c (ffffffff814a0bbf)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/pstore/inode.c (ffffffff814a7c17)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
```
```
In security/landlock/fs.c (ffffffff81538edf)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff81539f1b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
```
```
In security/integrity/ima/ima_main.c (ffffffff8153b46b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In security/integrity/ima/ima_api.c (ffffffff8153d900)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-core.c (ffffffff81569b90)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-ioc.c (ffffffff8156d82e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-ioc.c:put_io_context
```
```
In block/blk-mq.c (ffffffff81573842)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff81579c11)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/genhd.c (ffffffff8157dc23)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/genhd.c:part_inflight_show
  - block/genhd.c:part_inflight_show
  - block/genhd.c:part_in_flight
  - block/genhd.c:part_in_flight
```
```
In block/blk-cgroup.c (ffffffff8158db7c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-cgroup-rwstat.c (ffffffff8158e031)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
```
```
In block/blk-iocost.c (ffffffff815952c1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:__propagate_weights
  - block/blk-iocost.c:ioc_now
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:trace_event_raw_event_iocost_ioc_vrate_adj
```
```
In lib/percpu-refcount.c (ffffffff815b5349)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_exit
```
```
In lib/genalloc.c (ffffffff815c2136)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_avail
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In lib/show_mem.c (ffffffff81be6c4b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
  - lib/show_mem.c:show_mem
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81710870)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
```
In drivers/tty/tty_ldsem.c (ffffffff81740375)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
```
```
In drivers/char/agp/backend.c (ffffffff81777425)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_initialize
```
```
In drivers/iommu/iova.c (ffffffff817a446c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:fq_ring_free
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8181955f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_show_fdinfo
```
```
In drivers/net/loopback.c (ffffffff8186f7ae)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/net/loopback.c:dev_lstats_read
  - drivers/net/loopback.c:dev_lstats_read
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81877004)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdio_bus_device_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
```
```
In drivers/net/tun.c (ffffffff8187ae67)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_get_stats64
```
```
In drivers/usb/core/devio.c (ffffffff818b8fb3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff81949dd9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/md.c:mismatch_cnt_show
```
```
In drivers/md/dm.c (ffffffff8196017f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In drivers/md/dm-stats.c (ffffffff8196d6b2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:__check_shared_memory
```
```
In drivers/firmware/efi/cper.c (ffffffff819a4a35)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff819cb16d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/sock.c:proto_seq_printf
  - net/core/sock.c:__sk_mem_reduce_allocated
```
```
In net/core/skbuff.c (ffffffff819d2edc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/core/dev.c (ffffffff819e4960)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
```
```
In net/core/sock_diag.c (ffffffff81a1cdb5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/sock_diag.c:__sock_gen_cookie
```
```
In net/ipv4/inetpeer.c (ffffffff83227a0a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_initpeers
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a393)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9ad72)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81aa342a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff81aa9305)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac2795)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81aeebfd)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81af7aaf)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nh_res_table_upkeep
```
```
In net/ipv4/proc.c (ffffffff81afa6a0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/proc.c:icmp_put
  - net/ipv4/proc.c:icmp_put
  - net/ipv4/proc.c:icmpmsg_put
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/unix/af_unix.c (ffffffff81b21271)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81b259ad)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/unix/scm.c (ffffffff81b2601b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/addrconf.c (ffffffff81b30115)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/proc.c (ffffffff81b79398)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_dev_seq_show
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:sockstat6_seq_show
```
```
In net/ipv6/seg6_local.c (ffffffff81b7d345)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/packet/af_packet.c (ffffffff81b88085)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81ba74a9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/mptcp/subflow.c (ffffffff81bb3e66)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In arch/x86/events/core.c (ffffffff81008bf5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100bafc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/ibs.c:perf_ibs_event_update
```
```
In arch/x86/events/msr.c (ffffffff8100ca73)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100f775)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
```
```
In arch/x86/events/intel/bts.c (ffffffff81011e7e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff8101272e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff8101ab34)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101dc23)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810642a4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81073612)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
```
```
In arch/x86/kernel/pvclock.c (ffffffff8108ffea)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In arch/x86/mm/tlb.c (ffffffff8109b4aa)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_func
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810aaeda)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_get_local64
```
```
In kernel/fork.c (ffffffff810b4e9c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:get_mm_exe_file
  - kernel/fork.c:fork_init
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In kernel/exit.c (ffffffff810bc3e4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff810d4126)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/workqueue.c (ffffffff81ca4f25)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/workqueue.c:show_pwq
  - kernel/workqueue.c:show_pwq
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:pwq_activate_inactive_work
```
```
In kernel/ucount.c (ffffffff810ea511)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/ucount.c:is_ucounts_overlimit
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/loadavg.c (ffffffff810fe36a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
```
```
In kernel/sched/fair.c (ffffffff81107242)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_cfs_group
```
```
In kernel/sched/debug.c (ffffffff81126016)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
```
```
In kernel/locking/mutex.c (ffffffff81d53b42)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_trylock
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/mutex.c:mutex_is_locked
```
```
In kernel/locking/rwsem.c (ffffffff8112d06b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/power/snapshot.c (ffffffff81caab5d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_image_size_init
```
```
In kernel/power/swap.c (ffffffff81135bc8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:swap_write_page
  - kernel/power/swap.c:swap_write_page
```
```
In kernel/printk/printk.c (ffffffff81139615)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8113cd2e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
  - kernel/printk/printk_ringbuffer.c:prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
  - kernel/printk/printk_ringbuffer.c:data_realloc
  - kernel/printk/printk_ringbuffer.c:data_alloc
  - kernel/printk/printk_ringbuffer.c:desc_read
  - kernel/printk/printk_ringbuffer.c:desc_read
```
```
In kernel/dma/pool.c (ffffffff832cd189)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_atomic_pool_init
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811759cf)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
```
```
In kernel/futex.c (ffffffff8117d7e7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/acct.c (ffffffff8118c5b9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/kexec_core.c (ffffffff8118d9da)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In kernel/cgroup/cgroup.c (ffffffff8119d412)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811a070e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811a16ee)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff811a1827)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_current_read
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/cgroup/rdma.c (ffffffff811a2921)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811a891c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/cgroup/misc.c (ffffffff811a8b42)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_current_show
  - kernel/cgroup/misc.c:misc_cg_res_total_usage
```
```
In kernel/tsacct.c (ffffffff811d2e03)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In kernel/trace/ring_buffer.c (ffffffff811e11b3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_iter_empty
  - kernel/trace/ring_buffer.c:ring_buffer_iter_empty
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_handle_head_page
  - kernel/trace/ring_buffer.c:rb_iter_head_event
  - kernel/trace/ring_buffer.c:rb_iter_head_event
  - kernel/trace/ring_buffer.c:rb_remove_pages
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_event_time_stamp
  - kernel/trace/ring_buffer.c:ring_buffer_event_time_stamp
```
```
In kernel/trace/trace.c (ffffffff811e411c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/trace.c:latency_fsnotify_workfn
```
```
In kernel/trace/tracing_map.c (ffffffff811f26c0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_cmp_atomic64
  - kernel/trace/tracing_map.c:tracing_map_cmp_atomic64
  - kernel/trace/tracing_map.c:tracing_map_read_var_once
  - kernel/trace/tracing_map.c:tracing_map_read_var
  - kernel/trace/tracing_map.c:tracing_map_read_sum
```
```
In kernel/trace/trace_events_hist.c (ffffffff81211a8d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
```
```
In kernel/bpf/syscall.c (ffffffff812342bc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/syscall.c:__bpf_map_inc_not_zero
```
```
In kernel/bpf/helpers.c (ffffffff8124ff4b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_timer_set_callback
  - kernel/bpf/helpers.c:bpf_timer_init
```
```
In kernel/bpf/task_iter.c (ffffffff81252cd9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In kernel/events/core.c (ffffffff81284c9d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:free_event
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
```
```
In kernel/events/ring_buffer.c (ffffffff8128e115)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_end
  - kernel/events/ring_buffer.c:perf_output_end
  - kernel/events/ring_buffer.c:perf_output_end
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In mm/oom_kill.c (ffffffff812a252f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/page-writeback.c (ffffffff812a76a8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:__wb_calc_thresh
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/swap.c (ffffffff832d547c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/vmscan.c (ffffffff812b8755)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:reparent_shrinker_deferred
```
```
In mm/shmem.c (ffffffff812bbc65)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_one
```
```
In mm/util.c (ffffffff812c130a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
```
```
In mm/vmstat.c (ffffffff812c50a0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:node_page_state
  - mm/vmstat.c:sum_zone_numa_event_state
  - mm/vmstat.c:sum_zone_node_page_state
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/backing-dev.c (ffffffff812c6159)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/mm_init.c (ffffffff812c7413)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/compaction.c (ffffffff812d4407)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
```
In mm/workingset.c (ffffffff832d77a3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/memory.c (ffffffff812e16bb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffff812eaa05)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff812f8dca)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff812ffc66)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:vmalloc_nr_pages
```
```
In mm/page_alloc.c (ffffffff813010b6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:build_zonerefs_node
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo_node
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:steal_suitable_fallback
```
```
In mm/madvise.c (ffffffff8130c54f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/swap_state.c (ffffffff81310bc5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:show_swap_cache_info
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swapfile.c (ffffffff81317b1b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swapfile.c:si_swapinfo
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/swap_slots.c (ffffffff813185a6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff8131a906)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff81320c45)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_report_usage
```
```
In mm/sparse.c (ffffffff8132bc83)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/slub.c (ffffffff8133b917)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:get_slabinfo
  - mm/slub.c:slab_debug_trace_open
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:validate_slab_cache
  - mm/slub.c:validate_slab_cache
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:slab_out_of_memory
```
```
In mm/kfence/core.c (ffffffff8133bca5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/kfence/core.c:stats_show
```
```
In mm/huge_memory.c (ffffffff832dd411)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In mm/page_counter.c (ffffffff81350826)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff81350bac)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:obj_cgroup_charge_pages
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_size
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff8135ccd4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/zsmalloc.c (ffffffff813634ef)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_zpool_total_size
```
```
In mm/memremap.c (ffffffff8136924d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/open.c (ffffffff8136d045)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/open.c:filp_close
  - fs/open.c:do_sys_openat2
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff813740ac)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
```
```
In fs/file_table.c (ffffffff81374a4f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:files_maxfiles_init
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/exec.c (ffffffff8137c811)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
```
```
In fs/namei.c (ffffffff813837b3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:lookup_one
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/readdir.c (ffffffff8138bab5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/dcache.c (ffffffff81390dca)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff81395169)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:__destroy_inode
```
```
In fs/attr.c (ffffffff81397992)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
```
```
In fs/file.c (ffffffff813998e6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/file.c:__fdget_pos
  - fs/file.c:__fget_files
```
```
In fs/namespace.c (ffffffff8139dfc5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/namespace.c:sb_prepare_remount_readonly
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/xattr.c (ffffffff813a4b0d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/libfs.c (ffffffff813a7717)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/fs-writeback.c (ffffffff813b03b4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/sync.c (ffffffff813b5003)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/nsfs.c (ffffffff813b872f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/remap_range.c (ffffffff813bbbbe)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
```
```
In fs/notify/fsnotify.c (ffffffff813c6f1c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/aio.c (ffffffff813d719e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff813eef69)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_show_fdinfo
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_buffer_account_pin
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_openat2
  - fs/io_uring.c:io_req_complete_post
```
```
In fs/fhandle.c (ffffffff81410f88)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/quota/dquot.c (ffffffff814193bc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/proc/task_mmu.c (ffffffff81421004)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/base.c (ffffffff81424eb5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/proc/array.c (ffffffff8142cb0b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/meminfo.c (ffffffff8142ee3f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/kernfs/file.c (ffffffff8143b277)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
```
```
In fs/configfs/dir.c (ffffffff8143fa85)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff81442c9f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/ext4/balloc.c (ffffffff81442d9b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/dir.c (ffffffff814453b0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8144f81d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:__ext4_ext_dirty
```
```
In fs/ext4/file.c (ffffffff81453965)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/ialloc.c (ffffffff81457006)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8145fd1f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff814674da)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/mballoc.c (ffffffff8147758e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
```
```
In fs/ext4/namei.c (ffffffff814831a6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/super.c (ffffffff8149def1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/sysfs.c (ffffffff814a76fc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In fs/ext4/xattr.c (ffffffff814a8c90)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/ext4/orphan.c (ffffffff814b16bd)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/fat/dir.c (ffffffff814cb638)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/file.c (ffffffff814d1ae2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/fat/inode.c (ffffffff814d355a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff814d5303)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_update_time
```
```
In fs/fat/namei_vfat.c (ffffffff814d7881)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/dir.c (ffffffff814ecdd0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/file.c (ffffffff814ef246)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/inode.c (ffffffff814f515c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/inode.c:set_global_limit
  - fs/fuse/inode.c:fuse_ilookup
```
```
In fs/fuse/readdir.c (ffffffff814f8a9e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/debugfs/inode.c (ffffffff814fd0b3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff814ff2de)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In fs/pstore/inode.c (ffffffff814fff07)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
```
```
In security/security.c (ffffffff815256b3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In security/landlock/fs.c (ffffffff815976ff)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff8159888b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
```
```
In security/integrity/ima/ima_main.c (ffffffff81599eeb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In security/integrity/ima/ima_api.c (ffffffff8159c790)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-core.c (ffffffff815cc634)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-core.c:blk_try_enter_queue
```
```
In block/blk-ioc.c (ffffffff815d21ce)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
```
```
In block/blk-mq.c (ffffffff815d7e45)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff815def59)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/genhd.c (ffffffff815e34bc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/genhd.c:part_inflight_show
  - block/genhd.c:part_inflight_show
  - block/genhd.c:part_in_flight
  - block/genhd.c:part_in_flight
```
```
In block/blk-cgroup.c (ffffffff815f35eb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_print_one_stat
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-cgroup-rwstat.c (ffffffff815f3bad)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
```
```
In block/blk-iocost.c (ffffffff815fc1c2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:__propagate_weights
  - block/blk-iocost.c:ioc_now
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:trace_event_raw_event_iocost_ioc_vrate_adj
```
```
In block/mq-deadline.c (ffffffff8160058b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_owned_by_driver
  - block/mq-deadline.c:dd_owned_by_driver
  - block/mq-deadline.c:dd_owned_by_driver
  - block/mq-deadline.c:dd_queued
  - block/mq-deadline.c:dd_queued
```
```
In lib/percpu-refcount.c (ffffffff8161b6e9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_exit
```
```
In lib/genalloc.c (ffffffff81629fb6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_avail
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In lib/show_mem.c (ffffffff81cdfab3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
  - lib/show_mem.c:show_mem
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8178d260)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
```
In drivers/tty/tty_ldsem.c (ffffffff817c0b55)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
```
```
In drivers/char/agp/backend.c (ffffffff817fd1c5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_initialize
```
```
In drivers/iommu/iova.c (ffffffff8182dbc0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:fq_ring_free
```
```
In drivers/dma-buf/dma-buf.c (ffffffff818a3ccf)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_show_fdinfo
```
```
In drivers/net/loopback.c (ffffffff818ffcff)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/net/loopback.c:dev_lstats_read
  - drivers/net/loopback.c:dev_lstats_read
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81907cf5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdio_bus_device_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
```
```
In drivers/net/tun.c (ffffffff8190c367)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_get_stats64
```
```
In drivers/usb/core/devio.c (ffffffff8194ea73)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff819eee59)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/md.c:mismatch_cnt_show
```
```
In drivers/md/dm.c (ffffffff81a0815d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In drivers/md/dm-stats.c (ffffffff81a15c82)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:__check_shared_memory
```
```
In drivers/firmware/efi/cper.c (ffffffff81a51d05)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff81a7a790)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/sock.c:proto_seq_printf
  - net/core/sock.c:__sk_mem_reduce_allocated
```
```
In net/core/skbuff.c (ffffffff81a82bbc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/core/dev.c (ffffffff81a95720)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
```
```
In net/core/sock_diag.c (ffffffff81ad0635)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/sock_diag.c:__sock_gen_cookie
```
```
In net/core/page_pool.c (ffffffff81ad86ca)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
```
```
In net/ipv4/inetpeer.c (ffffffff83311dd0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_initpeers
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81b55803)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b561e2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81b5f5f5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff81b651f1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b805f8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81baefcd)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81bb7844)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nh_res_table_upkeep
```
```
In net/ipv4/proc.c (ffffffff81bbb3f2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/proc.c:icmp_put
  - net/ipv4/proc.c:icmp_put
  - net/ipv4/proc.c:icmpmsg_put
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/unix/af_unix.c (ffffffff81be6336)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81beb0ec)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/unix/scm.c (ffffffff81bebc7b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/addrconf.c (ffffffff81bf6500)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/proc.c (ffffffff81c43ff8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_dev_seq_show
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:sockstat6_seq_show
```
```
In net/ipv6/seg6_local.c (ffffffff81c48502)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/packet/af_packet.c (ffffffff81c507b4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81c750c3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/mptcp/subflow.c (ffffffff81c825a8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In arch/x86/events/core.c (ffffffff81008265)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100c71b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/ibs.c:perf_ibs_event_update
```
```
In arch/x86/events/msr.c (ffffffff8100d873)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff81010cc5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
```
```
In arch/x86/events/intel/bts.c (ffffffff810136b3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff81014328)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff8101d384)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
```
```
In arch/x86/events/intel/uncore.c (ffffffff810206ab)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81081a58)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
```
```
In arch/x86/kernel/pvclock.c (ffffffff810a0f3a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In arch/x86/mm/tlb.c (ffffffff810ae9ba)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_func
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810c092a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_get_local64
```
```
In kernel/fork.c (ffffffff810c9c39)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:get_mm_exe_file
  - kernel/fork.c:fork_init
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In kernel/exit.c (ffffffff810d2ed3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff810ece06)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/workqueue.c (ffffffff81e547f2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/workqueue.c:show_pwq
  - kernel/workqueue.c:show_pwq
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:pwq_activate_inactive_work
```
```
In kernel/ucount.c (ffffffff81105215)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/ucount.c:is_ucounts_overlimit
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/fair.c (ffffffff81124455)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_cfs_group
```
```
In kernel/sched/build_utility.c (ffffffff81148902)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
```
```
In kernel/locking/mutex.c (ffffffff81f241e0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_trylock
  - kernel/locking/mutex.c:ww_mutex_trylock
  - kernel/locking/mutex.c:ww_mutex_trylock
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/mutex.c:mutex_is_locked
```
```
In kernel/locking/rwsem.c (ffffffff8114e37a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/power/snapshot.c (ffffffff81e5af84)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_image_size_init
```
```
In kernel/power/swap.c (ffffffff81157fbd)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:swap_write_page
  - kernel/power/swap.c:swap_write_page
```
```
In kernel/printk/printk.c (ffffffff8115c0cc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff81160c91)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_next_seq
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
  - kernel/printk/printk_ringbuffer.c:prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
  - kernel/printk/printk_ringbuffer.c:data_realloc
  - kernel/printk/printk_ringbuffer.c:data_alloc
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:data_push_tail
  - kernel/printk/printk_ringbuffer.c:data_push_tail
  - kernel/printk/printk_ringbuffer.c:desc_read
  - kernel/printk/printk_ringbuffer.c:desc_read
```
```
In kernel/dma/pool.c (ffffffff83480cc8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_atomic_pool_init
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811aa983)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
```
```
In kernel/futex/core.c (ffffffff811b2a49)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/acct.c (ffffffff811bba3f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/kexec_core.c (ffffffff811bceca)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In kernel/cgroup/cgroup.c (ffffffff811cd797)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811d0e4c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811d2045)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff811d2186)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_current_read
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/cgroup/rdma.c (ffffffff811d3400)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811d9b49)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/cgroup/misc.c (ffffffff811d9d42)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_events_show
  - kernel/cgroup/misc.c:misc_cg_current_show
  - kernel/cgroup/misc.c:misc_cg_res_total_usage
```
```
In kernel/tsacct.c (ffffffff812077c3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In kernel/trace/ring_buffer.c (ffffffff81217ecd)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_iter_empty
  - kernel/trace/ring_buffer.c:ring_buffer_iter_empty
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_handle_head_page
  - kernel/trace/ring_buffer.c:rb_iter_head_event
  - kernel/trace/ring_buffer.c:rb_iter_head_event
  - kernel/trace/ring_buffer.c:rb_remove_pages
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_event_time_stamp
  - kernel/trace/ring_buffer.c:ring_buffer_event_time_stamp
```
```
In kernel/trace/trace.c (ffffffff8121b38c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/trace.c:latency_fsnotify_workfn
```
```
In kernel/trace/tracing_map.c (ffffffff8122bb80)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_cmp_atomic64
  - kernel/trace/tracing_map.c:tracing_map_cmp_atomic64
  - kernel/trace/tracing_map.c:tracing_map_read_var_once
  - kernel/trace/tracing_map.c:tracing_map_read_var
  - kernel/trace/tracing_map.c:tracing_map_read_sum
```
```
In kernel/trace/trace_events_hist.c (ffffffff8124e036)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
```
```
In kernel/bpf/syscall.c (ffffffff8126f0b5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_inc_not_zero
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:__bpf_map_inc_not_zero
```
```
In kernel/bpf/helpers.c (ffffffff8129786b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_timer_set_callback
  - kernel/bpf/helpers.c:bpf_timer_init
```
```
In kernel/bpf/task_iter.c (ffffffff8129ae6e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In kernel/events/core.c (ffffffff812d91ad)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:free_event
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:perf_get_aux_event
```
```
In kernel/events/ring_buffer.c (ffffffff812e2d6c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - kernel/events/ring_buffer.c:perf_output_put_handle
```
```
In mm/oom_kill.c (ffffffff812fa06c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:oom_badness
  - mm/oom_kill.c:oom_badness
  - mm/oom_kill.c:oom_badness
  - mm/oom_kill.c:oom_badness
  - mm/oom_kill.c:oom_badness
```
```
In mm/page-writeback.c (ffffffff812ffcc8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:__wb_calc_thresh
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/swap.c (ffffffff83489ca7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/vmscan.c (ffffffff81314185)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:allow_direct_reclaim
  - mm/vmscan.c:allow_direct_reclaim
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:reparent_shrinker_deferred
```
```
In mm/shmem.c (ffffffff81317365)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_one
```
```
In mm/util.c (ffffffff8131e2ea)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
```
```
In mm/vmstat.c (ffffffff81322620)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:node_page_state
  - mm/vmstat.c:sum_zone_numa_event_state
  - mm/vmstat.c:sum_zone_node_page_state
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/backing-dev.c (ffffffff813235d6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/mm_init.c (ffffffff81324763)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/compaction.c (ffffffff81333370)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
```
In mm/workingset.c (ffffffff8348c342)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/memory.c (ffffffff81342221)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffff8134d805)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff8135f62a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81366e83)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:drain_vmap_area_work
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:vmalloc_nr_pages
```
```
In mm/page_alloc.c (ffffffff813686a6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo_node
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:steal_suitable_fallback
```
```
In mm/madvise.c (ffffffff81375ae3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/swap_state.c (ffffffff8137b989)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:show_swap_cache_info
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swapfile.c (ffffffff8138318b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swapfile.c:si_swapinfo
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/swap_slots.c (ffffffff81383c66)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/zswap.c (ffffffff81385f6b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff8138d925)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_report_usage
```
```
In mm/slub.c (ffffffff813ae047)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:get_slabinfo
  - mm/slub.c:slab_debug_trace_open
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:validate_slab_cache
  - mm/slub.c:validate_slab_cache
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:slab_out_of_memory
```
```
In mm/kfence/core.c (ffffffff813afa31)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/kfence/core.c:__kfence_alloc
  - mm/kfence/core.c:stats_show
```
```
In mm/migrate.c (ffffffff813b2d86)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
```
```
In mm/huge_memory.c (ffffffff83492c3f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In mm/page_counter.c (ffffffff813c8b86)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff813d5ccc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:__get_obj_cgroup_from_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_size
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff813d69b4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff813dd745)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memory-failure.c:clear_hwpoisoned_pages
```
```
In mm/zsmalloc.c (ffffffff813dfc15)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_zpool_total_size
```
```
In mm/memremap.c (ffffffff813e70a8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/open.c (ffffffff813eb3a5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/open.c:filp_close
  - fs/open.c:do_sys_openat2
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff813f2ec9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
```
```
In fs/file_table.c (ffffffff813f384a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:files_maxfiles_init
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/exec.c (ffffffff813fa8b2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
```
```
In fs/namei.c (ffffffff81404725)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:lookup_one
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/readdir.c (ffffffff8140d012)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/dcache.c (ffffffff81412066)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff81417fbf)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:__destroy_inode
```
```
In fs/attr.c (ffffffff81419a12)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
```
```
In fs/file.c (ffffffff8141c2ba)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/file.c:__fdget_pos
  - fs/file.c:__fget_light
  - fs/file.c:fget_task
  - fs/file.c:fget_raw
  - fs/file.c:fget
```
```
In fs/namespace.c (ffffffff81421105)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/namespace.c:sb_prepare_remount_readonly
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/xattr.c (ffffffff81428668)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/libfs.c (ffffffff8142c306)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/fs-writeback.c (ffffffff81434ff4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/sync.c (ffffffff81439ea5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/nsfs.c (ffffffff8143e004)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/remap_range.c (ffffffff8144245e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
```
```
In fs/notify/fsnotify.c (ffffffff8144e272)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/aio.c (ffffffff81460d36)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/fhandle.c (ffffffff81486967)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/quota/dquot.c (ffffffff8148fe5b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/proc/task_mmu.c (ffffffff81498e9a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/base.c (ffffffff8149dc25)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/proc/array.c (ffffffff814a63df)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/meminfo.c (ffffffff814a8a50)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/kernfs/file.c (ffffffff814b5ca1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
```
```
In fs/configfs/dir.c (ffffffff814bbfe7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff814bea5c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/ext4/balloc.c (ffffffff814beb9b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/dir.c (ffffffff814c1472)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff814cc6e4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:__ext4_ext_dirty
```
```
In fs/ext4/file.c (ffffffff814d14cb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/ialloc.c (ffffffff814d4afc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/ext4/inline.c (ffffffff814de464)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff814e70e9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/mballoc.c (ffffffff814f98dd)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
```
```
In fs/ext4/namei.c (ffffffff81507c90)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/super.c (ffffffff815224f1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/sysfs.c (ffffffff8152f00b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In fs/ext4/xattr.c (ffffffff8153023a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/ext4/orphan.c (ffffffff8153a1c3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/fat/dir.c (ffffffff81557bd1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/file.c (ffffffff8155e765)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/fat/inode.c (ffffffff8156096e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff8156230e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_update_time
```
```
In fs/fat/namei_vfat.c (ffffffff81564eed)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_revalidate
```
```
In fs/fuse/dir.c (ffffffff815798ac)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/file.c (ffffffff8157efce)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/inode.c (ffffffff815850a6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/inode.c:set_global_limit
  - fs/fuse/inode.c:fuse_ilookup
```
```
In fs/fuse/readdir.c (ffffffff8158908f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/debugfs/inode.c (ffffffff8158d266)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff815905a9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In fs/pstore/inode.c (ffffffff815910a0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
```
```
In security/security.c (ffffffff815b9844)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In security/landlock/fs.c (ffffffff81639528)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff8163d241)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
```
```
In security/integrity/ima/ima_main.c (ffffffff8163eb0c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In security/integrity/ima/ima_api.c (ffffffff8164180c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-core.c (ffffffff8167a003)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-ioc.c (ffffffff8167dd78)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:ioc_find_get_icq
```
```
In block/blk-mq.c (ffffffff81684584)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_get_new_requests
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff8168d6c9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/genhd.c (ffffffff81692748)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/genhd.c:part_inflight_show
  - block/genhd.c:part_inflight_show
  - block/genhd.c:part_in_flight
  - block/genhd.c:part_in_flight
```
```
In block/blk-cgroup.c (ffffffff816a4bd5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-cgroup-rwstat.c (ffffffff816a530f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
```
```
In block/blk-iocost.c (ffffffff816b0582)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:__propagate_weights
  - block/blk-iocost.c:ioc_now
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:trace_event_raw_event_iocost_ioc_vrate_adj
```
```
In io_uring/io_uring.c (ffffffff816d6d66)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_buffer_account_pin
  - io_uring/io_uring.c:io_openat2
  - io_uring/io_uring.c:io_fallocate
  - io_uring/io_uring.c:__io_complete_rw_common
  - io_uring/io_uring.c:__io_complete_rw_common
```
```
In lib/percpu-refcount.c (ffffffff816e8f02)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_exit
```
```
In lib/genalloc.c (ffffffff816fb2fc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_avail
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In lib/show_mem.c (ffffffff81ea6272)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
  - lib/show_mem.c:show_mem
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c5374)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
```
In drivers/tty/tty_ldsem.c (ffffffff818fd415)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
```
```
In drivers/char/agp/backend.c (ffffffff8193c125)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_initialize
```
```
In drivers/iommu/dma-iommu.c (ffffffff8196ae7c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:fq_ring_free
```
```
In drivers/dma-buf/dma-buf.c (ffffffff819ec382)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_show_fdinfo
```
```
In drivers/net/loopback.c (ffffffff81a51616)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/net/loopback.c:dev_lstats_read
  - drivers/net/loopback.c:dev_lstats_read
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81a5adf5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdio_bus_device_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
```
```
In drivers/net/tun.c (ffffffff81a5fef7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_get_stats64
```
```
In drivers/md/md.c (ffffffff81b55dc9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/md.c:mismatch_cnt_show
```
```
In drivers/md/dm-stats.c (ffffffff81b7e682)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:__check_shared_memory
```
```
In drivers/firmware/efi/cper.c (ffffffff81bc0cf5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff81bee312)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/sock.c:proto_seq_printf
  - net/core/sock.c:__sk_mem_reduce_allocated
```
```
In net/core/skbuff.c (ffffffff81bf78d3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_account_pinned_pages
```
```
In net/core/gen_stats.c (ffffffff81c029e5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff81c0366c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/sock_diag.c (ffffffff81c4dec5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/sock_diag.c:__sock_gen_cookie
```
```
In net/core/xdp.c (ffffffff81c51a98)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/net-sysfs.c (ffffffff81c553e9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_timeout_show
```
```
In net/core/page_pool.c (ffffffff81c5a61b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_return_skb_page
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
```
```
In net/ipv4/inetpeer.c (ffffffff834cbcd2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_initpeers
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce34fd)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce42f8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81cee065)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff81cf3b32)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d1097f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_net_metrics_init
```
```
In net/ipv4/inet_fragment.c (ffffffff81d42059)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/nexthop.c (ffffffff81d4b675)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nh_res_table_upkeep
```
```
In net/ipv4/proc.c (ffffffff81d4f4c2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/proc.c:icmp_put
  - net/ipv4/proc.c:icmp_put
  - net/ipv4/proc.c:icmpmsg_put
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/unix/af_unix.c (ffffffff81d7ed85)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81d833f0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/unix/scm.c (ffffffff81d8416b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/addrconf.c (ffffffff81d8f7e8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/proc.c (ffffffff81de2813)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_seq_show_item
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:sockstat6_seq_show
```
```
In net/ipv6/seg6_local.c (ffffffff81de7a31)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/packet/af_packet.c (ffffffff81df136d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81e19267)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/mptcp/protocol.c (ffffffff81e1e1e3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
```
In net/mptcp/subflow.c (ffffffff81e282d7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
```
```
In net/mptcp/options.c (ffffffff81e2b0a5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
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
In arch/x86/events/core.c (ffffffff81007f24)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100f74d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/ibs.c:perf_ibs_event_update
```
```
In arch/x86/events/msr.c (ffffffff81010ab3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff81014675)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
```
```
In arch/x86/events/intel/bts.c (ffffffff81017753)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff810184e8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff81021794)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
```
```
In arch/x86/events/intel/uncore.c (ffffffff81024feb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81094478)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_direct
```
```
In arch/x86/kernel/pvclock.c (ffffffff810b8daa)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In arch/x86/mm/tlb.c (ffffffff810c8d82)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_func
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810dc8aa)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_get_local64
```
```
In kernel/fork.c (ffffffff810e695e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
  - kernel/fork.c:fork_init
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In kernel/workqueue.c (ffffffff8111207d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/workqueue.c:show_pwq
  - kernel/workqueue.c:show_pwq
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__cancel_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:pwq_activate_inactive_work
```
```
In kernel/ucount.c (ffffffff8112ac75)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/ucount.c:is_rlimit_overlimit
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/fair.c (ffffffff8114c425)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_cfs_group
```
```
In kernel/sched/build_utility.c (ffffffff81177122)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
```
```
In kernel/locking/mutex.c (ffffffff820cf6d0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_trylock
  - kernel/locking/mutex.c:ww_mutex_trylock
  - kernel/locking/mutex.c:ww_mutex_trylock
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/mutex.c:mutex_is_locked
```
```
In kernel/locking/rwsem.c (ffffffff8117d30a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/power/snapshot.c (ffffffff811874a4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_image_size_init
```
```
In kernel/power/swap.c (ffffffff8118905d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:swap_write_page
  - kernel/power/swap.c:swap_write_page
```
```
In kernel/printk/printk.c (ffffffff8118eb4c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff81194221)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_next_seq
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
  - kernel/printk/printk_ringbuffer.c:prb_read
  - kernel/printk/printk_ringbuffer.c:prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
  - kernel/printk/printk_ringbuffer.c:data_realloc
  - kernel/printk/printk_ringbuffer.c:data_alloc
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:data_push_tail
  - kernel/printk/printk_ringbuffer.c:data_push_tail
  - kernel/printk/printk_ringbuffer.c:desc_read
  - kernel/printk/printk_ringbuffer.c:desc_read
```
```
In kernel/rcu/srcutree.c (ffffffff811ad812)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:srcu_readers_active
  - kernel/rcu/srcutree.c:srcu_readers_active
  - kernel/rcu/srcutree.c:srcu_readers_active
  - kernel/rcu/srcutree.c:srcu_readers_active
```
```
In kernel/dma/pool.c (ffffffff83ead9c8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_atomic_pool_init
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811eaa73)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
```
```
In kernel/futex/core.c (ffffffff811f38e9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/acct.c (ffffffff811fd8cf)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/kexec_core.c (ffffffff811fee8a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In kernel/cgroup/cgroup.c (ffffffff81210e27)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812149ac)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81215d75)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff81215f26)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_current_read
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/cgroup/rdma.c (ffffffff81217380)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8121f019)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/cgroup/misc.c (ffffffff8121f262)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_events_show
  - kernel/cgroup/misc.c:misc_cg_current_show
  - kernel/cgroup/misc.c:misc_cg_res_total_usage
```
```
In kernel/trace/ring_buffer.c (ffffffff81261405)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_iter_empty
  - kernel/trace/ring_buffer.c:ring_buffer_iter_empty
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_handle_head_page
  - kernel/trace/ring_buffer.c:rb_iter_head_event
  - kernel/trace/ring_buffer.c:rb_iter_head_event
  - kernel/trace/ring_buffer.c:rb_remove_pages
  - kernel/trace/ring_buffer.c:ring_buffer_nr_dirty_pages
  - kernel/trace/ring_buffer.c:ring_buffer_nr_dirty_pages
  - kernel/trace/ring_buffer.c:ring_buffer_nr_dirty_pages
  - kernel/trace/ring_buffer.c:ring_buffer_event_time_stamp
  - kernel/trace/ring_buffer.c:ring_buffer_event_time_stamp
```
```
In kernel/trace/trace.c (ffffffff81264ebc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/trace.c:latency_fsnotify_workfn
```
```
In kernel/trace/tracing_map.c (ffffffff812775a0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_cmp_atomic64
  - kernel/trace/tracing_map.c:tracing_map_cmp_atomic64
  - kernel/trace/tracing_map.c:tracing_map_read_var_once
  - kernel/trace/tracing_map.c:tracing_map_read_var
  - kernel/trace/tracing_map.c:tracing_map_read_sum
```
```
In kernel/trace/trace_events_hist.c (ffffffff8129d146)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
```
```
In kernel/bpf/syscall.c (ffffffff812cd87d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_link_inc_not_zero
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/syscall.c:__bpf_map_inc_not_zero
```
```
In kernel/bpf/helpers.c (ffffffff812f43b9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_kptr_get
  - kernel/bpf/helpers.c:bpf_timer_set_callback
  - kernel/bpf/helpers.c:bpf_timer_init
```
```
In kernel/bpf/task_iter.c (ffffffff812f7726)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In kernel/bpf/memalloc.c (ffffffff8131bee4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In kernel/events/core.c (ffffffff8134165d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:free_event
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:perf_get_aux_event
```
```
In kernel/events/ring_buffer.c (ffffffff8134b3bc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - kernel/events/ring_buffer.c:perf_output_put_handle
```
```
In mm/oom_kill.c (ffffffff81364793)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:oom_badness
```
```
In mm/page-writeback.c (ffffffff8136a5c8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:__wb_calc_thresh
  - mm/page-writeback.c:bdi_set_max_bytes
  - mm/page-writeback.c:bdi_set_max_bytes
  - mm/page-writeback.c:bdi_set_max_bytes
  - mm/page-writeback.c:bdi_set_min_bytes
  - mm/page-writeback.c:bdi_set_min_bytes
  - mm/page-writeback.c:bdi_set_min_bytes
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/swap.c (ffffffff83eba4e5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/vmscan.c (ffffffff81388245)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:allow_direct_reclaim
  - mm/vmscan.c:allow_direct_reclaim
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:lru_gen_seq_show
  - mm/vmscan.c:lru_gen_seq_show
  - mm/vmscan.c:lru_gen_shrink_lruvec
  - mm/vmscan.c:lru_gen_shrink_lruvec
  - mm/vmscan.c:get_nr_to_scan
  - mm/vmscan.c:get_nr_to_scan
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:lru_gen_age_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:reparent_shrinker_deferred
```
```
In mm/shmem.c (ffffffff8138bd45)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_one
```
```
In mm/util.c (ffffffff81391d5a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
```
```
In mm/vmstat.c (ffffffff81396855)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:node_page_state
  - mm/vmstat.c:sum_zone_numa_event_state
  - mm/vmstat.c:sum_zone_node_page_state
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/backing-dev.c (ffffffff81397e26)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/mm_init.c (ffffffff83ebacb7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mm_init.c:mm_compute_batch_notifier
```
```
In mm/compaction.c (ffffffff813aa06f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
```
In mm/workingset.c (ffffffff83ebd685)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/mmap.c (ffffffff813c69f5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
```
```
In mm/rmap.c (ffffffff813da48a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
```
```
In mm/vmalloc.c (ffffffff813e2d23)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:drain_vmap_area_work
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:vmalloc_nr_pages
```
```
In mm/page_alloc.c (ffffffff813e4956)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:zone_pcp_init
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:si_meminfo_node
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:steal_suitable_fallback
```
```
In mm/swap_state.c (ffffffff813f92fe)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cache_get_folio
  - mm/swap_state.c:show_swap_cache_info
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swapfile.c (ffffffff81400b3b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swapfile.c:si_swapinfo
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/swap_slots.c (ffffffff814017af)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/zswap.c (ffffffff81403d9b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff8140c685)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_report_usage
```
```
In mm/slub.c (ffffffff8142e447)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:get_slabinfo
  - mm/slub.c:slab_debug_trace_open
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:validate_slab_cache
  - mm/slub.c:validate_slab_cache
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:slab_out_of_memory
```
```
In mm/kfence/core.c (ffffffff8142fffb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/kfence/core.c:__kfence_alloc
  - mm/kfence/core.c:stats_show
```
```
In mm/migrate.c (ffffffff814331eb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
```
```
In mm/huge_memory.c (ffffffff814428fc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:hugepage_init
```
```
In mm/page_counter.c (ffffffff8144d2b9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff8145b6b3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:__get_obj_cgroup_from_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_size
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff8145d3a7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/zsmalloc.c (ffffffff81466a35)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_zpool_total_size
```
```
In mm/memremap.c (ffffffff8146f8c5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/open.c (ffffffff81473675)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/open.c:filp_close
  - fs/open.c:do_sys_openat2
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff8147bcdd)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write_iter
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
```
```
In fs/file_table.c (ffffffff8147c61e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:files_maxfiles_init
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/exec.c (ffffffff81485c2a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
```
```
In fs/namei.c (ffffffff8148eba5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:lookup_one
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/readdir.c (ffffffff81497ab2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/dcache.c (ffffffff8149ce46)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff814a2617)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/attr.c (ffffffff814a5a32)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
```
```
In fs/file.c (ffffffff814a839a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/file.c:__fdget_pos
  - fs/file.c:__fget_light
  - fs/file.c:fget_task
  - fs/file.c:fget_raw
  - fs/file.c:fget
```
```
In fs/namespace.c (ffffffff814ad775)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/namespace.c:sb_prepare_remount_readonly
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/xattr.c (ffffffff814b5b88)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/libfs.c (ffffffff814b7b6f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/libfs.c:inode_maybe_inc_iversion
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/fs-writeback.c (ffffffff814c3034)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/sync.c (ffffffff814c8245)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/nsfs.c (ffffffff814cca14)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/remap_range.c (ffffffff814d113e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
```
```
In fs/notify/fsnotify.c (ffffffff814dc962)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/aio.c (ffffffff814f0ce6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/posix_acl.c (ffffffff81516080)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
```
```
In fs/fhandle.c (ffffffff8151a2c7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/quota/dquot.c (ffffffff815239ab)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/proc/task_mmu.c (ffffffff8153032b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/base.c (ffffffff815328b5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/proc/array.c (ffffffff8153c47f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/meminfo.c (ffffffff8153e4c0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/kernfs/file.c (ffffffff8154ce31)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
```
```
In fs/configfs/dir.c (ffffffff81553b12)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff8155691c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/ext4/balloc.c (ffffffff81556a7b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/dir.c (ffffffff81559712)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff81564e04)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:__ext4_ext_dirty
```
```
In fs/ext4/file.c (ffffffff81569ff3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/ialloc.c (ffffffff8156d7bc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/ext4/inline.c (ffffffff815774d4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff8157b9e6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/mballoc.c (ffffffff815940f5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
```
```
In fs/ext4/super.c (ffffffff815bf311)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/sysfs.c (ffffffff815cd4a8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In fs/ext4/xattr.c (ffffffff815cec3e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/ext4/orphan.c (ffffffff815d8733)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/fat/file.c (ffffffff8160095b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/fat/namei_vfat.c (ffffffff8160636b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_revalidate
```
```
In fs/fuse/dir.c (ffffffff8161ef4c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff81624c8f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/inode.c (ffffffff83ecec44)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:set_global_limit
  - fs/fuse/inode.c:fuse_ilookup
```
```
In fs/fuse/readdir.c (ffffffff8162f5a8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/debugfs/inode.c (ffffffff81633d66)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81637a29)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In fs/pstore/inode.c (ffffffff81638680)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
```
```
In security/security.c (ffffffff81665104)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In security/landlock/fs.c (ffffffff816f0b98)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff816f4d21)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
```
```
In security/integrity/ima/ima_main.c (ffffffff816f679c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In security/integrity/ima/ima_api.c (ffffffff816f981c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In security/integrity/ima/ima_kexec.c (ffffffff81700fa8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_kexec.c:ima_add_kexec_buffer
```
```
In block/blk-core.c (ffffffff817364a8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-ioc.c (ffffffff8173a9c8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:ioc_find_get_icq
```
```
In block/blk-mq.c (ffffffff817423af)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_get_new_requests
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff8174bec2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/genhd.c (ffffffff81750dd0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/genhd.c:part_inflight_show
  - block/genhd.c:part_inflight_show
  - block/genhd.c:part_in_flight
  - block/genhd.c:part_in_flight
```
```
In block/blk-cgroup.c (ffffffff81763964)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-cgroup-rwstat.c (ffffffff8176419b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
```
```
In block/blk-iocost.c (ffffffff817703ea)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_lat_stat
  - block/blk-iocost.c:ioc_lat_stat
  - block/blk-iocost.c:ioc_lat_stat
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:__propagate_weights
  - block/blk-iocost.c:ioc_now
```
```
In io_uring/sync.c (ffffffff81793cc1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - io_uring/sync.c:io_fallocate
```
```
In io_uring/openclose.c (ffffffff817947e0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - io_uring/openclose.c:io_openat2
```
```
In io_uring/fdinfo.c (ffffffff8179b972)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - io_uring/fdinfo.c:io_uring_show_fdinfo
```
```
In io_uring/rsrc.c (ffffffff817a086d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_account_mem
```
```
In io_uring/rw.c (ffffffff817a3a17)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In lib/percpu-refcount.c (ffffffff817d8fd2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_exit
```
```
In lib/genalloc.c (ffffffff817edebc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_avail
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/pci/p2pdma.c (ffffffff8191c6f8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_alloc_p2pmem
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a15c64)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
```
In drivers/tty/tty_ldsem.c (ffffffff81a56af5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
```
```
In drivers/char/agp/backend.c (ffffffff81a9c9e5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_initialize
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad535c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:fq_ring_free
```
```
In drivers/base/memory.c (ffffffff81b16d60)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:memory_block_online
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81b69062)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_show_fdinfo
```
```
In drivers/spi/spi.c (ffffffff81bd4c63)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
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
```
```
In drivers/net/loopback.c (ffffffff81bdaad3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/net/loopback.c:dev_lstats_read
  - drivers/net/loopback.c:dev_lstats_read
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81be5725)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdio_bus_device_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
```
```
In drivers/net/tun.c (ffffffff81beb2c7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_get_stats64
```
```
In drivers/md/md.c (ffffffff81ceee89)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/md.c:mismatch_cnt_show
```
```
In drivers/md/dm-stats.c (ffffffff81d1c792)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:__check_shared_memory
```
```
In drivers/firmware/efi/cper.c (ffffffff81d645e5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff81d99c3f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/sock.c:proto_seq_printf
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_setsockopt
```
```
In net/core/skbuff.c (ffffffff81da6633)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_account_pinned_pages
```
```
In net/core/gen_stats.c (ffffffff81db1ea5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff81db2c5c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff81dc171f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:netdev_stats_to_stats64
```
```
In net/core/sock_diag.c (ffffffff81e02fe4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
```
```
In net/core/xdp.c (ffffffff81e06e57)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/net-sysfs.c (ffffffff81e0ad19)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_timeout_show
```
```
In net/core/page_pool.c (ffffffff81e100fb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_return_skb_page
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
```
```
In net/core/drop_monitor.c (ffffffff81e25ed4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
```
```
In net/core/devlink.c (ffffffff81e39623)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_read
  - net/core/devlink.c:devlink_trap_stats_read
```
```
In net/ipv4/inetpeer.c (ffffffff83f0e3c5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_initpeers
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea59cd)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea6e73)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81eb1307)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff81eb8534)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed66df)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_net_metrics_init
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0ae99)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/nexthop.c (ffffffff81f14ddb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nh_res_table_upkeep
```
```
In net/ipv4/proc.c (ffffffff81f190f2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/proc.c:icmp_put
  - net/ipv4/proc.c:icmp_put
  - net/ipv4/proc.c:icmpmsg_put
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/unix/af_unix.c (ffffffff81f4c115)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81f50a90)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/unix/scm.c (ffffffff81f51a0b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/addrconf.c (ffffffff81f5da08)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/proc.c (ffffffff81fb50ee)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_seq_show_item
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:sockstat6_seq_show
```
```
In net/ipv6/seg6_local.c (ffffffff81fbbbfd)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/packet/af_packet.c (ffffffff81fc4fdd)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81ff04bd)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/mptcp/protocol.c (ffffffff81ff6c29)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
```
In net/mptcp/subflow.c (ffffffff82000239)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
```
```
In net/mptcp/options.c (ffffffff82003255)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
```
```
In lib/show_mem.c (ffffffff8203cf7d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/show_mem.c:__show_mem
  - lib/show_mem.c:__show_mem
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
In arch/x86/events/core.c (ffffffff81007714)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100ed40)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/ibs.c:perf_ibs_event_update
```
```
In arch/x86/events/msr.c (ffffffff81010173)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff81013ed5)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
```
```
In arch/x86/events/intel/bts.c (ffffffff810170f3)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff81017dc8)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff810214e4)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
```
```
In arch/x86/events/intel/uncore.c (ffffffff81024ee7)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In arch/x86/kernel/nmi.c (ffffffff81053786)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_backtrace_stall_check
  - arch/x86/kernel/nmi.c:nmi_backtrace_stall_snap
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81097408)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_direct
```
```
In arch/x86/kernel/pvclock.c (ffffffff821410c0)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read_nowd
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In arch/x86/mm/tlb.c (ffffffff810cc3c0)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_func
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e7e8a)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_get_local64
```
```
In kernel/fork.c (ffffffff810f22fe)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
  - kernel/fork.c:fork_init
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In kernel/workqueue.c (ffffffff8111e03c)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/workqueue.c:show_pwq
  - kernel/workqueue.c:show_pwq
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__cancel_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:pwq_activate_inactive_work
  - kernel/workqueue.c:wq_cpu_intensive_report
```
```
In kernel/ucount.c (ffffffff81137ea0)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/ucount.c:is_rlimit_overlimit
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/fair.c (ffffffff8115a6b5)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_cfs_group
```
```
In kernel/sched/build_utility.c (ffffffff81187d72)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
```
```
In kernel/locking/mutex.c (ffffffff82154440)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_trylock
  - kernel/locking/mutex.c:ww_mutex_trylock
  - kernel/locking/mutex.c:ww_mutex_trylock
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/mutex.c:mutex_is_locked
```
```
In kernel/locking/rwsem.c (ffffffff8118dfc1)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/power/snapshot.c (ffffffff81198634)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_image_size_init
```
```
In kernel/power/swap.c (ffffffff8119a222)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:swap_write_page
  - kernel/power/swap.c:swap_write_page
```
```
In kernel/printk/printk.c (ffffffff811a02e7)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff811a5a81)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_next_seq
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
  - kernel/printk/printk_ringbuffer.c:prb_read
  - kernel/printk/printk_ringbuffer.c:prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
  - kernel/printk/printk_ringbuffer.c:data_realloc
  - kernel/printk/printk_ringbuffer.c:data_alloc
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:data_push_tail
  - kernel/printk/printk_ringbuffer.c:data_push_tail
  - kernel/printk/printk_ringbuffer.c:desc_read
  - kernel/printk/printk_ringbuffer.c:desc_read
```
```
In kernel/rcu/srcutree.c (ffffffff811bf540)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:srcu_readers_active
  - kernel/rcu/srcutree.c:srcu_readers_active
  - kernel/rcu/srcutree.c:srcu_readers_active
  - kernel/rcu/srcutree.c:srcu_readers_active
```
```
In kernel/dma/swiotlb.c (ffffffff811d6745)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:io_tlb_hiwater_get
  - kernel/dma/swiotlb.c:io_tlb_used_get
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/dma/swiotlb.c:swiotlb_do_find_slots
```
```
In kernel/dma/pool.c (ffffffff836d29a8)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_atomic_pool_init
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811ff1c3)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
```
```
In kernel/futex/core.c (ffffffff81208070)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/acct.c (ffffffff81212a4f)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/kexec_core.c (ffffffff8121428a)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In kernel/cgroup/cgroup.c (ffffffff81226817)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8122a2cc)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8122b6ae)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff8122b866)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_current_read
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/cgroup/rdma.c (ffffffff8122cca0)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81235149)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/cgroup/misc.c (ffffffff81235392)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_events_show
  - kernel/cgroup/misc.c:misc_cg_current_show
  - kernel/cgroup/misc.c:misc_cg_res_total_usage
```
```
In kernel/trace/ring_buffer.c (ffffffff81278495)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_iter_empty
  - kernel/trace/ring_buffer.c:ring_buffer_iter_empty
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_handle_head_page
  - kernel/trace/ring_buffer.c:rb_iter_head_event
  - kernel/trace/ring_buffer.c:rb_iter_head_event
  - kernel/trace/ring_buffer.c:rb_remove_pages
  - kernel/trace/ring_buffer.c:ring_buffer_nr_dirty_pages
  - kernel/trace/ring_buffer.c:ring_buffer_nr_dirty_pages
  - kernel/trace/ring_buffer.c:ring_buffer_nr_dirty_pages
  - kernel/trace/ring_buffer.c:ring_buffer_event_time_stamp
  - kernel/trace/ring_buffer.c:ring_buffer_event_time_stamp
```
```
In kernel/trace/trace.c (ffffffff8127bf7c)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/trace/trace.c:latency_fsnotify_workfn
```
```
In kernel/trace/tracing_map.c (ffffffff8128efe0)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_cmp_atomic64
  - kernel/trace/tracing_map.c:tracing_map_cmp_atomic64
  - kernel/trace/tracing_map.c:tracing_map_read_var_once
  - kernel/trace/tracing_map.c:tracing_map_read_var
  - kernel/trace/tracing_map.c:tracing_map_read_sum
```
```
In kernel/trace/trace_osnoise.c (ffffffff81297e19)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:timerlat_irq
  - kernel/trace/trace_osnoise.c:timerlat_irq
  - kernel/trace/trace_osnoise.c:timerlat_irq
  - kernel/trace/trace_osnoise.c:timerlat_irq
  - kernel/trace/trace_osnoise.c:timerlat_irq
  - kernel/trace/trace_osnoise.c:timerlat_irq
  - kernel/trace/trace_osnoise.c:trace_sched_switch_callback
  - kernel/trace/trace_osnoise.c:trace_sched_switch_callback
  - kernel/trace/trace_osnoise.c:trace_sched_switch_callback
  - kernel/trace/trace_osnoise.c:trace_sched_switch_callback
  - kernel/trace/trace_osnoise.c:trace_softirq_exit_callback
  - kernel/trace/trace_osnoise.c:trace_softirq_exit_callback
  - kernel/trace/trace_osnoise.c:trace_softirq_entry_callback
  - kernel/trace/trace_osnoise.c:trace_softirq_entry_callback
  - kernel/trace/trace_osnoise.c:osnoise_trace_irq_exit
  - kernel/trace/trace_osnoise.c:osnoise_trace_irq_exit
  - kernel/trace/trace_osnoise.c:osnoise_trace_irq_entry
  - kernel/trace/trace_osnoise.c:osnoise_trace_irq_entry
```
```
In kernel/trace/trace_events_hist.c (ffffffff812baad9)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
```
```
In kernel/bpf/syscall.c (ffffffff812eba05)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_inc_not_zero
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:__bpf_map_inc_not_zero
```
```
In kernel/bpf/helpers.c (ffffffff81321557)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_ancestor
  - kernel/bpf/helpers.c:bpf_cgroup_acquire
  - kernel/bpf/helpers.c:bpf_timer_set_callback
  - kernel/bpf/helpers.c:bpf_timer_init
```
```
In kernel/bpf/task_iter.c (ffffffff81325606)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In kernel/bpf/memalloc.c (ffffffff8134c567)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8135d19a)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_sys_lookup_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_sys_lookup_elem
```
```
In kernel/events/core.c (ffffffff813725dd)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:perf_get_aux_event
```
```
In kernel/events/ring_buffer.c (ffffffff8137c40c)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - kernel/events/ring_buffer.c:perf_output_put_handle
```
```
In mm/oom_kill.c (ffffffff81396c72)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:oom_badness
```
```
In mm/page-writeback.c (ffffffff8139c758)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:__wb_calc_thresh
  - mm/page-writeback.c:bdi_set_max_bytes
  - mm/page-writeback.c:bdi_set_max_bytes
  - mm/page-writeback.c:bdi_set_max_bytes
  - mm/page-writeback.c:bdi_set_min_bytes
  - mm/page-writeback.c:bdi_set_min_bytes
  - mm/page-writeback.c:bdi_set_min_bytes
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/swap.c (ffffffff836dfaf5)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/vmscan.c (ffffffff813ba525)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:allow_direct_reclaim
  - mm/vmscan.c:allow_direct_reclaim
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:lru_gen_seq_show
  - mm/vmscan.c:lru_gen_seq_show
  - mm/vmscan.c:shrink_many
  - mm/vmscan.c:shrink_one
  - mm/vmscan.c:shrink_one
  - mm/vmscan.c:try_to_shrink_lruvec
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:lru_gen_age_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:reparent_shrinker_deferred
```
```
In mm/shmem.c (ffffffff813be299)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_one
```
```
In mm/util.c (ffffffff813c475a)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
```
```
In mm/vmstat.c (ffffffff813c9775)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:node_page_state
  - mm/vmstat.c:sum_zone_numa_event_state
  - mm/vmstat.c:sum_zone_node_page_state
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/backing-dev.c (ffffffff813cada6)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/mm_init.c (ffffffff836e317e)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/mm_init.c:mm_core_init
  - mm/mm_init.c:mm_core_init
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mm_init.c:mm_compute_batch_notifier
```
```
In mm/compaction.c (ffffffff813dd31c)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
```
In mm/show_mem.c (ffffffff813debdb)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/show_mem.c:__show_mem
  - mm/show_mem.c:__show_mem
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:si_meminfo_node
  - mm/show_mem.c:si_meminfo
  - mm/show_mem.c:si_meminfo
  - mm/show_mem.c:si_meminfo
  - mm/show_mem.c:si_mem_available
  - mm/show_mem.c:si_mem_available
  - mm/show_mem.c:si_mem_available
  - mm/show_mem.c:si_mem_available
```
```
In mm/workingset.c (ffffffff836e5b45)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_eviction
```
```
In mm/mmap.c (ffffffff813fae95)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
```
```
In mm/rmap.c (ffffffff8140ebca)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
```
```
In mm/vmalloc.c (ffffffff81417983)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:drain_vmap_area_work
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:vmalloc_nr_pages
```
```
In mm/page_alloc.c (ffffffff8141b89c)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/page_alloc.c:try_to_accept_memory
  - mm/page_alloc.c:try_to_accept_memory
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:zone_pcp_init
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:steal_suitable_fallback
```
```
In mm/swap_state.c (ffffffff8142c64d)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cache_get_folio
  - mm/swap_state.c:show_swap_cache_info
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swapfile.c (ffffffff81433a1b)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/swapfile.c:si_swapinfo
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/swap_slots.c (ffffffff8143468f)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/zswap.c (ffffffff81436bfa)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:shrink_worker
```
```
In mm/hugetlb.c (ffffffff8143faf5)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_report_usage
```
```
In mm/slub.c (ffffffff81463b93)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:get_slabinfo
  - mm/slub.c:slab_debug_trace_open
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:validate_slab_cache
  - mm/slub.c:validate_slab_cache
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:slab_out_of_memory
```
```
In mm/kfence/core.c (ffffffff8146598b)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/kfence/core.c:__kfence_alloc
  - mm/kfence/core.c:stats_show
```
```
In mm/migrate.c (ffffffff81468b04)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
```
```
In mm/huge_memory.c (ffffffff81478227)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:hugepage_init
```
```
In mm/page_counter.c (ffffffff81482b79)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff81491323)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:__get_obj_cgroup_from_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_size
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:memcg_check_events
  - mm/memcontrol.c:memcg_check_events
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff81492157)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/zsmalloc.c (ffffffff8149bfd5)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_zpool_total_size
```
```
In mm/memremap.c (ffffffff814a40a5)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/open.c (ffffffff814a7e75)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/open.c:filp_close
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff814b089a)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write_iter
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
```
```
In fs/file_table.c (ffffffff814b10cd)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:files_maxfiles_init
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/namei.c (ffffffff814c43d7)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:lookup_one
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/readdir.c (ffffffff814ccaa2)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/dcache.c (ffffffff814d2266)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff814d7777)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/attr.c (ffffffff814daae1)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
```
```
In fs/file.c (ffffffff814dd386)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/file.c:__fdget_pos
  - fs/file.c:__fget_light
  - fs/file.c:fget_task
  - fs/file.c:fget_raw
  - fs/file.c:fget
```
```
In fs/namespace.c (ffffffff814e2555)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/namespace.c:sb_prepare_remount_readonly
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/xattr.c (ffffffff814ea3d8)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/libfs.c (ffffffff814eca15)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/libfs.c:inode_query_iversion
  - fs/libfs.c:inode_maybe_inc_iversion
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/fs-writeback.c (ffffffff814f8414)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/splice.c (ffffffff814fded0)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
```
In fs/sync.c (ffffffff814fe475)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
```
```
In fs/nsfs.c (ffffffff81502c54)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/remap_range.c (ffffffff815073c9)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
```
```
In fs/notify/fsnotify.c (ffffffff815131b2)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/aio.c (ffffffff81527a86)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/posix_acl.c (ffffffff8154da17)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
```
```
In fs/quota/dquot.c (ffffffff8155bd6a)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/proc/task_mmu.c (ffffffff815684ab)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/base.c (ffffffff8156aaa5)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/proc/array.c (ffffffff815747c0)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/meminfo.c (ffffffff81576790)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/kernfs/file.c (ffffffff81584b04)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
```
```
In fs/configfs/dir.c (ffffffff8158b8a2)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff8158e6dc)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/ext4/balloc.c (ffffffff8158e83b)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/dir.c (ffffffff81591535)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8159ca9c)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:__ext4_ext_dirty
```
```
In fs/ext4/file.c (ffffffff815a1dea)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/ialloc.c (ffffffff815a56ac)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
```
```
In fs/ext4/inline.c (ffffffff815aea0c)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff815b2dde)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/mballoc.c (ffffffff815cb0fc)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
```
```
In fs/ext4/super.c (ffffffff815f64d1)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/sysfs.c (ffffffff81604ca4)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In fs/ext4/xattr.c (ffffffff8160651d)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/ext4/orphan.c (ffffffff816102c7)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/fat/file.c (ffffffff8163884e)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/fat/namei_vfat.c (ffffffff8163df0f)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_revalidate
```
```
In fs/fuse/dir.c (ffffffff8165736c)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff8165d02d)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/inode.c (ffffffff836f3cd4)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:set_global_limit
  - fs/fuse/inode.c:fuse_ilookup
```
```
In fs/fuse/readdir.c (ffffffff8166781b)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/debugfs/inode.c (ffffffff8166c08f)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8166fe29)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In fs/pstore/inode.c (ffffffff81670a80)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
```
```
In security/security.c (ffffffff8169d62c)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
```
```
In security/landlock/fs.c (ffffffff8172b038)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff8172ee31)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
```
```
In security/integrity/ima/ima_kexec.c (ffffffff8173b048)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - security/integrity/ima/ima_kexec.c:ima_add_kexec_buffer
```
```
In crypto/aead.c (ffffffff817419db)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_report_stat
  - crypto/aead.c:crypto_aead_report_stat
  - crypto/aead.c:crypto_aead_report_stat
  - crypto/aead.c:crypto_aead_report_stat
  - crypto/aead.c:crypto_aead_report_stat
```
```
In crypto/skcipher.c (ffffffff81742665)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_report_stat
  - crypto/skcipher.c:crypto_skcipher_report_stat
  - crypto/skcipher.c:crypto_skcipher_report_stat
  - crypto/skcipher.c:crypto_skcipher_report_stat
  - crypto/skcipher.c:crypto_skcipher_report_stat
```
```
In crypto/ahash.c (ffffffff81744bdb)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
```
```
In crypto/shash.c (ffffffff8174605b)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
```
```
In crypto/akcipher.c (ffffffff8174716b)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_report_stat
  - crypto/akcipher.c:crypto_akcipher_report_stat
  - crypto/akcipher.c:crypto_akcipher_report_stat
  - crypto/akcipher.c:crypto_akcipher_report_stat
  - crypto/akcipher.c:crypto_akcipher_report_stat
  - crypto/akcipher.c:crypto_akcipher_report_stat
  - crypto/akcipher.c:crypto_akcipher_report_stat
```
```
In crypto/kpp.c (ffffffff81747ece)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_kpp_report_stat
  - crypto/kpp.c:crypto_kpp_report_stat
  - crypto/kpp.c:crypto_kpp_report_stat
  - crypto/kpp.c:crypto_kpp_report_stat
```
```
In crypto/acompress.c (ffffffff8174b06b)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - crypto/acompress.c:__crypto_acomp_report_stat
  - crypto/acompress.c:__crypto_acomp_report_stat
  - crypto/acompress.c:__crypto_acomp_report_stat
  - crypto/acompress.c:__crypto_acomp_report_stat
  - crypto/acompress.c:__crypto_acomp_report_stat
```
```
In crypto/rng.c (ffffffff8175856e)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_report_stat
  - crypto/rng.c:crypto_rng_report_stat
  - crypto/rng.c:crypto_rng_report_stat
  - crypto/rng.c:crypto_rng_report_stat
```
```
In block/blk-core.c (ffffffff81772ad9)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-ioc.c (ffffffff817770c8)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:ioc_find_get_icq
```
```
In block/blk-mq.c (ffffffff8177f9d8)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - block/blk-mq.c:blk_rq_poll
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_get_new_requests
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff817885e2)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/genhd.c (ffffffff8178d3a6)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - block/genhd.c:part_inflight_show
  - block/genhd.c:part_inflight_show
  - block/genhd.c:part_in_flight
  - block/genhd.c:part_in_flight
```
```
In block/blk-cgroup.c (ffffffff817a29f4)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-cgroup-rwstat.c (ffffffff817a3233)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
```
```
In block/blk-iocost.c (ffffffff817af41a)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_lat_stat
  - block/blk-iocost.c:ioc_lat_stat
  - block/blk-iocost.c:ioc_lat_stat
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:__propagate_weights
  - block/blk-iocost.c:ioc_now
```
```
In io_uring/sync.c (ffffffff817d49f3)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - io_uring/sync.c:io_fallocate
```
```
In io_uring/fdinfo.c (ffffffff817dcaa4)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - io_uring/fdinfo.c:io_uring_show_fdinfo
```
```
In io_uring/rsrc.c (ffffffff817e1ac1)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_account_mem
```
```
In io_uring/rw.c (ffffffff817e4a5f)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
```
```
In lib/percpu-refcount.c (ffffffff818181e2)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_exit
```
```
In lib/genalloc.c (ffffffff8182e2cc)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_avail
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/pci/p2pdma.c (ffffffff8195fcb8)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_alloc_p2pmem
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5ed14)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
```
In drivers/xen/grant-table.c (ffffffff81a63728)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/tty/tty_ldsem.c (ffffffff81aa10d5)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
```
```
In drivers/char/agp/backend.c (ffffffff81ae8345)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_initialize
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b1a91b)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_event_update
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b23b0c)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:fq_ring_free
```
```
In drivers/base/memory.c (ffffffff81b65ad0)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:memory_block_online
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81bbc492)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_show_fdinfo
```
```
In drivers/spi/spi.c (ffffffff81c29b5c)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_emit_pcpu_stats
```
```
In drivers/net/loopback.c (ffffffff81c31573)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/net/loopback.c:dev_lstats_read
  - drivers/net/loopback.c:dev_lstats_read
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81c3d147)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdio_bus_device_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
```
```
In drivers/net/tun.c (ffffffff81c43707)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_get_stats64
```
```
In drivers/md/md.c (ffffffff81d57c19)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/md/md.c:mismatch_cnt_show
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm-stats.c (ffffffff81d85972)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:__check_shared_memory
```
```
In drivers/firmware/efi/cper.c (ffffffff81dcf715)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff81e07f71)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/core/sock.c:proto_seq_printf
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_setsockopt
```
```
In net/core/skbuff.c (ffffffff81e1573c)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_account_pinned_pages
```
```
In net/core/gen_stats.c (ffffffff81e22475)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff81e2322c)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff81e30f3f)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:netdev_stats_to_stats64
```
```
In net/core/sock_diag.c (ffffffff81e75584)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
```
```
In net/core/xdp.c (ffffffff81e7979a)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/net-sysfs.c (ffffffff81e7e0a9)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_timeout_show
```
```
In net/core/page_pool.c (ffffffff81e8398d)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_return_skb_page
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
```
```
In net/core/drop_monitor.c (ffffffff81e9b474)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
```
```
In net/ipv4/inetpeer.c (ffffffff837349d5)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_initpeers
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f0415f)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f0564d)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81f0f997)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff81f169a4)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f3564b)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_net_metrics_init
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6a9d9)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/nexthop.c (ffffffff81f74aa1)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nh_res_table_upkeep
```
```
In net/ipv4/proc.c (ffffffff81f78d62)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/ipv4/proc.c:icmp_put
  - net/ipv4/proc.c:icmp_put
  - net/ipv4/proc.c:icmpmsg_put
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/unix/af_unix.c (ffffffff81fabef5)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81fb0400)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/unix/scm.c (ffffffff81fb13bb)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/addrconf.c (ffffffff81fbd708)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/proc.c (ffffffff8201582e)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_seq_show_item
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:sockstat6_seq_show
```
```
In net/ipv6/seg6_local.c (ffffffff8201c4fd)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/packet/af_packet.c (ffffffff8202a864)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/devlink/leftover.c (ffffffff8203bf29)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_trap_group_fill
  - net/devlink/leftover.c:devlink_nl_trap_group_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_trap_stats_read
  - net/devlink/leftover.c:devlink_trap_stats_read
```
```
In net/xdp/xdp_umem.c (ffffffff8206c66b)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/mptcp/protocol.c (ffffffff82073309)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
```
In net/mptcp/subflow.c (ffffffff8207c40b)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
```
```
In net/mptcp/options.c (ffffffff8207f3e5)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
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
In arch/x86/events/core.c (ffffffff8100ce34)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/ibs.c (ffffffff81014480)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/ibs.c:perf_ibs_event_update
```
```
In arch/x86/events/msr.c (ffffffff81015915)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff81019515)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
```
```
In arch/x86/events/intel/bts.c (ffffffff8101cc33)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff8101d938)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff81027e64)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
```
```
In arch/x86/events/intel/uncore.c (ffffffff8102b047)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In arch/x86/kernel/nmi.c (ffffffff8105a9a6)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_backtrace_stall_check
  - arch/x86/kernel/nmi.c:nmi_backtrace_stall_snap
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109e978)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_direct
```
```
In arch/x86/kernel/pvclock.c (ffffffff82222fd0)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read_nowd
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In arch/x86/mm/tlb.c (ffffffff810d4a50)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_func
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f021a)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_get_local64
```
```
In kernel/fork.c (ffffffff838f9c66)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In kernel/workqueue.c (ffffffff81127d6c)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/workqueue.c:show_pwq
  - kernel/workqueue.c:show_pwq
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__cancel_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:pwq_activate_inactive_work
  - kernel/workqueue.c:wq_cpu_intensive_report
  - kernel/workqueue.c:kick_pool
```
```
In kernel/cred.c (ffffffff8113eab1)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:get_task_cred
  - kernel/cred.c:__put_cred
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/ucount.c (ffffffff811430b0)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/ucount.c:is_rlimit_overlimit
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/fair.c (ffffffff8116c01d)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_cfs_group
```
```
In kernel/sched/build_utility.c (ffffffff81196522)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
```
```
In kernel/locking/mutex.c (ffffffff82237280)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_trylock
  - kernel/locking/mutex.c:ww_mutex_trylock
  - kernel/locking/mutex.c:ww_mutex_trylock
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/mutex.c:mutex_is_locked
```
```
In kernel/locking/rwsem.c (ffffffff8119c971)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/power/snapshot.c (ffffffff811a74b5)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_image_size_init
```
```
In kernel/power/swap.c (ffffffff811a929d)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:swap_write_page
  - kernel/power/swap.c:swap_write_page
```
```
In kernel/printk/printk.c (ffffffff811af307)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
```
```
In kernel/printk/nbcon.c (ffffffff811b3a85)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/printk/nbcon.c:nbcon_seq_read
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff811b5571)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_next_seq
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
  - kernel/printk/printk_ringbuffer.c:prb_read
  - kernel/printk/printk_ringbuffer.c:prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
  - kernel/printk/printk_ringbuffer.c:data_realloc
  - kernel/printk/printk_ringbuffer.c:data_alloc
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:data_push_tail
  - kernel/printk/printk_ringbuffer.c:data_push_tail
  - kernel/printk/printk_ringbuffer.c:desc_read
  - kernel/printk/printk_ringbuffer.c:desc_read
```
```
In kernel/rcu/update.c (ffffffff811cbc46)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/rcu/update.c:call_rcu_tasks_generic
```
```
In kernel/rcu/srcutree.c (ffffffff811cf9b0)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:srcu_readers_active
  - kernel/rcu/srcutree.c:srcu_readers_active
  - kernel/rcu/srcutree.c:srcu_readers_active
  - kernel/rcu/srcutree.c:srcu_readers_active
```
```
In kernel/rcu/tree.c (ffffffff811d3dff)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/rcu/tree.c:show_rcu_nocb_state
  - kernel/rcu/tree.c:__call_rcu_nocb_wake
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:__call_rcu_common
  - kernel/rcu/tree.c:__call_rcu_common
  - kernel/rcu/tree.c:__call_rcu_common
  - kernel/rcu/tree.c:__call_rcu_common
  - kernel/rcu/tree.c:__call_rcu_common
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_gp_cleanup
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811e2a55)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
```
```
In kernel/dma/swiotlb.c (ffffffff811eb735)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:io_tlb_hiwater_get
  - kernel/dma/swiotlb.c:io_tlb_used_get
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/dma/swiotlb.c:swiotlb_search_pool_area
```
```
In kernel/dma/pool.c (ffffffff83904768)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_atomic_pool_init
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8121558a)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
```
```
In kernel/futex/core.c (ffffffff8121effe)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/acct.c (ffffffff8122a0ef)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/kexec_core.c (ffffffff8122c1da)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In kernel/cgroup/cgroup.c (ffffffff8123e4a7)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_tryget_css
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812422a9)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:task_get_cgroup1
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8124369e)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff81243866)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_current_read
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/cgroup/rdma.c (ffffffff81244d60)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8124ed98)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/cgroup/misc.c (ffffffff8124efe2)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_events_show
  - kernel/cgroup/misc.c:misc_cg_current_show
  - kernel/cgroup/misc.c:misc_cg_res_total_usage
```
```
In kernel/trace/ring_buffer.c (ffffffff81292fa6)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_iter_empty
  - kernel/trace/ring_buffer.c:ring_buffer_iter_empty
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:rb_add_timestamp
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_handle_head_page
  - kernel/trace/ring_buffer.c:rb_handle_head_page
  - kernel/trace/ring_buffer.c:rb_iter_head_event
  - kernel/trace/ring_buffer.c:rb_iter_head_event
  - kernel/trace/ring_buffer.c:rb_remove_pages
  - kernel/trace/ring_buffer.c:rb_remove_pages
  - kernel/trace/ring_buffer.c:ring_buffer_nr_dirty_pages
  - kernel/trace/ring_buffer.c:ring_buffer_nr_dirty_pages
  - kernel/trace/ring_buffer.c:ring_buffer_nr_dirty_pages
  - kernel/trace/ring_buffer.c:ring_buffer_event_time_stamp
  - kernel/trace/ring_buffer.c:ring_buffer_event_time_stamp
```
```
In kernel/trace/trace.c (ffffffff81296c6c)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/trace/trace.c:latency_fsnotify_workfn
```
```
In kernel/trace/tracing_map.c (ffffffff812aa540)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_cmp_atomic64
  - kernel/trace/tracing_map.c:tracing_map_cmp_atomic64
  - kernel/trace/tracing_map.c:tracing_map_read_var_once
  - kernel/trace/tracing_map.c:tracing_map_read_var
  - kernel/trace/tracing_map.c:tracing_map_read_sum
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b347b)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:timerlat_irq
  - kernel/trace/trace_osnoise.c:timerlat_irq
  - kernel/trace/trace_osnoise.c:timerlat_irq
  - kernel/trace/trace_osnoise.c:timerlat_irq
  - kernel/trace/trace_osnoise.c:timerlat_irq
  - kernel/trace/trace_osnoise.c:timerlat_irq
  - kernel/trace/trace_osnoise.c:trace_sched_switch_callback
  - kernel/trace/trace_osnoise.c:trace_sched_switch_callback
  - kernel/trace/trace_osnoise.c:trace_sched_switch_callback
  - kernel/trace/trace_osnoise.c:trace_sched_switch_callback
  - kernel/trace/trace_osnoise.c:trace_softirq_exit_callback
  - kernel/trace/trace_osnoise.c:trace_softirq_exit_callback
  - kernel/trace/trace_osnoise.c:trace_softirq_entry_callback
  - kernel/trace/trace_osnoise.c:trace_softirq_entry_callback
  - kernel/trace/trace_osnoise.c:osnoise_trace_irq_exit
  - kernel/trace/trace_osnoise.c:osnoise_trace_irq_exit
  - kernel/trace/trace_osnoise.c:osnoise_trace_irq_entry
  - kernel/trace/trace_osnoise.c:osnoise_trace_irq_entry
```
```
In kernel/trace/trace_events_hist.c (ffffffff812d7129)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
```
```
In kernel/bpf/syscall.c (ffffffff81309f55)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_inc_not_zero
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:__bpf_map_inc_not_zero
```
```
In kernel/bpf/helpers.c (ffffffff81343c87)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_ancestor
  - kernel/bpf/helpers.c:bpf_cgroup_acquire
  - kernel/bpf/helpers.c:bpf_timer_set_callback
  - kernel/bpf/helpers.c:bpf_timer_init
```
```
In kernel/bpf/map_in_map.c (ffffffff813553c3)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr
```
```
In kernel/bpf/mprog.c (ffffffff8135c8e2)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/bpf/mprog.c:bpf_mprog_query
  - kernel/bpf/mprog.c:bpf_mprog_detach
  - kernel/bpf/mprog.c:bpf_mprog_attach
```
```
In kernel/bpf/memalloc.c (ffffffff81371ec3)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff813858aa)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_sys_lookup_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_sys_lookup_elem
```
```
In kernel/events/core.c (ffffffff8139b94d)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_swevent_event
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:perf_get_aux_event
```
```
In kernel/events/ring_buffer.c (ffffffff813a565c)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - kernel/events/ring_buffer.c:perf_output_put_handle
```
```
In mm/oom_kill.c (ffffffff813c09e2)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:oom_badness
```
```
In mm/page-writeback.c (ffffffff813c6438)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:__wb_calc_thresh
  - mm/page-writeback.c:bdi_set_max_bytes
  - mm/page-writeback.c:bdi_set_max_bytes
  - mm/page-writeback.c:bdi_set_max_bytes
  - mm/page-writeback.c:bdi_set_min_bytes
  - mm/page-writeback.c:bdi_set_min_bytes
  - mm/page-writeback.c:bdi_set_min_bytes
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/swap.c (ffffffff83912375)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/vmscan.c (ffffffff813e3645)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:allow_direct_reclaim
  - mm/vmscan.c:allow_direct_reclaim
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:lru_gen_seq_show
  - mm/vmscan.c:lru_gen_seq_show
  - mm/vmscan.c:shrink_many
  - mm/vmscan.c:shrink_one
  - mm/vmscan.c:shrink_one
  - mm/vmscan.c:try_to_shrink_lruvec
  - mm/vmscan.c:should_abort_scan
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:isolate_folios
  - mm/vmscan.c:lru_gen_age_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:prepare_scan_control
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/shrinker.c (ffffffff813e4c38)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/shrinker.c:reparent_shrinker_deferred
```
```
In mm/shmem.c (ffffffff813e72f8)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_one
```
```
In mm/util.c (ffffffff813ef1da)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
```
```
In mm/vmstat.c (ffffffff813f4105)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:node_page_state
  - mm/vmstat.c:sum_zone_numa_event_state
  - mm/vmstat.c:sum_zone_node_page_state
  - mm/vmstat.c:calculate_normal_threshold
```
```
In mm/backing-dev.c (ffffffff813f5d86)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/mm_init.c (ffffffff83915a0e)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/mm_init.c:mm_core_init
  - mm/mm_init.c:mm_core_init
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mm_init.c:mm_compute_batch_notifier
```
```
In mm/compaction.c (ffffffff8140727c)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
```
In mm/show_mem.c (ffffffff81408aab)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/show_mem.c:__show_mem
  - mm/show_mem.c:__show_mem
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:si_meminfo_node
  - mm/show_mem.c:si_meminfo
  - mm/show_mem.c:si_meminfo
  - mm/show_mem.c:si_meminfo
  - mm/show_mem.c:si_mem_available
  - mm/show_mem.c:si_mem_available
  - mm/show_mem.c:si_mem_available
  - mm/show_mem.c:si_mem_available
  - mm/show_mem.c:si_mem_available
```
```
In mm/workingset.c (ffffffff83918385)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_eviction
```
```
In mm/mmap.c (ffffffff81426ae5)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
```
```
In mm/rmap.c (ffffffff8143b58a)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
```
```
In mm/vmalloc.c (ffffffff814444d3)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:drain_vmap_area_work
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:vmalloc_nr_pages
```
```
In mm/page_alloc.c (ffffffff814488dc)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/page_alloc.c:try_to_accept_memory
  - mm/page_alloc.c:try_to_accept_memory
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:zone_batchsize
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:steal_suitable_fallback
```
```
In mm/slub.c (ffffffff8145fde3)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:get_slabinfo
  - mm/slub.c:slab_debug_trace_open
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:validate_slab_cache
  - mm/slub.c:validate_slab_cache
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:slab_out_of_memory
```
```
In mm/swap_state.c (ffffffff81465d80)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cache_get_folio
  - mm/swap_state.c:show_swap_cache_info
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swapfile.c (ffffffff8146ce0b)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/swapfile.c:si_swapinfo
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/swap_slots.c (ffffffff8146da89)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/zswap.c (ffffffff81470745)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
  - mm/zswap.c:shrink_worker
  - mm/zswap.c:shrink_worker
  - mm/zswap.c:zswap_shrinker_count
  - mm/zswap.c:zswap_shrinker_scan
```
```
In mm/hugetlb.c (ffffffff81479715)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_report_usage
```
```
In mm/kfence/core.c (ffffffff81494c6b)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/kfence/core.c:__kfence_alloc
  - mm/kfence/core.c:stats_show
```
```
In mm/migrate.c (ffffffff8149ac3b)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:migrate_misplaced_folio
```
```
In mm/huge_memory.c (ffffffff814a7967)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:hugepage_init
```
```
In mm/page_counter.c (ffffffff814b1ef9)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff814c0c93)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_css_rstat_flush
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:get_obj_cgroup_from_folio
  - mm/memcontrol.c:current_objcg_update
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:reclaim_high
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_size
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_current
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:memcg_check_events
  - mm/memcontrol.c:memcg_check_events
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_memcg_lruvec_state
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff814c1b67)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/zsmalloc.c (ffffffff814cb6f5)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_zpool_total_size
```
```
In mm/memremap.c (ffffffff814d4f52)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/open.c (ffffffff814d8a15)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/open.c:filp_flush
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff814e203d)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_readv
  - fs/read_write.c:vfs_iter_write
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:vfs_iter_read
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write_iter
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:rw_verify_area
```
```
In fs/file_table.c (ffffffff814e2a10)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:files_maxfiles_init
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/namei.c (ffffffff814f635f)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:lookup_one
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/readdir.c (ffffffff814ff5de)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
  - fs/readdir.c:iterate_dir
```
```
In fs/dcache.c (ffffffff81504ca6)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff81509cdd)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/inode.c:inode_needs_update_time
  - fs/inode.c:__destroy_inode
```
```
In fs/attr.c (ffffffff8150d081)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
```
```
In fs/file.c (ffffffff8150ede0)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:__fdget_pos
  - fs/file.c:__fdget_pos
  - fs/file.c:__fdget_raw
  - fs/file.c:task_lookup_next_fdget_rcu
  - fs/file.c:task_lookup_fdget_rcu
  - fs/file.c:lookup_fdget_rcu
  - fs/file.c:fget_task
  - fs/file.c:fget
  - fs/file.c:__get_file_rcu
```
```
In fs/namespace.c (ffffffff81516345)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/namespace.c:sb_prepare_remount_readonly
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/xattr.c (ffffffff8151e278)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/libfs.c (ffffffff81520965)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/libfs.c:inode_query_iversion
  - fs/libfs.c:inode_maybe_inc_iversion
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/fs-writeback.c (ffffffff8152cb94)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/splice.c (ffffffff81532aa9)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
```
In fs/sync.c (ffffffff81533075)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
```
```
In fs/nsfs.c (ffffffff815378a2)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/remap_range.c (ffffffff8153c878)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/notify/fsnotify.c (ffffffff81547662)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/userfaultfd.c (ffffffff8155b83e)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff8155c816)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/posix_acl.c (ffffffff81583847)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
```
```
In fs/quota/dquot.c (ffffffff815924ea)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/proc/task_mmu.c (ffffffff815a0acb)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/base.c (ffffffff815a3485)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/proc/array.c (ffffffff815ad190)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/meminfo.c (ffffffff815af0e0)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/kernfs/file.c (ffffffff815bd554)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
```
```
In fs/configfs/dir.c (ffffffff815c45d8)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff815c73ef)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/ext4/balloc.c (ffffffff815c754b)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/dir.c (ffffffff815ca275)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff815d574c)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:__ext4_ext_dirty
```
```
In fs/ext4/file.c (ffffffff815da927)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/ialloc.c (ffffffff815de51c)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
```
```
In fs/ext4/inline.c (ffffffff815e77cc)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff815ebbd4)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/mballoc.c (ffffffff81603f1c)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
```
```
In fs/ext4/super.c (ffffffff8162edd1)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/sysfs.c (ffffffff8163d964)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In fs/ext4/xattr.c (ffffffff8163f25d)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/ext4/orphan.c (ffffffff81649087)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/fat/file.c (ffffffff81671d3e)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/fat/namei_vfat.c (ffffffff8167747f)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_revalidate
```
```
In fs/fuse/dir.c (ffffffff81690fbc)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_statx
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff81696d8a)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/inode.c (ffffffff83926ea4)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:set_global_limit
  - fs/fuse/inode.c:fuse_ilookup
```
```
In fs/fuse/readdir.c (ffffffff816a1b75)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/debugfs/inode.c (ffffffff816a652f)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff816aaa42)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In fs/tracefs/event_inode.c (ffffffff816abf3f)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/tracefs/event_inode.c:eventfs_create_events_dir
```
```
In fs/pstore/inode.c (ffffffff816ac96c)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
```
```
In security/security.c (ffffffff816dcaf8)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_open
```
```
In security/landlock/fs.c (ffffffff8176cb58)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff8176f791)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
```
```
In security/integrity/ima/ima_main.c (ffffffff8177121c)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_kexec.c (ffffffff8177bbb8)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - security/integrity/ima/ima_kexec.c:ima_add_kexec_buffer
```
```
In crypto/aead.c (ffffffff8178287b)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_report_stat
  - crypto/aead.c:crypto_aead_report_stat
  - crypto/aead.c:crypto_aead_report_stat
  - crypto/aead.c:crypto_aead_report_stat
  - crypto/aead.c:crypto_aead_report_stat
```
```
In crypto/lskcipher.c (ffffffff817834e5)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - crypto/lskcipher.c:crypto_lskcipher_report_stat
  - crypto/lskcipher.c:crypto_lskcipher_report_stat
  - crypto/lskcipher.c:crypto_lskcipher_report_stat
  - crypto/lskcipher.c:crypto_lskcipher_report_stat
  - crypto/lskcipher.c:crypto_lskcipher_report_stat
```
```
In crypto/skcipher.c (ffffffff817848b5)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_report_stat
  - crypto/skcipher.c:crypto_skcipher_report_stat
  - crypto/skcipher.c:crypto_skcipher_report_stat
  - crypto/skcipher.c:crypto_skcipher_report_stat
  - crypto/skcipher.c:crypto_skcipher_report_stat
```
```
In crypto/ahash.c (ffffffff8178740b)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
```
```
In crypto/shash.c (ffffffff8178869b)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
```
```
In crypto/akcipher.c (ffffffff81788fdb)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_report_stat
  - crypto/akcipher.c:crypto_akcipher_report_stat
  - crypto/akcipher.c:crypto_akcipher_report_stat
  - crypto/akcipher.c:crypto_akcipher_report_stat
  - crypto/akcipher.c:crypto_akcipher_report_stat
  - crypto/akcipher.c:crypto_akcipher_report_stat
  - crypto/akcipher.c:crypto_akcipher_report_stat
```
```
In crypto/kpp.c (ffffffff81789d3e)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_kpp_report_stat
  - crypto/kpp.c:crypto_kpp_report_stat
  - crypto/kpp.c:crypto_kpp_report_stat
  - crypto/kpp.c:crypto_kpp_report_stat
```
```
In crypto/acompress.c (ffffffff8178cf3b)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - crypto/acompress.c:__crypto_acomp_report_stat
  - crypto/acompress.c:__crypto_acomp_report_stat
  - crypto/acompress.c:__crypto_acomp_report_stat
  - crypto/acompress.c:__crypto_acomp_report_stat
  - crypto/acompress.c:__crypto_acomp_report_stat
```
```
In crypto/rng.c (ffffffff8179a46e)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_report_stat
  - crypto/rng.c:crypto_rng_report_stat
  - crypto/rng.c:crypto_rng_report_stat
  - crypto/rng.c:crypto_rng_report_stat
```
```
In block/blk-core.c (ffffffff817b4e73)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-ioc.c (ffffffff817b92f8)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:ioc_find_get_icq
```
```
In block/blk-mq.c (ffffffff817c24b8)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - block/blk-mq.c:blk_rq_poll
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff817cacb2)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/genhd.c (ffffffff817cfc06)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - block/genhd.c:part_inflight_show
  - block/genhd.c:part_inflight_show
  - block/genhd.c:part_in_flight
  - block/genhd.c:part_in_flight
```
```
In block/blk-cgroup.c (ffffffff817e6537)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-cgroup-rwstat.c (ffffffff817e6d83)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
```
```
In block/blk-iocost.c (ffffffff817f322d)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_lat_stat
  - block/blk-iocost.c:ioc_lat_stat
  - block/blk-iocost.c:ioc_lat_stat
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:__propagate_weights
  - block/blk-iocost.c:ioc_now
```
```
In io_uring/sync.c (ffffffff81818854)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - io_uring/sync.c:io_fallocate
```
```
In io_uring/rsrc.c (ffffffff81825e81)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_account_mem
```
```
In io_uring/rw.c (ffffffff81828f05)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
```
```
In lib/percpu-refcount.c (ffffffff8185d4e2)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_exit
```
```
In lib/genalloc.c (ffffffff8187fe8c)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_avail
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/pci/p2pdma.c (ffffffff819a9378)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_alloc_p2pmem
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab1474)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
```
In drivers/xen/grant-table.c (ffffffff81ab5f77)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/tty/tty_ldsem.c (ffffffff81af3b35)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
```
```
In drivers/char/agp/backend.c (ffffffff81b3b7b5)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_initialize
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b7044b)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_event_update
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b7959a)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:queue_iova
  - drivers/iommu/dma-iommu.c:fq_ring_free_locked
```
```
In drivers/base/memory.c (ffffffff81bb9950)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:memory_block_online
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81c10c92)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_show_fdinfo
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb3e78)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_count_and_time
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_count
  - drivers/gpu/drm/drm_vblank.c:drm_update_vblank_count
```
```
In drivers/gpu/drm/drm_vblank_work.c (ffffffff81cb7bb5)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank_work.c:drm_handle_vblank_works
```
```
In drivers/spi/spi.c (ffffffff81cdc3ac)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_emit_pcpu_stats
```
```
In drivers/net/loopback.c (ffffffff81ce43f3)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/net/loopback.c:dev_lstats_read
  - drivers/net/loopback.c:dev_lstats_read
```
```
In drivers/net/netkit.c (ffffffff81ce49f1)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_get_stats
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81cf24f7)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdio_bus_device_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
```
```
In drivers/net/tun.c (ffffffff81cf9017)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_get_stats64
```
```
In drivers/net/virtio_net.c (ffffffff81d01353)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_get_ethtool_stats
  - drivers/net/virtio_net.c:virtnet_get_ethtool_stats
  - drivers/net/virtio_net.c:virtnet_stats
  - drivers/net/virtio_net.c:virtnet_stats
  - drivers/net/virtio_net.c:virtnet_stats
  - drivers/net/virtio_net.c:virtnet_stats
  - drivers/net/virtio_net.c:virtnet_stats
  - drivers/net/virtio_net.c:virtnet_stats
  - drivers/net/virtio_net.c:virtnet_stats
  - drivers/net/virtio_net.c:virtnet_stats
  - drivers/net/virtio_net.c:virtnet_stats
  - drivers/net/virtio_net.c:virtnet_stats
  - drivers/net/virtio_net.c:virtnet_poll
  - drivers/net/virtio_net.c:virtnet_poll
```
```
In drivers/md/md.c (ffffffff81e0eab9)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/md/md.c:mismatch_cnt_show
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm-stats.c (ffffffff81e3d0b2)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:__check_shared_memory
```
```
In drivers/firmware/efi/cper.c (ffffffff81e88445)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff81ec49b1)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/core/sock.c:proto_seq_printf
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_setsockopt
```
```
In net/core/skbuff.c (ffffffff81ed2adc)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_account_pinned_pages
  - net/core/skbuff.c:napi_pp_put_page
```
```
In net/core/gen_stats.c (ffffffff81ee03b5)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff81ee119a)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff81eef63f)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:netdev_stats_to_stats64
```
```
In net/core/sock_diag.c (ffffffff81f34e34)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
```
```
In net/core/xdp.c (ffffffff81f39784)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/net-sysfs.c (ffffffff81f3efb9)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_timeout_show
```
```
In net/core/page_pool.c (ffffffff81f447fd)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
```
```
In net/core/drop_monitor.c (ffffffff81f5dbe4)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
```
```
In net/ipv4/inetpeer.c (ffffffff83968f95)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_initpeers
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8497)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fc99b3)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81fd3b87)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff81fdb814)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
```
In net/ipv4/tcp_metrics.c (ffffffff83969917)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
```
```
In net/ipv4/inet_fragment.c (ffffffff82031089)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/nexthop.c (ffffffff8203b241)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nh_res_table_upkeep
```
```
In net/ipv4/proc.c (ffffffff8203f422)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/ipv4/proc.c:icmp_put
  - net/ipv4/proc.c:icmp_put
  - net/ipv4/proc.c:icmpmsg_put
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv4/tcp_ao.c (ffffffff82059546)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_get_sock_info
  - net/ipv4/tcp_ao.c:tcp_ao_get_sock_info
  - net/ipv4/tcp_ao.c:tcp_ao_get_sock_info
  - net/ipv4/tcp_ao.c:tcp_ao_get_sock_info
  - net/ipv4/tcp_ao.c:tcp_ao_get_sock_info
  - net/ipv4/tcp_ao.c:tcp_ao_copy_mkts_to_user
  - net/ipv4/tcp_ao.c:tcp_ao_copy_mkts_to_user
```
```
In net/unix/af_unix.c (ffffffff82079315)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff8207da60)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/unix/scm.c (ffffffff8207eadb)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/addrconf.c (ffffffff8208ab50)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/proc.c (ffffffff820e496e)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_seq_show_item
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:sockstat6_seq_show
```
```
In net/ipv6/seg6_local.c (ffffffff820eb4cd)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/packet/af_packet.c (ffffffff820f7f21)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/devlink/trap.c (ffffffff82115479)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_nl_trap_group_fill
  - net/devlink/trap.c:devlink_nl_trap_group_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
  - net/devlink/trap.c:devlink_trap_stats_read
  - net/devlink/trap.c:devlink_trap_stats_read
```
```
In net/xdp/xdp_umem.c (ffffffff82140469)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/mptcp/protocol.c (ffffffff82147559)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
```
In net/mptcp/subflow.c (ffffffff821518f2)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
```
```
In net/mptcp/options.c (ffffffff821548d5)
Location: arch/x86/include/asm/atomic64_64.h:13
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
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
In arch/x86/events/core.c (ffffffff81007785)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009d3e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100aa54)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100b1f4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
```
In arch/x86/events/msr.c (ffffffff8100b953)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/bts.c (ffffffff8100f7c3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fc3a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81014ad5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017d35)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056105)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
```
In arch/x86/kernel/pvclock.c (ffffffff810782cb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In arch/x86/mm/tlb.c (ffffffff81087d04)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/fork.c (ffffffff8109989f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:get_mm_exe_file
  - kernel/fork.c:fork_init
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In kernel/exit.c (ffffffff8109fd2b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff810b7436)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/workqueue.c (ffffffff810bfadb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:pwq_activate_delayed_work
  - kernel/workqueue.c:get_work_pool
```
```
In kernel/sched/loadavg.c (ffffffff810d90ba)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
```
```
In kernel/sched/fair.c (ffffffff810df074)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
```
```
In kernel/sched/debug.c (ffffffff810f62d7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
```
```
In kernel/locking/mutex.c (ffffffff81a70c45)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_wound
  - kernel/locking/mutex.c:mutex_trylock_recursive
  - kernel/locking/mutex.c:mutex_trylock_recursive
  - kernel/locking/mutex.c:mutex_is_locked
```
```
In kernel/locking/rwsem.c (ffffffff810fceeb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/power/snapshot.c (ffffffff81105a7e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In kernel/power/swap.c (ffffffff81106d28)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113c931)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
```
```
In kernel/futex.c (ffffffff81142e88)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/acct.c (ffffffff8115134f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/kexec_core.c (ffffffff81151d7a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In kernel/cgroup/cgroup.c (ffffffff8115f504)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81161da2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81162f40)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff81162fd7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_current_read
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/cgroup/rdma.c (ffffffff81163e43)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811699db)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/tsacct.c (ffffffff8118e142)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In kernel/trace/ring_buffer.c (ffffffff8119a124)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_iter_empty
  - kernel/trace/ring_buffer.c:ring_buffer_iter_empty
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/trace/tracing_map.c (ffffffff811a8b20)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_cmp_atomic64
  - kernel/trace/tracing_map.c:tracing_map_cmp_atomic64
  - kernel/trace/tracing_map.c:tracing_map_read_var_once
  - kernel/trace/tracing_map.c:tracing_map_read_var
  - kernel/trace/tracing_map.c:tracing_map_read_sum
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c0f3e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
```
```
In kernel/bpf/cgroup.c (ffffffff811fc957)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
```
```
In kernel/events/core.c (ffffffff8120f200)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_swevent_overflow
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:free_event
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_out
```
```
In kernel/events/ring_buffer.c (ffffffff812102fa)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - kernel/events/ring_buffer.c:perf_output_put_handle
```
```
In mm/oom_kill.c (ffffffff81222128)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
```
```
In mm/page-writeback.c (ffffffff81226f4f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:__wb_calc_thresh
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/swap.c (ffffffff828c2793)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/vmscan.c (ffffffff81231a25)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/shmem.c (ffffffff812390bd)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_one
```
```
In mm/util.c (ffffffff8123e068)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:vm_commit_limit
```
```
In mm/vmstat.c (ffffffff8124088b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_numa_state
  - mm/vmstat.c:sum_zone_node_page_state
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/backing-dev.c (ffffffff812412d2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In mm/mm_init.c (ffffffff81a6b88d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/compaction.c (ffffffff8124e45f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
```
In mm/workingset.c (ffffffff828c6213)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
  - mm/workingset.c:workingset_refault
```
```
In mm/memory.c (ffffffff81258a0f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffff812608a5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff8126d09a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81271979)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:vmalloc_nr_pages
```
```
In mm/page_alloc.c (ffffffff81273e46)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:zone_batchsize
  - mm/page_alloc.c:build_zonerefs_node
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo_node
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__isolate_free_page
```
```
In mm/madvise.c (ffffffff8127bd2d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/swap_state.c (ffffffff8127fd05)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swapfile.c (ffffffff81285682)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swapfile.c:si_swapinfo
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/swap_slots.c (ffffffff81286113)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff81287b8c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff8128c855)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_report_usage
```
```
In mm/sparse.c (ffffffff81295fc5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/slub.c (ffffffff812a32e2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:get_slabinfo
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:store_user_store
  - mm/slub.c:poison_store
  - mm/slub.c:red_zone_store
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:list_locations
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:alloc_slab_page
```
```
In mm/huge_memory.c (ffffffff828cb1ca)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In mm/page_counter.c (ffffffff812b7716)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff812b7aac)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_exact_page_state
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_size
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff812c1f03)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/zsmalloc.c (ffffffff812c7527)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_zpool_total_size
```
```
In mm/memremap.c (ffffffff812cc9df)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/open.c (ffffffff812cfcc5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/open.c:filp_close
```
```
In fs/file_table.c (ffffffff828ccb64)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/exec.c (ffffffff812df0a9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/namei.c (ffffffff812e3915)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/inode.c (ffffffff812f4e01)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:generic_update_time
  - fs/inode.c:__destroy_inode
```
```
In fs/attr.c (ffffffff812f73e7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/file.c (ffffffff812f8d96)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/file.c:__fdget_pos
  - fs/file.c:__fget
```
```
In fs/namespace.c (ffffffff812fbbf5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/namespace.c:sb_prepare_remount_readonly
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs-writeback.c (ffffffff8130cdd3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/sync.c (ffffffff813118e5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/nsfs.c (ffffffff81314f57)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/notify/fsnotify.c (ffffffff813251aa)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/eventpoll.c (ffffffff8132bfba)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/userfaultfd.c (ffffffff813325db)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff8133338e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff8133d571)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_get_req
```
```
In fs/quota/dquot.c (ffffffff81360d9b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/proc/task_mmu.c (ffffffff8136743d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/base.c (ffffffff8136b095)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/proc/array.c (ffffffff813719ea)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/meminfo.c (ffffffff81373ae1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/ext4/balloc.c (ffffffff81385e42)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/dir.c (ffffffff8138841f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff813929fd)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:__ext4_ext_dirty
```
```
In fs/ext4/ialloc.c (ffffffff81398728)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/ext4/inline.c (ffffffff813a07db)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff813a7dc0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/namei.c (ffffffff813c30cd)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/super.c (ffffffff813d6278)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/sysfs.c (ffffffff813e0b63)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In fs/ext4/xattr.c (ffffffff813e2ed4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/fat/dir.c (ffffffff813fd59a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff814050d3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff814068d8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff81408ba4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/dir.c (ffffffff8141c698)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/file.c (ffffffff8141f997)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/fuse/inode.c (ffffffff828d7bb8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
```
```
In fs/fuse/readdir.c (ffffffff81428dab)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/pstore/inode.c (ffffffff8142ccad)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
```
```
In security/integrity/ima/ima_fs.c (ffffffff814adc0b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
```
```
In security/integrity/ima/ima_main.c (ffffffff814aee4c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In security/integrity/ima/ima_api.c (ffffffff814b0cb1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/bio.c (ffffffff814d69c8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In block/blk-core.c (ffffffff814df0ea)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-ioc.c (ffffffff814e29a5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In block/blk-mq.c (ffffffff814e74b9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq.c:blk_mq_freeze_queue_wait
```
```
In block/blk-mq-tag.c (ffffffff814ed14e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/genhd.c (ffffffff814f1ece)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/genhd.c:part_in_flight_rw
  - block/genhd.c:part_in_flight_rw
```
```
In block/blk-cgroup.c (ffffffff81503663)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-iocost.c (ffffffff815090a9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:ioc_now
  - block/blk-iocost.c:ioc_refresh_params
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:trace_event_raw_event_iocost_ioc_vrate_adj
```
```
In block/blk-pm.c (ffffffff8151829f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In lib/percpu-refcount.c (ffffffff81522935)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff8152f8a0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_avail
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81626ab0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
```
In drivers/tty/tty_ldsem.c (ffffffff81653d65)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
```
```
In drivers/char/agp/backend.c (ffffffff8168b2f0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_add_bridge
```
```
In drivers/iommu/iova.c (ffffffff816a3200)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/dma-buf/dma-buf.c (ffffffff817192af)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_show_fdinfo
```
```
In drivers/usb/core/devio.c (ffffffff817b2b13)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff818362e5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/md.c:mismatch_cnt_show
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/dm.c (ffffffff8184d921)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm.c:dm_wait_for_completion
```
```
In drivers/md/dm-stats.c (ffffffff8185b066)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
```
In net/core/sock.c (ffffffff818b335a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/core/skbuff.c (ffffffff818b90d1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/core/dev.c (ffffffff818ca780)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
```
```
In net/core/sock_diag.c (ffffffff81900365)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81959e15)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195aa40)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81962720)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff819643ec)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197e803)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff819a669b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/ipv4/proc.c (ffffffff819ae268)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/proc.c:icmpmsg_put
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/unix/af_unix.c (ffffffff819d0131)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff819d3c6d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/unix/scm.c (ffffffff819d429b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/addrconf.c (ffffffff819dd6bb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/proc.c (ffffffff81a1f95d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:sockstat6_seq_show
```
```
In net/packet/af_packet.c (ffffffff81a2c657)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81a4becb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/show_mem.c (ffffffff81a558d1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
  - lib/show_mem.c:show_mem
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
In arch/x86/events/core.c (ffffffff81005f25)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008727)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff81009380)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/amd/iommu.c (ffffffff81009b84)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
```
In arch/x86/events/msr.c (ffffffff8100a338)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/bts.c (ffffffff8100e523)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff8100e9a8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81013da5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017185)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81046315)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
```
In arch/x86/kernel/pvclock.c (ffffffff81067b7b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In arch/x86/mm/tlb.c (ffffffff81076971)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/fork.c (ffffffff810882e5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:get_mm_exe_file
  - kernel/fork.c:fork_init
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In kernel/exit.c (ffffffff8108e75b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff810a5d76)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/workqueue.c (ffffffff810ae2fb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:pwq_activate_delayed_work
  - kernel/workqueue.c:get_work_pool
```
```
In kernel/sched/loadavg.c (ffffffff810c7aba)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
```
```
In kernel/sched/fair.c (ffffffff810ce084)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
```
```
In kernel/sched/debug.c (ffffffff810e6497)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
```
```
In kernel/locking/mutex.c (ffffffff81a2d035)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_wound
  - kernel/locking/mutex.c:mutex_trylock_recursive
  - kernel/locking/mutex.c:mutex_trylock_recursive
  - kernel/locking/mutex.c:mutex_is_locked
```
```
In kernel/locking/rwsem.c (ffffffff810ed0fb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/power/snapshot.c (ffffffff810f6d1e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_image_size_init
```
```
In kernel/power/swap.c (ffffffff810f7c10)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/rcu/srcutree.c (ffffffff8110dc07)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffff811154ff)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff81116305)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112f3a1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
```
```
In kernel/futex.c (ffffffff811361e8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/acct.c (ffffffff8114462f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/kexec_core.c (ffffffff8114505a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In kernel/cgroup/cgroup.c (ffffffff81152794)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81155002)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81156190)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff81156227)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_current_read
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/cgroup/rdma.c (ffffffff81157093)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8115cbdb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/tsacct.c (ffffffff81181252)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In kernel/trace/ring_buffer.c (ffffffff8118d1a4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_iter_empty
  - kernel/trace/ring_buffer.c:ring_buffer_iter_empty
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/trace/tracing_map.c (ffffffff8119baa0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_cmp_atomic64
  - kernel/trace/tracing_map.c:tracing_map_cmp_atomic64
  - kernel/trace/tracing_map.c:tracing_map_read_var_once
  - kernel/trace/tracing_map.c:tracing_map_read_var
  - kernel/trace/tracing_map.c:tracing_map_read_sum
```
```
In kernel/trace/trace_events_hist.c (ffffffff811b3d1e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
```
```
In kernel/bpf/cgroup.c (ffffffff811ef6a7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
```
```
In kernel/events/core.c (ffffffff81201faa)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_swevent_overflow
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:free_event
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_out
```
```
In kernel/events/ring_buffer.c (ffffffff8120308a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - kernel/events/ring_buffer.c:perf_output_put_handle
```
```
In mm/oom_kill.c (ffffffff812152d8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
```
```
In mm/page-writeback.c (ffffffff8121a0bf)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:__wb_calc_thresh
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/swap.c (ffffffff828baebb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/vmscan.c (ffffffff81224ae5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/shmem.c (ffffffff8122c0fd)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_one
```
```
In mm/util.c (ffffffff81231068)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:vm_commit_limit
```
```
In mm/vmstat.c (ffffffff8123388b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_numa_state
  - mm/vmstat.c:sum_zone_node_page_state
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/backing-dev.c (ffffffff812342d2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In mm/mm_init.c (ffffffff81a27dd4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/compaction.c (ffffffff812413ff)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
```
In mm/workingset.c (ffffffff828be938)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
  - mm/workingset.c:workingset_refault
```
```
In mm/memory.c (ffffffff8124aecf)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffff81252cc5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff8125f0ca)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff812638e9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:vmalloc_nr_pages
```
```
In mm/page_alloc.c (ffffffff81265db6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:zone_batchsize
  - mm/page_alloc.c:build_zonerefs_node
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo_node
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__isolate_free_page
```
```
In mm/madvise.c (ffffffff8126dc0d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/swap_state.c (ffffffff81271b4b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swapfile.c (ffffffff812774f2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swapfile.c:si_swapinfo
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/swap_slots.c (ffffffff81277f73)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff812799ec)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff8127e685)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_report_usage
```
```
In mm/sparse.c (ffffffff81287bd5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/slub.c (ffffffff81294db2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:get_slabinfo
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:store_user_store
  - mm/slub.c:poison_store
  - mm/slub.c:red_zone_store
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:list_locations
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:alloc_slab_page
```
```
In mm/huge_memory.c (ffffffff828c38ef)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In mm/page_counter.c (ffffffff812a88e6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff812a8c7c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_exact_page_state
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_size
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff812b2f53)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/zsmalloc.c (ffffffff812b8567)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_zpool_total_size
```
```
In mm/memremap.c (ffffffff812bd84f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/open.c (ffffffff812c0945)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/open.c:filp_close
```
```
In fs/file_table.c (ffffffff828c5280)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/exec.c (ffffffff812cf1b1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/namei.c (ffffffff812d4555)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/inode.c (ffffffff812e5a21)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:generic_update_time
  - fs/inode.c:__destroy_inode
```
```
In fs/attr.c (ffffffff812e8007)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/file.c (ffffffff812e99b6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/file.c:__fdget_pos
  - fs/file.c:__fget
```
```
In fs/namespace.c (ffffffff812ec815)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/namespace.c:sb_prepare_remount_readonly
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs-writeback.c (ffffffff812fd9f3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/sync.c (ffffffff813024f5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/nsfs.c (ffffffff81305b47)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/notify/fsnotify.c (ffffffff81315d4a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/eventpoll.c (ffffffff8131d32a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/userfaultfd.c (ffffffff8132319b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff81323ffe)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff8132e231)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_get_req
```
```
In fs/quota/dquot.c (ffffffff81351a3b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/proc/task_mmu.c (ffffffff813580dd)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/base.c (ffffffff8135bb25)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/proc/array.c (ffffffff813624c6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/meminfo.c (ffffffff813645b1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/ext4/balloc.c (ffffffff813768d2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/dir.c (ffffffff81378eaf)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8138348d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:__ext4_ext_dirty
```
```
In fs/ext4/ialloc.c (ffffffff813891b8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8139126b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff81398850)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/namei.c (ffffffff813b3b5d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/super.c (ffffffff813c6cf8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/sysfs.c (ffffffff813d15e3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In fs/ext4/xattr.c (ffffffff813d3954)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/fat/dir.c (ffffffff813ee01a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff813f5b53)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff813f7358)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff813f9624)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/dir.c (ffffffff8140d118)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/file.c (ffffffff81410417)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/fuse/inode.c (ffffffff828d02d4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
```
```
In fs/fuse/readdir.c (ffffffff8141982b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/pstore/inode.c (ffffffff8141d72d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
```
```
In security/integrity/ima/ima_fs.c (ffffffff8149e62b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
```
```
In security/integrity/ima/ima_main.c (ffffffff8149f86c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In security/integrity/ima/ima_api.c (ffffffff814a16d1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/bio.c (ffffffff814c7388)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In block/blk-core.c (ffffffff814cfa8a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-ioc.c (ffffffff814d3335)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In block/blk-mq.c (ffffffff814d7a29)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq.c:blk_mq_freeze_queue_wait
```
```
In block/blk-mq-tag.c (ffffffff814dd69e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/genhd.c (ffffffff814e23fe)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/genhd.c:part_in_flight_rw
  - block/genhd.c:part_in_flight_rw
```
```
In block/blk-cgroup.c (ffffffff814f3b23)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-iocost.c (ffffffff814f9559)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:ioc_now
  - block/blk-iocost.c:ioc_refresh_params
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:trace_event_raw_event_iocost_ioc_vrate_adj
```
```
In block/blk-pm.c (ffffffff815085a9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In lib/percpu-refcount.c (ffffffff81512c15)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff8151fb80)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_avail
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8161b130)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
```
In drivers/tty/tty_ldsem.c (ffffffff81634145)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
```
```
In drivers/char/agp/backend.c (ffffffff81668cf0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_add_bridge
```
```
In drivers/iommu/iova.c (ffffffff81680bf0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816f271f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_show_fdinfo
```
```
In drivers/usb/core/devio.c (ffffffff817a4543)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff817fd955)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/md.c:mismatch_cnt_show
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/dm.c (ffffffff81814f41)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm.c:dm_wait_for_completion
```
```
In drivers/md/dm-stats.c (ffffffff81822646)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
```
In drivers/firmware/efi/cper.c (ffffffff81845985)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff8186d2aa)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/core/skbuff.c (ffffffff81873021)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/core/dev.c (ffffffff818846c0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
```
```
In net/core/sock_diag.c (ffffffff818ba195)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81913905)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81914530)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff8191c210)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff8191dedc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_metrics.c (ffffffff819382c3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff8196015b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/ipv4/proc.c (ffffffff8196a898)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/proc.c:icmpmsg_put
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/unix/af_unix.c (ffffffff8198cef1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81990a2d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/unix/scm.c (ffffffff8199105b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/addrconf.c (ffffffff8199a47b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/proc.c (ffffffff819dc71d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:sockstat6_seq_show
```
```
In net/packet/af_packet.c (ffffffff819e9847)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81a08abb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/show_mem.c (ffffffff81a129b1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
  - lib/show_mem.c:show_mem
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
In arch/x86/events/core.c (ffffffff81007745)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009cfe)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100aa14)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100b1b4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
```
In arch/x86/events/msr.c (ffffffff8100b913)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/bts.c (ffffffff8100f783)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fbfa)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81014a95)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017cf5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056535)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
```
In arch/x86/kernel/pvclock.c (ffffffff8107827b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In arch/x86/mm/tlb.c (ffffffff81087cb4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/fork.c (ffffffff8109984f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:get_mm_exe_file
  - kernel/fork.c:fork_init
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In kernel/exit.c (ffffffff8109fcdb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff810b6996)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/workqueue.c (ffffffff810bf03b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:pwq_activate_delayed_work
  - kernel/workqueue.c:get_work_pool
```
```
In kernel/sched/loadavg.c (ffffffff810d53fa)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
```
```
In kernel/sched/fair.c (ffffffff810db3f4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
```
```
In kernel/sched/debug.c (ffffffff810f34d7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
```
```
In kernel/locking/mutex.c (ffffffff81add055)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_wound
  - kernel/locking/mutex.c:mutex_trylock_recursive
  - kernel/locking/mutex.c:mutex_trylock_recursive
  - kernel/locking/mutex.c:mutex_is_locked
```
```
In kernel/locking/rwsem.c (ffffffff810fa0ab)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/power/snapshot.c (ffffffff81103d2e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_image_size_init
```
```
In kernel/power/swap.c (ffffffff81104c20)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113a651)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
```
```
In kernel/futex.c (ffffffff81140d38)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/acct.c (ffffffff8114f1ff)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/kexec_core.c (ffffffff8114fc2a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In kernel/cgroup/cgroup.c (ffffffff8115d2d4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115fb72)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81160d10)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff81160da7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_current_read
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/cgroup/rdma.c (ffffffff81161c13)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811677ab)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/tsacct.c (ffffffff8118bf12)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In kernel/trace/ring_buffer.c (ffffffff81197ef4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_iter_empty
  - kernel/trace/ring_buffer.c:ring_buffer_iter_empty
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/trace/tracing_map.c (ffffffff811a68f0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_cmp_atomic64
  - kernel/trace/tracing_map.c:tracing_map_cmp_atomic64
  - kernel/trace/tracing_map.c:tracing_map_read_var_once
  - kernel/trace/tracing_map.c:tracing_map_read_var
  - kernel/trace/tracing_map.c:tracing_map_read_sum
```
```
In kernel/trace/trace_events_hist.c (ffffffff811bed0e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
```
```
In kernel/bpf/cgroup.c (ffffffff811fa727)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
```
```
In kernel/events/core.c (ffffffff8120cfa0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_swevent_overflow
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:free_event
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_out
```
```
In kernel/events/ring_buffer.c (ffffffff8120e09a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - kernel/events/ring_buffer.c:perf_output_put_handle
```
```
In mm/oom_kill.c (ffffffff8121fec8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
```
```
In mm/page-writeback.c (ffffffff81224cef)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:__wb_calc_thresh
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/swap.c (ffffffff828d5516)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/vmscan.c (ffffffff8122f7c5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/shmem.c (ffffffff81236e5d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_one
```
```
In mm/util.c (ffffffff8123be08)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:vm_commit_limit
```
```
In mm/vmstat.c (ffffffff8123e62b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_numa_state
  - mm/vmstat.c:sum_zone_node_page_state
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/backing-dev.c (ffffffff8123f072)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In mm/mm_init.c (ffffffff81ad7c9d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/compaction.c (ffffffff8124c1ff)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
```
In mm/workingset.c (ffffffff828d8f93)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
  - mm/workingset.c:workingset_refault
```
```
In mm/memory.c (ffffffff812567af)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffff8125e645)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff8126ae3a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8126f719)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:vmalloc_nr_pages
```
```
In mm/page_alloc.c (ffffffff81271be6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:zone_batchsize
  - mm/page_alloc.c:build_zonerefs_node
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo_node
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__isolate_free_page
```
```
In mm/madvise.c (ffffffff81279acd)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/swap_state.c (ffffffff8127db2b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swapfile.c (ffffffff81283492)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swapfile.c:si_swapinfo
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/swap_slots.c (ffffffff81283f23)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff8128599c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff8128a665)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_report_usage
```
```
In mm/sparse.c (ffffffff81293dd5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/slub.c (ffffffff812a10f2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:get_slabinfo
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:store_user_store
  - mm/slub.c:poison_store
  - mm/slub.c:red_zone_store
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:list_locations
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:alloc_slab_page
```
```
In mm/huge_memory.c (ffffffff828ddf4a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In mm/page_counter.c (ffffffff812b5526)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff812b58bc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_exact_page_state
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_size
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff812bfd13)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/zsmalloc.c (ffffffff812c5337)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_zpool_total_size
```
```
In mm/memremap.c (ffffffff812ca7ef)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/open.c (ffffffff812cdad5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/open.c:filp_close
```
```
In fs/file_table.c (ffffffff828df8e4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/exec.c (ffffffff812dceb9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/namei.c (ffffffff812e1725)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/inode.c (ffffffff812f2c11)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:generic_update_time
  - fs/inode.c:__destroy_inode
```
```
In fs/attr.c (ffffffff812f51f7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/file.c (ffffffff812f6ba6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/file.c:__fdget_pos
  - fs/file.c:__fget
```
```
In fs/namespace.c (ffffffff812f99e5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/namespace.c:sb_prepare_remount_readonly
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs-writeback.c (ffffffff8130abc3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/sync.c (ffffffff8130f6d5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/nsfs.c (ffffffff81312d47)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/notify/fsnotify.c (ffffffff81322c7a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/eventpoll.c (ffffffff81329a8a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/userfaultfd.c (ffffffff813300ab)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff81330e5e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff8133b041)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_get_req
```
```
In fs/quota/dquot.c (ffffffff8135e86b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/proc/task_mmu.c (ffffffff81364f0d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/base.c (ffffffff81368b65)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/proc/array.c (ffffffff8136f4ba)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/meminfo.c (ffffffff813715b1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/ext4/balloc.c (ffffffff81383912)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/dir.c (ffffffff81385d7f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8139035d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:__ext4_ext_dirty
```
```
In fs/ext4/ialloc.c (ffffffff81395f88)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8139e03b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff813a5620)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/namei.c (ffffffff813c055d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/super.c (ffffffff813d3708)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/sysfs.c (ffffffff813ddee3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In fs/ext4/xattr.c (ffffffff813e0254)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/fat/dir.c (ffffffff813fa91a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff81402453)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff81403c58)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff81405f24)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/dir.c (ffffffff81418838)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/file.c (ffffffff8141bb37)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/fuse/inode.c (ffffffff828ea938)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
```
```
In fs/fuse/readdir.c (ffffffff81424f4b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/pstore/inode.c (ffffffff81428e4d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
```
```
In security/integrity/ima/ima_fs.c (ffffffff814a9cab)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
```
```
In security/integrity/ima/ima_main.c (ffffffff814aaeec)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In security/integrity/ima/ima_api.c (ffffffff814acd41)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/bio.c (ffffffff814d2a58)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In block/blk-core.c (ffffffff814db17a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-ioc.c (ffffffff814dea35)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In block/blk-mq.c (ffffffff814e3549)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq.c:blk_mq_freeze_queue_wait
```
```
In block/blk-mq-tag.c (ffffffff814e91de)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/genhd.c (ffffffff814edf5e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/genhd.c:part_in_flight_rw
  - block/genhd.c:part_in_flight_rw
```
```
In block/blk-cgroup.c (ffffffff814ff6f3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-iocost.c (ffffffff81505139)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:ioc_now
  - block/blk-iocost.c:ioc_refresh_params
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:trace_event_raw_event_iocost_ioc_vrate_adj
```
```
In block/blk-pm.c (ffffffff8151432f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In lib/percpu-refcount.c (ffffffff8151e9c5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff8152b5e0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_avail
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81654a80)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
```
In drivers/tty/tty_ldsem.c (ffffffff81682125)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
```
```
In drivers/char/agp/backend.c (ffffffff816b9560)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_add_bridge
```
```
In drivers/iommu/iova.c (ffffffff816d1470)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8175807f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_show_fdinfo
```
```
In drivers/usb/core/devio.c (ffffffff817ef5b3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff81885915)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/md.c:mismatch_cnt_show
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/dm.c (ffffffff8189cf51)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm.c:dm_wait_for_completion
```
```
In drivers/md/dm-stats.c (ffffffff818aa696)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
```
In drivers/firmware/efi/cper.c (ffffffff818e00e5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff8190435a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/core/skbuff.c (ffffffff8190a0d1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/core/dev.c (ffffffff8191b780)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
```
```
In net/core/sock_diag.c (ffffffff81951395)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff819a08e5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_init_start
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
```
```
In net/netfilter/nf_conntrack_standalone.c (ffffffff819a0d91)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_standalone.c:seq_print_acct
  - net/netfilter/nf_conntrack_standalone.c:seq_print_acct
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819ac128)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:dump_counters
  - net/netfilter/nf_conntrack_netlink.c:dump_counters
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819c45e5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c5210)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff819ccef0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff819cebbc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e8fd3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10f3b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/ipv4/proc.c (ffffffff81a18b08)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/proc.c:icmpmsg_put
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/unix/af_unix.c (ffffffff81a3abb1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81a3e6ed)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/unix/scm.c (ffffffff81a3ed1b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/addrconf.c (ffffffff81a4813b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/proc.c (ffffffff81a8a3dd)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:sockstat6_seq_show
```
```
In net/packet/af_packet.c (ffffffff81a98207)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81ab7d7b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/show_mem.c (ffffffff81ac1cc1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
  - lib/show_mem.c:show_mem
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
In arch/x86/events/core.c (ffffffff810078a5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009e5e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a9a4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100b394)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
```
In arch/x86/events/msr.c (ffffffff8100baf3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/bts.c (ffffffff8100f953)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fe0a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81014cd5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017f35)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81057a85)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
```
In arch/x86/kernel/pvclock.c (ffffffff8107a37b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In arch/x86/mm/tlb.c (ffffffff81089ea4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109a6ea)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_get_local64
```
```
In kernel/fork.c (ffffffff810a14b8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:get_mm_exe_file
  - kernel/fork.c:fork_init
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In kernel/exit.c (ffffffff810a7c4b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff810bed16)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/workqueue.c (ffffffff810c73a6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:pwq_activate_delayed_work
  - kernel/workqueue.c:get_work_pool
```
```
In kernel/sched/loadavg.c (ffffffff810e0caa)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
```
```
In kernel/sched/fair.c (ffffffff810e70e4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
```
```
In kernel/sched/debug.c (ffffffff810fe4d7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
```
```
In kernel/locking/mutex.c (ffffffff81ae9b78)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_wound
  - kernel/locking/mutex.c:mutex_trylock_recursive
  - kernel/locking/mutex.c:mutex_trylock_recursive
  - kernel/locking/mutex.c:mutex_is_locked
```
```
In kernel/locking/rwsem.c (ffffffff8110521b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/power/snapshot.c (ffffffff8110f11e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_image_size_init
```
```
In kernel/power/swap.c (ffffffff81110000)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81147111)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
  - kernel/time/posix-cpu-timers.c:thread_group_sample_cputime
```
```
In kernel/futex.c (ffffffff8114df8e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/acct.c (ffffffff8115c008)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/kexec_core.c (ffffffff8115ca8a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In kernel/cgroup/cgroup.c (ffffffff8116a4eb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116ce72)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116e149)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff8116e1f7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_current_read
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/cgroup/rdma.c (ffffffff8116f0bd)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81174ed5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/tsacct.c (ffffffff81199892)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In kernel/trace/ring_buffer.c (ffffffff811a5b24)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_iter_empty
  - kernel/trace/ring_buffer.c:ring_buffer_iter_empty
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/trace/tracing_map.c (ffffffff811b4690)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_cmp_atomic64
  - kernel/trace/tracing_map.c:tracing_map_cmp_atomic64
  - kernel/trace/tracing_map.c:tracing_map_read_var_once
  - kernel/trace/tracing_map.c:tracing_map_read_var
  - kernel/trace/tracing_map.c:tracing_map_read_sum
```
```
In kernel/trace/trace_events_hist.c (ffffffff811ccdae)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
```
```
In kernel/bpf/cgroup.c (ffffffff812091e7)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
```
```
In kernel/events/core.c (ffffffff8121be87)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_swevent_overflow
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:free_event
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_out
```
```
In kernel/events/ring_buffer.c (ffffffff8121cf8b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - kernel/events/ring_buffer.c:perf_output_put_handle
  - kernel/events/ring_buffer.c:perf_output_put_handle
```
```
In mm/oom_kill.c (ffffffff8122efb2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
```
```
In mm/page-writeback.c (ffffffff81233fbf)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:__wb_calc_thresh
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/swap.c (ffffffff828da937)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/vmscan.c (ffffffff8123ebf5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/shmem.c (ffffffff8124450d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_one
```
```
In mm/util.c (ffffffff8124b518)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:vm_commit_limit
```
```
In mm/vmstat.c (ffffffff8124dd5b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_numa_state
  - mm/vmstat.c:sum_zone_node_page_state
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/backing-dev.c (ffffffff8124ebb4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In mm/mm_init.c (ffffffff81ae415d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/compaction.c (ffffffff8125bb5f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
```
In mm/workingset.c (ffffffff828de3b4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
  - mm/workingset.c:workingset_refault
```
```
In mm/memory.c (ffffffff8126624f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffff8126e095)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff8127a7af)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8127f129)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:vmalloc_nr_pages
```
```
In mm/page_alloc.c (ffffffff81281646)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:zone_batchsize
  - mm/page_alloc.c:build_zonerefs_node
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo_node
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__isolate_free_page
```
```
In mm/madvise.c (ffffffff812896bd)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/swap_state.c (ffffffff8128d6db)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swapfile.c (ffffffff81293172)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swapfile.c:si_swapinfo
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/swap_slots.c (ffffffff81293c03)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff812956bc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff8129a455)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_report_usage
```
```
In mm/sparse.c (ffffffff812a3c35)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/slub.c (ffffffff812b12a2)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:get_slabinfo
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:store_user_store
  - mm/slub.c:poison_store
  - mm/slub.c:red_zone_store
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:list_locations
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:alloc_slab_page
```
```
In mm/huge_memory.c (ffffffff828e3361)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In mm/page_counter.c (ffffffff812c5a46)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff812c5ddc)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:__memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_exact_page_state
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_size
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff812d0753)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/zsmalloc.c (ffffffff812d5e12)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_zpool_total_size
```
```
In mm/memremap.c (ffffffff812db54f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/open.c (ffffffff812de8e5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/open.c:filp_close
```
```
In fs/file_table.c (ffffffff828e4cfb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/exec.c (ffffffff812edcaa)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/namei.c (ffffffff812f2675)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/inode.c (ffffffff81304321)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:generic_update_time
  - fs/inode.c:__destroy_inode
```
```
In fs/attr.c (ffffffff81306387)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/file.c (ffffffff81307df6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/file.c:__fdget_pos
  - fs/file.c:__fget
```
```
In fs/namespace.c (ffffffff8130ad05)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/namespace.c:sb_prepare_remount_readonly
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs-writeback.c (ffffffff8131c2f0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:__writeback_inodes_sb_nr
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/sync.c (ffffffff81320ed5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/nsfs.c (ffffffff8132457c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/notify/fsnotify.c (ffffffff813349b5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/eventpoll.c (ffffffff8133beb0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
```
In fs/userfaultfd.c (ffffffff81342a0b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff81343a59)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff8134e1f1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_get_req
```
```
In fs/quota/dquot.c (ffffffff8137370b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/proc/task_mmu.c (ffffffff81377f4a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/base.c (ffffffff8137c1e5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/proc/array.c (ffffffff81382e4a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/meminfo.c (ffffffff81384f91)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/ext4/balloc.c (ffffffff81397432)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/dir.c (ffffffff81399a6f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff813a41ed)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:__ext4_ext_dirty
```
```
In fs/ext4/ialloc.c (ffffffff813aa22c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/ext4/inline.c (ffffffff813b25ab)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff813b9d60)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/namei.c (ffffffff813d568d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/super.c (ffffffff813e4708)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/sysfs.c (ffffffff813f3303)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In fs/ext4/xattr.c (ffffffff813f5674)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/fat/dir.c (ffffffff8141057a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff81418423)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff814198c8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff8141bbe4)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_revalidate
```
```
In fs/fuse/dir.c (ffffffff8142f5a8)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/file.c (ffffffff81432aeb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In fs/fuse/inode.c (ffffffff828efd4e)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
```
```
In fs/fuse/readdir.c (ffffffff8143bde6)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/pstore/inode.c (ffffffff8143fd0d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
```
```
In security/integrity/ima/ima_fs.c (ffffffff814c26fb)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
```
```
In security/integrity/ima/ima_main.c (ffffffff814c392c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In security/integrity/ima/ima_api.c (ffffffff814c5791)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/bio.c (ffffffff814eb5c5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In block/blk-core.c (ffffffff814f3fb9)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-ioc.c (ffffffff814f78a5)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In block/blk-mq.c (ffffffff814fc46a)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq.c:blk_mq_freeze_queue_wait
```
```
In block/blk-mq-tag.c (ffffffff81502196)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/genhd.c (ffffffff81506fde)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/genhd.c:part_in_flight_rw
  - block/genhd.c:part_in_flight_rw
```
```
In block/blk-cgroup.c (ffffffff815188d1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-iocost.c (ffffffff8151e799)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:ioc_now
  - block/blk-iocost.c:ioc_refresh_params
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:trace_event_raw_event_iocost_ioc_vrate_adj
```
```
In block/blk-pm.c (ffffffff8152dabe)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In lib/percpu-refcount.c (ffffffff81538285)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff81545870)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_avail
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8166f450)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
```
In drivers/tty/tty_ldsem.c (ffffffff8169c765)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
```
```
In drivers/char/agp/backend.c (ffffffff816d3b30)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_add_bridge
```
```
In drivers/iommu/iova.c (ffffffff816ebd80)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8177355f)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_show_fdinfo
```
```
In drivers/usb/core/devio.c (ffffffff818097f3)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff818a1695)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/md.c:mismatch_cnt_show
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/dm.c (ffffffff818b92b1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm.c:dm_wait_for_completion
```
```
In drivers/md/dm-stats.c (ffffffff818c5eaf)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
```
In drivers/firmware/efi/cper.c (ffffffff818fcb85)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff819253da)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/core/skbuff.c (ffffffff8192b1d1)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/core/dev.c (ffffffff8193c980)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
```
```
In net/core/sock_diag.c (ffffffff81972d85)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ce185)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cece0)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff819d6a80)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff819d874c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f2d33)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b89b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
```
```
In net/ipv4/proc.c (ffffffff81a23588)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/proc.c:icmpmsg_put
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/unix/af_unix.c (ffffffff81a45e31)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81a4a1ad)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/unix/scm.c (ffffffff81a4a7db)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/addrconf.c (ffffffff81a5406c)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/proc.c (ffffffff81a9703d)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:sockstat6_seq_show
```
```
In net/packet/af_packet.c (ffffffff81aa4a77)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81ac419b)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/show_mem.c (ffffffff81ace191)
Location: arch/x86/include/asm/atomic64_64.h:20
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
  - lib/show_mem.c:show_mem
```
</details>
</li>
</ul>

## Differences
