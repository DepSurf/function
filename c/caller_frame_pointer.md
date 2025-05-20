# Function: <code>caller_frame_pointer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003417)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004472)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff810277eb)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb
  - arch/x86/xen/trace.c:perf_trace_xen_mc__batch
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_single
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry_alloc
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush_reason
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pmd_clear
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pud_clear
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd_clear
  - arch/x86/xen/trace.c:perf_trace_xen_mc_callback
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_load_idt
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush
  - arch/x86/xen/trace.c:perf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:perf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pte_clear
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_domain_pte
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pgd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_alloc_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_gdt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pte_at
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff8102fef2)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:perf_trace_x86_irq_vector
```
```
In arch/x86/kernel/nmi.c (ffffffff8103219c)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81043773)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:perf_trace_mce_record
```
```
In arch/x86/mm/init.c (ffffffff810688a7)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff81069f6c)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff81074d27)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
```
```
In kernel/fork.c (ffffffff8107d7cd)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/softirq.c (ffffffff8108495a)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_irq_handler_entry
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
```
```
In kernel/signal.c (ffffffff8108c9ea)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_generate
  - kernel/signal.c:perf_trace_signal_deliver
```
```
In kernel/workqueue.c (ffffffff81096e1c)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
```
```
In kernel/sched/core.c (ffffffff810a6c11)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_stat_template
  - kernel/sched/core.c:perf_trace_sched_wakeup_template
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_process_wait
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
  - kernel/sched/core.c:perf_trace_sched_process_hang
  - kernel/sched/core.c:perf_trace_sched_stat_runtime
  - kernel/sched/core.c:perf_trace_sched_process_template
  - kernel/sched/core.c:perf_trace_sched_pi_setprio
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_process_fork
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:perf_trace_sched_process_exec
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:__schedule
```
```
In kernel/printk/printk.c (ffffffff810d6715)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/rcu/update.c (ffffffff810e3302)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/time/timer.c (ffffffff810ebca2)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - kernel/time/timer.c:perf_trace_hrtimer_start
  - kernel/time/timer.c:perf_trace_itimer_expire
  - kernel/time/timer.c:perf_trace_hrtimer_class
  - kernel/time/timer.c:perf_trace_timer_class
  - kernel/time/timer.c:perf_trace_hrtimer_init
  - kernel/time/timer.c:perf_trace_timer_expire_entry
  - kernel/time/timer.c:perf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:perf_trace_timer_start
  - kernel/time/timer.c:perf_trace_itimer_state
  - kernel/time/timer.c:perf_trace_tick_stop
```
```
In kernel/module.c (ffffffff81104a0e)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
  - kernel/module.c:perf_trace_module_request
```
```
In kernel/trace/trace_event_perf.c (ffffffff811624ea)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/power-traces.c (ffffffff8116a367)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_cpu
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_suspend_resume
  - kernel/trace/power-traces.c:perf_trace_pstate_sample
  - kernel/trace/power-traces.c:perf_trace_wakeup_source
  - kernel/trace/power-traces.c:perf_trace_clock
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_power_domain
  - kernel/trace/power-traces.c:perf_trace_powernv_throttle
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_start
```
```
In kernel/trace/rpm-traces.c (ffffffff8116c60d)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In mm/filemap.c (ffffffff8118c6c2)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff811904b6)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
```
```
In mm/swap.c (ffffffff8119c547)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_activate
```
```
In mm/vmscan.c (ffffffff8119f985)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_shrink_slab_start
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_sleep
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_end_template
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_wake
  - mm/vmscan.c:perf_trace_mm_vmscan_wakeup_kswapd
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_isolate_template
  - mm/vmscan.c:perf_trace_mm_shrink_slab_end
```
```
In mm/slab_common.c (ffffffff811b24a5)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_kmem_free
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_kmem_alloc
  - mm/slab_common.c:perf_trace_kmem_alloc_node
```
```
In mm/compaction.c (ffffffff811b4d67)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - mm/compaction.c:perf_trace_mm_compaction_defer_template
  - mm/compaction.c:perf_trace_mm_compaction_migratepages
  - mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:perf_trace_mm_compaction_isolate_template
  - mm/compaction.c:perf_trace_mm_compaction_begin
  - mm/compaction.c:perf_trace_mm_compaction_end
  - mm/compaction.c:perf_trace_mm_compaction_suitable_template
```
```
In mm/migrate.c (ffffffff811f0510)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_numa_migrate_ratelimit
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/cma.c (ffffffff81206aa1)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_alloc
  - mm/cma.c:perf_trace_cma_release
```
```
In fs/open.c (ffffffff812091fc)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - fs/open.c:perf_trace_do_sys_open
  - fs/open.c:perf_trace_open_exec
```
```
In fs/fs-writeback.c (ffffffff81236862)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_pages_written
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:perf_trace_writeback_lazytime_template
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_page
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
```
```
In fs/locks.c (ffffffff8125f297)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_generic_add_lease
```
```
In fs/ext4/super.c (ffffffff812a9063)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_mballoc_alloc
  - fs/ext4/super.c:perf_trace_ext4__mballoc
  - fs/ext4/super.c:perf_trace_ext4__bitmap_load
  - fs/ext4/super.c:perf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_sync_fs
  - fs/ext4/super.c:perf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:perf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:perf_trace_ext4_discard_blocks
  - fs/ext4/super.c:perf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:perf_trace_ext4_load_inode
  - fs/ext4/super.c:perf_trace_ext4_journal_start
  - fs/ext4/super.c:perf_trace_ext4_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_request_inode
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:perf_trace_ext4_es_find_delayed_extent_range_enter
  - fs/ext4/super.c:perf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:perf_trace_ext4_drop_inode
  - fs/ext4/super.c:perf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:perf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:perf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:perf_trace_ext4_evict_inode
  - fs/ext4/super.c:perf_trace_ext4_collapse_range
  - fs/ext4/super.c:perf_trace_ext4_insert_range
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:perf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:perf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:perf_trace_ext4_get_reserved_cluster_alloc
  - fs/ext4/super.c:perf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:perf_trace_ext4__truncate
  - fs/ext4/super.c:perf_trace_ext4__write_end
  - fs/ext4/super.c:perf_trace_ext4_allocate_inode
  - fs/ext4/super.c:perf_trace_ext4__write_begin
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space
  - fs/ext4/super.c:perf_trace_ext4_ext_put_in_cache
  - fs/ext4/super.c:perf_trace_ext4_ext_show_extent
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_enter
  - fs/ext4/super.c:perf_trace_ext4_unlink_exit
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_enter
  - fs/ext4/super.c:perf_trace_ext4__fallocate_mode
  - fs/ext4/super.c:perf_trace_ext4_fallocate_exit
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:perf_trace_ext4_alloc_da_blocks
  - fs/ext4/super.c:perf_trace_ext4__trim
  - fs/ext4/super.c:perf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:perf_trace_ext4_forget
  - fs/ext4/super.c:perf_trace_ext4_free_blocks
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:perf_trace_ext4_find_delalloc_range
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4__page_op
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_unlink_enter
  - fs/ext4/super.c:perf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:perf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:perf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:perf_trace_ext4_da_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:perf_trace_ext4_writepages_result
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:perf_trace_ext4_da_release_space
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_writepages
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_request_blocks
  - fs/ext4/super.c:perf_trace_ext4_mballoc_prealloc
  - fs/ext4/super.c:perf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:perf_trace_ext4_free_inode
```
```
In fs/jbd2/journal.c (ffffffff812ee18c)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
```
```
In block/blk-core.c (ffffffff813b505a)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_buffer
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_with_error
```
```
In lib/swiotlb.c (ffffffff81412c5e)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - lib/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In drivers/gpio/gpiolib.c (ffffffff814243bc)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
```
```
In drivers/regulator/core.c (ffffffff814d78ac)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
  - drivers/regulator/core.c:perf_trace_regulator_value
```
```
In drivers/char/random.c (ffffffff81511bb5)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - drivers/char/random.c:perf_trace_xfer_secondary_pool
  - drivers/char/random.c:perf_trace_add_input_randomness
  - drivers/char/random.c:perf_trace_debit_entropy
  - drivers/char/random.c:perf_trace_add_disk_randomness
  - drivers/char/random.c:perf_trace_random__get_random_bytes
  - drivers/char/random.c:perf_trace_add_device_randomness
  - drivers/char/random.c:perf_trace_urandom_read
  - drivers/char/random.c:perf_trace_random__mix_pool_bytes
  - drivers/char/random.c:perf_trace_push_to_pool
  - drivers/char/random.c:perf_trace_random_read
  - drivers/char/random.c:perf_trace_random__extract_entropy
  - drivers/char/random.c:perf_trace_credit_entropy_bits
```
```
In drivers/iommu/iommu-traces.c (ffffffff8152c05c)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
```
```
In drivers/base/regmap/regmap.c (ffffffff81562de2)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
```
```
In drivers/dma-buf/fence.c (ffffffff815a485f)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - drivers/dma-buf/fence.c:perf_trace_fence
  - drivers/dma-buf/fence.c:perf_trace_fence_annotate_wait_on
```
```
In drivers/scsi/scsi.c (ffffffff815a5c8b)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
```
```
In drivers/ata/libata-core.c (ffffffff815c77c3)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
```
```
In drivers/spi/spi.c (ffffffff815e5192)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_master
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_transfer
```
```
In drivers/usb/host/xhci-trace.c (ffffffff816616b1)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_event
```
```
In drivers/i2c/i2c-core.c (ffffffff8167814e)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:perf_trace_i2c_write
  - drivers/i2c/i2c-core.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core.c:perf_trace_smbus_write
  - drivers/i2c/i2c-core.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core.c:perf_trace_i2c_reply
```
```
In drivers/thermal/thermal_core.c (ffffffff81685ade)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit
```
```
In drivers/thermal/power_allocator.c (ffffffff81689850)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
```
```
In drivers/clk/clk.c (ffffffff816e6a7b)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_rate
```
```
In drivers/ras/ras.c (ffffffff816f35af)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_mc_event
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
```
```
In net/core/net-traces.c (ffffffff8173b56c)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_consume_skb
  - net/core/net-traces.c:perf_trace_kfree_skb
  - net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_net_dev_xmit
  - net/core/net-traces.c:perf_trace_napi_poll
  - net/core/net-traces.c:perf_trace_net_dev_template
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_fib_table_lookup_nh
  - net/core/net-traces.c:perf_trace_fib_validate_source
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003067)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810045b2)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff81027877)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_gdt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_load_idt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_single
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_all
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_alloc_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd_clear
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pud_clear
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pgd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pmd_clear
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pte_clear
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pte_at
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_domain_pte
  - arch/x86/xen/trace.c:perf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:perf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush_reason
  - arch/x86/xen/trace.c:perf_trace_xen_mc_callback
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry_alloc
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mc__batch
```
```
In arch/x86/kernel/irq.c (ffffffff8102ef52)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:perf_trace_x86_irq_vector
```
```
In arch/x86/kernel/nmi.c (ffffffff810312bc)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81038a26)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81043886)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:perf_trace_mce_record
```
```
In arch/x86/mm/init.c (ffffffff81068577)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff81069c8c)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff810765d2)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff8107f3c4)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff81083140)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff81087ca2)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff8108fbb0)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff8109a3c2)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/sched/core.c (ffffffff8189a47d)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
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
```
```
In kernel/printk/printk.c (ffffffff810db6a1)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/rcu/update.c (ffffffff810e9082)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/time/timer.c (ffffffff810f3227)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
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
```
```
In kernel/module.c (ffffffff8110c2db)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/trace/trace_event_perf.c (ffffffff8116ccae)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/bpf_trace.c (ffffffff811744fa)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_event_output
```
```
In kernel/trace/power-traces.c (ffffffff81177f0b)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
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
  - kernel/trace/power-traces.c:perf_trace_pstate_sample
  - kernel/trace/power-traces.c:perf_trace_powernv_throttle
  - kernel/trace/power-traces.c:perf_trace_cpu
```
```
In kernel/trace/rpm-traces.c (ffffffff81179acd)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In mm/filemap.c (ffffffff8119f4e6)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff811a462a)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
```
```
In mm/swap.c (ffffffff811b1722)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff811b5ff8)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_isolate_template
  - mm/vmscan.c:perf_trace_mm_shrink_slab_end
  - mm/vmscan.c:perf_trace_mm_shrink_slab_start
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_end_template
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:perf_trace_mm_vmscan_wakeup_kswapd
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_wake
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_sleep
```
```
In mm/slab_common.c (ffffffff811cbf2a)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_free
  - mm/slab_common.c:perf_trace_kmem_alloc_node
  - mm/slab_common.c:perf_trace_kmem_alloc
```
```
In mm/compaction.c (ffffffff811ce75c)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - mm/compaction.c:perf_trace_kcompactd_wake_template
  - mm/compaction.c:perf_trace_mm_compaction_kcompactd_sleep
  - mm/compaction.c:perf_trace_mm_compaction_defer_template
  - mm/compaction.c:perf_trace_mm_compaction_suitable_template
  - mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:perf_trace_mm_compaction_end
  - mm/compaction.c:perf_trace_mm_compaction_begin
  - mm/compaction.c:perf_trace_mm_compaction_migratepages
  - mm/compaction.c:perf_trace_mm_compaction_isolate_template
```
```
In mm/migrate.c (ffffffff8120f914)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_numa_migrate_ratelimit
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff81218cb0)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff8122885c)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff8122c58c)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff8122f000)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/fs-writeback.c (ffffffff8125e3f6)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
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
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_page
```
```
In fs/locks.c (ffffffff8128b0ab)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff812dd3eb)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:perf_trace_ext4_insert_range
  - fs/ext4/super.c:perf_trace_ext4_collapse_range
  - fs/ext4/super.c:perf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:perf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:perf_trace_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_delayed_extent_range_enter
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
  - fs/ext4/super.c:perf_trace_ext4_drop_inode
  - fs/ext4/super.c:perf_trace_ext4_evict_inode
  - fs/ext4/super.c:perf_trace_ext4_allocate_inode
  - fs/ext4/super.c:perf_trace_ext4_request_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
```
```
In fs/jbd2/journal.c (ffffffff8131c6d7)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
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
```
```
In block/blk-core.c (ffffffff813f9993)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
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
  - block/blk-core.c:perf_trace_block_rq_with_error
  - block/blk-core.c:perf_trace_block_buffer
```
```
In lib/swiotlb.c (ffffffff8145a7c2)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - lib/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In arch/x86/lib/msr.c (ffffffff81463d7c)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff8146da8c)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/regulator/core.c (ffffffff815287b3)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff8156494c)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
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
```
```
In drivers/iommu/iommu-traces.c (ffffffff8157fa02)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff815b7b39)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
```
```
In drivers/dma-buf/fence.c (ffffffff815fb907)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - drivers/dma-buf/fence.c:perf_trace_fence
  - drivers/dma-buf/fence.c:perf_trace_fence_annotate_wait_on
```
```
In drivers/scsi/scsi.c (ffffffff815fdfb2)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff816203f6)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff81642f6b)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_master
```
```
In drivers/usb/host/xhci-trace.c (ffffffff816c17bf)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_event
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
```
```
In drivers/i2c/i2c-core.c (ffffffff816d93e8)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core.c:perf_trace_smbus_write
  - drivers/i2c/i2c-core.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core.c:perf_trace_i2c_write
```
```
In drivers/thermal/thermal_core.c (ffffffff816e4341)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff816ea6a8)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff81720e50)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/clk/clk.c (ffffffff81748e9f)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/ras/ras.c (ffffffff8175826c)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_mc_event
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
```
```
In net/core/net-traces.c (ffffffff817a8f5d)
Location: arch/x86/include/asm/stacktrace.h:105
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_fib6_table_lookup
  - net/core/net-traces.c:perf_trace_fib_validate_source
  - net/core/net-traces.c:perf_trace_fib_table_lookup_nh
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:perf_trace_napi_poll
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_template
  - net/core/net-traces.c:perf_trace_net_dev_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:perf_trace_consume_skb
  - net/core/net-traces.c:perf_trace_kfree_skb
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
In arch/x86/entry/common.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In arch/x86/mm/init.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In kernel/fork.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In kernel/cpu.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In kernel/softirq.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In kernel/signal.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In kernel/workqueue.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In kernel/time/timer.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In kernel/module.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In kernel/cgroup.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In kernel/trace/trace_event_perf.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In kernel/trace/power-traces.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In kernel/trace/rpm-traces.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In mm/filemap.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In mm/oom_kill.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In mm/swap.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In mm/vmscan.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In mm/slab_common.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In mm/compaction.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In mm/page_isolation.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In mm/cma.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In fs/open.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In fs/locks.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In fs/ext4/super.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In block/blk-core.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In block/blk-wbt.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In lib/swiotlb.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In arch/x86/lib/msr.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/char/random.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/iommu/iommu-traces.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/usb/host/xhci-trace.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/i2c/i2c-core.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/thermal/power_allocator.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/ras/ras.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In net/core/net-traces.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
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
In arch/x86/entry/common.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In arch/x86/mm/init.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In kernel/fork.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In kernel/cpu.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In kernel/softirq.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In kernel/signal.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In kernel/workqueue.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In kernel/time/timer.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In kernel/module.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In kernel/trace/trace_event_perf.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In kernel/trace/power-traces.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In kernel/trace/rpm-traces.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In mm/filemap.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In mm/oom_kill.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In mm/swap.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In mm/vmscan.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In mm/slab_common.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In mm/compaction.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In mm/page_isolation.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In mm/cma.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In fs/open.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In fs/locks.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In fs/ext4/super.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In block/blk-core.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In block/blk-wbt.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In lib/swiotlb.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In arch/x86/lib/msr.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/char/random.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/iommu/iommu-traces.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/usb/host/xhci-trace.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/thermal/power_allocator.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In drivers/ras/ras.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
```
In net/core/net-traces.c (0)
Location: arch/x86/include/asm/stacktrace.h:99
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In arch/x86/kernel/nmi.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In arch/x86/mm/init.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In kernel/fork.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In kernel/cpu.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In kernel/softirq.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In kernel/signal.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In kernel/workqueue.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In kernel/time/timer.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In kernel/module.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In kernel/trace/trace_event_perf.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In kernel/trace/power-traces.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In kernel/trace/rpm-traces.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In mm/filemap.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In mm/oom_kill.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In mm/swap.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In mm/vmscan.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In mm/slab_common.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In mm/compaction.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In mm/page_isolation.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In mm/cma.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In fs/open.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In fs/locks.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In fs/ext4/super.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In block/blk-core.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In block/blk-wbt.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In lib/swiotlb.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In arch/x86/lib/msr.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In drivers/char/random.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In drivers/iommu/iommu-traces.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In drivers/usb/host/xhci-trace.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In drivers/thermal/power_allocator.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In drivers/ras/ras.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
```
In net/core/net-traces.c (0)
Location: arch/x86/include/asm/stacktrace.h:103
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff810021ad)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/common.c (ffffffff8100372d)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004eb8)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff810277bd)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_gdt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_load_idt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_one_user
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_alloc_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pte_at
  - arch/x86/xen/trace.c:perf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:perf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush_reason
  - arch/x86/xen/trace.c:perf_trace_xen_mc_callback
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry_alloc
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mc__batch
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102ba0a)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff8102fafa)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:perf_trace_vector_free_moved
  - arch/x86/kernel/irq.c:perf_trace_vector_setup
  - arch/x86/kernel/irq.c:perf_trace_vector_teardown
  - arch/x86/kernel/irq.c:perf_trace_vector_activate
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc_managed
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc
  - arch/x86/kernel/irq.c:perf_trace_vector_reserve
  - arch/x86/kernel/irq.c:perf_trace_vector_mod
  - arch/x86/kernel/irq.c:perf_trace_vector_config
  - arch/x86/kernel/irq.c:perf_trace_x86_irq_vector
```
```
In arch/x86/kernel/nmi.c (ffffffff81032592)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039f5c)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104b651)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:perf_trace_mce_record
```
```
In arch/x86/mm/init.c (ffffffff81072d0d)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff81074ad6)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff81081f78)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff8108a629)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff8108efaa)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff81094518)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff8109c11a)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810aa2e8)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/sched/core.c (ffffffff819ec90e)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
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
```
```
In kernel/printk/printk.c (ffffffff810f1850)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff8110116e)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff81102148)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff8110d698)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffffffff8111275d)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
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
```
```
In kernel/time/alarmtimer.c (ffffffff8111cba1)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff8112fe60)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff8113cfab)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_event_perf.c (ffffffff811976c4)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/bpf_trace.c (ffffffff811a594e)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
```
```
In kernel/trace/power-traces.c (ffffffff811aa28f)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
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
  - kernel/trace/power-traces.c:perf_trace_pstate_sample
  - kernel/trace/power-traces.c:perf_trace_powernv_throttle
  - kernel/trace/power-traces.c:perf_trace_cpu
```
```
In kernel/trace/rpm-traces.c (ffffffff811ab8d5)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/bpf/core.c (ffffffff811b0ae5)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/rseq.c (ffffffff811e9cfa)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff811eaef5)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff811f21da)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:perf_trace_skip_task_reaping
  - mm/oom_kill.c:perf_trace_finish_task_reaping
  - mm/oom_kill.c:perf_trace_start_task_reaping
  - mm/oom_kill.c:perf_trace_wake_reaper
  - mm/oom_kill.c:perf_trace_mark_victim
  - mm/oom_kill.c:perf_trace_reclaim_retry_zone
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
```
```
In mm/swap.c (ffffffff8120079c)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff812055b2)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
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
```
```
In mm/percpu.c (ffffffff812199f8)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff8121d034)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_free
  - mm/slab_common.c:perf_trace_kmem_alloc_node
  - mm/slab_common.c:perf_trace_kmem_alloc
```
```
In mm/compaction.c (ffffffff8121fc72)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - mm/compaction.c:perf_trace_kcompactd_wake_template
  - mm/compaction.c:perf_trace_mm_compaction_kcompactd_sleep
  - mm/compaction.c:perf_trace_mm_compaction_defer_template
  - mm/compaction.c:perf_trace_mm_compaction_suitable_template
  - mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:perf_trace_mm_compaction_end
  - mm/compaction.c:perf_trace_mm_compaction_begin
  - mm/compaction.c:perf_trace_mm_compaction_migratepages
  - mm/compaction.c:perf_trace_mm_compaction_isolate_template
```
```
In mm/migrate.c (ffffffff8126cb65)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_numa_migrate_ratelimit
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff8127a07a)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff8128b2b2)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff8128ef62)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff81295969)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/fs-writeback.c (ffffffff812c7fd0)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
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
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_page
```
```
In fs/dax.c (ffffffff812f64d6)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - fs/dax.c:perf_trace_dax_writeback_one
  - fs/dax.c:perf_trace_dax_writeback_range_class
  - fs/dax.c:perf_trace_dax_insert_mapping
  - fs/dax.c:perf_trace_dax_pte_fault_class
  - fs/dax.c:perf_trace_dax_pmd_insert_mapping_class
  - fs/dax.c:perf_trace_dax_pmd_load_hole_class
  - fs/dax.c:perf_trace_dax_pmd_fault_class
```
```
In fs/locks.c (ffffffff812fd105)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff8137a192)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_error
  - fs/ext4/super.c:perf_trace_ext4_shutdown
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:perf_trace_ext4_insert_range
  - fs/ext4/super.c:perf_trace_ext4_collapse_range
  - fs/ext4/super.c:perf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:perf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:perf_trace_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_delayed_extent_range_enter
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
  - fs/ext4/super.c:perf_trace_ext4_drop_inode
  - fs/ext4/super.c:perf_trace_ext4_evict_inode
  - fs/ext4/super.c:perf_trace_ext4_allocate_inode
  - fs/ext4/super.c:perf_trace_ext4_request_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
```
```
In fs/jbd2/journal.c (ffffffff8139a3bd)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
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
```
```
In block/blk-core.c (ffffffff8147e7ff)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
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
```
```
In block/blk-wbt.c (ffffffff814b8835)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff814f9812)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff81506842)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff815e3210)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff8160be0c)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff816455e2)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
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
```
```
In drivers/iommu/iommu-traces.c (ffffffff81663a49)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff8169fb81)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816e4823)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816e6cee)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff816e7b78)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff8170b850)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff8172eae5)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff817391f6)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff817b0ebc)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_slot_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ep_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_free_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_trb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
```
```
In drivers/rtc/interface.c (ffffffff817cc57c)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/rtc/interface.c:perf_trace_rtc_timer_class
  - drivers/rtc/interface.c:perf_trace_rtc_offset_class
  - drivers/rtc/interface.c:perf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_state
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_freq
  - drivers/rtc/interface.c:perf_trace_rtc_time_alarm_class
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817d2306)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff817d5d41)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/thermal/thermal_core.c (ffffffff817e7dd8)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff817ec391)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff8183234b)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/ras/ras.c (ffffffff81864632)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
```
```
In net/core/net-traces.c (ffffffff818c4cf1)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
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
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_template
  - net/core/net-traces.c:perf_trace_net_dev_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:perf_trace_consume_skb
  - net/core/net-traces.c:perf_trace_kfree_skb
```
```
In net/ipv6/route.c (ffffffff81970235)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
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
In init/main.c (ffffffff810021ad)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/common.c (ffffffff810037bd)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004e18)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff81027d9d)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_gdt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_load_idt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_one_user
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_alloc_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pte_at
  - arch/x86/xen/trace.c:perf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:perf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush
  - arch/x86/xen/trace.c:perf_trace_xen_mc_flush_reason
  - arch/x86/xen/trace.c:perf_trace_xen_mc_callback
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry_alloc
  - arch/x86/xen/trace.c:perf_trace_xen_mc_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mc__batch
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102c456)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff81030d8a)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:perf_trace_vector_free_moved
  - arch/x86/kernel/irq.c:perf_trace_vector_setup
  - arch/x86/kernel/irq.c:perf_trace_vector_teardown
  - arch/x86/kernel/irq.c:perf_trace_vector_activate
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc_managed
  - arch/x86/kernel/irq.c:perf_trace_vector_alloc
  - arch/x86/kernel/irq.c:perf_trace_vector_reserve
  - arch/x86/kernel/irq.c:perf_trace_vector_mod
  - arch/x86/kernel/irq.c:perf_trace_vector_config
  - arch/x86/kernel/irq.c:perf_trace_x86_irq_vector
```
```
In arch/x86/kernel/nmi.c (ffffffff81033852)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103b47c)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81048d11)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105bdcd)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff81078d9d)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff8107a996)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff81088b88)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff810925c9)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff810972aa)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff8109c878)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810a437a)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810b33b8)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/sched/core.c (ffffffff81a27a3a)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
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
```
```
In kernel/printk/printk.c (ffffffff810fcf00)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff8110ca8e)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff8110db48)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff81119298)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffffffff8111df2d)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
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
```
```
In kernel/time/alarmtimer.c (ffffffff81128351)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff8113b710)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff811488e9)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_event_perf.c (ffffffff811a5834)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/bpf_trace.c (ffffffff811b3c5e)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
```
```
In kernel/trace/power-traces.c (ffffffff811b863f)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
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
```
```
In kernel/trace/rpm-traces.c (ffffffff811b9e95)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/bpf/core.c (ffffffff811bf165)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/rseq.c (ffffffff811fa86a)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff811fba65)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff8120404a)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:perf_trace_skip_task_reaping
  - mm/oom_kill.c:perf_trace_finish_task_reaping
  - mm/oom_kill.c:perf_trace_start_task_reaping
  - mm/oom_kill.c:perf_trace_wake_reaper
  - mm/oom_kill.c:perf_trace_mark_victim
  - mm/oom_kill.c:perf_trace_reclaim_retry_zone
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
```
```
In mm/swap.c (ffffffff8121310c)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81217f82)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
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
```
```
In mm/percpu.c (ffffffff8122c968)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff81230024)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_free
  - mm/slab_common.c:perf_trace_kmem_alloc_node
  - mm/slab_common.c:perf_trace_kmem_alloc
```
```
In mm/compaction.c (ffffffff81232ca2)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - mm/compaction.c:perf_trace_kcompactd_wake_template
  - mm/compaction.c:perf_trace_mm_compaction_kcompactd_sleep
  - mm/compaction.c:perf_trace_mm_compaction_defer_template
  - mm/compaction.c:perf_trace_mm_compaction_suitable_template
  - mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:perf_trace_mm_compaction_end
  - mm/compaction.c:perf_trace_mm_compaction_begin
  - mm/compaction.c:perf_trace_mm_compaction_migratepages
  - mm/compaction.c:perf_trace_mm_compaction_isolate_template
```
```
In mm/migrate.c (ffffffff8128126a)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff8128e67a)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff812a0202)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff812a3e62)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff812aa759)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/fs-writeback.c (ffffffff812dd1d0)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
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
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_page
```
```
In fs/dax.c (ffffffff8130b5c6)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - fs/dax.c:perf_trace_dax_writeback_one
  - fs/dax.c:perf_trace_dax_writeback_range_class
  - fs/dax.c:perf_trace_dax_insert_mapping
  - fs/dax.c:perf_trace_dax_pte_fault_class
  - fs/dax.c:perf_trace_dax_pmd_insert_mapping_class
  - fs/dax.c:perf_trace_dax_pmd_load_hole_class
  - fs/dax.c:perf_trace_dax_pmd_fault_class
```
```
In fs/locks.c (ffffffff81312975)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff81392c32)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
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
```
```
In fs/jbd2/journal.c (ffffffff813b312d)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
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
```
```
In block/blk-core.c (ffffffff8149be4f)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
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
```
```
In block/blk-wbt.c (ffffffff814cc825)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff8150e0b2)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff8151ae42)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff815fd631)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff81623c7c)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff816638e2)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
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
```
```
In drivers/iommu/iommu-traces.c (ffffffff81682039)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff816bff91)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81707c13)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8170a07e)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff8170b678)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff8172dcd0)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff81751055)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff8175c916)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff817d743c)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_slot_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ep_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_free_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_trb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
```
```
In drivers/rtc/interface.c (ffffffff817f387c)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/rtc/interface.c:perf_trace_rtc_timer_class
  - drivers/rtc/interface.c:perf_trace_rtc_offset_class
  - drivers/rtc/interface.c:perf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_state
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_freq
  - drivers/rtc/interface.c:perf_trace_rtc_time_alarm_class
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817f9466)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff817fce71)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff81811840)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff81813c88)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff81818261)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff8185e54b)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/ras/ras.c (ffffffff81884202)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
```
```
In net/core/net-traces.c (ffffffff818edd61)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
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
  - net/core/net-traces.c:perf_trace_net_dev_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:perf_trace_consume_skb
  - net/core/net-traces.c:perf_trace_kfree_skb
```
```
In net/ipv6/route.c (ffffffff819a5e65)
Location: arch/x86/include/asm/stacktrace.h:101
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
</details>
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
