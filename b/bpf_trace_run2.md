# Function: <code>bpf_trace_run2</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
void bpf_trace_run2(struct bpf_prog *prog, u64 arg0, u64 arg1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811a47e0)
Location: kernel/trace/bpf_trace.c:1134
Inline: False
Direct callers:
  - init/main.c:__bpf_trace_initcall_finish
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_callback
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_entry
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_mmu_flush_tlb_others
  - arch/x86/kernel/irq.c:__bpf_trace_vector_reserve
  - arch/x86/mm/init.c:__bpf_trace_tlb_flush
  - arch/x86/mm/mpx.c:__bpf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:__bpf_trace_mpx_bounds_register_exception
  - kernel/fork.c:__bpf_trace_task_rename
  - kernel/fork.c:__bpf_trace_task_newtask
  - kernel/softirq.c:__bpf_trace_irq_handler_entry
  - kernel/sched/core.c:__bpf_trace_sched_stat_template
  - kernel/sched/core.c:__bpf_trace_sched_migrate_task
  - kernel/printk/printk.c:__bpf_trace_console
  - kernel/irq/matrix.c:__bpf_trace_irq_matrix_global_update
  - kernel/time/timer.c:__bpf_trace_tick_stop
  - kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:__bpf_trace_hrtimer_start
  - kernel/time/alarmtimer.c:__bpf_trace_alarm_class
  - kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend
  - kernel/module.c:__bpf_trace_module_refcnt
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_request
  - kernel/trace/power-traces.c:__bpf_trace_wakeup_source
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:__bpf_trace_cpu
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal
  - mm/filemap.c:__bpf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:__bpf_trace_filemap_set_wb_err
  - mm/swap.c:__bpf_trace_mm_lru_insertion
  - mm/slab_common.c:__bpf_trace_mm_page_free
  - mm/slab_common.c:__bpf_trace_kmem_free
  - mm/compaction.c:__bpf_trace_mm_compaction_defer_template
  - fs/fs-writeback.c:__bpf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:__bpf_trace_global_dirty_state
  - fs/fs-writeback.c:__bpf_trace_wbc_class
  - fs/fs-writeback.c:__bpf_trace_writeback_work_class
  - fs/fs-writeback.c:__bpf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:__bpf_trace_writeback_dirty_page
  - fs/ext4/super.c:__bpf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:__bpf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:__bpf_trace_ext4_unlink_exit
  - fs/ext4/super.c:__bpf_trace_ext4_unlink_enter
  - fs/ext4/super.c:__bpf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:__bpf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:__bpf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:__bpf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:__bpf_trace_ext4_writepages
  - fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate
  - fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall
  - block/blk-wbt.c:__bpf_trace_wbt_lat
  - block/blk-wbt.c:__bpf_trace_wbt_stat
  - drivers/clk/clk.c:__bpf_trace_clk_phase
  - drivers/clk/clk.c:__bpf_trace_clk_parent
  - drivers/clk/clk.c:__bpf_trace_clk_rate
  - drivers/regulator/core.c:__bpf_trace_regulator_value
  - drivers/char/random.c:__bpf_trace_add_disk_randomness
  - drivers/char/random.c:__bpf_trace_debit_entropy
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool
  - drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error
  - drivers/spi/spi.c:__bpf_trace_spi_transfer
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb
  - drivers/rtc/interface.c:__bpf_trace_rtc_offset_class
  - drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:__bpf_trace_rtc_time_alarm_class
  - drivers/thermal/thermal_core.c:__bpf_trace_cdev_update
  - net/core/net-traces.c:__bpf_trace_fdb_delete
  - net/core/net-traces.c:__bpf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:__bpf_trace_net_dev_start_xmit
  - net/core/net-traces.c:__bpf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:__bpf_trace_kfree_skb
```
**Symbols:**

```
ffffffff811a47e0-ffffffff811a4826: bpf_trace_run2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bpf_trace_run2(struct bpf_prog *prog, u64 arg0, u64 arg1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b28b0)
Location: kernel/trace/bpf_trace.c:1179
Inline: False
Direct callers:
  - init/main.c:__bpf_trace_initcall_finish
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_callback
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_entry
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_mmu_flush_tlb_others
  - arch/x86/kernel/irq.c:__bpf_trace_vector_reserve
  - arch/x86/mm/init.c:__bpf_trace_tlb_flush
  - arch/x86/mm/mpx.c:__bpf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:__bpf_trace_mpx_bounds_register_exception
  - kernel/fork.c:__bpf_trace_task_rename
  - kernel/fork.c:__bpf_trace_task_newtask
  - kernel/softirq.c:__bpf_trace_irq_handler_entry
  - kernel/sched/core.c:__bpf_trace_sched_stat_template
  - kernel/sched/core.c:__bpf_trace_sched_migrate_task
  - kernel/printk/printk.c:__bpf_trace_console
  - kernel/irq/matrix.c:__bpf_trace_irq_matrix_global_update
  - kernel/time/timer.c:__bpf_trace_tick_stop
  - kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:__bpf_trace_hrtimer_start
  - kernel/time/alarmtimer.c:__bpf_trace_alarm_class
  - kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend
  - kernel/module.c:__bpf_trace_module_refcnt
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_request
  - kernel/trace/power-traces.c:__bpf_trace_wakeup_source
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:__bpf_trace_cpu
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal
  - mm/filemap.c:__bpf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:__bpf_trace_filemap_set_wb_err
  - mm/swap.c:__bpf_trace_mm_lru_insertion
  - mm/slab_common.c:__bpf_trace_mm_page_free
  - mm/slab_common.c:__bpf_trace_kmem_free
  - mm/compaction.c:__bpf_trace_mm_compaction_defer_template
  - fs/fs-writeback.c:__bpf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:__bpf_trace_global_dirty_state
  - fs/fs-writeback.c:__bpf_trace_wbc_class
  - fs/fs-writeback.c:__bpf_trace_writeback_work_class
  - fs/fs-writeback.c:__bpf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:__bpf_trace_writeback_dirty_page
  - fs/ext4/super.c:__bpf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:__bpf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:__bpf_trace_ext4_unlink_exit
  - fs/ext4/super.c:__bpf_trace_ext4_unlink_enter
  - fs/ext4/super.c:__bpf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:__bpf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:__bpf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:__bpf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:__bpf_trace_ext4_writepages
  - fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate
  - fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall
  - block/blk-wbt.c:__bpf_trace_wbt_lat
  - block/blk-wbt.c:__bpf_trace_wbt_stat
  - drivers/clk/clk.c:__bpf_trace_clk_duty_cycle
  - drivers/clk/clk.c:__bpf_trace_clk_phase
  - drivers/clk/clk.c:__bpf_trace_clk_parent
  - drivers/clk/clk.c:__bpf_trace_clk_rate
  - drivers/regulator/core.c:__bpf_trace_regulator_value
  - drivers/char/random.c:__bpf_trace_add_disk_randomness
  - drivers/char/random.c:__bpf_trace_debit_entropy
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool
  - drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error
  - drivers/spi/spi.c:__bpf_trace_spi_transfer
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb
  - drivers/rtc/interface.c:__bpf_trace_rtc_offset_class
  - drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:__bpf_trace_rtc_time_alarm_class
  - drivers/thermal/thermal_core.c:__bpf_trace_cdev_update
  - net/core/net-traces.c:__bpf_trace_fdb_delete
  - net/core/net-traces.c:__bpf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:__bpf_trace_net_dev_start_xmit
  - net/core/net-traces.c:__bpf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:__bpf_trace_kfree_skb
```
**Symbols:**

```
ffffffff811b28b0-ffffffff811b28f6: bpf_trace_run2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bpf_trace_run2(struct bpf_prog *prog, u64 arg0, u64 arg1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c1250)
Location: kernel/trace/bpf_trace.c:1348
Inline: False
Direct callers:
  - init/main.c:__bpf_trace_initcall_finish
  - arch/x86/entry/common.c:__bpf_trace_sys_exit
  - arch/x86/entry/common.c:__bpf_trace_sys_enter
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_callback
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_entry
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_mmu_flush_tlb_others
  - arch/x86/kernel/irq.c:__bpf_trace_vector_reserve
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_l2
  - arch/x86/mm/init.c:__bpf_trace_tlb_flush
  - arch/x86/mm/mpx.c:__bpf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:__bpf_trace_mpx_bounds_register_exception
  - kernel/fork.c:__bpf_trace_task_rename
  - kernel/fork.c:__bpf_trace_task_newtask
  - kernel/softirq.c:__bpf_trace_irq_handler_entry
  - kernel/sched/core.c:__bpf_trace_sched_pi_setprio
  - kernel/sched/core.c:__bpf_trace_sched_stat_template
  - kernel/sched/core.c:__bpf_trace_sched_process_fork
  - kernel/sched/core.c:__bpf_trace_sched_migrate_task
  - kernel/printk/printk.c:__bpf_trace_console
  - kernel/irq/matrix.c:__bpf_trace_irq_matrix_global_update
  - kernel/time/timer.c:__bpf_trace_tick_stop
  - kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:__bpf_trace_hrtimer_start
  - kernel/time/timer.c:__bpf_trace_timer_expire_entry
  - kernel/time/alarmtimer.c:__bpf_trace_alarm_class
  - kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend
  - kernel/module.c:__bpf_trace_module_refcnt
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_request
  - kernel/trace/power-traces.c:__bpf_trace_wakeup_source
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:__bpf_trace_cpu
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal
  - kernel/bpf/core.c:__bpf_trace_mem_return_failed
  - kernel/bpf/core.c:__bpf_trace_mem_connect
  - mm/filemap.c:__bpf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:__bpf_trace_filemap_set_wb_err
  - mm/swap.c:__bpf_trace_mm_lru_insertion
  - mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/slab_common.c:__bpf_trace_mm_page_free
  - mm/slab_common.c:__bpf_trace_kmem_free
  - mm/compaction.c:__bpf_trace_mm_compaction_defer_template
  - fs/fs-writeback.c:__bpf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:__bpf_trace_global_dirty_state
  - fs/fs-writeback.c:__bpf_trace_wbc_class
  - fs/fs-writeback.c:__bpf_trace_writeback_work_class
  - fs/fs-writeback.c:__bpf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:__bpf_trace_writeback_page_template
  - fs/locks.c:__bpf_trace_generic_add_lease
  - fs/locks.c:__bpf_trace_filelock_lease
  - fs/ext4/super.c:__bpf_trace_ext4_shutdown
  - fs/ext4/super.c:__bpf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:__bpf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:__bpf_trace_ext4_es_find_extent_range_enter
  - fs/ext4/super.c:__bpf_trace_ext4__es_extent
  - fs/ext4/super.c:__bpf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:__bpf_trace_ext4_unlink_exit
  - fs/ext4/super.c:__bpf_trace_ext4_unlink_enter
  - fs/ext4/super.c:__bpf_trace_ext4__bitmap_load
  - fs/ext4/super.c:__bpf_trace_ext4_da_release_space
  - fs/ext4/super.c:__bpf_trace_ext4_sync_fs
  - fs/ext4/super.c:__bpf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:__bpf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:__bpf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:__bpf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:__bpf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:__bpf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:__bpf_trace_ext4_writepages
  - fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:__bpf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:__bpf_trace_ext4_drop_inode
  - fs/ext4/super.c:__bpf_trace_ext4_request_inode
  - fs/ext4/super.c:__bpf_trace_ext4_other_inode_update_time
  - fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:__bpf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:__bpf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:__bpf_trace_jbd2_commit
  - fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint
  - block/blk-core.c:__bpf_trace_block_bio_queue
  - block/blk-core.c:__bpf_trace_block_bio_bounce
  - block/blk-core.c:__bpf_trace_block_rq
  - block/blk-core.c:__bpf_trace_block_rq_requeue
  - block/blk-wbt.c:__bpf_trace_wbt_lat
  - block/blk-wbt.c:__bpf_trace_wbt_stat
  - drivers/clk/clk.c:__bpf_trace_clk_duty_cycle
  - drivers/clk/clk.c:__bpf_trace_clk_phase
  - drivers/clk/clk.c:__bpf_trace_clk_parent
  - drivers/clk/clk.c:__bpf_trace_clk_rate
  - drivers/regulator/core.c:__bpf_trace_regulator_value
  - drivers/char/random.c:__bpf_trace_random__get_random_bytes
  - drivers/char/random.c:__bpf_trace_add_disk_randomness
  - drivers/char/random.c:__bpf_trace_debit_entropy
  - drivers/char/random.c:__bpf_trace_add_device_randomness
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool
  - drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error
  - drivers/spi/spi.c:__bpf_trace_spi_transfer
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb
  - drivers/rtc/interface.c:__bpf_trace_rtc_offset_class
  - drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:__bpf_trace_rtc_irq_set_state
  - drivers/rtc/interface.c:__bpf_trace_rtc_irq_set_freq
  - drivers/rtc/interface.c:__bpf_trace_rtc_time_alarm_class
  - drivers/thermal/thermal_core.c:__bpf_trace_cdev_update
  - drivers/mmc/core/core.c:__bpf_trace_mmc_request_done
  - drivers/mmc/core/core.c:__bpf_trace_mmc_request_start
  - net/core/net-traces.c:__bpf_trace_neigh__update
  - net/core/net-traces.c:__bpf_trace_fdb_delete
  - net/core/net-traces.c:__bpf_trace_tcp_probe
  - net/core/net-traces.c:__bpf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:__bpf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:__bpf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:__bpf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:__bpf_trace_net_dev_start_xmit
  - net/core/net-traces.c:__bpf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:__bpf_trace_kfree_skb
```
**Symbols:**

```
ffffffff811c1250-ffffffff811c12e6: bpf_trace_run2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_trace_run2(struct bpf_prog *prog, u64 arg0, u64 arg1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811cca00)
Location: kernel/trace/bpf_trace.c:1372
Inline: False
Direct callers:
  - init/main.c:__bpf_trace_initcall_finish
  - arch/x86/entry/common.c:__bpf_trace_sys_exit
  - arch/x86/entry/common.c:__bpf_trace_sys_enter
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_callback
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_entry
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_mmu_flush_tlb_others
  - arch/x86/kernel/irq.c:__bpf_trace_vector_reserve
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_l2
  - arch/x86/mm/init.c:__bpf_trace_tlb_flush
  - arch/x86/mm/mpx.c:__bpf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:__bpf_trace_mpx_bounds_register_exception
  - kernel/fork.c:__bpf_trace_task_rename
  - kernel/fork.c:__bpf_trace_task_newtask
  - kernel/softirq.c:__bpf_trace_irq_handler_entry
  - kernel/sched/core.c:__bpf_trace_sched_pi_setprio
  - kernel/sched/core.c:__bpf_trace_sched_stat_template
  - kernel/sched/core.c:__bpf_trace_sched_process_fork
  - kernel/sched/core.c:__bpf_trace_sched_migrate_task
  - kernel/printk/printk.c:__bpf_trace_console
  - kernel/irq/matrix.c:__bpf_trace_irq_matrix_global_update
  - kernel/time/timer.c:__bpf_trace_tick_stop
  - kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:__bpf_trace_hrtimer_start
  - kernel/time/timer.c:__bpf_trace_timer_expire_entry
  - kernel/time/alarmtimer.c:__bpf_trace_alarm_class
  - kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend
  - kernel/module.c:__bpf_trace_module_refcnt
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_request
  - kernel/trace/power-traces.c:__bpf_trace_wakeup_source
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:__bpf_trace_cpu
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal
  - kernel/bpf/core.c:__bpf_trace_mem_return_failed
  - kernel/bpf/core.c:__bpf_trace_mem_connect
  - mm/filemap.c:__bpf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:__bpf_trace_filemap_set_wb_err
  - mm/swap.c:__bpf_trace_mm_lru_insertion
  - mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/slab_common.c:__bpf_trace_mm_page_free
  - mm/slab_common.c:__bpf_trace_kmem_free
  - mm/compaction.c:__bpf_trace_mm_compaction_defer_template
  - fs/fs-writeback.c:__bpf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:__bpf_trace_global_dirty_state
  - fs/fs-writeback.c:__bpf_trace_wbc_class
  - fs/fs-writeback.c:__bpf_trace_writeback_work_class
  - fs/fs-writeback.c:__bpf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:__bpf_trace_track_foreign_dirty
  - fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:__bpf_trace_writeback_page_template
  - fs/locks.c:__bpf_trace_generic_add_lease
  - fs/locks.c:__bpf_trace_filelock_lease
  - fs/ext4/super.c:__bpf_trace_ext4_shutdown
  - fs/ext4/super.c:__bpf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:__bpf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:__bpf_trace_ext4_es_find_extent_range_enter
  - fs/ext4/super.c:__bpf_trace_ext4__es_extent
  - fs/ext4/super.c:__bpf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:__bpf_trace_ext4_unlink_exit
  - fs/ext4/super.c:__bpf_trace_ext4_unlink_enter
  - fs/ext4/super.c:__bpf_trace_ext4__bitmap_load
  - fs/ext4/super.c:__bpf_trace_ext4_da_release_space
  - fs/ext4/super.c:__bpf_trace_ext4_sync_fs
  - fs/ext4/super.c:__bpf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:__bpf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:__bpf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:__bpf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:__bpf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:__bpf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:__bpf_trace_ext4_writepages
  - fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:__bpf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:__bpf_trace_ext4_drop_inode
  - fs/ext4/super.c:__bpf_trace_ext4_request_inode
  - fs/ext4/super.c:__bpf_trace_ext4_other_inode_update_time
  - fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:__bpf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:__bpf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:__bpf_trace_jbd2_commit
  - fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint
  - block/blk-core.c:__bpf_trace_block_bio_queue
  - block/blk-core.c:__bpf_trace_block_bio_bounce
  - block/blk-core.c:__bpf_trace_block_rq
  - block/blk-core.c:__bpf_trace_block_rq_requeue
  - block/blk-wbt.c:__bpf_trace_wbt_lat
  - block/blk-wbt.c:__bpf_trace_wbt_stat
  - drivers/clk/clk.c:__bpf_trace_clk_duty_cycle
  - drivers/clk/clk.c:__bpf_trace_clk_phase
  - drivers/clk/clk.c:__bpf_trace_clk_parent
  - drivers/clk/clk.c:__bpf_trace_clk_rate
  - drivers/regulator/core.c:__bpf_trace_regulator_value
  - drivers/char/random.c:__bpf_trace_random__get_random_bytes
  - drivers/char/random.c:__bpf_trace_add_disk_randomness
  - drivers/char/random.c:__bpf_trace_debit_entropy
  - drivers/char/random.c:__bpf_trace_add_device_randomness
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool
  - drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error
  - drivers/spi/spi.c:__bpf_trace_spi_transfer
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb
  - drivers/rtc/interface.c:__bpf_trace_rtc_offset_class
  - drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:__bpf_trace_rtc_irq_set_state
  - drivers/rtc/interface.c:__bpf_trace_rtc_irq_set_freq
  - drivers/rtc/interface.c:__bpf_trace_rtc_time_alarm_class
  - drivers/thermal/thermal_core.c:__bpf_trace_cdev_update
  - drivers/mmc/core/core.c:__bpf_trace_mmc_request_done
  - drivers/mmc/core/core.c:__bpf_trace_mmc_request_start
  - net/core/net-traces.c:__bpf_trace_neigh__update
  - net/core/net-traces.c:__bpf_trace_fdb_delete
  - net/core/net-traces.c:__bpf_trace_tcp_probe
  - net/core/net-traces.c:__bpf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:__bpf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:__bpf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:__bpf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:__bpf_trace_net_dev_start_xmit
  - net/core/net-traces.c:__bpf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:__bpf_trace_kfree_skb
```
**Symbols:**

```
ffffffff811cca00-ffffffff811cca96: bpf_trace_run2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bpf_trace_run2(struct bpf_prog *prog, u64 arg0, u64 arg1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e8390)
Location: kernel/trace/bpf_trace.c:1866
Inline: False
Direct callers:
  - init/main.c:__bpf_trace_initcall_finish
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_callback
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_one
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_mmu_flush_tlb_others
  - arch/x86/kernel/irq.c:__bpf_trace_vector_reserve
  - arch/x86/mm/init.c:__bpf_trace_tlb_flush
  - kernel/fork.c:__bpf_trace_task_rename
  - kernel/fork.c:__bpf_trace_task_newtask
  - kernel/softirq.c:__bpf_trace_irq_handler_entry
  - kernel/workqueue.c:__bpf_trace_workqueue_execute_end
  - kernel/sched/core.c:__bpf_trace_sched_stat_template
  - kernel/sched/core.c:__bpf_trace_sched_migrate_task
  - kernel/printk/printk.c:__bpf_trace_console
  - kernel/irq/matrix.c:__bpf_trace_irq_matrix_global_update
  - kernel/time/timer.c:__bpf_trace_tick_stop
  - kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:__bpf_trace_hrtimer_start
  - kernel/time/timer.c:__bpf_trace_timer_expire_entry
  - kernel/time/alarmtimer.c:__bpf_trace_alarm_class
  - kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend
  - kernel/module.c:__bpf_trace_module_refcnt
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup
  - kernel/trace/power-traces.c:__bpf_trace_wakeup_source
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:__bpf_trace_cpu
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal
  - mm/swap.c:__bpf_trace_mm_lru_insertion
  - mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/slab_common.c:__bpf_trace_mm_page_free
  - mm/slab_common.c:__bpf_trace_kmem_free
  - mm/compaction.c:__bpf_trace_mm_compaction_defer_template
  - mm/mmap.c:__bpf_trace_vm_unmapped_area
  - fs/fs-writeback.c:__bpf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:__bpf_trace_global_dirty_state
  - fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template
  - fs/io_uring.c:__bpf_trace_io_uring_fail_link
  - fs/iomap/trace.c:__bpf_trace_iomap_class
  - fs/iomap/trace.c:__bpf_trace_iomap_readpage_class
  - fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate
  - fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall
  - block/blk-wbt.c:__bpf_trace_wbt_lat
  - block/blk-wbt.c:__bpf_trace_wbt_stat
  - drivers/pwm/core.c:__bpf_trace_pwm
  - drivers/clk/clk.c:__bpf_trace_clk_phase
  - drivers/clk/clk.c:__bpf_trace_clk_rate
  - drivers/regulator/core.c:__bpf_trace_regulator_value
  - drivers/char/random.c:__bpf_trace_add_disk_randomness
  - drivers/char/random.c:__bpf_trace_debit_entropy
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool
  - drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error
  - drivers/spi/spi.c:__bpf_trace_spi_transfer
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb
  - drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable
  - drivers/thermal/thermal_core.c:__bpf_trace_cdev_update
  - drivers/platform/chrome/cros_ec_trace.c:__bpf_trace_cros_ec_request_done
  - drivers/interconnect/core.c:__bpf_trace_icc_set_bw_end
  - net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb
```
**Symbols:**

```
ffffffff811e8390-ffffffff811e8426: bpf_trace_run2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_trace_run2(struct bpf_prog *prog, u64 arg0, u64 arg1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e7910)
Location: kernel/trace/bpf_trace.c:2122
Inline: False
Direct callers:
  - init/main.c:__bpf_trace_initcall_finish
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_callback
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_one
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_mmu_flush_tlb_others
  - arch/x86/kernel/irq.c:__bpf_trace_vector_reserve
  - arch/x86/mm/init.c:__bpf_trace_tlb_flush
  - kernel/fork.c:__bpf_trace_task_rename
  - kernel/fork.c:__bpf_trace_task_newtask
  - kernel/softirq.c:__bpf_trace_irq_handler_entry
  - kernel/workqueue.c:__bpf_trace_workqueue_execute_end
  - kernel/sched/core.c:__bpf_trace_sched_stat_template
  - kernel/sched/core.c:__bpf_trace_sched_migrate_task
  - kernel/sched/core.c:__bpf_trace_sched_kthread_work_execute_end
  - kernel/printk/printk.c:__bpf_trace_console
  - kernel/irq/matrix.c:__bpf_trace_irq_matrix_global_update
  - kernel/time/timer.c:__bpf_trace_tick_stop
  - kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:__bpf_trace_hrtimer_start
  - kernel/time/timer.c:__bpf_trace_timer_expire_entry
  - kernel/time/alarmtimer.c:__bpf_trace_alarm_class
  - kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend
  - kernel/module.c:__bpf_trace_module_refcnt
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup
  - kernel/trace/power-traces.c:__bpf_trace_wakeup_source
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:__bpf_trace_cpu
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal
  - mm/swap.c:__bpf_trace_mm_lru_insertion
  - mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/slab_common.c:__bpf_trace_mm_page_free
  - mm/slab_common.c:__bpf_trace_kmem_free
  - mm/compaction.c:__bpf_trace_mm_compaction_defer_template
  - mm/mmap.c:__bpf_trace_vm_unmapped_area
  - fs/fs-writeback.c:__bpf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:__bpf_trace_global_dirty_state
  - fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template
  - fs/io_uring.c:__bpf_trace_io_uring_fail_link
  - fs/iomap/trace.c:__bpf_trace_iomap_class
  - fs/iomap/trace.c:__bpf_trace_iomap_readpage_class
  - fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate
  - fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall
  - block/blk-core.c:__bpf_trace_block_split
  - block/blk-core.c:__bpf_trace_block_bio_complete
  - block/blk-wbt.c:__bpf_trace_wbt_lat
  - block/blk-wbt.c:__bpf_trace_wbt_stat
  - drivers/pwm/core.c:__bpf_trace_pwm
  - drivers/clk/clk.c:__bpf_trace_clk_phase
  - drivers/clk/clk.c:__bpf_trace_clk_rate
  - drivers/regulator/core.c:__bpf_trace_regulator_value
  - drivers/char/random.c:__bpf_trace_add_disk_randomness
  - drivers/char/random.c:__bpf_trace_debit_entropy
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool
  - drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error
  - drivers/spi/spi.c:__bpf_trace_spi_transfer
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb
  - drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable
  - drivers/thermal/thermal_core.c:__bpf_trace_cdev_update
  - drivers/platform/chrome/cros_ec_trace.c:__bpf_trace_cros_ec_request_done
  - drivers/interconnect/core.c:__bpf_trace_icc_set_bw_end
  - net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb
```
**Symbols:**

```
ffffffff811e7910-ffffffff811e79ab: bpf_trace_run2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_trace_run2(struct bpf_prog *prog, u64 arg0, u64 arg1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e8760)
Location: kernel/trace/bpf_trace.c:1818
Inline: False
Direct callers:
  - init/main.c:__bpf_trace_initcall_finish
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_callback
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_one
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_mmu_flush_tlb_multi
  - arch/x86/kernel/irq.c:__bpf_trace_vector_reserve
  - arch/x86/mm/init.c:__bpf_trace_tlb_flush
  - kernel/fork.c:__bpf_trace_task_rename
  - kernel/fork.c:__bpf_trace_task_newtask
  - kernel/softirq.c:__bpf_trace_irq_handler_entry
  - kernel/workqueue.c:__bpf_trace_workqueue_execute_end
  - kernel/sched/core.c:__bpf_trace_sched_overutilized_tp
  - kernel/sched/core.c:__bpf_trace_sched_stat_template
  - kernel/sched/core.c:__bpf_trace_sched_kthread_work_execute_end
  - kernel/printk/printk.c:__bpf_trace_console
  - kernel/irq/matrix.c:__bpf_trace_irq_matrix_global_update
  - kernel/rcu/update.c:__bpf_trace_rcu_stall_warning
  - kernel/time/timer.c:__bpf_trace_tick_stop
  - kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:__bpf_trace_hrtimer_start
  - kernel/time/timer.c:__bpf_trace_timer_expire_entry
  - kernel/time/alarmtimer.c:__bpf_trace_alarm_class
  - kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend
  - kernel/module.c:__bpf_trace_module_refcnt
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup
  - kernel/trace/error_report-traces.c:__bpf_trace_error_report_template
  - kernel/trace/power-traces.c:__bpf_trace_wakeup_source
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:__bpf_trace_cpu
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal
  - mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/slab_common.c:__bpf_trace_mm_page_free
  - mm/slab_common.c:__bpf_trace_kfree
  - mm/compaction.c:__bpf_trace_mm_compaction_defer_template
  - mm/mmap.c:__bpf_trace_vm_unmapped_area
  - mm/migrate.c:__bpf_trace_mm_migrate_pages_start
  - fs/fs-writeback.c:__bpf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:__bpf_trace_global_dirty_state
  - fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template
  - fs/io_uring.c:__bpf_trace_io_uring_fail_link
  - fs/iomap/trace.c:__bpf_trace_iomap_class
  - fs/iomap/trace.c:__bpf_trace_iomap_readpage_class
  - fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate
  - fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall
  - block/blk-core.c:__bpf_trace_block_split
  - block/blk-core.c:__bpf_trace_block_bio_complete
  - block/blk-wbt.c:__bpf_trace_wbt_lat
  - block/blk-wbt.c:__bpf_trace_wbt_stat
  - drivers/pwm/core.c:__bpf_trace_pwm
  - drivers/clk/clk.c:__bpf_trace_clk_phase
  - drivers/clk/clk.c:__bpf_trace_clk_rate
  - drivers/regulator/core.c:__bpf_trace_regulator_value
  - drivers/char/random.c:__bpf_trace_add_disk_randomness
  - drivers/char/random.c:__bpf_trace_debit_entropy
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool
  - drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error
  - drivers/spi/spi.c:__bpf_trace_spi_transfer
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb
  - drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable
  - drivers/thermal/thermal_core.c:__bpf_trace_cdev_update
  - drivers/platform/chrome/cros_ec_trace.c:__bpf_trace_cros_ec_request_done
  - drivers/interconnect/core.c:__bpf_trace_icc_set_bw_end
  - net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb
  - net/mptcp/protocol.c:__bpf_trace_subflow_check_data_avail
```
**Symbols:**

```
ffffffff811e8760-ffffffff811e87f4: bpf_trace_run2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_trace_run2(struct bpf_prog *prog, u64 arg0, u64 arg1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812193e0)
Location: kernel/trace/bpf_trace.c:1902
Inline: False
Direct callers:
  - init/main.c:__bpf_trace_initcall_finish
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_callback
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_one
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_mmu_flush_tlb_multi
  - arch/x86/kernel/irq.c:__bpf_trace_vector_reserve
  - arch/x86/mm/init.c:__bpf_trace_tlb_flush
  - kernel/fork.c:__bpf_trace_task_rename
  - kernel/fork.c:__bpf_trace_task_newtask
  - kernel/softirq.c:__bpf_trace_irq_handler_entry
  - kernel/workqueue.c:__bpf_trace_workqueue_execute_end
  - kernel/sched/core.c:__bpf_trace_sched_overutilized_tp
  - kernel/sched/core.c:__bpf_trace_sched_stat_template
  - kernel/sched/core.c:__bpf_trace_sched_kthread_work_execute_end
  - kernel/printk/printk.c:__bpf_trace_console
  - kernel/irq/matrix.c:__bpf_trace_irq_matrix_global_update
  - kernel/rcu/update.c:__bpf_trace_rcu_stall_warning
  - kernel/time/timer.c:__bpf_trace_tick_stop
  - kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:__bpf_trace_hrtimer_start
  - kernel/time/timer.c:__bpf_trace_timer_expire_entry
  - kernel/time/alarmtimer.c:__bpf_trace_alarm_class
  - kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend
  - kernel/module.c:__bpf_trace_module_refcnt
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup
  - kernel/trace/error_report-traces.c:__bpf_trace_error_report_template
  - kernel/trace/power-traces.c:__bpf_trace_wakeup_source
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:__bpf_trace_cpu
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal
  - mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/slab_common.c:__bpf_trace_mm_page_free
  - mm/slab_common.c:__bpf_trace_kfree
  - mm/compaction.c:__bpf_trace_mm_compaction_defer_template
  - mm/mmap.c:__bpf_trace_vm_unmapped_area
  - mm/migrate.c:__bpf_trace_mm_migrate_pages_start
  - fs/fs-writeback.c:__bpf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:__bpf_trace_global_dirty_state
  - fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template
  - fs/io_uring.c:__bpf_trace_io_uring_fail_link
  - fs/iomap/trace.c:__bpf_trace_iomap_class
  - fs/iomap/trace.c:__bpf_trace_iomap_readpage_class
  - fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate
  - fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall
  - block/blk-core.c:__bpf_trace_block_split
  - block/blk-core.c:__bpf_trace_block_bio_complete
  - block/blk-wbt.c:__bpf_trace_wbt_lat
  - block/blk-wbt.c:__bpf_trace_wbt_stat
  - drivers/pwm/core.c:__bpf_trace_pwm
  - drivers/clk/clk.c:__bpf_trace_clk_phase
  - drivers/clk/clk.c:__bpf_trace_clk_rate
  - drivers/regulator/core.c:__bpf_trace_regulator_value
  - drivers/char/random.c:__bpf_trace_add_disk_randomness
  - drivers/char/random.c:__bpf_trace_debit_entropy
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool
  - drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error
  - drivers/spi/spi.c:__bpf_trace_spi_transfer
  - drivers/spi/spi.c:__bpf_trace_spi_set_cs
  - drivers/spi/spi.c:__bpf_trace_spi_setup
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb
  - drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable
  - drivers/thermal/thermal_core.c:__bpf_trace_cdev_update
  - drivers/platform/chrome/cros_ec_trace.c:__bpf_trace_cros_ec_request_done
  - drivers/interconnect/core.c:__bpf_trace_icc_set_bw_end
  - net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb
  - net/mptcp/protocol.c:__bpf_trace_subflow_check_data_avail
```
**Symbols:**

```
ffffffff812193e0-ffffffff81219470: bpf_trace_run2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_trace_run2(struct bpf_prog *prog, u64 arg0, u64 arg1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81257c60)
Location: kernel/trace/bpf_trace.c:2083
Inline: False
Direct callers:
  - init/main.c:__bpf_trace_initcall_finish
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_callback
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_one
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_mmu_flush_tlb_multi
  - arch/x86/kernel/irq.c:__bpf_trace_vector_reserve
  - kernel/fork.c:__bpf_trace_task_rename
  - kernel/fork.c:__bpf_trace_task_newtask
  - kernel/softirq.c:__bpf_trace_irq_handler_entry
  - kernel/workqueue.c:__bpf_trace_workqueue_execute_end
  - kernel/sched/core.c:__bpf_trace_sched_overutilized_tp
  - kernel/sched/core.c:__bpf_trace_sched_stat_template
  - kernel/sched/core.c:__bpf_trace_sched_kthread_work_execute_end
  - kernel/locking/mutex.c:__bpf_trace_contention_end
  - kernel/locking/mutex.c:__bpf_trace_contention_begin
  - kernel/printk/printk.c:__bpf_trace_console
  - kernel/irq/matrix.c:__bpf_trace_irq_matrix_global_update
  - kernel/rcu/update.c:__bpf_trace_rcu_stall_warning
  - kernel/module/main.c:__bpf_trace_module_refcnt
  - kernel/time/timer.c:__bpf_trace_tick_stop
  - kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:__bpf_trace_hrtimer_start
  - kernel/time/timer.c:__bpf_trace_timer_expire_entry
  - kernel/time/alarmtimer.c:__bpf_trace_alarm_class
  - kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup
  - kernel/trace/error_report-traces.c:__bpf_trace_error_report_template
  - kernel/trace/power-traces.c:__bpf_trace_wakeup_source
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:__bpf_trace_cpu
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal
  - mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/slab_common.c:__bpf_trace_mm_page_free
  - mm/slab_common.c:__bpf_trace_kfree
  - mm/compaction.c:__bpf_trace_mm_compaction_defer_template
  - mm/compaction.c:__bpf_trace_mm_compaction_migratepages
  - mm/mmap.c:__bpf_trace_vm_unmapped_area
  - mm/rmap.c:__bpf_trace_mm_migrate_pages_start
  - mm/rmap.c:__bpf_trace_tlb_flush
  - fs/fs-writeback.c:__bpf_trace_global_dirty_state
  - fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template
  - fs/iomap/trace.c:__bpf_trace_iomap_class
  - fs/iomap/trace.c:__bpf_trace_iomap_readpage_class
  - fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate
  - fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall
  - block/blk-core.c:__bpf_trace_block_split
  - block/blk-core.c:__bpf_trace_block_bio_complete
  - block/blk-wbt.c:__bpf_trace_wbt_lat
  - block/blk-wbt.c:__bpf_trace_wbt_stat
  - io_uring/io_uring.c:__bpf_trace_io_uring_cqring_wait
  - drivers/pwm/core.c:__bpf_trace_pwm
  - drivers/clk/clk.c:__bpf_trace_clk_phase
  - drivers/clk/clk.c:__bpf_trace_clk_rate
  - drivers/regulator/core.c:__bpf_trace_regulator_value
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool
  - drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error
  - drivers/ata/libata-core.c:__bpf_trace_ata_sff_hsm_template
  - drivers/ata/libata-core.c:__bpf_trace_ata_bmdma_status
  - drivers/ata/libata-core.c:__bpf_trace_ata_tf_load
  - drivers/spi/spi.c:__bpf_trace_spi_transfer
  - drivers/spi/spi.c:__bpf_trace_spi_set_cs
  - drivers/spi/spi.c:__bpf_trace_spi_setup
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb
  - drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable
  - drivers/thermal/thermal_core.c:__bpf_trace_cdev_update
  - drivers/platform/chrome/cros_ec_trace.c:__bpf_trace_cros_ec_request_done
  - drivers/interconnect/core.c:__bpf_trace_icc_set_bw_end
  - net/core/net-traces.c:__bpf_trace_tcp_cong_state_set
  - net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb
  - net/mptcp/protocol.c:__bpf_trace_subflow_check_data_avail
  - net/mctp/af_mctp.c:__bpf_trace_mctp_key_release
```
**Symbols:**

```
ffffffff81257c60-ffffffff81257d01: bpf_trace_run2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_trace_run2(struct bpf_prog *prog, u64 arg0, u64 arg1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a7300)
Location: kernel/trace/bpf_trace.c:2306
Inline: False
Direct callers:
  - init/main.c:__bpf_trace_initcall_finish
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_callback
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_one
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_mmu_flush_tlb_multi
  - arch/x86/kernel/irq.c:__bpf_trace_vector_reserve
  - kernel/fork.c:__bpf_trace_task_rename
  - kernel/fork.c:__bpf_trace_task_newtask
  - kernel/softirq.c:__bpf_trace_irq_handler_entry
  - kernel/workqueue.c:__bpf_trace_workqueue_execute_end
  - kernel/sched/core.c:__bpf_trace_sched_overutilized_tp
  - kernel/sched/core.c:__bpf_trace_sched_stat_template
  - kernel/sched/core.c:__bpf_trace_sched_kthread_work_execute_end
  - kernel/locking/mutex.c:__bpf_trace_contention_end
  - kernel/locking/mutex.c:__bpf_trace_contention_begin
  - kernel/printk/printk.c:__bpf_trace_console
  - kernel/irq/matrix.c:__bpf_trace_irq_matrix_global_update
  - kernel/rcu/update.c:__bpf_trace_rcu_stall_warning
  - kernel/module/main.c:__bpf_trace_module_refcnt
  - kernel/time/timer.c:__bpf_trace_tick_stop
  - kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:__bpf_trace_hrtimer_start
  - kernel/time/timer.c:__bpf_trace_timer_expire_entry
  - kernel/time/alarmtimer.c:__bpf_trace_alarm_class
  - kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup
  - kernel/trace/error_report-traces.c:__bpf_trace_error_report_template
  - kernel/trace/power-traces.c:__bpf_trace_wakeup_source
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:__bpf_trace_cpu
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal
  - mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/slab_common.c:__bpf_trace_rss_stat
  - mm/slab_common.c:__bpf_trace_mm_page_free
  - mm/slab_common.c:__bpf_trace_kfree
  - mm/compaction.c:__bpf_trace_mm_compaction_defer_template
  - mm/compaction.c:__bpf_trace_mm_compaction_migratepages
  - mm/mmap.c:__bpf_trace_vma_store
  - mm/mmap.c:__bpf_trace_vm_unmapped_area
  - mm/rmap.c:__bpf_trace_mm_migrate_pages_start
  - mm/rmap.c:__bpf_trace_tlb_flush
  - fs/fs-writeback.c:__bpf_trace_global_dirty_state
  - fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template
  - fs/iomap/trace.c:__bpf_trace_iomap_class
  - fs/iomap/trace.c:__bpf_trace_iomap_readpage_class
  - fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate
  - fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:__bpf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint
  - block/blk-core.c:__bpf_trace_block_split
  - block/blk-core.c:__bpf_trace_block_bio_complete
  - block/blk-wbt.c:__bpf_trace_wbt_lat
  - block/blk-wbt.c:__bpf_trace_wbt_stat
  - io_uring/io_uring.c:__bpf_trace_io_uring_submit_sqe
  - drivers/clk/clk.c:__bpf_trace_clk_phase
  - drivers/clk/clk.c:__bpf_trace_clk_rate
  - drivers/regulator/core.c:__bpf_trace_regulator_value
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool
  - drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error
  - drivers/ata/libata-core.c:__bpf_trace_ata_sff_hsm_template
  - drivers/ata/libata-core.c:__bpf_trace_ata_bmdma_status
  - drivers/ata/libata-core.c:__bpf_trace_ata_tf_load
  - drivers/spi/spi.c:__bpf_trace_spi_transfer
  - drivers/spi/spi.c:__bpf_trace_spi_set_cs
  - drivers/spi/spi.c:__bpf_trace_spi_setup
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb
  - drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable
  - drivers/thermal/thermal_core.c:__bpf_trace_cdev_update
  - drivers/watchdog/watchdog_core.c:__bpf_trace_watchdog_template
  - drivers/platform/chrome/cros_ec_trace.c:__bpf_trace_cros_ec_request_done
  - drivers/interconnect/core.c:__bpf_trace_icc_set_bw_end
  - net/core/net-traces.c:__bpf_trace_tcp_cong_state_set
  - net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb
  - net/mptcp/protocol.c:__bpf_trace_subflow_check_data_avail
  - net/mctp/af_mctp.c:__bpf_trace_mctp_key_release
```
**Symbols:**

```
ffffffff812a7300-ffffffff812a73ca: bpf_trace_run2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_trace_run2(struct bpf_prog *prog, u64 arg0, u64 arg1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812c9590)
Location: kernel/trace/bpf_trace.c:2315
Inline: False
Direct callers:
  - init/main.c:__bpf_trace_initcall_finish
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_callback
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_one
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_mmu_flush_tlb_multi
  - arch/x86/kernel/irq.c:__bpf_trace_vector_reserve
  - kernel/fork.c:__bpf_trace_task_rename
  - kernel/fork.c:__bpf_trace_task_newtask
  - kernel/softirq.c:__bpf_trace_tasklet
  - kernel/softirq.c:__bpf_trace_irq_handler_entry
  - kernel/workqueue.c:__bpf_trace_workqueue_execute_end
  - kernel/sched/core.c:__bpf_trace_sched_overutilized_tp
  - kernel/sched/core.c:__bpf_trace_sched_stat_template
  - kernel/sched/core.c:__bpf_trace_sched_kthread_work_execute_end
  - kernel/locking/mutex.c:__bpf_trace_contention_end
  - kernel/locking/mutex.c:__bpf_trace_contention_begin
  - kernel/printk/printk.c:__bpf_trace_console
  - kernel/irq/matrix.c:__bpf_trace_irq_matrix_global_update
  - kernel/rcu/update.c:__bpf_trace_rcu_stall_warning
  - kernel/module/main.c:__bpf_trace_module_refcnt
  - kernel/time/timer.c:__bpf_trace_tick_stop
  - kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:__bpf_trace_hrtimer_start
  - kernel/time/timer.c:__bpf_trace_timer_expire_entry
  - kernel/time/alarmtimer.c:__bpf_trace_alarm_class
  - kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend
  - kernel/smp.c:__bpf_trace_csd_function
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup
  - kernel/trace/trace_osnoise.c:__bpf_trace_nmi_noise
  - kernel/trace/error_report-traces.c:__bpf_trace_error_report_template
  - kernel/trace/power-traces.c:__bpf_trace_wakeup_source
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:__bpf_trace_cpu
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal
  - mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/slab_common.c:__bpf_trace_rss_stat
  - mm/slab_common.c:__bpf_trace_mm_page_free
  - mm/slab_common.c:__bpf_trace_kfree
  - mm/compaction.c:__bpf_trace_mm_compaction_defer_template
  - mm/compaction.c:__bpf_trace_mm_compaction_migratepages
  - mm/mmap.c:__bpf_trace_vma_store
  - mm/mmap.c:__bpf_trace_vm_unmapped_area
  - mm/rmap.c:__bpf_trace_mm_migrate_pages_start
  - mm/rmap.c:__bpf_trace_tlb_flush
  - mm/ksm.c:__bpf_trace_ksm_scan_template
  - fs/fs-writeback.c:__bpf_trace_global_dirty_state
  - fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template
  - fs/iomap/trace.c:__bpf_trace_iomap_class
  - fs/iomap/trace.c:__bpf_trace_iomap_readpage_class
  - fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate
  - fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:__bpf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint
  - block/blk-core.c:__bpf_trace_block_split
  - block/blk-core.c:__bpf_trace_block_bio_complete
  - block/blk-wbt.c:__bpf_trace_wbt_lat
  - block/blk-wbt.c:__bpf_trace_wbt_stat
  - drivers/clk/clk.c:__bpf_trace_clk_phase
  - drivers/clk/clk.c:__bpf_trace_clk_rate
  - drivers/regulator/core.c:__bpf_trace_regulator_value
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool
  - drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error
  - drivers/ata/libata-core.c:__bpf_trace_ata_sff_hsm_template
  - drivers/ata/libata-core.c:__bpf_trace_ata_bmdma_status
  - drivers/ata/libata-core.c:__bpf_trace_ata_tf_load
  - drivers/spi/spi.c:__bpf_trace_spi_transfer
  - drivers/spi/spi.c:__bpf_trace_spi_set_cs
  - drivers/spi/spi.c:__bpf_trace_spi_setup
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb
  - drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable
  - drivers/thermal/thermal_core.c:__bpf_trace_cdev_update
  - drivers/watchdog/watchdog_core.c:__bpf_trace_watchdog_template
  - drivers/platform/chrome/cros_ec_trace.c:__bpf_trace_cros_ec_request_done
  - drivers/interconnect/core.c:__bpf_trace_icc_set_bw_end
  - net/core/net-traces.c:__bpf_trace_tcp_cong_state_set
  - net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb
  - net/mptcp/protocol.c:__bpf_trace_subflow_check_data_avail
  - net/mctp/af_mctp.c:__bpf_trace_mctp_key_release
```
**Symbols:**

```
ffffffff812c9590-ffffffff812c965a: bpf_trace_run2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_trace_run2(struct bpf_prog *prog, u64 arg0, u64 arg1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e6f40)
Location: kernel/trace/bpf_trace.c:2420
Inline: False
Direct callers:
  - init/main.c:__bpf_trace_initcall_finish
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_callback
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_one
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_mmu_flush_tlb_multi
  - arch/x86/kernel/irq.c:__bpf_trace_vector_reserve
  - kernel/fork.c:__bpf_trace_task_rename
  - kernel/fork.c:__bpf_trace_task_newtask
  - kernel/softirq.c:__bpf_trace_tasklet
  - kernel/softirq.c:__bpf_trace_irq_handler_entry
  - kernel/workqueue.c:__bpf_trace_workqueue_execute_end
  - kernel/sched/core.c:__bpf_trace_sched_overutilized_tp
  - kernel/sched/core.c:__bpf_trace_sched_kthread_work_execute_end
  - kernel/locking/mutex.c:__bpf_trace_contention_end
  - kernel/locking/mutex.c:__bpf_trace_contention_begin
  - kernel/printk/printk.c:__bpf_trace_console
  - kernel/irq/matrix.c:__bpf_trace_irq_matrix_global_update
  - kernel/rcu/update.c:__bpf_trace_rcu_stall_warning
  - kernel/module/main.c:__bpf_trace_module_refcnt
  - kernel/time/timer.c:__bpf_trace_tick_stop
  - kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:__bpf_trace_hrtimer_start
  - kernel/time/timer.c:__bpf_trace_timer_base_idle
  - kernel/time/alarmtimer.c:__bpf_trace_alarm_class
  - kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend
  - kernel/smp.c:__bpf_trace_csd_function
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup
  - kernel/trace/trace_osnoise.c:__bpf_trace_nmi_noise
  - kernel/trace/error_report-traces.c:__bpf_trace_error_report_template
  - kernel/trace/power-traces.c:__bpf_trace_wakeup_source
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:__bpf_trace_cpu
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal
  - mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/slab_common.c:__bpf_trace_rss_stat
  - mm/slab_common.c:__bpf_trace_mm_page_free
  - mm/slab_common.c:__bpf_trace_kfree
  - mm/compaction.c:__bpf_trace_mm_compaction_defer_template
  - mm/compaction.c:__bpf_trace_mm_compaction_migratepages
  - mm/mmap.c:__bpf_trace_vma_store
  - mm/mmap.c:__bpf_trace_vm_unmapped_area
  - mm/rmap.c:__bpf_trace_mm_migrate_pages_start
  - mm/rmap.c:__bpf_trace_tlb_flush
  - mm/ksm.c:__bpf_trace_ksm_scan_template
  - fs/fs-writeback.c:__bpf_trace_global_dirty_state
  - fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template
  - fs/iomap/trace.c:__bpf_trace_iomap_class
  - fs/iomap/trace.c:__bpf_trace_iomap_readpage_class
  - fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate
  - fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:__bpf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint
  - block/blk-core.c:__bpf_trace_block_split
  - block/blk-core.c:__bpf_trace_block_bio_complete
  - block/blk-wbt.c:__bpf_trace_wbt_lat
  - block/blk-wbt.c:__bpf_trace_wbt_stat
  - drivers/clk/clk.c:__bpf_trace_clk_phase
  - drivers/clk/clk.c:__bpf_trace_clk_rate
  - drivers/regulator/core.c:__bpf_trace_regulator_value
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool
  - drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error
  - drivers/ata/libata-core.c:__bpf_trace_ata_sff_hsm_template
  - drivers/ata/libata-core.c:__bpf_trace_ata_bmdma_status
  - drivers/ata/libata-core.c:__bpf_trace_ata_tf_load
  - drivers/spi/spi.c:__bpf_trace_spi_transfer
  - drivers/spi/spi.c:__bpf_trace_spi_set_cs
  - drivers/spi/spi.c:__bpf_trace_spi_setup
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_doorbell
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb
  - drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable
  - drivers/thermal/thermal_core.c:__bpf_trace_cdev_update
  - drivers/watchdog/watchdog_core.c:__bpf_trace_watchdog_template
  - drivers/platform/chrome/cros_ec_trace.c:__bpf_trace_cros_ec_request_done
  - drivers/interconnect/core.c:__bpf_trace_icc_set_bw_end
  - net/core/net-traces.c:__bpf_trace_tcp_cong_state_set
  - net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb
  - net/mptcp/protocol.c:__bpf_trace_subflow_check_data_avail
  - net/mctp/af_mctp.c:__bpf_trace_mctp_key_release
  - net/handshake/trace.c:__bpf_trace_tls_contenttype
```
**Symbols:**

```
ffffffff812e6f40-ffffffff812e700a: bpf_trace_run2 (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void bpf_trace_run2(struct bpf_prog *prog, u64 arg0, u64 arg1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffff80001024dde8)
Location: kernel/trace/bpf_trace.c:1372
Inline: False
Direct callers:
  - init/main.c:__bpf_trace_initcall_finish
  - arch/arm64/kernel/smp.c:__bpf_trace_ipi_raise
  - arch/arm64/kernel/armv8_deprecated.c:__bpf_trace_instruction_emulation
  - virt/kvm/kvm_main.c:__bpf_trace_kvm_ack_irq
  - virt/kvm/kvm_main.c:__bpf_trace_kvm_userspace_exit
  - virt/kvm/arm/arm.c:__bpf_trace_kvm_timer_emulate
  - virt/kvm/arm/arm.c:__bpf_trace_kvm_get_timer_map
  - virt/kvm/arm/arm.c:__bpf_trace_kvm_set_way_flush
  - arch/arm64/kvm/handle_exit.c:__bpf_trace_kvm_arm_set_dreg32
  - arch/arm64/kvm/handle_exit.c:__bpf_trace_kvm_wfx_arm64
  - kernel/fork.c:__bpf_trace_task_rename
  - kernel/fork.c:__bpf_trace_task_newtask
  - kernel/softirq.c:__bpf_trace_irq_handler_entry
  - kernel/sched/core.c:__bpf_trace_sched_stat_template
  - kernel/sched/core.c:__bpf_trace_sched_migrate_task
  - kernel/printk/printk.c:__bpf_trace_console
  - kernel/time/timer.c:__bpf_trace_tick_stop
  - kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:__bpf_trace_hrtimer_start
  - kernel/time/timer.c:__bpf_trace_timer_expire_entry
  - kernel/time/alarmtimer.c:__bpf_trace_alarm_class
  - kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend
  - kernel/module.c:__bpf_trace_module_refcnt
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_request
  - kernel/trace/power-traces.c:__bpf_trace_wakeup_source
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:__bpf_trace_cpu
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal
  - kernel/bpf/core.c:__bpf_trace_mem_return_failed
  - kernel/bpf/core.c:__bpf_trace_mem_connect
  - mm/filemap.c:__bpf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:__bpf_trace_filemap_set_wb_err
  - mm/swap.c:__bpf_trace_mm_lru_insertion
  - mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/slab_common.c:__bpf_trace_mm_page_free
  - mm/slab_common.c:__bpf_trace_kmem_free
  - mm/compaction.c:__bpf_trace_mm_compaction_defer_template
  - fs/fs-writeback.c:__bpf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:__bpf_trace_global_dirty_state
  - fs/fs-writeback.c:__bpf_trace_wbc_class
  - fs/fs-writeback.c:__bpf_trace_writeback_work_class
  - fs/fs-writeback.c:__bpf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:__bpf_trace_track_foreign_dirty
  - fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:__bpf_trace_writeback_page_template
  - fs/ext4/super.c:__bpf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:__bpf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:__bpf_trace_ext4_unlink_exit
  - fs/ext4/super.c:__bpf_trace_ext4_unlink_enter
  - fs/ext4/super.c:__bpf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:__bpf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:__bpf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:__bpf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:__bpf_trace_ext4_writepages
  - fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate
  - fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall
  - block/blk-wbt.c:__bpf_trace_wbt_lat
  - block/blk-wbt.c:__bpf_trace_wbt_stat
  - drivers/clk/clk.c:__bpf_trace_clk_duty_cycle
  - drivers/clk/clk.c:__bpf_trace_clk_phase
  - drivers/clk/clk.c:__bpf_trace_clk_parent
  - drivers/clk/clk.c:__bpf_trace_clk_rate
  - drivers/regulator/core.c:__bpf_trace_regulator_value
  - drivers/char/random.c:__bpf_trace_add_disk_randomness
  - drivers/char/random.c:__bpf_trace_debit_entropy
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool
  - drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error
  - drivers/spi/spi.c:__bpf_trace_spi_transfer
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb
  - drivers/rtc/interface.c:__bpf_trace_rtc_offset_class
  - drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:__bpf_trace_rtc_time_alarm_class
  - drivers/thermal/thermal_core.c:__bpf_trace_cdev_update
  - net/core/net-traces.c:__bpf_trace_neigh__update
  - net/core/net-traces.c:__bpf_trace_fdb_delete
  - net/core/net-traces.c:__bpf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:__bpf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:__bpf_trace_net_dev_start_xmit
  - net/core/net-traces.c:__bpf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:__bpf_trace_kfree_skb
```
**Symbols:**

```
ffff80001024dde8-ffff80001024de9c: bpf_trace_run2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_trace_run2(struct bpf_prog *prog, u64 arg0, u64 arg1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c047ed58)
Location: kernel/trace/bpf_trace.c:1372
Inline: False
Direct callers:
  - init/main.c:__bpf_trace_initcall_finish
  - arch/arm/kernel/ptrace.c:__bpf_trace_sys_enter
  - arch/arm/kernel/smp.c:__bpf_trace_ipi_raise
  - arch/arm/common/bL_switcher.c:__bpf_trace_cpu_migrate
  - kernel/fork.c:__bpf_trace_task_rename
  - kernel/fork.c:__bpf_trace_task_newtask
  - kernel/softirq.c:__bpf_trace_irq_handler_entry
  - kernel/sched/core.c:__bpf_trace_sched_stat_template
  - kernel/sched/core.c:__bpf_trace_sched_process_fork
  - kernel/sched/core.c:__bpf_trace_sched_migrate_task
  - kernel/printk/printk.c:__bpf_trace_console
  - kernel/time/timer.c:__bpf_trace_tick_stop
  - kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:__bpf_trace_hrtimer_start
  - kernel/time/timer.c:__bpf_trace_timer_expire_entry
  - kernel/time/alarmtimer.c:__bpf_trace_alarm_class
  - kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend
  - kernel/module.c:__bpf_trace_module_refcnt
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_request
  - kernel/trace/power-traces.c:__bpf_trace_wakeup_source
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:__bpf_trace_cpu
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal
  - kernel/bpf/core.c:__bpf_trace_mem_return_failed
  - kernel/bpf/core.c:__bpf_trace_mem_connect
  - mm/filemap.c:__bpf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:__bpf_trace_filemap_set_wb_err
  - mm/swap.c:__bpf_trace_mm_lru_insertion
  - mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/slab_common.c:__bpf_trace_mm_page_free
  - mm/slab_common.c:__bpf_trace_kmem_free
  - mm/compaction.c:__bpf_trace_mm_compaction_defer_template
  - fs/fs-writeback.c:__bpf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:__bpf_trace_global_dirty_state
  - fs/fs-writeback.c:__bpf_trace_wbc_class
  - fs/fs-writeback.c:__bpf_trace_writeback_work_class
  - fs/fs-writeback.c:__bpf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:__bpf_trace_track_foreign_dirty
  - fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:__bpf_trace_writeback_page_template
  - fs/locks.c:__bpf_trace_filelock_lease
  - fs/ext4/super.c:__bpf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:__bpf_trace_ext4_es_find_extent_range_enter
  - fs/ext4/super.c:__bpf_trace_ext4__es_extent
  - fs/ext4/super.c:__bpf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:__bpf_trace_ext4_unlink_exit
  - fs/ext4/super.c:__bpf_trace_ext4_unlink_enter
  - fs/ext4/super.c:__bpf_trace_ext4__bitmap_load
  - fs/ext4/super.c:__bpf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:__bpf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:__bpf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:__bpf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:__bpf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:__bpf_trace_ext4_writepages
  - fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:__bpf_trace_ext4_request_inode
  - fs/ext4/super.c:__bpf_trace_ext4_other_inode_update_time
  - fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:__bpf_trace_jbd2_commit
  - fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint
  - block/blk-core.c:__bpf_trace_block_bio_bounce
  - block/blk-core.c:__bpf_trace_block_rq_requeue
  - block/blk-wbt.c:__bpf_trace_wbt_lat
  - block/blk-wbt.c:__bpf_trace_wbt_stat
  - drivers/clk/clk.c:__bpf_trace_clk_duty_cycle
  - drivers/clk/clk.c:__bpf_trace_clk_phase
  - drivers/clk/clk.c:__bpf_trace_clk_parent
  - drivers/clk/clk.c:__bpf_trace_clk_rate
  - drivers/dma/tegra20-apb-dma.c:__bpf_trace_tegra_dma_isr
  - drivers/regulator/core.c:__bpf_trace_regulator_value
  - drivers/char/random.c:__bpf_trace_add_disk_randomness
  - drivers/char/random.c:__bpf_trace_debit_entropy
  - drivers/char/random.c:__bpf_trace_add_device_randomness
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool
  - drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error
  - drivers/spi/spi.c:__bpf_trace_spi_transfer
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb
  - drivers/usb/musb/musb_trace.c:__bpf_trace_musb_urb
  - drivers/usb/musb/musb_trace.c:__bpf_trace_musb_log
  - drivers/usb/gadget/udc/trace.c:__bpf_trace_udc_log_ep
  - drivers/usb/gadget/udc/trace.c:__bpf_trace_udc_log_gadget
  - drivers/rtc/interface.c:__bpf_trace_rtc_offset_class
  - drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:__bpf_trace_rtc_irq_set_freq
  - drivers/rtc/interface.c:__bpf_trace_rtc_time_alarm_class
  - drivers/thermal/thermal_core.c:__bpf_trace_cdev_update
  - drivers/mmc/core/core.c:__bpf_trace_mmc_request_start
  - sound/soc/soc-core.c:__bpf_trace_snd_soc_jack_notify
  - sound/soc/soc-core.c:__bpf_trace_snd_soc_dapm_connected
  - sound/soc/soc-core.c:__bpf_trace_snd_soc_dapm_widget
  - sound/soc/soc-core.c:__bpf_trace_snd_soc_card
  - net/core/net-traces.c:__bpf_trace_neigh__update
  - net/core/net-traces.c:__bpf_trace_fdb_delete
  - net/core/net-traces.c:__bpf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:__bpf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:__bpf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:__bpf_trace_net_dev_start_xmit
  - net/core/net-traces.c:__bpf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:__bpf_trace_kfree_skb
```
**Symbols:**

```
c047ed58-c047ee68: bpf_trace_run2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_trace_run2(struct bpf_prog *prog, u64 arg0, u64 arg1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0000000002e7bb0)
Location: kernel/trace/bpf_trace.c:1372
Inline: False
Direct callers:
  - init/main.c:__bpf_trace_initcall_finish
  - arch/powerpc/kernel/ptrace.c:__bpf_trace_sys_exit
  - arch/powerpc/kernel/ptrace.c:__bpf_trace_sys_enter
  - arch/powerpc/kernel/irq.c:__bpf_trace_opal_exit
  - arch/powerpc/kernel/irq.c:__bpf_trace_opal_entry
  - arch/powerpc/kernel/irq.c:__bpf_trace_hcall_entry
  - arch/powerpc/mm/book3s64/hash_pgtable.c:__bpf_trace_hugepage_splitting
  - arch/powerpc/mm/book3s64/hash_pgtable.c:__bpf_trace_hugepage_set_pmd
  - arch/powerpc/mm/book3s64/hash_pgtable.c:__bpf_trace_hugepage_invalidate
  - arch/powerpc/platforms/powernv/vas-window.c:__bpf_trace_vas_paste_crb
  - kernel/fork.c:__bpf_trace_task_rename
  - kernel/fork.c:__bpf_trace_task_newtask
  - kernel/softirq.c:__bpf_trace_irq_handler_entry
  - kernel/sched/core.c:__bpf_trace_sched_pi_setprio
  - kernel/sched/core.c:__bpf_trace_sched_stat_template
  - kernel/sched/core.c:__bpf_trace_sched_process_fork
  - kernel/sched/core.c:__bpf_trace_sched_migrate_task
  - kernel/printk/printk.c:__bpf_trace_console
  - kernel/time/timer.c:__bpf_trace_tick_stop
  - kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:__bpf_trace_hrtimer_start
  - kernel/time/timer.c:__bpf_trace_timer_expire_entry
  - kernel/time/alarmtimer.c:__bpf_trace_alarm_class
  - kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend
  - kernel/module.c:__bpf_trace_module_refcnt
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_request
  - kernel/trace/power-traces.c:__bpf_trace_wakeup_source
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:__bpf_trace_cpu
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal
  - kernel/bpf/core.c:__bpf_trace_mem_return_failed
  - kernel/bpf/core.c:__bpf_trace_mem_connect
  - mm/filemap.c:__bpf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:__bpf_trace_filemap_set_wb_err
  - mm/swap.c:__bpf_trace_mm_lru_insertion
  - mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/slab_common.c:__bpf_trace_mm_page_free
  - mm/slab_common.c:__bpf_trace_kmem_free
  - mm/compaction.c:__bpf_trace_mm_compaction_defer_template
  - fs/fs-writeback.c:__bpf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:__bpf_trace_global_dirty_state
  - fs/fs-writeback.c:__bpf_trace_wbc_class
  - fs/fs-writeback.c:__bpf_trace_writeback_work_class
  - fs/fs-writeback.c:__bpf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:__bpf_trace_track_foreign_dirty
  - fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:__bpf_trace_writeback_page_template
  - fs/locks.c:__bpf_trace_generic_add_lease
  - fs/locks.c:__bpf_trace_filelock_lease
  - fs/ext4/super.c:__bpf_trace_ext4_shutdown
  - fs/ext4/super.c:__bpf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:__bpf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:__bpf_trace_ext4_es_find_extent_range_enter
  - fs/ext4/super.c:__bpf_trace_ext4__es_extent
  - fs/ext4/super.c:__bpf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:__bpf_trace_ext4_unlink_exit
  - fs/ext4/super.c:__bpf_trace_ext4_unlink_enter
  - fs/ext4/super.c:__bpf_trace_ext4__bitmap_load
  - fs/ext4/super.c:__bpf_trace_ext4_da_release_space
  - fs/ext4/super.c:__bpf_trace_ext4_sync_fs
  - fs/ext4/super.c:__bpf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:__bpf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:__bpf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:__bpf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:__bpf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:__bpf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:__bpf_trace_ext4_writepages
  - fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:__bpf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:__bpf_trace_ext4_drop_inode
  - fs/ext4/super.c:__bpf_trace_ext4_request_inode
  - fs/ext4/super.c:__bpf_trace_ext4_other_inode_update_time
  - fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:__bpf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:__bpf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:__bpf_trace_jbd2_commit
  - fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint
  - block/blk-core.c:__bpf_trace_block_bio_queue
  - block/blk-core.c:__bpf_trace_block_bio_bounce
  - block/blk-core.c:__bpf_trace_block_rq
  - block/blk-core.c:__bpf_trace_block_rq_requeue
  - block/blk-wbt.c:__bpf_trace_wbt_lat
  - block/blk-wbt.c:__bpf_trace_wbt_stat
  - drivers/regulator/core.c:__bpf_trace_regulator_value
  - drivers/char/random.c:__bpf_trace_random__get_random_bytes
  - drivers/char/random.c:__bpf_trace_add_disk_randomness
  - drivers/char/random.c:__bpf_trace_debit_entropy
  - drivers/char/random.c:__bpf_trace_add_device_randomness
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool
  - drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error
  - drivers/spi/spi.c:__bpf_trace_spi_transfer
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb
  - drivers/rtc/interface.c:__bpf_trace_rtc_offset_class
  - drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:__bpf_trace_rtc_irq_set_state
  - drivers/rtc/interface.c:__bpf_trace_rtc_irq_set_freq
  - drivers/rtc/interface.c:__bpf_trace_rtc_time_alarm_class
  - drivers/thermal/thermal_core.c:__bpf_trace_cdev_update
  - drivers/mmc/core/core.c:__bpf_trace_mmc_request_done
  - drivers/mmc/core/core.c:__bpf_trace_mmc_request_start
  - net/core/net-traces.c:__bpf_trace_neigh__update
  - net/core/net-traces.c:__bpf_trace_fdb_delete
  - net/core/net-traces.c:__bpf_trace_tcp_probe
  - net/core/net-traces.c:__bpf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:__bpf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:__bpf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:__bpf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:__bpf_trace_net_dev_start_xmit
  - net/core/net-traces.c:__bpf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:__bpf_trace_kfree_skb
```
**Symbols:**

```
c0000000002e7bb0-c0000000002e7ca0: bpf_trace_run2 (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void bpf_trace_run2(struct bpf_prog *prog, u64 arg0, u64 arg1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c5020)
Location: kernel/trace/bpf_trace.c:1372
Inline: False
Direct callers:
  - init/main.c:__bpf_trace_initcall_finish
  - arch/x86/entry/common.c:__bpf_trace_sys_exit
  - arch/x86/entry/common.c:__bpf_trace_sys_enter
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_callback
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_entry
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_mmu_flush_tlb_others
  - arch/x86/kernel/irq.c:__bpf_trace_vector_reserve
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_l2
  - arch/x86/mm/init.c:__bpf_trace_tlb_flush
  - arch/x86/mm/mpx.c:__bpf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:__bpf_trace_mpx_bounds_register_exception
  - kernel/fork.c:__bpf_trace_task_rename
  - kernel/fork.c:__bpf_trace_task_newtask
  - kernel/softirq.c:__bpf_trace_irq_handler_entry
  - kernel/sched/core.c:__bpf_trace_sched_pi_setprio
  - kernel/sched/core.c:__bpf_trace_sched_stat_template
  - kernel/sched/core.c:__bpf_trace_sched_process_fork
  - kernel/sched/core.c:__bpf_trace_sched_migrate_task
  - kernel/printk/printk.c:__bpf_trace_console
  - kernel/irq/matrix.c:__bpf_trace_irq_matrix_global_update
  - kernel/time/timer.c:__bpf_trace_tick_stop
  - kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:__bpf_trace_hrtimer_start
  - kernel/time/timer.c:__bpf_trace_timer_expire_entry
  - kernel/time/alarmtimer.c:__bpf_trace_alarm_class
  - kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend
  - kernel/module.c:__bpf_trace_module_refcnt
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_request
  - kernel/trace/power-traces.c:__bpf_trace_wakeup_source
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:__bpf_trace_cpu
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal
  - kernel/bpf/core.c:__bpf_trace_mem_return_failed
  - kernel/bpf/core.c:__bpf_trace_mem_connect
  - mm/filemap.c:__bpf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:__bpf_trace_filemap_set_wb_err
  - mm/swap.c:__bpf_trace_mm_lru_insertion
  - mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/slab_common.c:__bpf_trace_mm_page_free
  - mm/slab_common.c:__bpf_trace_kmem_free
  - mm/compaction.c:__bpf_trace_mm_compaction_defer_template
  - fs/fs-writeback.c:__bpf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:__bpf_trace_global_dirty_state
  - fs/fs-writeback.c:__bpf_trace_wbc_class
  - fs/fs-writeback.c:__bpf_trace_writeback_work_class
  - fs/fs-writeback.c:__bpf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:__bpf_trace_track_foreign_dirty
  - fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:__bpf_trace_writeback_page_template
  - fs/locks.c:__bpf_trace_generic_add_lease
  - fs/locks.c:__bpf_trace_filelock_lease
  - fs/ext4/super.c:__bpf_trace_ext4_shutdown
  - fs/ext4/super.c:__bpf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:__bpf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:__bpf_trace_ext4_es_find_extent_range_enter
  - fs/ext4/super.c:__bpf_trace_ext4__es_extent
  - fs/ext4/super.c:__bpf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:__bpf_trace_ext4_unlink_exit
  - fs/ext4/super.c:__bpf_trace_ext4_unlink_enter
  - fs/ext4/super.c:__bpf_trace_ext4__bitmap_load
  - fs/ext4/super.c:__bpf_trace_ext4_da_release_space
  - fs/ext4/super.c:__bpf_trace_ext4_sync_fs
  - fs/ext4/super.c:__bpf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:__bpf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:__bpf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:__bpf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:__bpf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:__bpf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:__bpf_trace_ext4_writepages
  - fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:__bpf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:__bpf_trace_ext4_drop_inode
  - fs/ext4/super.c:__bpf_trace_ext4_request_inode
  - fs/ext4/super.c:__bpf_trace_ext4_other_inode_update_time
  - fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:__bpf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:__bpf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:__bpf_trace_jbd2_commit
  - fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint
  - block/blk-core.c:__bpf_trace_block_bio_queue
  - block/blk-core.c:__bpf_trace_block_bio_bounce
  - block/blk-core.c:__bpf_trace_block_rq
  - block/blk-core.c:__bpf_trace_block_rq_requeue
  - block/blk-wbt.c:__bpf_trace_wbt_lat
  - block/blk-wbt.c:__bpf_trace_wbt_stat
  - drivers/clk/clk.c:__bpf_trace_clk_duty_cycle
  - drivers/clk/clk.c:__bpf_trace_clk_phase
  - drivers/clk/clk.c:__bpf_trace_clk_parent
  - drivers/clk/clk.c:__bpf_trace_clk_rate
  - drivers/regulator/core.c:__bpf_trace_regulator_value
  - drivers/char/random.c:__bpf_trace_random__get_random_bytes
  - drivers/char/random.c:__bpf_trace_add_disk_randomness
  - drivers/char/random.c:__bpf_trace_debit_entropy
  - drivers/char/random.c:__bpf_trace_add_device_randomness
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool
  - drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error
  - drivers/nvme/host/core.c:__bpf_trace_nvme_async_event
  - drivers/nvme/host/core.c:__bpf_trace_nvme_setup_cmd
  - drivers/spi/spi.c:__bpf_trace_spi_transfer
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb
  - drivers/rtc/interface.c:__bpf_trace_rtc_offset_class
  - drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:__bpf_trace_rtc_irq_set_state
  - drivers/rtc/interface.c:__bpf_trace_rtc_irq_set_freq
  - drivers/rtc/interface.c:__bpf_trace_rtc_time_alarm_class
  - drivers/thermal/thermal_core.c:__bpf_trace_cdev_update
  - drivers/mmc/core/core.c:__bpf_trace_mmc_request_done
  - drivers/mmc/core/core.c:__bpf_trace_mmc_request_start
  - net/core/net-traces.c:__bpf_trace_neigh__update
  - net/core/net-traces.c:__bpf_trace_fdb_delete
  - net/core/net-traces.c:__bpf_trace_tcp_probe
  - net/core/net-traces.c:__bpf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:__bpf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:__bpf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:__bpf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:__bpf_trace_net_dev_start_xmit
  - net/core/net-traces.c:__bpf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:__bpf_trace_kfree_skb
```
**Symbols:**

```
ffffffff811c5020-ffffffff811c50b6: bpf_trace_run2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_trace_run2(struct bpf_prog *prog, u64 arg0, u64 arg1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b7e00)
Location: kernel/trace/bpf_trace.c:1372
Inline: False
Direct callers:
  - init/main.c:__bpf_trace_initcall_finish
  - arch/x86/entry/common.c:__bpf_trace_sys_exit
  - arch/x86/entry/common.c:__bpf_trace_sys_enter
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_mmu_flush_tlb_others
  - arch/x86/kernel/irq.c:__bpf_trace_vector_reserve
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_l2
  - arch/x86/mm/init.c:__bpf_trace_tlb_flush
  - arch/x86/mm/mpx.c:__bpf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:__bpf_trace_mpx_bounds_register_exception
  - kernel/fork.c:__bpf_trace_task_rename
  - kernel/fork.c:__bpf_trace_task_newtask
  - kernel/softirq.c:__bpf_trace_irq_handler_entry
  - kernel/sched/core.c:__bpf_trace_sched_pi_setprio
  - kernel/sched/core.c:__bpf_trace_sched_stat_template
  - kernel/sched/core.c:__bpf_trace_sched_process_fork
  - kernel/sched/core.c:__bpf_trace_sched_migrate_task
  - kernel/printk/printk.c:__bpf_trace_console
  - kernel/irq/matrix.c:__bpf_trace_irq_matrix_global_update
  - kernel/time/timer.c:__bpf_trace_tick_stop
  - kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:__bpf_trace_hrtimer_start
  - kernel/time/timer.c:__bpf_trace_timer_expire_entry
  - kernel/time/alarmtimer.c:__bpf_trace_alarm_class
  - kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend
  - kernel/module.c:__bpf_trace_module_refcnt
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_request
  - kernel/trace/power-traces.c:__bpf_trace_wakeup_source
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:__bpf_trace_cpu
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal
  - kernel/bpf/core.c:__bpf_trace_mem_return_failed
  - kernel/bpf/core.c:__bpf_trace_mem_connect
  - mm/filemap.c:__bpf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:__bpf_trace_filemap_set_wb_err
  - mm/swap.c:__bpf_trace_mm_lru_insertion
  - mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/slab_common.c:__bpf_trace_mm_page_free
  - mm/slab_common.c:__bpf_trace_kmem_free
  - mm/compaction.c:__bpf_trace_mm_compaction_defer_template
  - fs/fs-writeback.c:__bpf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:__bpf_trace_global_dirty_state
  - fs/fs-writeback.c:__bpf_trace_wbc_class
  - fs/fs-writeback.c:__bpf_trace_writeback_work_class
  - fs/fs-writeback.c:__bpf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:__bpf_trace_track_foreign_dirty
  - fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:__bpf_trace_writeback_page_template
  - fs/locks.c:__bpf_trace_generic_add_lease
  - fs/locks.c:__bpf_trace_filelock_lease
  - fs/ext4/super.c:__bpf_trace_ext4_shutdown
  - fs/ext4/super.c:__bpf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:__bpf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:__bpf_trace_ext4_es_find_extent_range_enter
  - fs/ext4/super.c:__bpf_trace_ext4__es_extent
  - fs/ext4/super.c:__bpf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:__bpf_trace_ext4_unlink_exit
  - fs/ext4/super.c:__bpf_trace_ext4_unlink_enter
  - fs/ext4/super.c:__bpf_trace_ext4__bitmap_load
  - fs/ext4/super.c:__bpf_trace_ext4_da_release_space
  - fs/ext4/super.c:__bpf_trace_ext4_sync_fs
  - fs/ext4/super.c:__bpf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:__bpf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:__bpf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:__bpf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:__bpf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:__bpf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:__bpf_trace_ext4_writepages
  - fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:__bpf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:__bpf_trace_ext4_drop_inode
  - fs/ext4/super.c:__bpf_trace_ext4_request_inode
  - fs/ext4/super.c:__bpf_trace_ext4_other_inode_update_time
  - fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:__bpf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:__bpf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:__bpf_trace_jbd2_commit
  - fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint
  - block/blk-core.c:__bpf_trace_block_bio_queue
  - block/blk-core.c:__bpf_trace_block_bio_bounce
  - block/blk-core.c:__bpf_trace_block_rq
  - block/blk-core.c:__bpf_trace_block_rq_requeue
  - block/blk-wbt.c:__bpf_trace_wbt_lat
  - block/blk-wbt.c:__bpf_trace_wbt_stat
  - drivers/clk/clk.c:__bpf_trace_clk_duty_cycle
  - drivers/clk/clk.c:__bpf_trace_clk_phase
  - drivers/clk/clk.c:__bpf_trace_clk_parent
  - drivers/clk/clk.c:__bpf_trace_clk_rate
  - drivers/regulator/core.c:__bpf_trace_regulator_value
  - drivers/char/random.c:__bpf_trace_random__get_random_bytes
  - drivers/char/random.c:__bpf_trace_add_disk_randomness
  - drivers/char/random.c:__bpf_trace_debit_entropy
  - drivers/char/random.c:__bpf_trace_add_device_randomness
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool
  - drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error
  - drivers/nvme/host/core.c:__bpf_trace_nvme_async_event
  - drivers/nvme/host/core.c:__bpf_trace_nvme_setup_cmd
  - drivers/spi/spi.c:__bpf_trace_spi_transfer
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb
  - drivers/rtc/interface.c:__bpf_trace_rtc_offset_class
  - drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:__bpf_trace_rtc_irq_set_state
  - drivers/rtc/interface.c:__bpf_trace_rtc_irq_set_freq
  - drivers/rtc/interface.c:__bpf_trace_rtc_time_alarm_class
  - drivers/thermal/thermal_core.c:__bpf_trace_cdev_update
  - drivers/hv/hv_trace.c:__bpf_trace_vmbus_send_tl_connect_request
  - drivers/hv/hv_trace.c:__bpf_trace_vmbus_release_relid
  - drivers/hv/hv_trace.c:__bpf_trace_vmbus_negotiate_version
  - drivers/hv/hv_trace.c:__bpf_trace_vmbus_teardown_gpadl
  - drivers/hv/hv_trace.c:__bpf_trace_vmbus_establish_gpadl_body
  - drivers/hv/hv_trace.c:__bpf_trace_vmbus_establish_gpadl_header
  - drivers/hv/hv_trace.c:__bpf_trace_vmbus_close_internal
  - drivers/hv/hv_trace.c:__bpf_trace_vmbus_open
  - net/core/net-traces.c:__bpf_trace_neigh__update
  - net/core/net-traces.c:__bpf_trace_fdb_delete
  - net/core/net-traces.c:__bpf_trace_tcp_probe
  - net/core/net-traces.c:__bpf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:__bpf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:__bpf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:__bpf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:__bpf_trace_net_dev_start_xmit
  - net/core/net-traces.c:__bpf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:__bpf_trace_kfree_skb
```
**Symbols:**

```
ffffffff811b7e00-ffffffff811b7e96: bpf_trace_run2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_trace_run2(struct bpf_prog *prog, u64 arg0, u64 arg1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c2df0)
Location: kernel/trace/bpf_trace.c:1372
Inline: False
Direct callers:
  - init/main.c:__bpf_trace_initcall_finish
  - arch/x86/entry/common.c:__bpf_trace_sys_exit
  - arch/x86/entry/common.c:__bpf_trace_sys_enter
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_callback
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_entry
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_mmu_flush_tlb_others
  - arch/x86/kernel/irq.c:__bpf_trace_vector_reserve
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_l2
  - arch/x86/mm/init.c:__bpf_trace_tlb_flush
  - arch/x86/mm/mpx.c:__bpf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:__bpf_trace_mpx_bounds_register_exception
  - kernel/fork.c:__bpf_trace_task_rename
  - kernel/fork.c:__bpf_trace_task_newtask
  - kernel/softirq.c:__bpf_trace_irq_handler_entry
  - kernel/sched/core.c:__bpf_trace_sched_pi_setprio
  - kernel/sched/core.c:__bpf_trace_sched_stat_template
  - kernel/sched/core.c:__bpf_trace_sched_process_fork
  - kernel/sched/core.c:__bpf_trace_sched_migrate_task
  - kernel/printk/printk.c:__bpf_trace_console
  - kernel/irq/matrix.c:__bpf_trace_irq_matrix_global_update
  - kernel/time/timer.c:__bpf_trace_tick_stop
  - kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:__bpf_trace_hrtimer_start
  - kernel/time/timer.c:__bpf_trace_timer_expire_entry
  - kernel/time/alarmtimer.c:__bpf_trace_alarm_class
  - kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend
  - kernel/module.c:__bpf_trace_module_refcnt
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_request
  - kernel/trace/power-traces.c:__bpf_trace_wakeup_source
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:__bpf_trace_cpu
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal
  - kernel/bpf/core.c:__bpf_trace_mem_return_failed
  - kernel/bpf/core.c:__bpf_trace_mem_connect
  - mm/filemap.c:__bpf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:__bpf_trace_filemap_set_wb_err
  - mm/swap.c:__bpf_trace_mm_lru_insertion
  - mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/slab_common.c:__bpf_trace_mm_page_free
  - mm/slab_common.c:__bpf_trace_kmem_free
  - mm/compaction.c:__bpf_trace_mm_compaction_defer_template
  - fs/fs-writeback.c:__bpf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:__bpf_trace_global_dirty_state
  - fs/fs-writeback.c:__bpf_trace_wbc_class
  - fs/fs-writeback.c:__bpf_trace_writeback_work_class
  - fs/fs-writeback.c:__bpf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:__bpf_trace_track_foreign_dirty
  - fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:__bpf_trace_writeback_page_template
  - fs/locks.c:__bpf_trace_generic_add_lease
  - fs/locks.c:__bpf_trace_filelock_lease
  - fs/ext4/super.c:__bpf_trace_ext4_shutdown
  - fs/ext4/super.c:__bpf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:__bpf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:__bpf_trace_ext4_es_find_extent_range_enter
  - fs/ext4/super.c:__bpf_trace_ext4__es_extent
  - fs/ext4/super.c:__bpf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:__bpf_trace_ext4_unlink_exit
  - fs/ext4/super.c:__bpf_trace_ext4_unlink_enter
  - fs/ext4/super.c:__bpf_trace_ext4__bitmap_load
  - fs/ext4/super.c:__bpf_trace_ext4_da_release_space
  - fs/ext4/super.c:__bpf_trace_ext4_sync_fs
  - fs/ext4/super.c:__bpf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:__bpf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:__bpf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:__bpf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:__bpf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:__bpf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:__bpf_trace_ext4_writepages
  - fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:__bpf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:__bpf_trace_ext4_drop_inode
  - fs/ext4/super.c:__bpf_trace_ext4_request_inode
  - fs/ext4/super.c:__bpf_trace_ext4_other_inode_update_time
  - fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:__bpf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:__bpf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:__bpf_trace_jbd2_commit
  - fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint
  - block/blk-core.c:__bpf_trace_block_bio_queue
  - block/blk-core.c:__bpf_trace_block_bio_bounce
  - block/blk-core.c:__bpf_trace_block_rq
  - block/blk-core.c:__bpf_trace_block_rq_requeue
  - block/blk-wbt.c:__bpf_trace_wbt_lat
  - block/blk-wbt.c:__bpf_trace_wbt_stat
  - drivers/clk/clk.c:__bpf_trace_clk_duty_cycle
  - drivers/clk/clk.c:__bpf_trace_clk_phase
  - drivers/clk/clk.c:__bpf_trace_clk_parent
  - drivers/clk/clk.c:__bpf_trace_clk_rate
  - drivers/regulator/core.c:__bpf_trace_regulator_value
  - drivers/char/random.c:__bpf_trace_random__get_random_bytes
  - drivers/char/random.c:__bpf_trace_add_disk_randomness
  - drivers/char/random.c:__bpf_trace_debit_entropy
  - drivers/char/random.c:__bpf_trace_add_device_randomness
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool
  - drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error
  - drivers/spi/spi.c:__bpf_trace_spi_transfer
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb
  - drivers/rtc/interface.c:__bpf_trace_rtc_offset_class
  - drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:__bpf_trace_rtc_irq_set_state
  - drivers/rtc/interface.c:__bpf_trace_rtc_irq_set_freq
  - drivers/rtc/interface.c:__bpf_trace_rtc_time_alarm_class
  - drivers/thermal/thermal_core.c:__bpf_trace_cdev_update
  - drivers/mmc/core/core.c:__bpf_trace_mmc_request_done
  - drivers/mmc/core/core.c:__bpf_trace_mmc_request_start
  - net/core/net-traces.c:__bpf_trace_neigh__update
  - net/core/net-traces.c:__bpf_trace_fdb_delete
  - net/core/net-traces.c:__bpf_trace_tcp_probe
  - net/core/net-traces.c:__bpf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:__bpf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:__bpf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:__bpf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:__bpf_trace_net_dev_start_xmit
  - net/core/net-traces.c:__bpf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:__bpf_trace_kfree_skb
```
**Symbols:**

```
ffffffff811c2df0-ffffffff811c2e86: bpf_trace_run2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_trace_run2(struct bpf_prog *prog, u64 arg0, u64 arg1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811d2170)
Location: kernel/trace/bpf_trace.c:1372
Inline: False
Direct callers:
  - init/main.c:__bpf_trace_initcall_finish
  - arch/x86/entry/common.c:__bpf_trace_sys_exit
  - arch/x86/entry/common.c:__bpf_trace_sys_enter
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_set_ldt
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_write_cr3
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_pgd
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pud
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pmd
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu__set_pte
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_callback
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_entry
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_nested_flush_guest_mapping_range
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_nested_flush_guest_mapping
  - arch/x86/hyperv/mmu.c:__bpf_trace_hyperv_mmu_flush_tlb_others
  - arch/x86/kernel/irq.c:__bpf_trace_vector_reserve
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_l3
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:__bpf_trace_pseudo_lock_l2
  - arch/x86/mm/init.c:__bpf_trace_tlb_flush
  - arch/x86/mm/mpx.c:__bpf_trace_mpx_range_trace
  - arch/x86/mm/mpx.c:__bpf_trace_mpx_bounds_register_exception
  - kernel/fork.c:__bpf_trace_task_rename
  - kernel/fork.c:__bpf_trace_task_newtask
  - kernel/softirq.c:__bpf_trace_irq_handler_entry
  - kernel/sched/core.c:__bpf_trace_sched_pi_setprio
  - kernel/sched/core.c:__bpf_trace_sched_stat_template
  - kernel/sched/core.c:__bpf_trace_sched_process_fork
  - kernel/sched/core.c:__bpf_trace_sched_migrate_task
  - kernel/printk/printk.c:__bpf_trace_console
  - kernel/irq/matrix.c:__bpf_trace_irq_matrix_global_update
  - kernel/time/timer.c:__bpf_trace_tick_stop
  - kernel/time/timer.c:__bpf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:__bpf_trace_hrtimer_start
  - kernel/time/timer.c:__bpf_trace_timer_expire_entry
  - kernel/time/alarmtimer.c:__bpf_trace_alarm_class
  - kernel/time/alarmtimer.c:__bpf_trace_alarmtimer_suspend
  - kernel/module.c:__bpf_trace_module_refcnt
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_request
  - kernel/trace/power-traces.c:__bpf_trace_wakeup_source
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:__bpf_trace_cpu
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_internal
  - kernel/bpf/core.c:__bpf_trace_mem_return_failed
  - kernel/bpf/core.c:__bpf_trace_mem_connect
  - mm/filemap.c:__bpf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:__bpf_trace_filemap_set_wb_err
  - mm/swap.c:__bpf_trace_mm_lru_insertion
  - mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/slab_common.c:__bpf_trace_mm_page_free
  - mm/slab_common.c:__bpf_trace_kmem_free
  - mm/compaction.c:__bpf_trace_mm_compaction_defer_template
  - fs/fs-writeback.c:__bpf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:__bpf_trace_global_dirty_state
  - fs/fs-writeback.c:__bpf_trace_wbc_class
  - fs/fs-writeback.c:__bpf_trace_writeback_work_class
  - fs/fs-writeback.c:__bpf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:__bpf_trace_track_foreign_dirty
  - fs/fs-writeback.c:__bpf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:__bpf_trace_writeback_page_template
  - fs/locks.c:__bpf_trace_generic_add_lease
  - fs/locks.c:__bpf_trace_filelock_lease
  - fs/ext4/super.c:__bpf_trace_ext4_shutdown
  - fs/ext4/super.c:__bpf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:__bpf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:__bpf_trace_ext4_es_find_extent_range_enter
  - fs/ext4/super.c:__bpf_trace_ext4__es_extent
  - fs/ext4/super.c:__bpf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:__bpf_trace_ext4_unlink_exit
  - fs/ext4/super.c:__bpf_trace_ext4_unlink_enter
  - fs/ext4/super.c:__bpf_trace_ext4__bitmap_load
  - fs/ext4/super.c:__bpf_trace_ext4_da_release_space
  - fs/ext4/super.c:__bpf_trace_ext4_sync_fs
  - fs/ext4/super.c:__bpf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:__bpf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:__bpf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:__bpf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:__bpf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:__bpf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:__bpf_trace_ext4_writepages
  - fs/ext4/super.c:__bpf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:__bpf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:__bpf_trace_ext4_drop_inode
  - fs/ext4/super.c:__bpf_trace_ext4_request_inode
  - fs/ext4/super.c:__bpf_trace_ext4_other_inode_update_time
  - fs/jbd2/journal.c:__bpf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:__bpf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:__bpf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:__bpf_trace_jbd2_commit
  - fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint
  - block/blk-core.c:__bpf_trace_block_bio_queue
  - block/blk-core.c:__bpf_trace_block_bio_bounce
  - block/blk-core.c:__bpf_trace_block_rq
  - block/blk-core.c:__bpf_trace_block_rq_requeue
  - block/blk-wbt.c:__bpf_trace_wbt_lat
  - block/blk-wbt.c:__bpf_trace_wbt_stat
  - drivers/clk/clk.c:__bpf_trace_clk_duty_cycle
  - drivers/clk/clk.c:__bpf_trace_clk_phase
  - drivers/clk/clk.c:__bpf_trace_clk_parent
  - drivers/clk/clk.c:__bpf_trace_clk_rate
  - drivers/regulator/core.c:__bpf_trace_regulator_value
  - drivers/char/random.c:__bpf_trace_random__get_random_bytes
  - drivers/char/random.c:__bpf_trace_add_disk_randomness
  - drivers/char/random.c:__bpf_trace_debit_entropy
  - drivers/char/random.c:__bpf_trace_add_device_randomness
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_group_event
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_bool
  - drivers/scsi/scsi.c:__bpf_trace_scsi_dispatch_cmd_error
  - drivers/spi/spi.c:__bpf_trace_spi_transfer
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_trb
  - drivers/rtc/interface.c:__bpf_trace_rtc_offset_class
  - drivers/rtc/interface.c:__bpf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:__bpf_trace_rtc_irq_set_state
  - drivers/rtc/interface.c:__bpf_trace_rtc_irq_set_freq
  - drivers/rtc/interface.c:__bpf_trace_rtc_time_alarm_class
  - drivers/thermal/thermal_core.c:__bpf_trace_cdev_update
  - drivers/mmc/core/core.c:__bpf_trace_mmc_request_done
  - drivers/mmc/core/core.c:__bpf_trace_mmc_request_start
  - net/core/net-traces.c:__bpf_trace_neigh__update
  - net/core/net-traces.c:__bpf_trace_fdb_delete
  - net/core/net-traces.c:__bpf_trace_tcp_probe
  - net/core/net-traces.c:__bpf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:__bpf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:__bpf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:__bpf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:__bpf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:__bpf_trace_net_dev_start_xmit
  - net/core/net-traces.c:__bpf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:__bpf_trace_kfree_skb
```
**Symbols:**

```
ffffffff811d2170-ffffffff811d2227: bpf_trace_run2 (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
