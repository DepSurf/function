# Function: <code>perf_fetch_caller_regs</code>

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
In arch/x86/entry/common.c (ffffffff810033de)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004439)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff810277b2)
Location: include/linux/perf_event.h:880
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
In arch/x86/kernel/irq.c (ffffffff8102feb9)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:perf_trace_x86_irq_vector
```
```
In arch/x86/kernel/nmi.c (ffffffff81032163)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104373a)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:perf_trace_mce_record
```
```
In arch/x86/mm/init.c (ffffffff8106886e)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff81069f33)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff81074cee)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
```
```
In kernel/fork.c (ffffffff8107d794)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/softirq.c (ffffffff81084921)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_irq_handler_entry
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
```
```
In kernel/signal.c (ffffffff8108c9b1)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_generate
  - kernel/signal.c:perf_trace_signal_deliver
```
```
In kernel/workqueue.c (ffffffff81096de3)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
```
```
In kernel/sched/core.c (ffffffff810a6bd8)
Location: include/linux/perf_event.h:880
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
In kernel/printk/printk.c (ffffffff810d66dc)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/rcu/update.c (ffffffff810e32c9)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/time/timer.c (ffffffff810ebc69)
Location: include/linux/perf_event.h:880
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
In kernel/module.c (ffffffff811049d5)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
  - kernel/module.c:perf_trace_module_request
```
```
In kernel/trace/trace_event_perf.c (ffffffff811624ca)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/power-traces.c (ffffffff8116a32e)
Location: include/linux/perf_event.h:880
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
In kernel/trace/rpm-traces.c (ffffffff8116c5d4)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In mm/filemap.c (ffffffff8118c689)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff8119047d)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
```
```
In mm/swap.c (ffffffff8119c50e)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_activate
```
```
In mm/vmscan.c (ffffffff8119f94c)
Location: include/linux/perf_event.h:880
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
In mm/slab_common.c (ffffffff811b246c)
Location: include/linux/perf_event.h:880
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
In mm/compaction.c (ffffffff811b4d2e)
Location: include/linux/perf_event.h:880
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
In mm/migrate.c (ffffffff811f04d7)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_numa_migrate_ratelimit
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/cma.c (ffffffff81206a68)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_alloc
  - mm/cma.c:perf_trace_cma_release
```
```
In fs/open.c (ffffffff812091c3)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - fs/open.c:perf_trace_do_sys_open
  - fs/open.c:perf_trace_open_exec
```
```
In fs/fs-writeback.c (ffffffff81236829)
Location: include/linux/perf_event.h:880
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
In fs/locks.c (ffffffff8125f25e)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_generic_add_lease
```
```
In fs/ext4/super.c (ffffffff812a902a)
Location: include/linux/perf_event.h:880
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
In fs/jbd2/journal.c (ffffffff812ee153)
Location: include/linux/perf_event.h:880
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
In block/blk-core.c (ffffffff813b5021)
Location: include/linux/perf_event.h:880
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
In lib/swiotlb.c (ffffffff81412c25)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - lib/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In drivers/gpio/gpiolib.c (ffffffff81424383)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
```
```
In drivers/regulator/core.c (ffffffff814d7873)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
  - drivers/regulator/core.c:perf_trace_regulator_value
```
```
In drivers/char/random.c (ffffffff81511b7c)
Location: include/linux/perf_event.h:880
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
In drivers/iommu/iommu-traces.c (ffffffff8152c023)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
```
```
In drivers/base/regmap/regmap.c (ffffffff81562da9)
Location: include/linux/perf_event.h:880
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
In drivers/dma-buf/fence.c (ffffffff815a4826)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - drivers/dma-buf/fence.c:perf_trace_fence
  - drivers/dma-buf/fence.c:perf_trace_fence_annotate_wait_on
```
```
In drivers/scsi/scsi.c (ffffffff815a5c52)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
```
```
In drivers/ata/libata-core.c (ffffffff815c778a)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
```
```
In drivers/spi/spi.c (ffffffff815e5159)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_master
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_transfer
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81661678)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_event
```
```
In drivers/i2c/i2c-core.c (ffffffff81678115)
Location: include/linux/perf_event.h:880
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
In drivers/thermal/thermal_core.c (ffffffff81685aa2)
Location: include/linux/perf_event.h:880
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
In drivers/thermal/power_allocator.c (ffffffff81689808)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
```
```
In drivers/clk/clk.c (ffffffff816e6a39)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_rate
```
```
In drivers/ras/ras.c (ffffffff816f356e)
Location: include/linux/perf_event.h:880
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_mc_event
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
```
```
In net/core/net-traces.c (ffffffff8173b533)
Location: include/linux/perf_event.h:880
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
In arch/x86/entry/common.c (ffffffff81003058)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810045a3)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff81027868)
Location: include/linux/perf_event.h:1008
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
In arch/x86/kernel/irq.c (ffffffff8102ef43)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:perf_trace_x86_irq_vector
```
```
In arch/x86/kernel/nmi.c (ffffffff810312ad)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81038a17)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81043877)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:perf_trace_mce_record
```
```
In arch/x86/mm/init.c (ffffffff81068568)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff81069c7d)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff810765c3)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff8107f3b4)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff81083131)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff81087c93)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff8108fba1)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff8109a3b3)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/sched/core.c (ffffffff8189a472)
Location: include/linux/perf_event.h:1008
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
In kernel/printk/printk.c (ffffffff810db692)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/rcu/update.c (ffffffff810e9073)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/time/timer.c (ffffffff810f3218)
Location: include/linux/perf_event.h:1008
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
In kernel/module.c (ffffffff8110c2cc)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/trace/trace_event_perf.c (ffffffff8116cca6)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/bpf_trace.c (ffffffff811744ef)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_event_output
```
```
In kernel/trace/power-traces.c (ffffffff81177efc)
Location: include/linux/perf_event.h:1008
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
In kernel/trace/rpm-traces.c (ffffffff81179abe)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In mm/filemap.c (ffffffff8119f4d7)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff811a461a)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
```
```
In mm/swap.c (ffffffff811b1713)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff811b5fe9)
Location: include/linux/perf_event.h:1008
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
In mm/slab_common.c (ffffffff811cbf1b)
Location: include/linux/perf_event.h:1008
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
In mm/compaction.c (ffffffff811ce74d)
Location: include/linux/perf_event.h:1008
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
In mm/migrate.c (ffffffff8120f904)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_numa_migrate_ratelimit
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff81218ca1)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff8122884d)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff8122c57d)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff8122eff1)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/fs-writeback.c (ffffffff8125e3e7)
Location: include/linux/perf_event.h:1008
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
In fs/locks.c (ffffffff8128b09c)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff812dd3dc)
Location: include/linux/perf_event.h:1008
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
In fs/jbd2/journal.c (ffffffff8131c6c8)
Location: include/linux/perf_event.h:1008
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
In block/blk-core.c (ffffffff813f9984)
Location: include/linux/perf_event.h:1008
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
In lib/swiotlb.c (ffffffff8145a7b3)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - lib/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In arch/x86/lib/msr.c (ffffffff81463d6d)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff8146da7d)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/regulator/core.c (ffffffff815287a4)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff8156493d)
Location: include/linux/perf_event.h:1008
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
In drivers/iommu/iommu-traces.c (ffffffff8157f9f3)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff815b7b2a)
Location: include/linux/perf_event.h:1008
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
In drivers/dma-buf/fence.c (ffffffff815fb8f8)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - drivers/dma-buf/fence.c:perf_trace_fence
  - drivers/dma-buf/fence.c:perf_trace_fence_annotate_wait_on
```
```
In drivers/scsi/scsi.c (ffffffff815fdfa3)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff816203e7)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff81642f5c)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_master
```
```
In drivers/usb/host/xhci-trace.c (ffffffff816c17af)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_event
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
```
```
In drivers/i2c/i2c-core.c (ffffffff816d93d9)
Location: include/linux/perf_event.h:1008
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
In drivers/thermal/thermal_core.c (ffffffff816e4332)
Location: include/linux/perf_event.h:1008
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
In drivers/thermal/power_allocator.c (ffffffff816ea699)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff81720e41)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/clk/clk.c (ffffffff81748e90)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/ras/ras.c (ffffffff8175825d)
Location: include/linux/perf_event.h:1008
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_mc_event
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
```
```
In net/core/net-traces.c (ffffffff817a8f4d)
Location: include/linux/perf_event.h:1008
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
In arch/x86/entry/common.c (ffffffff81003058)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004623)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff81027fb8)
Location: include/linux/perf_event.h:1031
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
In arch/x86/kernel/irq.c (ffffffff8102ef03)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:perf_trace_x86_irq_vector
```
```
In arch/x86/kernel/nmi.c (ffffffff81030efd)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81038407)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810452c7)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:perf_trace_mce_record
```
```
In arch/x86/mm/init.c (ffffffff8106c1e8)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff8106d82d)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff8107a1b3)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff81083a64)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff81087cd1)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff8108cbf3)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff81094b21)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff8109f7e3)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/sched/core.c (ffffffff818cea4a)
Location: include/linux/perf_event.h:1031
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
In kernel/printk/printk.c (ffffffff810e2162)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/rcu/update.c (ffffffff810eff43)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/time/timer.c (ffffffff810fa548)
Location: include/linux/perf_event.h:1031
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
In kernel/time/alarmtimer.c (ffffffff81103fe8)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff81113d1c)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup.c (ffffffff81122dc6)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - kernel/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup.c:perf_trace_cgroup
  - kernel/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_event_perf.c (ffffffff81177f76)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/bpf_trace.c (ffffffff8117ff6f)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_event_output
```
```
In kernel/trace/power-traces.c (ffffffff811839bc)
Location: include/linux/perf_event.h:1031
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
In kernel/trace/rpm-traces.c (ffffffff8118558e)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In mm/filemap.c (ffffffff811aeef7)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff811b497a)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
```
```
In mm/swap.c (ffffffff811c1d53)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff811c65f9)
Location: include/linux/perf_event.h:1031
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
In mm/slab_common.c (ffffffff811dc02b)
Location: include/linux/perf_event.h:1031
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
In mm/compaction.c (ffffffff811de87d)
Location: include/linux/perf_event.h:1031
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
In mm/migrate.c (ffffffff81221a44)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_numa_migrate_ratelimit
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff8122b231)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff8123adfd)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff8123eaad)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff81241551)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/fs-writeback.c (ffffffff81271907)
Location: include/linux/perf_event.h:1031
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
In fs/locks.c (ffffffff8129fdfc)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff812f2f2c)
Location: include/linux/perf_event.h:1031
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
In fs/jbd2/journal.c (ffffffff813326a8)
Location: include/linux/perf_event.h:1031
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
In block/blk-core.c (ffffffff81413334)
Location: include/linux/perf_event.h:1031
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
In block/blk-wbt.c (ffffffff81449808)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In lib/swiotlb.c (ffffffff81479373)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - lib/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In arch/x86/lib/msr.c (ffffffff8148300d)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff8148f93d)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff81531710)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff81554d04)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff815912cd)
Location: include/linux/perf_event.h:1031
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
In drivers/iommu/iommu-traces.c (ffffffff815ac583)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff815e6e6a)
Location: include/linux/perf_event.h:1031
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
In drivers/dma-buf/dma-fence.c (ffffffff816299d8)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence_annotate_wait_on
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8162c045)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff8162d5a3)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff81650f57)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff8167402c)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_master
```
```
In drivers/net/phy/mdio_bus.c (ffffffff8167ce3c)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff816ef71f)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_event
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
```
```
In drivers/i2c/i2c-core.c (ffffffff817094c9)
Location: include/linux/perf_event.h:1031
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
In drivers/thermal/thermal_core.c (ffffffff81714ee2)
Location: include/linux/perf_event.h:1031
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
In drivers/thermal/power_allocator.c (ffffffff8171b5b9)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff817536d1)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/ras/ras.c (ffffffff8178482d)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_mc_event
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
```
```
In net/core/net-traces.c (ffffffff817d7a8d)
Location: include/linux/perf_event.h:1031
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
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81002f48)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810044dd)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff810265b4)
Location: include/linux/perf_event.h:1031
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
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
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
In arch/x86/kernel/irq.c (ffffffff8102d3ad)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:perf_trace_x86_irq_vector
```
```
In arch/x86/kernel/nmi.c (ffffffff8102f20f)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810365e7)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045431)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:perf_trace_mce_record
```
```
In arch/x86/mm/init.c (ffffffff8106b614)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff8106cf7f)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff81078a9d)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff81080920)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff81084ca3)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff81089b8d)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff81091a91)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff8109cfd1)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/sched/core.c (ffffffff81905f64)
Location: include/linux/perf_event.h:1031
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
In kernel/printk/printk.c (ffffffff810e1427)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/rcu/update.c (ffffffff810eff1d)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/time/timer.c (ffffffff810fc9d4)
Location: include/linux/perf_event.h:1031
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
In kernel/time/alarmtimer.c (ffffffff81106138)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff81116d40)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff8112300d)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_event_perf.c (ffffffff8117aca9)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/bpf_trace.c (ffffffff81182dfa)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_event_output
```
```
In kernel/trace/power-traces.c (ffffffff81186c6f)
Location: include/linux/perf_event.h:1031
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
In kernel/trace/rpm-traces.c (ffffffff811883b5)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/bpf/core.c (ffffffff8118e2d4)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_xdp_exception
  - kernel/bpf/core.c:perf_trace_bpf_map_next_key
  - kernel/bpf/core.c:perf_trace_bpf_map_delete_elem
  - kernel/bpf/core.c:perf_trace_bpf_map_keyval
  - kernel/bpf/core.c:perf_trace_bpf_obj_map
  - kernel/bpf/core.c:perf_trace_bpf_obj_prog
  - kernel/bpf/core.c:perf_trace_bpf_map_create
  - kernel/bpf/core.c:perf_trace_bpf_prog_load
  - kernel/bpf/core.c:perf_trace_bpf_prog_event
```
```
In mm/filemap.c (ffffffff811b5c5c)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff811bc391)
Location: include/linux/perf_event.h:1031
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
In mm/swap.c (ffffffff811ca021)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff811ceb39)
Location: include/linux/perf_event.h:1031
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
In mm/percpu.c (ffffffff811e25ed)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff811e5b69)
Location: include/linux/perf_event.h:1031
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
In mm/compaction.c (ffffffff811e85ef)
Location: include/linux/perf_event.h:1031
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
In mm/migrate.c (ffffffff8122d76c)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_numa_migrate_ratelimit
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff81236dd3)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff812468af)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff8124a38f)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff8124db11)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/fs-writeback.c (ffffffff8127e971)
Location: include/linux/perf_event.h:1031
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
In fs/dax.c (ffffffff812a8cbf)
Location: include/linux/perf_event.h:1031
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
In fs/locks.c (ffffffff812aec5c)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff81327cd8)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
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
In fs/jbd2/journal.c (ffffffff813475e4)
Location: include/linux/perf_event.h:1031
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
In block/blk-core.c (ffffffff81420984)
Location: include/linux/perf_event.h:1031
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
In block/blk-wbt.c (ffffffff81457d2c)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In lib/swiotlb.c (ffffffff81482741)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - lib/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In arch/x86/lib/msr.c (ffffffff8148c78f)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff814992cf)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff81547910)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff8156fa3c)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff815a523f)
Location: include/linux/perf_event.h:1031
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
In drivers/iommu/iommu-traces.c (ffffffff815c2503)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff815fb871)
Location: include/linux/perf_event.h:1031
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
In drivers/dma-buf/dma-fence.c (ffffffff8163f9a2)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence_annotate_wait_on
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81641db2)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff8164264d)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff81665771)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff816887c8)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81691e3c)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81704e18)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_slot_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ep_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_trb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8171e70f)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81722016)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/thermal/thermal_core.c (ffffffff8172f1ba)
Location: include/linux/perf_event.h:1031
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
In drivers/thermal/power_allocator.c (ffffffff817336f6)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff81773421)
Location: include/linux/perf_event.h:1031
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/ras/ras.c (ffffffff817a343f)
Location: include/linux/perf_event.h:1031
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
In net/core/net-traces.c (ffffffff817f5f4a)
Location: include/linux/perf_event.h:1031
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
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81002f7e)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004757)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff81026cde)
Location: include/linux/perf_event.h:1018
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
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_all
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
In arch/x86/hyperv/mmu.c (ffffffff8102ae35)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff8102eac8)
Location: include/linux/perf_event.h:1018
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
In arch/x86/kernel/nmi.c (ffffffff81031215)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810389d7)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81048d28)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:perf_trace_mce_record
```
```
In arch/x86/mm/init.c (ffffffff8106feae)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff81071cf5)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff8107edf7)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff810871ea)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff8108b748)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff81090917)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff81098945)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810a3817)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/sched/core.c (ffffffff8198ff9b)
Location: include/linux/perf_event.h:1018
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
In kernel/printk/printk.c (ffffffff810e9583)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff810f8c19)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff810f9be7)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/time/timer.c (ffffffff8110729e)
Location: include/linux/perf_event.h:1018
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
In kernel/time/alarmtimer.c (ffffffff811111be)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff81122363)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff8112ecb7)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_event_perf.c (ffffffff81188504)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/bpf_trace.c (ffffffff811908c9)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_event_output
```
```
In kernel/trace/power-traces.c (ffffffff811946c2)
Location: include/linux/perf_event.h:1018
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
In kernel/trace/rpm-traces.c (ffffffff81196074)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/bpf/core.c (ffffffff8119b4b9)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_exception
  - kernel/bpf/core.c:perf_trace_bpf_map_next_key
  - kernel/bpf/core.c:perf_trace_bpf_map_delete_elem
  - kernel/bpf/core.c:perf_trace_bpf_map_keyval
  - kernel/bpf/core.c:perf_trace_bpf_obj_map
  - kernel/bpf/core.c:perf_trace_bpf_obj_prog
  - kernel/bpf/core.c:perf_trace_bpf_map_create
  - kernel/bpf/core.c:perf_trace_bpf_prog_load
  - kernel/bpf/core.c:perf_trace_bpf_prog_event
```
```
In mm/filemap.c (ffffffff811c9d9e)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff811d0fb5)
Location: include/linux/perf_event.h:1018
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
In mm/swap.c (ffffffff811deef7)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff811e3f6d)
Location: include/linux/perf_event.h:1018
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
In mm/percpu.c (ffffffff811f8777)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff811fbdaf)
Location: include/linux/perf_event.h:1018
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
In mm/compaction.c (ffffffff811fe925)
Location: include/linux/perf_event.h:1018
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
In mm/migrate.c (ffffffff812490ba)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_numa_migrate_ratelimit
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff81256178)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff81266a25)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff8126a595)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff8126fc4c)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/fs-writeback.c (ffffffff812a1457)
Location: include/linux/perf_event.h:1018
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
In fs/dax.c (ffffffff812cc1a5)
Location: include/linux/perf_event.h:1018
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
In fs/locks.c (ffffffff812d264e)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff8134c18e)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
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
In fs/jbd2/journal.c (ffffffff8136bc2e)
Location: include/linux/perf_event.h:1018
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
In block/blk-core.c (ffffffff8144b4f9)
Location: include/linux/perf_event.h:1018
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
In block/blk-wbt.c (ffffffff81483aa0)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In lib/swiotlb.c (ffffffff814be763)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - lib/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In arch/x86/lib/msr.c (ffffffff814c8885)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff814d75d5)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff815ab24f)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff815d3ecf)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff8160bb45)
Location: include/linux/perf_event.h:1018
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
In drivers/iommu/iommu-traces.c (ffffffff81628d08)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff81663a3e)
Location: include/linux/perf_event.h:1018
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
In drivers/dma-buf/dma-fence.c (ffffffff816a8534)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816aa801)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff816ab667)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff816cedc7)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff816f209e)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff816fbc55)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81770ad7)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_slot_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ep_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_trb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8178f9a5)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8179343c)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/thermal/thermal_core.c (ffffffff817a0816)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff817a48bc)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff817e94db)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/ras/ras.c (ffffffff8181a5b5)
Location: include/linux/perf_event.h:1018
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
In net/core/net-traces.c (ffffffff81873565)
Location: include/linux/perf_event.h:1018
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_br_fdb_update
  - net/core/net-traces.c:perf_trace_fdb_delete
  - net/core/net-traces.c:perf_trace_br_fdb_external_learn_add
  - net/core/net-traces.c:perf_trace_br_fdb_add
  - net/core/net-traces.c:perf_trace_fib6_table_lookup
  - net/core/net-traces.c:perf_trace_qdisc_dequeue
  - net/core/net-traces.c:perf_trace_fib_validate_source
  - net/core/net-traces.c:perf_trace_fib_table_lookup_nh
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_set_state
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
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
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff810021a6)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/common.c (ffffffff81003726)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004eb1)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff810277b6)
Location: include/linux/perf_event.h:1045
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
In arch/x86/hyperv/mmu.c (ffffffff8102ba03)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff8102faf3)
Location: include/linux/perf_event.h:1045
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
In arch/x86/kernel/nmi.c (ffffffff8103258b)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039f55)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104b64a)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:perf_trace_mce_record
```
```
In arch/x86/mm/init.c (ffffffff81072d06)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff81074acf)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff81081f71)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff8108a622)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff8108efa3)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff81094511)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff8109c113)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810aa2e1)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/sched/core.c (ffffffff819ec903)
Location: include/linux/perf_event.h:1045
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
In kernel/printk/printk.c (ffffffff810f1849)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff81101167)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff81102141)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff8110d691)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffffffff81112756)
Location: include/linux/perf_event.h:1045
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
In kernel/time/alarmtimer.c (ffffffff8111cb9a)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff8112fe59)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff8113cfa4)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_event_perf.c (ffffffff811976b4)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/bpf_trace.c (ffffffff811a5943)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
```
```
In kernel/trace/power-traces.c (ffffffff811aa288)
Location: include/linux/perf_event.h:1045
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
In kernel/trace/rpm-traces.c (ffffffff811ab8ce)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/bpf/core.c (ffffffff811b0ade)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/rseq.c (ffffffff811e9cf3)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff811eaeee)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff811f21d3)
Location: include/linux/perf_event.h:1045
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
In mm/swap.c (ffffffff81200795)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff812055ab)
Location: include/linux/perf_event.h:1045
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
In mm/percpu.c (ffffffff812199f1)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff8121d02d)
Location: include/linux/perf_event.h:1045
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
In mm/compaction.c (ffffffff8121fc6b)
Location: include/linux/perf_event.h:1045
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
In mm/migrate.c (ffffffff8126cb5e)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_numa_migrate_ratelimit
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff8127a073)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff8128b2ab)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff8128ef5b)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff81295962)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/fs-writeback.c (ffffffff812c7fc9)
Location: include/linux/perf_event.h:1045
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
In fs/dax.c (ffffffff812f64cf)
Location: include/linux/perf_event.h:1045
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
In fs/locks.c (ffffffff812fd0fe)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff8137a18b)
Location: include/linux/perf_event.h:1045
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
In fs/jbd2/journal.c (ffffffff8139a3b6)
Location: include/linux/perf_event.h:1045
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
In block/blk-core.c (ffffffff8147e7f8)
Location: include/linux/perf_event.h:1045
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
In block/blk-wbt.c (ffffffff814b882e)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff814f980b)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff8150683b)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff815e3209)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff8160be05)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff816455db)
Location: include/linux/perf_event.h:1045
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
In drivers/iommu/iommu-traces.c (ffffffff81663a42)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff8169fb7a)
Location: include/linux/perf_event.h:1045
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
In drivers/dma-buf/dma-fence.c (ffffffff816e481c)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816e6ce7)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff816e7b71)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff8170b849)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff8172eade)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff817391ef)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff817b0eb5)
Location: include/linux/perf_event.h:1045
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
In drivers/rtc/interface.c (ffffffff817cc575)
Location: include/linux/perf_event.h:1045
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
In drivers/i2c/i2c-core-base.c (ffffffff817d22ff)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff817d5d3a)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/thermal/thermal_core.c (ffffffff817e7dd1)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff817ec38a)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff81832344)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/ras/ras.c (ffffffff8186462b)
Location: include/linux/perf_event.h:1045
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
In net/core/net-traces.c (ffffffff818c4cea)
Location: include/linux/perf_event.h:1045
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
In net/ipv6/route.c (ffffffff8197022e)
Location: include/linux/perf_event.h:1045
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
In init/main.c (ffffffff810021a6)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/common.c (ffffffff810037b6)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004e11)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff81027d96)
Location: include/linux/perf_event.h:1050
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
In arch/x86/hyperv/mmu.c (ffffffff8102c44f)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff81030d83)
Location: include/linux/perf_event.h:1050
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
In arch/x86/kernel/nmi.c (ffffffff8103384b)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103b475)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81048d0a)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105bdc6)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff81078d96)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff8107a98f)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff81088b81)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff810925c2)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff810972a3)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff8109c871)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810a4373)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810b33b1)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/sched/core.c (ffffffff81a27a2f)
Location: include/linux/perf_event.h:1050
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
In kernel/printk/printk.c (ffffffff810fcef9)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff8110ca87)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff8110db41)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff81119291)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffffffff8111df26)
Location: include/linux/perf_event.h:1050
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
In kernel/time/alarmtimer.c (ffffffff8112834a)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff8113b709)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff811488e2)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_event_perf.c (ffffffff811a5824)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/bpf_trace.c (ffffffff811b3c53)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
```
```
In kernel/trace/power-traces.c (ffffffff811b8638)
Location: include/linux/perf_event.h:1050
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
In kernel/trace/rpm-traces.c (ffffffff811b9e8e)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/bpf/core.c (ffffffff811bf15e)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/rseq.c (ffffffff811fa863)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff811fba5e)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff81204043)
Location: include/linux/perf_event.h:1050
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
In mm/swap.c (ffffffff81213105)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81217f7b)
Location: include/linux/perf_event.h:1050
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
In mm/percpu.c (ffffffff8122c961)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff8123001d)
Location: include/linux/perf_event.h:1050
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
In mm/compaction.c (ffffffff81232c9b)
Location: include/linux/perf_event.h:1050
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
In mm/migrate.c (ffffffff81281263)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff8128e673)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff812a01fb)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff812a3e5b)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff812aa752)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/fs-writeback.c (ffffffff812dd1c9)
Location: include/linux/perf_event.h:1050
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
In fs/dax.c (ffffffff8130b5bf)
Location: include/linux/perf_event.h:1050
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
In fs/locks.c (ffffffff8131296e)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff81392c2b)
Location: include/linux/perf_event.h:1050
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
In fs/jbd2/journal.c (ffffffff813b3126)
Location: include/linux/perf_event.h:1050
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
In block/blk-core.c (ffffffff8149be48)
Location: include/linux/perf_event.h:1050
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
In block/blk-wbt.c (ffffffff814cc81e)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff8150e0ab)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff8151ae3b)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff815fd62a)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff81623c75)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff816638db)
Location: include/linux/perf_event.h:1050
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
In drivers/iommu/iommu-traces.c (ffffffff81682032)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff816bff8a)
Location: include/linux/perf_event.h:1050
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
In drivers/dma-buf/dma-fence.c (ffffffff81707c0c)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8170a077)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff8170b671)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff8172dcc9)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff8175104e)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff8175c90f)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff817d7435)
Location: include/linux/perf_event.h:1050
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
In drivers/rtc/interface.c (ffffffff817f3875)
Location: include/linux/perf_event.h:1050
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
In drivers/i2c/i2c-core-base.c (ffffffff817f945f)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff817fce6a)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff81811839)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff81813c81)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff8181825a)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff8185e544)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/ras/ras.c (ffffffff818841fb)
Location: include/linux/perf_event.h:1050
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
In net/core/net-traces.c (ffffffff818edd5a)
Location: include/linux/perf_event.h:1050
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
In net/ipv6/route.c (ffffffff819a5e5e)
Location: include/linux/perf_event.h:1050
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
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
In init/main.c (ffffffff81002239)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/common.c (ffffffff810038f9)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004ee4)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff81029a09)
Location: include/linux/perf_event.h:1086
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
In arch/x86/hyperv/mmu.c (ffffffff8102d82b)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff81032ad2)
Location: include/linux/perf_event.h:1086
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
In arch/x86/kernel/nmi.c (ffffffff810355de)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103da48)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104bdbd)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105f139)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff8107c989)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff8107e6fe)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff8108c754)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff81096452)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff8109b832)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff810a0eb4)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810a9032)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810b8f64)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/sched/core.c (ffffffff81a9836a)
Location: include/linux/perf_event.h:1086
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
In kernel/printk/printk.c (ffffffff811055ec)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff81116175)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff811171e4)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff81123cf7)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffffffff81128b99)
Location: include/linux/perf_event.h:1086
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
In kernel/time/alarmtimer.c (ffffffff81132d89)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff81146d4d)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff811538e5)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_event_perf.c (ffffffff811b3746)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/bpf_trace.c (ffffffff811c2c4f)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
```
```
In kernel/trace/power-traces.c (ffffffff811c773c)
Location: include/linux/perf_event.h:1086
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
In kernel/trace/rpm-traces.c (ffffffff811c8edc)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/bpf/core.c (ffffffff811cf469)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/rseq.c (ffffffff81211fb2)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff81213131)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff8121b429)
Location: include/linux/perf_event.h:1086
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
In mm/swap.c (ffffffff81222a24)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff812279ae)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
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
```
```
In mm/percpu.c (ffffffff8123c9e4)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff8124005d)
Location: include/linux/perf_event.h:1086
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
In mm/compaction.c (ffffffff8124322e)
Location: include/linux/perf_event.h:1086
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
In mm/migrate.c (ffffffff8129d592)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff812a8fa2)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff812bb47e)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff812bf26e)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff812c6f26)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/fs-writeback.c (ffffffff812fb878)
Location: include/linux/perf_event.h:1086
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
  - fs/fs-writeback.c:perf_trace_writeback_page_template
```
```
In fs/dax.c (ffffffff81332a4e)
Location: include/linux/perf_event.h:1086
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
In fs/locks.c (ffffffff8133a032)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff813bcace)
Location: include/linux/perf_event.h:1086
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
In fs/jbd2/journal.c (ffffffff813dd6f9)
Location: include/linux/perf_event.h:1086
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
In block/blk-core.c (ffffffff814c9f57)
Location: include/linux/perf_event.h:1086
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
In block/blk-wbt.c (ffffffff814fb06a)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff8153c71e)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff81548dae)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff8162e87d)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff81656887)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff8169925e)
Location: include/linux/perf_event.h:1086
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
In drivers/iommu/iommu-traces.c (ffffffff816b9788)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff816fade8)
Location: include/linux/perf_event.h:1086
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
In drivers/dma-buf/dma-fence.c (ffffffff81742e43)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8174589a)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff81746db4)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff81769438)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff8178f372)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81799e1e)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81817a58)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
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
```
```
In drivers/rtc/interface.c (ffffffff81834564)
Location: include/linux/perf_event.h:1086
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
In drivers/i2c/i2c-core-base.c (ffffffff8183a15e)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8183deda)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff8185384c)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff81855830)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff8185a37a)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff818a1f39)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff818bedc4)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_cmd_class
```
```
In drivers/devfreq/devfreq.c (ffffffff818c77ff)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/ras/ras.c (ffffffff818ce8ee)
Location: include/linux/perf_event.h:1086
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
In net/core/net-traces.c (ffffffff8193e663)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
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
```
```
In net/core/devlink.c (ffffffff81949fd5)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/bpf/test_run.c (ffffffff8196cfb4)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (ffffffff81a1247e)
Location: include/linux/perf_event.h:1086
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
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
In init/main.c (ffffffff81002239)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/common.c (ffffffff810038f9)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004f64)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff8102a309)
Location: include/linux/perf_event.h:1100
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
In arch/x86/hyperv/mmu.c (ffffffff8102e13b)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff81033392)
Location: include/linux/perf_event.h:1100
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
In arch/x86/kernel/nmi.c (ffffffff81035e0e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e208)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c77d)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105f9b9)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff8107da39)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff8107f78e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff8108d3b4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff8109ca12)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff810a1db2)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff810a7474)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810af602)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810bf4a4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/sched/core.c (ffffffff81acfbda)
Location: include/linux/perf_event.h:1100
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
In kernel/printk/printk.c (ffffffff8111196c)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff81122545)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff811235b4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff8112fc87)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffffffff81134b39)
Location: include/linux/perf_event.h:1100
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
In kernel/time/alarmtimer.c (ffffffff8113ece9)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff8115292d)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff8115f535)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_event_perf.c (ffffffff811bed36)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/bpf_trace.c (ffffffff811ce3bf)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
```
```
In kernel/trace/power-traces.c (ffffffff811d342c)
Location: include/linux/perf_event.h:1100
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
In kernel/trace/rpm-traces.c (ffffffff811d4bcc)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/bpf/core.c (ffffffff811dba69)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/rseq.c (ffffffff8121f792)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff812208f1)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff81228598)
Location: include/linux/perf_event.h:1100
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
In mm/swap.c (ffffffff812304d4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8123584e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
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
```
```
In mm/percpu.c (ffffffff8124ae34)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff8124e46d)
Location: include/linux/perf_event.h:1100
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
In mm/compaction.c (ffffffff812516ee)
Location: include/linux/perf_event.h:1100
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
In mm/migrate.c (ffffffff812acd72)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff812ba512)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff812cd35e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff812d11be)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff812d8936)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/fs-writeback.c (ffffffff8130e1e8)
Location: include/linux/perf_event.h:1100
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
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
```
```
In fs/dax.c (ffffffff813465fe)
Location: include/linux/perf_event.h:1100
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
In fs/locks.c (ffffffff81352562)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff813d5d9e)
Location: include/linux/perf_event.h:1100
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
In fs/jbd2/journal.c (ffffffff813f7749)
Location: include/linux/perf_event.h:1100
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
In block/blk-core.c (ffffffff814e3137)
Location: include/linux/perf_event.h:1100
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
In block/blk-iocost.c (ffffffff81511542)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_activate
```
```
In block/blk-wbt.c (ffffffff81518faa)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff8155d52e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff81569e2e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff816503ad)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff81679dc7)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff816bbe6e)
Location: include/linux/perf_event.h:1100
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
In drivers/iommu/iommu-traces.c (ffffffff816dc578)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/iommu/intel-trace.c (ffffffff816f115d)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/iommu/intel-trace.c:perf_trace_dma_unmap
  - drivers/iommu/intel-trace.c:perf_trace_dma_map
```
```
In drivers/base/regmap/regmap.c (ffffffff8171f198)
Location: include/linux/perf_event.h:1100
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
In drivers/dma-buf/dma-fence.c (ffffffff81766e13)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81769a1a)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff8176af04)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff8178d498)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff817b2f32)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff817bd8ee)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81848d98)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
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
```
```
In drivers/rtc/interface.c (ffffffff81865eb4)
Location: include/linux/perf_event.h:1100
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
In drivers/i2c/i2c-core-base.c (ffffffff8186bace)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8186f87a)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff818852bc)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff81887290)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff8188be8a)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff818d4239)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff818f1914)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_cmd_class
```
```
In drivers/devfreq/devfreq.c (ffffffff818f9cdf)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/ras/ras.c (ffffffff81900cde)
Location: include/linux/perf_event.h:1100
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
In net/core/net-traces.c (ffffffff819714f3)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
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
```
```
In net/core/devlink.c (ffffffff8197fa25)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/bpf/test_run.c (ffffffff819a38d4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (ffffffff81a4906e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
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
In init/main.c (ffffffff81003265)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/common.c (ffffffff81004bc2)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005e7c)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff8102c205)
Location: include/linux/perf_event.h:1149
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
In arch/x86/hyperv/mmu.c (ffffffff810303e5)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_one
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff810351ce)
Location: include/linux/perf_event.h:1149
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
In arch/x86/kernel/nmi.c (ffffffff81037e19)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81041660)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81050fc4)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81065495)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff810840e5)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff8108676a)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In kernel/fork.c (ffffffff810a364a)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff810a8c3e)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff810aebbc)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810b7309)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810c6845)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_end
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_activate_work
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
```
```
In kernel/sched/core.c (ffffffff810df0b2)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
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
In kernel/printk/printk.c (ffffffff8111d035)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff8112eb71)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff8112fc2c)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff8113ea5b)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffffffff811437f5)
Location: include/linux/perf_event.h:1149
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
In kernel/time/alarmtimer.c (ffffffff8114dee5)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff811641ce)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff8116fa0a)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_event_perf.c (ffffffff811d8716)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/bpf_trace.c (ffffffff811ea360)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
```
```
In kernel/trace/power-traces.c (ffffffff811efe3d)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_cpu_latency_qos_request
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
In kernel/trace/rpm-traces.c (ffffffff811f11df)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/bpf/core.c (ffffffff811f8615)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/rseq.c (ffffffff8124ba5e)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff8124dc98)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff81254f3a)
Location: include/linux/perf_event.h:1149
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
In mm/swap.c (ffffffff8125d780)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81262ed9)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
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
```
```
In mm/percpu.c (ffffffff81278cec)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff8127d88e)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_rss_stat
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
In mm/compaction.c (ffffffff8127fe09)
Location: include/linux/perf_event.h:1149
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
In mm/mmap.c (ffffffff81298349)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - mm/mmap.c:perf_trace_vm_unmapped_area
```
```
In mm/migrate.c (ffffffff812e1e1e)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff812ef12e)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff813035ba)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In fs/fs-writeback.c (ffffffff81347a40)
Location: include/linux/perf_event.h:1149
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
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
```
```
In fs/io_uring.c (ffffffff8137a5ca)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - fs/io_uring.c:perf_trace_io_uring_task_run
  - fs/io_uring.c:perf_trace_io_uring_task_add
  - fs/io_uring.c:perf_trace_io_uring_poll_wake
  - fs/io_uring.c:perf_trace_io_uring_poll_arm
  - fs/io_uring.c:perf_trace_io_uring_submit_sqe
  - fs/io_uring.c:perf_trace_io_uring_complete
  - fs/io_uring.c:perf_trace_io_uring_fail_link
  - fs/io_uring.c:perf_trace_io_uring_cqring_wait
  - fs/io_uring.c:perf_trace_io_uring_link
  - fs/io_uring.c:perf_trace_io_uring_defer
  - fs/io_uring.c:perf_trace_io_uring_queue_async_work
  - fs/io_uring.c:perf_trace_io_uring_file_get
  - fs/io_uring.c:perf_trace_io_uring_register
  - fs/io_uring.c:perf_trace_io_uring_create
```
```
In fs/dax.c (ffffffff8138be0a)
Location: include/linux/perf_event.h:1149
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
In fs/locks.c (ffffffff81398f19)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/iomap/trace.c (ffffffff813a91a7)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - fs/iomap/trace.c:perf_trace_iomap_apply
  - fs/iomap/trace.c:perf_trace_iomap_class
  - fs/iomap/trace.c:perf_trace_iomap_range_class
  - fs/iomap/trace.c:perf_trace_iomap_readpage_class
```
```
In fs/ext4/super.c (ffffffff814224ba)
Location: include/linux/perf_event.h:1149
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
In fs/jbd2/journal.c (ffffffff81444b75)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start_class
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In block/blk-core.c (ffffffff81541b9f)
Location: include/linux/perf_event.h:1149
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
In block/blk-iocost.c (ffffffff81572055)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_activate
```
```
In block/blk-wbt.c (ffffffff815795be)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff815e6e49)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff8160c789)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/pwm/core.c (ffffffff8161ae55)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - drivers/pwm/core.c:perf_trace_pwm
```
```
In drivers/clk/clk.c (ffffffff816fe4ca)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff81728c67)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff817701f9)
Location: include/linux/perf_event.h:1149
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
In drivers/iommu/iommu-traces.c (ffffffff8179148c)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/iommu/intel/trace.c (ffffffff817a8cec)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - drivers/iommu/intel/trace.c:perf_trace_dma_map_sg
  - drivers/iommu/intel/trace.c:perf_trace_dma_unmap
  - drivers/iommu/intel/trace.c:perf_trace_dma_map
```
```
In drivers/base/regmap/regmap.c (ffffffff817dadc0)
Location: include/linux/perf_event.h:1149
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
In drivers/dma-buf/dma-fence.c (ffffffff81826505)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8182bbde)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff8182d1f0)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff81851d10)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff81879456)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff818862f6)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff8191b5c0)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_doorbell
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
```
```
In drivers/rtc/interface.c (ffffffff81939850)
Location: include/linux/perf_event.h:1149
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
In drivers/i2c/i2c-core-base.c (ffffffff8193f7fa)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff819437b2)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff81953801)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff81955681)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff8195aa52)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff819a6829)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff819c7024)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_start
```
```
In drivers/devfreq/devfreq.c (ffffffff819d014a)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/ras/ras.c (ffffffff819d7cf9)
Location: include/linux/perf_event.h:1149
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
In drivers/interconnect/core.c (ffffffff819dd47d)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - drivers/interconnect/core.c:perf_trace_icc_set_bw_end
  - drivers/interconnect/core.c:perf_trace_icc_set_bw
```
```
In net/core/net-traces.c (ffffffff81a44eeb)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:perf_trace_neigh_create
  - net/core/net-traces.c:perf_trace_page_pool_update_nid
  - net/core/net-traces.c:perf_trace_page_pool_state_hold
  - net/core/net-traces.c:perf_trace_page_pool_state_release
  - net/core/net-traces.c:perf_trace_page_pool_release
  - net/core/net-traces.c:perf_trace_br_fdb_update
  - net/core/net-traces.c:perf_trace_fdb_delete
  - net/core/net-traces.c:perf_trace_br_fdb_external_learn_add
  - net/core/net-traces.c:perf_trace_br_fdb_add
  - net/core/net-traces.c:perf_trace_qdisc_create
  - net/core/net-traces.c:perf_trace_qdisc_destroy
  - net/core/net-traces.c:perf_trace_qdisc_reset
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
```
```
In net/core/devlink.c (ffffffff81a51b4e)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/bpf/test_run.c (ffffffff81a7df70)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (ffffffff81b3fb45)
Location: include/linux/perf_event.h:1149
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
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
In init/main.c (ffffffff81003325)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8100502c)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff8102d1b5)
Location: include/linux/perf_event.h:1160
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
In arch/x86/hyperv/mmu.c (ffffffff81031155)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_one
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff810363de)
Location: include/linux/perf_event.h:1160
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
In arch/x86/kernel/nmi.c (ffffffff81038959)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81041700)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81050294)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81063745)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff81085635)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff8108705a)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In kernel/fork.c (ffffffff8109ee6a)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff810a468e)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff810aa38c)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810b2599)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810c18d5)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_end
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_activate_work
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
```
```
In kernel/sched/core.c (ffffffff810da3f0)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
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
  - kernel/sched/core.c:perf_trace_sched_kthread_work_execute_end
  - kernel/sched/core.c:perf_trace_sched_kthread_work_execute_start
  - kernel/sched/core.c:perf_trace_sched_kthread_work_queue_work
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
```
```
In kernel/printk/printk.c (ffffffff81117b05)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff8112ab51)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff8112ba8c)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff8113a0cb)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/entry/common.c (ffffffff8113b202)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - kernel/entry/common.c:perf_trace_sys_exit
  - kernel/entry/common.c:perf_trace_sys_enter
```
```
In kernel/time/timer.c (ffffffff8113fe65)
Location: include/linux/perf_event.h:1160
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
In kernel/time/alarmtimer.c (ffffffff8114a175)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff8116015e)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff8116c4ba)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_event_perf.c (ffffffff811d576e)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/bpf_trace.c (ffffffff811e8330)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:perf_trace_bpf_trace_printk
```
```
In kernel/trace/power-traces.c (ffffffff811ee6dd)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_cpu_latency_qos_request
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
In kernel/trace/rpm-traces.c (ffffffff811efc0f)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/bpf/core.c (ffffffff811f7605)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/rseq.c (ffffffff81255eee)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff812581e8)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff8125fc0a)
Location: include/linux/perf_event.h:1160
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
In mm/swap.c (ffffffff81267bc0)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8126d869)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
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
```
```
In mm/percpu.c (ffffffff8128355c)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff8128805e)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_rss_stat
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
In mm/compaction.c (ffffffff81289ea9)
Location: include/linux/perf_event.h:1160
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
In mm/mmap_lock.c (ffffffff8129646e)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - mm/mmap_lock.c:perf_trace_mmap_lock_released
  - mm/mmap_lock.c:perf_trace_mmap_lock_acquire_returned
  - mm/mmap_lock.c:perf_trace_mmap_lock_start_locking
```
```
In mm/mmap.c (ffffffff812a34f9)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - mm/mmap.c:perf_trace_vm_unmapped_area
```
```
In mm/migrate.c (ffffffff812ecd12)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff812fa8fe)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff8130f4ea)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In fs/fs-writeback.c (ffffffff81354c50)
Location: include/linux/perf_event.h:1160
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
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
```
```
In fs/io_uring.c (ffffffff8138889a)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - fs/io_uring.c:perf_trace_io_uring_task_run
  - fs/io_uring.c:perf_trace_io_uring_task_add
  - fs/io_uring.c:perf_trace_io_uring_poll_wake
  - fs/io_uring.c:perf_trace_io_uring_poll_arm
  - fs/io_uring.c:perf_trace_io_uring_submit_sqe
  - fs/io_uring.c:perf_trace_io_uring_complete
  - fs/io_uring.c:perf_trace_io_uring_fail_link
  - fs/io_uring.c:perf_trace_io_uring_cqring_wait
  - fs/io_uring.c:perf_trace_io_uring_link
  - fs/io_uring.c:perf_trace_io_uring_defer
  - fs/io_uring.c:perf_trace_io_uring_queue_async_work
  - fs/io_uring.c:perf_trace_io_uring_file_get
  - fs/io_uring.c:perf_trace_io_uring_register
  - fs/io_uring.c:perf_trace_io_uring_create
```
```
In fs/dax.c (ffffffff8139d53a)
Location: include/linux/perf_event.h:1160
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
In fs/locks.c (ffffffff813aa9f9)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/iomap/trace.c (ffffffff813ba847)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - fs/iomap/trace.c:perf_trace_iomap_apply
  - fs/iomap/trace.c:perf_trace_iomap_class
  - fs/iomap/trace.c:perf_trace_iomap_range_class
  - fs/iomap/trace.c:perf_trace_iomap_readpage_class
```
```
In fs/ext4/super.c (ffffffff814396be)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_fc_track_range
  - fs/ext4/super.c:perf_trace_ext4_fc_track_inode
  - fs/ext4/super.c:perf_trace_ext4_fc_track_unlink
  - fs/ext4/super.c:perf_trace_ext4_fc_track_link
  - fs/ext4/super.c:perf_trace_ext4_fc_track_create
  - fs/ext4/super.c:perf_trace_ext4_fc_stats
  - fs/ext4/super.c:perf_trace_ext4_fc_commit_stop
  - fs/ext4/super.c:perf_trace_ext4_fc_commit_start
  - fs/ext4/super.c:perf_trace_ext4_fc_replay
  - fs/ext4/super.c:perf_trace_ext4_fc_replay_scan
  - fs/ext4/super.c:perf_trace_ext4_lazy_itable_init
  - fs/ext4/super.c:perf_trace_ext4_prefetch_bitmaps
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
  - fs/ext4/super.c:perf_trace_ext4_read_block_bitmap_load
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
In fs/jbd2/journal.c (ffffffff81461235)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start_class
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In security/selinux/avc.c (ffffffff814cafaf)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - security/selinux/avc.c:perf_trace_selinux_audited
```
```
In block/blk-core.c (ffffffff8155e68f)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_bio
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_buffer
```
```
In block/blk-iocost.c (ffffffff8158e958)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_iocg_forgive_debt
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_state
```
```
In block/blk-wbt.c (ffffffff81596372)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff8160c0b9)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff81633559)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/pwm/core.c (ffffffff816415d5)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - drivers/pwm/core.c:perf_trace_pwm
```
```
In drivers/clk/clk.c (ffffffff8171b80a)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate_range
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff81745817)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff8178b21c)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - drivers/char/random.c:perf_trace_prandom_u32
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
In drivers/iommu/intel/trace.c (ffffffff817b4c0c)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - drivers/iommu/intel/trace.c:perf_trace_dma_map_sg
  - drivers/iommu/intel/trace.c:perf_trace_dma_unmap
  - drivers/iommu/intel/trace.c:perf_trace_dma_map
```
```
In drivers/iommu/iommu-traces.c (ffffffff817bd6bc)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff817eff90)
Location: include/linux/perf_event.h:1160
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
In drivers/dma-buf/dma-fence.c (ffffffff81837025)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8183caf0)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff8183e230)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff81862070)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff81887cc6)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81894786)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81922c30)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_doorbell
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
```
```
In drivers/rtc/interface.c (ffffffff8193fcb0)
Location: include/linux/perf_event.h:1160
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
In drivers/i2c/i2c-core-base.c (ffffffff8194598a)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81949832)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff81958621)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff8195b0b3)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff819616e2)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff819a98d9)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff819c6e94)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_start
```
```
In drivers/devfreq/devfreq.c (ffffffff819d076a)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_frequency
```
```
In drivers/ras/ras.c (ffffffff819d70a9)
Location: include/linux/perf_event.h:1160
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
In drivers/interconnect/core.c (ffffffff819dcced)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - drivers/interconnect/core.c:perf_trace_icc_set_bw_end
  - drivers/interconnect/core.c:perf_trace_icc_set_bw
```
```
In net/core/net-traces.c (ffffffff81a48fe4)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:perf_trace_neigh_create
  - net/core/net-traces.c:perf_trace_page_pool_update_nid
  - net/core/net-traces.c:perf_trace_page_pool_state_hold
  - net/core/net-traces.c:perf_trace_page_pool_state_release
  - net/core/net-traces.c:perf_trace_page_pool_release
  - net/core/net-traces.c:perf_trace_br_fdb_update
  - net/core/net-traces.c:perf_trace_fdb_delete
  - net/core/net-traces.c:perf_trace_br_fdb_external_learn_add
  - net/core/net-traces.c:perf_trace_br_fdb_add
  - net/core/net-traces.c:perf_trace_qdisc_create
  - net/core/net-traces.c:perf_trace_qdisc_destroy
  - net/core/net-traces.c:perf_trace_qdisc_reset
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
```
```
In net/core/devlink.c (ffffffff81a57e6e)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_trap_report
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/bpf/test_run.c (ffffffff81a87600)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (ffffffff81b4e605)
Location: include/linux/perf_event.h:1160
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
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
In init/main.c (ffffffff81003325)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004fcc)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff8102dcc5)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_gdt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_load_idt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_multi
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_one_user
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_alloc_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pmd
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
In arch/x86/hyperv/mmu.c (ffffffff81031cb5)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_one
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_multi
```
```
In arch/x86/kernel/irq.c (ffffffff81037dfe)
Location: include/linux/perf_event.h:1161
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
In arch/x86/kernel/nmi.c (ffffffff8103a469)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81043100)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81051db4)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81063ec5)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff81086335)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff81087c7a)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In kernel/fork.c (ffffffff8109fd2a)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff810a533e)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff810ab3cc)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810b3bc9)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810c31b5)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_end
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_activate_work
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
```
```
In kernel/sched/core.c (ffffffff810dca5f)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
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
  - kernel/sched/core.c:perf_trace_sched_kthread_work_execute_end
  - kernel/sched/core.c:perf_trace_sched_kthread_work_execute_start
  - kernel/sched/core.c:perf_trace_sched_kthread_work_queue_work
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
```
```
In kernel/printk/printk.c (ffffffff811181e5)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff8112add1)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff8112be95)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_stall_warning
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff8113b61b)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/entry/common.c (ffffffff8113c4f2)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - kernel/entry/common.c:perf_trace_sys_exit
  - kernel/entry/common.c:perf_trace_sys_enter
```
```
In kernel/time/timer.c (ffffffff81141065)
Location: include/linux/perf_event.h:1161
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
In kernel/time/alarmtimer.c (ffffffff8114b635)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff8116102e)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff8116d11a)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_event_perf.c (ffffffff811d6c8e)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/bpf_trace.c (ffffffff811e911d)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:perf_trace_bpf_trace_printk
```
```
In kernel/trace/error_report-traces.c (ffffffff811ed835)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - kernel/trace/error_report-traces.c:perf_trace_error_report_template
```
```
In kernel/trace/power-traces.c (ffffffff811ef62d)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_cpu_latency_qos_request
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
In kernel/trace/rpm-traces.c (ffffffff811f0b3f)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/bpf/core.c (ffffffff811f8455)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/rseq.c (ffffffff8125a4ae)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff8125c7c8)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff81264756)
Location: include/linux/perf_event.h:1161
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
In mm/swap.c (ffffffff8126c7c0)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff812725a9)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
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
```
```
In mm/percpu.c (ffffffff8128865c)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff8128d3fe)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_rss_stat
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_cache_free
  - mm/slab_common.c:perf_trace_kfree
  - mm/slab_common.c:perf_trace_kmem_alloc_node
  - mm/slab_common.c:perf_trace_kmem_alloc
```
```
In mm/compaction.c (ffffffff8128f519)
Location: include/linux/perf_event.h:1161
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
In mm/mmap_lock.c (ffffffff8129be0e)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - mm/mmap_lock.c:perf_trace_mmap_lock_released
  - mm/mmap_lock.c:perf_trace_mmap_lock_acquire_returned
  - mm/mmap_lock.c:perf_trace_mmap_lock_start_locking
```
```
In mm/mmap.c (ffffffff812a8d39)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - mm/mmap.c:perf_trace_vm_unmapped_area
```
```
In mm/migrate.c (ffffffff812f2fe5)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages_start
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff813016be)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff8131583a)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In fs/fs-writeback.c (ffffffff8135b8f0)
Location: include/linux/perf_event.h:1161
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
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
```
```
In fs/io_uring.c (ffffffff8138f9ba)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - fs/io_uring.c:perf_trace_io_uring_task_run
  - fs/io_uring.c:perf_trace_io_uring_task_add
  - fs/io_uring.c:perf_trace_io_uring_poll_wake
  - fs/io_uring.c:perf_trace_io_uring_poll_arm
  - fs/io_uring.c:perf_trace_io_uring_submit_sqe
  - fs/io_uring.c:perf_trace_io_uring_complete
  - fs/io_uring.c:perf_trace_io_uring_fail_link
  - fs/io_uring.c:perf_trace_io_uring_cqring_wait
  - fs/io_uring.c:perf_trace_io_uring_link
  - fs/io_uring.c:perf_trace_io_uring_defer
  - fs/io_uring.c:perf_trace_io_uring_queue_async_work
  - fs/io_uring.c:perf_trace_io_uring_file_get
  - fs/io_uring.c:perf_trace_io_uring_register
  - fs/io_uring.c:perf_trace_io_uring_create
```
```
In fs/dax.c (ffffffff813a474a)
Location: include/linux/perf_event.h:1161
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
In fs/locks.c (ffffffff813b1ec9)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/iomap/trace.c (ffffffff813c1967)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - fs/iomap/trace.c:perf_trace_iomap_apply
  - fs/iomap/trace.c:perf_trace_iomap_class
  - fs/iomap/trace.c:perf_trace_iomap_range_class
  - fs/iomap/trace.c:perf_trace_iomap_readpage_class
```
```
In fs/ext4/super.c (ffffffff8143f86e)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_fc_track_range
  - fs/ext4/super.c:perf_trace_ext4_fc_track_inode
  - fs/ext4/super.c:perf_trace_ext4_fc_track_unlink
  - fs/ext4/super.c:perf_trace_ext4_fc_track_link
  - fs/ext4/super.c:perf_trace_ext4_fc_track_create
  - fs/ext4/super.c:perf_trace_ext4_fc_stats
  - fs/ext4/super.c:perf_trace_ext4_fc_commit_stop
  - fs/ext4/super.c:perf_trace_ext4_fc_commit_start
  - fs/ext4/super.c:perf_trace_ext4_fc_replay
  - fs/ext4/super.c:perf_trace_ext4_fc_replay_scan
  - fs/ext4/super.c:perf_trace_ext4_lazy_itable_init
  - fs/ext4/super.c:perf_trace_ext4_prefetch_bitmaps
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
  - fs/ext4/super.c:perf_trace_ext4_read_block_bitmap_load
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
In fs/jbd2/journal.c (ffffffff814669e5)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start_class
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In security/selinux/avc.c (ffffffff814d15df)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - security/selinux/avc.c:perf_trace_selinux_audited
```
```
In block/blk-core.c (ffffffff81566edf)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_bio
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_buffer
```
```
In block/blk-iocost.c (ffffffff815956b3)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_iocg_forgive_debt
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_state
```
```
In block/blk-wbt.c (ffffffff8159d1b2)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff815ef3d9)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff81617249)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/pwm/core.c (ffffffff81624515)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - drivers/pwm/core.c:perf_trace_pwm
```
```
In drivers/clk/clk.c (ffffffff816fc8ea)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate_range
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff81729227)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff8176e5ec)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - drivers/char/random.c:perf_trace_prandom_u32
  - drivers/char/random.c:perf_trace_urandom_read
  - drivers/char/random.c:perf_trace_random__extract_entropy
  - drivers/char/random.c:perf_trace_random__get_random_bytes
  - drivers/char/random.c:perf_trace_add_disk_randomness
  - drivers/char/random.c:perf_trace_add_input_randomness
  - drivers/char/random.c:perf_trace_debit_entropy
  - drivers/char/random.c:perf_trace_credit_entropy_bits
  - drivers/char/random.c:perf_trace_random__mix_pool_bytes
  - drivers/char/random.c:perf_trace_add_device_randomness
```
```
In drivers/iommu/intel/trace.c (ffffffff81797902)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - drivers/iommu/intel/trace.c:perf_trace_qi_submit
```
```
In drivers/iommu/iommu-traces.c (ffffffff817a08fc)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff817d49d0)
Location: include/linux/perf_event.h:1161
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
In drivers/dma-buf/dma-fence.c (ffffffff8181a1e5)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8181fc99)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff818213d0)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff81844e40)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff8186a525)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81877086)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81906340)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_doorbell
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
```
```
In drivers/rtc/interface.c (ffffffff81923450)
Location: include/linux/perf_event.h:1161
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
In drivers/i2c/i2c-core-base.c (ffffffff8192915a)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8192d132)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff8193c7bd)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff8193dfff)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81944b32)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff8198e599)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff819abde4)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_start
```
```
In drivers/devfreq/devfreq.c (ffffffff819b59da)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_frequency
```
```
In drivers/ras/ras.c (ffffffff819bd219)
Location: include/linux/perf_event.h:1161
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
In drivers/interconnect/core.c (ffffffff819c2f3f)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - drivers/interconnect/core.c:perf_trace_icc_set_bw_end
  - drivers/interconnect/core.c:perf_trace_icc_set_bw
```
```
In net/core/net-traces.c (ffffffff81a2df30)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:perf_trace_neigh_create
  - net/core/net-traces.c:perf_trace_page_pool_update_nid
  - net/core/net-traces.c:perf_trace_page_pool_state_hold
  - net/core/net-traces.c:perf_trace_page_pool_state_release
  - net/core/net-traces.c:perf_trace_page_pool_release
  - net/core/net-traces.c:perf_trace_br_fdb_update
  - net/core/net-traces.c:perf_trace_fdb_delete
  - net/core/net-traces.c:perf_trace_br_fdb_external_learn_add
  - net/core/net-traces.c:perf_trace_br_fdb_add
  - net/core/net-traces.c:perf_trace_qdisc_create
  - net/core/net-traces.c:perf_trace_qdisc_destroy
  - net/core/net-traces.c:perf_trace_qdisc_reset
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
```
```
In net/core/devlink.c (ffffffff81a3ab5e)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_trap_report
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/netlink/af_netlink.c (ffffffff81a691ee)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:perf_trace_netlink_extack
```
```
In net/bpf/test_run.c (ffffffff81a706d0)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (ffffffff81b3c465)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/mptcp/protocol.c (ffffffff81ba9fc5)
Location: include/linux/perf_event.h:1161
Inline: True
Inline callers:
  - net/mptcp/protocol.c:perf_trace_subflow_check_data_avail
  - net/mptcp/protocol.c:perf_trace_ack_update_msk
  - net/mptcp/protocol.c:perf_trace_mptcp_dump_mpext
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
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
In init/main.c (ffffffff81003365)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810055dc)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff81032575)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_gdt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_load_idt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_multi
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_one_user
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_alloc_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pmd
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
In arch/x86/hyperv/mmu.c (ffffffff81036e35)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_one
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_multi
```
```
In arch/x86/kernel/irq.c (ffffffff8103d0ae)
Location: include/linux/perf_event.h:1155
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
In arch/x86/kernel/nmi.c (ffffffff8103fe19)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81049470)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105a244)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106deb5)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff81095545)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff81096ffa)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In kernel/fork.c (ffffffff810b117a)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff810b6b5e)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff810bceec)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810c5dd9)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810d5cf5)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_end
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_activate_work
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
```
```
In kernel/sched/core.c (ffffffff810f157f)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
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
  - kernel/sched/core.c:perf_trace_sched_kthread_work_execute_end
  - kernel/sched/core.c:perf_trace_sched_kthread_work_execute_start
  - kernel/sched/core.c:perf_trace_sched_kthread_work_queue_work
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
```
```
In kernel/printk/printk.c (ffffffff811384e5)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff8114b87f)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff8114ca25)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_stall_warning
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff8115e75b)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/entry/common.c (ffffffff8115f612)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - kernel/entry/common.c:perf_trace_sys_exit
  - kernel/entry/common.c:perf_trace_sys_enter
```
```
In kernel/time/timer.c (ffffffff81164525)
Location: include/linux/perf_event.h:1155
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
In kernel/time/alarmtimer.c (ffffffff8116f315)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff811861fe)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff81192dfa)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_event_perf.c (ffffffff81203be0)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/bpf_trace.c (ffffffff81219b9d)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:perf_trace_bpf_trace_printk
```
```
In kernel/trace/error_report-traces.c (ffffffff8121e8a5)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - kernel/trace/error_report-traces.c:perf_trace_error_report_template
```
```
In kernel/trace/power-traces.c (ffffffff812206bd)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_cpu_latency_qos_request
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
In kernel/trace/rpm-traces.c (ffffffff81221bdf)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/bpf/core.c (ffffffff81229a35)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/rseq.c (ffffffff8129629e)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff81298688)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff812a0f76)
Location: include/linux/perf_event.h:1155
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
In mm/swap.c (ffffffff812a94e0)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff812af979)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_node_reclaim_begin
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
In mm/percpu.c (ffffffff812c7d9c)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff812cd23e)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_rss_stat
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_cache_free
  - mm/slab_common.c:perf_trace_kfree
  - mm/slab_common.c:perf_trace_kmem_alloc_node
  - mm/slab_common.c:perf_trace_kmem_alloc
```
```
In mm/compaction.c (ffffffff812cf3c9)
Location: include/linux/perf_event.h:1155
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
In mm/mmap_lock.c (ffffffff812dc90e)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - mm/mmap_lock.c:perf_trace_mmap_lock_released
  - mm/mmap_lock.c:perf_trace_mmap_lock_acquire_returned
  - mm/mmap_lock.c:perf_trace_mmap_lock_start_locking
```
```
In mm/mmap.c (ffffffff812ea3a9)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - mm/mmap.c:perf_trace_vm_unmapped_area
```
```
In mm/migrate.c (ffffffff8133d455)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages_start
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff8134b3be)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff813618ea)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In fs/fs-writeback.c (ffffffff813a9d90)
Location: include/linux/perf_event.h:1155
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
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
```
```
In fs/io_uring.c (ffffffff813dd27e)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - fs/io_uring.c:perf_trace_io_uring_task_run
  - fs/io_uring.c:perf_trace_io_uring_task_add
  - fs/io_uring.c:perf_trace_io_uring_poll_wake
  - fs/io_uring.c:perf_trace_io_uring_poll_arm
  - fs/io_uring.c:perf_trace_io_uring_submit_sqe
  - fs/io_uring.c:perf_trace_io_uring_complete
  - fs/io_uring.c:perf_trace_io_uring_fail_link
  - fs/io_uring.c:perf_trace_io_uring_cqring_wait
  - fs/io_uring.c:perf_trace_io_uring_link
  - fs/io_uring.c:perf_trace_io_uring_defer
  - fs/io_uring.c:perf_trace_io_uring_queue_async_work
  - fs/io_uring.c:perf_trace_io_uring_file_get
  - fs/io_uring.c:perf_trace_io_uring_register
  - fs/io_uring.c:perf_trace_io_uring_create
```
```
In fs/dax.c (ffffffff813f406a)
Location: include/linux/perf_event.h:1155
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
In fs/locks.c (ffffffff81401bb9)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/iomap/trace.c (ffffffff81411b6e)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - fs/iomap/trace.c:perf_trace_iomap_iter
  - fs/iomap/trace.c:perf_trace_iomap_class
  - fs/iomap/trace.c:perf_trace_iomap_range_class
  - fs/iomap/trace.c:perf_trace_iomap_readpage_class
```
```
In fs/ext4/super.c (ffffffff814934fe)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_fc_track_range
  - fs/ext4/super.c:perf_trace_ext4_fc_track_inode
  - fs/ext4/super.c:perf_trace_ext4_fc_track_unlink
  - fs/ext4/super.c:perf_trace_ext4_fc_track_link
  - fs/ext4/super.c:perf_trace_ext4_fc_track_create
  - fs/ext4/super.c:perf_trace_ext4_fc_stats
  - fs/ext4/super.c:perf_trace_ext4_fc_commit_stop
  - fs/ext4/super.c:perf_trace_ext4_fc_commit_start
  - fs/ext4/super.c:perf_trace_ext4_fc_replay
  - fs/ext4/super.c:perf_trace_ext4_fc_replay_scan
  - fs/ext4/super.c:perf_trace_ext4_lazy_itable_init
  - fs/ext4/super.c:perf_trace_ext4_prefetch_bitmaps
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
  - fs/ext4/super.c:perf_trace_ext4_read_block_bitmap_load
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
In fs/jbd2/journal.c (ffffffff814bc792)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_shrink_checkpoint_list
  - fs/jbd2/journal.c:perf_trace_jbd2_shrink_scan_exit
  - fs/jbd2/journal.c:perf_trace_jbd2_journal_shrink
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start_class
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In security/selinux/avc.c (ffffffff8152a32f)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - security/selinux/avc.c:perf_trace_selinux_audited
```
```
In block/blk-core.c (ffffffff815cb45f)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_bio
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_buffer
```
```
In block/blk-iocost.c (ffffffff815fcc2a)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_iocg_forgive_debt
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_state
```
```
In block/blk-wbt.c (ffffffff81605862)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff8165c4e9)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff816864c9)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/pwm/core.c (ffffffff81693ff2)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - drivers/pwm/core.c:perf_trace_pwm
```
```
In drivers/clk/clk.c (ffffffff81776b6a)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate_range
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff817a8547)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff817f3dbc)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - drivers/char/random.c:perf_trace_prandom_u32
  - drivers/char/random.c:perf_trace_urandom_read
  - drivers/char/random.c:perf_trace_random__extract_entropy
  - drivers/char/random.c:perf_trace_random__get_random_bytes
  - drivers/char/random.c:perf_trace_add_disk_randomness
  - drivers/char/random.c:perf_trace_add_input_randomness
  - drivers/char/random.c:perf_trace_debit_entropy
  - drivers/char/random.c:perf_trace_credit_entropy_bits
  - drivers/char/random.c:perf_trace_random__mix_pool_bytes
  - drivers/char/random.c:perf_trace_add_device_randomness
```
```
In drivers/iommu/intel/trace.c (ffffffff818200dc)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - drivers/iommu/intel/trace.c:perf_trace_prq_report
  - drivers/iommu/intel/trace.c:perf_trace_qi_submit
```
```
In drivers/iommu/iommu-traces.c (ffffffff818298fc)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff8185fba0)
Location: include/linux/perf_event.h:1155
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
In drivers/base/trace.c (ffffffff8186be4c)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - drivers/base/trace.c:perf_trace_devres
```
```
In drivers/dma-buf/dma-fence.c (ffffffff818a4695)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff818aa359)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff818abd20)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff818d18c0)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff818fa895)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_set_cs
  - drivers/spi/spi.c:perf_trace_spi_setup
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81907d96)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff819a6b70)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_doorbell
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
```
```
In drivers/rtc/interface.c (ffffffff819c6400)
Location: include/linux/perf_event.h:1155
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
In drivers/i2c/i2c-core-base.c (ffffffff819cc2aa)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff819d0342)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff819e105d)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff819e28bf)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff819e9562)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff81a39c29)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff81a59dae)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_sensorhub_filter
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_sensorhub_data
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_sensorhub_timestamp
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_start
```
```
In drivers/devfreq/devfreq.c (ffffffff81a6453a)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_frequency
```
```
In drivers/ras/ras.c (ffffffff81a6c7a9)
Location: include/linux/perf_event.h:1155
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
In drivers/interconnect/core.c (ffffffff81a727df)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - drivers/interconnect/core.c:perf_trace_icc_set_bw_end
  - drivers/interconnect/core.c:perf_trace_icc_set_bw
```
```
In net/core/net-traces.c (ffffffff81ae3510)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:perf_trace_neigh_create
  - net/core/net-traces.c:perf_trace_page_pool_update_nid
  - net/core/net-traces.c:perf_trace_page_pool_state_hold
  - net/core/net-traces.c:perf_trace_page_pool_state_release
  - net/core/net-traces.c:perf_trace_page_pool_release
  - net/core/net-traces.c:perf_trace_br_fdb_update
  - net/core/net-traces.c:perf_trace_fdb_delete
  - net/core/net-traces.c:perf_trace_br_fdb_external_learn_add
  - net/core/net-traces.c:perf_trace_br_fdb_add
  - net/core/net-traces.c:perf_trace_qdisc_create
  - net/core/net-traces.c:perf_trace_qdisc_destroy
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:perf_trace_qdisc_enqueue
  - net/core/net-traces.c:perf_trace_qdisc_dequeue
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_inet_sk_error_report
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
```
```
In net/core/devlink.c (ffffffff81af0ebe)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_trap_report
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/netlink/af_netlink.c (ffffffff81b2279e)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:perf_trace_netlink_extack
```
```
In net/bpf/test_run.c (ffffffff81b29e20)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (ffffffff81c02d55)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/mptcp/protocol.c (ffffffff81c77345)
Location: include/linux/perf_event.h:1155
Inline: True
Inline callers:
  - net/mptcp/protocol.c:perf_trace_subflow_check_data_avail
  - net/mptcp/protocol.c:perf_trace_ack_update_msk
  - net/mptcp/protocol.c:perf_trace_mptcp_dump_mpext
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
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
In init/main.c (ffffffff81000fd4)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8100473f)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff81038054)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_gdt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_load_idt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_multi
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_one_user
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_alloc_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pmd
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
In arch/x86/hyperv/mmu.c (ffffffff8103cf04)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_one
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_multi
```
```
In arch/x86/kernel/irq.c (ffffffff810444bd)
Location: include/linux/perf_event.h:1185
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
In arch/x86/kernel/nmi.c (ffffffff81047608)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8105260f)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81066a03)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107b524)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/fault.c (ffffffff810a9af9)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In kernel/fork.c (ffffffff810c73ee)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff810cd10d)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff810d3dcf)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810dd3e9)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810ef294)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_end
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_activate_work
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
```
```
In kernel/sched/core.c (ffffffff8110d991)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
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
  - kernel/sched/core.c:perf_trace_sched_kthread_work_execute_end
  - kernel/sched/core.c:perf_trace_sched_kthread_work_execute_start
  - kernel/sched/core.c:perf_trace_sched_kthread_work_queue_work
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
```
```
In kernel/locking/mutex.c (ffffffff8114d664)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - kernel/locking/mutex.c:perf_trace_contention_end
  - kernel/locking/mutex.c:perf_trace_contention_begin
```
```
In kernel/printk/printk.c (ffffffff8115ada2)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff811711fe)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff81172594)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_stall_warning
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff81188344)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/entry/common.c (ffffffff81189a55)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - kernel/entry/common.c:perf_trace_sys_exit
  - kernel/entry/common.c:perf_trace_sys_enter
```
```
In kernel/module/main.c (ffffffff8118b9df)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - kernel/module/main.c:perf_trace_module_request
  - kernel/module/main.c:perf_trace_module_refcnt
  - kernel/module/main.c:perf_trace_module_free
  - kernel/module/main.c:perf_trace_module_load
```
```
In kernel/time/timer.c (ffffffff811977a4)
Location: include/linux/perf_event.h:1185
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
In kernel/time/alarmtimer.c (ffffffff811a36f4)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/cgroup/cgroup.c (ffffffff811c251c)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_event_perf.c (ffffffff8123efdb)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/bpf_trace.c (ffffffff81258321)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:perf_trace_bpf_trace_printk
```
```
In kernel/trace/error_report-traces.c (ffffffff8125df34)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - kernel/trace/error_report-traces.c:perf_trace_error_report_template
```
```
In kernel/trace/power-traces.c (ffffffff8125fd9a)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_cpu_latency_qos_request
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
In kernel/trace/rpm-traces.c (ffffffff812615e1)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/bpf/core.c (ffffffff8126ac24)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/rseq.c (ffffffff812ec0dd)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff812eeb57)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff812f8749)
Location: include/linux/perf_event.h:1185
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
In mm/swap.c (ffffffff813028cf)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8130b65d)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_throttled
  - mm/vmscan.c:perf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:perf_trace_mm_vmscan_write_folio
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
In mm/percpu.c (ffffffff813252af)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff8132ac8d)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_rss_stat
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_cache_free
  - mm/slab_common.c:perf_trace_kfree
  - mm/slab_common.c:perf_trace_kmem_alloc_node
  - mm/slab_common.c:perf_trace_kmem_alloc
```
```
In mm/compaction.c (ffffffff8132d638)
Location: include/linux/perf_event.h:1185
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
In mm/mmap_lock.c (ffffffff8133c034)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - mm/mmap_lock.c:perf_trace_mmap_lock_acquire_returned
  - mm/mmap_lock.c:perf_trace_mmap_lock
```
```
In mm/mmap.c (ffffffff8134cf68)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - mm/mmap.c:perf_trace_vm_unmapped_area
```
```
In mm/rmap.c (ffffffff8135a8c8)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - mm/rmap.c:perf_trace_migration_pte
  - mm/rmap.c:perf_trace_mm_migrate_pages_start
  - mm/rmap.c:perf_trace_mm_migrate_pages
  - mm/rmap.c:perf_trace_tlb_flush
```
```
In mm/huge_memory.c (ffffffff813b8a04)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - mm/huge_memory.c:perf_trace_migration_pmd
  - mm/huge_memory.c:perf_trace_hugepage_update
  - mm/huge_memory.c:perf_trace_hugepage_set_pmd
```
```
In mm/khugepaged.c (ffffffff813c272d)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff813dd879)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In fs/fs-writeback.c (ffffffff8142f21f)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
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
  - fs/fs-writeback.c:perf_trace_writeback_folio_template
```
```
In fs/dax.c (ffffffff814668e9)
Location: include/linux/perf_event.h:1185
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
In fs/locks.c (ffffffff81475fa9)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/iomap/trace.c (ffffffff8148727d)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - fs/iomap/trace.c:perf_trace_iomap_iter
  - fs/iomap/trace.c:perf_trace_iomap_class
  - fs/iomap/trace.c:perf_trace_iomap_range_class
  - fs/iomap/trace.c:perf_trace_iomap_readpage_class
```
```
In fs/ext4/super.c (ffffffff815186c9)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_update_sb
  - fs/ext4/super.c:perf_trace_ext4_fc_cleanup
  - fs/ext4/super.c:perf_trace_ext4_fc_track_range
  - fs/ext4/super.c:perf_trace_ext4_fc_track_inode
  - fs/ext4/super.c:perf_trace_ext4_fc_track_dentry
  - fs/ext4/super.c:perf_trace_ext4_fc_stats
  - fs/ext4/super.c:perf_trace_ext4_fc_commit_stop
  - fs/ext4/super.c:perf_trace_ext4_fc_commit_start
  - fs/ext4/super.c:perf_trace_ext4_fc_replay
  - fs/ext4/super.c:perf_trace_ext4_fc_replay_scan
  - fs/ext4/super.c:perf_trace_ext4_lazy_itable_init
  - fs/ext4/super.c:perf_trace_ext4_prefetch_bitmaps
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
  - fs/ext4/super.c:perf_trace_ext4_read_block_bitmap_load
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
  - fs/ext4/super.c:perf_trace_ext4_invalidate_folio_op
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
In fs/jbd2/journal.c (ffffffff81546ad1)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_shrink_checkpoint_list
  - fs/jbd2/journal.c:perf_trace_jbd2_shrink_scan_exit
  - fs/jbd2/journal.c:perf_trace_jbd2_journal_shrink
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start_class
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In security/selinux/avc.c (ffffffff815bff6a)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - security/selinux/avc.c:perf_trace_selinux_audited
```
```
In block/blk-core.c (ffffffff8167731e)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_bio
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_completion
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_buffer
```
```
In block/blk-iocost.c (ffffffff816ad1fe)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_iocg_forgive_debt
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_state
```
```
In block/blk-wbt.c (ffffffff816b9101)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In io_uring/io_uring.c (ffffffff816c5ac1)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - io_uring/io_uring.c:perf_trace_io_uring_cqe_overflow
  - io_uring/io_uring.c:perf_trace_io_uring_req_failed
  - io_uring/io_uring.c:perf_trace_io_uring_task_add
  - io_uring/io_uring.c:perf_trace_io_uring_poll_arm
  - io_uring/io_uring.c:perf_trace_io_uring_submit_sqe
  - io_uring/io_uring.c:perf_trace_io_uring_complete
  - io_uring/io_uring.c:perf_trace_io_uring_fail_link
  - io_uring/io_uring.c:perf_trace_io_uring_cqring_wait
  - io_uring/io_uring.c:perf_trace_io_uring_link
  - io_uring/io_uring.c:perf_trace_io_uring_defer
  - io_uring/io_uring.c:perf_trace_io_uring_queue_async_work
  - io_uring/io_uring.c:perf_trace_io_uring_file_get
  - io_uring/io_uring.c:perf_trace_io_uring_register
  - io_uring/io_uring.c:perf_trace_io_uring_create
```
```
In arch/x86/lib/msr.c (ffffffff817755a8)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff817a2ed8)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/pwm/core.c (ffffffff817b4cc6)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - drivers/pwm/core.c:perf_trace_pwm
```
```
In drivers/clk/clk.c (ffffffff818ab910)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate_range
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff818e1e40)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/iommu/intel/trace.c (ffffffff8195fbe5)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - drivers/iommu/intel/trace.c:perf_trace_prq_report
  - drivers/iommu/intel/trace.c:perf_trace_qi_submit
```
```
In drivers/iommu/iommu-traces.c (ffffffff819697a5)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff819a6d22)
Location: include/linux/perf_event.h:1185
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
In drivers/base/trace.c (ffffffff819b4ade)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - drivers/base/trace.c:perf_trace_devres
```
```
In drivers/dma-buf/dma-fence.c (ffffffff819ee00c)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff819f43f5)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff819f669f)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff81a204ef)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_sff_template
  - drivers/ata/libata-core.c:perf_trace_ata_transfer_data_template
  - drivers/ata/libata-core.c:perf_trace_ata_sff_hsm_template
  - drivers/ata/libata-core.c:perf_trace_ata_port_eh_begin_template
  - drivers/ata/libata-core.c:perf_trace_ata_link_reset_end_template
  - drivers/ata/libata-core.c:perf_trace_ata_link_reset_begin_template
  - drivers/ata/libata-core.c:perf_trace_ata_eh_action_template
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_bmdma_status
  - drivers/ata/libata-core.c:perf_trace_ata_exec_command_template
  - drivers/ata/libata-core.c:perf_trace_ata_tf_load
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue_template
```
```
In drivers/spi/spi.c (ffffffff81a48b8a)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_set_cs
  - drivers/spi/spi.c:perf_trace_spi_setup
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81a5aeb1)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81b0496f)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_doorbell
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
```
```
In drivers/rtc/interface.c (ffffffff81b26d1f)
Location: include/linux/perf_event.h:1185
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
In drivers/i2c/i2c-core-base.c (ffffffff81b2db19)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81b32311)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff81b44cc6)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff81b472b6)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81b4f190)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/cpufreq/amd-pstate-trace.c (ffffffff81b978b1)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate-trace.c:perf_trace_amd_pstate_perf
```
```
In drivers/mmc/core/core.c (ffffffff81ba4f98)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff81bc98a4)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_start
```
```
In drivers/devfreq/devfreq.c (ffffffff81bd1b65)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_frequency
```
```
In drivers/ras/ras.c (ffffffff81bdd398)
Location: include/linux/perf_event.h:1185
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
In drivers/interconnect/core.c (ffffffff81be2b51)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - drivers/interconnect/core.c:perf_trace_icc_set_bw_end
  - drivers/interconnect/core.c:perf_trace_icc_set_bw
```
```
In net/core/net-traces.c (ffffffff81c681aa)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:perf_trace_neigh_create
  - net/core/net-traces.c:perf_trace_page_pool_update_nid
  - net/core/net-traces.c:perf_trace_page_pool_state_hold
  - net/core/net-traces.c:perf_trace_page_pool_state_release
  - net/core/net-traces.c:perf_trace_page_pool_release
  - net/core/net-traces.c:perf_trace_br_fdb_update
  - net/core/net-traces.c:perf_trace_fdb_delete
  - net/core/net-traces.c:perf_trace_br_fdb_external_learn_add
  - net/core/net-traces.c:perf_trace_br_fdb_add
  - net/core/net-traces.c:perf_trace_qdisc_create
  - net/core/net-traces.c:perf_trace_qdisc_destroy
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:perf_trace_qdisc_enqueue
  - net/core/net-traces.c:perf_trace_qdisc_dequeue
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_tcp_cong_state_set
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_inet_sk_error_report
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
```
```
In net/core/devlink.c (ffffffff81c745e5)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_trap_report
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/netlink/af_netlink.c (ffffffff81ca9b5d)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:perf_trace_netlink_extack
```
```
In net/bpf/test_run.c (ffffffff81cb307f)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (ffffffff81d9cbf4)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/mptcp/protocol.c (ffffffff81e1bf44)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - net/mptcp/protocol.c:perf_trace_subflow_check_data_avail
  - net/mptcp/protocol.c:perf_trace_ack_update_msk
  - net/mptcp/protocol.c:perf_trace_mptcp_dump_mpext
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
```
```
In net/mctp/af_mctp.c (ffffffff81e36873)
Location: include/linux/perf_event.h:1185
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:perf_trace_mctp_key_release
  - net/mctp/af_mctp.c:perf_trace_mctp_key_acquire
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
In init/main.c (ffffffff81001561)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810050fc)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff810400f1)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_gdt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_load_idt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_multi
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_one_user
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_alloc_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pmd
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
In arch/x86/hyperv/mmu.c (ffffffff81045be1)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_one
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_multi
```
```
In arch/x86/kernel/irq.c (ffffffff8104e1ca)
Location: include/linux/perf_event.h:1284
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
In arch/x86/kernel/nmi.c (ffffffff81052025)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8106067c)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81075d40)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108c881)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/fault.c (ffffffff810c2f56)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In kernel/fork.c (ffffffff810e4a2b)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff810eb13a)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff810f2b9c)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810fd7e6)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff81110971)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_end
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_activate_work
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
```
```
In kernel/sched/core.c (ffffffff811346b1)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
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
  - kernel/sched/core.c:perf_trace_sched_kthread_work_execute_end
  - kernel/sched/core.c:perf_trace_sched_kthread_work_execute_start
  - kernel/sched/core.c:perf_trace_sched_kthread_work_queue_work
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
```
```
In kernel/locking/mutex.c (ffffffff8117c771)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - kernel/locking/mutex.c:perf_trace_contention_end
  - kernel/locking/mutex.c:perf_trace_contention_begin
```
```
In kernel/printk/printk.c (ffffffff8118dc4f)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff811a77eb)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff811a8ed1)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_stall_warning
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff811c4241)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/entry/common.c (ffffffff811c5ef2)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - kernel/entry/common.c:perf_trace_sys_exit
  - kernel/entry/common.c:perf_trace_sys_enter
```
```
In kernel/module/main.c (ffffffff811c80ac)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - kernel/module/main.c:perf_trace_module_request
  - kernel/module/main.c:perf_trace_module_refcnt
  - kernel/module/main.c:perf_trace_module_free
  - kernel/module/main.c:perf_trace_module_load
```
```
In kernel/time/timer.c (ffffffff811d5921)
Location: include/linux/perf_event.h:1284
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
In kernel/time/alarmtimer.c (ffffffff811e2d81)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/cgroup/cgroup.c (ffffffff81204889)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_event_perf.c (ffffffff8128ca4b)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/bpf_trace.c (ffffffff812a80b1)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:perf_trace_bpf_trace_printk
```
```
In kernel/trace/error_report-traces.c (ffffffff812aea11)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - kernel/trace/error_report-traces.c:perf_trace_error_report_template
```
```
In kernel/trace/power-traces.c (ffffffff812afe85)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_guest_halt_poll_ns
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_cpu_latency_qos_request
  - kernel/trace/power-traces.c:perf_trace_power_domain
  - kernel/trace/power-traces.c:perf_trace_clock
  - kernel/trace/power-traces.c:perf_trace_wakeup_source
  - kernel/trace/power-traces.c:perf_trace_suspend_resume
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:perf_trace_cpu_frequency_limits
  - kernel/trace/power-traces.c:perf_trace_pstate_sample
  - kernel/trace/power-traces.c:perf_trace_powernv_throttle
  - kernel/trace/power-traces.c:perf_trace_cpu_idle_miss
  - kernel/trace/power-traces.c:perf_trace_cpu
```
```
In kernel/trace/rpm-traces.c (ffffffff812b2c9e)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/rv/rv.c (ffffffff812bbd06)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - kernel/trace/rv/rv.c:perf_trace_error_da_monitor_id
  - kernel/trace/rv/rv.c:perf_trace_event_da_monitor_id
```
```
In kernel/bpf/core.c (ffffffff812bfcb1)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/rseq.c (ffffffff813562ea)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff81359274)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff81362196)
Location: include/linux/perf_event.h:1284
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
In mm/swap.c (ffffffff8136cf0c)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81375a1a)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_throttled
  - mm/vmscan.c:perf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:perf_trace_mm_vmscan_write_folio
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
In mm/percpu.c (ffffffff81399dec)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff8139ffb7)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_rss_stat
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_cache_free
  - mm/slab_common.c:perf_trace_kfree
  - mm/slab_common.c:perf_trace_kmalloc
  - mm/slab_common.c:perf_trace_kmem_cache_alloc
```
```
In mm/compaction.c (ffffffff813a3c95)
Location: include/linux/perf_event.h:1284
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
In mm/mmap_lock.c (ffffffff813b3b51)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - mm/mmap_lock.c:perf_trace_mmap_lock_acquire_returned
  - mm/mmap_lock.c:perf_trace_mmap_lock
```
```
In mm/mmap.c (ffffffff813c5c3c)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - mm/mmap.c:perf_trace_exit_mmap
  - mm/mmap.c:perf_trace_vma_store
  - mm/mmap.c:perf_trace_vma_mas_szero
  - mm/mmap.c:perf_trace_vm_unmapped_area
```
```
In mm/rmap.c (ffffffff813d5425)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - mm/rmap.c:perf_trace_migration_pte
  - mm/rmap.c:perf_trace_mm_migrate_pages_start
  - mm/rmap.c:perf_trace_mm_migrate_pages
  - mm/rmap.c:perf_trace_tlb_flush
```
```
In mm/vmalloc.c (ffffffff813db6e6)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - mm/vmalloc.c:perf_trace_free_vmap_area_noflush
  - mm/vmalloc.c:perf_trace_purge_vmap_area_lazy
  - mm/vmalloc.c:perf_trace_alloc_vmap_area
```
```
In mm/huge_memory.c (ffffffff8143ab91)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - mm/huge_memory.c:perf_trace_migration_pmd
  - mm/huge_memory.c:perf_trace_hugepage_update
  - mm/huge_memory.c:perf_trace_hugepage_set_pmd
```
```
In mm/khugepaged.c (ffffffff81446509)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_khugepaged_collapse_file
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_file
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff814644b6)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In fs/fs-writeback.c (ffffffff814bcc5c)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
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
  - fs/fs-writeback.c:perf_trace_writeback_folio_template
```
```
In fs/dax.c (ffffffff814f6aa6)
Location: include/linux/perf_event.h:1284
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
In fs/locks.c (ffffffff81508516)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/iomap/trace.c (ffffffff8151ad3a)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - fs/iomap/trace.c:perf_trace_iomap_iter
  - fs/iomap/trace.c:perf_trace_iomap_class
  - fs/iomap/trace.c:perf_trace_iomap_range_class
  - fs/iomap/trace.c:perf_trace_iomap_readpage_class
```
```
In fs/ext4/super.c (ffffffff815b4296)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_update_sb
  - fs/ext4/super.c:perf_trace_ext4_fc_cleanup
  - fs/ext4/super.c:perf_trace_ext4_fc_track_range
  - fs/ext4/super.c:perf_trace_ext4_fc_track_inode
  - fs/ext4/super.c:perf_trace_ext4_fc_track_dentry
  - fs/ext4/super.c:perf_trace_ext4_fc_stats
  - fs/ext4/super.c:perf_trace_ext4_fc_commit_stop
  - fs/ext4/super.c:perf_trace_ext4_fc_commit_start
  - fs/ext4/super.c:perf_trace_ext4_fc_replay
  - fs/ext4/super.c:perf_trace_ext4_fc_replay_scan
  - fs/ext4/super.c:perf_trace_ext4_lazy_itable_init
  - fs/ext4/super.c:perf_trace_ext4_prefetch_bitmaps
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
  - fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:perf_trace_ext4__trim
  - fs/ext4/super.c:perf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:perf_trace_ext4_journal_start_inode
  - fs/ext4/super.c:perf_trace_ext4_journal_start_sb
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
  - fs/ext4/super.c:perf_trace_ext4_read_block_bitmap_load
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
  - fs/ext4/super.c:perf_trace_ext4_invalidate_folio_op
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
In fs/jbd2/journal.c (ffffffff815e5ece)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_shrink_checkpoint_list
  - fs/jbd2/journal.c:perf_trace_jbd2_shrink_scan_exit
  - fs/jbd2/journal.c:perf_trace_jbd2_journal_shrink
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start_class
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In security/selinux/avc.c (ffffffff8166c477)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - security/selinux/avc.c:perf_trace_selinux_audited
```
```
In block/blk-core.c (ffffffff817334bb)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_bio
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_completion
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_buffer
```
```
In block/blk-iocost.c (ffffffff8176bb88)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_iocg_forgive_debt
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_state
```
```
In block/blk-wbt.c (ffffffff8177948e)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In io_uring/io_uring.c (ffffffff81786e65)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - io_uring/io_uring.c:perf_trace_io_uring_local_work_run
  - io_uring/io_uring.c:perf_trace_io_uring_short_write
  - io_uring/io_uring.c:perf_trace_io_uring_task_work_run
  - io_uring/io_uring.c:perf_trace_io_uring_cqe_overflow
  - io_uring/io_uring.c:perf_trace_io_uring_req_failed
  - io_uring/io_uring.c:perf_trace_io_uring_task_add
  - io_uring/io_uring.c:perf_trace_io_uring_poll_arm
  - io_uring/io_uring.c:perf_trace_io_uring_submit_sqe
  - io_uring/io_uring.c:perf_trace_io_uring_complete
  - io_uring/io_uring.c:perf_trace_io_uring_fail_link
  - io_uring/io_uring.c:perf_trace_io_uring_cqring_wait
  - io_uring/io_uring.c:perf_trace_io_uring_link
  - io_uring/io_uring.c:perf_trace_io_uring_defer
  - io_uring/io_uring.c:perf_trace_io_uring_queue_async_work
  - io_uring/io_uring.c:perf_trace_io_uring_file_get
  - io_uring/io_uring.c:perf_trace_io_uring_register
  - io_uring/io_uring.c:perf_trace_io_uring_create
```
```
In arch/x86/lib/msr.c (ffffffff818a61d5)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff818ba305)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/pwm/core.c (ffffffff818cef87)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - drivers/pwm/core.c:perf_trace_pwm
```
```
In drivers/clk/clk.c (ffffffff819f5087)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_rate_request
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate_range
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff81a370fd)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/iommu/intel/trace.c (ffffffff81ac78c2)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - drivers/iommu/intel/trace.c:perf_trace_prq_report
  - drivers/iommu/intel/trace.c:perf_trace_qi_submit
```
```
In drivers/iommu/iommu-traces.c (ffffffff81ad3772)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff81b19b7f)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bulk
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
```
```
In drivers/base/trace.c (ffffffff81b29afb)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - drivers/base/trace.c:perf_trace_devres
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81b6b3f9)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81b717b0)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff81b73d2c)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/scsi/sd_zbc.c (ffffffff81b9568e)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:perf_trace_scsi_zone_wp_update
  - drivers/scsi/sd_zbc.c:perf_trace_scsi_prepare_zone_append
```
```
In drivers/ata/libata-core.c (ffffffff81ba1c1c)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_sff_template
  - drivers/ata/libata-core.c:perf_trace_ata_transfer_data_template
  - drivers/ata/libata-core.c:perf_trace_ata_sff_hsm_template
  - drivers/ata/libata-core.c:perf_trace_ata_port_eh_begin_template
  - drivers/ata/libata-core.c:perf_trace_ata_link_reset_end_template
  - drivers/ata/libata-core.c:perf_trace_ata_link_reset_begin_template
  - drivers/ata/libata-core.c:perf_trace_ata_eh_action_template
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_bmdma_status
  - drivers/ata/libata-core.c:perf_trace_ata_exec_command_template
  - drivers/ata/libata-core.c:perf_trace_ata_tf_load
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue_template
```
```
In drivers/spi/spi.c (ffffffff81bd0d47)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_set_cs
  - drivers/spi/spi.c:perf_trace_spi_setup
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81be57ee)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81c93f0c)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_doorbell
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
```
```
In drivers/rtc/interface.c (ffffffff81cba5bc)
Location: include/linux/perf_event.h:1284
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
In drivers/i2c/i2c-core-base.c (ffffffff81cc1c86)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81cc6fae)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff81cdbe11)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff81cde9a3)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81ce6ffd)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/watchdog/watchdog_core.c (ffffffff81ceb246)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:perf_trace_watchdog_set_timeout
  - drivers/watchdog/watchdog_core.c:perf_trace_watchdog_template
```
```
In drivers/cpufreq/amd-pstate-trace.c (ffffffff81d3879e)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate-trace.c:perf_trace_amd_pstate_perf
```
```
In drivers/mmc/core/core.c (ffffffff81d47205)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff81d72ce1)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_start
```
```
In drivers/devfreq/devfreq.c (ffffffff81d7d6f2)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_frequency
```
```
In drivers/ras/ras.c (ffffffff81d88655)
Location: include/linux/perf_event.h:1284
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
In drivers/interconnect/core.c (ffffffff81d8e77e)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - drivers/interconnect/core.c:perf_trace_icc_set_bw_end
  - drivers/interconnect/core.c:perf_trace_icc_set_bw
```
```
In net/core/net-traces.c (ffffffff81e1f46b)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:perf_trace_neigh_create
  - net/core/net-traces.c:perf_trace_page_pool_update_nid
  - net/core/net-traces.c:perf_trace_page_pool_state_hold
  - net/core/net-traces.c:perf_trace_page_pool_state_release
  - net/core/net-traces.c:perf_trace_page_pool_release
  - net/core/net-traces.c:perf_trace_br_fdb_update
  - net/core/net-traces.c:perf_trace_fdb_delete
  - net/core/net-traces.c:perf_trace_br_fdb_external_learn_add
  - net/core/net-traces.c:perf_trace_br_fdb_add
  - net/core/net-traces.c:perf_trace_qdisc_create
  - net/core/net-traces.c:perf_trace_qdisc_destroy
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:perf_trace_qdisc_enqueue
  - net/core/net-traces.c:perf_trace_qdisc_dequeue
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_tcp_cong_state_set
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_inet_sk_error_report
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
```
```
In net/core/devlink.c (ffffffff81e2d201)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_trap_report
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/netlink/af_netlink.c (ffffffff81e66b3a)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:perf_trace_netlink_extack
```
```
In net/bpf/test_run.c (ffffffff81e7113c)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (ffffffff81f6b961)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/mptcp/protocol.c (ffffffff81ff35a1)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - net/mptcp/protocol.c:perf_trace_subflow_check_data_avail
  - net/mptcp/protocol.c:perf_trace_ack_update_msk
  - net/mptcp/protocol.c:perf_trace_mptcp_dump_mpext
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
```
```
In net/mctp/af_mctp.c (ffffffff8200f8c0)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:perf_trace_mctp_key_release
  - net/mctp/af_mctp.c:perf_trace_mctp_key_acquire
```
```
In lib/maple_tree.c (ffffffff82025b8e)
Location: include/linux/perf_event.h:1284
Inline: True
Inline callers:
  - lib/maple_tree.c:perf_trace_ma_write
  - lib/maple_tree.c:perf_trace_ma_read
  - lib/maple_tree.c:perf_trace_ma_op
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
In init/main.c (ffffffff81001321)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8100491c)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff81040231)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_gdt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_load_idt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_multi
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_one_user
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_alloc_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pmd
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
In arch/x86/hyperv/mmu.c (ffffffff81045d91)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_one
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_multi
```
```
In arch/x86/kernel/irq.c (ffffffff8104eb7a)
Location: include/linux/perf_event.h:1398
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
In arch/x86/kernel/nmi.c (ffffffff81052d85)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81061f2c)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81077ec0)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108f711)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/fault.c (ffffffff810c6656)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In kernel/fork.c (ffffffff810f00db)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff810f6d7a)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff810fed61)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_tasklet
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff81109856)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff8111cb71)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_end
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_activate_work
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
```
```
In kernel/notifier.c (ffffffff811321ac)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - kernel/notifier.c:perf_trace_notifier_info
```
```
In kernel/sched/core.c (ffffffff811438b0)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:perf_trace_ipi_handler
  - kernel/sched/core.c:perf_trace_ipi_send_cpumask
  - kernel/sched/core.c:perf_trace_ipi_send_cpu
  - kernel/sched/core.c:perf_trace_ipi_raise
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
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
  - kernel/sched/core.c:perf_trace_sched_kthread_work_execute_end
  - kernel/sched/core.c:perf_trace_sched_kthread_work_execute_start
  - kernel/sched/core.c:perf_trace_sched_kthread_work_queue_work
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
```
```
In kernel/locking/mutex.c (ffffffff8118d451)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - kernel/locking/mutex.c:perf_trace_contention_end
  - kernel/locking/mutex.c:perf_trace_contention_begin
```
```
In kernel/printk/printk.c (ffffffff8119f3ff)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff811b93ab)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff811bac21)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_stall_warning
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff811d73e1)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/entry/common.c (ffffffff811d8af2)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - kernel/entry/common.c:perf_trace_sys_exit
  - kernel/entry/common.c:perf_trace_sys_enter
```
```
In kernel/module/main.c (ffffffff811db10c)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - kernel/module/main.c:perf_trace_module_request
  - kernel/module/main.c:perf_trace_module_refcnt
  - kernel/module/main.c:perf_trace_module_free
  - kernel/module/main.c:perf_trace_module_load
```
```
In kernel/time/timer.c (ffffffff811e9d11)
Location: include/linux/perf_event.h:1398
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
In kernel/time/alarmtimer.c (ffffffff811f73b1)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/smp.c (ffffffff8120d741)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - kernel/smp.c:perf_trace_csd_function
  - kernel/smp.c:perf_trace_csd_queue_cpu
```
```
In kernel/cgroup/cgroup.c (ffffffff81219e79)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_osnoise.c (ffffffff812950f6)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:perf_trace_sample_threshold
  - kernel/trace/trace_osnoise.c:perf_trace_nmi_noise
  - kernel/trace/trace_osnoise.c:perf_trace_irq_noise
  - kernel/trace/trace_osnoise.c:perf_trace_softirq_noise
  - kernel/trace/trace_osnoise.c:perf_trace_thread_noise
```
```
In kernel/trace/trace_event_perf.c (ffffffff812a996a)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/trace_events_user.c (ffffffff812c3a47)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_perf
```
```
In kernel/trace/bpf_trace.c (ffffffff812ca39b)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:perf_trace_bpf_trace_printk
```
```
In kernel/trace/error_report-traces.c (ffffffff812d0f51)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - kernel/trace/error_report-traces.c:perf_trace_error_report_template
```
```
In kernel/trace/power-traces.c (ffffffff812d2585)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_guest_halt_poll_ns
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_cpu_latency_qos_request
  - kernel/trace/power-traces.c:perf_trace_power_domain
  - kernel/trace/power-traces.c:perf_trace_clock
  - kernel/trace/power-traces.c:perf_trace_wakeup_source
  - kernel/trace/power-traces.c:perf_trace_suspend_resume
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:perf_trace_cpu_frequency_limits
  - kernel/trace/power-traces.c:perf_trace_pstate_sample
  - kernel/trace/power-traces.c:perf_trace_powernv_throttle
  - kernel/trace/power-traces.c:perf_trace_cpu_idle_miss
  - kernel/trace/power-traces.c:perf_trace_cpu
```
```
In kernel/trace/rpm-traces.c (ffffffff812d552e)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/rv/rv.c (ffffffff812e28f6)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - kernel/trace/rv/rv.c:perf_trace_error_da_monitor_id
  - kernel/trace/rv/rv.c:perf_trace_event_da_monitor_id
```
```
In kernel/bpf/core.c (ffffffff812e6a61)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/rseq.c (ffffffff81387a1a)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff8138abc4)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff813945d2)
Location: include/linux/perf_event.h:1398
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
In mm/swap.c (ffffffff8139f18c)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff813a72fa)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_throttled
  - mm/vmscan.c:perf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:perf_trace_mm_vmscan_write_folio
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
In mm/percpu.c (ffffffff813cce7c)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff813d3277)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_rss_stat
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_cache_free
  - mm/slab_common.c:perf_trace_kfree
  - mm/slab_common.c:perf_trace_kmalloc
  - mm/slab_common.c:perf_trace_kmem_cache_alloc
```
```
In mm/compaction.c (ffffffff813d7485)
Location: include/linux/perf_event.h:1398
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
In mm/mmap_lock.c (ffffffff813e89f1)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - mm/mmap_lock.c:perf_trace_mmap_lock_acquire_returned
  - mm/mmap_lock.c:perf_trace_mmap_lock
```
```
In mm/mmap.c (ffffffff813fa08c)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - mm/mmap.c:perf_trace_exit_mmap
  - mm/mmap.c:perf_trace_vma_store
  - mm/mmap.c:perf_trace_vma_mas_szero
  - mm/mmap.c:perf_trace_vm_unmapped_area
```
```
In mm/rmap.c (ffffffff8140a2e5)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - mm/rmap.c:perf_trace_migration_pte
  - mm/rmap.c:perf_trace_mm_migrate_pages_start
  - mm/rmap.c:perf_trace_mm_migrate_pages
  - mm/rmap.c:perf_trace_tlb_flush
```
```
In mm/vmalloc.c (ffffffff8140fe76)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - mm/vmalloc.c:perf_trace_free_vmap_area_noflush
  - mm/vmalloc.c:perf_trace_purge_vmap_area_lazy
  - mm/vmalloc.c:perf_trace_alloc_vmap_area
```
```
In mm/ksm.c (ffffffff814512c6)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - mm/ksm.c:perf_trace_ksm_remove_rmap_item
  - mm/ksm.c:perf_trace_ksm_remove_ksm_page
  - mm/ksm.c:perf_trace_ksm_merge_with_ksm_page
  - mm/ksm.c:perf_trace_ksm_merge_one_page
  - mm/ksm.c:perf_trace_ksm_enter_exit_template
  - mm/ksm.c:perf_trace_ksm_scan_template
```
```
In mm/huge_memory.c (ffffffff814704e1)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - mm/huge_memory.c:perf_trace_migration_pmd
  - mm/huge_memory.c:perf_trace_hugepage_update
  - mm/huge_memory.c:perf_trace_hugepage_set_pmd
```
```
In mm/khugepaged.c (ffffffff8147b959)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_khugepaged_collapse_file
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_file
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff81499fb6)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In fs/fs-writeback.c (ffffffff814f1d7c)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
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
  - fs/fs-writeback.c:perf_trace_writeback_folio_template
```
```
In fs/dax.c (ffffffff8152d8f6)
Location: include/linux/perf_event.h:1398
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
In fs/locks.c (ffffffff8153fad6)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/iomap/trace.c (ffffffff81552a9a)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - fs/iomap/trace.c:perf_trace_iomap_dio_complete
  - fs/iomap/trace.c:perf_trace_iomap_dio_rw_begin
  - fs/iomap/trace.c:perf_trace_iomap_iter
  - fs/iomap/trace.c:perf_trace_iomap_class
  - fs/iomap/trace.c:perf_trace_iomap_range_class
  - fs/iomap/trace.c:perf_trace_iomap_readpage_class
```
```
In fs/ext4/super.c (ffffffff815eaff6)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_update_sb
  - fs/ext4/super.c:perf_trace_ext4_fc_cleanup
  - fs/ext4/super.c:perf_trace_ext4_fc_track_range
  - fs/ext4/super.c:perf_trace_ext4_fc_track_inode
  - fs/ext4/super.c:perf_trace_ext4_fc_track_dentry
  - fs/ext4/super.c:perf_trace_ext4_fc_stats
  - fs/ext4/super.c:perf_trace_ext4_fc_commit_stop
  - fs/ext4/super.c:perf_trace_ext4_fc_commit_start
  - fs/ext4/super.c:perf_trace_ext4_fc_replay
  - fs/ext4/super.c:perf_trace_ext4_fc_replay_scan
  - fs/ext4/super.c:perf_trace_ext4_lazy_itable_init
  - fs/ext4/super.c:perf_trace_ext4_prefetch_bitmaps
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
  - fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:perf_trace_ext4__trim
  - fs/ext4/super.c:perf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:perf_trace_ext4_journal_start_inode
  - fs/ext4/super.c:perf_trace_ext4_journal_start_sb
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
  - fs/ext4/super.c:perf_trace_ext4_read_block_bitmap_load
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
  - fs/ext4/super.c:perf_trace_ext4_invalidate_folio_op
  - fs/ext4/super.c:perf_trace_ext4__folio_op
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
In fs/jbd2/journal.c (ffffffff8161d80e)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_shrink_checkpoint_list
  - fs/jbd2/journal.c:perf_trace_jbd2_shrink_scan_exit
  - fs/jbd2/journal.c:perf_trace_jbd2_journal_shrink
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start_class
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In security/selinux/avc.c (ffffffff816a4db8)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - security/selinux/avc.c:perf_trace_selinux_audited
```
```
In block/blk-core.c (ffffffff8176f8db)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_bio
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_completion
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_buffer
```
```
In block/blk-iocost.c (ffffffff817ab152)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_iocg_forgive_debt
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_state
```
```
In block/blk-wbt.c (ffffffff817b90be)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In io_uring/io_uring.c (ffffffff817c73a5)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - io_uring/io_uring.c:perf_trace_io_uring_local_work_run
  - io_uring/io_uring.c:perf_trace_io_uring_short_write
  - io_uring/io_uring.c:perf_trace_io_uring_task_work_run
  - io_uring/io_uring.c:perf_trace_io_uring_cqe_overflow
  - io_uring/io_uring.c:perf_trace_io_uring_req_failed
  - io_uring/io_uring.c:perf_trace_io_uring_task_add
  - io_uring/io_uring.c:perf_trace_io_uring_poll_arm
  - io_uring/io_uring.c:perf_trace_io_uring_submit_req
  - io_uring/io_uring.c:perf_trace_io_uring_complete
  - io_uring/io_uring.c:perf_trace_io_uring_fail_link
  - io_uring/io_uring.c:perf_trace_io_uring_cqring_wait
  - io_uring/io_uring.c:perf_trace_io_uring_link
  - io_uring/io_uring.c:perf_trace_io_uring_defer
  - io_uring/io_uring.c:perf_trace_io_uring_queue_async_work
  - io_uring/io_uring.c:perf_trace_io_uring_file_get
  - io_uring/io_uring.c:perf_trace_io_uring_register
  - io_uring/io_uring.c:perf_trace_io_uring_create
```
```
In arch/x86/lib/msr.c (ffffffff818e9005)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff818fd405)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/pwm/core.c (ffffffff81911fc7)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - drivers/pwm/core.c:perf_trace_pwm
```
```
In drivers/clk/clk.c (ffffffff81a3d80f)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_rate_request
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate_range
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff81a80e3d)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/iommu/intel/trace.c (ffffffff81b14643)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - drivers/iommu/intel/trace.c:perf_trace_prq_report
  - drivers/iommu/intel/trace.c:perf_trace_qi_submit
```
```
In drivers/iommu/iommu-traces.c (ffffffff81b21f3a)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff81b687af)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bulk
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
```
```
In drivers/base/trace.c (ffffffff81b79ccb)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - drivers/base/trace.c:perf_trace_devres
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81bbe861)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81bc5032)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff81bc74dc)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/scsi/sd_zbc.c (ffffffff81bebc2e)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:perf_trace_scsi_zone_wp_update
  - drivers/scsi/sd_zbc.c:perf_trace_scsi_prepare_zone_append
```
```
In drivers/ata/libata-core.c (ffffffff81bf842c)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_sff_template
  - drivers/ata/libata-core.c:perf_trace_ata_transfer_data_template
  - drivers/ata/libata-core.c:perf_trace_ata_sff_hsm_template
  - drivers/ata/libata-core.c:perf_trace_ata_port_eh_begin_template
  - drivers/ata/libata-core.c:perf_trace_ata_link_reset_end_template
  - drivers/ata/libata-core.c:perf_trace_ata_link_reset_begin_template
  - drivers/ata/libata-core.c:perf_trace_ata_eh_action_template
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_bmdma_status
  - drivers/ata/libata-core.c:perf_trace_ata_exec_command_template
  - drivers/ata/libata-core.c:perf_trace_ata_tf_load
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue_template
```
```
In drivers/spi/spi.c (ffffffff81c289b7)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_set_cs
  - drivers/spi/spi.c:perf_trace_spi_setup
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81c3d20e)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81cfa64c)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_doorbell
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
```
```
In drivers/rtc/interface.c (ffffffff81d21d6c)
Location: include/linux/perf_event.h:1398
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
In drivers/i2c/i2c-core-base.c (ffffffff81d29696)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81d2ecde)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff81d44372)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff81d468b3)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81d4f6fd)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/watchdog/watchdog_core.c (ffffffff81d53e96)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:perf_trace_watchdog_set_timeout
  - drivers/watchdog/watchdog_core.c:perf_trace_watchdog_template
```
```
In drivers/cpufreq/amd-pstate-trace.c (ffffffff81da321e)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate-trace.c:perf_trace_amd_pstate_perf
```
```
In drivers/mmc/core/core.c (ffffffff81db1a95)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff81de0ac1)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_start
```
```
In drivers/devfreq/devfreq.c (ffffffff81deba72)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_frequency
```
```
In drivers/ras/ras.c (ffffffff81df6c65)
Location: include/linux/perf_event.h:1398
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
In drivers/interconnect/core.c (ffffffff81dfd086)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - drivers/interconnect/core.c:perf_trace_icc_set_bw_end
  - drivers/interconnect/core.c:perf_trace_icc_set_bw
```
```
In net/core/net-traces.c (ffffffff81e91b57)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:perf_trace_neigh_create
  - net/core/net-traces.c:perf_trace_page_pool_update_nid
  - net/core/net-traces.c:perf_trace_page_pool_state_hold
  - net/core/net-traces.c:perf_trace_page_pool_state_release
  - net/core/net-traces.c:perf_trace_page_pool_release
  - net/core/net-traces.c:perf_trace_br_mdb_full
  - net/core/net-traces.c:perf_trace_br_fdb_update
  - net/core/net-traces.c:perf_trace_fdb_delete
  - net/core/net-traces.c:perf_trace_br_fdb_external_learn_add
  - net/core/net-traces.c:perf_trace_br_fdb_add
  - net/core/net-traces.c:perf_trace_qdisc_create
  - net/core/net-traces.c:perf_trace_qdisc_destroy
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:perf_trace_qdisc_enqueue
  - net/core/net-traces.c:perf_trace_qdisc_dequeue
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_tcp_cong_state_set
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_sock_msg_length
  - net/core/net-traces.c:perf_trace_sk_data_ready
  - net/core/net-traces.c:perf_trace_inet_sk_error_report
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
```
```
In net/netlink/af_netlink.c (ffffffff81ec28fa)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:perf_trace_netlink_extack
```
```
In net/bpf/test_run.c (ffffffff81ecd27c)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (ffffffff81fcbab1)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/devlink/leftover.c (ffffffff8203175a)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - net/devlink/leftover.c:perf_trace_devlink_trap_report
  - net/devlink/leftover.c:perf_trace_devlink_health_reporter_state_update
  - net/devlink/leftover.c:perf_trace_devlink_health_recover_aborted
  - net/devlink/leftover.c:perf_trace_devlink_health_report
  - net/devlink/leftover.c:perf_trace_devlink_hwerr
  - net/devlink/leftover.c:perf_trace_devlink_hwmsg
```
```
In net/mptcp/protocol.c (ffffffff8206f911)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - net/mptcp/protocol.c:perf_trace_subflow_check_data_avail
  - net/mptcp/protocol.c:perf_trace_ack_update_msk
  - net/mptcp/protocol.c:perf_trace_mptcp_dump_mpext
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
```
```
In net/mctp/af_mctp.c (ffffffff8208c4e0)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:perf_trace_mctp_key_release
  - net/mctp/af_mctp.c:perf_trace_mctp_key_acquire
```
```
In net/handshake/trace.c (ffffffff82094eea)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - net/handshake/trace.c:perf_trace_handshake_complete
  - net/handshake/trace.c:perf_trace_handshake_error_class
  - net/handshake/trace.c:perf_trace_handshake_fd_class
  - net/handshake/trace.c:perf_trace_handshake_event_class
```
```
In lib/maple_tree.c (ffffffff820a5cde)
Location: include/linux/perf_event.h:1398
Inline: True
Inline callers:
  - lib/maple_tree.c:perf_trace_ma_write
  - lib/maple_tree.c:perf_trace_ma_read
  - lib/maple_tree.c:perf_trace_ma_op
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
In init/main.c (ffffffff81001331)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8100722c)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff81046701)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_gdt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_load_idt
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_multi
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_one_user
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_alloc_ptpage
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_pmd
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
In arch/x86/hyperv/mmu.c (ffffffff8104c461)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_one
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_multi
```
```
In arch/x86/kernel/irq.c (ffffffff81055daa)
Location: include/linux/perf_event.h:1440
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
In arch/x86/kernel/nmi.c (ffffffff81059fa5)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8106916c)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107f370)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81096aa1)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/fault.c (ffffffff810cead6)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In kernel/fork.c (ffffffff810f94e7)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff8110012a)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff81108411)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_tasklet
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff811131f6)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff811265f1)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_end
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_activate_work
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
```
```
In kernel/notifier.c (ffffffff8113d0bc)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - kernel/notifier.c:perf_trace_notifier_info
```
```
In kernel/sched/core.c (ffffffff8114edd0)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:perf_trace_ipi_handler
  - kernel/sched/core.c:perf_trace_ipi_send_cpumask
  - kernel/sched/core.c:perf_trace_ipi_send_cpu
  - kernel/sched/core.c:perf_trace_ipi_raise
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_skip_vma_numa
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
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
  - kernel/sched/core.c:perf_trace_sched_kthread_work_execute_end
  - kernel/sched/core.c:perf_trace_sched_kthread_work_execute_start
  - kernel/sched/core.c:perf_trace_sched_kthread_work_queue_work
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
```
```
In kernel/locking/mutex.c (ffffffff8119be01)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - kernel/locking/mutex.c:perf_trace_contention_end
  - kernel/locking/mutex.c:perf_trace_contention_begin
```
```
In kernel/printk/printk.c (ffffffff811ae5df)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff811c926b)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff811cabe1)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_stall_warning
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff811ec391)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/entry/common.c (ffffffff811ee602)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - kernel/entry/common.c:perf_trace_sys_exit
  - kernel/entry/common.c:perf_trace_sys_enter
```
```
In kernel/module/main.c (ffffffff811f0dbc)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - kernel/module/main.c:perf_trace_module_request
  - kernel/module/main.c:perf_trace_module_refcnt
  - kernel/module/main.c:perf_trace_module_free
  - kernel/module/main.c:perf_trace_module_load
```
```
In kernel/time/timer.c (ffffffff811ffba1)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - kernel/time/timer.c:perf_trace_tick_stop
  - kernel/time/timer.c:perf_trace_itimer_expire
  - kernel/time/timer.c:perf_trace_itimer_state
  - kernel/time/timer.c:perf_trace_hrtimer_class
  - kernel/time/timer.c:perf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:perf_trace_hrtimer_start
  - kernel/time/timer.c:perf_trace_hrtimer_init
  - kernel/time/timer.c:perf_trace_timer_base_idle
  - kernel/time/timer.c:perf_trace_timer_expire_entry
  - kernel/time/timer.c:perf_trace_timer_start
  - kernel/time/timer.c:perf_trace_timer_class
```
```
In kernel/time/alarmtimer.c (ffffffff8120d551)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/smp.c (ffffffff81224ed1)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - kernel/smp.c:perf_trace_csd_function
  - kernel/smp.c:perf_trace_csd_queue_cpu
```
```
In kernel/cgroup/cgroup.c (ffffffff812319a9)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b0756)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:perf_trace_sample_threshold
  - kernel/trace/trace_osnoise.c:perf_trace_nmi_noise
  - kernel/trace/trace_osnoise.c:perf_trace_irq_noise
  - kernel/trace/trace_osnoise.c:perf_trace_softirq_noise
  - kernel/trace/trace_osnoise.c:perf_trace_thread_noise
```
```
In kernel/trace/trace_event_perf.c (ffffffff812c567a)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/trace_events_user.c (ffffffff812e0297)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_perf
```
```
In kernel/trace/bpf_trace.c (ffffffff812e751b)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:perf_trace_bpf_trace_printk
```
```
In kernel/trace/error_report-traces.c (ffffffff812eea51)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - kernel/trace/error_report-traces.c:perf_trace_error_report_template
```
```
In kernel/trace/power-traces.c (ffffffff812f0085)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_guest_halt_poll_ns
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_cpu_latency_qos_request
  - kernel/trace/power-traces.c:perf_trace_power_domain
  - kernel/trace/power-traces.c:perf_trace_clock
  - kernel/trace/power-traces.c:perf_trace_wakeup_source
  - kernel/trace/power-traces.c:perf_trace_suspend_resume
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:perf_trace_cpu_frequency_limits
  - kernel/trace/power-traces.c:perf_trace_pstate_sample
  - kernel/trace/power-traces.c:perf_trace_powernv_throttle
  - kernel/trace/power-traces.c:perf_trace_cpu_idle_miss
  - kernel/trace/power-traces.c:perf_trace_cpu
```
```
In kernel/trace/rpm-traces.c (ffffffff812f303e)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/rv/rv.c (ffffffff81300946)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - kernel/trace/rv/rv.c:perf_trace_error_da_monitor_id
  - kernel/trace/rv/rv.c:perf_trace_event_da_monitor_id
```
```
In kernel/bpf/core.c (ffffffff81305cca)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_bpf_xdp_link_attach_failed
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/context_tracking.c (ffffffff813b088c)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - kernel/context_tracking.c:perf_trace_context_tracking_user
```
```
In kernel/rseq.c (ffffffff813b147a)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff813b46e4)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff813be392)
Location: include/linux/perf_event.h:1440
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
In mm/swap.c (ffffffff813c8dec)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff813d0e5a)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_throttled
  - mm/vmscan.c:perf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:perf_trace_mm_vmscan_write_folio
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
In mm/percpu.c (ffffffff813f77ec)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff813fdc77)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_rss_stat
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_cache_free
  - mm/slab_common.c:perf_trace_kfree
  - mm/slab_common.c:perf_trace_kmalloc
  - mm/slab_common.c:perf_trace_kmem_cache_alloc
```
```
In mm/compaction.c (ffffffff81401165)
Location: include/linux/perf_event.h:1440
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
In mm/mmap_lock.c (ffffffff81413661)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - mm/mmap_lock.c:perf_trace_mmap_lock_acquire_returned
  - mm/mmap_lock.c:perf_trace_mmap_lock
```
```
In mm/mmap.c (ffffffff81425e4c)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - mm/mmap.c:perf_trace_exit_mmap
  - mm/mmap.c:perf_trace_vma_store
  - mm/mmap.c:perf_trace_vma_mas_szero
  - mm/mmap.c:perf_trace_vm_unmapped_area
```
```
In mm/rmap.c (ffffffff81436b25)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - mm/rmap.c:perf_trace_migration_pte
  - mm/rmap.c:perf_trace_mm_migrate_pages_start
  - mm/rmap.c:perf_trace_mm_migrate_pages
  - mm/rmap.c:perf_trace_tlb_flush
```
```
In mm/vmalloc.c (ffffffff8143c7d6)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - mm/vmalloc.c:perf_trace_free_vmap_area_noflush
  - mm/vmalloc.c:perf_trace_purge_vmap_area_lazy
  - mm/vmalloc.c:perf_trace_alloc_vmap_area
```
```
In mm/ksm.c (ffffffff8148b175)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - mm/ksm.c:perf_trace_ksm_advisor
  - mm/ksm.c:perf_trace_ksm_remove_rmap_item
  - mm/ksm.c:perf_trace_ksm_remove_ksm_page
  - mm/ksm.c:perf_trace_ksm_merge_with_ksm_page
  - mm/ksm.c:perf_trace_ksm_merge_one_page
  - mm/ksm.c:perf_trace_ksm_enter_exit_template
  - mm/ksm.c:perf_trace_ksm_scan_template
```
```
In mm/huge_memory.c (ffffffff8149f8a1)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - mm/huge_memory.c:perf_trace_migration_pmd
  - mm/huge_memory.c:perf_trace_hugepage_update
  - mm/huge_memory.c:perf_trace_hugepage_set
```
```
In mm/khugepaged.c (ffffffff814aabd9)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_khugepaged_collapse_file
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_file
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff814c9736)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In fs/fs-writeback.c (ffffffff8152648c)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
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
  - fs/fs-writeback.c:perf_trace_writeback_folio_template
```
```
In fs/dax.c (ffffffff815627d6)
Location: include/linux/perf_event.h:1440
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
In fs/locks.c (ffffffff81574fb6)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/iomap/trace.c (ffffffff81588a5a)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - fs/iomap/trace.c:perf_trace_iomap_dio_complete
  - fs/iomap/trace.c:perf_trace_iomap_dio_rw_begin
  - fs/iomap/trace.c:perf_trace_iomap_iter
  - fs/iomap/trace.c:perf_trace_iomap_class
  - fs/iomap/trace.c:perf_trace_iomap_range_class
  - fs/iomap/trace.c:perf_trace_iomap_readpage_class
```
```
In fs/ext4/super.c (ffffffff816239e6)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_update_sb
  - fs/ext4/super.c:perf_trace_ext4_fc_cleanup
  - fs/ext4/super.c:perf_trace_ext4_fc_track_range
  - fs/ext4/super.c:perf_trace_ext4_fc_track_inode
  - fs/ext4/super.c:perf_trace_ext4_fc_track_dentry
  - fs/ext4/super.c:perf_trace_ext4_fc_stats
  - fs/ext4/super.c:perf_trace_ext4_fc_commit_stop
  - fs/ext4/super.c:perf_trace_ext4_fc_commit_start
  - fs/ext4/super.c:perf_trace_ext4_fc_replay
  - fs/ext4/super.c:perf_trace_ext4_fc_replay_scan
  - fs/ext4/super.c:perf_trace_ext4_lazy_itable_init
  - fs/ext4/super.c:perf_trace_ext4_prefetch_bitmaps
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
  - fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:perf_trace_ext4__trim
  - fs/ext4/super.c:perf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:perf_trace_ext4_journal_start_inode
  - fs/ext4/super.c:perf_trace_ext4_journal_start_sb
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
  - fs/ext4/super.c:perf_trace_ext4_read_block_bitmap_load
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
  - fs/ext4/super.c:perf_trace_ext4_invalidate_folio_op
  - fs/ext4/super.c:perf_trace_ext4__folio_op
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
In fs/jbd2/journal.c (ffffffff8165671e)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_shrink_checkpoint_list
  - fs/jbd2/journal.c:perf_trace_jbd2_shrink_scan_exit
  - fs/jbd2/journal.c:perf_trace_jbd2_journal_shrink
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start_class
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In security/selinux/avc.c (ffffffff816e1818)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - security/selinux/avc.c:perf_trace_selinux_audited
```
```
In block/blk-core.c (ffffffff817b1b4b)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_bio
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_completion
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_buffer
```
```
In block/blk-iocost.c (ffffffff817eef02)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_iocg_forgive_debt
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_state
```
```
In block/blk-wbt.c (ffffffff817fd9fe)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In io_uring/io_uring.c (ffffffff8180c075)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - io_uring/io_uring.c:perf_trace_io_uring_local_work_run
  - io_uring/io_uring.c:perf_trace_io_uring_short_write
  - io_uring/io_uring.c:perf_trace_io_uring_task_work_run
  - io_uring/io_uring.c:perf_trace_io_uring_cqe_overflow
  - io_uring/io_uring.c:perf_trace_io_uring_req_failed
  - io_uring/io_uring.c:perf_trace_io_uring_task_add
  - io_uring/io_uring.c:perf_trace_io_uring_poll_arm
  - io_uring/io_uring.c:perf_trace_io_uring_submit_req
  - io_uring/io_uring.c:perf_trace_io_uring_complete
  - io_uring/io_uring.c:perf_trace_io_uring_fail_link
  - io_uring/io_uring.c:perf_trace_io_uring_cqring_wait
  - io_uring/io_uring.c:perf_trace_io_uring_link
  - io_uring/io_uring.c:perf_trace_io_uring_defer
  - io_uring/io_uring.c:perf_trace_io_uring_queue_async_work
  - io_uring/io_uring.c:perf_trace_io_uring_file_get
  - io_uring/io_uring.c:perf_trace_io_uring_register
  - io_uring/io_uring.c:perf_trace_io_uring_create
```
```
In arch/x86/lib/msr.c (ffffffff819304a5)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff81944a05)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/pwm/core.c (ffffffff81959e37)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - drivers/pwm/core.c:perf_trace_pwm
```
```
In drivers/clk/clk.c (ffffffff81a890ff)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_rate_request
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate_range
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff81ad33ed)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/iommu/intel/trace.c (ffffffff81b69f83)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - drivers/iommu/intel/trace.c:perf_trace_prq_report
  - drivers/iommu/intel/trace.c:perf_trace_qi_submit
```
```
In drivers/iommu/iommu-traces.c (ffffffff81b78ada)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff81bbc43f)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bulk
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
```
```
In drivers/base/trace.c (ffffffff81bcdc2b)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - drivers/base/trace.c:perf_trace_devres
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81c12fb1)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81c199e2)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff81c1c04c)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/scsi/sd_zbc.c (ffffffff81c412ee)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:perf_trace_scsi_zone_wp_update
  - drivers/scsi/sd_zbc.c:perf_trace_scsi_prepare_zone_append
```
```
In drivers/ata/libata-core.c (ffffffff81c4dccc)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_sff_template
  - drivers/ata/libata-core.c:perf_trace_ata_transfer_data_template
  - drivers/ata/libata-core.c:perf_trace_ata_sff_hsm_template
  - drivers/ata/libata-core.c:perf_trace_ata_port_eh_begin_template
  - drivers/ata/libata-core.c:perf_trace_ata_link_reset_end_template
  - drivers/ata/libata-core.c:perf_trace_ata_link_reset_begin_template
  - drivers/ata/libata-core.c:perf_trace_ata_eh_action_template
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_bmdma_status
  - drivers/ata/libata-core.c:perf_trace_ata_exec_command_template
  - drivers/ata/libata-core.c:perf_trace_ata_tf_load
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue_template
```
```
In drivers/gpu/drm/drm_trace_points.c (ffffffff81cb3835)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_trace_points.c:perf_trace_drm_vblank_event_delivered
  - drivers/gpu/drm/drm_trace_points.c:perf_trace_drm_vblank_event_queued
  - drivers/gpu/drm/drm_trace_points.c:perf_trace_drm_vblank_event
```
```
In drivers/spi/spi.c (ffffffff81cdb387)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_set_cs
  - drivers/spi/spi.c:perf_trace_spi_setup
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81cf25be)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81daffac)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_doorbell
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
```
```
In drivers/rtc/interface.c (ffffffff81dd7acc)
Location: include/linux/perf_event.h:1440
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
In drivers/i2c/i2c-core-base.c (ffffffff81ddf556)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81de4c8e)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff81dfad42)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff81dfd2e3)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81e0643d)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_actor
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/watchdog/watchdog_core.c (ffffffff81e0ad66)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:perf_trace_watchdog_set_timeout
  - drivers/watchdog/watchdog_core.c:perf_trace_watchdog_template
```
```
In drivers/cpufreq/amd-pstate-trace.c (ffffffff81e5b29e)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate-trace.c:perf_trace_amd_pstate_perf
```
```
In drivers/mmc/core/core.c (ffffffff81e69ab5)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff81e96a81)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_start
```
```
In drivers/devfreq/devfreq.c (ffffffff81ea1e62)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_frequency
```
```
In drivers/ras/ras.c (ffffffff81ead375)
Location: include/linux/perf_event.h:1440
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
In drivers/interconnect/core.c (ffffffff81eb3e16)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - drivers/interconnect/core.c:perf_trace_icc_set_bw_end
  - drivers/interconnect/core.c:perf_trace_icc_set_bw
```
```
In net/core/net-traces.c (ffffffff81f53f15)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:perf_trace_neigh_create
  - net/core/net-traces.c:perf_trace_page_pool_update_nid
  - net/core/net-traces.c:perf_trace_page_pool_state_hold
  - net/core/net-traces.c:perf_trace_page_pool_state_release
  - net/core/net-traces.c:perf_trace_page_pool_release
  - net/core/net-traces.c:perf_trace_br_mdb_full
  - net/core/net-traces.c:perf_trace_br_fdb_update
  - net/core/net-traces.c:perf_trace_fdb_delete
  - net/core/net-traces.c:perf_trace_br_fdb_external_learn_add
  - net/core/net-traces.c:perf_trace_br_fdb_add
  - net/core/net-traces.c:perf_trace_qdisc_create
  - net/core/net-traces.c:perf_trace_qdisc_destroy
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:perf_trace_qdisc_enqueue
  - net/core/net-traces.c:perf_trace_qdisc_dequeue
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_tcp_cong_state_set
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_sock_msg_length
  - net/core/net-traces.c:perf_trace_sk_data_ready
  - net/core/net-traces.c:perf_trace_inet_sk_error_report
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
```
```
In net/netlink/af_netlink.c (ffffffff81f85c4a)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:perf_trace_netlink_extack
```
```
In net/bpf/test_run.c (ffffffff81f90aac)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (ffffffff820991f1)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/devlink/core.c (ffffffff820ff16a)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - net/devlink/core.c:perf_trace_devlink_trap_report
  - net/devlink/core.c:perf_trace_devlink_health_reporter_state_update
  - net/devlink/core.c:perf_trace_devlink_health_recover_aborted
  - net/devlink/core.c:perf_trace_devlink_health_report
  - net/devlink/core.c:perf_trace_devlink_hwerr
  - net/devlink/core.c:perf_trace_devlink_hwmsg
```
```
In net/mptcp/protocol.c (ffffffff82143a21)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - net/mptcp/protocol.c:perf_trace_subflow_check_data_avail
  - net/mptcp/protocol.c:perf_trace_ack_update_msk
  - net/mptcp/protocol.c:perf_trace_mptcp_dump_mpext
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
```
```
In net/mctp/af_mctp.c (ffffffff821629a0)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:perf_trace_mctp_key_release
  - net/mctp/af_mctp.c:perf_trace_mctp_key_acquire
```
```
In net/handshake/trace.c (ffffffff8216ca39)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - net/handshake/trace.c:perf_trace_tls_contenttype
  - net/handshake/trace.c:perf_trace_handshake_complete
  - net/handshake/trace.c:perf_trace_handshake_alert_class
  - net/handshake/trace.c:perf_trace_handshake_error_class
  - net/handshake/trace.c:perf_trace_handshake_fd_class
  - net/handshake/trace.c:perf_trace_handshake_event_class
```
```
In lib/maple_tree.c (ffffffff8217df5e)
Location: include/linux/perf_event.h:1440
Inline: True
Inline callers:
  - lib/maple_tree.c:perf_trace_ma_write
  - lib/maple_tree.c:perf_trace_ma_read
  - lib/maple_tree.c:perf_trace_ma_op
```
</details>
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
In init/main.c (ffff800010084cc0)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/arm64/kernel/ptrace.c (ffff80001008a960)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:perf_trace_sys_exit
  - arch/arm64/kernel/ptrace.c:perf_trace_sys_enter
```
```
In arch/arm64/kernel/smp.c (ffff80001009be94)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:perf_trace_ipi_handler
  - arch/arm64/kernel/smp.c:perf_trace_ipi_raise
```
```
In arch/arm64/kernel/armv8_deprecated.c (ffff8000100a8530)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/arm64/kernel/armv8_deprecated.c:perf_trace_instruction_emulation
```
```
In virt/kvm/kvm_main.c (ffff8000100ba538)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:perf_trace_kvm_halt_poll_ns
  - virt/kvm/kvm_main.c:perf_trace_kvm_age_page
  - virt/kvm/kvm_main.c:perf_trace_kvm_fpu
  - virt/kvm/kvm_main.c:perf_trace_kvm_mmio
  - virt/kvm/kvm_main.c:perf_trace_kvm_ack_irq
  - virt/kvm/kvm_main.c:perf_trace_kvm_set_irq
  - virt/kvm/kvm_main.c:perf_trace_kvm_vcpu_wakeup
  - virt/kvm/kvm_main.c:perf_trace_kvm_userspace_exit
```
```
In virt/kvm/arm/arm.c (ffff8000100c4f5c)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:perf_trace_kvm_timer_emulate
  - virt/kvm/arm/arm.c:perf_trace_kvm_timer_hrtimer_expire
  - virt/kvm/arm/arm.c:perf_trace_kvm_timer_restore_state
  - virt/kvm/arm/arm.c:perf_trace_kvm_timer_save_state
  - virt/kvm/arm/arm.c:perf_trace_kvm_get_timer_map
  - virt/kvm/arm/arm.c:perf_trace_kvm_timer_update_irq
  - virt/kvm/arm/arm.c:perf_trace_kvm_toggle_cache
  - virt/kvm/arm/arm.c:perf_trace_kvm_set_way_flush
  - virt/kvm/arm/arm.c:perf_trace_kvm_test_age_hva
  - virt/kvm/arm/arm.c:perf_trace_kvm_age_hva
  - virt/kvm/arm/arm.c:perf_trace_kvm_set_spte_hva
  - virt/kvm/arm/arm.c:perf_trace_kvm_unmap_hva_range
  - virt/kvm/arm/arm.c:perf_trace_kvm_mmio_emulate
  - virt/kvm/arm/arm.c:perf_trace_kvm_irq_line
  - virt/kvm/arm/arm.c:perf_trace_kvm_access_fault
  - virt/kvm/arm/arm.c:perf_trace_kvm_guest_fault
  - virt/kvm/arm/arm.c:perf_trace_kvm_exit
  - virt/kvm/arm/arm.c:perf_trace_kvm_entry
```
```
In arch/arm64/kvm/handle_exit.c (ffff8000100d0d70)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/arm64/kvm/handle_exit.c:perf_trace_kvm_set_guest_debug
  - arch/arm64/kvm/handle_exit.c:perf_trace_kvm_sys_access
  - arch/arm64/kvm/handle_exit.c:perf_trace_kvm_handle_sys_reg
  - arch/arm64/kvm/handle_exit.c:perf_trace_trap_reg
  - arch/arm64/kvm/handle_exit.c:perf_trace_kvm_arm_set_regset
  - arch/arm64/kvm/handle_exit.c:perf_trace_kvm_arm_set_dreg32
  - arch/arm64/kvm/handle_exit.c:perf_trace_kvm_arm_clear_debug
  - arch/arm64/kvm/handle_exit.c:perf_trace_kvm_arm_setup_debug
  - arch/arm64/kvm/handle_exit.c:perf_trace_kvm_hvc_arm64
  - arch/arm64/kvm/handle_exit.c:perf_trace_kvm_wfx_arm64
```
```
In virt/kvm/arm/vgic/vgic.c (ffff8000100db8a4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic.c:perf_trace_vgic_update_irq_pending
```
```
In kernel/fork.c (ffff8000100f17b0)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffff8000100f7cbc)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffff8000100fecf4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffff80001010b108)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffff80001011d534)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/sched/core.c (ffff800010da187c)
Location: include/linux/perf_event.h:1100
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
In kernel/printk/printk.c (ffff800010172b24)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/rcu/update.c (ffff80001018869c)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffff800010196454)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffff80001019db08)
Location: include/linux/perf_event.h:1100
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
In kernel/time/alarmtimer.c (ffff8000101a8f30)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffff8000101c246c)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffff8000101d0654)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_event_perf.c (ffff80001023e660)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/bpf_trace.c (ffff80001024dcf0)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
```
```
In kernel/trace/power-traces.c (ffff8000102541fc)
Location: include/linux/perf_event.h:1100
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
In kernel/trace/rpm-traces.c (ffff800010254cec)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/bpf/core.c (ffff80001025cc58)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/rseq.c (ffff8000102ac14c)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffff8000102aeb08)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffff8000102b6e00)
Location: include/linux/perf_event.h:1100
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
In mm/swap.c (ffff8000102c0434)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffff8000102c7228)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
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
```
```
In mm/percpu.c (ffff8000102e2034)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffff8000102e69d4)
Location: include/linux/perf_event.h:1100
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
In mm/compaction.c (ffff8000102e9568)
Location: include/linux/perf_event.h:1100
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
In mm/migrate.c (ffff80001034ea64)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffff80001035c3f4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffff800010371978)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffff800010376cd8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffff80001037d418)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/fs-writeback.c (ffff8000103c53b4)
Location: include/linux/perf_event.h:1100
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
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
```
```
In fs/dax.c (ffff800010408208)
Location: include/linux/perf_event.h:1100
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
In fs/locks.c (ffff800010415b0c)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffff8000104b3368)
Location: include/linux/perf_event.h:1100
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
In fs/jbd2/journal.c (ffff8000104d4f98)
Location: include/linux/perf_event.h:1100
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
In block/blk-core.c (ffff8000105e2254)
Location: include/linux/perf_event.h:1100
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
In block/blk-iocost.c (ffff800010614b10)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_activate
```
```
In block/blk-wbt.c (ffff800010621acc)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In drivers/gpio/gpiolib.c (ffff8000106bf8e8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffff8000107bff64)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/soc/qcom/rpmh-rsc.c (ffff80001081b8ec)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/soc/qcom/rpmh-rsc.c:perf_trace_rpmh_send_msg
  - drivers/soc/qcom/rpmh-rsc.c:perf_trace_rpmh_tx_done
```
```
In drivers/regulator/core.c (ffff800010843ad8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffff8000108ad6b0)
Location: include/linux/perf_event.h:1100
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
In drivers/iommu/iommu-traces.c (ffff8000108c8654)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffff800010913f28)
Location: include/linux/perf_event.h:1100
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
In drivers/dma-buf/dma-fence.c (ffff800010966f00)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffff80001096b180)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffff80001096e464)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffff800010998c64)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffff8000109c473c)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffff8000109d7794)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffff800010a89ebc)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
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
```
```
In drivers/rtc/interface.c (ffff800010aa8454)
Location: include/linux/perf_event.h:1100
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
In drivers/i2c/i2c-core-base.c (ffff800010ab0dc8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffff800010ab40cc)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffff800010ad2224)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffff800010ad4670)
Location: include/linux/perf_event.h:1100
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
In drivers/thermal/power_allocator.c (ffff800010adb138)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffff800010b2c5ec)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffff800010b79a1c)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_cmd_class
```
```
In drivers/devfreq/devfreq.c (ffff800010b86714)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/ras/ras.c (ffff800010b9dc58)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
```
```
In net/core/net-traces.c (ffff800010c198d4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
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
```
```
In net/core/devlink.c (ffff800010c2770c)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/bpf/test_run.c (ffff800010c52f94)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (ffff800010d0f898)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (c0302fa4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/arm/kernel/ptrace.c (c030b7b4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/arm/kernel/ptrace.c:perf_trace_sys_exit
  - arch/arm/kernel/ptrace.c:perf_trace_sys_enter
```
```
In arch/arm/kernel/smp.c (c0311f74)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/arm/kernel/smp.c:perf_trace_ipi_handler
  - arch/arm/kernel/smp.c:perf_trace_ipi_raise
```
```
In arch/arm/common/bL_switcher.c (c03264a4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/arm/common/bL_switcher.c:perf_trace_cpu_migrate
```
```
In kernel/fork.c (c034ff68)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (c03550a4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (c035b468)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (c03637bc)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (c0370c54)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/sched/core.c (c0e99b1c)
Location: include/linux/perf_event.h:1100
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
In kernel/printk/printk.c (c03c4a50)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/rcu/update.c (c03d7000)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/time/timer.c (c03e6c88)
Location: include/linux/perf_event.h:1100
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
In kernel/time/alarmtimer.c (c03f3f1c)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (c040909c)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (c0413a50)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_event_perf.c (c0479a50)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/bpf_trace.c (c0481454)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
```
```
In kernel/trace/power-traces.c (c0486428)
Location: include/linux/perf_event.h:1100
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
In kernel/trace/rpm-traces.c (c0487f2c)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/bpf/core.c (c048fa64)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/rseq.c (c04d91cc)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (c04da518)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (c04e2ec0)
Location: include/linux/perf_event.h:1100
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
In mm/swap.c (c04eb864)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (c04f0604)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
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
```
```
In mm/percpu.c (c05055f8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (c0509308)
Location: include/linux/perf_event.h:1100
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
In mm/compaction.c (c050c9c8)
Location: include/linux/perf_event.h:1100
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
In mm/migrate.c (c0550bf0)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/page_isolation.c (c055e5ac)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (c05626a0)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (c0568734)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/fs-writeback.c (c059f828)
Location: include/linux/perf_event.h:1100
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
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
```
```
In fs/locks.c (c05e0720)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (c0670b60)
Location: include/linux/perf_event.h:1100
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
In fs/jbd2/journal.c (c0695fa4)
Location: include/linux/perf_event.h:1100
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
In block/blk-core.c (c078d2b8)
Location: include/linux/perf_event.h:1100
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
In block/blk-iocost.c (c07c087c)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_activate
```
```
In block/blk-wbt.c (c07c81e0)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In drivers/gpio/gpiolib.c (c085d16c)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (c08ee558)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/dma/tegra20-apb-dma.c (c092c740)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/dma/tegra20-apb-dma.c:perf_trace_tegra_dma_isr
  - drivers/dma/tegra20-apb-dma.c:perf_trace_tegra_dma_complete_cb
  - drivers/dma/tegra20-apb-dma.c:perf_trace_tegra_dma_tx_status
```
```
In drivers/regulator/core.c (c094cb7c)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (c09a8bc8)
Location: include/linux/perf_event.h:1100
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
In drivers/iommu/iommu-traces.c (c09bf61c)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (c09f8fe4)
Location: include/linux/perf_event.h:1100
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
In drivers/dma-buf/dma-fence.c (c0a3df84)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (c0a41714)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (c0a427e8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (c0a667e8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (c0ab1260)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (c0abe498)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (c0b5acdc)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
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
```
```
In drivers/usb/musb/musb_trace.c (c0b67e78)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/usb/musb/musb_trace.c:perf_trace_musb_req
  - drivers/usb/musb/musb_trace.c:perf_trace_musb_urb
  - drivers/usb/musb/musb_trace.c:perf_trace_musb_isr
  - drivers/usb/musb/musb_trace.c:perf_trace_musb_regl
  - drivers/usb/musb/musb_trace.c:perf_trace_musb_regw
  - drivers/usb/musb/musb_trace.c:perf_trace_musb_regb
  - drivers/usb/musb/musb_trace.c:perf_trace_musb_log
```
```
In drivers/usb/gadget/udc/trace.c (c0b748c0)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/usb/gadget/udc/trace.c:perf_trace_udc_log_req
  - drivers/usb/gadget/udc/trace.c:perf_trace_udc_log_ep
  - drivers/usb/gadget/udc/trace.c:perf_trace_udc_log_gadget
```
```
In drivers/rtc/interface.c (c0b8643c)
Location: include/linux/perf_event.h:1100
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
In drivers/i2c/i2c-core-base.c (c0b902b4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (c0b945d4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (c0bb2078)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (c0bb5328)
Location: include/linux/perf_event.h:1100
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
In drivers/thermal/power_allocator.c (c0bbac68)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (c0c08de4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (c0c5f3a0)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_cmd_class
```
```
In drivers/devfreq/devfreq.c (c0c69734)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/ras/ras.c (c0c7fa68)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
```
```
In sound/soc/soc-core.c (c0ca4a40)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - sound/soc/soc-core.c:perf_trace_snd_soc_jack_notify
  - sound/soc/soc-core.c:perf_trace_snd_soc_jack_report
  - sound/soc/soc-core.c:perf_trace_snd_soc_jack_irq
  - sound/soc/soc-core.c:perf_trace_snd_soc_dapm_connected
  - sound/soc/soc-core.c:perf_trace_snd_soc_dapm_path
  - sound/soc/soc-core.c:perf_trace_snd_soc_dapm_walk_done
  - sound/soc/soc-core.c:perf_trace_snd_soc_dapm_widget
  - sound/soc/soc-core.c:perf_trace_snd_soc_dapm_basic
  - sound/soc/soc-core.c:perf_trace_snd_soc_card
```
```
In net/core/net-traces.c (c0d2f324)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
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
```
```
In net/core/devlink.c (c0d3ed2c)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/bpf/test_run.c (c0d622e4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (c0e12238)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (c00000000000f580)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/powerpc/kernel/ptrace.c (c0000000000116d0)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/powerpc/kernel/ptrace.c:perf_trace_sys_exit
  - arch/powerpc/kernel/ptrace.c:perf_trace_sys_enter
```
```
In arch/powerpc/kernel/irq.c (c00000000001a358)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/powerpc/kernel/irq.c:perf_trace_tlbia
  - arch/powerpc/kernel/irq.c:perf_trace_tlbie
  - arch/powerpc/kernel/irq.c:perf_trace_hash_fault
  - arch/powerpc/kernel/irq.c:perf_trace_opal_exit
  - arch/powerpc/kernel/irq.c:perf_trace_opal_entry
  - arch/powerpc/kernel/irq.c:perf_trace_hcall_exit
  - arch/powerpc/kernel/irq.c:perf_trace_hcall_entry
  - arch/powerpc/kernel/irq.c:perf_trace_ppc64_interrupt_class
```
```
In arch/powerpc/mm/book3s64/hash_pgtable.c (c00000000008ac90)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_pgtable.c:perf_trace_hugepage_splitting
  - arch/powerpc/mm/book3s64/hash_pgtable.c:perf_trace_hugepage_update
  - arch/powerpc/mm/book3s64/hash_pgtable.c:perf_trace_hugepage_set_pmd
  - arch/powerpc/mm/book3s64/hash_pgtable.c:perf_trace_hugepage_invalidate
```
```
In arch/powerpc/platforms/powernv/vas-window.c (c0000000000e1a70)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/vas-window.c:perf_trace_vas_paste_crb
  - arch/powerpc/platforms/powernv/vas-window.c:perf_trace_vas_tx_win_open
  - arch/powerpc/platforms/powernv/vas-window.c:perf_trace_vas_rx_win_open
```
```
In kernel/fork.c (c0000000001369d0)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (c00000000013cff0)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (c0000000001455f8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (c0000000001518d8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (c000000000164518)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/sched/core.c (c000000000ee2a94)
Location: include/linux/perf_event.h:1100
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
In kernel/printk/printk.c (c0000000001cab1c)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/rcu/update.c (c0000000001e2738)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (c0000000001f661c)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (c0000000001fd460)
Location: include/linux/perf_event.h:1100
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
In kernel/time/alarmtimer.c (c00000000020bb30)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (c000000000228450)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (c00000000023a560)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_event_perf.c (c0000000002cdfbc)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/bpf_trace.c (c0000000002ea65c)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
```
```
In kernel/trace/power-traces.c (c0000000002f26f0)
Location: include/linux/perf_event.h:1100
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
In kernel/trace/rpm-traces.c (c0000000002f4824)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/bpf/core.c (c000000000300700)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/rseq.c (c000000000360090)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (c000000000361be0)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (c00000000036d4b0)
Location: include/linux/perf_event.h:1100
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
In mm/swap.c (c000000000378ea8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (c000000000380df8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
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
```
```
In mm/percpu.c (c0000000003a0a68)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (c0000000003a5e98)
Location: include/linux/perf_event.h:1100
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
In mm/compaction.c (c0000000003aad48)
Location: include/linux/perf_event.h:1100
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
In mm/migrate.c (c000000000430ee0)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (c000000000444bc0)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (c000000000462b38)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (c000000000468cd8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (c000000000473540)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/fs-writeback.c (c0000000004c27e8)
Location: include/linux/perf_event.h:1100
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
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
```
```
In fs/dax.c (c000000000511818)
Location: include/linux/perf_event.h:1100
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
In fs/locks.c (c000000000522c18)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (c0000000005deb88)
Location: include/linux/perf_event.h:1100
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
In fs/jbd2/journal.c (c00000000060da00)
Location: include/linux/perf_event.h:1100
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
In block/blk-core.c (c000000000772d98)
Location: include/linux/perf_event.h:1100
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
In block/blk-iocost.c (c0000000007b45f4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_activate
```
```
In block/blk-wbt.c (c0000000007c0440)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In drivers/gpio/gpiolib.c (c0000000008394d8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/regulator/core.c (c0000000008ddd28)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (c000000000944a68)
Location: include/linux/perf_event.h:1100
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
In drivers/iommu/iommu-traces.c (c00000000096fcd4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (c0000000009b5110)
Location: include/linux/perf_event.h:1100
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
In drivers/dma-buf/dma-fence.c (c000000000a1f284)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (c000000000a24528)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (c000000000a25ca8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (c000000000a588e8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (c000000000a870d8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (c000000000a98358)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/vfio/pci/vfio_pci_nvlink2.c (c000000000abd7a8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_nvlink2.c:perf_trace_vfio_pci_npu2_mmap
  - drivers/vfio/pci/vfio_pci_nvlink2.c:perf_trace_vfio_pci_nvgpu_mmap
  - drivers/vfio/pci/vfio_pci_nvlink2.c:perf_trace_vfio_pci_nvgpu_mmap_fault
```
```
In drivers/usb/host/xhci-trace.c (c000000000b625f8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
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
```
```
In drivers/rtc/interface.c (c000000000b88c08)
Location: include/linux/perf_event.h:1100
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
In drivers/i2c/i2c-core-base.c (c000000000b90bc8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (c000000000b96ad8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (c000000000bb5d0c)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (c000000000bb93c8)
Location: include/linux/perf_event.h:1100
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
In drivers/thermal/power_allocator.c (c000000000bc25c8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (c000000000c26abc)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/devfreq/devfreq.c (c000000000c65154)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/ras/ras.c (c000000000c6fa08)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
```
```
In net/core/net-traces.c (c000000000d0625c)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
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
```
```
In net/core/devlink.c (c000000000d1c324)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/bpf/test_run.c (c000000000d51e18)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (c000000000e36fb0)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffe0000b3ef6)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/riscv/kernel/ptrace.c (ffffffe0000b5c00)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/riscv/kernel/ptrace.c:perf_trace_sys_exit
  - arch/riscv/kernel/ptrace.c:perf_trace_sys_enter
```
```
In kernel/fork.c (ffffffe0000be55a)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffe0000c2a48)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffe0000c6966)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffe0000cd248)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffe0000d6448)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/sched/core.c (ffffffe0008c5208)
Location: include/linux/perf_event.h:1100
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
In kernel/printk/printk.c (ffffffe00010e13e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/rcu/update.c (ffffffe00011dcc6)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffe000127e4a)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffffffe00012b71c)
Location: include/linux/perf_event.h:1100
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
In kernel/time/alarmtimer.c (ffffffe0001345a8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffe0001414ba)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffe0001489b4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_event_perf.c (ffffffe000193d42)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/power-traces.c (ffffffe000198748)
Location: include/linux/perf_event.h:1100
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
In kernel/trace/rpm-traces.c (ffffffe000199db4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/bpf/core.c (ffffffe00019ade8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In mm/filemap.c (ffffffe0001d3ff8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffe0001da9ac)
Location: include/linux/perf_event.h:1100
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
In mm/swap.c (ffffffe0001e1cda)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffe0001e5f84)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
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
```
```
In mm/percpu.c (ffffffe0001f834e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffe0001fb486)
Location: include/linux/perf_event.h:1100
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
In mm/compaction.c (ffffffe0001fdfce)
Location: include/linux/perf_event.h:1100
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
In mm/migrate.c (ffffffe00023dff2)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/page_isolation.c (ffffffe00024abe0)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffe00024ecb8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffe000252d4e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/fs-writeback.c (ffffffe000282c06)
Location: include/linux/perf_event.h:1100
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
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
```
```
In fs/dax.c (ffffffe0002b19a8)
Location: include/linux/perf_event.h:1100
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
In fs/locks.c (ffffffe0002bbca8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffe00032ca58)
Location: include/linux/perf_event.h:1100
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
In fs/jbd2/journal.c (ffffffe00034a560)
Location: include/linux/perf_event.h:1100
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
In block/blk-core.c (ffffffe000422d32)
Location: include/linux/perf_event.h:1100
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
In block/blk-iocost.c (ffffffe00044be9c)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_activate
```
```
In block/blk-wbt.c (ffffffe000452eae)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In drivers/gpio/gpiolib.c (ffffffe0004a435e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffe00050ab62)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffe000521758)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffe00056101c)
Location: include/linux/perf_event.h:1100
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
In drivers/base/regmap/regmap.c (ffffffe00059526c)
Location: include/linux/perf_event.h:1100
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
In drivers/dma-buf/dma-fence.c (ffffffe0005d37de)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffe0005d61fe)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffe0005d7cba)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffe0005f7942)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffe0006173b8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffe000622c3e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffe00069d200)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
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
```
```
In drivers/rtc/interface.c (ffffffe0006b3482)
Location: include/linux/perf_event.h:1100
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
In drivers/i2c/i2c-core-base.c (ffffffe0006b7024)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffe0006bad90)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffe0006cdc88)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffe0006cead0)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffe0006d4f76)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffe0007065d8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/devfreq/devfreq.c (ffffffe00072f7f6)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/ras/ras.c (ffffffe000735b00)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
```
```
In net/core/net-traces.c (ffffffe000791e1e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
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
```
```
In net/core/devlink.c (ffffffe00079e33a)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/bpf/test_run.c (ffffffe0007bd672)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (ffffffe0008533dc)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
</details>
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
In init/main.c (ffffffff81002239)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/common.c (ffffffff810038f9)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004f64)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff8102a469)
Location: include/linux/perf_event.h:1100
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
In arch/x86/hyperv/mmu.c (ffffffff8102e29b)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff810334f2)
Location: include/linux/perf_event.h:1100
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
In arch/x86/kernel/nmi.c (ffffffff81035f6e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e388)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c8ed)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105f539)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff8107ca39)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff8107e78e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff8108c374)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff81096332)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff8109b6d2)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff810a0d94)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810a9972)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810b9814)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/sched/core.c (ffffffff81a6ea4a)
Location: include/linux/perf_event.h:1100
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
In kernel/printk/printk.c (ffffffff81109f4c)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff8111ab25)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff8111bb94)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff81128437)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffffffff8112d2e9)
Location: include/linux/perf_event.h:1100
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
In kernel/time/alarmtimer.c (ffffffff81137499)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff8114af4d)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff81157b55)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_event_perf.c (ffffffff811b7356)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/bpf_trace.c (ffffffff811c69df)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
```
```
In kernel/trace/power-traces.c (ffffffff811cba4c)
Location: include/linux/perf_event.h:1100
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
In kernel/trace/rpm-traces.c (ffffffff811cd1ec)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/bpf/core.c (ffffffff811d4089)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/rseq.c (ffffffff81217de2)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff81218f41)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff81220be8)
Location: include/linux/perf_event.h:1100
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
In mm/swap.c (ffffffff81228b24)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8122de9e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
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
```
```
In mm/percpu.c (ffffffff81243484)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff81246abd)
Location: include/linux/perf_event.h:1100
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
In mm/compaction.c (ffffffff81249d3e)
Location: include/linux/perf_event.h:1100
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
In mm/migrate.c (ffffffff812a5352)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff812b2af2)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff812c593e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff812c979e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff812d0f16)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/fs-writeback.c (ffffffff813067c8)
Location: include/linux/perf_event.h:1100
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
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
```
```
In fs/dax.c (ffffffff8133ebde)
Location: include/linux/perf_event.h:1100
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
In fs/locks.c (ffffffff8134ab42)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff813ce37e)
Location: include/linux/perf_event.h:1100
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
In fs/jbd2/journal.c (ffffffff813efd29)
Location: include/linux/perf_event.h:1100
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
In block/blk-core.c (ffffffff814db717)
Location: include/linux/perf_event.h:1100
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
In block/blk-iocost.c (ffffffff81509b22)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_activate
```
```
In block/blk-wbt.c (ffffffff8151158a)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff81555b1e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff8155f5ee)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff8161640d)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff8163f8c7)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff816818ce)
Location: include/linux/perf_event.h:1100
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
In drivers/iommu/iommu-traces.c (ffffffff816a1fc8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/iommu/intel-trace.c (ffffffff816b694d)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/iommu/intel-trace.c:perf_trace_dma_unmap
  - drivers/iommu/intel-trace.c:perf_trace_dma_map
```
```
In drivers/base/regmap/regmap.c (ffffffff816e54c8)
Location: include/linux/perf_event.h:1100
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
In drivers/dma-buf/dma-fence.c (ffffffff8171b503)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8171e10a)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff8171f5f4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/nvme/host/core.c (ffffffff817458e6)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:perf_trace_nvme_sq
  - drivers/nvme/host/core.c:perf_trace_nvme_async_event
  - drivers/nvme/host/core.c:perf_trace_nvme_complete_rq
  - drivers/nvme/host/core.c:perf_trace_nvme_setup_cmd
```
```
In drivers/ata/libata-core.c (ffffffff81752628)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff81777a12)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff817823be)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81801148)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
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
```
```
In drivers/rtc/interface.c (ffffffff81818b64)
Location: include/linux/perf_event.h:1100
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
In drivers/hwmon/hwmon.c (ffffffff8182b13c)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff8182d110)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff81831d0a)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff81877bf9)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff81892c44)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_cmd_class
```
```
In drivers/devfreq/devfreq.c (ffffffff8189b00f)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/ras/ras.c (ffffffff818a055e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
```
```
In net/core/net-traces.c (ffffffff819114c3)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
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
```
```
In net/core/devlink.c (ffffffff8191f895)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/bpf/test_run.c (ffffffff81943744)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (ffffffff819e86fe)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
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
In init/main.c (ffffffff81000729)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/common.c (ffffffff81001dd9)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81003644)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/hyperv/mmu.c (ffffffff8101dc5b)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff81022e32)
Location: include/linux/perf_event.h:1100
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
In arch/x86/kernel/nmi.c (ffffffff810258be)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8102db88)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103bc9d)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8104f869)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff8106c1a9)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff8106d87e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff8107aea4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff81084db2)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff8108a102)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff8108f7b4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff81098322)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810a8154)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/sched/core.c (ffffffff81a2ae33)
Location: include/linux/perf_event.h:1100
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
In kernel/printk/printk.c (ffffffff810fae2c)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff8110bb95)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff8110cc04)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff8111acc7)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffffffff8111fb59)
Location: include/linux/perf_event.h:1100
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
In kernel/time/alarmtimer.c (ffffffff81129ee9)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff8113e1fd)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff8114ae75)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_event_perf.c (ffffffff811aa136)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/bpf_trace.c (ffffffff811b97bf)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
```
```
In kernel/trace/power-traces.c (ffffffff811be81c)
Location: include/linux/perf_event.h:1100
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
In kernel/trace/rpm-traces.c (ffffffff811bffbc)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/bpf/core.c (ffffffff811c6e49)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/context_tracking.c (ffffffff8120a764)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/context_tracking.c:perf_trace_context_tracking_user
```
```
In kernel/rseq.c (ffffffff8120aff2)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff8120c151)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff81213d98)
Location: include/linux/perf_event.h:1100
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
In mm/swap.c (ffffffff8121bc64)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81220f5e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
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
```
```
In mm/percpu.c (ffffffff81236454)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff81239a6d)
Location: include/linux/perf_event.h:1100
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
In mm/compaction.c (ffffffff8123ccee)
Location: include/linux/perf_event.h:1100
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
In mm/migrate.c (ffffffff81296e22)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff812a3e72)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff812b697e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff812ba7de)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff812c1b96)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/fs-writeback.c (ffffffff812f73e8)
Location: include/linux/perf_event.h:1100
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
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
```
```
In fs/dax.c (ffffffff8132f89e)
Location: include/linux/perf_event.h:1100
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
In fs/locks.c (ffffffff8133b822)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff813bedfe)
Location: include/linux/perf_event.h:1100
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
In fs/jbd2/journal.c (ffffffff813e07a9)
Location: include/linux/perf_event.h:1100
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
In block/blk-core.c (ffffffff814cc0c7)
Location: include/linux/perf_event.h:1100
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
In block/blk-iocost.c (ffffffff814f9fd2)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_activate
```
```
In block/blk-wbt.c (ffffffff815018aa)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff81545cfe)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff8155043e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff8160a93d)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff8161fca7)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff8165f74e)
Location: include/linux/perf_event.h:1100
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
In drivers/iommu/iommu-traces.c (ffffffff8167f9b8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/iommu/intel-trace.c (ffffffff8169458d)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/iommu/intel-trace.c:perf_trace_dma_unmap
  - drivers/iommu/intel-trace.c:perf_trace_dma_map
```
```
In drivers/base/regmap/regmap.c (ffffffff816bfb08)
Location: include/linux/perf_event.h:1100
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
In drivers/dma-buf/dma-fence.c (ffffffff816f4963)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816f768a)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff816f8a24)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/nvme/host/core.c (ffffffff81727576)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:perf_trace_nvme_sq
  - drivers/nvme/host/core.c:perf_trace_nvme_async_event
  - drivers/nvme/host/core.c:perf_trace_nvme_complete_rq
  - drivers/nvme/host/core.c:perf_trace_nvme_setup_cmd
```
```
In drivers/ata/libata-core.c (ffffffff817324c8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff817577c2)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff8176214e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff817c62e8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
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
```
```
In drivers/rtc/interface.c (ffffffff817e0254)
Location: include/linux/perf_event.h:1100
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
In drivers/hwmon/hwmon.c (ffffffff817f27cc)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff817f47a0)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff817f939a)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/hv/hv_trace.c (ffffffff81854a84)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/hv/hv_trace.c:perf_trace_vmbus_channel
  - drivers/hv/hv_trace.c:perf_trace_vmbus_send_tl_connect_request
  - drivers/hv/hv_trace.c:perf_trace_vmbus_release_relid
  - drivers/hv/hv_trace.c:perf_trace_vmbus_negotiate_version
  - drivers/hv/hv_trace.c:perf_trace_vmbus_teardown_gpadl
  - drivers/hv/hv_trace.c:perf_trace_vmbus_establish_gpadl_body
  - drivers/hv/hv_trace.c:perf_trace_vmbus_establish_gpadl_header
  - drivers/hv/hv_trace.c:perf_trace_vmbus_close_internal
  - drivers/hv/hv_trace.c:perf_trace_vmbus_open
  - drivers/hv/hv_trace.c:perf_trace_vmbus_request_offers
  - drivers/hv/hv_trace.c:perf_trace_vmbus_onversion_response
  - drivers/hv/hv_trace.c:perf_trace_vmbus_ongpadl_torndown
  - drivers/hv/hv_trace.c:perf_trace_vmbus_ongpadl_created
  - drivers/hv/hv_trace.c:perf_trace_vmbus_onopen_result
  - drivers/hv/hv_trace.c:perf_trace_vmbus_onoffer_rescind
  - drivers/hv/hv_trace.c:perf_trace_vmbus_onoffer
  - drivers/hv/hv_trace.c:perf_trace_vmbus_hdr_msg
```
```
In drivers/devfreq/devfreq.c (ffffffff818584df)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/ras/ras.c (ffffffff8185bcce)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
```
```
In net/core/net-traces.c (ffffffff818cb283)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
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
```
```
In net/core/devlink.c (ffffffff818d9645)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/bpf/test_run.c (ffffffff818fd234)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (ffffffff819a54be)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
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
In init/main.c (ffffffff81002239)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/common.c (ffffffff810038f9)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004f24)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff8102a2c9)
Location: include/linux/perf_event.h:1100
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
In arch/x86/hyperv/mmu.c (ffffffff8102e0fb)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff81033352)
Location: include/linux/perf_event.h:1100
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
In arch/x86/kernel/nmi.c (ffffffff81035dce)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e1c8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c72d)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105f969)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff8107c9e9)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff8107e73e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff8108c324)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff810962e2)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff8109b682)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff810a0d44)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810a8ed2)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810b8d74)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/sched/core.c (ffffffff81adae5a)
Location: include/linux/perf_event.h:1100
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
In kernel/printk/printk.c (ffffffff81107e3c)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff81118a15)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff81119a84)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff81126157)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffffffff8112b009)
Location: include/linux/perf_event.h:1100
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
In kernel/time/alarmtimer.c (ffffffff811351b9)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff81148dfd)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff81155925)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_event_perf.c (ffffffff811b5126)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/bpf_trace.c (ffffffff811c47af)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
```
```
In kernel/trace/power-traces.c (ffffffff811c981c)
Location: include/linux/perf_event.h:1100
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
In kernel/trace/rpm-traces.c (ffffffff811cafbc)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/bpf/core.c (ffffffff811d1e59)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/rseq.c (ffffffff81215b82)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff81216ce1)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff8121e988)
Location: include/linux/perf_event.h:1100
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
In mm/swap.c (ffffffff812268c4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8122bc3e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
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
```
```
In mm/percpu.c (ffffffff81241224)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff8124485d)
Location: include/linux/perf_event.h:1100
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
In mm/compaction.c (ffffffff81247ade)
Location: include/linux/perf_event.h:1100
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
In mm/migrate.c (ffffffff812a3162)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff812b0902)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff812c374e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff812c75ae)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff812ced26)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/fs-writeback.c (ffffffff813045b8)
Location: include/linux/perf_event.h:1100
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
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
```
```
In fs/dax.c (ffffffff8133c6ae)
Location: include/linux/perf_event.h:1100
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
In fs/locks.c (ffffffff81348612)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff813cb80e)
Location: include/linux/perf_event.h:1100
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
In fs/jbd2/journal.c (ffffffff813ed0a9)
Location: include/linux/perf_event.h:1100
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
In block/blk-core.c (ffffffff814d77a7)
Location: include/linux/perf_event.h:1100
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
In block/blk-iocost.c (ffffffff81505bb2)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_activate
```
```
In block/blk-wbt.c (ffffffff8150d61a)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff8155185e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff8155e15e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff816441ed)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff8166dc07)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff816afcae)
Location: include/linux/perf_event.h:1100
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
In drivers/iommu/iommu-traces.c (ffffffff816d0238)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/iommu/intel-trace.c (ffffffff816e4e1d)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/iommu/intel-trace.c:perf_trace_dma_unmap
  - drivers/iommu/intel-trace.c:perf_trace_dma_map
```
```
In drivers/base/regmap/regmap.c (ffffffff81712658)
Location: include/linux/perf_event.h:1100
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
In drivers/dma-buf/dma-fence.c (ffffffff8175a2d3)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8175ceda)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff8175e3c4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff81782318)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff817a7db2)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff817b276e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff8183dc18)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
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
```
```
In drivers/rtc/interface.c (ffffffff8185a044)
Location: include/linux/perf_event.h:1100
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
In drivers/i2c/i2c-core-base.c (ffffffff8185fc5e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81863a0a)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff8187a76c)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff8187c740)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff8188133a)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff818c9099)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff818e6744)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_cmd_class
```
```
In drivers/devfreq/devfreq.c (ffffffff818ea6ff)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/ras/ras.c (ffffffff818f16fe)
Location: include/linux/perf_event.h:1100
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
In net/core/net-traces.c (ffffffff819624f3)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
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
```
```
In net/core/devlink.c (ffffffff81970a25)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/bpf/test_run.c (ffffffff819948d4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (ffffffff81a5317e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
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
In init/main.c (ffffffff81002239)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/common.c (ffffffff810039c9)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005064)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff8102b0b9)
Location: include/linux/perf_event.h:1100
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
In arch/x86/hyperv/mmu.c (ffffffff8102eeeb)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff810342b2)
Location: include/linux/perf_event.h:1100
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
In arch/x86/kernel/nmi.c (ffffffff81036dae)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103f348)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104db3d)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060ec9)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff8107eae9)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff8108082e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff8108e684)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff8109df02)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff810a32f2)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff810a8cc4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810b1022)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810c17d4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/sched/core.c (ffffffff81ae731c)
Location: include/linux/perf_event.h:1100
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
In kernel/printk/printk.c (ffffffff811131dc)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff811240a5)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff811251f4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff81132797)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffffffff81137419)
Location: include/linux/perf_event.h:1100
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
In kernel/time/alarmtimer.c (ffffffff81141bd9)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff81155a1d)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff81163095)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_event_perf.c (ffffffff811c31c6)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/bpf_trace.c (ffffffff811d264f)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
```
```
In kernel/trace/power-traces.c (ffffffff811d7a7c)
Location: include/linux/perf_event.h:1100
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
In kernel/trace/rpm-traces.c (ffffffff811d921c)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/bpf/core.c (ffffffff811e0149)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/rseq.c (ffffffff81224b82)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff81225d61)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff8122d9d8)
Location: include/linux/perf_event.h:1100
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
In mm/swap.c (ffffffff81235bf4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8123b02e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
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
```
```
In mm/percpu.c (ffffffff812509a4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff8125401d)
Location: include/linux/perf_event.h:1100
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
In mm/compaction.c (ffffffff8125730e)
Location: include/linux/perf_event.h:1100
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
In mm/migrate.c (ffffffff812b33f2)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff812c0c42)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff812d41ee)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff812d829e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff812dfb36)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/fs-writeback.c (ffffffff81315928)
Location: include/linux/perf_event.h:1100
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
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
```
```
In fs/dax.c (ffffffff8134f85e)
Location: include/linux/perf_event.h:1100
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
In fs/locks.c (ffffffff8135b952)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff813e0a5e)
Location: include/linux/perf_event.h:1100
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
In fs/jbd2/journal.c (ffffffff81402a79)
Location: include/linux/perf_event.h:1100
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
In block/blk-core.c (ffffffff814f03b7)
Location: include/linux/perf_event.h:1100
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
In block/blk-iocost.c (ffffffff81521452)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_activate
```
```
In block/blk-wbt.c (ffffffff81526c3a)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff8156b56e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff81577fee)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff8165e62d)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff81688267)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff816ca30e)
Location: include/linux/perf_event.h:1100
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
In drivers/iommu/iommu-traces.c (ffffffff816ea7c8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/iommu/intel-trace.c (ffffffff816ff4dd)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/iommu/intel-trace.c:perf_trace_dma_unmap
  - drivers/iommu/intel-trace.c:perf_trace_dma_map
```
```
In drivers/base/regmap/regmap.c (ffffffff8172d848)
Location: include/linux/perf_event.h:1100
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
In drivers/dma-buf/dma-fence.c (ffffffff81775893)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff817786aa)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff81779a24)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff8179c108)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff817c1c32)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff817cc6fe)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff818580e8)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
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
```
```
In drivers/rtc/interface.c (ffffffff81875124)
Location: include/linux/perf_event.h:1100
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
In drivers/i2c/i2c-core-base.c (ffffffff8187ae6e)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8187ec6a)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff8189616c)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff81898170)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff8189cdaa)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff818e5bb9)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff819033c4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_cmd_class
```
```
In drivers/devfreq/devfreq.c (ffffffff8190b77f)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/ras/ras.c (ffffffff8191277e)
Location: include/linux/perf_event.h:1100
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
In net/core/net-traces.c (ffffffff81984763)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
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
```
```
In net/core/devlink.c (ffffffff81992f15)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/bpf/test_run.c (ffffffff819b73e4)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (ffffffff81a5f0ce)
Location: include/linux/perf_event.h:1100
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
</details>
</li>
</ul>

## Differences
