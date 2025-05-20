# Function: <code>raw_atomic64_read</code>

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
In arch/x86/events/core.c (ffffffff81007714)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100ed40)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/ibs.c:perf_ibs_event_update
```
```
In arch/x86/events/msr.c (ffffffff81010173)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff81013ed5)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
```
```
In arch/x86/events/intel/bts.c (ffffffff810170f3)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff81017dc8)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff810214e4)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
```
```
In arch/x86/events/intel/uncore.c (ffffffff81024ee7)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In arch/x86/kernel/nmi.c (ffffffff81053786)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_backtrace_stall_check
  - arch/x86/kernel/nmi.c:nmi_backtrace_stall_snap
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81097408)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read_nowd
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In arch/x86/mm/tlb.c (ffffffff810cc3c0)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_func
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e7e8a)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_get_local64
```
```
In kernel/fork.c (ffffffff810f22fe)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
  - kernel/fork.c:fork_init
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In kernel/workqueue.c (ffffffff8111e03c)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - kernel/ucount.c:is_rlimit_overlimit
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/fair.c (ffffffff8115a6b5)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_cfs_group
```
```
In kernel/sched/build_utility.c (ffffffff81187d72)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:io_tlb_hiwater_get
  - kernel/dma/swiotlb.c:io_tlb_used_get
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/dma/swiotlb.c:swiotlb_do_find_slots
```
```
In kernel/dma/pool.c (ffffffff836d29a8)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_atomic_pool_init
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811ff1c3)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/acct.c (ffffffff81212a4f)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/kexec_core.c (ffffffff8121428a)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In kernel/cgroup/cgroup.c (ffffffff81226817)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8122b6ae)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff8122b866)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_current_read
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/cgroup/rdma.c (ffffffff8122cca0)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81235149)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_events_show
  - kernel/cgroup/misc.c:misc_cg_current_show
  - kernel/cgroup/misc.c:misc_cg_res_total_usage
```
```
In kernel/trace/ring_buffer.c (ffffffff81278495)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - kernel/trace/trace.c:latency_fsnotify_workfn
```
```
In kernel/trace/tracing_map.c (ffffffff8128efe0)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
```
```
In kernel/bpf/syscall.c (ffffffff812eba05)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_ancestor
  - kernel/bpf/helpers.c:bpf_cgroup_acquire
  - kernel/bpf/helpers.c:bpf_timer_set_callback
  - kernel/bpf/helpers.c:bpf_timer_init
```
```
In kernel/bpf/task_iter.c (ffffffff81325606)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In kernel/bpf/memalloc.c (ffffffff8134c567)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8135d19a)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_sys_lookup_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_sys_lookup_elem
```
```
In kernel/events/core.c (ffffffff813725dd)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/vmscan.c (ffffffff813ba525)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
```
```
In mm/vmstat.c (ffffffff813c9775)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/mm_init.c (ffffffff836e317e)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - mm/mm_init.c:mm_core_init
  - mm/mm_init.c:mm_core_init
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mm_init.c:mm_compute_batch_notifier
```
```
In mm/compaction.c (ffffffff813dd31c)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
```
In mm/show_mem.c (ffffffff813debdb)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_eviction
```
```
In mm/mmap.c (ffffffff813fae95)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
```
```
In mm/vmalloc.c (ffffffff81417983)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cache_get_folio
  - mm/swap_state.c:show_swap_cache_info
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swapfile.c (ffffffff81433a1b)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/zswap.c (ffffffff81436bfa)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:shrink_worker
```
```
In mm/hugetlb.c (ffffffff8143faf5)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_report_usage
```
```
In mm/slub.c (ffffffff81463b93)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - mm/kfence/core.c:__kfence_alloc
  - mm/kfence/core.c:stats_show
```
```
In mm/migrate.c (ffffffff81468b04)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
```
```
In mm/huge_memory.c (ffffffff81478227)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:hugepage_init
```
```
In mm/page_counter.c (ffffffff81482b79)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_zpool_total_size
```
```
In mm/memremap.c (ffffffff814a40a5)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/open.c (ffffffff814a7e75)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/open.c:filp_close
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff814b089a)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:files_maxfiles_init
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/namei.c (ffffffff814c43d7)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/dcache.c (ffffffff814d2266)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff814d7777)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/attr.c (ffffffff814daae1)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
```
```
In fs/file.c (ffffffff814dd386)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/namespace.c:sb_prepare_remount_readonly
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/xattr.c (ffffffff814ea3d8)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/libfs.c (ffffffff814eca15)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/libfs.c:inode_query_iversion
  - fs/libfs.c:inode_maybe_inc_iversion
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/fs-writeback.c (ffffffff814f8414)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
```
```
In fs/nsfs.c (ffffffff81502c54)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/remap_range.c (ffffffff815073c9)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
```
```
In fs/notify/fsnotify.c (ffffffff815131b2)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/aio.c (ffffffff81527a86)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/posix_acl.c (ffffffff8154da17)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
```
```
In fs/quota/dquot.c (ffffffff8155bd6a)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/proc/task_mmu.c (ffffffff815684ab)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/base.c (ffffffff8156aaa5)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/proc/array.c (ffffffff815747c0)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/meminfo.c (ffffffff81576790)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
```
```
In fs/configfs/dir.c (ffffffff8158b8a2)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff8158e6dc)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/ext4/balloc.c (ffffffff8158e83b)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/dir.c (ffffffff81591535)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8159ca9c)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/ialloc.c (ffffffff815a56ac)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
```
```
In fs/ext4/inline.c (ffffffff815aea0c)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff815b2dde)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/sysfs.c (ffffffff81604ca4)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In fs/ext4/xattr.c (ffffffff8160651d)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/ext4/orphan.c (ffffffff816102c7)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/fat/file.c (ffffffff8163884e)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/fat/namei_vfat.c (ffffffff8163df0f)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_revalidate
```
```
In fs/fuse/dir.c (ffffffff8165736c)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff8165d02d)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/inode.c (ffffffff836f3cd4)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:set_global_limit
  - fs/fuse/inode.c:fuse_ilookup
```
```
In fs/fuse/readdir.c (ffffffff8166781b)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/debugfs/inode.c (ffffffff8166c08f)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In fs/pstore/inode.c (ffffffff81670a80)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
```
```
In security/security.c (ffffffff8169d62c)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
```
```
In security/landlock/fs.c (ffffffff8172b038)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff8172ee31)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
```
```
In security/integrity/ima/ima_kexec.c (ffffffff8173b048)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - security/integrity/ima/ima_kexec.c:ima_add_kexec_buffer
```
```
In crypto/aead.c (ffffffff817419db)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
```
```
In crypto/shash.c (ffffffff8174605b)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
```
```
In crypto/akcipher.c (ffffffff8174716b)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_kpp_report_stat
  - crypto/kpp.c:crypto_kpp_report_stat
  - crypto/kpp.c:crypto_kpp_report_stat
  - crypto/kpp.c:crypto_kpp_report_stat
```
```
In crypto/acompress.c (ffffffff8174b06b)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_report_stat
  - crypto/rng.c:crypto_rng_report_stat
  - crypto/rng.c:crypto_rng_report_stat
  - crypto/rng.c:crypto_rng_report_stat
```
```
In block/blk-core.c (ffffffff81772ad9)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-ioc.c (ffffffff817770c8)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:ioc_find_get_icq
```
```
In block/blk-mq.c (ffffffff8177f9d8)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - block/blk-mq.c:blk_rq_poll
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_get_new_requests
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff817885e2)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/genhd.c (ffffffff8178d3a6)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - block/genhd.c:part_inflight_show
  - block/genhd.c:part_inflight_show
  - block/genhd.c:part_in_flight
  - block/genhd.c:part_in_flight
```
```
In block/blk-cgroup.c (ffffffff817a29f4)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
```
```
In block/blk-iocost.c (ffffffff817af41a)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - io_uring/sync.c:io_fallocate
```
```
In io_uring/fdinfo.c (ffffffff817dcaa4)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - io_uring/fdinfo.c:io_uring_show_fdinfo
```
```
In io_uring/rsrc.c (ffffffff817e1ac1)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_account_mem
```
```
In io_uring/rw.c (ffffffff817e4a5f)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
```
```
In lib/percpu-refcount.c (ffffffff818181e2)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_avail
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/pci/p2pdma.c (ffffffff8195fcb8)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_alloc_p2pmem
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5ed14)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
```
In drivers/xen/grant-table.c (ffffffff81a63728)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/tty/tty_ldsem.c (ffffffff81aa10d5)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
```
```
In drivers/char/agp/backend.c (ffffffff81ae8345)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_initialize
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b1a91b)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_event_update
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b23b0c)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:fq_ring_free
```
```
In drivers/base/memory.c (ffffffff81b65ad0)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:memory_block_online
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81bbc492)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_show_fdinfo
```
```
In drivers/spi/spi.c (ffffffff81c29b5c)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_emit_pcpu_stats
```
```
In drivers/net/loopback.c (ffffffff81c31573)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - drivers/net/loopback.c:dev_lstats_read
  - drivers/net/loopback.c:dev_lstats_read
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81c3d147)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdio_bus_device_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
```
```
In drivers/net/tun.c (ffffffff81c43707)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_get_stats64
```
```
In drivers/md/md.c (ffffffff81d57c19)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - drivers/md/md.c:mismatch_cnt_show
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm-stats.c (ffffffff81d85972)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:__check_shared_memory
```
```
In drivers/firmware/efi/cper.c (ffffffff81dcf715)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff81e07f71)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - net/core/sock.c:proto_seq_printf
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_setsockopt
```
```
In net/core/skbuff.c (ffffffff81e1573c)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_account_pinned_pages
```
```
In net/core/gen_stats.c (ffffffff81e22475)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff81e2322c)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff81e30f3f)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
```
```
In net/core/xdp.c (ffffffff81e7979a)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/net-sysfs.c (ffffffff81e7e0a9)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_timeout_show
```
```
In net/core/page_pool.c (ffffffff81e8398d)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_return_skb_page
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
```
```
In net/core/drop_monitor.c (ffffffff81e9b474)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
```
```
In net/ipv4/inetpeer.c (ffffffff837349d5)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_initpeers
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f0415f)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f0564d)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81f0f997)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff81f169a4)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f3564b)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_net_metrics_init
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6a9d9)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/nexthop.c (ffffffff81f74aa1)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nh_res_table_upkeep
```
```
In net/ipv4/proc.c (ffffffff81f78d62)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81fb0400)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/unix/scm.c (ffffffff81fb13bb)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/addrconf.c (ffffffff81fbd708)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/proc.c (ffffffff8201582e)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_seq_show_item
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:sockstat6_seq_show
```
```
In net/ipv6/seg6_local.c (ffffffff8201c4fd)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/packet/af_packet.c (ffffffff8202a864)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/devlink/leftover.c (ffffffff8203bf29)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/mptcp/protocol.c (ffffffff82073309)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
```
In net/mptcp/subflow.c (ffffffff8207c40b)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
```
```
In net/mptcp/options.c (ffffffff8207f3e5)
Location: include/linux/atomic/atomic-arch-fallback.h:2558
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/ibs.c (ffffffff81014480)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/ibs.c:perf_ibs_event_update
```
```
In arch/x86/events/msr.c (ffffffff81015915)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff81019515)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
```
```
In arch/x86/events/intel/bts.c (ffffffff8101cc33)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff8101d938)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff81027e64)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
```
```
In arch/x86/events/intel/uncore.c (ffffffff8102b047)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In arch/x86/kernel/nmi.c (ffffffff8105a9a6)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_backtrace_stall_check
  - arch/x86/kernel/nmi.c:nmi_backtrace_stall_snap
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109e978)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read_nowd
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In arch/x86/mm/tlb.c (ffffffff810d4a50)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_func
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f021a)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_get_local64
```
```
In kernel/fork.c (ffffffff838f9c66)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In kernel/workqueue.c (ffffffff81127d6c)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - kernel/ucount.c:is_rlimit_overlimit
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/fair.c (ffffffff8116c01d)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_cfs_group
```
```
In kernel/sched/build_utility.c (ffffffff81196522)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - kernel/printk/nbcon.c:nbcon_seq_read
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff811b5571)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/rcu/update.c:call_rcu_tasks_generic
```
```
In kernel/rcu/srcutree.c (ffffffff811cf9b0)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
```
```
In kernel/dma/swiotlb.c (ffffffff811eb735)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:io_tlb_hiwater_get
  - kernel/dma/swiotlb.c:io_tlb_used_get
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/dma/swiotlb.c:swiotlb_search_pool_area
```
```
In kernel/dma/pool.c (ffffffff83904768)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_atomic_pool_init
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8121558a)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/acct.c (ffffffff8122a0ef)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/kexec_core.c (ffffffff8122c1da)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In kernel/cgroup/cgroup.c (ffffffff8123e4a7)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:task_get_cgroup1
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8124369e)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff81243866)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_current_read
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/cgroup/rdma.c (ffffffff81244d60)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8124ed98)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_events_show
  - kernel/cgroup/misc.c:misc_cg_current_show
  - kernel/cgroup/misc.c:misc_cg_res_total_usage
```
```
In kernel/trace/ring_buffer.c (ffffffff81292fa6)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - kernel/trace/trace.c:latency_fsnotify_workfn
```
```
In kernel/trace/tracing_map.c (ffffffff812aa540)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:hist_show
```
```
In kernel/bpf/syscall.c (ffffffff81309f55)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_ancestor
  - kernel/bpf/helpers.c:bpf_cgroup_acquire
  - kernel/bpf/helpers.c:bpf_timer_set_callback
  - kernel/bpf/helpers.c:bpf_timer_init
```
```
In kernel/bpf/map_in_map.c (ffffffff813553c3)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr
```
```
In kernel/bpf/mprog.c (ffffffff8135c8e2)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - kernel/bpf/mprog.c:bpf_mprog_query
  - kernel/bpf/mprog.c:bpf_mprog_detach
  - kernel/bpf/mprog.c:bpf_mprog_attach
```
```
In kernel/bpf/memalloc.c (ffffffff81371ec3)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff813858aa)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_sys_lookup_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_sys_lookup_elem
```
```
In kernel/events/core.c (ffffffff8139b94d)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/vmscan.c (ffffffff813e3645)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - mm/shrinker.c:reparent_shrinker_deferred
```
```
In mm/shmem.c (ffffffff813e72f8)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
```
```
In mm/vmstat.c (ffffffff813f4105)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/mm_init.c (ffffffff83915a0e)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - mm/mm_init.c:mm_core_init
  - mm/mm_init.c:mm_core_init
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mm_init.c:mm_compute_batch_notifier
```
```
In mm/compaction.c (ffffffff8140727c)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
```
In mm/show_mem.c (ffffffff81408aab)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_eviction
```
```
In mm/mmap.c (ffffffff81426ae5)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
```
```
In mm/vmalloc.c (ffffffff814444d3)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cache_get_folio
  - mm/swap_state.c:show_swap_cache_info
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swapfile.c (ffffffff8146ce0b)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/zswap.c (ffffffff81470745)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_report_usage
```
```
In mm/kfence/core.c (ffffffff81494c6b)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - mm/kfence/core.c:__kfence_alloc
  - mm/kfence/core.c:stats_show
```
```
In mm/migrate.c (ffffffff8149ac3b)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:migrate_misplaced_folio
```
```
In mm/huge_memory.c (ffffffff814a7967)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:hugepage_init
```
```
In mm/page_counter.c (ffffffff814b1ef9)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_zpool_total_size
```
```
In mm/memremap.c (ffffffff814d4f52)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/open.c (ffffffff814d8a15)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/open.c:filp_flush
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff814e203d)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:files_maxfiles_init
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/namei.c (ffffffff814f635f)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
  - fs/readdir.c:iterate_dir
```
```
In fs/dcache.c (ffffffff81504ca6)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff81509cdd)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/inode.c:inode_needs_update_time
  - fs/inode.c:__destroy_inode
```
```
In fs/attr.c (ffffffff8150d081)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
```
```
In fs/file.c (ffffffff8150ede0)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/namespace.c:sb_prepare_remount_readonly
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/xattr.c (ffffffff8151e278)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/libfs.c (ffffffff81520965)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/libfs.c:inode_query_iversion
  - fs/libfs.c:inode_maybe_inc_iversion
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/fs-writeback.c (ffffffff8152cb94)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
```
```
In fs/nsfs.c (ffffffff815378a2)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/remap_range.c (ffffffff8153c878)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/notify/fsnotify.c (ffffffff81547662)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/userfaultfd.c (ffffffff8155b83e)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff8155c816)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/posix_acl.c (ffffffff81583847)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
```
```
In fs/quota/dquot.c (ffffffff815924ea)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/proc/task_mmu.c (ffffffff815a0acb)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/base.c (ffffffff815a3485)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/proc/array.c (ffffffff815ad190)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/meminfo.c (ffffffff815af0e0)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
```
```
In fs/configfs/dir.c (ffffffff815c45d8)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff815c73ef)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/ext4/balloc.c (ffffffff815c754b)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/dir.c (ffffffff815ca275)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff815d574c)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/ialloc.c (ffffffff815de51c)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
```
```
In fs/ext4/inline.c (ffffffff815e77cc)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff815ebbd4)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/sysfs.c (ffffffff8163d964)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In fs/ext4/xattr.c (ffffffff8163f25d)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/ext4/orphan.c (ffffffff81649087)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/fat/file.c (ffffffff81671d3e)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/fat/namei_vfat.c (ffffffff8167747f)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_revalidate
```
```
In fs/fuse/dir.c (ffffffff81690fbc)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_statx
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff81696d8a)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/inode.c (ffffffff83926ea4)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:set_global_limit
  - fs/fuse/inode.c:fuse_ilookup
```
```
In fs/fuse/readdir.c (ffffffff816a1b75)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/debugfs/inode.c (ffffffff816a652f)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In fs/tracefs/event_inode.c (ffffffff816abf3f)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/tracefs/event_inode.c:eventfs_create_events_dir
```
```
In fs/pstore/inode.c (ffffffff816ac96c)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
```
```
In security/security.c (ffffffff816dcaf8)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - security/security.c:security_file_open
  - security/security.c:security_file_open
```
```
In security/landlock/fs.c (ffffffff8176cb58)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff8176f791)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
```
```
In security/integrity/ima/ima_main.c (ffffffff8177121c)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_kexec.c (ffffffff8177bbb8)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - security/integrity/ima/ima_kexec.c:ima_add_kexec_buffer
```
```
In crypto/aead.c (ffffffff8178287b)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
```
```
In crypto/shash.c (ffffffff8178869b)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
```
```
In crypto/akcipher.c (ffffffff81788fdb)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_kpp_report_stat
  - crypto/kpp.c:crypto_kpp_report_stat
  - crypto/kpp.c:crypto_kpp_report_stat
  - crypto/kpp.c:crypto_kpp_report_stat
```
```
In crypto/acompress.c (ffffffff8178cf3b)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_report_stat
  - crypto/rng.c:crypto_rng_report_stat
  - crypto/rng.c:crypto_rng_report_stat
  - crypto/rng.c:crypto_rng_report_stat
```
```
In block/blk-core.c (ffffffff817b4e73)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-ioc.c (ffffffff817b92f8)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:ioc_find_get_icq
```
```
In block/blk-mq.c (ffffffff817c24b8)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - block/blk-mq.c:blk_rq_poll
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff817cacb2)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/genhd.c (ffffffff817cfc06)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - block/genhd.c:part_inflight_show
  - block/genhd.c:part_inflight_show
  - block/genhd.c:part_in_flight
  - block/genhd.c:part_in_flight
```
```
In block/blk-cgroup.c (ffffffff817e6537)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
```
```
In block/blk-iocost.c (ffffffff817f322d)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - io_uring/sync.c:io_fallocate
```
```
In io_uring/rsrc.c (ffffffff81825e81)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_account_mem
```
```
In io_uring/rw.c (ffffffff81828f05)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
```
```
In lib/percpu-refcount.c (ffffffff8185d4e2)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_avail
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/pci/p2pdma.c (ffffffff819a9378)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_alloc_p2pmem
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab1474)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
```
In drivers/xen/grant-table.c (ffffffff81ab5f77)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/tty/tty_ldsem.c (ffffffff81af3b35)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
```
```
In drivers/char/agp/backend.c (ffffffff81b3b7b5)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_initialize
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b7044b)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_event_update
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b7959a)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:queue_iova
  - drivers/iommu/dma-iommu.c:fq_ring_free_locked
```
```
In drivers/base/memory.c (ffffffff81bb9950)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:memory_block_online
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81c10c92)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_show_fdinfo
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb3e78)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_count_and_time
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_count
  - drivers/gpu/drm/drm_vblank.c:drm_update_vblank_count
```
```
In drivers/gpu/drm/drm_vblank_work.c (ffffffff81cb7bb5)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank_work.c:drm_handle_vblank_works
```
```
In drivers/spi/spi.c (ffffffff81cdc3ac)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_emit_pcpu_stats
```
```
In drivers/net/loopback.c (ffffffff81ce43f3)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - drivers/net/loopback.c:dev_lstats_read
  - drivers/net/loopback.c:dev_lstats_read
```
```
In drivers/net/netkit.c (ffffffff81ce49f1)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_get_stats
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81cf24f7)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdio_bus_device_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
```
```
In drivers/net/tun.c (ffffffff81cf9017)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_get_stats64
```
```
In drivers/net/virtio_net.c (ffffffff81d01353)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - drivers/md/md.c:mismatch_cnt_show
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm-stats.c (ffffffff81e3d0b2)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:__check_shared_memory
```
```
In drivers/firmware/efi/cper.c (ffffffff81e88445)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff81ec49b1)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - net/core/sock.c:proto_seq_printf
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_setsockopt
```
```
In net/core/skbuff.c (ffffffff81ed2adc)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_account_pinned_pages
  - net/core/skbuff.c:napi_pp_put_page
```
```
In net/core/gen_stats.c (ffffffff81ee03b5)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff81ee119a)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff81eef63f)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
```
```
In net/core/xdp.c (ffffffff81f39784)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/net-sysfs.c (ffffffff81f3efb9)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_timeout_show
```
```
In net/core/page_pool.c (ffffffff81f447fd)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
```
```
In net/core/drop_monitor.c (ffffffff81f5dbe4)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
```
```
In net/ipv4/inetpeer.c (ffffffff83968f95)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_initpeers
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8497)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fc99b3)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81fd3b87)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff81fdb814)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
```
In net/ipv4/tcp_metrics.c (ffffffff83969917)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
```
```
In net/ipv4/inet_fragment.c (ffffffff82031089)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/nexthop.c (ffffffff8203b241)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nh_res_table_upkeep
```
```
In net/ipv4/proc.c (ffffffff8203f422)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff8207da60)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/unix/scm.c (ffffffff8207eadb)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/addrconf.c (ffffffff8208ab50)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/proc.c (ffffffff820e496e)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_seq_show_item
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:sockstat6_seq_show
```
```
In net/ipv6/seg6_local.c (ffffffff820eb4cd)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/packet/af_packet.c (ffffffff820f7f21)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/mptcp/protocol.c (ffffffff82147559)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
```
In net/mptcp/subflow.c (ffffffff821518f2)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
```
```
In net/mptcp/options.c (ffffffff821548d5)
Location: include/linux/atomic/atomic-arch-fallback.h:2567
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
