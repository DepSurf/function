# Function: <code>arch_atomic_long_read</code>

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
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008bf5)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100bafc)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/ibs.c:perf_ibs_event_update
```
```
In arch/x86/events/msr.c (ffffffff8100ca73)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100f775)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
```
```
In arch/x86/events/intel/bts.c (ffffffff81011e7e)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff8101272e)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff8101ab34)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101dc23)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810642a4)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81073612)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810aaeda)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_get_local64
```
```
In kernel/fork.c (ffffffff810b4e9c)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:fork_init
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In kernel/exit.c (ffffffff810bc3e4)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff810d4126)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/workqueue.c (ffffffff81ca4f25)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - kernel/ucount.c:is_ucounts_overlimit
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/loadavg.c (ffffffff810fe36a)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
```
```
In kernel/sched/fair.c (ffffffff81107242)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_cfs_group
```
```
In kernel/sched/debug.c (ffffffff81126016)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
```
```
In kernel/locking/mutex.c (ffffffff81d53b42)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
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
In kernel/printk/printk_ringbuffer.c (ffffffff8113cd2e)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_atomic_pool_init
```
```
In kernel/kexec_core.c (ffffffff8118d9da)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In kernel/cgroup/misc.c (ffffffff811a8b42)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_current_show
  - kernel/cgroup/misc.c:misc_cg_res_total_usage
```
```
In kernel/tsacct.c (ffffffff811d2e03)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - kernel/trace/trace.c:latency_fsnotify_workfn
```
```
In kernel/bpf/syscall.c (ffffffff8122d14b)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/syscall.c:bpf_prog_get_stats
```
```
In kernel/events/core.c (ffffffff81284c9d)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:free_event
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:__perf_remove_from_context
```
```
In kernel/events/ring_buffer.c (ffffffff8128e115)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/vmscan.c (ffffffff812b8755)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
```
```
In mm/vmstat.c (ffffffff812c50a0)
Location: include/linux/atomic/atomic-long.h:27
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
In mm/mm_init.c (ffffffff812c7413)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/compaction.c (ffffffff812d4407)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
```
In mm/workingset.c (ffffffff832d77a3)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/memory.c (ffffffff812e16bb)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:vmalloc_nr_pages
```
```
In mm/page_alloc.c (ffffffff813010b6)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/swap_state.c (ffffffff81310bc5)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:show_swap_cache_info
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swapfile.c (ffffffff81317b1b)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/swapfile.c:si_swapinfo
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/swap_slots.c (ffffffff813185a6)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff8131a906)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff81320c45)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_report_usage
```
```
In mm/sparse.c (ffffffff8132bc83)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/slub.c (ffffffff8133b917)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/kfence/core.c:stats_show
```
```
In mm/huge_memory.c (ffffffff832dd411)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In mm/page_counter.c (ffffffff81350826)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
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
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff8135ccd4)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/zsmalloc.c (ffffffff813634ef)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_zpool_total_size
```
```
In fs/open.c (ffffffff8136d045)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/open.c:filp_close
  - fs/open.c:do_sys_openat2
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff813740ac)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:files_maxfiles_init
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/exec.c (ffffffff8137c811)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/dcache.c (ffffffff81390dca)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff81394c6f)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/attr.c (ffffffff81397992)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
```
```
In fs/file.c (ffffffff813998e6)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/file.c:__fdget_pos
```
```
In fs/namespace.c (ffffffff8139dfc5)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/namespace.c:sb_prepare_remount_readonly
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/xattr.c (ffffffff813a4b0d)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/libfs.c (ffffffff813a7717)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/fs-writeback.c (ffffffff813b03b4)
Location: include/linux/atomic/atomic-long.h:27
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
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
```
In fs/nsfs.c (ffffffff813b872f)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/remap_range.c (ffffffff813bbbbe)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
```
```
In fs/notify/fsnotify.c (ffffffff813c6f1c)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/io_uring.c (ffffffff813df751)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/io_uring.c:io_buffer_account_pin
  - fs/io_uring.c:io_openat2
```
```
In fs/fhandle.c (ffffffff81410f88)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/quota/dquot.c (ffffffff814193bc)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/proc/task_mmu.c (ffffffff81421004)
Location: include/linux/atomic/atomic-long.h:27
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
In fs/proc/base.c (ffffffff81424eb5)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/proc/array.c (ffffffff8142cb0b)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/meminfo.c (ffffffff8142ee3f)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
```
```
In fs/configfs/dir.c (ffffffff8143fa85)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff81442c9f)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/ext4/extents.c (ffffffff8144f81d)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff8145ef1e)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff81469556)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/xattr.c (ffffffff814a8c90)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
```
In fs/ext4/orphan.c (ffffffff814b16bd)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/fat/file.c (ffffffff814d1ae2)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/fuse/dir.c (ffffffff814ecdd0)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_set_nowrite
```
```
In fs/fuse/inode.c (ffffffff814f515c)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/fuse/inode.c:set_global_limit
  - fs/fuse/inode.c:fuse_ilookup
```
```
In fs/debugfs/inode.c (ffffffff814fd0b3)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff814ff2de)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In fs/pstore/inode.c (ffffffff814fff07)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
```
```
In security/security.c (ffffffff815256b3)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
```
```
In security/landlock/fs.c (ffffffff815976ff)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff8159888b)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
```
```
In block/blk-ioc.c (ffffffff815d21ce)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
```
```
In block/genhd.c (ffffffff815e34bc)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - block/genhd.c:part_inflight_show
  - block/genhd.c:part_inflight_show
  - block/genhd.c:part_in_flight
  - block/genhd.c:part_in_flight
```
```
In block/blk-iocost.c (ffffffff815ff04c)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
```
```
In block/mq-deadline.c (ffffffff8160058b)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_avail
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In lib/show_mem.c (ffffffff81cdfab3)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
  - lib/show_mem.c:show_mem
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8178d260)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
```
In drivers/tty/tty_ldsem.c (ffffffff817c0b55)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
```
```
In drivers/char/agp/backend.c (ffffffff817fd1c5)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_initialize
```
```
In drivers/dma-buf/dma-buf.c (ffffffff818a3ccf)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_show_fdinfo
```
```
In drivers/net/loopback.c (ffffffff818ffcff)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - drivers/net/loopback.c:dev_lstats_read
  - drivers/net/loopback.c:dev_lstats_read
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81907cf5)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdio_bus_device_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
```
```
In drivers/net/tun.c (ffffffff8190c367)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_get_stats64
```
```
In drivers/md/dm.c (ffffffff81a0815d)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
```
```
In drivers/md/dm-stats.c (ffffffff81a15c82)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:__check_shared_memory
```
```
In net/core/sock.c (ffffffff81a7a790)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/core/sock.c:proto_seq_printf
  - net/core/sock.c:__sk_mem_reduce_allocated
```
```
In net/core/skbuff.c (ffffffff81a82bbc)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
```
```
In net/core/dev.c (ffffffff81a95720)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
```
```
In net/core/page_pool.c (ffffffff81ad86ca)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
```
```
In net/ipv4/inetpeer.c (ffffffff83311dd0)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_initpeers
```
```
In net/ipv4/tcp.c (ffffffff81b5f5f5)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff81b651f1)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b805f8)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81baefcd)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81bb7844)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nh_res_table_upkeep
```
```
In net/ipv4/proc.c (ffffffff81bbb3f2)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81beb0ec)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/unix/scm.c (ffffffff81bebc7b)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/addrconf.c (ffffffff81bf6500)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/proc.c (ffffffff81c43ff8)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_dev_seq_show
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:sockstat6_seq_show
```
```
In net/ipv6/seg6_local.c (ffffffff81c48502)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/packet/af_packet.c (ffffffff81c507b4)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81c750c3)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100c71b)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/ibs.c:perf_ibs_event_update
```
```
In arch/x86/events/msr.c (ffffffff8100d873)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff81010cc5)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
```
```
In arch/x86/events/intel/bts.c (ffffffff810136b3)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff81014328)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff8101d384)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
```
```
In arch/x86/events/intel/uncore.c (ffffffff810206ab)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81081a58)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810c092a)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_get_local64
```
```
In kernel/fork.c (ffffffff810c9c39)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:fork_init
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In kernel/exit.c (ffffffff810d2ed3)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff810ece06)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/workqueue.c (ffffffff81e547f2)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - kernel/ucount.c:is_ucounts_overlimit
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/fair.c (ffffffff81124455)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_cfs_group
```
```
In kernel/sched/build_utility.c (ffffffff81148902)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
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
In kernel/printk/printk_ringbuffer.c (ffffffff81160c91)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_atomic_pool_init
```
```
In kernel/kexec_core.c (ffffffff811bceca)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In kernel/cgroup/misc.c (ffffffff811d9d42)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_events_show
  - kernel/cgroup/misc.c:misc_cg_current_show
  - kernel/cgroup/misc.c:misc_cg_res_total_usage
```
```
In kernel/tsacct.c (ffffffff812077c3)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - kernel/trace/trace.c:latency_fsnotify_workfn
```
```
In kernel/bpf/syscall.c (ffffffff8126f5ab)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/syscall.c:bpf_prog_get_stats
```
```
In kernel/events/core.c (ffffffff812d91ad)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:free_event
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:__perf_remove_from_context
```
```
In kernel/events/ring_buffer.c (ffffffff812e2d6c)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/vmscan.c (ffffffff81314185)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
```
```
In mm/vmstat.c (ffffffff81322620)
Location: include/linux/atomic/atomic-long.h:27
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
In mm/mm_init.c (ffffffff81324763)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/compaction.c (ffffffff81333370)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
```
In mm/workingset.c (ffffffff8348c342)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/memory.c (ffffffff81342221)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/swap_state.c (ffffffff8137b989)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:show_swap_cache_info
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swapfile.c (ffffffff8138318b)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/swapfile.c:si_swapinfo
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/swap_slots.c (ffffffff81383c66)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/zswap.c (ffffffff81385f6b)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff8138d925)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_report_usage
```
```
In mm/slub.c (ffffffff813ae047)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/kfence/core.c:__kfence_alloc
  - mm/kfence/core.c:stats_show
```
```
In mm/migrate.c (ffffffff813b2d86)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
```
```
In mm/huge_memory.c (ffffffff83492c3f)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In mm/page_counter.c (ffffffff813c8b86)
Location: include/linux/atomic/atomic-long.h:27
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
In mm/memcontrol.c (ffffffff813c908c)
Location: include/linux/atomic/atomic-long.h:27
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
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff813d69b4)
Location: include/linux/atomic/atomic-long.h:27
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
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff813dd745)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/memory-failure.c:clear_hwpoisoned_pages
```
```
In mm/zsmalloc.c (ffffffff813dfc15)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_zpool_total_size
```
```
In fs/open.c (ffffffff813eb3a5)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/open.c:filp_close
  - fs/open.c:do_sys_openat2
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff813f2ec9)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:files_maxfiles_init
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/exec.c (ffffffff813fa8b2)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/dcache.c (ffffffff81412066)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff81417017)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/attr.c (ffffffff81419a12)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
```
```
In fs/file.c (ffffffff8141c2ba)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/file.c:__fdget_pos
```
```
In fs/namespace.c (ffffffff81421105)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/namespace.c:sb_prepare_remount_readonly
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/xattr.c (ffffffff81428668)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/libfs.c (ffffffff8142c306)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/fs-writeback.c (ffffffff81434ff4)
Location: include/linux/atomic/atomic-long.h:27
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
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
```
```
In fs/nsfs.c (ffffffff8143e004)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/remap_range.c (ffffffff8144245e)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
```
```
In fs/notify/fsnotify.c (ffffffff8144e272)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/fhandle.c (ffffffff81486967)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/quota/dquot.c (ffffffff8148fe5b)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/proc/task_mmu.c (ffffffff81498e9a)
Location: include/linux/atomic/atomic-long.h:27
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
In fs/proc/base.c (ffffffff8149dc25)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/proc/array.c (ffffffff814a63df)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/meminfo.c (ffffffff814a8a50)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
```
```
In fs/configfs/dir.c (ffffffff814bbfe7)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff814bea5c)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/ext4/extents.c (ffffffff814cc6e4)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff814dd6a7)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff814e9336)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/xattr.c (ffffffff8153023a)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
```
In fs/ext4/orphan.c (ffffffff8153a1c3)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/fat/file.c (ffffffff8155e765)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/fuse/dir.c (ffffffff8157bb90)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
```
```
In fs/fuse/inode.c (ffffffff815850a6)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/fuse/inode.c:set_global_limit
  - fs/fuse/inode.c:fuse_ilookup
```
```
In fs/debugfs/inode.c (ffffffff8158d266)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In fs/pstore/inode.c (ffffffff815910a0)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
```
```
In security/security.c (ffffffff815b9844)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
```
```
In security/landlock/fs.c (ffffffff81639528)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff8163d241)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
```
```
In block/blk-ioc.c (ffffffff8167dd78)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:ioc_find_get_icq
```
```
In block/genhd.c (ffffffff81692748)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - block/genhd.c:part_inflight_show
  - block/genhd.c:part_inflight_show
  - block/genhd.c:part_in_flight
  - block/genhd.c:part_in_flight
```
```
In block/blk-iocost.c (ffffffff816b0fb6)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
```
```
In io_uring/io_uring.c (ffffffff816cd3dd)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_buffer_account_pin
  - io_uring/io_uring.c:io_openat2
  - io_uring/io_uring.c:io_fallocate
  - io_uring/io_uring.c:__io_complete_rw_common
  - io_uring/io_uring.c:__io_complete_rw_common
```
```
In lib/percpu-refcount.c (ffffffff816e8f02)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_avail
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In lib/show_mem.c (ffffffff81ea6272)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
  - lib/show_mem.c:show_mem
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c5374)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
```
In drivers/tty/tty_ldsem.c (ffffffff818fd415)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
```
```
In drivers/char/agp/backend.c (ffffffff8193c125)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_initialize
```
```
In drivers/dma-buf/dma-buf.c (ffffffff819ec382)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_show_fdinfo
```
```
In drivers/net/loopback.c (ffffffff81a51616)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - drivers/net/loopback.c:dev_lstats_read
  - drivers/net/loopback.c:dev_lstats_read
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81a5adf5)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdio_bus_device_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
```
```
In drivers/net/tun.c (ffffffff81a5fef7)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_get_stats64
```
```
In drivers/md/dm-stats.c (ffffffff81b7e682)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:__check_shared_memory
```
```
In net/core/sock.c (ffffffff81bee312)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/core/sock.c:proto_seq_printf
  - net/core/sock.c:__sk_mem_reduce_allocated
```
```
In net/core/skbuff.c (ffffffff81bf78d3)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_account_pinned_pages
```
```
In net/core/gen_stats.c (ffffffff81c029e5)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff81c0366c)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/xdp.c (ffffffff81c51a98)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/net-sysfs.c (ffffffff81c553e9)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_timeout_show
```
```
In net/core/page_pool.c (ffffffff81c5a61b)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_return_skb_page
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
```
```
In net/ipv4/inetpeer.c (ffffffff834cbcd2)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_initpeers
```
```
In net/ipv4/tcp.c (ffffffff81cee065)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff81cf3b32)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d1097f)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_net_metrics_init
```
```
In net/ipv4/inet_fragment.c (ffffffff81d42059)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/nexthop.c (ffffffff81d4b675)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nh_res_table_upkeep
```
```
In net/ipv4/proc.c (ffffffff81d4f4c2)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81d833f0)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/unix/scm.c (ffffffff81d8416b)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/addrconf.c (ffffffff81d8f7e8)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/proc.c (ffffffff81de2813)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_seq_show_item
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:sockstat6_seq_show
```
```
In net/ipv6/seg6_local.c (ffffffff81de7a31)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/packet/af_packet.c (ffffffff81df136d)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81e19267)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100f74d)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/ibs.c:perf_ibs_event_update
```
```
In arch/x86/events/msr.c (ffffffff81010ab3)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff81014675)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
```
```
In arch/x86/events/intel/bts.c (ffffffff81017753)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff810184e8)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff81021794)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
```
```
In arch/x86/events/intel/uncore.c (ffffffff81024feb)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81094478)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_direct
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810dc8aa)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_get_local64
```
```
In kernel/fork.c (ffffffff83ea4c86)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
```
```
In kernel/workqueue.c (ffffffff8111207d)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - kernel/ucount.c:is_rlimit_overlimit
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/fair.c (ffffffff8114c425)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_cfs_group
```
```
In kernel/sched/build_utility.c (ffffffff81177122)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
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
In kernel/printk/printk_ringbuffer.c (ffffffff81194221)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_atomic_pool_init
```
```
In kernel/kexec_core.c (ffffffff811fee8a)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In kernel/cgroup/misc.c (ffffffff8121f262)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_events_show
  - kernel/cgroup/misc.c:misc_cg_current_show
  - kernel/cgroup/misc.c:misc_cg_res_total_usage
```
```
In kernel/trace/ring_buffer.c (ffffffff81261405)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - kernel/trace/trace.c:latency_fsnotify_workfn
```
```
In kernel/bpf/syscall.c (ffffffff812c5a97)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/syscall.c:bpf_prog_get_stats
```
```
In kernel/events/core.c (ffffffff8134165d)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:free_event
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:__perf_remove_from_context
```
```
In kernel/events/ring_buffer.c (ffffffff8134b3bc)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/vmscan.c (ffffffff81388245)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
```
```
In mm/vmstat.c (ffffffff81396855)
Location: include/linux/atomic/atomic-long.h:27
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
In mm/mm_init.c (ffffffff83ebacb7)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mm_init.c:mm_compute_batch_notifier
```
```
In mm/compaction.c (ffffffff813aa06f)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
```
In mm/workingset.c (ffffffff83ebd685)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/mmap.c (ffffffff813c69f5)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
```
```
In mm/vmalloc.c (ffffffff813e2d23)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cache_get_folio
  - mm/swap_state.c:show_swap_cache_info
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/swapfile.c (ffffffff81400b3b)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/swapfile.c:si_swapinfo
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/swap_slots.c (ffffffff814017af)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/zswap.c (ffffffff81403d9b)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff8140c685)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_report_usage
```
```
In mm/slub.c (ffffffff8142e447)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/kfence/core.c:__kfence_alloc
  - mm/kfence/core.c:stats_show
```
```
In mm/migrate.c (ffffffff814331eb)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
```
```
In mm/huge_memory.c (ffffffff814428fc)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:hugepage_init
```
```
In mm/page_counter.c (ffffffff8144d2b9)
Location: include/linux/atomic/atomic-long.h:27
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
In mm/memcontrol.c (ffffffff8144d8cc)
Location: include/linux/atomic/atomic-long.h:27
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
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff8145d3a7)
Location: include/linux/atomic/atomic-long.h:27
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
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/zsmalloc.c (ffffffff81466a35)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_zpool_total_size
```
```
In fs/open.c (ffffffff81473675)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/open.c:filp_close
  - fs/open.c:do_sys_openat2
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff8147bcdd)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:files_maxfiles_init
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/exec.c (ffffffff81485c2a)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
```
```
In fs/namei.c (ffffffff8148eba5)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/dcache.c (ffffffff8149ce46)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff814a2617)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/attr.c (ffffffff814a5a32)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
```
```
In fs/file.c (ffffffff814a839a)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/file.c:__fdget_pos
```
```
In fs/namespace.c (ffffffff814ad775)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/namespace.c:sb_prepare_remount_readonly
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/xattr.c (ffffffff814b5b88)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/libfs.c (ffffffff814b9a16)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/fs-writeback.c (ffffffff814c3034)
Location: include/linux/atomic/atomic-long.h:27
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
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
```
```
In fs/nsfs.c (ffffffff814cca14)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/remap_range.c (ffffffff814d113e)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
```
```
In fs/notify/fsnotify.c (ffffffff814dc962)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/posix_acl.c (ffffffff81516080)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
```
```
In fs/fhandle.c (ffffffff8151a2c7)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/quota/dquot.c (ffffffff815239ab)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/proc/task_mmu.c (ffffffff81530462)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/base.c (ffffffff815328b5)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/proc/array.c (ffffffff8153c47f)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/meminfo.c (ffffffff8153e4c0)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
```
```
In fs/configfs/dir.c (ffffffff81553b12)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff8155691c)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/ext4/extents.c (ffffffff81564e04)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff815766da)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff81582e37)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/xattr.c (ffffffff815cec3e)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
```
In fs/ext4/orphan.c (ffffffff815d8733)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/fat/file.c (ffffffff8160095b)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/fuse/dir.c (ffffffff81621570)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
```
```
In fs/fuse/inode.c (ffffffff83ecec44)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:set_global_limit
  - fs/fuse/inode.c:fuse_ilookup
```
```
In fs/debugfs/inode.c (ffffffff81633d66)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In fs/pstore/inode.c (ffffffff81638680)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
```
```
In security/security.c (ffffffff81665104)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
```
```
In security/landlock/fs.c (ffffffff816f0b98)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff816f4d21)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
```
```
In security/integrity/ima/ima_kexec.c (ffffffff81700fa8)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - security/integrity/ima/ima_kexec.c:ima_add_kexec_buffer
```
```
In block/blk-ioc.c (ffffffff8173a9c8)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:ioc_find_get_icq
```
```
In block/genhd.c (ffffffff81750dd0)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - block/genhd.c:part_inflight_show
  - block/genhd.c:part_inflight_show
  - block/genhd.c:part_in_flight
  - block/genhd.c:part_in_flight
```
```
In block/blk-iocost.c (ffffffff8176cb45)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_lat_stat
  - block/blk-iocost.c:ioc_lat_stat
  - block/blk-iocost.c:ioc_lat_stat
```
```
In io_uring/sync.c (ffffffff81793cc1)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - io_uring/sync.c:io_fallocate
```
```
In io_uring/openclose.c (ffffffff817947e0)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - io_uring/openclose.c:io_openat2
```
```
In io_uring/rsrc.c (ffffffff817a086d)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_account_mem
```
```
In io_uring/rw.c (ffffffff817a3a17)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
```
```
In lib/percpu-refcount.c (ffffffff817d8fd2)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_avail
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a15c64)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
```
In drivers/tty/tty_ldsem.c (ffffffff81a56af5)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
```
```
In drivers/char/agp/backend.c (ffffffff81a9c9e5)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_initialize
```
```
In drivers/base/memory.c (ffffffff81b16d60)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:memory_block_online
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81b69062)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_show_fdinfo
```
```
In drivers/spi/spi.c (ffffffff81bd4c63)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - drivers/net/loopback.c:dev_lstats_read
  - drivers/net/loopback.c:dev_lstats_read
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81be5725)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdio_bus_device_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
```
```
In drivers/net/tun.c (ffffffff81beb2c7)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_get_stats64
```
```
In drivers/md/dm-stats.c (ffffffff81d1c792)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:__check_shared_memory
```
```
In net/core/sock.c (ffffffff81d99c3f)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/core/sock.c:proto_seq_printf
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_setsockopt
```
```
In net/core/skbuff.c (ffffffff81da6633)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_account_pinned_pages
```
```
In net/core/gen_stats.c (ffffffff81db1ea5)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff81db2c5c)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff81dc171f)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:netdev_stats_to_stats64
```
```
In net/core/xdp.c (ffffffff81e06e57)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/net-sysfs.c (ffffffff81e0ad19)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_timeout_show
```
```
In net/core/page_pool.c (ffffffff81e100fb)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_return_skb_page
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
```
```
In net/core/drop_monitor.c (ffffffff81e25ed4)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
```
```
In net/core/devlink.c (ffffffff81e39623)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_initpeers
```
```
In net/ipv4/tcp.c (ffffffff81eb1307)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/tcp_input.c (ffffffff81eb8534)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed66df)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_net_metrics_init
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0ae99)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/nexthop.c (ffffffff81f14ddb)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nh_res_table_upkeep
```
```
In net/ipv4/proc.c (ffffffff81f190f2)
Location: include/linux/atomic/atomic-long.h:27
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
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81f50a90)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/unix/scm.c (ffffffff81f51a0b)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/addrconf.c (ffffffff81f5da08)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/proc.c (ffffffff81fb50ee)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_seq_show_item
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:snmp6_seq_show_icmpv6msg
  - net/ipv6/proc.c:sockstat6_seq_show
```
```
In net/ipv6/seg6_local.c (ffffffff81fbbbfd)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/packet/af_packet.c (ffffffff81fc4fdd)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81ff04bd)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In lib/show_mem.c (ffffffff8203cf7d)
Location: include/linux/atomic/atomic-long.h:27
Inline: True
Inline callers:
  - lib/show_mem.c:__show_mem
  - lib/show_mem.c:__show_mem
```
</details>
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
