# Function: <code>current_stack_pointer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102f96b)
Location: arch/x86/include/asm/thread_info.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:ist_begin_non_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102ea2b)
Location: arch/x86/include/asm/thread_info.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:ist_begin_non_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102e96b)
Location: arch/x86/include/asm/thread_info.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:ist_begin_non_atomic
```
```
In arch/x86/mm/tlb.c (ffffffff81075fad)
Location: arch/x86/include/asm/thread_info.h:155
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102c82b)
Location: arch/x86/include/asm/thread_info.h:158
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:ist_begin_non_atomic
```
```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/include/asm/thread_info.h:158
Inline: True
```
</details>
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
<summary>In <code>ppc64el</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
  - arch/powerpc/kernel/ptrace.c:perf_trace_sys_exit
  - arch/powerpc/kernel/ptrace.c:perf_trace_sys_enter
  - arch/powerpc/kernel/irq.c:do_IRQ
  - arch/powerpc/kernel/irq.c:perf_trace_tlbia
  - arch/powerpc/kernel/irq.c:perf_trace_tlbie
  - arch/powerpc/kernel/irq.c:perf_trace_hash_fault
  - arch/powerpc/kernel/irq.c:perf_trace_opal_exit
  - arch/powerpc/kernel/irq.c:perf_trace_opal_entry
  - arch/powerpc/kernel/irq.c:perf_trace_hcall_exit
  - arch/powerpc/kernel/irq.c:perf_trace_hcall_entry
  - arch/powerpc/kernel/irq.c:perf_trace_ppc64_interrupt_class
  - arch/powerpc/kernel/process.c:show_stack
  - arch/powerpc/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/powerpc/kernel/stacktrace.c:save_stack_trace
  - arch/powerpc/mm/book3s64/hash_pgtable.c:perf_trace_hugepage_splitting
  - arch/powerpc/mm/book3s64/hash_pgtable.c:perf_trace_hugepage_update
  - arch/powerpc/mm/book3s64/hash_pgtable.c:perf_trace_hugepage_set_pmd
  - arch/powerpc/mm/book3s64/hash_pgtable.c:perf_trace_hugepage_invalidate
  - arch/powerpc/platforms/powernv/vas-window.c:perf_trace_vas_paste_crb
  - arch/powerpc/platforms/powernv/vas-window.c:perf_trace_vas_tx_win_open
  - arch/powerpc/platforms/powernv/vas-window.c:perf_trace_vas_rx_win_open
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_process_hang
  - kernel/sched/core.c:perf_trace_sched_pi_setprio
  - kernel/sched/core.c:perf_trace_sched_stat_runtime
  - kernel/sched/core.c:perf_trace_sched_stat_template
  - kernel/sched/core.c:perf_trace_sched_process_exec
  - kernel/sched/core.c:perf_trace_sched_process_fork
  - kernel/sched/core.c:perf_trace_sched_process_wait
  - kernel/sched/core.c:perf_trace_sched_process_template
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:perf_trace_sched_wakeup_template
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
  - kernel/printk/printk.c:perf_trace_console
  - kernel/rcu/update.c:perf_trace_rcu_utilization
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
  - kernel/time/timer.c:perf_trace_tick_stop
  - kernel/time/timer.c:perf_trace_itimer_expire
  - kernel/time/timer.c:perf_trace_itimer_state
  - kernel/time/timer.c:perf_trace_hrtimer_class
  - kernel/time/timer.c:perf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:perf_trace_hrtimer_start
  - kernel/time/timer.c:perf_trace_hrtimer_init
  - kernel/time/timer.c:perf_trace_timer_expire_entry
  - kernel/time/timer.c:perf_trace_timer_start
  - kernel/time/timer.c:perf_trace_timer_class
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:perf_trace_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_power_domain
  - kernel/trace/power-traces.c:perf_trace_clock
  - kernel/trace/power-traces.c:perf_trace_wakeup_source
  - kernel/trace/power-traces.c:perf_trace_suspend_resume
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:perf_trace_cpu_frequency_limits
  - kernel/trace/power-traces.c:perf_trace_pstate_sample
  - kernel/trace/power-traces.c:perf_trace_powernv_throttle
  - kernel/trace/power-traces.c:perf_trace_cpu
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:perf_trace_skip_task_reaping
  - mm/oom_kill.c:perf_trace_finish_task_reaping
  - mm/oom_kill.c:perf_trace_start_task_reaping
  - mm/oom_kill.c:perf_trace_wake_reaper
  - mm/oom_kill.c:perf_trace_mark_victim
  - mm/oom_kill.c:perf_trace_reclaim_retry_zone
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/vmscan.c:perf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:perf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_isolate
  - mm/vmscan.c:perf_trace_mm_shrink_slab_end
  - mm/vmscan.c:perf_trace_mm_shrink_slab_start
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_end_template
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:perf_trace_mm_vmscan_wakeup_kswapd
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_wake
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_sleep
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_free
  - mm/slab_common.c:perf_trace_kmem_alloc_node
  - mm/slab_common.c:perf_trace_kmem_alloc
  - mm/compaction.c:perf_trace_kcompactd_wake_template
  - mm/compaction.c:perf_trace_mm_compaction_kcompactd_sleep
  - mm/compaction.c:perf_trace_mm_compaction_defer_template
  - mm/compaction.c:perf_trace_mm_compaction_suitable_template
  - mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:perf_trace_mm_compaction_end
  - mm/compaction.c:perf_trace_mm_compaction_begin
  - mm/compaction.c:perf_trace_mm_compaction_migratepages
  - mm/compaction.c:perf_trace_mm_compaction_isolate_template
  - mm/migrate.c:perf_trace_mm_migrate_pages
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
  - mm/page_isolation.c:perf_trace_test_pages_isolated
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
  - fs/fs-writeback.c:perf_trace_writeback_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_pages_written
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/dax.c:perf_trace_dax_writeback_one
  - fs/dax.c:perf_trace_dax_writeback_range_class
  - fs/dax.c:perf_trace_dax_insert_mapping
  - fs/dax.c:perf_trace_dax_pte_fault_class
  - fs/dax.c:perf_trace_dax_pmd_insert_mapping_class
  - fs/dax.c:perf_trace_dax_pmd_load_hole_class
  - fs/dax.c:perf_trace_dax_pmd_fault_class
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
  - fs/ext4/super.c:perf_trace_ext4_error
  - fs/ext4/super.c:perf_trace_ext4_shutdown
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:perf_trace_ext4_insert_range
  - fs/ext4/super.c:perf_trace_ext4_collapse_range
  - fs/ext4/super.c:perf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:perf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_enter
  - fs/ext4/super.c:perf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_show_extent
  - fs/ext4/super.c:perf_trace_ext4_get_reserved_cluster_alloc
  - fs/ext4/super.c:perf_trace_ext4_find_delalloc_range
  - fs/ext4/super.c:perf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:perf_trace_ext4_ext_put_in_cache
  - fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:perf_trace_ext4__trim
  - fs/ext4/super.c:perf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:perf_trace_ext4_journal_start
  - fs/ext4/super.c:perf_trace_ext4_load_inode
  - fs/ext4/super.c:perf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_exit
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_enter
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:perf_trace_ext4__truncate
  - fs/ext4/super.c:perf_trace_ext4_unlink_exit
  - fs/ext4/super.c:perf_trace_ext4_unlink_enter
  - fs/ext4/super.c:perf_trace_ext4_fallocate_exit
  - fs/ext4/super.c:perf_trace_ext4__fallocate_mode
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_enter
  - fs/ext4/super.c:perf_trace_ext4__bitmap_load
  - fs/ext4/super.c:perf_trace_ext4_da_release_space
  - fs/ext4/super.c:perf_trace_ext4_da_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_forget
  - fs/ext4/super.c:perf_trace_ext4__mballoc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_prealloc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_alloc
  - fs/ext4/super.c:perf_trace_ext4_alloc_da_blocks
  - fs/ext4/super.c:perf_trace_ext4_sync_fs
  - fs/ext4/super.c:perf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:perf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:perf_trace_ext4_free_blocks
  - fs/ext4/super.c:perf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:perf_trace_ext4_request_blocks
  - fs/ext4/super.c:perf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:perf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:perf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:perf_trace_ext4_discard_blocks
  - fs/ext4/super.c:perf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:perf_trace_ext4__page_op
  - fs/ext4/super.c:perf_trace_ext4_writepages_result
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages
  - fs/ext4/super.c:perf_trace_ext4_writepages
  - fs/ext4/super.c:perf_trace_ext4__write_end
  - fs/ext4/super.c:perf_trace_ext4__write_begin
  - fs/ext4/super.c:perf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:perf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:perf_trace_ext4_nfs_commit_metadata
  - fs/ext4/super.c:perf_trace_ext4_drop_inode
  - fs/ext4/super.c:perf_trace_ext4_evict_inode
  - fs/ext4/super.c:perf_trace_ext4_allocate_inode
  - fs/ext4/super.c:perf_trace_ext4_request_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_buffer
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_activate
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
  - drivers/char/random.c:perf_trace_urandom_read
  - drivers/char/random.c:perf_trace_random_read
  - drivers/char/random.c:perf_trace_random__extract_entropy
  - drivers/char/random.c:perf_trace_random__get_random_bytes
  - drivers/char/random.c:perf_trace_xfer_secondary_pool
  - drivers/char/random.c:perf_trace_add_disk_randomness
  - drivers/char/random.c:perf_trace_add_input_randomness
  - drivers/char/random.c:perf_trace_debit_entropy
  - drivers/char/random.c:perf_trace_push_to_pool
  - drivers/char/random.c:perf_trace_credit_entropy_bits
  - drivers/char/random.c:perf_trace_random__mix_pool_bytes
  - drivers/char/random.c:perf_trace_add_device_randomness
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
  - drivers/vfio/pci/vfio_pci_nvlink2.c:perf_trace_vfio_pci_npu2_mmap
  - drivers/vfio/pci/vfio_pci_nvlink2.c:perf_trace_vfio_pci_nvgpu_mmap
  - drivers/vfio/pci/vfio_pci_nvlink2.c:perf_trace_vfio_pci_nvgpu_mmap_fault
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_slot_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ep_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_free_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_trb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
  - drivers/rtc/interface.c:perf_trace_rtc_timer_class
  - drivers/rtc/interface.c:perf_trace_rtc_offset_class
  - drivers/rtc/interface.c:perf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_state
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_freq
  - drivers/rtc/interface.c:perf_trace_rtc_time_alarm_class
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:perf_trace_neigh_create
  - net/core/net-traces.c:perf_trace_page_pool_state_hold
  - net/core/net-traces.c:perf_trace_page_pool_state_release
  - net/core/net-traces.c:perf_trace_page_pool_inflight
  - net/core/net-traces.c:perf_trace_br_fdb_update
  - net/core/net-traces.c:perf_trace_fdb_delete
  - net/core/net-traces.c:perf_trace_br_fdb_external_learn_add
  - net/core/net-traces.c:perf_trace_br_fdb_add
  - net/core/net-traces.c:perf_trace_qdisc_dequeue
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:perf_trace_napi_poll
  - net/core/net-traces.c:perf_trace_net_dev_rx_exit_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_template
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:perf_trace_net_dev_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:perf_trace_consume_skb
  - net/core/net-traces.c:perf_trace_kfree_skb
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
**Symbols:**

```
c0000000000307c0-c0000000000307c0: current_stack_pointer (STB_GLOBAL)
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
