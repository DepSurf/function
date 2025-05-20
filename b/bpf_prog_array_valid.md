# Function: <code>bpf_prog_array_valid</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81002f33)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8100470e)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff81026c93)
Location: include/linux/trace_events.h:288
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
In arch/x86/hyperv/mmu.c (ffffffff8102ade5)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff8102ea78)
Location: include/linux/trace_events.h:288
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
In arch/x86/kernel/nmi.c (ffffffff810311c8)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103898e)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81048cde)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:perf_trace_mce_record
```
```
In arch/x86/mm/init.c (ffffffff8106fe63)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff81071ca8)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff8107edae)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff81087194)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff8108b6f8)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff810908ce)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810988f8)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810a37ce)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/sched/core.c (ffffffff810b1c5e)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
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
In kernel/printk/printk.c (ffffffff810e9525)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff810f8bc8)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff810f9b9e)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/time/timer.c (ffffffff81107253)
Location: include/linux/trace_events.h:288
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
In kernel/time/alarmtimer.c (ffffffff81111173)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff81122309)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff8112ec51)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_syscalls.c (ffffffff8118761f)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811912ca)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/power-traces.c (ffffffff81194668)
Location: include/linux/trace_events.h:288
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
In kernel/trace/rpm-traces.c (ffffffff8119601a)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff81198c69)
Location: include/linux/trace_events.h:288
Inline: True
```
```
In kernel/bpf/core.c (ffffffff8119b468)
Location: include/linux/trace_events.h:288
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
In kernel/events/core.c (ffffffff811b6b93)
Location: include/linux/trace_events.h:288
Inline: True
```
```
In mm/filemap.c (ffffffff811c9d53)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff811d0f5c)
Location: include/linux/trace_events.h:288
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
In mm/swap.c (ffffffff811deeae)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff811e3f18)
Location: include/linux/trace_events.h:288
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
In mm/percpu.c (ffffffff811f872e)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff811fbd58)
Location: include/linux/trace_events.h:288
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
In mm/compaction.c (ffffffff811fe8d8)
Location: include/linux/trace_events.h:288
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
In mm/migrate.c (ffffffff81249067)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_numa_migrate_ratelimit
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff81256128)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff812669d8)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff8126a548)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff8126fbf2)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/fs-writeback.c (ffffffff812a140e)
Location: include/linux/trace_events.h:288
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
In fs/dax.c (ffffffff812cc158)
Location: include/linux/trace_events.h:288
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
In fs/locks.c (ffffffff812d2603)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff8134c143)
Location: include/linux/trace_events.h:288
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
In fs/jbd2/journal.c (ffffffff8136bbe3)
Location: include/linux/trace_events.h:288
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
In block/blk-core.c (ffffffff8144b4a5)
Location: include/linux/trace_events.h:288
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
In block/blk-wbt.c (ffffffff81483a48)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In lib/swiotlb.c (ffffffff814be70d)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - lib/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In arch/x86/lib/msr.c (ffffffff814c8838)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff814d7588)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff815ab1f5)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff815d3e75)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff8160baf8)
Location: include/linux/trace_events.h:288
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
In drivers/iommu/iommu-traces.c (ffffffff81628cac)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff816639e3)
Location: include/linux/trace_events.h:288
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
In drivers/dma-buf/dma-fence.c (ffffffff816a84f2)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816aa7a7)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff816ab61e)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff816ced7e)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff816f2053)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff816fbbf8)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81770a8e)
Location: include/linux/trace_events.h:288
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
In drivers/i2c/i2c-core-base.c (ffffffff8178f958)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff817933e8)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/thermal/thermal_core.c (ffffffff817a07bc)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff817a4868)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff817e9476)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/ras/ras.c (ffffffff8181a568)
Location: include/linux/trace_events.h:288
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
In net/core/net-traces.c (ffffffff81873506)
Location: include/linux/trace_events.h:288
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
In init/main.c (ffffffff81002173)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/common.c (ffffffff810036f3)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004e7e)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff81027783)
Location: include/linux/trace_events.h:288
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
In arch/x86/hyperv/mmu.c (ffffffff8102b9c5)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff8102fab8)
Location: include/linux/trace_events.h:288
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
In arch/x86/kernel/nmi.c (ffffffff81032558)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039f1e)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104b60e)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:perf_trace_mce_record
```
```
In arch/x86/mm/init.c (ffffffff81072cd3)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff81074a98)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff81081f3e)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff8108a5e4)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff8108ef68)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff810944de)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff8109c0d8)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810aa2ae)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/sched/core.c (ffffffff810b8cfe)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
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
In kernel/printk/printk.c (ffffffff810f17f8)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff81101128)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff8110210e)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff8110d64a)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffffffff81112723)
Location: include/linux/trace_events.h:288
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
In kernel/time/alarmtimer.c (ffffffff8111cb63)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff8112fe18)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff8113cf57)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_syscalls.c (ffffffff81196811)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811a6819)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/power-traces.c (ffffffff811aa247)
Location: include/linux/trace_events.h:288
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
In kernel/trace/rpm-traces.c (ffffffff811ab889)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ae349)
Location: include/linux/trace_events.h:288
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811b0a9c)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/events/core.c (ffffffff811d64d0)
Location: include/linux/trace_events.h:288
Inline: True
```
```
In kernel/rseq.c (ffffffff811e9cb8)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff811eaeb3)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff811f218c)
Location: include/linux/trace_events.h:288
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
In mm/swap.c (ffffffff8120075e)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81205568)
Location: include/linux/trace_events.h:288
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
In mm/percpu.c (ffffffff812199be)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff8121cfe8)
Location: include/linux/trace_events.h:288
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
In mm/compaction.c (ffffffff8121fc38)
Location: include/linux/trace_events.h:288
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
In mm/migrate.c (ffffffff8126cb27)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_numa_migrate_ratelimit
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff8127a038)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff8128b278)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff8128ef28)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff81295921)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/fs-writeback.c (ffffffff812c7f8e)
Location: include/linux/trace_events.h:288
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
In fs/dax.c (ffffffff812f6498)
Location: include/linux/trace_events.h:288
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
In fs/locks.c (ffffffff812fd0c3)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff8137a158)
Location: include/linux/trace_events.h:288
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
In fs/jbd2/journal.c (ffffffff8139a383)
Location: include/linux/trace_events.h:288
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
In block/blk-core.c (ffffffff8147e7b5)
Location: include/linux/trace_events.h:288
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
In block/blk-wbt.c (ffffffff814b87ec)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff814f97d8)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff81506808)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff815e31c4)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff8160bdc4)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff816455a8)
Location: include/linux/trace_events.h:288
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
In drivers/iommu/iommu-traces.c (ffffffff816639fd)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff8169fb35)
Location: include/linux/trace_events.h:288
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
In drivers/dma-buf/dma-fence.c (ffffffff816e47d7)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816e6ca6)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff816e7b3e)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff8170b80e)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff8172eaa3)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff817391b0)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff817b0e7e)
Location: include/linux/trace_events.h:288
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
In drivers/rtc/interface.c (ffffffff817cc53e)
Location: include/linux/trace_events.h:288
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
In drivers/i2c/i2c-core-base.c (ffffffff817d22c8)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff817d5cf8)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/thermal/thermal_core.c (ffffffff817e7d8d)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff817ec348)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff818322f1)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/ras/ras.c (ffffffff818645f8)
Location: include/linux/trace_events.h:288
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
In net/core/net-traces.c (ffffffff818c4c9b)
Location: include/linux/trace_events.h:288
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
In net/ipv6/route.c (ffffffff819701eb)
Location: include/linux/trace_events.h:288
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
In init/main.c (ffffffff81002173)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/common.c (ffffffff81003783)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004dde)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff81027d63)
Location: include/linux/trace_events.h:288
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
In arch/x86/hyperv/mmu.c (ffffffff8102c415)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff81030d48)
Location: include/linux/trace_events.h:288
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
In arch/x86/kernel/nmi.c (ffffffff81033818)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103b43e)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81048cce)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105bd93)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff81078d63)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff8107a958)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff81088b4e)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff81092584)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff81097268)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff8109c83e)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810a4338)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810b337e)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/sched/core.c (ffffffff810c1dfe)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
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
In kernel/printk/printk.c (ffffffff810fcea8)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff8110ca48)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff8110db0e)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff8111924a)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffffffff8111def3)
Location: include/linux/trace_events.h:288
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
In kernel/time/alarmtimer.c (ffffffff81128313)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff8113b6c8)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff81148895)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_syscalls.c (ffffffff811a4951)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811b692a)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/power-traces.c (ffffffff811b85f7)
Location: include/linux/trace_events.h:288
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
In kernel/trace/rpm-traces.c (ffffffff811b9e49)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff811bca59)
Location: include/linux/trace_events.h:288
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811bf11c)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_exception
```
```
In kernel/events/core.c (ffffffff811e6e70)
Location: include/linux/trace_events.h:288
Inline: True
```
```
In kernel/rseq.c (ffffffff811fa828)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff811fba23)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff81203ffc)
Location: include/linux/trace_events.h:288
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
In mm/swap.c (ffffffff812130ce)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81217f38)
Location: include/linux/trace_events.h:288
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
In mm/percpu.c (ffffffff8122c92e)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff8122ffd8)
Location: include/linux/trace_events.h:288
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
In mm/compaction.c (ffffffff81232c68)
Location: include/linux/trace_events.h:288
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
In mm/migrate.c (ffffffff81281228)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff8128e638)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff812a01c8)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff812a3e28)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff812aa711)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/fs-writeback.c (ffffffff812dd18e)
Location: include/linux/trace_events.h:288
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
In fs/dax.c (ffffffff8130b588)
Location: include/linux/trace_events.h:288
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
In fs/locks.c (ffffffff81312933)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff81392bf8)
Location: include/linux/trace_events.h:288
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
In fs/jbd2/journal.c (ffffffff813b30f3)
Location: include/linux/trace_events.h:288
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
In block/blk-core.c (ffffffff8149be05)
Location: include/linux/trace_events.h:288
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
In block/blk-wbt.c (ffffffff814cc7dc)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff8150e078)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff8151ae08)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff815fd5e5)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff81623c34)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff816638a8)
Location: include/linux/trace_events.h:288
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
In drivers/iommu/iommu-traces.c (ffffffff81681fed)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff816bff45)
Location: include/linux/trace_events.h:288
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
In drivers/dma-buf/dma-fence.c (ffffffff81707bc7)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8170a036)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff8170b63e)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff8172dc8e)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff81751013)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff8175c8d0)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff817d73fe)
Location: include/linux/trace_events.h:288
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
In drivers/rtc/interface.c (ffffffff817f383e)
Location: include/linux/trace_events.h:288
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
In drivers/i2c/i2c-core-base.c (ffffffff817f9428)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff817fce28)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff818117eb)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff81813c3d)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff81818218)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff8185e4f1)
Location: include/linux/trace_events.h:288
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/ras/ras.c (ffffffff818841c8)
Location: include/linux/trace_events.h:288
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
In net/core/net-traces.c (ffffffff818edd0b)
Location: include/linux/trace_events.h:288
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
In net/ipv6/route.c (ffffffff819a5e1b)
Location: include/linux/trace_events.h:288
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
In init/main.c (ffffffff81002203)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/common.c (ffffffff810038c3)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004eae)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff810299d3)
Location: include/linux/trace_events.h:289
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
In arch/x86/hyperv/mmu.c (ffffffff8102d7f5)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff81032a9c)
Location: include/linux/trace_events.h:289
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
In arch/x86/kernel/nmi.c (ffffffff810355a8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103da0e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104bd7e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105f103)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff8107c953)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff8107e6c8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff8108c71e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff81096414)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff8109b7fc)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff810a0e7e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810a8ff8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810b8f2e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/sched/core.c (ffffffff810c7e4e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
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
In kernel/printk/printk.c (ffffffff81105598)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff81116127)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff811171ae)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff81123cac)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffffffff81128b63)
Location: include/linux/trace_events.h:289
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
In kernel/time/alarmtimer.c (ffffffff81132d53)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff81146d09)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff81153895)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b2896)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c59b9)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/power-traces.c (ffffffff811c76f8)
Location: include/linux/trace_events.h:289
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
In kernel/trace/rpm-traces.c (ffffffff811c8e97)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cc1ad)
Location: include/linux/trace_events.h:289
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811cf433)
Location: include/linux/trace_events.h:289
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
In kernel/events/core.c (ffffffff811fe4e0)
Location: include/linux/trace_events.h:289
Inline: True
```
```
In kernel/rseq.c (ffffffff81211f7c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff812130f3)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff8121b3df)
Location: include/linux/trace_events.h:289
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
In mm/swap.c (ffffffff812229ee)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81227978)
Location: include/linux/trace_events.h:289
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
In mm/percpu.c (ffffffff8123c9ae)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff8124001f)
Location: include/linux/trace_events.h:289
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
In mm/compaction.c (ffffffff812431f8)
Location: include/linux/trace_events.h:289
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
In mm/migrate.c (ffffffff8129d55c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff812a8f6c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff812bb448)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff812bf238)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff812c6ee2)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/fs-writeback.c (ffffffff812fb83e)
Location: include/linux/trace_events.h:289
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
In fs/dax.c (ffffffff81332a18)
Location: include/linux/trace_events.h:289
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
In fs/locks.c (ffffffff81339ff7)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff813bca98)
Location: include/linux/trace_events.h:289
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
In fs/jbd2/journal.c (ffffffff813dd6c3)
Location: include/linux/trace_events.h:289
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
In block/blk-core.c (ffffffff814c9f15)
Location: include/linux/trace_events.h:289
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
In block/blk-wbt.c (ffffffff814fb02c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff8153c6e8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff81548d78)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff8162e835)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff81656842)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff81699228)
Location: include/linux/trace_events.h:289
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
In drivers/iommu/iommu-traces.c (ffffffff816b9740)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff816fada3)
Location: include/linux/trace_events.h:289
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
In drivers/dma-buf/dma-fence.c (ffffffff81742dfb)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81745856)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff81746d7e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff817693fe)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff8178f321)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81799de0)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81817a1e)
Location: include/linux/trace_events.h:289
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
In drivers/rtc/interface.c (ffffffff8183452e)
Location: include/linux/trace_events.h:289
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
In drivers/i2c/i2c-core-base.c (ffffffff8183a128)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8183dea0)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff818537f2)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff818557ec)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff8185a340)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff818a1ee8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff818bed8e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_cmd_class
```
```
In drivers/devfreq/devfreq.c (ffffffff818c77b5)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/ras/ras.c (ffffffff818ce8b8)
Location: include/linux/trace_events.h:289
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
In net/core/net-traces.c (ffffffff8193e61b)
Location: include/linux/trace_events.h:289
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
In net/core/devlink.c (ffffffff81949f74)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/bpf/test_run.c (ffffffff8196cf7e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (ffffffff81a1243b)
Location: include/linux/trace_events.h:289
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
In init/main.c (ffffffff81002203)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/common.c (ffffffff810038c3)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004f2e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff8102a2d3)
Location: include/linux/trace_events.h:289
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
In arch/x86/hyperv/mmu.c (ffffffff8102e105)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff8103335c)
Location: include/linux/trace_events.h:289
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
In arch/x86/kernel/nmi.c (ffffffff81035dd8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e1ce)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c73e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105f983)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff8107da03)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff8107f758)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff8108d37e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff8109c9d4)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff810a1d7c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff810a743e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810af5c8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810bf46e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/sched/core.c (ffffffff810d0f1e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
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
In kernel/printk/printk.c (ffffffff81111918)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff811224f7)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff8112357e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff8112fc3c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffffffff81134b03)
Location: include/linux/trace_events.h:289
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
In kernel/time/alarmtimer.c (ffffffff8113ecb3)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff811528e9)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff8115f4e5)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_syscalls.c (ffffffff811bde86)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811d1694)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/power-traces.c (ffffffff811d33e8)
Location: include/linux/trace_events.h:289
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
In kernel/trace/rpm-traces.c (ffffffff811d4b87)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d86c4)
Location: include/linux/trace_events.h:289
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811dba33)
Location: include/linux/trace_events.h:289
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
In kernel/events/core.c (ffffffff8120b780)
Location: include/linux/trace_events.h:289
Inline: True
```
```
In kernel/rseq.c (ffffffff8121f75c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff812208b3)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff8122854f)
Location: include/linux/trace_events.h:289
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
In mm/swap.c (ffffffff8123049e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81235818)
Location: include/linux/trace_events.h:289
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
In mm/percpu.c (ffffffff8124adfe)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff8124e42f)
Location: include/linux/trace_events.h:289
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
In mm/compaction.c (ffffffff812516b8)
Location: include/linux/trace_events.h:289
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
In mm/migrate.c (ffffffff812acd3c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff812ba4dc)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff812cd328)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff812d1188)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff812d88f2)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/fs-writeback.c (ffffffff8130e1ae)
Location: include/linux/trace_events.h:289
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
In fs/dax.c (ffffffff813465c8)
Location: include/linux/trace_events.h:289
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
In fs/locks.c (ffffffff81352527)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff813d5d68)
Location: include/linux/trace_events.h:289
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
In fs/jbd2/journal.c (ffffffff813f7713)
Location: include/linux/trace_events.h:289
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
In block/blk-core.c (ffffffff814e30f5)
Location: include/linux/trace_events.h:289
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
In block/blk-iocost.c (ffffffff815114f2)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_activate
```
```
In block/blk-wbt.c (ffffffff81518f6c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff8155d4f8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff81569df8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff81650365)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff81679d82)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff816bbe38)
Location: include/linux/trace_events.h:289
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
In drivers/iommu/iommu-traces.c (ffffffff816dc530)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/iommu/intel-trace.c (ffffffff816f1118)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/iommu/intel-trace.c:perf_trace_dma_unmap
  - drivers/iommu/intel-trace.c:perf_trace_dma_map
```
```
In drivers/base/regmap/regmap.c (ffffffff8171f153)
Location: include/linux/trace_events.h:289
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
In drivers/dma-buf/dma-fence.c (ffffffff81766dcb)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff817699d6)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff8176aece)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff8178d45e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff817b2ee1)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff817bd8b0)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81848d5e)
Location: include/linux/trace_events.h:289
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
In drivers/rtc/interface.c (ffffffff81865e7e)
Location: include/linux/trace_events.h:289
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
In drivers/i2c/i2c-core-base.c (ffffffff8186ba98)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8186f840)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff81885262)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff8188724c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff8188be50)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff818d41e8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff818f18de)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_cmd_class
```
```
In drivers/devfreq/devfreq.c (ffffffff818f9c95)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/ras/ras.c (ffffffff81900ca8)
Location: include/linux/trace_events.h:289
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
In net/core/net-traces.c (ffffffff819714ab)
Location: include/linux/trace_events.h:289
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
In net/core/devlink.c (ffffffff8197f9c4)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/bpf/test_run.c (ffffffff819a389e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (ffffffff81a4902b)
Location: include/linux/trace_events.h:289
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
In init/main.c (ffffffff81003233)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/common.c (ffffffff81004b94)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005e4e)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff8102c1d3)
Location: include/linux/trace_events.h:313
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
In arch/x86/hyperv/mmu.c (ffffffff810303b3)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_one
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff8103519c)
Location: include/linux/trace_events.h:313
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
In arch/x86/kernel/nmi.c (ffffffff81037de7)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8104162e)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81050f8e)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81065463)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff810840b3)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff81086738)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In kernel/fork.c (ffffffff810a3614)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff810a8c0c)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff810aeb8e)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810b72d7)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810c6813)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_end
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_activate_work
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
```
```
In kernel/sched/core.c (ffffffff810dac6e)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
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
In kernel/printk/printk.c (ffffffff8111cff1)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff8112eb3b)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff8112fbfe)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff8113ea1f)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffffffff811437c3)
Location: include/linux/trace_events.h:313
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
In kernel/time/alarmtimer.c (ffffffff8114deb3)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff8116418e)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff8116f9c2)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d7c30)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ed162)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/power-traces.c (ffffffff811efdfd)
Location: include/linux/trace_events.h:313
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
In kernel/trace/rpm-traces.c (ffffffff811f119f)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4748)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/core.c (ffffffff811f85e3)
Location: include/linux/trace_events.h:313
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
In kernel/events/core.c (ffffffff812374c0)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/events/core.c:perf_trace_run_bpf_submit
```
```
In kernel/rseq.c (ffffffff8124ba2c)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff8124dc62)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff81254f01)
Location: include/linux/trace_events.h:313
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
In mm/swap.c (ffffffff8125d74e)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81262ea7)
Location: include/linux/trace_events.h:313
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
In mm/percpu.c (ffffffff81278cbe)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff8127d858)
Location: include/linux/trace_events.h:313
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
In mm/compaction.c (ffffffff8127fdd7)
Location: include/linux/trace_events.h:313
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
In mm/mmap.c (ffffffff81298313)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - mm/mmap.c:perf_trace_vm_unmapped_area
```
```
In mm/migrate.c (ffffffff812e1dec)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff812ef0fc)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff81303588)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In fs/fs-writeback.c (ffffffff81347a0e)
Location: include/linux/trace_events.h:313
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
In fs/io_uring.c (ffffffff8137a598)
Location: include/linux/trace_events.h:313
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
In fs/dax.c (ffffffff8138bdd8)
Location: include/linux/trace_events.h:313
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
In fs/locks.c (ffffffff81398ee7)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/iomap/trace.c (ffffffff813a9175)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - fs/iomap/trace.c:perf_trace_iomap_apply
  - fs/iomap/trace.c:perf_trace_iomap_class
  - fs/iomap/trace.c:perf_trace_iomap_range_class
  - fs/iomap/trace.c:perf_trace_iomap_readpage_class
```
```
In fs/ext4/super.c (ffffffff81422488)
Location: include/linux/trace_events.h:313
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
In fs/jbd2/journal.c (ffffffff81444b43)
Location: include/linux/trace_events.h:313
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
In block/blk-core.c (ffffffff81541b69)
Location: include/linux/trace_events.h:313
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
In block/blk-iocost.c (ffffffff81572011)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_activate
```
```
In block/blk-wbt.c (ffffffff8157958c)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff815e6e17)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff8160c757)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/pwm/core.c (ffffffff8161ae23)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/pwm/core.c:perf_trace_pwm
```
```
In drivers/clk/clk.c (ffffffff816fe48a)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff81728c27)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff817701c7)
Location: include/linux/trace_events.h:313
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
In drivers/iommu/iommu-traces.c (ffffffff8179144e)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/iommu/intel/trace.c (ffffffff817a8ca4)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/iommu/intel/trace.c:perf_trace_dma_map_sg
  - drivers/iommu/intel/trace.c:perf_trace_dma_unmap
  - drivers/iommu/intel/trace.c:perf_trace_dma_map
```
```
In drivers/base/regmap/regmap.c (ffffffff817dad84)
Location: include/linux/trace_events.h:313
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
In drivers/dma-buf/dma-fence.c (ffffffff818264cb)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8182bb9e)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff8182d1be)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff81851cde)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff81879411)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff818862c0)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff8191b58e)
Location: include/linux/trace_events.h:313
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
In drivers/rtc/interface.c (ffffffff8193981e)
Location: include/linux/trace_events.h:313
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
In drivers/i2c/i2c-core-base.c (ffffffff8193f7c8)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81943780)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff819537be)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff81955641)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff8195aa20)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff819a67e2)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff819c6ff2)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_start
```
```
In drivers/devfreq/devfreq.c (ffffffff819d010a)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/ras/ras.c (ffffffff819d7cc7)
Location: include/linux/trace_events.h:313
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
In drivers/interconnect/core.c (ffffffff819dd43f)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/interconnect/core.c:perf_trace_icc_set_bw_end
  - drivers/interconnect/core.c:perf_trace_icc_set_bw
```
```
In net/core/net-traces.c (ffffffff81a44eab)
Location: include/linux/trace_events.h:313
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
In net/core/devlink.c (ffffffff81a51b11)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/bpf/test_run.c (ffffffff81a7df3e)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (ffffffff81b3fb0b)
Location: include/linux/trace_events.h:313
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
In init/main.c (ffffffff810032f3)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004ffe)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff8102d183)
Location: include/linux/trace_events.h:313
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
In arch/x86/hyperv/mmu.c (ffffffff81031123)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_one
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff810363ac)
Location: include/linux/trace_events.h:313
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
In arch/x86/kernel/nmi.c (ffffffff81038927)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810416ce)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105025e)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81063713)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff81085603)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff81087028)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In kernel/fork.c (ffffffff8109ee34)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff810a465c)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff810aa35e)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810b2567)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810c18a3)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_end
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_activate_work
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
```
```
In kernel/sched/core.c (ffffffff810d71ee)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
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
In kernel/printk/printk.c (ffffffff81117ac1)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff8112ab1b)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff8112ba5e)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff8113a08f)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/entry/common.c (ffffffff8113b1d4)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/entry/common.c:perf_trace_sys_exit
  - kernel/entry/common.c:perf_trace_sys_enter
```
```
In kernel/time/timer.c (ffffffff8113fe33)
Location: include/linux/trace_events.h:313
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
In kernel/time/alarmtimer.c (ffffffff8114a143)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff8116011e)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff8116c472)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d4d00)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/bpf_trace.c (ffffffff811e8172)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_trace_bpf_trace_printk
```
```
In kernel/trace/trace_kprobe.c (ffffffff811eb2b2)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/power-traces.c (ffffffff811ee69d)
Location: include/linux/trace_events.h:313
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
In kernel/trace/rpm-traces.c (ffffffff811efbcf)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f30d8)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/core.c (ffffffff811f75d3)
Location: include/linux/trace_events.h:313
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
In kernel/events/core.c (ffffffff812410d0)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/events/core.c:perf_trace_run_bpf_submit
```
```
In kernel/rseq.c (ffffffff81255ebc)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff812581b2)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff8125fbd1)
Location: include/linux/trace_events.h:313
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
In mm/swap.c (ffffffff81267b8e)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8126d837)
Location: include/linux/trace_events.h:313
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
In mm/percpu.c (ffffffff8128352e)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff81288028)
Location: include/linux/trace_events.h:313
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
In mm/compaction.c (ffffffff81289e77)
Location: include/linux/trace_events.h:313
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
In mm/mmap_lock.c (ffffffff8129642e)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - mm/mmap_lock.c:perf_trace_mmap_lock_released
  - mm/mmap_lock.c:perf_trace_mmap_lock_acquire_returned
  - mm/mmap_lock.c:perf_trace_mmap_lock_start_locking
```
```
In mm/mmap.c (ffffffff812a34c3)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - mm/mmap.c:perf_trace_vm_unmapped_area
```
```
In mm/migrate.c (ffffffff812ecce0)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff812fa8cc)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff8130f4b8)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In fs/fs-writeback.c (ffffffff81354c1e)
Location: include/linux/trace_events.h:313
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
In fs/io_uring.c (ffffffff81388868)
Location: include/linux/trace_events.h:313
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
In fs/dax.c (ffffffff8139d508)
Location: include/linux/trace_events.h:313
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
In fs/locks.c (ffffffff813aa9c7)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/iomap/trace.c (ffffffff813ba815)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - fs/iomap/trace.c:perf_trace_iomap_apply
  - fs/iomap/trace.c:perf_trace_iomap_class
  - fs/iomap/trace.c:perf_trace_iomap_range_class
  - fs/iomap/trace.c:perf_trace_iomap_readpage_class
```
```
In fs/ext4/super.c (ffffffff8143968c)
Location: include/linux/trace_events.h:313
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
In fs/jbd2/journal.c (ffffffff81461203)
Location: include/linux/trace_events.h:313
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
In security/selinux/avc.c (ffffffff814caf61)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - security/selinux/avc.c:perf_trace_selinux_audited
```
```
In block/blk-core.c (ffffffff8155e659)
Location: include/linux/trace_events.h:313
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
In block/blk-iocost.c (ffffffff8158e911)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_iocg_forgive_debt
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_state
```
```
In block/blk-wbt.c (ffffffff8159633c)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff8160c087)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff81633527)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/pwm/core.c (ffffffff816415a3)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/pwm/core.c:perf_trace_pwm
```
```
In drivers/clk/clk.c (ffffffff8171b7ca)
Location: include/linux/trace_events.h:313
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
In drivers/regulator/core.c (ffffffff817457d7)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff8178b1ee)
Location: include/linux/trace_events.h:313
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
In drivers/iommu/intel/trace.c (ffffffff817b4bc4)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/iommu/intel/trace.c:perf_trace_dma_map_sg
  - drivers/iommu/intel/trace.c:perf_trace_dma_unmap
  - drivers/iommu/intel/trace.c:perf_trace_dma_map
```
```
In drivers/iommu/iommu-traces.c (ffffffff817bd67e)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff817eff54)
Location: include/linux/trace_events.h:313
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
In drivers/dma-buf/dma-fence.c (ffffffff81836feb)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8183caae)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff8183e1fe)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff8186203e)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff81887c81)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81894750)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81922bfe)
Location: include/linux/trace_events.h:313
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
In drivers/rtc/interface.c (ffffffff8193fc7e)
Location: include/linux/trace_events.h:313
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
In drivers/i2c/i2c-core-base.c (ffffffff81945958)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81949800)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff819585de)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff8195b074)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff819616b0)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff819a9892)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff819c6e62)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_start
```
```
In drivers/devfreq/devfreq.c (ffffffff819d072a)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_frequency
```
```
In drivers/ras/ras.c (ffffffff819d7077)
Location: include/linux/trace_events.h:313
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
In drivers/interconnect/core.c (ffffffff819dccaf)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - drivers/interconnect/core.c:perf_trace_icc_set_bw_end
  - drivers/interconnect/core.c:perf_trace_icc_set_bw
```
```
In net/core/net-traces.c (ffffffff81a48fa2)
Location: include/linux/trace_events.h:313
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
In net/core/devlink.c (ffffffff81a57e31)
Location: include/linux/trace_events.h:313
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
In net/bpf/test_run.c (ffffffff81a875ce)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (ffffffff81b4e5cb)
Location: include/linux/trace_events.h:313
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
In init/main.c (ffffffff810032f3)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004f9e)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff8102dc93)
Location: include/linux/trace_events.h:367
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
In arch/x86/hyperv/mmu.c (ffffffff81031c83)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_one
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_multi
```
```
In arch/x86/kernel/irq.c (ffffffff81037dcc)
Location: include/linux/trace_events.h:367
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
In arch/x86/kernel/nmi.c (ffffffff8103a437)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810430ce)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81051d7e)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81063e93)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff81086303)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff81087c48)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In kernel/fork.c (ffffffff8109fcf4)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff810a530c)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff810ab39e)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810b3b97)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810c3183)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_end
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_activate_work
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
```
```
In kernel/sched/core.c (ffffffff810d8e9e)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
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
In kernel/printk/printk.c (ffffffff811181a1)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff8112ad9b)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff8112be63)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_stall_warning
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff8113b5df)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/entry/common.c (ffffffff8113c4c4)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - kernel/entry/common.c:perf_trace_sys_exit
  - kernel/entry/common.c:perf_trace_sys_enter
```
```
In kernel/time/timer.c (ffffffff81141033)
Location: include/linux/trace_events.h:367
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
In kernel/time/alarmtimer.c (ffffffff8114b603)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff81160fee)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff8116d0d2)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d6550)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/bpf_trace.c (ffffffff811e8f72)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_trace_bpf_trace_printk
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ec682)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/error_report-traces.c (ffffffff811ed803)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - kernel/trace/error_report-traces.c:perf_trace_error_report_template
```
```
In kernel/trace/power-traces.c (ffffffff811ef5ed)
Location: include/linux/trace_events.h:367
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
In kernel/trace/rpm-traces.c (ffffffff811f0aff)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4008)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/core.c (ffffffff811f8423)
Location: include/linux/trace_events.h:367
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
In kernel/events/core.c (ffffffff81244e80)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - kernel/events/core.c:perf_trace_run_bpf_submit
```
```
In kernel/rseq.c (ffffffff8125a47c)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff8125c792)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff81264721)
Location: include/linux/trace_events.h:367
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
In mm/swap.c (ffffffff8126c78e)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81272577)
Location: include/linux/trace_events.h:367
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
In mm/percpu.c (ffffffff8128862e)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff8128d3c8)
Location: include/linux/trace_events.h:367
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
In mm/compaction.c (ffffffff8128f4e7)
Location: include/linux/trace_events.h:367
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
In mm/mmap_lock.c (ffffffff8129bdce)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - mm/mmap_lock.c:perf_trace_mmap_lock_released
  - mm/mmap_lock.c:perf_trace_mmap_lock_acquire_returned
  - mm/mmap_lock.c:perf_trace_mmap_lock_start_locking
```
```
In mm/mmap.c (ffffffff812a8d03)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - mm/mmap.c:perf_trace_vm_unmapped_area
```
```
In mm/migrate.c (ffffffff812f2fb3)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages_start
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff8130168c)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff81315808)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In fs/fs-writeback.c (ffffffff8135b8be)
Location: include/linux/trace_events.h:367
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
In fs/io_uring.c (ffffffff8138f988)
Location: include/linux/trace_events.h:367
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
In fs/dax.c (ffffffff813a4718)
Location: include/linux/trace_events.h:367
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
In fs/locks.c (ffffffff813b1e97)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/iomap/trace.c (ffffffff813c1935)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - fs/iomap/trace.c:perf_trace_iomap_apply
  - fs/iomap/trace.c:perf_trace_iomap_class
  - fs/iomap/trace.c:perf_trace_iomap_range_class
  - fs/iomap/trace.c:perf_trace_iomap_readpage_class
```
```
In fs/ext4/super.c (ffffffff8143f83c)
Location: include/linux/trace_events.h:367
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
In fs/jbd2/journal.c (ffffffff814669b3)
Location: include/linux/trace_events.h:367
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
In security/selinux/avc.c (ffffffff814d1591)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - security/selinux/avc.c:perf_trace_selinux_audited
```
```
In block/blk-core.c (ffffffff81566ea9)
Location: include/linux/trace_events.h:367
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
In block/blk-iocost.c (ffffffff8159566c)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_iocg_forgive_debt
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_state
```
```
In block/blk-wbt.c (ffffffff8159d17c)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff815ef3a7)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff81617217)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/pwm/core.c (ffffffff816244e3)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - drivers/pwm/core.c:perf_trace_pwm
```
```
In drivers/clk/clk.c (ffffffff816fc8aa)
Location: include/linux/trace_events.h:367
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
In drivers/regulator/core.c (ffffffff817291e7)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff8176e5be)
Location: include/linux/trace_events.h:367
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
In drivers/iommu/intel/trace.c (ffffffff817978c7)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - drivers/iommu/intel/trace.c:perf_trace_qi_submit
```
```
In drivers/iommu/iommu-traces.c (ffffffff817a08be)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff817d4994)
Location: include/linux/trace_events.h:367
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
In drivers/dma-buf/dma-fence.c (ffffffff8181a1ab)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8181fc5b)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff8182139e)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff81844e0e)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff8186a4e0)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81877050)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff8190630e)
Location: include/linux/trace_events.h:367
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
In drivers/rtc/interface.c (ffffffff8192341e)
Location: include/linux/trace_events.h:367
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
In drivers/i2c/i2c-core-base.c (ffffffff81929128)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8192d100)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff8193c77e)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff8193dfbf)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81944b00)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff8198e552)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff819abdb2)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_start
```
```
In drivers/devfreq/devfreq.c (ffffffff819b599a)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_frequency
```
```
In drivers/ras/ras.c (ffffffff819bd1e7)
Location: include/linux/trace_events.h:367
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
In drivers/interconnect/core.c (ffffffff819c2f01)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - drivers/interconnect/core.c:perf_trace_icc_set_bw_end
  - drivers/interconnect/core.c:perf_trace_icc_set_bw
```
```
In net/core/net-traces.c (ffffffff81a2def2)
Location: include/linux/trace_events.h:367
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
In net/core/devlink.c (ffffffff81a3ab21)
Location: include/linux/trace_events.h:367
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
In net/netlink/af_netlink.c (ffffffff81a691b2)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:perf_trace_netlink_extack
```
```
In net/bpf/test_run.c (ffffffff81a7069e)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (ffffffff81b3c42b)
Location: include/linux/trace_events.h:367
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/mptcp/protocol.c (ffffffff81ba9f93)
Location: include/linux/trace_events.h:367
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
In init/main.c (ffffffff81003333)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810055ae)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff81032543)
Location: include/linux/trace_events.h:416
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
In arch/x86/hyperv/mmu.c (ffffffff81036e03)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_one
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_multi
```
```
In arch/x86/kernel/irq.c (ffffffff8103d07c)
Location: include/linux/trace_events.h:416
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
In arch/x86/kernel/nmi.c (ffffffff8103fde7)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8104943e)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105a20e)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106de83)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff81095513)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff81096fc8)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In kernel/fork.c (ffffffff810b1144)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff810b6b2c)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff810bcebe)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810c5da7)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810d5cc3)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_end
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_activate_work
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
```
```
In kernel/sched/core.c (ffffffff810ec7de)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
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
In kernel/printk/printk.c (ffffffff811384a1)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff8114b848)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff8114c9f3)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_stall_warning
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff8115e71f)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/entry/common.c (ffffffff8115f5e4)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - kernel/entry/common.c:perf_trace_sys_exit
  - kernel/entry/common.c:perf_trace_sys_enter
```
```
In kernel/time/timer.c (ffffffff811644f3)
Location: include/linux/trace_events.h:416
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
In kernel/time/alarmtimer.c (ffffffff8116f2e3)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff811861be)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff81192db2)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_syscalls.c (ffffffff812033e0)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/bpf_trace.c (ffffffff81219d12)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_trace_bpf_trace_printk
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121d6c2)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/error_report-traces.c (ffffffff8121e873)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - kernel/trace/error_report-traces.c:perf_trace_error_report_template
```
```
In kernel/trace/power-traces.c (ffffffff8122067d)
Location: include/linux/trace_events.h:416
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
In kernel/trace/rpm-traces.c (ffffffff81221b9f)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff812254e8)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/core.c (ffffffff81229a03)
Location: include/linux/trace_events.h:416
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
In kernel/events/core.c (ffffffff8127fe30)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - kernel/events/core.c:perf_trace_run_bpf_submit
```
```
In kernel/rseq.c (ffffffff8129626c)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff81298652)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff812a0f41)
Location: include/linux/trace_events.h:416
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
In mm/swap.c (ffffffff812a94ae)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff812af947)
Location: include/linux/trace_events.h:416
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
In mm/percpu.c (ffffffff812c7d6e)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff812cd208)
Location: include/linux/trace_events.h:416
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
In mm/compaction.c (ffffffff812cf397)
Location: include/linux/trace_events.h:416
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
In mm/mmap_lock.c (ffffffff812dc8ce)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - mm/mmap_lock.c:perf_trace_mmap_lock_released
  - mm/mmap_lock.c:perf_trace_mmap_lock_acquire_returned
  - mm/mmap_lock.c:perf_trace_mmap_lock_start_locking
```
```
In mm/mmap.c (ffffffff812ea373)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - mm/mmap.c:perf_trace_vm_unmapped_area
```
```
In mm/migrate.c (ffffffff8133d423)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages_start
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff8134b38c)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff813618b8)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In fs/fs-writeback.c (ffffffff813a9d5e)
Location: include/linux/trace_events.h:416
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
In fs/io_uring.c (ffffffff813dd24c)
Location: include/linux/trace_events.h:416
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
In fs/dax.c (ffffffff813f4038)
Location: include/linux/trace_events.h:416
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
In fs/locks.c (ffffffff81401b87)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/iomap/trace.c (ffffffff81411b38)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - fs/iomap/trace.c:perf_trace_iomap_iter
  - fs/iomap/trace.c:perf_trace_iomap_class
  - fs/iomap/trace.c:perf_trace_iomap_range_class
  - fs/iomap/trace.c:perf_trace_iomap_readpage_class
```
```
In fs/ext4/super.c (ffffffff814934cc)
Location: include/linux/trace_events.h:416
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
In fs/jbd2/journal.c (ffffffff814bc760)
Location: include/linux/trace_events.h:416
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
In security/selinux/avc.c (ffffffff8152a2e1)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - security/selinux/avc.c:perf_trace_selinux_audited
```
```
In block/blk-core.c (ffffffff815cb429)
Location: include/linux/trace_events.h:416
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
In block/blk-iocost.c (ffffffff815fcbe1)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_iocg_forgive_debt
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_state
```
```
In block/blk-wbt.c (ffffffff8160582c)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff8165c4b7)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff81686497)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/pwm/core.c (ffffffff81693fc3)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - drivers/pwm/core.c:perf_trace_pwm
```
```
In drivers/clk/clk.c (ffffffff81776b2a)
Location: include/linux/trace_events.h:416
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
In drivers/regulator/core.c (ffffffff817a8507)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff817f3d8e)
Location: include/linux/trace_events.h:416
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
In drivers/iommu/intel/trace.c (ffffffff81820099)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - drivers/iommu/intel/trace.c:perf_trace_prq_report
  - drivers/iommu/intel/trace.c:perf_trace_qi_submit
```
```
In drivers/iommu/iommu-traces.c (ffffffff818298be)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff8185fb64)
Location: include/linux/trace_events.h:416
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
In drivers/base/trace.c (ffffffff8186be08)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - drivers/base/trace.c:perf_trace_devres
```
```
In drivers/dma-buf/dma-fence.c (ffffffff818a465b)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff818aa31b)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff818abcee)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff818d188e)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff818fa850)
Location: include/linux/trace_events.h:416
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
In drivers/net/phy/mdio_bus.c (ffffffff81907d60)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff819a6b3e)
Location: include/linux/trace_events.h:416
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
In drivers/rtc/interface.c (ffffffff819c63ce)
Location: include/linux/trace_events.h:416
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
In drivers/i2c/i2c-core-base.c (ffffffff819cc278)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff819d0310)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff819e101e)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff819e287f)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff819e9530)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff81a39be2)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff81a59d78)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_sensorhub_filter
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_sensorhub_data
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_sensorhub_timestamp
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_start
```
```
In drivers/devfreq/devfreq.c (ffffffff81a644fa)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_frequency
```
```
In drivers/ras/ras.c (ffffffff81a6c777)
Location: include/linux/trace_events.h:416
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
In drivers/interconnect/core.c (ffffffff81a727a1)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - drivers/interconnect/core.c:perf_trace_icc_set_bw_end
  - drivers/interconnect/core.c:perf_trace_icc_set_bw
```
```
In net/core/net-traces.c (ffffffff81ae34d2)
Location: include/linux/trace_events.h:416
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
In net/core/devlink.c (ffffffff81af0e81)
Location: include/linux/trace_events.h:416
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
In net/netlink/af_netlink.c (ffffffff81b22762)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:perf_trace_netlink_extack
```
```
In net/bpf/test_run.c (ffffffff81b29dee)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (ffffffff81c02d1b)
Location: include/linux/trace_events.h:416
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/mptcp/protocol.c (ffffffff81c77313)
Location: include/linux/trace_events.h:416
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
In init/main.c (ffffffff81000fa9)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004714)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff81038029)
Location: include/linux/trace_events.h:423
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
In arch/x86/hyperv/mmu.c (ffffffff8103ced9)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_one
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_multi
```
```
In arch/x86/kernel/irq.c (ffffffff8104448b)
Location: include/linux/trace_events.h:423
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
In arch/x86/kernel/nmi.c (ffffffff810475dd)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810525e4)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810669d4)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107b4f9)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/fault.c (ffffffff810a9ace)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In kernel/fork.c (ffffffff810c73bb)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff810cd0db)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff810d3da4)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810dd3be)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810ef269)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_end
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_activate_work
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
```
```
In kernel/sched/core.c (ffffffff81107954)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
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
In kernel/locking/mutex.c (ffffffff8114d639)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - kernel/locking/mutex.c:perf_trace_contention_end
  - kernel/locking/mutex.c:perf_trace_contention_begin
```
```
In kernel/printk/printk.c (ffffffff8115ad69)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff811711ce)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff81172569)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_stall_warning
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff8118830f)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/entry/common.c (ffffffff81189a2a)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - kernel/entry/common.c:perf_trace_sys_exit
  - kernel/entry/common.c:perf_trace_sys_enter
```
```
In kernel/module/main.c (ffffffff8118b9ae)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - kernel/module/main.c:perf_trace_module_request
  - kernel/module/main.c:perf_trace_module_refcnt
  - kernel/module/main.c:perf_trace_module_free
  - kernel/module/main.c:perf_trace_module_load
```
```
In kernel/time/timer.c (ffffffff81197779)
Location: include/linux/trace_events.h:423
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
In kernel/time/alarmtimer.c (ffffffff811a36c9)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/cgroup/cgroup.c (ffffffff811c24db)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_syscalls.c (ffffffff8123e213)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/bpf_trace.c (ffffffff8125608c)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_trace_bpf_trace_printk
```
```
In kernel/trace/trace_kprobe.c (ffffffff8125c468)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/error_report-traces.c (ffffffff8125df09)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - kernel/trace/error_report-traces.c:perf_trace_error_report_template
```
```
In kernel/trace/power-traces.c (ffffffff8125fd6d)
Location: include/linux/trace_events.h:423
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
In kernel/trace/rpm-traces.c (ffffffff812615b0)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff812656ee)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/core.c (ffffffff8126abf9)
Location: include/linux/trace_events.h:423
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
In kernel/events/core.c (ffffffff812d4ed5)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - kernel/events/core.c:perf_trace_run_bpf_submit
```
```
In kernel/rseq.c (ffffffff812ec0ab)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff812eeb28)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff812f8710)
Location: include/linux/trace_events.h:423
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
In mm/swap.c (ffffffff813028a4)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8130b627)
Location: include/linux/trace_events.h:423
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
In mm/percpu.c (ffffffff81325284)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff8132ac57)
Location: include/linux/trace_events.h:423
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
In mm/compaction.c (ffffffff8132d60d)
Location: include/linux/trace_events.h:423
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
In mm/mmap_lock.c (ffffffff8133c003)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - mm/mmap_lock.c:perf_trace_mmap_lock_acquire_returned
  - mm/mmap_lock.c:perf_trace_mmap_lock
```
```
In mm/mmap.c (ffffffff8134cf39)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - mm/mmap.c:perf_trace_vm_unmapped_area
```
```
In mm/rmap.c (ffffffff8135a89d)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - mm/rmap.c:perf_trace_migration_pte
  - mm/rmap.c:perf_trace_mm_migrate_pages_start
  - mm/rmap.c:perf_trace_mm_migrate_pages
  - mm/rmap.c:perf_trace_tlb_flush
```
```
In mm/huge_memory.c (ffffffff813b89d9)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - mm/huge_memory.c:perf_trace_migration_pmd
  - mm/huge_memory.c:perf_trace_hugepage_update
  - mm/huge_memory.c:perf_trace_hugepage_set_pmd
```
```
In mm/khugepaged.c (ffffffff813c26fb)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff813dd84e)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In fs/fs-writeback.c (ffffffff8142f1f4)
Location: include/linux/trace_events.h:423
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
In fs/dax.c (ffffffff814668be)
Location: include/linux/trace_events.h:423
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
In fs/locks.c (ffffffff81475f7e)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/iomap/trace.c (ffffffff8148724e)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - fs/iomap/trace.c:perf_trace_iomap_iter
  - fs/iomap/trace.c:perf_trace_iomap_class
  - fs/iomap/trace.c:perf_trace_iomap_range_class
  - fs/iomap/trace.c:perf_trace_iomap_readpage_class
```
```
In fs/ext4/super.c (ffffffff8151869e)
Location: include/linux/trace_events.h:423
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
In fs/jbd2/journal.c (ffffffff81546a9f)
Location: include/linux/trace_events.h:423
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
In security/selinux/avc.c (ffffffff815bff26)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - security/selinux/avc.c:perf_trace_selinux_audited
```
```
In block/blk-core.c (ffffffff816772e8)
Location: include/linux/trace_events.h:423
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
In block/blk-iocost.c (ffffffff816ad1c8)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_iocg_forgive_debt
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_state
```
```
In block/blk-wbt.c (ffffffff816b90cb)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In io_uring/io_uring.c (ffffffff816c5a8f)
Location: include/linux/trace_events.h:423
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
In arch/x86/lib/msr.c (ffffffff8177557d)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff817a2ead)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/pwm/core.c (ffffffff817b4c9a)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - drivers/pwm/core.c:perf_trace_pwm
```
```
In drivers/clk/clk.c (ffffffff818ab8df)
Location: include/linux/trace_events.h:423
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
In drivers/regulator/core.c (ffffffff818e1e0f)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/iommu/intel/trace.c (ffffffff8195fbaf)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - drivers/iommu/intel/trace.c:perf_trace_prq_report
  - drivers/iommu/intel/trace.c:perf_trace_qi_submit
```
```
In drivers/iommu/iommu-traces.c (ffffffff81969770)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff819a6ce9)
Location: include/linux/trace_events.h:423
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
In drivers/base/trace.c (ffffffff819b4aa9)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - drivers/base/trace.c:perf_trace_devres
```
```
In drivers/dma-buf/dma-fence.c (ffffffff819edfd9)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff819f43c3)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff819f6674)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff81a204c4)
Location: include/linux/trace_events.h:423
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
In drivers/spi/spi.c (ffffffff81a48b4c)
Location: include/linux/trace_events.h:423
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
In drivers/net/phy/mdio_bus.c (ffffffff81a5ae7f)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81b04944)
Location: include/linux/trace_events.h:423
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
In drivers/rtc/interface.c (ffffffff81b26cf4)
Location: include/linux/trace_events.h:423
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
In drivers/i2c/i2c-core-base.c (ffffffff81b2daee)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81b322df)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff81b44c92)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff81b47285)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81b4f15e)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/cpufreq/amd-pstate-trace.c (ffffffff81b9787b)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate-trace.c:perf_trace_amd_pstate_perf
```
```
In drivers/mmc/core/core.c (ffffffff81ba4f58)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff81bc9879)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_start
```
```
In drivers/devfreq/devfreq.c (ffffffff81bd1b2c)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_frequency
```
```
In drivers/ras/ras.c (ffffffff81bdd36d)
Location: include/linux/trace_events.h:423
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
In drivers/interconnect/core.c (ffffffff81be2b1c)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - drivers/interconnect/core.c:perf_trace_icc_set_bw_end
  - drivers/interconnect/core.c:perf_trace_icc_set_bw
```
```
In net/core/net-traces.c (ffffffff81c68178)
Location: include/linux/trace_events.h:423
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
In net/core/devlink.c (ffffffff81c745af)
Location: include/linux/trace_events.h:423
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
In net/netlink/af_netlink.c (ffffffff81ca9b2c)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:perf_trace_netlink_extack
```
```
In net/bpf/test_run.c (ffffffff81cb3054)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (ffffffff81d9cbba)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/mptcp/protocol.c (ffffffff81e1bf19)
Location: include/linux/trace_events.h:423
Inline: True
Inline callers:
  - net/mptcp/protocol.c:perf_trace_subflow_check_data_avail
  - net/mptcp/protocol.c:perf_trace_ack_update_msk
  - net/mptcp/protocol.c:perf_trace_mptcp_dump_mpext
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
```
```
In net/mctp/af_mctp.c (ffffffff81e36848)
Location: include/linux/trace_events.h:423
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
In init/main.c (ffffffff81001536)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810050d1)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff810400c6)
Location: include/linux/trace_events.h:425
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
In arch/x86/hyperv/mmu.c (ffffffff81045bb6)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_one
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_multi
```
```
In arch/x86/kernel/irq.c (ffffffff8104e19b)
Location: include/linux/trace_events.h:425
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
In arch/x86/kernel/nmi.c (ffffffff81051ffa)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81060651)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81075d11)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108c856)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/fault.c (ffffffff810c2f2b)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In kernel/fork.c (ffffffff810e49f8)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff810eb10b)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff810f2b71)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810fd7bb)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff81110946)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_end
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_activate_work
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
```
```
In kernel/sched/core.c (ffffffff8112dce1)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
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
In kernel/locking/mutex.c (ffffffff8117c746)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - kernel/locking/mutex.c:perf_trace_contention_end
  - kernel/locking/mutex.c:perf_trace_contention_begin
```
```
In kernel/printk/printk.c (ffffffff8118dc16)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff811a77bb)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff811a8ea6)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_stall_warning
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff811c420c)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/entry/common.c (ffffffff811c5ec7)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - kernel/entry/common.c:perf_trace_sys_exit
  - kernel/entry/common.c:perf_trace_sys_enter
```
```
In kernel/module/main.c (ffffffff811c807b)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - kernel/module/main.c:perf_trace_module_request
  - kernel/module/main.c:perf_trace_module_refcnt
  - kernel/module/main.c:perf_trace_module_free
  - kernel/module/main.c:perf_trace_module_load
```
```
In kernel/time/timer.c (ffffffff811d58f6)
Location: include/linux/trace_events.h:425
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
In kernel/time/alarmtimer.c (ffffffff811e2d56)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/cgroup/cgroup.c (ffffffff81204848)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_syscalls.c (ffffffff8128bbe0)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/bpf_trace.c (ffffffff812a56d9)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_trace_bpf_trace_printk
```
```
In kernel/trace/trace_kprobe.c (ffffffff812adfd8)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/error_report-traces.c (ffffffff812ae9e6)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - kernel/trace/error_report-traces.c:perf_trace_error_report_template
```
```
In kernel/trace/power-traces.c (ffffffff812afe5a)
Location: include/linux/trace_events.h:425
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
In kernel/trace/rpm-traces.c (ffffffff812b2c6d)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b7f12)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/trace/rv/rv.c (ffffffff812bbcdb)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - kernel/trace/rv/rv.c:perf_trace_error_da_monitor_id
  - kernel/trace/rv/rv.c:perf_trace_event_da_monitor_id
```
```
In kernel/bpf/core.c (ffffffff812bfc86)
Location: include/linux/trace_events.h:425
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
In kernel/events/core.c (ffffffff8133d6a5)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - kernel/events/core.c:perf_trace_run_bpf_submit
```
```
In kernel/rseq.c (ffffffff813562bb)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff81359245)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff81362160)
Location: include/linux/trace_events.h:425
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
In mm/swap.c (ffffffff8136cee1)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff813759e7)
Location: include/linux/trace_events.h:425
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
In mm/percpu.c (ffffffff81399dc1)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff8139ff88)
Location: include/linux/trace_events.h:425
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
In mm/compaction.c (ffffffff813a3c6a)
Location: include/linux/trace_events.h:425
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
In mm/mmap_lock.c (ffffffff813b3b20)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - mm/mmap_lock.c:perf_trace_mmap_lock_acquire_returned
  - mm/mmap_lock.c:perf_trace_mmap_lock
```
```
In mm/mmap.c (ffffffff813c5c11)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - mm/mmap.c:perf_trace_exit_mmap
  - mm/mmap.c:perf_trace_vma_store
  - mm/mmap.c:perf_trace_vma_mas_szero
  - mm/mmap.c:perf_trace_vm_unmapped_area
```
```
In mm/rmap.c (ffffffff813d53fa)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - mm/rmap.c:perf_trace_migration_pte
  - mm/rmap.c:perf_trace_mm_migrate_pages_start
  - mm/rmap.c:perf_trace_mm_migrate_pages
  - mm/rmap.c:perf_trace_tlb_flush
```
```
In mm/vmalloc.c (ffffffff813db6bb)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - mm/vmalloc.c:perf_trace_free_vmap_area_noflush
  - mm/vmalloc.c:perf_trace_purge_vmap_area_lazy
  - mm/vmalloc.c:perf_trace_alloc_vmap_area
```
```
In mm/huge_memory.c (ffffffff8143ab66)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - mm/huge_memory.c:perf_trace_migration_pmd
  - mm/huge_memory.c:perf_trace_hugepage_update
  - mm/huge_memory.c:perf_trace_hugepage_set_pmd
```
```
In mm/khugepaged.c (ffffffff814464d3)
Location: include/linux/trace_events.h:425
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
In mm/page_isolation.c (ffffffff8146448b)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In fs/fs-writeback.c (ffffffff814bcc31)
Location: include/linux/trace_events.h:425
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
In fs/dax.c (ffffffff814f6a7b)
Location: include/linux/trace_events.h:425
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
In fs/locks.c (ffffffff815084eb)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/iomap/trace.c (ffffffff8151ad0b)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - fs/iomap/trace.c:perf_trace_iomap_iter
  - fs/iomap/trace.c:perf_trace_iomap_class
  - fs/iomap/trace.c:perf_trace_iomap_range_class
  - fs/iomap/trace.c:perf_trace_iomap_readpage_class
```
```
In fs/ext4/super.c (ffffffff815b426b)
Location: include/linux/trace_events.h:425
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
In fs/jbd2/journal.c (ffffffff815e5e9f)
Location: include/linux/trace_events.h:425
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
In security/selinux/avc.c (ffffffff8166c433)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - security/selinux/avc.c:perf_trace_selinux_audited
```
```
In block/blk-core.c (ffffffff81733488)
Location: include/linux/trace_events.h:425
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
In block/blk-iocost.c (ffffffff8176bb52)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_iocg_forgive_debt
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_state
```
```
In block/blk-wbt.c (ffffffff8177945b)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In io_uring/io_uring.c (ffffffff81786e3a)
Location: include/linux/trace_events.h:425
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
In arch/x86/lib/msr.c (ffffffff818a61aa)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff818ba2da)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/pwm/core.c (ffffffff818cef5b)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - drivers/pwm/core.c:perf_trace_pwm
```
```
In drivers/clk/clk.c (ffffffff819f5056)
Location: include/linux/trace_events.h:425
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
In drivers/regulator/core.c (ffffffff81a370cc)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/iommu/intel/trace.c (ffffffff81ac788c)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - drivers/iommu/intel/trace.c:perf_trace_prq_report
  - drivers/iommu/intel/trace.c:perf_trace_qi_submit
```
```
In drivers/iommu/iommu-traces.c (ffffffff81ad373d)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff81b19b46)
Location: include/linux/trace_events.h:425
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
In drivers/base/trace.c (ffffffff81b29ac6)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - drivers/base/trace.c:perf_trace_devres
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81b6b3c6)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81b7177e)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff81b73d01)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/scsi/sd_zbc.c (ffffffff81b9565b)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:perf_trace_scsi_zone_wp_update
  - drivers/scsi/sd_zbc.c:perf_trace_scsi_prepare_zone_append
```
```
In drivers/ata/libata-core.c (ffffffff81ba1bf1)
Location: include/linux/trace_events.h:425
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
In drivers/spi/spi.c (ffffffff81bd0d09)
Location: include/linux/trace_events.h:425
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
In drivers/net/phy/mdio_bus.c (ffffffff81be57bf)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81c93ee1)
Location: include/linux/trace_events.h:425
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
In drivers/rtc/interface.c (ffffffff81cba591)
Location: include/linux/trace_events.h:425
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
In drivers/i2c/i2c-core-base.c (ffffffff81cc1c5b)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81cc6f7f)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff81cdbdd0)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff81cde972)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81ce6fce)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/watchdog/watchdog_core.c (ffffffff81ceb21b)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:perf_trace_watchdog_set_timeout
  - drivers/watchdog/watchdog_core.c:perf_trace_watchdog_template
```
```
In drivers/cpufreq/amd-pstate-trace.c (ffffffff81d3876b)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate-trace.c:perf_trace_amd_pstate_perf
```
```
In drivers/mmc/core/core.c (ffffffff81d471c5)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff81d72cb6)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_start
```
```
In drivers/devfreq/devfreq.c (ffffffff81d7d6b9)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_frequency
```
```
In drivers/ras/ras.c (ffffffff81d8862a)
Location: include/linux/trace_events.h:425
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
In drivers/interconnect/core.c (ffffffff81d8e749)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - drivers/interconnect/core.c:perf_trace_icc_set_bw_end
  - drivers/interconnect/core.c:perf_trace_icc_set_bw
```
```
In net/core/net-traces.c (ffffffff81e1f435)
Location: include/linux/trace_events.h:425
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
In net/core/devlink.c (ffffffff81e2d1cb)
Location: include/linux/trace_events.h:425
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
In net/netlink/af_netlink.c (ffffffff81e66b09)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:perf_trace_netlink_extack
```
```
In net/bpf/test_run.c (ffffffff81e71111)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (ffffffff81f6b92a)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/mptcp/protocol.c (ffffffff81ff3576)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - net/mptcp/protocol.c:perf_trace_subflow_check_data_avail
  - net/mptcp/protocol.c:perf_trace_ack_update_msk
  - net/mptcp/protocol.c:perf_trace_mptcp_dump_mpext
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
```
```
In net/mctp/af_mctp.c (ffffffff8200f895)
Location: include/linux/trace_events.h:425
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:perf_trace_mctp_key_release
  - net/mctp/af_mctp.c:perf_trace_mctp_key_acquire
```
```
In lib/maple_tree.c (ffffffff82025b5b)
Location: include/linux/trace_events.h:425
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
In init/main.c (ffffffff810012f6)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810048f1)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff81040206)
Location: include/linux/trace_events.h:439
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
In arch/x86/hyperv/mmu.c (ffffffff81045d66)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_one
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_multi
```
```
In arch/x86/kernel/irq.c (ffffffff8104eb4b)
Location: include/linux/trace_events.h:439
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
In arch/x86/kernel/nmi.c (ffffffff81052d5a)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81061f01)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81077e91)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108f6e6)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/fault.c (ffffffff810c662b)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In kernel/fork.c (ffffffff810f00a8)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff810f6d4b)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff810fed36)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_tasklet
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff8110982b)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff8111cb46)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_end
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_activate_work
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
```
```
In kernel/notifier.c (ffffffff81132181)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/notifier.c:perf_trace_notifier_info
```
```
In kernel/sched/core.c (ffffffff8113b341)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
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
In kernel/locking/mutex.c (ffffffff8118d426)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/locking/mutex.c:perf_trace_contention_end
  - kernel/locking/mutex.c:perf_trace_contention_begin
```
```
In kernel/printk/printk.c (ffffffff8119f3c6)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff811b937b)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff811babf6)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_stall_warning
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff811d73ac)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/entry/common.c (ffffffff811d8ac7)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/entry/common.c:perf_trace_sys_exit
  - kernel/entry/common.c:perf_trace_sys_enter
```
```
In kernel/module/main.c (ffffffff811db0db)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/module/main.c:perf_trace_module_request
  - kernel/module/main.c:perf_trace_module_refcnt
  - kernel/module/main.c:perf_trace_module_free
  - kernel/module/main.c:perf_trace_module_load
```
```
In kernel/time/timer.c (ffffffff811e9ce6)
Location: include/linux/trace_events.h:439
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
In kernel/time/alarmtimer.c (ffffffff811f7386)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/smp.c (ffffffff8120d716)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/smp.c:perf_trace_csd_function
  - kernel/smp.c:perf_trace_csd_queue_cpu
```
```
In kernel/cgroup/cgroup.c (ffffffff81219e38)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_osnoise.c (ffffffff812950cb)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:perf_trace_sample_threshold
  - kernel/trace/trace_osnoise.c:perf_trace_nmi_noise
  - kernel/trace/trace_osnoise.c:perf_trace_irq_noise
  - kernel/trace/trace_osnoise.c:perf_trace_softirq_noise
  - kernel/trace/trace_osnoise.c:perf_trace_thread_noise
```
```
In kernel/trace/trace_syscalls.c (ffffffff812a8af0)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/bpf_trace.c (ffffffff812c7b89)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_trace_bpf_trace_printk
```
```
In kernel/trace/trace_kprobe.c (ffffffff812cfc17)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/error_report-traces.c (ffffffff812d0f26)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/trace/error_report-traces.c:perf_trace_error_report_template
```
```
In kernel/trace/power-traces.c (ffffffff812d255a)
Location: include/linux/trace_events.h:439
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
In kernel/trace/rpm-traces.c (ffffffff812d54fd)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff812db541)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/trace/rv/rv.c (ffffffff812e28cb)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/trace/rv/rv.c:perf_trace_error_da_monitor_id
  - kernel/trace/rv/rv.c:perf_trace_event_da_monitor_id
```
```
In kernel/bpf/core.c (ffffffff812e6a36)
Location: include/linux/trace_events.h:439
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
In kernel/events/core.c (ffffffff8136e875)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/events/core.c:perf_trace_run_bpf_submit
```
```
In kernel/rseq.c (ffffffff813879eb)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff8138ab95)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff813945a0)
Location: include/linux/trace_events.h:439
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
In mm/swap.c (ffffffff8139f161)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff813a72c7)
Location: include/linux/trace_events.h:439
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
In mm/percpu.c (ffffffff813cce51)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff813d3248)
Location: include/linux/trace_events.h:439
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
In mm/compaction.c (ffffffff813d745a)
Location: include/linux/trace_events.h:439
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
In mm/mmap_lock.c (ffffffff813e89c0)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - mm/mmap_lock.c:perf_trace_mmap_lock_acquire_returned
  - mm/mmap_lock.c:perf_trace_mmap_lock
```
```
In mm/mmap.c (ffffffff813fa061)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - mm/mmap.c:perf_trace_exit_mmap
  - mm/mmap.c:perf_trace_vma_store
  - mm/mmap.c:perf_trace_vma_mas_szero
  - mm/mmap.c:perf_trace_vm_unmapped_area
```
```
In mm/rmap.c (ffffffff8140a2ba)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - mm/rmap.c:perf_trace_migration_pte
  - mm/rmap.c:perf_trace_mm_migrate_pages_start
  - mm/rmap.c:perf_trace_mm_migrate_pages
  - mm/rmap.c:perf_trace_tlb_flush
```
```
In mm/vmalloc.c (ffffffff8140fe4b)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - mm/vmalloc.c:perf_trace_free_vmap_area_noflush
  - mm/vmalloc.c:perf_trace_purge_vmap_area_lazy
  - mm/vmalloc.c:perf_trace_alloc_vmap_area
```
```
In mm/ksm.c (ffffffff8145129b)
Location: include/linux/trace_events.h:439
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
In mm/huge_memory.c (ffffffff814704b6)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - mm/huge_memory.c:perf_trace_migration_pmd
  - mm/huge_memory.c:perf_trace_hugepage_update
  - mm/huge_memory.c:perf_trace_hugepage_set_pmd
```
```
In mm/khugepaged.c (ffffffff8147b923)
Location: include/linux/trace_events.h:439
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
In mm/page_isolation.c (ffffffff81499f8b)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In fs/fs-writeback.c (ffffffff814f1d51)
Location: include/linux/trace_events.h:439
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
In fs/dax.c (ffffffff8152d8cb)
Location: include/linux/trace_events.h:439
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
In fs/locks.c (ffffffff8153faab)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/iomap/trace.c (ffffffff81552a6b)
Location: include/linux/trace_events.h:439
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
In fs/ext4/super.c (ffffffff815eafcb)
Location: include/linux/trace_events.h:439
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
In fs/jbd2/journal.c (ffffffff8161d7df)
Location: include/linux/trace_events.h:439
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
In security/selinux/avc.c (ffffffff816a4d74)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - security/selinux/avc.c:perf_trace_selinux_audited
```
```
In block/blk-core.c (ffffffff8176f8a8)
Location: include/linux/trace_events.h:439
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
In block/blk-iocost.c (ffffffff817ab11c)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_iocg_forgive_debt
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_state
```
```
In block/blk-wbt.c (ffffffff817b908b)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In io_uring/io_uring.c (ffffffff817c737a)
Location: include/linux/trace_events.h:439
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
In arch/x86/lib/msr.c (ffffffff818e8fda)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff818fd3da)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/pwm/core.c (ffffffff81911f9b)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/pwm/core.c:perf_trace_pwm
```
```
In drivers/clk/clk.c (ffffffff81a3d7de)
Location: include/linux/trace_events.h:439
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
In drivers/regulator/core.c (ffffffff81a80e0c)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/iommu/intel/trace.c (ffffffff81b1460d)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/iommu/intel/trace.c:perf_trace_prq_report
  - drivers/iommu/intel/trace.c:perf_trace_qi_submit
```
```
In drivers/iommu/iommu-traces.c (ffffffff81b21f05)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff81b68776)
Location: include/linux/trace_events.h:439
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
In drivers/base/trace.c (ffffffff81b79c96)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/base/trace.c:perf_trace_devres
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81bbe82e)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81bc4ffc)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff81bc74b1)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/scsi/sd_zbc.c (ffffffff81bebbfb)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:perf_trace_scsi_zone_wp_update
  - drivers/scsi/sd_zbc.c:perf_trace_scsi_prepare_zone_append
```
```
In drivers/ata/libata-core.c (ffffffff81bf8401)
Location: include/linux/trace_events.h:439
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
In drivers/spi/spi.c (ffffffff81c28979)
Location: include/linux/trace_events.h:439
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
In drivers/net/phy/mdio_bus.c (ffffffff81c3d1df)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81cfa621)
Location: include/linux/trace_events.h:439
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
In drivers/rtc/interface.c (ffffffff81d21d41)
Location: include/linux/trace_events.h:439
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
In drivers/i2c/i2c-core-base.c (ffffffff81d2966b)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81d2ecaf)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff81d4433a)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff81d46882)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81d4f6ce)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/watchdog/watchdog_core.c (ffffffff81d53e6b)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:perf_trace_watchdog_set_timeout
  - drivers/watchdog/watchdog_core.c:perf_trace_watchdog_template
```
```
In drivers/cpufreq/amd-pstate-trace.c (ffffffff81da31eb)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate-trace.c:perf_trace_amd_pstate_perf
```
```
In drivers/mmc/core/core.c (ffffffff81db1a55)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff81de0a96)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_start
```
```
In drivers/devfreq/devfreq.c (ffffffff81deba39)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_frequency
```
```
In drivers/ras/ras.c (ffffffff81df6c3a)
Location: include/linux/trace_events.h:439
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
In drivers/interconnect/core.c (ffffffff81dfd051)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/interconnect/core.c:perf_trace_icc_set_bw_end
  - drivers/interconnect/core.c:perf_trace_icc_set_bw
```
```
In net/core/net-traces.c (ffffffff81e91b21)
Location: include/linux/trace_events.h:439
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
In net/netlink/af_netlink.c (ffffffff81ec28c9)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:perf_trace_netlink_extack
```
```
In net/bpf/test_run.c (ffffffff81ecd251)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (ffffffff81fcba7a)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/devlink/leftover.c (ffffffff82031724)
Location: include/linux/trace_events.h:439
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
In net/mptcp/protocol.c (ffffffff8206f8e6)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - net/mptcp/protocol.c:perf_trace_subflow_check_data_avail
  - net/mptcp/protocol.c:perf_trace_ack_update_msk
  - net/mptcp/protocol.c:perf_trace_mptcp_dump_mpext
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
```
```
In net/mctp/af_mctp.c (ffffffff8208c4b5)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:perf_trace_mctp_key_release
  - net/mctp/af_mctp.c:perf_trace_mctp_key_acquire
```
```
In net/handshake/trace.c (ffffffff82094ebb)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - net/handshake/trace.c:perf_trace_handshake_complete
  - net/handshake/trace.c:perf_trace_handshake_error_class
  - net/handshake/trace.c:perf_trace_handshake_fd_class
  - net/handshake/trace.c:perf_trace_handshake_event_class
```
```
In lib/maple_tree.c (ffffffff820a5cab)
Location: include/linux/trace_events.h:439
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
In init/main.c (ffffffff81001306)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81007201)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff810466d6)
Location: include/linux/trace_events.h:439
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
In arch/x86/hyperv/mmu.c (ffffffff8104c436)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_one
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_multi
```
```
In arch/x86/kernel/irq.c (ffffffff81055d7b)
Location: include/linux/trace_events.h:439
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
In arch/x86/kernel/nmi.c (ffffffff81059f7a)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81069141)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107f341)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81096a76)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/fault.c (ffffffff810ceaab)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In kernel/fork.c (ffffffff810f94b8)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff811000fb)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff811083e6)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_tasklet
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff811131cb)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff811265c6)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_end
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_activate_work
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
```
```
In kernel/notifier.c (ffffffff8113d091)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/notifier.c:perf_trace_notifier_info
```
```
In kernel/sched/core.c (ffffffff81146301)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
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
In kernel/locking/mutex.c (ffffffff8119bdd6)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/locking/mutex.c:perf_trace_contention_end
  - kernel/locking/mutex.c:perf_trace_contention_begin
```
```
In kernel/printk/printk.c (ffffffff811ae5a6)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff811c923b)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff811cabb6)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_stall_warning
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff811ec35c)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/entry/common.c (ffffffff811ee5d7)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/entry/common.c:perf_trace_sys_exit
  - kernel/entry/common.c:perf_trace_sys_enter
```
```
In kernel/module/main.c (ffffffff811f0d8b)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/module/main.c:perf_trace_module_request
  - kernel/module/main.c:perf_trace_module_refcnt
  - kernel/module/main.c:perf_trace_module_free
  - kernel/module/main.c:perf_trace_module_load
```
```
In kernel/time/timer.c (ffffffff811ffb76)
Location: include/linux/trace_events.h:439
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
In kernel/time/alarmtimer.c (ffffffff8120d526)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/smp.c (ffffffff81224ea6)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/smp.c:perf_trace_csd_function
  - kernel/smp.c:perf_trace_csd_queue_cpu
```
```
In kernel/cgroup/cgroup.c (ffffffff81231968)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b072b)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:perf_trace_sample_threshold
  - kernel/trace/trace_osnoise.c:perf_trace_nmi_noise
  - kernel/trace/trace_osnoise.c:perf_trace_irq_noise
  - kernel/trace/trace_osnoise.c:perf_trace_softirq_noise
  - kernel/trace/trace_osnoise.c:perf_trace_thread_noise
```
```
In kernel/trace/trace_syscalls.c (ffffffff812c4800)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/bpf_trace.c (ffffffff812e4539)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_trace_bpf_trace_printk
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ed617)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/error_report-traces.c (ffffffff812eea26)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/trace/error_report-traces.c:perf_trace_error_report_template
```
```
In kernel/trace/power-traces.c (ffffffff812f005a)
Location: include/linux/trace_events.h:439
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
In kernel/trace/rpm-traces.c (ffffffff812f300d)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff812f9614)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/trace/rv/rv.c (ffffffff8130091b)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/trace/rv/rv.c:perf_trace_error_da_monitor_id
  - kernel/trace/rv/rv.c:perf_trace_event_da_monitor_id
```
```
In kernel/bpf/core.c (ffffffff81305c99)
Location: include/linux/trace_events.h:439
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
In kernel/events/core.c (ffffffff81397965)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/events/core.c:perf_trace_run_bpf_submit
```
```
In kernel/context_tracking.c (ffffffff813b0861)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/context_tracking.c:perf_trace_context_tracking_user
```
```
In kernel/rseq.c (ffffffff813b144b)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff813b46b5)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff813be360)
Location: include/linux/trace_events.h:439
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
In mm/swap.c (ffffffff813c8dc1)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff813d0e27)
Location: include/linux/trace_events.h:439
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
In mm/percpu.c (ffffffff813f77c1)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff813fdc48)
Location: include/linux/trace_events.h:439
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
In mm/compaction.c (ffffffff8140113a)
Location: include/linux/trace_events.h:439
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
In mm/mmap_lock.c (ffffffff81413630)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - mm/mmap_lock.c:perf_trace_mmap_lock_acquire_returned
  - mm/mmap_lock.c:perf_trace_mmap_lock
```
```
In mm/mmap.c (ffffffff81425e21)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - mm/mmap.c:perf_trace_exit_mmap
  - mm/mmap.c:perf_trace_vma_store
  - mm/mmap.c:perf_trace_vma_mas_szero
  - mm/mmap.c:perf_trace_vm_unmapped_area
```
```
In mm/rmap.c (ffffffff81436afa)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - mm/rmap.c:perf_trace_migration_pte
  - mm/rmap.c:perf_trace_mm_migrate_pages_start
  - mm/rmap.c:perf_trace_mm_migrate_pages
  - mm/rmap.c:perf_trace_tlb_flush
```
```
In mm/vmalloc.c (ffffffff8143c7ab)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - mm/vmalloc.c:perf_trace_free_vmap_area_noflush
  - mm/vmalloc.c:perf_trace_purge_vmap_area_lazy
  - mm/vmalloc.c:perf_trace_alloc_vmap_area
```
```
In mm/ksm.c (ffffffff8148b14a)
Location: include/linux/trace_events.h:439
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
In mm/huge_memory.c (ffffffff8149f876)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - mm/huge_memory.c:perf_trace_migration_pmd
  - mm/huge_memory.c:perf_trace_hugepage_update
  - mm/huge_memory.c:perf_trace_hugepage_set
```
```
In mm/khugepaged.c (ffffffff814aaba3)
Location: include/linux/trace_events.h:439
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
In mm/page_isolation.c (ffffffff814c970b)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In fs/fs-writeback.c (ffffffff81526461)
Location: include/linux/trace_events.h:439
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
In fs/dax.c (ffffffff815627ab)
Location: include/linux/trace_events.h:439
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
In fs/locks.c (ffffffff81574f8b)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/iomap/trace.c (ffffffff81588a2b)
Location: include/linux/trace_events.h:439
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
In fs/ext4/super.c (ffffffff816239bb)
Location: include/linux/trace_events.h:439
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
In fs/jbd2/journal.c (ffffffff816566ef)
Location: include/linux/trace_events.h:439
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
In security/selinux/avc.c (ffffffff816e17d4)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - security/selinux/avc.c:perf_trace_selinux_audited
```
```
In block/blk-core.c (ffffffff817b1b18)
Location: include/linux/trace_events.h:439
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
In block/blk-iocost.c (ffffffff817eeecc)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_iocg_forgive_debt
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_state
```
```
In block/blk-wbt.c (ffffffff817fd9cb)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In io_uring/io_uring.c (ffffffff8180c04a)
Location: include/linux/trace_events.h:439
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
In arch/x86/lib/msr.c (ffffffff8193047a)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff819449da)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/pwm/core.c (ffffffff81959e0b)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/pwm/core.c:perf_trace_pwm
```
```
In drivers/clk/clk.c (ffffffff81a890ce)
Location: include/linux/trace_events.h:439
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
In drivers/regulator/core.c (ffffffff81ad33bc)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/iommu/intel/trace.c (ffffffff81b69f4d)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/iommu/intel/trace.c:perf_trace_prq_report
  - drivers/iommu/intel/trace.c:perf_trace_qi_submit
```
```
In drivers/iommu/iommu-traces.c (ffffffff81b78aa5)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffffffff81bbc406)
Location: include/linux/trace_events.h:439
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
In drivers/base/trace.c (ffffffff81bcdbf6)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/base/trace.c:perf_trace_devres
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81c12f7e)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81c199ac)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff81c1c021)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/scsi/sd_zbc.c (ffffffff81c412bb)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:perf_trace_scsi_zone_wp_update
  - drivers/scsi/sd_zbc.c:perf_trace_scsi_prepare_zone_append
```
```
In drivers/ata/libata-core.c (ffffffff81c4dca1)
Location: include/linux/trace_events.h:439
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
In drivers/gpu/drm/drm_trace_points.c (ffffffff81cb380a)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_trace_points.c:perf_trace_drm_vblank_event_delivered
  - drivers/gpu/drm/drm_trace_points.c:perf_trace_drm_vblank_event_queued
  - drivers/gpu/drm/drm_trace_points.c:perf_trace_drm_vblank_event
```
```
In drivers/spi/spi.c (ffffffff81cdb349)
Location: include/linux/trace_events.h:439
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
In drivers/net/phy/mdio_bus.c (ffffffff81cf258f)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81daff81)
Location: include/linux/trace_events.h:439
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
In drivers/rtc/interface.c (ffffffff81dd7aa1)
Location: include/linux/trace_events.h:439
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
In drivers/i2c/i2c-core-base.c (ffffffff81ddf52b)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81de4c5f)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff81dfad0a)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff81dfd2b2)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81e0640e)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_actor
  - drivers/thermal/gov_power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/watchdog/watchdog_core.c (ffffffff81e0ad3b)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:perf_trace_watchdog_set_timeout
  - drivers/watchdog/watchdog_core.c:perf_trace_watchdog_template
```
```
In drivers/cpufreq/amd-pstate-trace.c (ffffffff81e5b26b)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate-trace.c:perf_trace_amd_pstate_perf
```
```
In drivers/mmc/core/core.c (ffffffff81e69a75)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff81e96a56)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_request_start
```
```
In drivers/devfreq/devfreq.c (ffffffff81ea1e29)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_frequency
```
```
In drivers/ras/ras.c (ffffffff81ead34a)
Location: include/linux/trace_events.h:439
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
In drivers/interconnect/core.c (ffffffff81eb3de1)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - drivers/interconnect/core.c:perf_trace_icc_set_bw_end
  - drivers/interconnect/core.c:perf_trace_icc_set_bw
```
```
In net/core/net-traces.c (ffffffff81f53edf)
Location: include/linux/trace_events.h:439
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
In net/netlink/af_netlink.c (ffffffff81f85c19)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:perf_trace_netlink_extack
```
```
In net/bpf/test_run.c (ffffffff81f90a81)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (ffffffff820991ba)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/devlink/core.c (ffffffff820ff134)
Location: include/linux/trace_events.h:439
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
In net/mptcp/protocol.c (ffffffff821439f6)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - net/mptcp/protocol.c:perf_trace_subflow_check_data_avail
  - net/mptcp/protocol.c:perf_trace_ack_update_msk
  - net/mptcp/protocol.c:perf_trace_mptcp_dump_mpext
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
```
```
In net/mctp/af_mctp.c (ffffffff82162975)
Location: include/linux/trace_events.h:439
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:perf_trace_mctp_key_release
  - net/mctp/af_mctp.c:perf_trace_mctp_key_acquire
```
```
In net/handshake/trace.c (ffffffff8216ca0a)
Location: include/linux/trace_events.h:439
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
In lib/maple_tree.c (ffffffff8217df2b)
Location: include/linux/trace_events.h:439
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
In init/main.c (ffff800010084c9c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/arm64/kernel/ptrace.c (ffff80001008a93c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:perf_trace_sys_exit
  - arch/arm64/kernel/ptrace.c:perf_trace_sys_enter
```
```
In arch/arm64/kernel/smp.c (ffff80001009be70)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:perf_trace_ipi_handler
  - arch/arm64/kernel/smp.c:perf_trace_ipi_raise
```
```
In arch/arm64/kernel/armv8_deprecated.c (ffff8000100a84fc)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/arm64/kernel/armv8_deprecated.c:perf_trace_instruction_emulation
```
```
In virt/kvm/kvm_main.c (ffff8000100ba514)
Location: include/linux/trace_events.h:289
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
In virt/kvm/arm/arm.c (ffff8000100c4f38)
Location: include/linux/trace_events.h:289
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
In arch/arm64/kvm/handle_exit.c (ffff8000100d0d4c)
Location: include/linux/trace_events.h:289
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
In virt/kvm/arm/vgic/vgic.c (ffff8000100db880)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic.c:perf_trace_vgic_update_irq_pending
```
```
In kernel/fork.c (ffff8000100f1788)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffff8000100f7c98)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffff8000100fecd0)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffff80001010b0e4)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffff80001011d510)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/sched/core.c (ffff800010135458)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
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
In kernel/printk/printk.c (ffff800010172af0)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/rcu/update.c (ffff800010188678)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffff80001019641c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffff80001019dae4)
Location: include/linux/trace_events.h:289
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
In kernel/time/alarmtimer.c (ffff8000101a8f0c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffff8000101c2438)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffff8000101d061c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_syscalls.c (ffff80001023d980)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffff80001025100c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/power-traces.c (ffff8000102541c8)
Location: include/linux/trace_events.h:289
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
In kernel/trace/rpm-traces.c (ffff800010254cb8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffff800010259834)
Location: include/linux/trace_events.h:289
Inline: True
```
```
In kernel/bpf/core.c (ffff80001025cc34)
Location: include/linux/trace_events.h:289
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
In kernel/events/core.c (ffff8000102a0ba8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/events/core.c:perf_trace_run_bpf_submit
```
```
In kernel/rseq.c (ffff8000102ac128)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffff8000102aeae4)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffff8000102b6ddc)
Location: include/linux/trace_events.h:289
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
In mm/swap.c (ffff8000102c0408)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffff8000102c7204)
Location: include/linux/trace_events.h:289
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
In mm/percpu.c (ffff8000102e2010)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffff8000102e69a4)
Location: include/linux/trace_events.h:289
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
In mm/compaction.c (ffff8000102e9544)
Location: include/linux/trace_events.h:289
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
In mm/migrate.c (ffff80001034ea40)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffff80001035c3d0)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffff800010371954)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffff800010376cb4)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffff80001037d3e4)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/fs-writeback.c (ffff8000103c5390)
Location: include/linux/trace_events.h:289
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
In fs/dax.c (ffff8000104081e4)
Location: include/linux/trace_events.h:289
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
In fs/locks.c (ffff800010415ae8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffff8000104b3344)
Location: include/linux/trace_events.h:289
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
In fs/jbd2/journal.c (ffff8000104d4f74)
Location: include/linux/trace_events.h:289
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
In block/blk-core.c (ffff8000105e222c)
Location: include/linux/trace_events.h:289
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
In block/blk-iocost.c (ffff800010614ad8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_activate
```
```
In block/blk-wbt.c (ffff800010621aa4)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In drivers/gpio/gpiolib.c (ffff8000106bf8c4)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffff8000107bff30)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/soc/qcom/rpmh-rsc.c (ffff80001081b8b4)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/soc/qcom/rpmh-rsc.c:perf_trace_rpmh_send_msg
  - drivers/soc/qcom/rpmh-rsc.c:perf_trace_rpmh_tx_done
```
```
In drivers/regulator/core.c (ffff800010843aa4)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffff8000108ad68c)
Location: include/linux/trace_events.h:289
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
In drivers/iommu/iommu-traces.c (ffff8000108c860c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (ffff800010913ef4)
Location: include/linux/trace_events.h:289
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
In drivers/dma-buf/dma-fence.c (ffff800010966ecc)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffff80001096b14c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffff80001096e440)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffff800010998c40)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffff8000109c4704)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffff8000109d776c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffff800010a89e98)
Location: include/linux/trace_events.h:289
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
In drivers/rtc/interface.c (ffff800010aa8430)
Location: include/linux/trace_events.h:289
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
In drivers/i2c/i2c-core-base.c (ffff800010ab0da4)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffff800010ab40a4)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffff800010ad21d4)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffff800010ad463c)
Location: include/linux/trace_events.h:289
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
In drivers/thermal/power_allocator.c (ffff800010adb110)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffff800010b2c5b8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffff800010b799f8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_cmd_class
```
```
In drivers/devfreq/devfreq.c (ffff800010b866e0)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/ras/ras.c (ffff800010b9dc34)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
```
```
In net/core/net-traces.c (ffff800010c1989c)
Location: include/linux/trace_events.h:289
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
In net/core/devlink.c (ffff800010c27690)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/bpf/test_run.c (ffff800010c52f70)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (ffff800010d0f870)
Location: include/linux/trace_events.h:289
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
In init/main.c (c0302f78)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/arm/kernel/ptrace.c (c030b788)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/arm/kernel/ptrace.c:perf_trace_sys_exit
  - arch/arm/kernel/ptrace.c:perf_trace_sys_enter
```
```
In arch/arm/kernel/smp.c (c0311f48)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/arm/kernel/smp.c:perf_trace_ipi_handler
  - arch/arm/kernel/smp.c:perf_trace_ipi_raise
```
```
In arch/arm/common/bL_switcher.c (c0326478)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/arm/common/bL_switcher.c:perf_trace_cpu_migrate
```
```
In kernel/fork.c (c034ff3c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (c0355078)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (c035b43c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (c0363790)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (c0370c28)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/sched/core.c (c0380cfc)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
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
In kernel/printk/printk.c (c03c4a18)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/rcu/update.c (c03d6fd4)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/time/timer.c (c03e6c5c)
Location: include/linux/trace_events.h:289
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
In kernel/time/alarmtimer.c (c03f3ef0)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (c0409060)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (c0413a14)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_syscalls.c (c04789f0)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (c048261c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/power-traces.c (c04863ec)
Location: include/linux/trace_events.h:289
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
In kernel/trace/rpm-traces.c (c0487ef0)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (c048b228)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/core.c (c048fa38)
Location: include/linux/trace_events.h:289
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
In kernel/events/core.c (c04d0b74)
Location: include/linux/trace_events.h:289
Inline: True
```
```
In kernel/rseq.c (c04d91a0)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (c04da4ec)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (c04e2e94)
Location: include/linux/trace_events.h:289
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
In mm/swap.c (c04eb814)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (c04f05d8)
Location: include/linux/trace_events.h:289
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
In mm/percpu.c (c05055cc)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (c05092c4)
Location: include/linux/trace_events.h:289
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
In mm/compaction.c (c050c99c)
Location: include/linux/trace_events.h:289
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
In mm/migrate.c (c0550bc4)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/page_isolation.c (c055e580)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (c0562674)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (c05686fc)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/fs-writeback.c (c059f7fc)
Location: include/linux/trace_events.h:289
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
In fs/locks.c (c05e06f4)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (c0670b34)
Location: include/linux/trace_events.h:289
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
In fs/jbd2/journal.c (c0695f78)
Location: include/linux/trace_events.h:289
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
In block/blk-core.c (c078d28c)
Location: include/linux/trace_events.h:289
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
In block/blk-iocost.c (c07c0840)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_activate
```
```
In block/blk-wbt.c (c07c81b4)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In drivers/gpio/gpiolib.c (c085d140)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (c08ee51c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/dma/tegra20-apb-dma.c (c092c708)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/dma/tegra20-apb-dma.c:perf_trace_tegra_dma_isr
  - drivers/dma/tegra20-apb-dma.c:perf_trace_tegra_dma_complete_cb
  - drivers/dma/tegra20-apb-dma.c:perf_trace_tegra_dma_tx_status
```
```
In drivers/regulator/core.c (c094cb44)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (c09a8b9c)
Location: include/linux/trace_events.h:289
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
In drivers/iommu/iommu-traces.c (c09bf5cc)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (c09f8fa8)
Location: include/linux/trace_events.h:289
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
In drivers/dma-buf/dma-fence.c (c0a3df48)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (c0a416dc)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (c0a427bc)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (c0a667bc)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (c0ab1224)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (c0abe46c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (c0b5acb0)
Location: include/linux/trace_events.h:289
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
In drivers/usb/musb/musb_trace.c (c0b67e4c)
Location: include/linux/trace_events.h:289
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
In drivers/usb/gadget/udc/trace.c (c0b74894)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/usb/gadget/udc/trace.c:perf_trace_udc_log_req
  - drivers/usb/gadget/udc/trace.c:perf_trace_udc_log_ep
  - drivers/usb/gadget/udc/trace.c:perf_trace_udc_log_gadget
```
```
In drivers/rtc/interface.c (c0b86410)
Location: include/linux/trace_events.h:289
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
In drivers/i2c/i2c-core-base.c (c0b90288)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (c0b945a8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (c0bb2028)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (c0bb52ec)
Location: include/linux/trace_events.h:289
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
In drivers/thermal/power_allocator.c (c0bbac3c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (c0c08da8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (c0c5f374)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_cmd_class
```
```
In drivers/devfreq/devfreq.c (c0c696fc)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/ras/ras.c (c0c7fa2c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
```
```
In sound/soc/soc-core.c (c0ca4a08)
Location: include/linux/trace_events.h:289
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
In net/core/net-traces.c (c0d2f2e8)
Location: include/linux/trace_events.h:289
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
In net/core/devlink.c (c0d3ecc4)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/bpf/test_run.c (c0d622b8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (c0e1220c)
Location: include/linux/trace_events.h:289
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
In init/main.c (c00000000000f538)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/powerpc/kernel/ptrace.c (c000000000011688)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/powerpc/kernel/ptrace.c:perf_trace_sys_exit
  - arch/powerpc/kernel/ptrace.c:perf_trace_sys_enter
```
```
In arch/powerpc/kernel/irq.c (c00000000001a310)
Location: include/linux/trace_events.h:289
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
In arch/powerpc/mm/book3s64/hash_pgtable.c (c00000000008ac48)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_pgtable.c:perf_trace_hugepage_splitting
  - arch/powerpc/mm/book3s64/hash_pgtable.c:perf_trace_hugepage_update
  - arch/powerpc/mm/book3s64/hash_pgtable.c:perf_trace_hugepage_set_pmd
  - arch/powerpc/mm/book3s64/hash_pgtable.c:perf_trace_hugepage_invalidate
```
```
In arch/powerpc/platforms/powernv/vas-window.c (c0000000000e1a28)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/vas-window.c:perf_trace_vas_paste_crb
  - arch/powerpc/platforms/powernv/vas-window.c:perf_trace_vas_tx_win_open
  - arch/powerpc/platforms/powernv/vas-window.c:perf_trace_vas_rx_win_open
```
```
In kernel/fork.c (c000000000136988)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (c00000000013cfa8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (c0000000001455b0)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (c000000000151890)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (c0000000001644d0)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/sched/core.c (c00000000017b010)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
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
In kernel/printk/printk.c (c0000000001caac0)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/rcu/update.c (c0000000001e26f0)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (c0000000001f65d4)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (c0000000001fd418)
Location: include/linux/trace_events.h:289
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
In kernel/time/alarmtimer.c (c00000000020bae8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (c000000000228408)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (c00000000023a518)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_syscalls.c (c0000000002cc738)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (c0000000002ebffc)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/power-traces.c (c0000000002f26a8)
Location: include/linux/trace_events.h:289
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
In kernel/trace/rpm-traces.c (c0000000002f47dc)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (c0000000002fb184)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/core.c (c0000000003006b8)
Location: include/linux/trace_events.h:289
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
In kernel/events/core.c (c000000000352678)
Location: include/linux/trace_events.h:289
Inline: True
```
```
In kernel/rseq.c (c000000000360048)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (c000000000361b98)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (c00000000036d468)
Location: include/linux/trace_events.h:289
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
In mm/swap.c (c000000000378e60)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (c000000000380db0)
Location: include/linux/trace_events.h:289
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
In mm/percpu.c (c0000000003a0a20)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (c0000000003a5e50)
Location: include/linux/trace_events.h:289
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
In mm/compaction.c (c0000000003aad00)
Location: include/linux/trace_events.h:289
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
In mm/migrate.c (c000000000430e98)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (c000000000444b78)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (c000000000462af0)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (c000000000468c90)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (c0000000004734f8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/fs-writeback.c (c0000000004c27a0)
Location: include/linux/trace_events.h:289
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
In fs/dax.c (c0000000005117d0)
Location: include/linux/trace_events.h:289
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
In fs/locks.c (c000000000522bd0)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (c0000000005deb40)
Location: include/linux/trace_events.h:289
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
In fs/jbd2/journal.c (c00000000060d9b8)
Location: include/linux/trace_events.h:289
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
In block/blk-core.c (c000000000772d50)
Location: include/linux/trace_events.h:289
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
In block/blk-iocost.c (c0000000007b45ac)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_activate
```
```
In block/blk-wbt.c (c0000000007c03f8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In drivers/gpio/gpiolib.c (c000000000839490)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/regulator/core.c (c0000000008ddce0)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (c000000000944a20)
Location: include/linux/trace_events.h:289
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
In drivers/iommu/iommu-traces.c (c00000000096fc84)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/base/regmap/regmap.c (c0000000009b50c8)
Location: include/linux/trace_events.h:289
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
In drivers/dma-buf/dma-fence.c (c000000000a1f23c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (c000000000a244e0)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (c000000000a25c60)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (c000000000a588a0)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (c000000000a87084)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (c000000000a98310)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/vfio/pci/vfio_pci_nvlink2.c (c000000000abd760)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_nvlink2.c:perf_trace_vfio_pci_npu2_mmap
  - drivers/vfio/pci/vfio_pci_nvlink2.c:perf_trace_vfio_pci_nvgpu_mmap
  - drivers/vfio/pci/vfio_pci_nvlink2.c:perf_trace_vfio_pci_nvgpu_mmap_fault
```
```
In drivers/usb/host/xhci-trace.c (c000000000b625b0)
Location: include/linux/trace_events.h:289
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
In drivers/rtc/interface.c (c000000000b88bc0)
Location: include/linux/trace_events.h:289
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
In drivers/i2c/i2c-core-base.c (c000000000b90b80)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (c000000000b96a94)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (c000000000bb5cbc)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (c000000000bb9380)
Location: include/linux/trace_events.h:289
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
In drivers/thermal/power_allocator.c (c000000000bc2584)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (c000000000c26a74)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/devfreq/devfreq.c (c000000000c6510c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/ras/ras.c (c000000000c6f9c0)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
```
```
In net/core/net-traces.c (c000000000d06214)
Location: include/linux/trace_events.h:289
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
In net/core/devlink.c (c000000000d1c2d4)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/bpf/test_run.c (c000000000d51dd0)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (c000000000e36f68)
Location: include/linux/trace_events.h:289
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
In init/main.c (ffffffe0000b3ed4)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/riscv/kernel/ptrace.c (ffffffe0000b5bde)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/riscv/kernel/ptrace.c:perf_trace_sys_exit
  - arch/riscv/kernel/ptrace.c:perf_trace_sys_enter
```
```
In kernel/fork.c (ffffffe0000be534)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffe0000c2a20)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffe0000c6946)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffe0000cd222)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffe0000d6428)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/sched/core.c (ffffffe0000e4d9a)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
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
In kernel/printk/printk.c (ffffffe00010e10a)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/rcu/update.c (ffffffe00011dca6)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffe000127e1e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffffffe00012b6fa)
Location: include/linux/trace_events.h:289
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
In kernel/time/alarmtimer.c (ffffffe000134584)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffe00014148e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffe000148988)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_syscalls.c (ffffffe000193256)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/power-traces.c (ffffffe00019871c)
Location: include/linux/trace_events.h:289
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
In kernel/trace/rpm-traces.c (ffffffe000199d88)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/bpf/core.c (ffffffe00019adc6)
Location: include/linux/trace_events.h:289
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
In kernel/events/core.c (ffffffe0001c6230)
Location: include/linux/trace_events.h:289
Inline: True
```
```
In mm/filemap.c (ffffffe0001d3fd4)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffe0001da97a)
Location: include/linux/trace_events.h:289
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
In mm/swap.c (ffffffe0001e1cba)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffe0001e5f60)
Location: include/linux/trace_events.h:289
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
In mm/percpu.c (ffffffe0001f832e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffe0001fb450)
Location: include/linux/trace_events.h:289
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
In mm/compaction.c (ffffffe0001fdfaa)
Location: include/linux/trace_events.h:289
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
In mm/migrate.c (ffffffe00023dfc8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/page_isolation.c (ffffffe00024abba)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffe00024ec92)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffe000252d24)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/fs-writeback.c (ffffffe000282be4)
Location: include/linux/trace_events.h:289
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
In fs/dax.c (ffffffe0002b1982)
Location: include/linux/trace_events.h:289
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
In fs/locks.c (ffffffe0002bbc82)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffe00032ca32)
Location: include/linux/trace_events.h:289
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
In fs/jbd2/journal.c (ffffffe00034a53e)
Location: include/linux/trace_events.h:289
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
In block/blk-core.c (ffffffe000422d08)
Location: include/linux/trace_events.h:289
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
In block/blk-iocost.c (ffffffe00044be68)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_activate
```
```
In block/blk-wbt.c (ffffffe000452e80)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In drivers/gpio/gpiolib.c (ffffffe0004a433a)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffe00050ab36)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffe00052172e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffe000560ff8)
Location: include/linux/trace_events.h:289
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
In drivers/base/regmap/regmap.c (ffffffe000595240)
Location: include/linux/trace_events.h:289
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
In drivers/dma-buf/dma-fence.c (ffffffe0005d37ac)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffe0005d61d4)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffe0005d7c9a)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffe0005f7922)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffe00061738a)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffe000622c0c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffe00069d1de)
Location: include/linux/trace_events.h:289
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
In drivers/rtc/interface.c (ffffffe0006b3460)
Location: include/linux/trace_events.h:289
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
In drivers/i2c/i2c-core-base.c (ffffffe0006b7000)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffe0006bad5e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffe0006cdc58)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffe0006ceaa4)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffe0006d4f42)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffe0007065a6)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/devfreq/devfreq.c (ffffffe00072f7ca)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/ras/ras.c (ffffffe000735ad4)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
```
```
In net/core/net-traces.c (ffffffe000791df0)
Location: include/linux/trace_events.h:289
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
In net/core/devlink.c (ffffffe00079e2f6)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/bpf/test_run.c (ffffffe0007bd652)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (ffffffe0008533aa)
Location: include/linux/trace_events.h:289
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
In init/main.c (ffffffff81002203)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/common.c (ffffffff810038c3)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004f2e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff8102a433)
Location: include/linux/trace_events.h:289
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
In arch/x86/hyperv/mmu.c (ffffffff8102e265)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff810334bc)
Location: include/linux/trace_events.h:289
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
In arch/x86/kernel/nmi.c (ffffffff81035f38)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e34e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c8ae)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105f503)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff8107ca03)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff8107e758)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff8108c33e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff810962f4)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff8109b69c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff810a0d5e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810a9938)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810b97de)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/sched/core.c (ffffffff810cb29e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
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
In kernel/printk/printk.c (ffffffff81109ef8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff8111aad7)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff8111bb5e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff811283ec)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffffffff8112d2b3)
Location: include/linux/trace_events.h:289
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
In kernel/time/alarmtimer.c (ffffffff81137463)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff8114af09)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff81157b05)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b64a6)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c9cb4)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/power-traces.c (ffffffff811cba08)
Location: include/linux/trace_events.h:289
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
In kernel/trace/rpm-traces.c (ffffffff811cd1a7)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d0ce4)
Location: include/linux/trace_events.h:289
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811d4053)
Location: include/linux/trace_events.h:289
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
In kernel/events/core.c (ffffffff81203da0)
Location: include/linux/trace_events.h:289
Inline: True
```
```
In kernel/rseq.c (ffffffff81217dac)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff81218f03)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff81220b9f)
Location: include/linux/trace_events.h:289
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
In mm/swap.c (ffffffff81228aee)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8122de68)
Location: include/linux/trace_events.h:289
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
In mm/percpu.c (ffffffff8124344e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff81246a7f)
Location: include/linux/trace_events.h:289
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
In mm/compaction.c (ffffffff81249d08)
Location: include/linux/trace_events.h:289
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
In mm/migrate.c (ffffffff812a531c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff812b2abc)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff812c5908)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff812c9768)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff812d0ed2)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/fs-writeback.c (ffffffff8130678e)
Location: include/linux/trace_events.h:289
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
In fs/dax.c (ffffffff8133eba8)
Location: include/linux/trace_events.h:289
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
In fs/locks.c (ffffffff8134ab07)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff813ce348)
Location: include/linux/trace_events.h:289
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
In fs/jbd2/journal.c (ffffffff813efcf3)
Location: include/linux/trace_events.h:289
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
In block/blk-core.c (ffffffff814db6d5)
Location: include/linux/trace_events.h:289
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
In block/blk-iocost.c (ffffffff81509ad2)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_activate
```
```
In block/blk-wbt.c (ffffffff8151154c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff81555ae8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff8155f5b8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff816163c5)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff8163f882)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff81681898)
Location: include/linux/trace_events.h:289
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
In drivers/iommu/iommu-traces.c (ffffffff816a1f80)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/iommu/intel-trace.c (ffffffff816b6908)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/iommu/intel-trace.c:perf_trace_dma_unmap
  - drivers/iommu/intel-trace.c:perf_trace_dma_map
```
```
In drivers/base/regmap/regmap.c (ffffffff816e5483)
Location: include/linux/trace_events.h:289
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
In drivers/dma-buf/dma-fence.c (ffffffff8171b4bb)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8171e0c6)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff8171f5be)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/nvme/host/core.c (ffffffff817458a8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:perf_trace_nvme_sq
  - drivers/nvme/host/core.c:perf_trace_nvme_async_event
  - drivers/nvme/host/core.c:perf_trace_nvme_complete_rq
  - drivers/nvme/host/core.c:perf_trace_nvme_setup_cmd
```
```
In drivers/ata/libata-core.c (ffffffff817525ee)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff817779c1)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81782380)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff8180110e)
Location: include/linux/trace_events.h:289
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
In drivers/rtc/interface.c (ffffffff81818b2e)
Location: include/linux/trace_events.h:289
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
In drivers/hwmon/hwmon.c (ffffffff8182b0e2)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff8182d0cc)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff81831cd0)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff81877ba8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff81892c0e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_cmd_class
```
```
In drivers/devfreq/devfreq.c (ffffffff8189afc5)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/ras/ras.c (ffffffff818a0528)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
```
```
In net/core/net-traces.c (ffffffff8191147b)
Location: include/linux/trace_events.h:289
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
In net/core/devlink.c (ffffffff8191f834)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/bpf/test_run.c (ffffffff8194370e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (ffffffff819e86bb)
Location: include/linux/trace_events.h:289
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
In init/main.c (ffffffff810006f3)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/common.c (ffffffff81001da3)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8100360e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/hyperv/mmu.c (ffffffff8101dc25)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff81022dfc)
Location: include/linux/trace_events.h:289
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
In arch/x86/kernel/nmi.c (ffffffff81025888)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8102db4e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103bc5e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8104f833)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff8106c173)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff8106d848)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff8107ae6e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff81084d74)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff8108a0cc)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff8108f77e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810982e8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810a811e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/sched/core.c (ffffffff810b9b6e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
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
In kernel/printk/printk.c (ffffffff810fadd8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff8110bb47)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff8110cbce)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff8111ac7c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffffffff8111fb23)
Location: include/linux/trace_events.h:289
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
In kernel/time/alarmtimer.c (ffffffff81129eb3)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff8113e1b9)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff8114ae25)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_syscalls.c (ffffffff811a92a6)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811bca84)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/power-traces.c (ffffffff811be7d8)
Location: include/linux/trace_events.h:289
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
In kernel/trace/rpm-traces.c (ffffffff811bff77)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c3ab4)
Location: include/linux/trace_events.h:289
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811c6e13)
Location: include/linux/trace_events.h:289
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
In kernel/events/core.c (ffffffff811f6b30)
Location: include/linux/trace_events.h:289
Inline: True
```
```
In kernel/context_tracking.c (ffffffff8120a72e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/context_tracking.c:perf_trace_context_tracking_user
```
```
In kernel/rseq.c (ffffffff8120afbc)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff8120c113)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff81213d4f)
Location: include/linux/trace_events.h:289
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
In mm/swap.c (ffffffff8121bc2e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81220f28)
Location: include/linux/trace_events.h:289
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
In mm/percpu.c (ffffffff8123641e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff81239a2f)
Location: include/linux/trace_events.h:289
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
In mm/compaction.c (ffffffff8123ccb8)
Location: include/linux/trace_events.h:289
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
In mm/migrate.c (ffffffff81296dec)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff812a3e3c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff812b6948)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff812ba7a8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff812c1b52)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/fs-writeback.c (ffffffff812f73ae)
Location: include/linux/trace_events.h:289
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
In fs/dax.c (ffffffff8132f868)
Location: include/linux/trace_events.h:289
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
In fs/locks.c (ffffffff8133b7e7)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff813bedc8)
Location: include/linux/trace_events.h:289
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
In fs/jbd2/journal.c (ffffffff813e0773)
Location: include/linux/trace_events.h:289
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
In block/blk-core.c (ffffffff814cc085)
Location: include/linux/trace_events.h:289
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
In block/blk-iocost.c (ffffffff814f9f82)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_activate
```
```
In block/blk-wbt.c (ffffffff8150186c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff81545cc8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff81550408)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff8160a8f5)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff8161fc62)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff8165f718)
Location: include/linux/trace_events.h:289
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
In drivers/iommu/iommu-traces.c (ffffffff8167f970)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/iommu/intel-trace.c (ffffffff81694548)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/iommu/intel-trace.c:perf_trace_dma_unmap
  - drivers/iommu/intel-trace.c:perf_trace_dma_map
```
```
In drivers/base/regmap/regmap.c (ffffffff816bfac3)
Location: include/linux/trace_events.h:289
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
In drivers/dma-buf/dma-fence.c (ffffffff816f491b)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816f7646)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff816f89ee)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/nvme/host/core.c (ffffffff81727538)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:perf_trace_nvme_sq
  - drivers/nvme/host/core.c:perf_trace_nvme_async_event
  - drivers/nvme/host/core.c:perf_trace_nvme_complete_rq
  - drivers/nvme/host/core.c:perf_trace_nvme_setup_cmd
```
```
In drivers/ata/libata-core.c (ffffffff8173248e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff81757771)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81762110)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff817c62ae)
Location: include/linux/trace_events.h:289
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
In drivers/rtc/interface.c (ffffffff817e021e)
Location: include/linux/trace_events.h:289
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
In drivers/hwmon/hwmon.c (ffffffff817f2772)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff817f475c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff817f9360)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/hv/hv_trace.c (ffffffff81854a4e)
Location: include/linux/trace_events.h:289
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
In drivers/devfreq/devfreq.c (ffffffff81858495)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/ras/ras.c (ffffffff8185bc98)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
```
```
In net/core/net-traces.c (ffffffff818cb23b)
Location: include/linux/trace_events.h:289
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
In net/core/devlink.c (ffffffff818d95e4)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/bpf/test_run.c (ffffffff818fd1fe)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (ffffffff819a547b)
Location: include/linux/trace_events.h:289
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
In init/main.c (ffffffff81002203)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/common.c (ffffffff810038c3)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004eee)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff8102a293)
Location: include/linux/trace_events.h:289
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
In arch/x86/hyperv/mmu.c (ffffffff8102e0c5)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff8103331c)
Location: include/linux/trace_events.h:289
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
In arch/x86/kernel/nmi.c (ffffffff81035d98)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e18e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c6ee)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105f933)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff8107c9b3)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff8107e708)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff8108c2ee)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff810962a4)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff8109b64c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff810a0d0e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810a8e98)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810b8d3e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/sched/core.c (ffffffff810ca7be)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
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
In kernel/printk/printk.c (ffffffff81107de8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff811189c7)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff81119a4e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff8112610c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffffffff8112afd3)
Location: include/linux/trace_events.h:289
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
In kernel/time/alarmtimer.c (ffffffff81135183)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff81148db9)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff811558d5)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b4276)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c7a84)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/power-traces.c (ffffffff811c97d8)
Location: include/linux/trace_events.h:289
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
In kernel/trace/rpm-traces.c (ffffffff811caf77)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ceab4)
Location: include/linux/trace_events.h:289
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811d1e23)
Location: include/linux/trace_events.h:289
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
In kernel/events/core.c (ffffffff81201b70)
Location: include/linux/trace_events.h:289
Inline: True
```
```
In kernel/rseq.c (ffffffff81215b4c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff81216ca3)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff8121e93f)
Location: include/linux/trace_events.h:289
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
In mm/swap.c (ffffffff8122688e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8122bc08)
Location: include/linux/trace_events.h:289
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
In mm/percpu.c (ffffffff812411ee)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff8124481f)
Location: include/linux/trace_events.h:289
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
In mm/compaction.c (ffffffff81247aa8)
Location: include/linux/trace_events.h:289
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
In mm/migrate.c (ffffffff812a312c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff812b08cc)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff812c3718)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff812c7578)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff812cece2)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/fs-writeback.c (ffffffff8130457e)
Location: include/linux/trace_events.h:289
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
In fs/dax.c (ffffffff8133c678)
Location: include/linux/trace_events.h:289
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
In fs/locks.c (ffffffff813485d7)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff813cb7d8)
Location: include/linux/trace_events.h:289
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
In fs/jbd2/journal.c (ffffffff813ed073)
Location: include/linux/trace_events.h:289
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
In block/blk-core.c (ffffffff814d7765)
Location: include/linux/trace_events.h:289
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
In block/blk-iocost.c (ffffffff81505b62)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_activate
```
```
In block/blk-wbt.c (ffffffff8150d5dc)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff81551828)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff8155e128)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff816441a5)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff8166dbc2)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff816afc78)
Location: include/linux/trace_events.h:289
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
In drivers/iommu/iommu-traces.c (ffffffff816d01f0)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/iommu/intel-trace.c (ffffffff816e4dd8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/iommu/intel-trace.c:perf_trace_dma_unmap
  - drivers/iommu/intel-trace.c:perf_trace_dma_map
```
```
In drivers/base/regmap/regmap.c (ffffffff81712613)
Location: include/linux/trace_events.h:289
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
In drivers/dma-buf/dma-fence.c (ffffffff8175a28b)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8175ce96)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff8175e38e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff817822de)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff817a7d61)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff817b2730)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff8183dbde)
Location: include/linux/trace_events.h:289
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
In drivers/rtc/interface.c (ffffffff8185a00e)
Location: include/linux/trace_events.h:289
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
In drivers/i2c/i2c-core-base.c (ffffffff8185fc28)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff818639d0)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff8187a712)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff8187c6fc)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff81881300)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff818c9048)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff818e670e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_cmd_class
```
```
In drivers/devfreq/devfreq.c (ffffffff818ea6b5)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/ras/ras.c (ffffffff818f16c8)
Location: include/linux/trace_events.h:289
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
In net/core/net-traces.c (ffffffff819624ab)
Location: include/linux/trace_events.h:289
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
In net/core/devlink.c (ffffffff819709c4)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/bpf/test_run.c (ffffffff8199489e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (ffffffff81a5313b)
Location: include/linux/trace_events.h:289
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
In init/main.c (ffffffff81002203)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/x86/entry/common.c (ffffffff81003993)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8100502e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:perf_trace_emulate_vsyscall
```
```
In arch/x86/xen/trace.c (ffffffff8102b083)
Location: include/linux/trace_events.h:289
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
In arch/x86/hyperv/mmu.c (ffffffff8102eeb5)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff8103427c)
Location: include/linux/trace_events.h:289
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
In arch/x86/kernel/nmi.c (ffffffff81036d78)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:perf_trace_nmi_handler
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103f30e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:perf_trace_x86_fpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104dafe)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:perf_trace_mce_record
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060e93)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_l2
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:perf_trace_pseudo_lock_mem_latency
```
```
In arch/x86/mm/init.c (ffffffff8107eab3)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/mm/init.c:perf_trace_tlb_flush
```
```
In arch/x86/mm/fault.c (ffffffff810807f8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:perf_trace_x86_exceptions
```
```
In arch/x86/mm/mpx.c (ffffffff8108e64e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:perf_trace_mpx_new_bounds_table
  - arch/x86/mm/mpx.c:perf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:perf_trace_bounds_exception_mpx
  - arch/x86/mm/mpx.c:perf_trace_mpx_bounds_register_exception
```
```
In kernel/fork.c (ffffffff8109dec4)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (ffffffff810a32bc)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/softirq.c (ffffffff810a8c8e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffffffff810b0fe8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (ffffffff810c179e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/sched/core.c (ffffffff810d2cbe)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
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
In kernel/printk/printk.c (ffffffff81113188)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/irq/matrix.c (ffffffff81124057)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/irq/matrix.c:perf_trace_irq_matrix_cpu
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global_update
  - kernel/irq/matrix.c:perf_trace_irq_matrix_global
```
```
In kernel/rcu/update.c (ffffffff811251be)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/dma/swiotlb.c (ffffffff8113274c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/time/timer.c (ffffffff811373e3)
Location: include/linux/trace_events.h:289
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
In kernel/time/alarmtimer.c (ffffffff81141ba3)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/module.c (ffffffff811559d9)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (ffffffff81163045)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/trace/trace_syscalls.c (ffffffff811c2316)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811d5ce4)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/power-traces.c (ffffffff811d7a38)
Location: include/linux/trace_events.h:289
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
In kernel/trace/rpm-traces.c (ffffffff811d91d7)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffffffff811dcd24)
Location: include/linux/trace_events.h:289
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811e0113)
Location: include/linux/trace_events.h:289
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
In kernel/events/core.c (ffffffff81210f00)
Location: include/linux/trace_events.h:289
Inline: True
```
```
In kernel/rseq.c (ffffffff81224b4c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (ffffffff81225d23)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffffffff8122d98f)
Location: include/linux/trace_events.h:289
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
In mm/swap.c (ffffffff81235bbe)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8123aff8)
Location: include/linux/trace_events.h:289
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
In mm/percpu.c (ffffffff8125096e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (ffffffff81253fdf)
Location: include/linux/trace_events.h:289
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
In mm/compaction.c (ffffffff812572d8)
Location: include/linux/trace_events.h:289
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
In mm/migrate.c (ffffffff812b33bc)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/khugepaged.c (ffffffff812c0c0c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/page_isolation.c (ffffffff812d41b8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/cma.c (ffffffff812d8268)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In fs/open.c (ffffffff812dfaf2)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/fs-writeback.c (ffffffff813158ee)
Location: include/linux/trace_events.h:289
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
In fs/dax.c (ffffffff8134f828)
Location: include/linux/trace_events.h:289
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
In fs/locks.c (ffffffff8135b917)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/ext4/super.c (ffffffff813e0a28)
Location: include/linux/trace_events.h:289
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
In fs/jbd2/journal.c (ffffffff81402a43)
Location: include/linux/trace_events.h:289
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
In block/blk-core.c (ffffffff814f0375)
Location: include/linux/trace_events.h:289
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
In block/blk-iocost.c (ffffffff81521402)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_activate
```
```
In block/blk-wbt.c (ffffffff81526bfc)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In arch/x86/lib/msr.c (ffffffff8156b538)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:perf_trace_msr_trace_class
```
```
In drivers/gpio/gpiolib.c (ffffffff81577fb8)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (ffffffff8165e5e5)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/regulator/core.c (ffffffff81688222)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/char/random.c (ffffffff816ca2d8)
Location: include/linux/trace_events.h:289
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
In drivers/iommu/iommu-traces.c (ffffffff816ea780)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/iommu/intel-trace.c (ffffffff816ff498)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/iommu/intel-trace.c:perf_trace_dma_unmap
  - drivers/iommu/intel-trace.c:perf_trace_dma_map
```
```
In drivers/base/regmap/regmap.c (ffffffff8172d803)
Location: include/linux/trace_events.h:289
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
In drivers/dma-buf/dma-fence.c (ffffffff8177584b)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81778666)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffffffff817799ee)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/ata/libata-core.c (ffffffff8179c0ce)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff817c1be1)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff817cc6c0)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/usb/host/xhci-trace.c (ffffffff818580ae)
Location: include/linux/trace_events.h:289
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
In drivers/rtc/interface.c (ffffffff818750ee)
Location: include/linux/trace_events.h:289
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
In drivers/i2c/i2c-core-base.c (ffffffff8187ae38)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8187ec30)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (ffffffff81896112)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffffffff8189812c)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (ffffffff8189cd70)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/mmc/core/core.c (ffffffff818e5b68)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffffffff8190338e)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_cmd_class
```
```
In drivers/devfreq/devfreq.c (ffffffff8190b735)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/ras/ras.c (ffffffff81912748)
Location: include/linux/trace_events.h:289
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
In net/core/net-traces.c (ffffffff8198471b)
Location: include/linux/trace_events.h:289
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
In net/core/devlink.c (ffffffff81992eb4)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/bpf/test_run.c (ffffffff819b73ae)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/ipv6/route.c (ffffffff81a5f08b)
Location: include/linux/trace_events.h:289
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
</details>
</li>
</ul>

## Differences
