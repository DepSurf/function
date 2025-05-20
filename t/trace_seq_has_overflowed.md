# Function: <code>trace_seq_has_overflowed</code>

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
In arch/x86/entry/common.c (ffffffff8100306f)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - arch/x86/entry/common.c:trace_raw_output_sys_enter
  - arch/x86/entry/common.c:trace_raw_output_sys_exit
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810045cb)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:trace_raw_output_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff810268ac)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mc__batch
  - arch/x86/xen/trace.c:trace_raw_output_xen_mc_entry
  - arch/x86/xen/trace.c:trace_raw_output_xen_mc_entry_alloc
  - arch/x86/xen/trace.c:trace_raw_output_xen_mc_callback
  - arch/x86/xen/trace.c:trace_raw_output_xen_mc_flush_reason
  - arch/x86/xen/trace.c:trace_raw_output_xen_mc_flush
  - arch/x86/xen/trace.c:trace_raw_output_xen_mc_extend_args
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_domain_pte
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pte_at
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_pte_clear
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_pmd_clear
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pgd
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_pud_clear
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_pgd_clear
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_alloc_ptpage
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_pgd
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_flush_tlb
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_flush_tlb_single
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:trace_raw_output_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:trace_raw_output_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:trace_raw_output_xen_cpu_load_idt
  - arch/x86/xen/trace.c:trace_raw_output_xen_cpu_write_gdt_entry
  - arch/x86/xen/trace.c:trace_raw_output_xen_cpu_set_ldt
```
```
In arch/x86/kernel/irq.c (ffffffff8103004b)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:trace_raw_output_x86_irq_vector
```
```
In arch/x86/kernel/nmi.c (ffffffff81032315)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:trace_raw_output_nmi_handler
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81043a19)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:trace_raw_output_mce_record
```
```
In arch/x86/mm/init.c (ffffffff81068a2d)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - arch/x86/mm/init.c:trace_raw_output_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff8106a0f5)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:trace_raw_output_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff81074ea8)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:trace_raw_output_mpx_bounds_register_exception
  - arch/x86/mm/mpx.c:trace_raw_output_bounds_exception_mpx
  - arch/x86/mm/mpx.c:trace_raw_output_mpx_range_trace
  - arch/x86/mm/mpx.c:trace_raw_output_mpx_new_bounds_table
```
```
In kernel/fork.c (ffffffff8107d69b)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/fork.c:trace_raw_output_task_newtask
  - kernel/fork.c:trace_raw_output_task_rename
```
```
In kernel/softirq.c (ffffffff81084b54)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/softirq.c:trace_raw_output_irq_handler_entry
  - kernel/softirq.c:trace_raw_output_irq_handler_exit
  - kernel/softirq.c:trace_raw_output_softirq
```
```
In kernel/signal.c (ffffffff8108cccc)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/signal.c:trace_raw_output_signal_generate
  - kernel/signal.c:trace_raw_output_signal_deliver
```
```
In kernel/workqueue.c (ffffffff81096fda)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/workqueue.c:trace_raw_output_workqueue_queue_work
  - kernel/workqueue.c:trace_raw_output_workqueue_work
  - kernel/workqueue.c:trace_raw_output_workqueue_execute_start
```
```
In kernel/sched/core.c (ffffffff810a4e80)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/sched/core.c:trace_raw_output_sched_kthread_stop
  - kernel/sched/core.c:trace_raw_output_sched_kthread_stop_ret
  - kernel/sched/core.c:trace_raw_output_sched_wakeup_template
  - kernel/sched/core.c:trace_raw_output_sched_migrate_task
  - kernel/sched/core.c:trace_raw_output_sched_process_template
  - kernel/sched/core.c:trace_raw_output_sched_process_wait
  - kernel/sched/core.c:trace_raw_output_sched_process_fork
  - kernel/sched/core.c:trace_raw_output_sched_process_exec
  - kernel/sched/core.c:trace_raw_output_sched_stat_template
  - kernel/sched/core.c:trace_raw_output_sched_stat_runtime
  - kernel/sched/core.c:trace_raw_output_sched_pi_setprio
  - kernel/sched/core.c:trace_raw_output_sched_process_hang
  - kernel/sched/core.c:trace_raw_output_sched_move_task_template
  - kernel/sched/core.c:trace_raw_output_sched_swap_numa
  - kernel/sched/core.c:trace_raw_output_sched_wake_idle_without_ipi
  - kernel/sched/core.c:trace_raw_output_sched_switch
```
```
In kernel/printk/printk.c (ffffffff810d68bf)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/printk/printk.c:trace_raw_output_console
```
```
In kernel/rcu/update.c (ffffffff810e345b)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/rcu/update.c:trace_raw_output_rcu_utilization
```
```
In kernel/time/timer.c (ffffffff810ebd6b)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/time/timer.c:trace_raw_output_timer_class
  - kernel/time/timer.c:trace_raw_output_timer_start
  - kernel/time/timer.c:trace_raw_output_timer_expire_entry
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/time/timer.c:trace_raw_output_hrtimer_start
  - kernel/time/timer.c:trace_raw_output_hrtimer_expire_entry
  - kernel/time/timer.c:trace_raw_output_hrtimer_class
  - kernel/time/timer.c:trace_raw_output_itimer_state
  - kernel/time/timer.c:trace_raw_output_itimer_expire
  - kernel/time/timer.c:trace_raw_output_tick_stop
```
```
In kernel/module.c (ffffffff81104c6e)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/module.c:trace_raw_output_module_load
  - kernel/module.c:trace_raw_output_module_free
  - kernel/module.c:trace_raw_output_module_refcnt
  - kernel/module.c:trace_raw_output_module_request
```
```
In kernel/trace/ring_buffer.c (ffffffff8114a36a)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
```
```
In kernel/trace/trace.c (ffffffff81150f77)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
```
In kernel/trace/trace_output.c (ffffffff811534ef)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_raw_output_prep
  - kernel/trace/trace_output.c:trace_nop_print
  - kernel/trace/trace_output.c:trace_print_raw
  - kernel/trace/trace_output.c:trace_bprint_raw
  - kernel/trace/trace_output.c:trace_bputs_raw
  - kernel/trace/trace_output.c:trace_ctxwake_raw
  - kernel/trace/trace_output.c:trace_fn_raw
  - kernel/trace/trace_output.c:trace_output_call
  - kernel/trace/trace_output.c:trace_ctxwake_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/trace_output.c:trace_ctxwake_hex
  - kernel/trace/trace_output.c:trace_fn_hex
  - kernel/trace/trace_output.c:trace_print_bputs_msg_only
  - kernel/trace/trace_output.c:trace_print_bprintk_msg_only
  - kernel/trace/trace_output.c:trace_print_printk_msg_only
  - kernel/trace/trace_output.c:seq_print_ip_sym
  - kernel/trace/trace_output.c:trace_print_print
  - kernel/trace/trace_output.c:trace_bprint_print
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_context
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff81158650)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8115a151)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
```
```
In kernel/trace/blktrace.c (ffffffff8115b6be)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:print_one_line
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
```
```
In kernel/trace/trace_syscalls.c (ffffffff81161566)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_syscalls.c:print_syscall_exit
```
```
In kernel/trace/trace_kprobe.c (ffffffff81167f8d)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
```
```
In kernel/trace/power-traces.c (ffffffff811698c0)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:trace_raw_output_cpu
  - kernel/trace/power-traces.c:trace_raw_output_powernv_throttle
  - kernel/trace/power-traces.c:trace_raw_output_pstate_sample
  - kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_end
  - kernel/trace/power-traces.c:trace_raw_output_suspend_resume
  - kernel/trace/power-traces.c:trace_raw_output_wakeup_source
  - kernel/trace/power-traces.c:trace_raw_output_clock
  - kernel/trace/power-traces.c:trace_raw_output_power_domain
  - kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update
  - kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request
```
```
In kernel/trace/rpm-traces.c (ffffffff8116c319)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:trace_raw_output_rpm_internal
  - kernel/trace/rpm-traces.c:trace_raw_output_rpm_return_int
```
```
In kernel/trace/trace_probe.c (ffffffff8116d22a)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_u8
  - kernel/trace/trace_probe.c:print_type_u16
  - kernel/trace/trace_probe.c:print_type_u32
  - kernel/trace/trace_probe.c:print_type_u64
  - kernel/trace/trace_probe.c:print_type_s8
  - kernel/trace/trace_probe.c:print_type_s16
  - kernel/trace/trace_probe.c:print_type_s32
  - kernel/trace/trace_probe.c:print_type_s64
  - kernel/trace/trace_probe.c:print_type_string
```
```
In kernel/trace/trace_uprobe.c (ffffffff8116f0cb)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:print_uprobe_event
```
```
In mm/filemap.c (ffffffff8118c8ee)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - mm/filemap.c:trace_raw_output_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff81190676)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - mm/oom_kill.c:trace_raw_output_oom_score_adj_update
```
```
In mm/swap.c (ffffffff8119c86e)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - mm/swap.c:trace_raw_output_mm_lru_insertion
  - mm/swap.c:trace_raw_output_mm_lru_activate
```
```
In mm/vmscan.c (ffffffff8119fb9b)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - mm/vmscan.c:trace_raw_output_mm_vmscan_kswapd_sleep
  - mm/vmscan.c:trace_raw_output_mm_vmscan_kswapd_wake
  - mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd
  - mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_end_template
  - mm/vmscan.c:trace_raw_output_mm_shrink_slab_end
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate_template
  - mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:trace_raw_output_mm_shrink_slab_start
  - mm/vmscan.c:trace_raw_output_mm_vmscan_writepage
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive
```
```
In mm/slab_common.c (ffffffff811b1ec6)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - mm/slab_common.c:trace_raw_output_kmem_alloc
  - mm/slab_common.c:trace_raw_output_kmem_alloc_node
  - mm/slab_common.c:trace_raw_output_kmem_free
  - mm/slab_common.c:trace_raw_output_mm_page_free
  - mm/slab_common.c:trace_raw_output_mm_page_free_batched
  - mm/slab_common.c:trace_raw_output_mm_page_alloc
  - mm/slab_common.c:trace_raw_output_mm_page
  - mm/slab_common.c:trace_raw_output_mm_page_pcpu_drain
  - mm/slab_common.c:trace_raw_output_mm_page_alloc_extfrag
```
```
In mm/compaction.c (ffffffff811b4f5a)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - mm/compaction.c:trace_raw_output_mm_compaction_isolate_template
  - mm/compaction.c:trace_raw_output_mm_compaction_migratepages
  - mm/compaction.c:trace_raw_output_mm_compaction_begin
  - mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages
  - mm/compaction.c:trace_raw_output_mm_compaction_end
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_defer_template
```
```
In mm/migrate.c (ffffffff811f06fd)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/migrate.c:trace_raw_output_mm_numa_migrate_ratelimit
```
```
In mm/cma.c (ffffffff81206c4a)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - mm/cma.c:trace_raw_output_cma_alloc
  - mm/cma.c:trace_raw_output_cma_release
```
```
In fs/open.c (ffffffff81209429)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - fs/open.c:trace_raw_output_do_sys_open
  - fs/open.c:trace_raw_output_open_exec
```
```
In fs/fs-writeback.c (ffffffff81235215)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_page
  - fs/fs-writeback.c:trace_raw_output_writeback_write_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_pages_written
  - fs/fs-writeback.c:trace_raw_output_writeback_class
  - fs/fs-writeback.c:trace_raw_output_writeback_bdi_register
  - fs/fs-writeback.c:trace_raw_output_wbc_class
  - fs/fs-writeback.c:trace_raw_output_global_dirty_state
  - fs/fs-writeback.c:trace_raw_output_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_raw_output_balance_dirty_pages
  - fs/fs-writeback.c:trace_raw_output_writeback_congest_waited_template
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_lazytime_template
  - fs/fs-writeback.c:trace_raw_output_writeback_work_class
  - fs/fs-writeback.c:trace_raw_output_writeback_queue_io
```
```
In fs/locks.c (ffffffff8125f586)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_generic_add_lease
```
```
In fs/ext4/super.c (ffffffff812a9323)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - fs/ext4/super.c:trace_raw_output_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_raw_output_ext4_free_inode
  - fs/ext4/super.c:trace_raw_output_ext4_request_inode
  - fs/ext4/super.c:trace_raw_output_ext4_allocate_inode
  - fs/ext4/super.c:trace_raw_output_ext4_evict_inode
  - fs/ext4/super.c:trace_raw_output_ext4_drop_inode
  - fs/ext4/super.c:trace_raw_output_ext4_mark_inode_dirty
  - fs/ext4/super.c:trace_raw_output_ext4_begin_ordered_truncate
  - fs/ext4/super.c:trace_raw_output_ext4__write_begin
  - fs/ext4/super.c:trace_raw_output_ext4__write_end
  - fs/ext4/super.c:trace_raw_output_ext4_writepages
  - fs/ext4/super.c:trace_raw_output_ext4_da_write_pages
  - fs/ext4/super.c:trace_raw_output_ext4_writepages_result
  - fs/ext4/super.c:trace_raw_output_ext4__page_op
  - fs/ext4/super.c:trace_raw_output_ext4_invalidatepage_op
  - fs/ext4/super.c:trace_raw_output_ext4_discard_blocks
  - fs/ext4/super.c:trace_raw_output_ext4__mb_new_pa
  - fs/ext4/super.c:trace_raw_output_ext4_mb_release_inode_pa
  - fs/ext4/super.c:trace_raw_output_ext4_mb_release_group_pa
  - fs/ext4/super.c:trace_raw_output_ext4_discard_preallocations
  - fs/ext4/super.c:trace_raw_output_ext4_mb_discard_preallocations
  - fs/ext4/super.c:trace_raw_output_ext4_sync_file_enter
  - fs/ext4/super.c:trace_raw_output_ext4_sync_file_exit
  - fs/ext4/super.c:trace_raw_output_ext4_sync_fs
  - fs/ext4/super.c:trace_raw_output_ext4_alloc_da_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_mballoc_prealloc
  - fs/ext4/super.c:trace_raw_output_ext4__mballoc
  - fs/ext4/super.c:trace_raw_output_ext4_forget
  - fs/ext4/super.c:trace_raw_output_ext4_da_update_reserve_space
  - fs/ext4/super.c:trace_raw_output_ext4_da_reserve_space
  - fs/ext4/super.c:trace_raw_output_ext4_da_release_space
  - fs/ext4/super.c:trace_raw_output_ext4__bitmap_load
  - fs/ext4/super.c:trace_raw_output_ext4_direct_IO_enter
  - fs/ext4/super.c:trace_raw_output_ext4_direct_IO_exit
  - fs/ext4/super.c:trace_raw_output_ext4_fallocate_exit
  - fs/ext4/super.c:trace_raw_output_ext4_unlink_enter
  - fs/ext4/super.c:trace_raw_output_ext4_unlink_exit
  - fs/ext4/super.c:trace_raw_output_ext4__truncate
  - fs/ext4/super.c:trace_raw_output_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:trace_raw_output_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_raw_output_ext4_ext_load_extent
  - fs/ext4/super.c:trace_raw_output_ext4_load_inode
  - fs/ext4/super.c:trace_raw_output_ext4_journal_start
  - fs/ext4/super.c:trace_raw_output_ext4_journal_start_reserved
  - fs/ext4/super.c:trace_raw_output_ext4__trim
  - fs/ext4/super.c:trace_raw_output_ext4_ext_put_in_cache
  - fs/ext4/super.c:trace_raw_output_ext4_ext_in_cache
  - fs/ext4/super.c:trace_raw_output_ext4_find_delalloc_range
  - fs/ext4/super.c:trace_raw_output_ext4_get_reserved_cluster_alloc
  - fs/ext4/super.c:trace_raw_output_ext4_ext_show_extent
  - fs/ext4/super.c:trace_raw_output_ext4_remove_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_ext_rm_leaf
  - fs/ext4/super.c:trace_raw_output_ext4_ext_rm_idx
  - fs/ext4/super.c:trace_raw_output_ext4_ext_remove_space
  - fs/ext4/super.c:trace_raw_output_ext4_ext_remove_space_done
  - fs/ext4/super.c:trace_raw_output_ext4_es_remove_extent
  - fs/ext4/super.c:trace_raw_output_ext4_es_find_delayed_extent_range_enter
  - fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:trace_raw_output_ext4__es_shrink_enter
  - fs/ext4/super.c:trace_raw_output_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:trace_raw_output_ext4_collapse_range
  - fs/ext4/super.c:trace_raw_output_ext4_insert_range
  - fs/ext4/super.c:trace_raw_output_ext4_es_shrink
  - fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent
  - fs/ext4/super.c:trace_raw_output_ext4_request_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_free_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc
  - fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:trace_raw_output_ext4__es_extent
  - fs/ext4/super.c:trace_raw_output_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit
```
```
In fs/jbd2/journal.c (ffffffff812ee39b)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint
  - fs/jbd2/journal.c:trace_raw_output_jbd2_commit
  - fs/jbd2/journal.c:trace_raw_output_jbd2_end_commit
  - fs/jbd2/journal.c:trace_raw_output_jbd2_submit_inode_data
  - fs/jbd2/journal.c:trace_raw_output_jbd2_handle_start
  - fs/jbd2/journal.c:trace_raw_output_jbd2_handle_extend
  - fs/jbd2/journal.c:trace_raw_output_jbd2_handle_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_update_log_tail
  - fs/jbd2/journal.c:trace_raw_output_jbd2_write_superblock
  - fs/jbd2/journal.c:trace_raw_output_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats
```
```
In block/blk-core.c (ffffffff813b47f0)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - block/blk-core.c:trace_raw_output_block_buffer
  - block/blk-core.c:trace_raw_output_block_rq_with_error
  - block/blk-core.c:trace_raw_output_block_rq_complete
  - block/blk-core.c:trace_raw_output_block_rq
  - block/blk-core.c:trace_raw_output_block_bio_bounce
  - block/blk-core.c:trace_raw_output_block_bio_complete
  - block/blk-core.c:trace_raw_output_block_bio_merge
  - block/blk-core.c:trace_raw_output_block_bio_queue
  - block/blk-core.c:trace_raw_output_block_get_rq
  - block/blk-core.c:trace_raw_output_block_plug
  - block/blk-core.c:trace_raw_output_block_unplug
  - block/blk-core.c:trace_raw_output_block_split
  - block/blk-core.c:trace_raw_output_block_bio_remap
  - block/blk-core.c:trace_raw_output_block_rq_remap
```
```
In lib/swiotlb.c (ffffffff81411eb3)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - lib/swiotlb.c:trace_raw_output_swiotlb_bounced
```
```
In drivers/gpio/gpiolib.c (ffffffff81424549)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:trace_raw_output_gpio_direction
  - drivers/gpio/gpiolib.c:trace_raw_output_gpio_value
```
```
In drivers/regulator/core.c (ffffffff814d7acf)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/regulator/core.c:trace_raw_output_regulator_basic
  - drivers/regulator/core.c:trace_raw_output_regulator_range
  - drivers/regulator/core.c:trace_raw_output_regulator_value
```
```
In drivers/char/random.c (ffffffff81511d70)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/char/random.c:trace_raw_output_add_device_randomness
  - drivers/char/random.c:trace_raw_output_random__mix_pool_bytes
  - drivers/char/random.c:trace_raw_output_credit_entropy_bits
  - drivers/char/random.c:trace_raw_output_push_to_pool
  - drivers/char/random.c:trace_raw_output_debit_entropy
  - drivers/char/random.c:trace_raw_output_add_input_randomness
  - drivers/char/random.c:trace_raw_output_add_disk_randomness
  - drivers/char/random.c:trace_raw_output_xfer_secondary_pool
  - drivers/char/random.c:trace_raw_output_random__get_random_bytes
  - drivers/char/random.c:trace_raw_output_random__extract_entropy
  - drivers/char/random.c:trace_raw_output_random_read
  - drivers/char/random.c:trace_raw_output_urandom_read
```
```
In drivers/iommu/iommu-traces.c (ffffffff8152bc04)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:trace_raw_output_iommu_group_event
  - drivers/iommu/iommu-traces.c:trace_raw_output_iommu_device_event
  - drivers/iommu/iommu-traces.c:trace_raw_output_map
  - drivers/iommu/iommu-traces.c:trace_raw_output_unmap
  - drivers/iommu/iommu-traces.c:trace_raw_output_iommu_error
```
```
In drivers/base/regmap/regmap.c (ffffffff81562279)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:trace_raw_output_regmap_reg
  - drivers/base/regmap/regmap.c:trace_raw_output_regmap_block
  - drivers/base/regmap/regmap.c:trace_raw_output_regcache_sync
  - drivers/base/regmap/regmap.c:trace_raw_output_regmap_bool
  - drivers/base/regmap/regmap.c:trace_raw_output_regmap_async
  - drivers/base/regmap/regmap.c:trace_raw_output_regcache_drop_region
```
```
In drivers/dma-buf/fence.c (ffffffff815a3af7)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/dma-buf/fence.c:trace_raw_output_fence_annotate_wait_on
  - drivers/dma-buf/fence.c:trace_raw_output_fence
```
```
In drivers/scsi/scsi.c (ffffffff815a5ffa)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_eh_wakeup
```
```
In drivers/ata/libata-core.c (ffffffff815c7b24)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_complete_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:trace_raw_output_ata_eh_link_autopsy
```
```
In drivers/spi/spi.c (ffffffff815e534b)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/spi/spi.c:trace_raw_output_spi_master
  - drivers/spi/spi.c:trace_raw_output_spi_message
  - drivers/spi/spi.c:trace_raw_output_spi_message_done
  - drivers/spi/spi.c:trace_raw_output_spi_transfer
```
```
In drivers/usb/host/xhci-trace.c (ffffffff816614df)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_msg
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_event
```
```
In drivers/i2c/i2c-core.c (ffffffff81678470)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:trace_raw_output_i2c_write
  - drivers/i2c/i2c-core.c:trace_raw_output_i2c_read
  - drivers/i2c/i2c-core.c:trace_raw_output_i2c_reply
  - drivers/i2c/i2c-core.c:trace_raw_output_i2c_result
  - drivers/i2c/i2c-core.c:trace_raw_output_smbus_write
  - drivers/i2c/i2c-core.c:trace_raw_output_smbus_read
  - drivers/i2c/i2c-core.c:trace_raw_output_smbus_reply
  - drivers/i2c/i2c-core.c:trace_raw_output_smbus_result
```
```
In drivers/thermal/thermal_core.c (ffffffff81682fce)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_temperature
  - drivers/thermal/thermal_core.c:trace_raw_output_cdev_update
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_power_cpu_limit
```
```
In drivers/thermal/power_allocator.c (ffffffff81689bba)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:trace_raw_output_thermal_power_allocator
  - drivers/thermal/power_allocator.c:trace_raw_output_thermal_power_allocator_pid
```
```
In drivers/clk/clk.c (ffffffff816e47df)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/clk/clk.c:trace_raw_output_clk
  - drivers/clk/clk.c:trace_raw_output_clk_rate
  - drivers/clk/clk.c:trace_raw_output_clk_parent
  - drivers/clk/clk.c:trace_raw_output_clk_phase
```
```
In drivers/ras/ras.c (ffffffff816f3158)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/ras/ras.c:trace_raw_output_extlog_mem_event
  - drivers/ras/ras.c:trace_raw_output_mc_event
  - drivers/ras/ras.c:trace_raw_output_aer_event
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
```
```
In net/core/net-traces.c (ffffffff8173ad56)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - net/core/net-traces.c:trace_raw_output_kfree_skb
  - net/core/net-traces.c:trace_raw_output_consume_skb
  - net/core/net-traces.c:trace_raw_output_skb_copy_datagram_iovec
  - net/core/net-traces.c:trace_raw_output_net_dev_start_xmit
  - net/core/net-traces.c:trace_raw_output_net_dev_xmit
  - net/core/net-traces.c:trace_raw_output_net_dev_template
  - net/core/net-traces.c:trace_raw_output_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_raw_output_napi_poll
  - net/core/net-traces.c:trace_raw_output_sock_rcvqueue_full
  - net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_raw_output_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:trace_raw_output_fib_table_lookup
  - net/core/net-traces.c:trace_raw_output_fib_table_lookup_nh
  - net/core/net-traces.c:trace_raw_output_fib_validate_source
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
In arch/x86/entry/common.c (ffffffff810031e0)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - arch/x86/entry/common.c:trace_raw_output_sys_exit
  - arch/x86/entry/common.c:trace_raw_output_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8100471b)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:trace_raw_output_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff81028800)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:trace_raw_output_xen_cpu_write_gdt_entry
  - arch/x86/xen/trace.c:trace_raw_output_xen_cpu_load_idt
  - arch/x86/xen/trace.c:trace_raw_output_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:trace_raw_output_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_flush_tlb_single
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_flush_tlb
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_pgd
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_alloc_ptpage
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_pgd_clear
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_pud_clear
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pgd
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_pmd_clear
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_pte_clear
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pte_at
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_domain_pte
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte
  - arch/x86/xen/trace.c:trace_raw_output_xen_mc_extend_args
  - arch/x86/xen/trace.c:trace_raw_output_xen_mc_flush
  - arch/x86/xen/trace.c:trace_raw_output_xen_mc_flush_reason
  - arch/x86/xen/trace.c:trace_raw_output_xen_mc_callback
  - arch/x86/xen/trace.c:trace_raw_output_xen_mc_entry_alloc
  - arch/x86/xen/trace.c:trace_raw_output_xen_mc_entry
  - arch/x86/xen/trace.c:trace_raw_output_xen_mc__batch
```
```
In arch/x86/kernel/irq.c (ffffffff8102f0bb)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:trace_raw_output_x86_irq_vector
```
```
In arch/x86/kernel/nmi.c (ffffffff81031445)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:trace_raw_output_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81038c47)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:trace_raw_output_x86_fpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81043b49)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:trace_raw_output_mce_record
```
```
In arch/x86/mm/init.c (ffffffff8106870d)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - arch/x86/mm/init.c:trace_raw_output_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff81069e35)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:trace_raw_output_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff8107689b)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:trace_raw_output_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:trace_raw_output_mpx_range_trace
  - arch/x86/mm/mpx.c:trace_raw_output_bounds_exception_mpx
  - arch/x86/mm/mpx.c:trace_raw_output_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff8107f32b)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/fork.c:trace_raw_output_task_rename
  - kernel/fork.c:trace_raw_output_task_newtask
```
```
In kernel/cpu.c (ffffffff8108336a)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/cpu.c:trace_raw_output_cpuhp_exit
  - kernel/cpu.c:trace_raw_output_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff81087f73)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/softirq.c:trace_raw_output_softirq
  - kernel/softirq.c:trace_raw_output_irq_handler_exit
  - kernel/softirq.c:trace_raw_output_irq_handler_entry
```
```
In kernel/signal.c (ffffffff8108ff0b)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/signal.c:trace_raw_output_signal_deliver
  - kernel/signal.c:trace_raw_output_signal_generate
```
```
In kernel/workqueue.c (ffffffff8109a650)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/workqueue.c:trace_raw_output_workqueue_execute_start
  - kernel/workqueue.c:trace_raw_output_workqueue_queue_work
  - kernel/workqueue.c:trace_raw_output_workqueue_work
```
```
In kernel/sched/core.c (ffffffff810a982b)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/sched/core.c:trace_raw_output_sched_wake_idle_without_ipi
  - kernel/sched/core.c:trace_raw_output_sched_swap_numa
  - kernel/sched/core.c:trace_raw_output_sched_move_task_template
  - kernel/sched/core.c:trace_raw_output_sched_process_hang
  - kernel/sched/core.c:trace_raw_output_sched_pi_setprio
  - kernel/sched/core.c:trace_raw_output_sched_stat_runtime
  - kernel/sched/core.c:trace_raw_output_sched_stat_template
  - kernel/sched/core.c:trace_raw_output_sched_process_exec
  - kernel/sched/core.c:trace_raw_output_sched_process_fork
  - kernel/sched/core.c:trace_raw_output_sched_process_wait
  - kernel/sched/core.c:trace_raw_output_sched_process_template
  - kernel/sched/core.c:trace_raw_output_sched_migrate_task
  - kernel/sched/core.c:trace_raw_output_sched_switch
  - kernel/sched/core.c:trace_raw_output_sched_wakeup_template
  - kernel/sched/core.c:trace_raw_output_sched_kthread_stop_ret
  - kernel/sched/core.c:trace_raw_output_sched_kthread_stop
```
```
In kernel/printk/printk.c (ffffffff810db8af)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/printk/printk.c:trace_raw_output_console
```
```
In kernel/rcu/update.c (ffffffff810e91eb)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/rcu/update.c:trace_raw_output_rcu_utilization
```
```
In kernel/time/timer.c (ffffffff810f37f3)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/time/timer.c:trace_raw_output_tick_stop
  - kernel/time/timer.c:trace_raw_output_itimer_expire
  - kernel/time/timer.c:trace_raw_output_itimer_state
  - kernel/time/timer.c:trace_raw_output_hrtimer_class
  - kernel/time/timer.c:trace_raw_output_hrtimer_expire_entry
  - kernel/time/timer.c:trace_raw_output_hrtimer_start
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/time/timer.c:trace_raw_output_timer_expire_entry
  - kernel/time/timer.c:trace_raw_output_timer_start
  - kernel/time/timer.c:trace_raw_output_timer_class
```
```
In kernel/module.c (ffffffff8110c69a)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/module.c:trace_raw_output_module_request
  - kernel/module.c:trace_raw_output_module_refcnt
  - kernel/module.c:trace_raw_output_module_free
  - kernel/module.c:trace_raw_output_module_load
```
```
In kernel/trace/ring_buffer.c (ffffffff81152e78)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
```
```
In kernel/trace/trace.c (ffffffff8115a4f7)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
```
```
In kernel/trace/trace_output.c (ffffffff8115c726)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_print_raw
  - kernel/trace/trace_output.c:trace_print_print
  - kernel/trace/trace_output.c:trace_bprint_raw
  - kernel/trace/trace_output.c:trace_bprint_print
  - kernel/trace/trace_output.c:trace_bputs_raw
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_hex
  - kernel/trace/trace_output.c:trace_ctxwake_raw
  - kernel/trace/trace_output.c:trace_ctxwake_print
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/trace_output.c:trace_fn_hex
  - kernel/trace/trace_output.c:trace_fn_raw
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_nop_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
  - kernel/trace/trace_output.c:trace_output_call
  - kernel/trace/trace_output.c:trace_print_printk_msg_only
  - kernel/trace/trace_output.c:trace_print_bprintk_msg_only
  - kernel/trace/trace_output.c:trace_print_bputs_msg_only
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff81162edc)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
```
```
In kernel/trace/trace_functions_graph.c (ffffffff81164fe2)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff811660c2)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:print_one_line
  - kernel/trace/blktrace.c:print_one_line
```
```
In kernel/trace/trace_syscalls.c (ffffffff8116bc86)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_syscalls.c:print_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811756d0)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
```
```
In kernel/trace/power-traces.c (ffffffff81178293)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_power_domain
  - kernel/trace/power-traces.c:trace_raw_output_clock
  - kernel/trace/power-traces.c:trace_raw_output_wakeup_source
  - kernel/trace/power-traces.c:trace_raw_output_suspend_resume
  - kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_end
  - kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start
  - kernel/trace/power-traces.c:trace_raw_output_pstate_sample
  - kernel/trace/power-traces.c:trace_raw_output_powernv_throttle
  - kernel/trace/power-traces.c:trace_raw_output_cpu
```
```
In kernel/trace/rpm-traces.c (ffffffff81179879)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:trace_raw_output_rpm_return_int
  - kernel/trace/rpm-traces.c:trace_raw_output_rpm_internal
```
```
In kernel/trace/trace_probe.c (ffffffff8117a992)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_probe.c:print_type_s64
  - kernel/trace/trace_probe.c:print_type_s32
  - kernel/trace/trace_probe.c:print_type_s16
  - kernel/trace/trace_probe.c:print_type_s8
  - kernel/trace/trace_probe.c:print_type_u64
  - kernel/trace/trace_probe.c:print_type_u32
  - kernel/trace/trace_probe.c:print_type_u16
  - kernel/trace/trace_probe.c:print_type_u8
```
```
In kernel/trace/trace_uprobe.c (ffffffff8117c78b)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:print_uprobe_event
```
```
In mm/filemap.c (ffffffff8119f71e)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - mm/filemap.c:trace_raw_output_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff811a47f6)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - mm/oom_kill.c:trace_raw_output_oom_score_adj_update
```
```
In mm/swap.c (ffffffff811b1a80)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - mm/swap.c:trace_raw_output_mm_lru_activate
  - mm/swap.c:trace_raw_output_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff811b6766)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:trace_raw_output_mm_vmscan_writepage
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate_template
  - mm/vmscan.c:trace_raw_output_mm_shrink_slab_end
  - mm/vmscan.c:trace_raw_output_mm_shrink_slab_start
  - mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_end_template
  - mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd
  - mm/vmscan.c:trace_raw_output_mm_vmscan_kswapd_wake
  - mm/vmscan.c:trace_raw_output_mm_vmscan_kswapd_sleep
```
```
In mm/slab_common.c (ffffffff811cbe80)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - mm/slab_common.c:trace_raw_output_mm_page_alloc_extfrag
  - mm/slab_common.c:trace_raw_output_mm_page_pcpu_drain
  - mm/slab_common.c:trace_raw_output_mm_page
  - mm/slab_common.c:trace_raw_output_mm_page_alloc
  - mm/slab_common.c:trace_raw_output_mm_page_free_batched
  - mm/slab_common.c:trace_raw_output_mm_page_free
  - mm/slab_common.c:trace_raw_output_kmem_free
  - mm/slab_common.c:trace_raw_output_kmem_alloc_node
  - mm/slab_common.c:trace_raw_output_kmem_alloc
```
```
In mm/compaction.c (ffffffff811cedc8)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - mm/compaction.c:trace_raw_output_kcompactd_wake_template
  - mm/compaction.c:trace_raw_output_mm_compaction_kcompactd_sleep
  - mm/compaction.c:trace_raw_output_mm_compaction_defer_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages
  - mm/compaction.c:trace_raw_output_mm_compaction_end
  - mm/compaction.c:trace_raw_output_mm_compaction_begin
  - mm/compaction.c:trace_raw_output_mm_compaction_migratepages
  - mm/compaction.c:trace_raw_output_mm_compaction_isolate_template
```
```
In mm/migrate.c (ffffffff8120fb9a)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - mm/migrate.c:trace_raw_output_mm_numa_migrate_ratelimit
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff8121908a)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page
  - mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff812289fa)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - mm/page_isolation.c:trace_raw_output_test_pages_isolated
```
```
In mm/cma.c (ffffffff8122c7a5)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - mm/cma.c:trace_raw_output_cma_release
  - mm/cma.c:trace_raw_output_cma_alloc
```
```
In fs/open.c (ffffffff8122f27f)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - fs/open.c:trace_raw_output_open_exec
  - fs/open.c:trace_raw_output_do_sys_open
```
```
In fs/fs-writeback.c (ffffffff8125ed77)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - fs/fs-writeback.c:trace_raw_output_writeback_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_congest_waited_template
  - fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_raw_output_balance_dirty_pages
  - fs/fs-writeback.c:trace_raw_output_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_raw_output_global_dirty_state
  - fs/fs-writeback.c:trace_raw_output_writeback_queue_io
  - fs/fs-writeback.c:trace_raw_output_wbc_class
  - fs/fs-writeback.c:trace_raw_output_writeback_bdi_register
  - fs/fs-writeback.c:trace_raw_output_writeback_class
  - fs/fs-writeback.c:trace_raw_output_writeback_pages_written
  - fs/fs-writeback.c:trace_raw_output_writeback_work_class
  - fs/fs-writeback.c:trace_raw_output_writeback_write_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_page
```
```
In fs/locks.c (ffffffff8128b68c)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/locks.c:trace_raw_output_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff812dfcd9)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - fs/ext4/super.c:trace_raw_output_ext4_es_shrink
  - fs/ext4/super.c:trace_raw_output_ext4_insert_range
  - fs/ext4/super.c:trace_raw_output_ext4_collapse_range
  - fs/ext4/super.c:trace_raw_output_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:trace_raw_output_ext4__es_shrink_enter
  - fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:trace_raw_output_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:trace_raw_output_ext4_es_find_delayed_extent_range_enter
  - fs/ext4/super.c:trace_raw_output_ext4_es_remove_extent
  - fs/ext4/super.c:trace_raw_output_ext4__es_extent
  - fs/ext4/super.c:trace_raw_output_ext4_ext_remove_space_done
  - fs/ext4/super.c:trace_raw_output_ext4_ext_remove_space
  - fs/ext4/super.c:trace_raw_output_ext4_ext_rm_idx
  - fs/ext4/super.c:trace_raw_output_ext4_ext_rm_leaf
  - fs/ext4/super.c:trace_raw_output_ext4_remove_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_ext_show_extent
  - fs/ext4/super.c:trace_raw_output_ext4_get_reserved_cluster_alloc
  - fs/ext4/super.c:trace_raw_output_ext4_find_delalloc_range
  - fs/ext4/super.c:trace_raw_output_ext4_ext_in_cache
  - fs/ext4/super.c:trace_raw_output_ext4_ext_put_in_cache
  - fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:trace_raw_output_ext4__trim
  - fs/ext4/super.c:trace_raw_output_ext4_journal_start_reserved
  - fs/ext4/super.c:trace_raw_output_ext4_journal_start
  - fs/ext4/super.c:trace_raw_output_ext4_load_inode
  - fs/ext4/super.c:trace_raw_output_ext4_ext_load_extent
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter
  - fs/ext4/super.c:trace_raw_output_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_raw_output_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:trace_raw_output_ext4__truncate
  - fs/ext4/super.c:trace_raw_output_ext4_unlink_exit
  - fs/ext4/super.c:trace_raw_output_ext4_unlink_enter
  - fs/ext4/super.c:trace_raw_output_ext4_fallocate_exit
  - fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode
  - fs/ext4/super.c:trace_raw_output_ext4_direct_IO_exit
  - fs/ext4/super.c:trace_raw_output_ext4_direct_IO_enter
  - fs/ext4/super.c:trace_raw_output_ext4__bitmap_load
  - fs/ext4/super.c:trace_raw_output_ext4_da_release_space
  - fs/ext4/super.c:trace_raw_output_ext4_da_reserve_space
  - fs/ext4/super.c:trace_raw_output_ext4_da_update_reserve_space
  - fs/ext4/super.c:trace_raw_output_ext4_forget
  - fs/ext4/super.c:trace_raw_output_ext4__mballoc
  - fs/ext4/super.c:trace_raw_output_ext4_mballoc_prealloc
  - fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc
  - fs/ext4/super.c:trace_raw_output_ext4_alloc_da_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_sync_fs
  - fs/ext4/super.c:trace_raw_output_ext4_sync_file_exit
  - fs/ext4/super.c:trace_raw_output_ext4_sync_file_enter
  - fs/ext4/super.c:trace_raw_output_ext4_free_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_request_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_mb_discard_preallocations
  - fs/ext4/super.c:trace_raw_output_ext4_discard_preallocations
  - fs/ext4/super.c:trace_raw_output_ext4_mb_release_group_pa
  - fs/ext4/super.c:trace_raw_output_ext4_mb_release_inode_pa
  - fs/ext4/super.c:trace_raw_output_ext4__mb_new_pa
  - fs/ext4/super.c:trace_raw_output_ext4_discard_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_invalidatepage_op
  - fs/ext4/super.c:trace_raw_output_ext4__page_op
  - fs/ext4/super.c:trace_raw_output_ext4_writepages_result
  - fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent
  - fs/ext4/super.c:trace_raw_output_ext4_da_write_pages
  - fs/ext4/super.c:trace_raw_output_ext4_writepages
  - fs/ext4/super.c:trace_raw_output_ext4__write_end
  - fs/ext4/super.c:trace_raw_output_ext4__write_begin
  - fs/ext4/super.c:trace_raw_output_ext4_begin_ordered_truncate
  - fs/ext4/super.c:trace_raw_output_ext4_mark_inode_dirty
  - fs/ext4/super.c:trace_raw_output_ext4_drop_inode
  - fs/ext4/super.c:trace_raw_output_ext4_evict_inode
  - fs/ext4/super.c:trace_raw_output_ext4_allocate_inode
  - fs/ext4/super.c:trace_raw_output_ext4_request_inode
  - fs/ext4/super.c:trace_raw_output_ext4_free_inode
  - fs/ext4/super.c:trace_raw_output_ext4_other_inode_update_time
```
```
In fs/jbd2/journal.c (ffffffff8131cd9b)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - fs/jbd2/journal.c:trace_raw_output_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:trace_raw_output_jbd2_write_superblock
  - fs/jbd2/journal.c:trace_raw_output_jbd2_update_log_tail
  - fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_handle_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_handle_extend
  - fs/jbd2/journal.c:trace_raw_output_jbd2_handle_start
  - fs/jbd2/journal.c:trace_raw_output_jbd2_submit_inode_data
  - fs/jbd2/journal.c:trace_raw_output_jbd2_end_commit
  - fs/jbd2/journal.c:trace_raw_output_jbd2_commit
  - fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint
```
```
In block/blk-core.c (ffffffff813f8fbb)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - block/blk-core.c:trace_raw_output_block_rq_remap
  - block/blk-core.c:trace_raw_output_block_bio_remap
  - block/blk-core.c:trace_raw_output_block_split
  - block/blk-core.c:trace_raw_output_block_unplug
  - block/blk-core.c:trace_raw_output_block_plug
  - block/blk-core.c:trace_raw_output_block_get_rq
  - block/blk-core.c:trace_raw_output_block_bio_queue
  - block/blk-core.c:trace_raw_output_block_bio_merge
  - block/blk-core.c:trace_raw_output_block_bio_complete
  - block/blk-core.c:trace_raw_output_block_bio_bounce
  - block/blk-core.c:trace_raw_output_block_rq
  - block/blk-core.c:trace_raw_output_block_rq_complete
  - block/blk-core.c:trace_raw_output_block_rq_with_error
  - block/blk-core.c:trace_raw_output_block_buffer
```
```
In lib/swiotlb.c (ffffffff81459c13)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - lib/swiotlb.c:trace_raw_output_swiotlb_bounced
```
```
In arch/x86/lib/msr.c (ffffffff81463f19)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:trace_raw_output_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff8146dcb9)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:trace_raw_output_gpio_value
  - drivers/gpio/gpiolib.c:trace_raw_output_gpio_direction
```
```
In drivers/regulator/core.c (ffffffff81528aa4)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/regulator/core.c:trace_raw_output_regulator_value
  - drivers/regulator/core.c:trace_raw_output_regulator_range
  - drivers/regulator/core.c:trace_raw_output_regulator_basic
```
```
In drivers/char/random.c (ffffffff81565235)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/char/random.c:trace_raw_output_urandom_read
  - drivers/char/random.c:trace_raw_output_random_read
  - drivers/char/random.c:trace_raw_output_random__extract_entropy
  - drivers/char/random.c:trace_raw_output_random__get_random_bytes
  - drivers/char/random.c:trace_raw_output_xfer_secondary_pool
  - drivers/char/random.c:trace_raw_output_add_disk_randomness
  - drivers/char/random.c:trace_raw_output_add_input_randomness
  - drivers/char/random.c:trace_raw_output_debit_entropy
  - drivers/char/random.c:trace_raw_output_push_to_pool
  - drivers/char/random.c:trace_raw_output_credit_entropy_bits
  - drivers/char/random.c:trace_raw_output_random__mix_pool_bytes
  - drivers/char/random.c:trace_raw_output_add_device_randomness
```
```
In drivers/iommu/iommu-traces.c (ffffffff8157f432)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:trace_raw_output_iommu_error
  - drivers/iommu/iommu-traces.c:trace_raw_output_unmap
  - drivers/iommu/iommu-traces.c:trace_raw_output_map
  - drivers/iommu/iommu-traces.c:trace_raw_output_iommu_device_event
  - drivers/iommu/iommu-traces.c:trace_raw_output_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff815b6e09)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:trace_raw_output_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_raw_output_regmap_async
  - drivers/base/regmap/regmap.c:trace_raw_output_regmap_bool
  - drivers/base/regmap/regmap.c:trace_raw_output_regcache_sync
  - drivers/base/regmap/regmap.c:trace_raw_output_regmap_block
  - drivers/base/regmap/regmap.c:trace_raw_output_regmap_reg
```
```
In drivers/dma-buf/fence.c (ffffffff815fac72)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/dma-buf/fence.c:trace_raw_output_fence
  - drivers/dma-buf/fence.c:trace_raw_output_fence_annotate_wait_on
```
```
In drivers/scsi/scsi.c (ffffffff815fe5ab)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:trace_raw_output_scsi_eh_wakeup
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff8162095d)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:trace_raw_output_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:trace_raw_output_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_complete_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff8164329a)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/spi/spi.c:trace_raw_output_spi_transfer
  - drivers/spi/spi.c:trace_raw_output_spi_message_done
  - drivers/spi/spi.c:trace_raw_output_spi_message
  - drivers/spi/spi.c:trace_raw_output_spi_master
```
```
In drivers/usb/host/xhci-trace.c (ffffffff816c19aa)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_event
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_msg
```
```
In drivers/i2c/i2c-core.c (ffffffff816d9b7e)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:trace_raw_output_smbus_result
  - drivers/i2c/i2c-core.c:trace_raw_output_smbus_reply
  - drivers/i2c/i2c-core.c:trace_raw_output_smbus_read
  - drivers/i2c/i2c-core.c:trace_raw_output_smbus_write
  - drivers/i2c/i2c-core.c:trace_raw_output_i2c_result
  - drivers/i2c/i2c-core.c:trace_raw_output_i2c_reply
  - drivers/i2c/i2c-core.c:trace_raw_output_i2c_read
  - drivers/i2c/i2c-core.c:trace_raw_output_i2c_write
```
```
In drivers/thermal/thermal_core.c (ffffffff816e45de)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip
  - drivers/thermal/thermal_core.c:trace_raw_output_cdev_update
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff816eaa6e)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:trace_raw_output_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:trace_raw_output_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff8171f39b)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:trace_raw_output_mmc_request_done
  - drivers/mmc/core/core.c:trace_raw_output_mmc_request_start
```
```
In drivers/clk/clk.c (ffffffff817490f4)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/clk/clk.c:trace_raw_output_clk_phase
  - drivers/clk/clk.c:trace_raw_output_clk_parent
  - drivers/clk/clk.c:trace_raw_output_clk_rate
  - drivers/clk/clk.c:trace_raw_output_clk
```
```
In drivers/ras/ras.c (ffffffff817586a8)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - drivers/ras/ras.c:trace_raw_output_aer_event
  - drivers/ras/ras.c:trace_raw_output_mc_event
  - drivers/ras/ras.c:trace_raw_output_extlog_mem_event
```
```
In net/core/net-traces.c (ffffffff817a8051)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - net/core/net-traces.c:trace_raw_output_fib6_table_lookup
  - net/core/net-traces.c:trace_raw_output_fib_validate_source
  - net/core/net-traces.c:trace_raw_output_fib_table_lookup_nh
  - net/core/net-traces.c:trace_raw_output_fib_table_lookup
  - net/core/net-traces.c:trace_raw_output_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_raw_output_sock_rcvqueue_full
  - net/core/net-traces.c:trace_raw_output_napi_poll
  - net/core/net-traces.c:trace_raw_output_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_raw_output_net_dev_template
  - net/core/net-traces.c:trace_raw_output_net_dev_xmit
  - net/core/net-traces.c:trace_raw_output_net_dev_start_xmit
  - net/core/net-traces.c:trace_raw_output_skb_copy_datagram_iovec
  - net/core/net-traces.c:trace_raw_output_consume_skb
  - net/core/net-traces.c:trace_raw_output_kfree_skb
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
In arch/x86/entry/common.c (ffffffff810031e0)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - arch/x86/entry/common.c:trace_raw_output_sys_exit
  - arch/x86/entry/common.c:trace_raw_output_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8100479b)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:trace_raw_output_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff81028f50)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:trace_raw_output_xen_cpu_write_gdt_entry
  - arch/x86/xen/trace.c:trace_raw_output_xen_cpu_load_idt
  - arch/x86/xen/trace.c:trace_raw_output_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:trace_raw_output_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_flush_tlb_single
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_flush_tlb
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_pgd
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_alloc_ptpage
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_pgd_clear
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_pud_clear
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pgd
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_pmd_clear
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_pte_clear
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pte_at
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_domain_pte
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte
  - arch/x86/xen/trace.c:trace_raw_output_xen_mc_extend_args
  - arch/x86/xen/trace.c:trace_raw_output_xen_mc_flush
  - arch/x86/xen/trace.c:trace_raw_output_xen_mc_flush_reason
  - arch/x86/xen/trace.c:trace_raw_output_xen_mc_callback
  - arch/x86/xen/trace.c:trace_raw_output_xen_mc_entry_alloc
  - arch/x86/xen/trace.c:trace_raw_output_xen_mc_entry
  - arch/x86/xen/trace.c:trace_raw_output_xen_mc__batch
```
```
In arch/x86/kernel/irq.c (ffffffff8102f07b)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:trace_raw_output_x86_irq_vector
```
```
In arch/x86/kernel/nmi.c (ffffffff81031095)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:trace_raw_output_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103861d)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:trace_raw_output_x86_fpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810455bb)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:trace_raw_output_mce_record
```
```
In arch/x86/mm/init.c (ffffffff8106c38d)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - arch/x86/mm/init.c:trace_raw_output_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff8106d9d5)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:trace_raw_output_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff8107a48b)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:trace_raw_output_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:trace_raw_output_mpx_range_trace
  - arch/x86/mm/mpx.c:trace_raw_output_bounds_exception_mpx
  - arch/x86/mm/mpx.c:trace_raw_output_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff810839db)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/fork.c:trace_raw_output_task_rename
  - kernel/fork.c:trace_raw_output_task_newtask
```
```
In kernel/cpu.c (ffffffff81087f7a)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/cpu.c:trace_raw_output_cpuhp_exit
  - kernel/cpu.c:trace_raw_output_cpuhp_multi_enter
  - kernel/cpu.c:trace_raw_output_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff8108ced3)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/softirq.c:trace_raw_output_softirq
  - kernel/softirq.c:trace_raw_output_irq_handler_exit
  - kernel/softirq.c:trace_raw_output_irq_handler_entry
```
```
In kernel/signal.c (ffffffff81094e8b)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/signal.c:trace_raw_output_signal_deliver
  - kernel/signal.c:trace_raw_output_signal_generate
```
```
In kernel/workqueue.c (ffffffff8109fa80)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/workqueue.c:trace_raw_output_workqueue_execute_start
  - kernel/workqueue.c:trace_raw_output_workqueue_queue_work
  - kernel/workqueue.c:trace_raw_output_workqueue_work
```
```
In kernel/sched/core.c (ffffffff810af6eb)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/sched/core.c:trace_raw_output_sched_wake_idle_without_ipi
  - kernel/sched/core.c:trace_raw_output_sched_swap_numa
  - kernel/sched/core.c:trace_raw_output_sched_move_task_template
  - kernel/sched/core.c:trace_raw_output_sched_process_hang
  - kernel/sched/core.c:trace_raw_output_sched_pi_setprio
  - kernel/sched/core.c:trace_raw_output_sched_stat_runtime
  - kernel/sched/core.c:trace_raw_output_sched_stat_template
  - kernel/sched/core.c:trace_raw_output_sched_process_exec
  - kernel/sched/core.c:trace_raw_output_sched_process_fork
  - kernel/sched/core.c:trace_raw_output_sched_process_wait
  - kernel/sched/core.c:trace_raw_output_sched_process_template
  - kernel/sched/core.c:trace_raw_output_sched_migrate_task
  - kernel/sched/core.c:trace_raw_output_sched_switch
  - kernel/sched/core.c:trace_raw_output_sched_wakeup_template
  - kernel/sched/core.c:trace_raw_output_sched_kthread_stop_ret
  - kernel/sched/core.c:trace_raw_output_sched_kthread_stop
```
```
In kernel/printk/printk.c (ffffffff810e237f)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/printk/printk.c:trace_raw_output_console
```
```
In kernel/rcu/update.c (ffffffff810f00bb)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/rcu/update.c:trace_raw_output_rcu_utilization
```
```
In kernel/time/timer.c (ffffffff810fab43)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/time/timer.c:trace_raw_output_tick_stop
  - kernel/time/timer.c:trace_raw_output_itimer_expire
  - kernel/time/timer.c:trace_raw_output_itimer_state
  - kernel/time/timer.c:trace_raw_output_hrtimer_class
  - kernel/time/timer.c:trace_raw_output_hrtimer_expire_entry
  - kernel/time/timer.c:trace_raw_output_hrtimer_start
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/time/timer.c:trace_raw_output_timer_expire_entry
  - kernel/time/timer.c:trace_raw_output_timer_start
  - kernel/time/timer.c:trace_raw_output_timer_class
```
```
In kernel/time/alarmtimer.c (ffffffff81104258)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:trace_raw_output_alarm_class
  - kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff811140ea)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/module.c:trace_raw_output_module_request
  - kernel/module.c:trace_raw_output_module_refcnt
  - kernel/module.c:trace_raw_output_module_free
  - kernel/module.c:trace_raw_output_module_load
```
```
In kernel/cgroup.c (ffffffff811211fd)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/cgroup.c:trace_raw_output_cgroup_migrate
  - kernel/cgroup.c:trace_raw_output_cgroup
  - kernel/cgroup.c:trace_raw_output_cgroup_root
```
```
In kernel/trace/ring_buffer.c (ffffffff8115ce68)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
```
```
In kernel/trace/trace.c (ffffffff81164d17)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
```
```
In kernel/trace/trace_output.c (ffffffff81167777)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_raw_data
  - kernel/trace/trace_output.c:trace_print_raw
  - kernel/trace/trace_output.c:trace_print_print
  - kernel/trace/trace_output.c:trace_bprint_raw
  - kernel/trace/trace_output.c:trace_bprint_print
  - kernel/trace/trace_output.c:trace_bputs_raw
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_hwlat_raw
  - kernel/trace/trace_output.c:trace_hwlat_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_hex
  - kernel/trace/trace_output.c:trace_ctxwake_raw
  - kernel/trace/trace_output.c:trace_ctxwake_print
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/trace_output.c:trace_fn_hex
  - kernel/trace/trace_output.c:trace_fn_raw
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_nop_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
  - kernel/trace/trace_output.c:trace_output_call
  - kernel/trace/trace_output.c:trace_print_printk_msg_only
  - kernel/trace/trace_output.c:trace_print_bprintk_msg_only
  - kernel/trace/trace_output.c:trace_print_bputs_msg_only
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff8116e20c)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811703e9)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff81171522)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:print_one_line
  - kernel/trace/blktrace.c:print_one_line
```
```
In kernel/trace/trace_syscalls.c (ffffffff81176f76)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_syscalls.c:print_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811810c0)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
```
```
In kernel/trace/power-traces.c (ffffffff81183d53)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_power_domain
  - kernel/trace/power-traces.c:trace_raw_output_clock
  - kernel/trace/power-traces.c:trace_raw_output_wakeup_source
  - kernel/trace/power-traces.c:trace_raw_output_suspend_resume
  - kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_end
  - kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start
  - kernel/trace/power-traces.c:trace_raw_output_pstate_sample
  - kernel/trace/power-traces.c:trace_raw_output_powernv_throttle
  - kernel/trace/power-traces.c:trace_raw_output_cpu
```
```
In kernel/trace/rpm-traces.c (ffffffff81185349)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:trace_raw_output_rpm_return_int
  - kernel/trace/rpm-traces.c:trace_raw_output_rpm_internal
```
```
In kernel/trace/trace_probe.c (ffffffff811865a2)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_probe.c:print_type_x64
  - kernel/trace/trace_probe.c:print_type_x32
  - kernel/trace/trace_probe.c:print_type_x16
  - kernel/trace/trace_probe.c:print_type_x8
  - kernel/trace/trace_probe.c:print_type_s64
  - kernel/trace/trace_probe.c:print_type_s32
  - kernel/trace/trace_probe.c:print_type_s16
  - kernel/trace/trace_probe.c:print_type_s8
  - kernel/trace/trace_probe.c:print_type_u64
  - kernel/trace/trace_probe.c:print_type_u32
  - kernel/trace/trace_probe.c:print_type_u16
  - kernel/trace/trace_probe.c:print_type_u8
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118839b)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:print_uprobe_event
```
```
In mm/filemap.c (ffffffff811af138)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - mm/filemap.c:trace_raw_output_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff811b4b56)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - mm/oom_kill.c:trace_raw_output_oom_score_adj_update
```
```
In mm/swap.c (ffffffff811c20e0)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - mm/swap.c:trace_raw_output_mm_lru_activate
  - mm/swap.c:trace_raw_output_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff811c6c46)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:trace_raw_output_mm_vmscan_writepage
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate_template
  - mm/vmscan.c:trace_raw_output_mm_shrink_slab_end
  - mm/vmscan.c:trace_raw_output_mm_shrink_slab_start
  - mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_end_template
  - mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd
  - mm/vmscan.c:trace_raw_output_mm_vmscan_kswapd_wake
  - mm/vmscan.c:trace_raw_output_mm_vmscan_kswapd_sleep
```
```
In mm/slab_common.c (ffffffff811dbf8a)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - mm/slab_common.c:trace_raw_output_mm_page_alloc_extfrag
  - mm/slab_common.c:trace_raw_output_mm_page_pcpu_drain
  - mm/slab_common.c:trace_raw_output_mm_page
  - mm/slab_common.c:trace_raw_output_mm_page_alloc
  - mm/slab_common.c:trace_raw_output_mm_page_free_batched
  - mm/slab_common.c:trace_raw_output_mm_page_free
  - mm/slab_common.c:trace_raw_output_kmem_free
  - mm/slab_common.c:trace_raw_output_kmem_alloc_node
  - mm/slab_common.c:trace_raw_output_kmem_alloc
```
```
In mm/compaction.c (ffffffff811deef8)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - mm/compaction.c:trace_raw_output_kcompactd_wake_template
  - mm/compaction.c:trace_raw_output_mm_compaction_kcompactd_sleep
  - mm/compaction.c:trace_raw_output_mm_compaction_defer_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages
  - mm/compaction.c:trace_raw_output_mm_compaction_end
  - mm/compaction.c:trace_raw_output_mm_compaction_begin
  - mm/compaction.c:trace_raw_output_mm_compaction_migratepages
  - mm/compaction.c:trace_raw_output_mm_compaction_isolate_template
```
```
In mm/migrate.c (ffffffff81221cca)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - mm/migrate.c:trace_raw_output_mm_numa_migrate_ratelimit
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff8122b60a)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page
  - mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff8123afaa)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - mm/page_isolation.c:trace_raw_output_test_pages_isolated
```
```
In mm/cma.c (ffffffff8123ecd5)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - mm/cma.c:trace_raw_output_cma_release
  - mm/cma.c:trace_raw_output_cma_alloc
```
```
In fs/open.c (ffffffff812417cf)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - fs/open.c:trace_raw_output_open_exec
  - fs/open.c:trace_raw_output_do_sys_open
```
```
In fs/fs-writeback.c (ffffffff81272297)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - fs/fs-writeback.c:trace_raw_output_writeback_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_congest_waited_template
  - fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_raw_output_balance_dirty_pages
  - fs/fs-writeback.c:trace_raw_output_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_raw_output_global_dirty_state
  - fs/fs-writeback.c:trace_raw_output_writeback_queue_io
  - fs/fs-writeback.c:trace_raw_output_wbc_class
  - fs/fs-writeback.c:trace_raw_output_writeback_bdi_register
  - fs/fs-writeback.c:trace_raw_output_writeback_class
  - fs/fs-writeback.c:trace_raw_output_writeback_pages_written
  - fs/fs-writeback.c:trace_raw_output_writeback_work_class
  - fs/fs-writeback.c:trace_raw_output_writeback_write_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_page
```
```
In fs/locks.c (ffffffff812a03dc)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/locks.c:trace_raw_output_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff812f5819)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - fs/ext4/super.c:trace_raw_output_ext4_es_shrink
  - fs/ext4/super.c:trace_raw_output_ext4_insert_range
  - fs/ext4/super.c:trace_raw_output_ext4_collapse_range
  - fs/ext4/super.c:trace_raw_output_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:trace_raw_output_ext4__es_shrink_enter
  - fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:trace_raw_output_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:trace_raw_output_ext4_es_find_delayed_extent_range_enter
  - fs/ext4/super.c:trace_raw_output_ext4_es_remove_extent
  - fs/ext4/super.c:trace_raw_output_ext4__es_extent
  - fs/ext4/super.c:trace_raw_output_ext4_ext_remove_space_done
  - fs/ext4/super.c:trace_raw_output_ext4_ext_remove_space
  - fs/ext4/super.c:trace_raw_output_ext4_ext_rm_idx
  - fs/ext4/super.c:trace_raw_output_ext4_ext_rm_leaf
  - fs/ext4/super.c:trace_raw_output_ext4_remove_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_ext_show_extent
  - fs/ext4/super.c:trace_raw_output_ext4_get_reserved_cluster_alloc
  - fs/ext4/super.c:trace_raw_output_ext4_find_delalloc_range
  - fs/ext4/super.c:trace_raw_output_ext4_ext_in_cache
  - fs/ext4/super.c:trace_raw_output_ext4_ext_put_in_cache
  - fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:trace_raw_output_ext4__trim
  - fs/ext4/super.c:trace_raw_output_ext4_journal_start_reserved
  - fs/ext4/super.c:trace_raw_output_ext4_journal_start
  - fs/ext4/super.c:trace_raw_output_ext4_load_inode
  - fs/ext4/super.c:trace_raw_output_ext4_ext_load_extent
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter
  - fs/ext4/super.c:trace_raw_output_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:trace_raw_output_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:trace_raw_output_ext4__truncate
  - fs/ext4/super.c:trace_raw_output_ext4_unlink_exit
  - fs/ext4/super.c:trace_raw_output_ext4_unlink_enter
  - fs/ext4/super.c:trace_raw_output_ext4_fallocate_exit
  - fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode
  - fs/ext4/super.c:trace_raw_output_ext4_direct_IO_exit
  - fs/ext4/super.c:trace_raw_output_ext4_direct_IO_enter
  - fs/ext4/super.c:trace_raw_output_ext4__bitmap_load
  - fs/ext4/super.c:trace_raw_output_ext4_da_release_space
  - fs/ext4/super.c:trace_raw_output_ext4_da_reserve_space
  - fs/ext4/super.c:trace_raw_output_ext4_da_update_reserve_space
  - fs/ext4/super.c:trace_raw_output_ext4_forget
  - fs/ext4/super.c:trace_raw_output_ext4__mballoc
  - fs/ext4/super.c:trace_raw_output_ext4_mballoc_prealloc
  - fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc
  - fs/ext4/super.c:trace_raw_output_ext4_alloc_da_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_sync_fs
  - fs/ext4/super.c:trace_raw_output_ext4_sync_file_exit
  - fs/ext4/super.c:trace_raw_output_ext4_sync_file_enter
  - fs/ext4/super.c:trace_raw_output_ext4_free_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_request_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_mb_discard_preallocations
  - fs/ext4/super.c:trace_raw_output_ext4_discard_preallocations
  - fs/ext4/super.c:trace_raw_output_ext4_mb_release_group_pa
  - fs/ext4/super.c:trace_raw_output_ext4_mb_release_inode_pa
  - fs/ext4/super.c:trace_raw_output_ext4__mb_new_pa
  - fs/ext4/super.c:trace_raw_output_ext4_discard_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_invalidatepage_op
  - fs/ext4/super.c:trace_raw_output_ext4__page_op
  - fs/ext4/super.c:trace_raw_output_ext4_writepages_result
  - fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent
  - fs/ext4/super.c:trace_raw_output_ext4_da_write_pages
  - fs/ext4/super.c:trace_raw_output_ext4_writepages
  - fs/ext4/super.c:trace_raw_output_ext4__write_end
  - fs/ext4/super.c:trace_raw_output_ext4__write_begin
  - fs/ext4/super.c:trace_raw_output_ext4_begin_ordered_truncate
  - fs/ext4/super.c:trace_raw_output_ext4_mark_inode_dirty
  - fs/ext4/super.c:trace_raw_output_ext4_drop_inode
  - fs/ext4/super.c:trace_raw_output_ext4_evict_inode
  - fs/ext4/super.c:trace_raw_output_ext4_allocate_inode
  - fs/ext4/super.c:trace_raw_output_ext4_request_inode
  - fs/ext4/super.c:trace_raw_output_ext4_free_inode
  - fs/ext4/super.c:trace_raw_output_ext4_other_inode_update_time
```
```
In fs/jbd2/journal.c (ffffffff81332d7b)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - fs/jbd2/journal.c:trace_raw_output_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:trace_raw_output_jbd2_write_superblock
  - fs/jbd2/journal.c:trace_raw_output_jbd2_update_log_tail
  - fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_handle_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_handle_extend
  - fs/jbd2/journal.c:trace_raw_output_jbd2_handle_start
  - fs/jbd2/journal.c:trace_raw_output_jbd2_submit_inode_data
  - fs/jbd2/journal.c:trace_raw_output_jbd2_end_commit
  - fs/jbd2/journal.c:trace_raw_output_jbd2_commit
  - fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint
```
```
In block/blk-core.c (ffffffff8141298b)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - block/blk-core.c:trace_raw_output_block_rq_remap
  - block/blk-core.c:trace_raw_output_block_bio_remap
  - block/blk-core.c:trace_raw_output_block_split
  - block/blk-core.c:trace_raw_output_block_unplug
  - block/blk-core.c:trace_raw_output_block_plug
  - block/blk-core.c:trace_raw_output_block_get_rq
  - block/blk-core.c:trace_raw_output_block_bio_queue
  - block/blk-core.c:trace_raw_output_block_bio_merge
  - block/blk-core.c:trace_raw_output_block_bio_complete
  - block/blk-core.c:trace_raw_output_block_bio_bounce
  - block/blk-core.c:trace_raw_output_block_rq
  - block/blk-core.c:trace_raw_output_block_rq_complete
  - block/blk-core.c:trace_raw_output_block_rq_with_error
  - block/blk-core.c:trace_raw_output_block_buffer
```
```
In block/blk-wbt.c (ffffffff81449c1a)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - block/blk-wbt.c:trace_raw_output_wbt_timer
  - block/blk-wbt.c:trace_raw_output_wbt_step
  - block/blk-wbt.c:trace_raw_output_wbt_lat
  - block/blk-wbt.c:trace_raw_output_wbt_stat
```
```
In lib/swiotlb.c (ffffffff814785ef)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - lib/swiotlb.c:trace_raw_output_swiotlb_bounced
```
```
In arch/x86/lib/msr.c (ffffffff814831b9)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:trace_raw_output_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff8148fb79)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:trace_raw_output_gpio_value
  - drivers/gpio/gpiolib.c:trace_raw_output_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff81531974)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/clk/clk.c:trace_raw_output_clk_phase
  - drivers/clk/clk.c:trace_raw_output_clk_parent
  - drivers/clk/clk.c:trace_raw_output_clk_rate
  - drivers/clk/clk.c:trace_raw_output_clk
```
```
In drivers/regulator/core.c (ffffffff81555004)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/regulator/core.c:trace_raw_output_regulator_value
  - drivers/regulator/core.c:trace_raw_output_regulator_range
  - drivers/regulator/core.c:trace_raw_output_regulator_basic
```
```
In drivers/char/random.c (ffffffff81591995)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/char/random.c:trace_raw_output_urandom_read
  - drivers/char/random.c:trace_raw_output_random_read
  - drivers/char/random.c:trace_raw_output_random__extract_entropy
  - drivers/char/random.c:trace_raw_output_random__get_random_bytes
  - drivers/char/random.c:trace_raw_output_xfer_secondary_pool
  - drivers/char/random.c:trace_raw_output_add_disk_randomness
  - drivers/char/random.c:trace_raw_output_add_input_randomness
  - drivers/char/random.c:trace_raw_output_debit_entropy
  - drivers/char/random.c:trace_raw_output_push_to_pool
  - drivers/char/random.c:trace_raw_output_credit_entropy_bits
  - drivers/char/random.c:trace_raw_output_random__mix_pool_bytes
  - drivers/char/random.c:trace_raw_output_add_device_randomness
```
```
In drivers/iommu/iommu-traces.c (ffffffff815abfc2)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:trace_raw_output_iommu_error
  - drivers/iommu/iommu-traces.c:trace_raw_output_unmap
  - drivers/iommu/iommu-traces.c:trace_raw_output_map
  - drivers/iommu/iommu-traces.c:trace_raw_output_iommu_device_event
  - drivers/iommu/iommu-traces.c:trace_raw_output_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff815e6129)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:trace_raw_output_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_raw_output_regmap_async
  - drivers/base/regmap/regmap.c:trace_raw_output_regmap_bool
  - drivers/base/regmap/regmap.c:trace_raw_output_regcache_sync
  - drivers/base/regmap/regmap.c:trace_raw_output_regmap_block
  - drivers/base/regmap/regmap.c:trace_raw_output_regmap_reg
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81628f42)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:trace_raw_output_dma_fence
  - drivers/dma-buf/dma-fence.c:trace_raw_output_dma_fence_annotate_wait_on
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8162c294)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:trace_raw_output_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff8162dbab)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:trace_raw_output_scsi_eh_wakeup
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff816514cd)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:trace_raw_output_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:trace_raw_output_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_complete_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff8167436a)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/spi/spi.c:trace_raw_output_spi_transfer
  - drivers/spi/spi.c:trace_raw_output_spi_message_done
  - drivers/spi/spi.c:trace_raw_output_spi_message
  - drivers/spi/spi.c:trace_raw_output_spi_master
```
```
In drivers/net/phy/mdio_bus.c (ffffffff8167d06f)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:trace_raw_output_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff816ef90a)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_event
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_msg
```
```
In drivers/i2c/i2c-core.c (ffffffff81709c6e)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:trace_raw_output_smbus_result
  - drivers/i2c/i2c-core.c:trace_raw_output_smbus_reply
  - drivers/i2c/i2c-core.c:trace_raw_output_smbus_read
  - drivers/i2c/i2c-core.c:trace_raw_output_smbus_write
  - drivers/i2c/i2c-core.c:trace_raw_output_i2c_result
  - drivers/i2c/i2c-core.c:trace_raw_output_i2c_reply
  - drivers/i2c/i2c-core.c:trace_raw_output_i2c_read
  - drivers/i2c/i2c-core.c:trace_raw_output_i2c_write
```
```
In drivers/thermal/thermal_core.c (ffffffff8171518e)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip
  - drivers/thermal/thermal_core.c:trace_raw_output_cdev_update
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff8171b98e)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:trace_raw_output_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:trace_raw_output_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff81751efb)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:trace_raw_output_mmc_request_done
  - drivers/mmc/core/core.c:trace_raw_output_mmc_request_start
```
```
In drivers/ras/ras.c (ffffffff81784c78)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - drivers/ras/ras.c:trace_raw_output_aer_event
  - drivers/ras/ras.c:trace_raw_output_mc_event
  - drivers/ras/ras.c:trace_raw_output_extlog_mem_event
```
```
In net/core/net-traces.c (ffffffff817d6ba1)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - net/core/net-traces.c:trace_raw_output_fib6_table_lookup
  - net/core/net-traces.c:trace_raw_output_fib_validate_source
  - net/core/net-traces.c:trace_raw_output_fib_table_lookup_nh
  - net/core/net-traces.c:trace_raw_output_fib_table_lookup
  - net/core/net-traces.c:trace_raw_output_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_raw_output_sock_rcvqueue_full
  - net/core/net-traces.c:trace_raw_output_napi_poll
  - net/core/net-traces.c:trace_raw_output_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_raw_output_net_dev_template
  - net/core/net-traces.c:trace_raw_output_net_dev_xmit
  - net/core/net-traces.c:trace_raw_output_net_dev_start_xmit
  - net/core/net-traces.c:trace_raw_output_skb_copy_datagram_iovec
  - net/core/net-traces.c:trace_raw_output_consume_skb
  - net/core/net-traces.c:trace_raw_output_kfree_skb
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
In kernel/trace/ring_buffer.c (ffffffff8115fe98)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
```
```
In kernel/trace/trace.c (ffffffff811681b3)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
```
```
In kernel/trace/trace_output.c (ffffffff8116b0bf)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811733e2)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
```
In kernel/trace/trace_syscalls.c (ffffffff81179d4b)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
```
```
In kernel/trace/trace_probe.c (ffffffff81189202)
Location: include/linux/trace_seq.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_probe.c:print_type_x64
  - kernel/trace/trace_probe.c:print_type_x32
  - kernel/trace/trace_probe.c:print_type_x16
  - kernel/trace/trace_probe.c:print_type_x8
  - kernel/trace/trace_probe.c:print_type_s64
  - kernel/trace/trace_probe.c:print_type_s32
  - kernel/trace/trace_probe.c:print_type_s16
  - kernel/trace/trace_probe.c:print_type_s8
  - kernel/trace/trace_probe.c:print_type_u64
  - kernel/trace/trace_probe.c:print_type_u32
  - kernel/trace/trace_probe.c:print_type_u16
  - kernel/trace/trace_probe.c:print_type_u8
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
In kernel/trace/ring_buffer.c (ffffffff8116cf68)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
```
```
In kernel/trace/trace.c (ffffffff81175156)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
```
```
In kernel/trace/trace_output.c (ffffffff8117819f)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
```
In kernel/trace/trace_functions_graph.c (ffffffff81180598)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
```
In kernel/trace/trace_syscalls.c (ffffffff811874ab)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
```
```
In kernel/trace/trace_probe.c (ffffffff81196e82)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_probe.c:print_type_x64
  - kernel/trace/trace_probe.c:print_type_x32
  - kernel/trace/trace_probe.c:print_type_x16
  - kernel/trace/trace_probe.c:print_type_x8
  - kernel/trace/trace_probe.c:print_type_s64
  - kernel/trace/trace_probe.c:print_type_s32
  - kernel/trace/trace_probe.c:print_type_s16
  - kernel/trace/trace_probe.c:print_type_s8
  - kernel/trace/trace_probe.c:print_type_u64
  - kernel/trace/trace_probe.c:print_type_u32
  - kernel/trace/trace_probe.c:print_type_u16
  - kernel/trace/trace_probe.c:print_type_u8
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
In kernel/trace/ring_buffer.c (ffffffff8117bf58)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
```
```
In kernel/trace/trace.c (ffffffff811840d4)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
```
```
In kernel/trace/trace_output.c (ffffffff811873b0)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8118f681)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
```
In kernel/trace/trace_syscalls.c (ffffffff811966ac)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
```
```
In kernel/trace/trace_events_hist.c (ffffffff8119f0ae)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:print_synth_event
```
```
In kernel/trace/trace_probe.c (ffffffff811ac713)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_probe.c:print_type_x64
  - kernel/trace/trace_probe.c:print_type_x32
  - kernel/trace/trace_probe.c:print_type_x16
  - kernel/trace/trace_probe.c:print_type_x8
  - kernel/trace/trace_probe.c:print_type_s64
  - kernel/trace/trace_probe.c:print_type_s32
  - kernel/trace/trace_probe.c:print_type_s16
  - kernel/trace/trace_probe.c:print_type_s8
  - kernel/trace/trace_probe.c:print_type_u64
  - kernel/trace/trace_probe.c:print_type_u32
  - kernel/trace/trace_probe.c:print_type_u16
  - kernel/trace/trace_probe.c:print_type_u8
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
In kernel/trace/ring_buffer.c (ffffffff81189058)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
```
```
In kernel/trace/trace.c (ffffffff81191a44)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
```
```
In kernel/trace/trace_output.c (ffffffff81194d20)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8119ce51)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
```
In kernel/trace/trace_syscalls.c (ffffffff811a47ec)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
```
```
In kernel/trace/trace_events_hist.c (ffffffff811acf6e)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:print_synth_event
```
```
In kernel/trace/trace_probe.c (ffffffff811babed)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_probe.c:print_type_symbol
  - kernel/trace/trace_probe.c:print_type_x64
  - kernel/trace/trace_probe.c:print_type_x32
  - kernel/trace/trace_probe.c:print_type_x16
  - kernel/trace/trace_probe.c:print_type_x8
  - kernel/trace/trace_probe.c:print_type_s64
  - kernel/trace/trace_probe.c:print_type_s32
  - kernel/trace/trace_probe.c:print_type_s16
  - kernel/trace/trace_probe.c:print_type_s8
  - kernel/trace/trace_probe.c:print_type_u64
  - kernel/trace/trace_probe.c:print_type_u32
  - kernel/trace/trace_probe.c:print_type_u16
  - kernel/trace/trace_probe.c:print_type_u8
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
In kernel/trace/ring_buffer.c (ffffffff81196638)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
```
```
In kernel/trace/trace.c (ffffffff8119f455)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
```
```
In kernel/trace/trace_output.c (ffffffff811a2aed)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811aaad3)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b27ce)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
```
```
In kernel/trace/trace_events_hist.c (ffffffff811bb230)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:print_synth_event
```
```
In kernel/trace/trace_probe.c (ffffffff811c9c8d)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_probe.c:print_type_symbol
  - kernel/trace/trace_probe.c:print_type_x64
  - kernel/trace/trace_probe.c:print_type_x32
  - kernel/trace/trace_probe.c:print_type_x16
  - kernel/trace/trace_probe.c:print_type_x8
  - kernel/trace/trace_probe.c:print_type_s64
  - kernel/trace/trace_probe.c:print_type_s32
  - kernel/trace/trace_probe.c:print_type_s16
  - kernel/trace/trace_probe.c:print_type_s8
  - kernel/trace/trace_probe.c:print_type_u64
  - kernel/trace/trace_probe.c:print_type_u32
  - kernel/trace/trace_probe.c:print_type_u16
  - kernel/trace/trace_probe.c:print_type_u8
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
In kernel/trace/ring_buffer.c (ffffffff811a2008)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
```
```
In kernel/trace/trace.c (ffffffff811aae15)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
```
```
In kernel/trace/trace_output.c (ffffffff811ae4ed)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811b62c3)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
```
In kernel/trace/trace_syscalls.c (ffffffff811bddbe)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c6973)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:print_synth_event
```
```
In kernel/trace/trace_probe.c (ffffffff811d59bd)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_probe.c:print_type_symbol
  - kernel/trace/trace_probe.c:print_type_x64
  - kernel/trace/trace_probe.c:print_type_x32
  - kernel/trace/trace_probe.c:print_type_x16
  - kernel/trace/trace_probe.c:print_type_x8
  - kernel/trace/trace_probe.c:print_type_s64
  - kernel/trace/trace_probe.c:print_type_s32
  - kernel/trace/trace_probe.c:print_type_s16
  - kernel/trace/trace_probe.c:print_type_s8
  - kernel/trace/trace_probe.c:print_type_u64
  - kernel/trace/trace_probe.c:print_type_u32
  - kernel/trace/trace_probe.c:print_type_u16
  - kernel/trace/trace_probe.c:print_type_u8
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
In kernel/trace/ring_buffer.c (ffffffff811b91c8)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
```
```
In kernel/trace/trace.c (ffffffff811c30fe)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_bin_fmt
  - kernel/trace/trace.c:print_hex_fmt
  - kernel/trace/trace.c:print_hex_fmt
  - kernel/trace/trace.c:print_raw_fmt
  - kernel/trace/trace.c:print_raw_fmt
  - kernel/trace/trace.c:print_trace_fmt
  - kernel/trace/trace.c:print_trace_fmt
```
```
In kernel/trace/trace_output.c (ffffffff811c66ad)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811ceafa)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d759e)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
```
```
In kernel/trace/trace_events_synth.c (ffffffff811de5f1)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:print_synth_event
```
```
In kernel/trace/trace_probe.c (ffffffff811f22ad)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_probe.c:print_type_symbol
  - kernel/trace/trace_probe.c:print_type_x64
  - kernel/trace/trace_probe.c:print_type_x32
  - kernel/trace/trace_probe.c:print_type_x16
  - kernel/trace/trace_probe.c:print_type_x8
  - kernel/trace/trace_probe.c:print_type_s64
  - kernel/trace/trace_probe.c:print_type_s32
  - kernel/trace/trace_probe.c:print_type_s16
  - kernel/trace/trace_probe.c:print_type_s8
  - kernel/trace/trace_probe.c:print_type_u64
  - kernel/trace/trace_probe.c:print_type_u32
  - kernel/trace/trace_probe.c:print_type_u16
  - kernel/trace/trace_probe.c:print_type_u8
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
In kernel/trace/ring_buffer.c (ffffffff811b6bd8)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
```
```
In kernel/trace/trace.c (ffffffff811c0d0e)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_bin_fmt
  - kernel/trace/trace.c:print_hex_fmt
  - kernel/trace/trace.c:print_hex_fmt
  - kernel/trace/trace.c:print_raw_fmt
  - kernel/trace/trace.c:print_raw_fmt
  - kernel/trace/trace.c:print_trace_fmt
  - kernel/trace/trace.c:print_trace_fmt
```
```
In kernel/trace/trace_output.c (ffffffff811c3c6d)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811cbfda)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d466e)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
```
```
In kernel/trace/trace_events_synth.c (ffffffff811db9d4)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:print_synth_event
```
```
In kernel/trace/trace_probe.c (ffffffff811f0c7d)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_probe.c:print_type_symbol
  - kernel/trace/trace_probe.c:print_type_x64
  - kernel/trace/trace_probe.c:print_type_x32
  - kernel/trace/trace_probe.c:print_type_x16
  - kernel/trace/trace_probe.c:print_type_x8
  - kernel/trace/trace_probe.c:print_type_s64
  - kernel/trace/trace_probe.c:print_type_s32
  - kernel/trace/trace_probe.c:print_type_s16
  - kernel/trace/trace_probe.c:print_type_s8
  - kernel/trace/trace_probe.c:print_type_u64
  - kernel/trace/trace_probe.c:print_type_u32
  - kernel/trace/trace_probe.c:print_type_u16
  - kernel/trace/trace_probe.c:print_type_u8
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
In kernel/trace/ring_buffer.c (ffffffff811b75d8)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
```
```
In kernel/trace/trace.c (ffffffff811c1c7f)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_fmt
  - kernel/trace/trace.c:print_trace_fmt
```
```
In kernel/trace/trace_output.c (ffffffff811c4d7d)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811cd30a)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d5cfe)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
```
```
In kernel/trace/trace_events_synth.c (ffffffff811dcf36)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:print_synth_event
```
```
In kernel/trace/trace_probe.c (ffffffff811f1bdd)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_probe.c:print_type_symbol
  - kernel/trace/trace_probe.c:print_type_x64
  - kernel/trace/trace_probe.c:print_type_x32
  - kernel/trace/trace_probe.c:print_type_x16
  - kernel/trace/trace_probe.c:print_type_x8
  - kernel/trace/trace_probe.c:print_type_s64
  - kernel/trace/trace_probe.c:print_type_s32
  - kernel/trace/trace_probe.c:print_type_s16
  - kernel/trace/trace_probe.c:print_type_s8
  - kernel/trace/trace_probe.c:print_type_u64
  - kernel/trace/trace_probe.c:print_type_u32
  - kernel/trace/trace_probe.c:print_type_u16
  - kernel/trace/trace_probe.c:print_type_u8
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
In kernel/trace/ring_buffer.c (ffffffff811e17d8)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
```
```
In kernel/trace/trace.c (ffffffff811ec81f)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_fmt
  - kernel/trace/trace.c:print_trace_fmt
```
```
In kernel/trace/trace_output.c (ffffffff811f02bd)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811f9ac9)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
```
In kernel/trace/trace_syscalls.c (ffffffff81202aae)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
```
```
In kernel/trace/trace_events_synth.c (ffffffff8120c756)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:print_synth_event
```
```
In kernel/trace/trace_probe.c (ffffffff81222d7d)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_probe.c:print_type_symbol
  - kernel/trace/trace_probe.c:print_type_x64
  - kernel/trace/trace_probe.c:print_type_x32
  - kernel/trace/trace_probe.c:print_type_x16
  - kernel/trace/trace_probe.c:print_type_x8
  - kernel/trace/trace_probe.c:print_type_s64
  - kernel/trace/trace_probe.c:print_type_s32
  - kernel/trace/trace_probe.c:print_type_s16
  - kernel/trace/trace_probe.c:print_type_s8
  - kernel/trace/trace_probe.c:print_type_u64
  - kernel/trace/trace_probe.c:print_type_u32
  - kernel/trace/trace_probe.c:print_type_u16
  - kernel/trace/trace_probe.c:print_type_u8
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
In kernel/trace/ring_buffer.c (ffffffff81218408)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
```
```
In kernel/trace/trace.c (ffffffff81224882)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_fmt
  - kernel/trace/trace.c:print_trace_fmt
```
```
In kernel/trace/trace_output.c (ffffffff812288e9)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
```
In kernel/trace/trace_functions_graph.c (ffffffff81233aaf)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
```
In kernel/trace/trace_syscalls.c (ffffffff8123def8)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
```
```
In kernel/trace/trace_events_synth.c (ffffffff81248d54)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:print_synth_event
```
```
In kernel/trace/trace_probe.c (ffffffff81262ccd)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_probe.c:print_type_symbol
  - kernel/trace/trace_probe.c:print_type_x64
  - kernel/trace/trace_probe.c:print_type_x32
  - kernel/trace/trace_probe.c:print_type_x16
  - kernel/trace/trace_probe.c:print_type_x8
  - kernel/trace/trace_probe.c:print_type_s64
  - kernel/trace/trace_probe.c:print_type_s32
  - kernel/trace/trace_probe.c:print_type_s16
  - kernel/trace/trace_probe.c:print_type_s8
  - kernel/trace/trace_probe.c:print_type_u64
  - kernel/trace/trace_probe.c:print_type_u32
  - kernel/trace/trace_probe.c:print_type_u16
  - kernel/trace/trace_probe.c:print_type_u8
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
In kernel/trace/ring_buffer.c (ffffffff81261965)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
```
```
In kernel/trace/trace.c (ffffffff8126f9f2)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_fmt
  - kernel/trace/trace.c:print_trace_fmt
```
```
In kernel/trace/trace_output.c (ffffffff81273fa9)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
```
In kernel/trace/trace_functions_graph.c (ffffffff812802bf)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
```
In kernel/trace/trace_syscalls.c (ffffffff8128b898)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
```
```
In kernel/trace/trace_events_synth.c (ffffffff81296eb4)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:print_synth_event
```
```
In kernel/trace/trace_probe.c (ffffffff812b465d)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_probe.c:print_type_symbol
  - kernel/trace/trace_probe.c:print_type_x64
  - kernel/trace/trace_probe.c:print_type_x32
  - kernel/trace/trace_probe.c:print_type_x16
  - kernel/trace/trace_probe.c:print_type_x8
  - kernel/trace/trace_probe.c:print_type_s64
  - kernel/trace/trace_probe.c:print_type_s32
  - kernel/trace/trace_probe.c:print_type_s16
  - kernel/trace/trace_probe.c:print_type_s8
  - kernel/trace/trace_probe.c:print_type_u64
  - kernel/trace/trace_probe.c:print_type_u32
  - kernel/trace/trace_probe.c:print_type_u16
  - kernel/trace/trace_probe.c:print_type_u8
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
In kernel/trace/ring_buffer.c (ffffffff812789e5)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
```
```
In kernel/trace/trace.c (ffffffff81286c41)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_fmt
  - kernel/trace/trace.c:print_trace_fmt
```
```
In kernel/trace/trace_output.c (ffffffff8128b8d2)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8129ce5f)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
```
In kernel/trace/trace_syscalls.c (ffffffff812a8798)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
```
```
In kernel/trace/trace_events_synth.c (ffffffff812b3e66)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:print_synth_event
```
```
In kernel/trace/trace_probe.c (ffffffff812d6fcd)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_probe.c:print_type_symbol
  - kernel/trace/trace_probe.c:print_type_char
  - kernel/trace/trace_probe.c:print_type_x64
  - kernel/trace/trace_probe.c:print_type_x32
  - kernel/trace/trace_probe.c:print_type_x16
  - kernel/trace/trace_probe.c:print_type_x8
  - kernel/trace/trace_probe.c:print_type_s64
  - kernel/trace/trace_probe.c:print_type_s32
  - kernel/trace/trace_probe.c:print_type_s16
  - kernel/trace/trace_probe.c:print_type_s8
  - kernel/trace/trace_probe.c:print_type_u64
  - kernel/trace/trace_probe.c:print_type_u32
  - kernel/trace/trace_probe.c:print_type_u16
  - kernel/trace/trace_probe.c:print_type_u8
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
In kernel/trace/ring_buffer.c (ffffffff812934a0)
Location: include/linux/trace_seq.h:78
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
```
```
In kernel/trace/trace.c (ffffffff812a1d11)
Location: include/linux/trace_seq.h:78
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_fmt
  - kernel/trace/trace.c:print_trace_fmt
```
```
In kernel/trace/trace_output.c (ffffffff812a6ca2)
Location: include/linux/trace_seq.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
```
In kernel/trace/trace_functions_graph.c (ffffffff812b853f)
Location: include/linux/trace_seq.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
```
In kernel/trace/trace_syscalls.c (ffffffff812c44a8)
Location: include/linux/trace_seq.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
```
```
In kernel/trace/trace_events_synth.c (ffffffff812d0416)
Location: include/linux/trace_seq.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:print_synth_event
```
```
In kernel/trace/trace_probe.c (ffffffff812f4add)
Location: include/linux/trace_seq.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_probe.c:print_type_symbol
  - kernel/trace/trace_probe.c:print_type_char
  - kernel/trace/trace_probe.c:print_type_x64
  - kernel/trace/trace_probe.c:print_type_x32
  - kernel/trace/trace_probe.c:print_type_x16
  - kernel/trace/trace_probe.c:print_type_x8
  - kernel/trace/trace_probe.c:print_type_s64
  - kernel/trace/trace_probe.c:print_type_s32
  - kernel/trace/trace_probe.c:print_type_s16
  - kernel/trace/trace_probe.c:print_type_s8
  - kernel/trace/trace_probe.c:print_type_u64
  - kernel/trace/trace_probe.c:print_type_u32
  - kernel/trace/trace_probe.c:print_type_u16
  - kernel/trace/trace_probe.c:print_type_u8
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
In kernel/trace/ring_buffer.c (ffff80001021c430)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
```
```
In kernel/trace/trace.c (ffff800010227bd4)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
```
```
In kernel/trace/trace_output.c (ffff80001022b918)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
```
In kernel/trace/trace_functions_graph.c (ffff8000102341b8)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
```
In kernel/trace/trace_syscalls.c (ffff80001023d1d8)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
```
```
In kernel/trace/trace_events_hist.c (ffff800010246ca0)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:print_synth_event
```
```
In kernel/trace/trace_probe.c (ffff800010255d98)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_probe.c:print_type_symbol
  - kernel/trace/trace_probe.c:print_type_x64
  - kernel/trace/trace_probe.c:print_type_x32
  - kernel/trace/trace_probe.c:print_type_x16
  - kernel/trace/trace_probe.c:print_type_x8
  - kernel/trace/trace_probe.c:print_type_s64
  - kernel/trace/trace_probe.c:print_type_s32
  - kernel/trace/trace_probe.c:print_type_s16
  - kernel/trace/trace_probe.c:print_type_s8
  - kernel/trace/trace_probe.c:print_type_u64
  - kernel/trace/trace_probe.c:print_type_u32
  - kernel/trace/trace_probe.c:print_type_u16
  - kernel/trace/trace_probe.c:print_type_u8
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
In kernel/trace/ring_buffer.c (c045ae84)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
```
```
In kernel/trace/trace.c (c046526c)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
```
```
In kernel/trace/trace_output.c (c0468e28)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
```
In kernel/trace/trace_functions_graph.c (c046fef8)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
```
In kernel/trace/trace_syscalls.c (c0478878)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
```
```
In kernel/trace/trace_probe.c (c0488eb4)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_probe.c:print_type_symbol
  - kernel/trace/trace_probe.c:print_type_x64
  - kernel/trace/trace_probe.c:print_type_x32
  - kernel/trace/trace_probe.c:print_type_x16
  - kernel/trace/trace_probe.c:print_type_x8
  - kernel/trace/trace_probe.c:print_type_s64
  - kernel/trace/trace_probe.c:print_type_s32
  - kernel/trace/trace_probe.c:print_type_s16
  - kernel/trace/trace_probe.c:print_type_s8
  - kernel/trace/trace_probe.c:print_type_u64
  - kernel/trace/trace_probe.c:print_type_u32
  - kernel/trace/trace_probe.c:print_type_u16
  - kernel/trace/trace_probe.c:print_type_u8
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
In kernel/trace/ring_buffer.c (c00000000029fadc)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
```
```
In kernel/trace/trace.c (c0000000002ae194)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
```
```
In kernel/trace/trace_output.c (c0000000002b3a10)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
```
In kernel/trace/trace_functions_graph.c (c0000000002bf9b4)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
```
In kernel/trace/trace_syscalls.c (c0000000002cc540)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
```
```
In kernel/trace/trace_events_hist.c (c0000000002db5a0)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:print_synth_event
```
```
In kernel/trace/trace_probe.c (c0000000002f6058)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_probe.c:print_type_symbol
  - kernel/trace/trace_probe.c:print_type_x64
  - kernel/trace/trace_probe.c:print_type_x32
  - kernel/trace/trace_probe.c:print_type_x16
  - kernel/trace/trace_probe.c:print_type_x8
  - kernel/trace/trace_probe.c:print_type_s64
  - kernel/trace/trace_probe.c:print_type_s32
  - kernel/trace/trace_probe.c:print_type_s16
  - kernel/trace/trace_probe.c:print_type_s8
  - kernel/trace/trace_probe.c:print_type_u64
  - kernel/trace/trace_probe.c:print_type_u32
  - kernel/trace/trace_probe.c:print_type_u16
  - kernel/trace/trace_probe.c:print_type_u8
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
In kernel/trace/ring_buffer.c (ffffffe000179f8a)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
```
```
In kernel/trace/trace.c (ffffffe0001824ba)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
```
```
In kernel/trace/trace_output.c (ffffffe000185882)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
```
In kernel/trace/trace_functions_graph.c (ffffffe00018b9c6)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
```
In kernel/trace/trace_syscalls.c (ffffffe000193020)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
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
In kernel/trace/ring_buffer.c (ffffffff8119a628)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
```
```
In kernel/trace/trace.c (ffffffff811a3435)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
```
```
In kernel/trace/trace_output.c (ffffffff811a6b0d)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811ae8e3)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b63de)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
```
```
In kernel/trace/trace_events_hist.c (ffffffff811bef93)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:print_synth_event
```
```
In kernel/trace/trace_probe.c (ffffffff811cdfdd)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_probe.c:print_type_symbol
  - kernel/trace/trace_probe.c:print_type_x64
  - kernel/trace/trace_probe.c:print_type_x32
  - kernel/trace/trace_probe.c:print_type_x16
  - kernel/trace/trace_probe.c:print_type_x8
  - kernel/trace/trace_probe.c:print_type_s64
  - kernel/trace/trace_probe.c:print_type_s32
  - kernel/trace/trace_probe.c:print_type_s16
  - kernel/trace/trace_probe.c:print_type_s8
  - kernel/trace/trace_probe.c:print_type_u64
  - kernel/trace/trace_probe.c:print_type_u32
  - kernel/trace/trace_probe.c:print_type_u16
  - kernel/trace/trace_probe.c:print_type_u8
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
In kernel/trace/ring_buffer.c (ffffffff8118d6a8)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
```
```
In kernel/trace/trace.c (ffffffff81196405)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
```
```
In kernel/trace/trace_output.c (ffffffff81199a8d)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811a1733)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
```
In kernel/trace/trace_syscalls.c (ffffffff811a91de)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
```
```
In kernel/trace/trace_events_hist.c (ffffffff811b1d73)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:print_synth_event
```
```
In kernel/trace/trace_probe.c (ffffffff811c0dad)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_probe.c:print_type_symbol
  - kernel/trace/trace_probe.c:print_type_x64
  - kernel/trace/trace_probe.c:print_type_x32
  - kernel/trace/trace_probe.c:print_type_x16
  - kernel/trace/trace_probe.c:print_type_x8
  - kernel/trace/trace_probe.c:print_type_s64
  - kernel/trace/trace_probe.c:print_type_s32
  - kernel/trace/trace_probe.c:print_type_s16
  - kernel/trace/trace_probe.c:print_type_s8
  - kernel/trace/trace_probe.c:print_type_u64
  - kernel/trace/trace_probe.c:print_type_u32
  - kernel/trace/trace_probe.c:print_type_u16
  - kernel/trace/trace_probe.c:print_type_u8
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
In kernel/trace/ring_buffer.c (ffffffff811983f8)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
```
```
In kernel/trace/trace.c (ffffffff811a1205)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
```
```
In kernel/trace/trace_output.c (ffffffff811a48dd)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811ac6b3)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b41ae)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
```
```
In kernel/trace/trace_events_hist.c (ffffffff811bcd63)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:print_synth_event
```
```
In kernel/trace/trace_probe.c (ffffffff811cbdad)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_probe.c:print_type_symbol
  - kernel/trace/trace_probe.c:print_type_x64
  - kernel/trace/trace_probe.c:print_type_x32
  - kernel/trace/trace_probe.c:print_type_x16
  - kernel/trace/trace_probe.c:print_type_x8
  - kernel/trace/trace_probe.c:print_type_s64
  - kernel/trace/trace_probe.c:print_type_s32
  - kernel/trace/trace_probe.c:print_type_s16
  - kernel/trace/trace_probe.c:print_type_s8
  - kernel/trace/trace_probe.c:print_type_u64
  - kernel/trace/trace_probe.c:print_type_u32
  - kernel/trace/trace_probe.c:print_type_u16
  - kernel/trace/trace_probe.c:print_type_u8
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
In kernel/trace/ring_buffer.c (ffffffff811a6028)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_page_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
```
```
In kernel/trace/trace.c (ffffffff811aef95)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
```
```
In kernel/trace/trace_output.c (ffffffff811b266d)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811ba583)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
```
In kernel/trace/trace_syscalls.c (ffffffff811c224e)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:print_syscall_enter
```
```
In kernel/trace/trace_events_hist.c (ffffffff811cae03)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:print_synth_event
```
```
In kernel/trace/trace_probe.c (ffffffff811da00d)
Location: include/linux/trace_seq.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_probe.c:print_type_symbol
  - kernel/trace/trace_probe.c:print_type_x64
  - kernel/trace/trace_probe.c:print_type_x32
  - kernel/trace/trace_probe.c:print_type_x16
  - kernel/trace/trace_probe.c:print_type_x8
  - kernel/trace/trace_probe.c:print_type_s64
  - kernel/trace/trace_probe.c:print_type_s32
  - kernel/trace/trace_probe.c:print_type_s16
  - kernel/trace/trace_probe.c:print_type_s8
  - kernel/trace/trace_probe.c:print_type_u64
  - kernel/trace/trace_probe.c:print_type_u32
  - kernel/trace/trace_probe.c:print_type_u16
  - kernel/trace/trace_probe.c:print_type_u8
```
</details>
</li>
</ul>

## Differences
