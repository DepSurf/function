# Function: <code>bpf_trace_run3</code>

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
void bpf_trace_run3(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811a4830)
Location: kernel/trace/bpf_trace.c:1135
Inline: False
Direct callers:
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush
  - arch/x86/kernel/irq.c:__bpf_trace_vector_setup
  - arch/x86/kernel/irq.c:__bpf_trace_vector_teardown
  - arch/x86/kernel/irq.c:__bpf_trace_vector_alloc_managed
  - arch/x86/kernel/nmi.c:__bpf_trace_nmi_handler
  - arch/x86/mm/fault.c:__bpf_trace_x86_exceptions
  - kernel/softirq.c:__bpf_trace_irq_handler_exit
  - kernel/signal.c:__bpf_trace_signal_deliver
  - kernel/workqueue.c:__bpf_trace_workqueue_queue_work
  - kernel/sched/core.c:__bpf_trace_sched_move_task_template
  - kernel/sched/core.c:__bpf_trace_sched_stat_runtime
  - kernel/sched/core.c:__bpf_trace_sched_process_exec
  - kernel/sched/core.c:__bpf_trace_sched_switch
  - kernel/time/timer.c:__bpf_trace_itimer_expire
  - kernel/time/timer.c:__bpf_trace_itimer_state
  - kernel/time/timer.c:__bpf_trace_hrtimer_init
  - kernel/time/timer.c:__bpf_trace_timer_start
  - kernel/module.c:__bpf_trace_module_request
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup_migrate
  - kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_update
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:__bpf_trace_suspend_resume
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:__bpf_trace_powernv_throttle
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int
  - kernel/bpf/core.c:__bpf_trace_xdp_exception
  - mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake
  - mm/percpu.c:__bpf_trace_percpu_free_percpu
  - mm/compaction.c:__bpf_trace_kcompactd_wake_template
  - mm/compaction.c:__bpf_trace_mm_compaction_suitable_template
  - mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:__bpf_trace_mm_compaction_migratepages
  - mm/migrate.c:__bpf_trace_mm_numa_migrate_ratelimit
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page
  - mm/page_isolation.c:__bpf_trace_test_pages_isolated
  - mm/cma.c:__bpf_trace_cma_release
  - fs/open.c:__bpf_trace_do_sys_open
  - fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:__bpf_trace_writeback_queue_io
  - fs/dax.c:__bpf_trace_dax_insert_mapping
  - fs/dax.c:__bpf_trace_dax_pte_fault_class
  - fs/locks.c:__bpf_trace_filelock_lock
  - fs/locks.c:__bpf_trace_locks_get_lock_context
  - fs/ext4/super.c:__bpf_trace_ext4_error
  - fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:__bpf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:__bpf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:__bpf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:__bpf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:__bpf_trace_ext4_forget
  - fs/ext4/super.c:__bpf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:__bpf_trace_ext4_discard_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:__bpf_trace_ext4_da_write_pages
  - fs/ext4/super.c:__bpf_trace_ext4_allocate_inode
  - fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:__bpf_trace_jbd2_run_stats
  - block/blk-core.c:__bpf_trace_block_split
  - block/blk-core.c:__bpf_trace_block_unplug
  - block/blk-core.c:__bpf_trace_block_bio_merge
  - block/blk-core.c:__bpf_trace_block_rq_complete
  - arch/x86/lib/msr.c:__bpf_trace_msr_trace_class
  - drivers/regulator/core.c:__bpf_trace_regulator_range
  - drivers/char/random.c:__bpf_trace_urandom_read
  - drivers/char/random.c:__bpf_trace_push_to_pool
  - drivers/char/random.c:__bpf_trace_random__mix_pool_bytes
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:__bpf_trace_unmap
  - drivers/iommu/iommu-traces.c:__bpf_trace_map
  - drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_block
  - drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx
  - drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip
  - drivers/ras/ras.c:__bpf_trace_memory_failure_event
  - net/core/net-traces.c:__bpf_trace_inet_sock_set_state
  - net/core/net-traces.c:__bpf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:__bpf_trace_napi_poll
```
**Symbols:**

```
ffffffff811a4830-ffffffff811a487a: bpf_trace_run3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bpf_trace_run3(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b2900)
Location: kernel/trace/bpf_trace.c:1180
Inline: False
Direct callers:
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush
  - arch/x86/kernel/irq.c:__bpf_trace_vector_setup
  - arch/x86/kernel/irq.c:__bpf_trace_vector_teardown
  - arch/x86/kernel/irq.c:__bpf_trace_vector_alloc_managed
  - arch/x86/kernel/nmi.c:__bpf_trace_nmi_handler
  - arch/x86/mm/fault.c:__bpf_trace_x86_exceptions
  - kernel/softirq.c:__bpf_trace_irq_handler_exit
  - kernel/signal.c:__bpf_trace_signal_deliver
  - kernel/workqueue.c:__bpf_trace_workqueue_queue_work
  - kernel/sched/core.c:__bpf_trace_sched_move_task_template
  - kernel/sched/core.c:__bpf_trace_sched_stat_runtime
  - kernel/sched/core.c:__bpf_trace_sched_process_exec
  - kernel/sched/core.c:__bpf_trace_sched_switch
  - kernel/time/timer.c:__bpf_trace_itimer_expire
  - kernel/time/timer.c:__bpf_trace_itimer_state
  - kernel/time/timer.c:__bpf_trace_hrtimer_init
  - kernel/time/timer.c:__bpf_trace_timer_start
  - kernel/module.c:__bpf_trace_module_request
  - kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_update
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:__bpf_trace_suspend_resume
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:__bpf_trace_powernv_throttle
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int
  - kernel/bpf/core.c:__bpf_trace_xdp_exception
  - mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake
  - mm/percpu.c:__bpf_trace_percpu_free_percpu
  - mm/compaction.c:__bpf_trace_kcompactd_wake_template
  - mm/compaction.c:__bpf_trace_mm_compaction_suitable_template
  - mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:__bpf_trace_mm_compaction_migratepages
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page
  - mm/page_isolation.c:__bpf_trace_test_pages_isolated
  - mm/cma.c:__bpf_trace_cma_release
  - fs/open.c:__bpf_trace_do_sys_open
  - fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:__bpf_trace_writeback_queue_io
  - fs/dax.c:__bpf_trace_dax_insert_mapping
  - fs/dax.c:__bpf_trace_dax_pte_fault_class
  - fs/locks.c:__bpf_trace_filelock_lock
  - fs/locks.c:__bpf_trace_locks_get_lock_context
  - fs/ext4/super.c:__bpf_trace_ext4_error
  - fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:__bpf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:__bpf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:__bpf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:__bpf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:__bpf_trace_ext4_forget
  - fs/ext4/super.c:__bpf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:__bpf_trace_ext4_discard_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:__bpf_trace_ext4_da_write_pages
  - fs/ext4/super.c:__bpf_trace_ext4_allocate_inode
  - fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:__bpf_trace_jbd2_run_stats
  - block/blk-core.c:__bpf_trace_block_split
  - block/blk-core.c:__bpf_trace_block_unplug
  - block/blk-core.c:__bpf_trace_block_bio_merge
  - block/blk-core.c:__bpf_trace_block_rq_complete
  - arch/x86/lib/msr.c:__bpf_trace_msr_trace_class
  - drivers/regulator/core.c:__bpf_trace_regulator_range
  - drivers/char/random.c:__bpf_trace_urandom_read
  - drivers/char/random.c:__bpf_trace_push_to_pool
  - drivers/char/random.c:__bpf_trace_random__mix_pool_bytes
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:__bpf_trace_unmap
  - drivers/iommu/iommu-traces.c:__bpf_trace_map
  - drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_block
  - drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx
  - drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip
  - drivers/ras/ras.c:__bpf_trace_memory_failure_event
  - net/core/net-traces.c:__bpf_trace_inet_sock_set_state
  - net/core/net-traces.c:__bpf_trace_napi_poll
```
**Symbols:**

```
ffffffff811b2900-ffffffff811b294a: bpf_trace_run3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bpf_trace_run3(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c12f0)
Location: kernel/trace/bpf_trace.c:1349
Inline: False
Direct callers:
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush
  - arch/x86/kernel/irq.c:__bpf_trace_vector_setup
  - arch/x86/kernel/irq.c:__bpf_trace_vector_teardown
  - arch/x86/kernel/irq.c:__bpf_trace_vector_alloc_managed
  - arch/x86/kernel/nmi.c:__bpf_trace_nmi_handler
  - arch/x86/mm/fault.c:__bpf_trace_x86_exceptions
  - kernel/softirq.c:__bpf_trace_irq_handler_exit
  - kernel/signal.c:__bpf_trace_signal_deliver
  - kernel/workqueue.c:__bpf_trace_workqueue_queue_work
  - kernel/sched/core.c:__bpf_trace_sched_move_task_template
  - kernel/sched/core.c:__bpf_trace_sched_stat_runtime
  - kernel/sched/core.c:__bpf_trace_sched_process_exec
  - kernel/sched/core.c:__bpf_trace_sched_switch
  - kernel/time/timer.c:__bpf_trace_itimer_expire
  - kernel/time/timer.c:__bpf_trace_itimer_state
  - kernel/time/timer.c:__bpf_trace_hrtimer_init
  - kernel/time/timer.c:__bpf_trace_timer_start
  - kernel/module.c:__bpf_trace_module_request
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event
  - kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_update
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:__bpf_trace_power_domain
  - kernel/trace/power-traces.c:__bpf_trace_clock
  - kernel/trace/power-traces.c:__bpf_trace_suspend_resume
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:__bpf_trace_powernv_throttle
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int
  - kernel/bpf/core.c:__bpf_trace_mem_disconnect
  - kernel/bpf/core.c:__bpf_trace_xdp_exception
  - mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake
  - mm/percpu.c:__bpf_trace_percpu_free_percpu
  - mm/slab_common.c:__bpf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:__bpf_trace_mm_page
  - mm/compaction.c:__bpf_trace_kcompactd_wake_template
  - mm/compaction.c:__bpf_trace_mm_compaction_suitable_template
  - mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:__bpf_trace_mm_compaction_migratepages
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page
  - mm/page_isolation.c:__bpf_trace_test_pages_isolated
  - mm/cma.c:__bpf_trace_cma_release
  - fs/open.c:__bpf_trace_do_sys_open
  - fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:__bpf_trace_writeback_queue_io
  - fs/dax.c:__bpf_trace_dax_writeback_one
  - fs/dax.c:__bpf_trace_dax_writeback_range_class
  - fs/dax.c:__bpf_trace_dax_insert_mapping
  - fs/dax.c:__bpf_trace_dax_pte_fault_class
  - fs/locks.c:__bpf_trace_leases_conflict
  - fs/locks.c:__bpf_trace_filelock_lock
  - fs/locks.c:__bpf_trace_locks_get_lock_context
  - fs/ext4/super.c:__bpf_trace_ext4_error
  - fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:__bpf_trace_ext4_insert_range
  - fs/ext4/super.c:__bpf_trace_ext4_collapse_range
  - fs/ext4/super.c:__bpf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:__bpf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:__bpf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:__bpf_trace_ext4_get_reserved_cluster_alloc
  - fs/ext4/super.c:__bpf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:__bpf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:__bpf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:__bpf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:__bpf_trace_ext4_forget
  - fs/ext4/super.c:__bpf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:__bpf_trace_ext4_discard_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:__bpf_trace_ext4_da_write_pages
  - fs/ext4/super.c:__bpf_trace_ext4_allocate_inode
  - fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:__bpf_trace_jbd2_run_stats
  - block/blk-core.c:__bpf_trace_block_split
  - block/blk-core.c:__bpf_trace_block_unplug
  - block/blk-core.c:__bpf_trace_block_get_rq
  - block/blk-core.c:__bpf_trace_block_bio_merge
  - block/blk-core.c:__bpf_trace_block_bio_complete
  - block/blk-core.c:__bpf_trace_block_rq_complete
  - arch/x86/lib/msr.c:__bpf_trace_msr_trace_class
  - drivers/gpio/gpiolib.c:__bpf_trace_gpio_value
  - drivers/gpio/gpiolib.c:__bpf_trace_gpio_direction
  - drivers/regulator/core.c:__bpf_trace_regulator_range
  - drivers/char/random.c:__bpf_trace_urandom_read
  - drivers/char/random.c:__bpf_trace_push_to_pool
  - drivers/char/random.c:__bpf_trace_random__mix_pool_bytes
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:__bpf_trace_unmap
  - drivers/iommu/iommu-traces.c:__bpf_trace_map
  - drivers/base/regmap/regmap.c:__bpf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_block
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_reg
  - drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx
  - drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_write
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip
  - drivers/ras/ras.c:__bpf_trace_memory_failure_event
  - net/core/net-traces.c:__bpf_trace_page_pool_state_hold
  - net/core/net-traces.c:__bpf_trace_page_pool_state_release
  - net/core/net-traces.c:__bpf_trace_inet_sock_set_state
  - net/core/net-traces.c:__bpf_trace_napi_poll
  - net/core/devlink.c:__bpf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:__bpf_trace_devlink_health_report
  - net/core/devlink.c:__bpf_trace_devlink_hwerr
```
**Symbols:**

```
ffffffff811c12f0-ffffffff811c138a: bpf_trace_run3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_trace_run3(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811ccaa0)
Location: kernel/trace/bpf_trace.c:1373
Inline: False
Direct callers:
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush
  - arch/x86/kernel/irq.c:__bpf_trace_vector_setup
  - arch/x86/kernel/irq.c:__bpf_trace_vector_teardown
  - arch/x86/kernel/irq.c:__bpf_trace_vector_alloc_managed
  - arch/x86/kernel/nmi.c:__bpf_trace_nmi_handler
  - arch/x86/mm/fault.c:__bpf_trace_x86_exceptions
  - kernel/softirq.c:__bpf_trace_irq_handler_exit
  - kernel/signal.c:__bpf_trace_signal_deliver
  - kernel/workqueue.c:__bpf_trace_workqueue_queue_work
  - kernel/sched/core.c:__bpf_trace_sched_move_task_template
  - kernel/sched/core.c:__bpf_trace_sched_stat_runtime
  - kernel/sched/core.c:__bpf_trace_sched_process_exec
  - kernel/sched/core.c:__bpf_trace_sched_switch
  - kernel/time/timer.c:__bpf_trace_itimer_expire
  - kernel/time/timer.c:__bpf_trace_itimer_state
  - kernel/time/timer.c:__bpf_trace_hrtimer_init
  - kernel/time/timer.c:__bpf_trace_timer_start
  - kernel/module.c:__bpf_trace_module_request
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event
  - kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_update
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:__bpf_trace_power_domain
  - kernel/trace/power-traces.c:__bpf_trace_clock
  - kernel/trace/power-traces.c:__bpf_trace_suspend_resume
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:__bpf_trace_powernv_throttle
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int
  - kernel/bpf/core.c:__bpf_trace_xdp_exception
  - mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake
  - mm/percpu.c:__bpf_trace_percpu_free_percpu
  - mm/slab_common.c:__bpf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:__bpf_trace_mm_page
  - mm/compaction.c:__bpf_trace_kcompactd_wake_template
  - mm/compaction.c:__bpf_trace_mm_compaction_suitable_template
  - mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:__bpf_trace_mm_compaction_migratepages
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page
  - mm/page_isolation.c:__bpf_trace_test_pages_isolated
  - mm/cma.c:__bpf_trace_cma_release
  - fs/open.c:__bpf_trace_do_sys_open
  - fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:__bpf_trace_writeback_queue_io
  - fs/fs-writeback.c:__bpf_trace_flush_foreign
  - fs/fs-writeback.c:__bpf_trace_inode_switch_wbs
  - fs/fs-writeback.c:__bpf_trace_inode_foreign_history
  - fs/dax.c:__bpf_trace_dax_writeback_one
  - fs/dax.c:__bpf_trace_dax_writeback_range_class
  - fs/dax.c:__bpf_trace_dax_insert_mapping
  - fs/dax.c:__bpf_trace_dax_pte_fault_class
  - fs/locks.c:__bpf_trace_leases_conflict
  - fs/locks.c:__bpf_trace_filelock_lock
  - fs/locks.c:__bpf_trace_locks_get_lock_context
  - fs/ext4/super.c:__bpf_trace_ext4_error
  - fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:__bpf_trace_ext4_insert_range
  - fs/ext4/super.c:__bpf_trace_ext4_collapse_range
  - fs/ext4/super.c:__bpf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:__bpf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:__bpf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:__bpf_trace_ext4_get_reserved_cluster_alloc
  - fs/ext4/super.c:__bpf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:__bpf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:__bpf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:__bpf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:__bpf_trace_ext4_forget
  - fs/ext4/super.c:__bpf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:__bpf_trace_ext4_discard_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:__bpf_trace_ext4_da_write_pages
  - fs/ext4/super.c:__bpf_trace_ext4_allocate_inode
  - fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:__bpf_trace_jbd2_run_stats
  - block/blk-core.c:__bpf_trace_block_split
  - block/blk-core.c:__bpf_trace_block_unplug
  - block/blk-core.c:__bpf_trace_block_get_rq
  - block/blk-core.c:__bpf_trace_block_bio_merge
  - block/blk-core.c:__bpf_trace_block_bio_complete
  - block/blk-core.c:__bpf_trace_block_rq_complete
  - arch/x86/lib/msr.c:__bpf_trace_msr_trace_class
  - drivers/gpio/gpiolib.c:__bpf_trace_gpio_value
  - drivers/gpio/gpiolib.c:__bpf_trace_gpio_direction
  - drivers/regulator/core.c:__bpf_trace_regulator_range
  - drivers/char/random.c:__bpf_trace_urandom_read
  - drivers/char/random.c:__bpf_trace_push_to_pool
  - drivers/char/random.c:__bpf_trace_random__mix_pool_bytes
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:__bpf_trace_unmap
  - drivers/iommu/iommu-traces.c:__bpf_trace_map
  - drivers/iommu/intel-trace.c:__bpf_trace_dma_unmap
  - drivers/base/regmap/regmap.c:__bpf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_block
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_reg
  - drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx
  - drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_write
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip
  - drivers/ras/ras.c:__bpf_trace_memory_failure_event
  - net/core/net-traces.c:__bpf_trace_page_pool_state_hold
  - net/core/net-traces.c:__bpf_trace_page_pool_state_release
  - net/core/net-traces.c:__bpf_trace_inet_sock_set_state
  - net/core/net-traces.c:__bpf_trace_napi_poll
  - net/core/devlink.c:__bpf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:__bpf_trace_devlink_health_report
  - net/core/devlink.c:__bpf_trace_devlink_hwerr
```
**Symbols:**

```
ffffffff811ccaa0-ffffffff811ccb3a: bpf_trace_run3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bpf_trace_run3(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e8430)
Location: kernel/trace/bpf_trace.c:1867
Inline: False
Direct callers:
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush
  - arch/x86/kernel/irq.c:__bpf_trace_vector_setup
  - arch/x86/kernel/irq.c:__bpf_trace_vector_teardown
  - arch/x86/kernel/irq.c:__bpf_trace_vector_alloc_managed
  - arch/x86/kernel/nmi.c:__bpf_trace_nmi_handler
  - arch/x86/mm/fault.c:__bpf_trace_x86_exceptions
  - kernel/softirq.c:__bpf_trace_irq_handler_exit
  - kernel/signal.c:__bpf_trace_signal_deliver
  - kernel/workqueue.c:__bpf_trace_workqueue_queue_work
  - kernel/sched/core.c:__bpf_trace_sched_move_numa
  - kernel/sched/core.c:__bpf_trace_sched_stat_runtime
  - kernel/sched/core.c:__bpf_trace_sched_process_exec
  - kernel/sched/core.c:__bpf_trace_sched_switch
  - kernel/time/timer.c:__bpf_trace_hrtimer_init
  - kernel/time/timer.c:__bpf_trace_timer_start
  - kernel/module.c:__bpf_trace_module_request
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event
  - kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_update
  - kernel/trace/power-traces.c:__bpf_trace_suspend_resume
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:__bpf_trace_powernv_throttle
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int
  - kernel/bpf/core.c:__bpf_trace_xdp_exception
  - mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake
  - mm/percpu.c:__bpf_trace_percpu_free_percpu
  - mm/slab_common.c:__bpf_trace_rss_stat
  - mm/compaction.c:__bpf_trace_kcompactd_wake_template
  - mm/compaction.c:__bpf_trace_mm_compaction_suitable_template
  - mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:__bpf_trace_mm_compaction_migratepages
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page
  - mm/page_isolation.c:__bpf_trace_test_pages_isolated
  - fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:__bpf_trace_flush_foreign
  - fs/fs-writeback.c:__bpf_trace_inode_switch_wbs
  - fs/fs-writeback.c:__bpf_trace_inode_foreign_history
  - fs/io_uring.c:__bpf_trace_io_uring_task_run
  - fs/io_uring.c:__bpf_trace_io_uring_complete
  - fs/io_uring.c:__bpf_trace_io_uring_link
  - fs/io_uring.c:__bpf_trace_io_uring_defer
  - fs/dax.c:__bpf_trace_dax_insert_mapping
  - fs/dax.c:__bpf_trace_dax_pte_fault_class
  - fs/locks.c:__bpf_trace_leases_conflict
  - fs/locks.c:__bpf_trace_filelock_lock
  - fs/locks.c:__bpf_trace_locks_get_lock_context
  - fs/iomap/trace.c:__bpf_trace_iomap_range_class
  - fs/ext4/super.c:__bpf_trace_ext4_error
  - fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:__bpf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:__bpf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:__bpf_trace_ext4_discard_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_da_write_pages
  - block/blk-core.c:__bpf_trace_block_split
  - block/blk-core.c:__bpf_trace_block_unplug
  - block/blk-core.c:__bpf_trace_block_get_rq
  - block/blk-core.c:__bpf_trace_block_bio_merge
  - block/blk-core.c:__bpf_trace_block_rq_complete
  - arch/x86/lib/msr.c:__bpf_trace_msr_trace_class
  - drivers/regulator/core.c:__bpf_trace_regulator_range
  - drivers/char/random.c:__bpf_trace_urandom_read
  - drivers/char/random.c:__bpf_trace_push_to_pool
  - drivers/char/random.c:__bpf_trace_random__mix_pool_bytes
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error
  - drivers/iommu/intel/trace.c:__bpf_trace_dma_unmap
  - drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_block
  - drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx
  - drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip
  - drivers/ras/ras.c:__bpf_trace_memory_failure_event
  - net/core/devlink.c:__bpf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:__bpf_trace_devlink_health_report
  - net/core/devlink.c:__bpf_trace_devlink_hwerr
```
**Symbols:**

```
ffffffff811e8430-ffffffff811e84ca: bpf_trace_run3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_trace_run3(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e79b0)
Location: kernel/trace/bpf_trace.c:2123
Inline: False
Direct callers:
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush
  - arch/x86/kernel/irq.c:__bpf_trace_vector_setup
  - arch/x86/kernel/irq.c:__bpf_trace_vector_teardown
  - arch/x86/kernel/irq.c:__bpf_trace_vector_alloc_managed
  - arch/x86/kernel/nmi.c:__bpf_trace_nmi_handler
  - arch/x86/mm/fault.c:__bpf_trace_x86_exceptions
  - kernel/softirq.c:__bpf_trace_irq_handler_exit
  - kernel/signal.c:__bpf_trace_signal_deliver
  - kernel/workqueue.c:__bpf_trace_workqueue_queue_work
  - kernel/sched/core.c:__bpf_trace_sched_move_numa
  - kernel/sched/core.c:__bpf_trace_sched_stat_runtime
  - kernel/sched/core.c:__bpf_trace_sched_process_exec
  - kernel/sched/core.c:__bpf_trace_sched_switch
  - kernel/time/timer.c:__bpf_trace_hrtimer_init
  - kernel/time/timer.c:__bpf_trace_timer_start
  - kernel/module.c:__bpf_trace_module_request
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event
  - kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_update
  - kernel/trace/power-traces.c:__bpf_trace_suspend_resume
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:__bpf_trace_powernv_throttle
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int
  - kernel/bpf/core.c:__bpf_trace_xdp_exception
  - mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake
  - mm/percpu.c:__bpf_trace_percpu_free_percpu
  - mm/slab_common.c:__bpf_trace_rss_stat
  - mm/compaction.c:__bpf_trace_kcompactd_wake_template
  - mm/compaction.c:__bpf_trace_mm_compaction_suitable_template
  - mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:__bpf_trace_mm_compaction_migratepages
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page
  - mm/page_isolation.c:__bpf_trace_test_pages_isolated
  - fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:__bpf_trace_flush_foreign
  - fs/fs-writeback.c:__bpf_trace_inode_switch_wbs
  - fs/fs-writeback.c:__bpf_trace_inode_foreign_history
  - fs/io_uring.c:__bpf_trace_io_uring_task_run
  - fs/io_uring.c:__bpf_trace_io_uring_complete
  - fs/io_uring.c:__bpf_trace_io_uring_link
  - fs/io_uring.c:__bpf_trace_io_uring_defer
  - fs/dax.c:__bpf_trace_dax_insert_mapping
  - fs/dax.c:__bpf_trace_dax_pte_fault_class
  - fs/locks.c:__bpf_trace_leases_conflict
  - fs/locks.c:__bpf_trace_filelock_lock
  - fs/locks.c:__bpf_trace_locks_get_lock_context
  - fs/iomap/trace.c:__bpf_trace_iomap_range_class
  - fs/ext4/super.c:__bpf_trace_ext4_error
  - fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:__bpf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:__bpf_trace_ext4_read_block_bitmap_load
  - fs/ext4/super.c:__bpf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:__bpf_trace_ext4_discard_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_da_write_pages
  - block/blk-core.c:__bpf_trace_block_unplug
  - block/blk-core.c:__bpf_trace_block_rq_complete
  - arch/x86/lib/msr.c:__bpf_trace_msr_trace_class
  - drivers/clk/clk.c:__bpf_trace_clk_rate_range
  - drivers/regulator/core.c:__bpf_trace_regulator_range
  - drivers/char/random.c:__bpf_trace_urandom_read
  - drivers/char/random.c:__bpf_trace_push_to_pool
  - drivers/char/random.c:__bpf_trace_random__mix_pool_bytes
  - drivers/iommu/intel/trace.c:__bpf_trace_dma_unmap
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error
  - drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_block
  - drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx
  - drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip
  - drivers/devfreq/devfreq.c:__bpf_trace_devfreq_frequency
  - drivers/ras/ras.c:__bpf_trace_memory_failure_event
  - net/core/devlink.c:__bpf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:__bpf_trace_devlink_hwerr
```
**Symbols:**

```
ffffffff811e79b0-ffffffff811e7a4f: bpf_trace_run3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_trace_run3(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e8800)
Location: kernel/trace/bpf_trace.c:1819
Inline: False
Direct callers:
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush
  - arch/x86/kernel/irq.c:__bpf_trace_vector_setup
  - arch/x86/kernel/irq.c:__bpf_trace_vector_teardown
  - arch/x86/kernel/irq.c:__bpf_trace_vector_alloc_managed
  - arch/x86/kernel/nmi.c:__bpf_trace_nmi_handler
  - arch/x86/mm/fault.c:__bpf_trace_x86_exceptions
  - kernel/softirq.c:__bpf_trace_irq_handler_exit
  - kernel/signal.c:__bpf_trace_signal_deliver
  - kernel/workqueue.c:__bpf_trace_workqueue_queue_work
  - kernel/sched/core.c:__bpf_trace_sched_move_numa
  - kernel/sched/core.c:__bpf_trace_sched_stat_runtime
  - kernel/sched/core.c:__bpf_trace_sched_process_exec
  - kernel/sched/core.c:__bpf_trace_sched_switch
  - kernel/time/timer.c:__bpf_trace_hrtimer_init
  - kernel/time/timer.c:__bpf_trace_timer_start
  - kernel/module.c:__bpf_trace_module_request
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event
  - kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_update
  - kernel/trace/power-traces.c:__bpf_trace_suspend_resume
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:__bpf_trace_powernv_throttle
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int
  - kernel/bpf/core.c:__bpf_trace_xdp_exception
  - mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake
  - mm/percpu.c:__bpf_trace_percpu_free_percpu
  - mm/slab_common.c:__bpf_trace_rss_stat
  - mm/slab_common.c:__bpf_trace_kmem_cache_free
  - mm/compaction.c:__bpf_trace_kcompactd_wake_template
  - mm/compaction.c:__bpf_trace_mm_compaction_suitable_template
  - mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:__bpf_trace_mm_compaction_migratepages
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page
  - mm/page_isolation.c:__bpf_trace_test_pages_isolated
  - fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:__bpf_trace_flush_foreign
  - fs/fs-writeback.c:__bpf_trace_inode_switch_wbs
  - fs/fs-writeback.c:__bpf_trace_inode_foreign_history
  - fs/io_uring.c:__bpf_trace_io_uring_task_run
  - fs/io_uring.c:__bpf_trace_io_uring_link
  - fs/io_uring.c:__bpf_trace_io_uring_defer
  - fs/dax.c:__bpf_trace_dax_insert_mapping
  - fs/dax.c:__bpf_trace_dax_pte_fault_class
  - fs/locks.c:__bpf_trace_leases_conflict
  - fs/locks.c:__bpf_trace_filelock_lock
  - fs/locks.c:__bpf_trace_locks_get_lock_context
  - fs/iomap/trace.c:__bpf_trace_iomap_range_class
  - fs/ext4/super.c:__bpf_trace_ext4_error
  - fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:__bpf_trace_ext4_read_block_bitmap_load
  - fs/ext4/super.c:__bpf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:__bpf_trace_ext4_discard_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_da_write_pages
  - block/blk-core.c:__bpf_trace_block_unplug
  - block/blk-core.c:__bpf_trace_block_rq_complete
  - arch/x86/lib/msr.c:__bpf_trace_msr_trace_class
  - drivers/clk/clk.c:__bpf_trace_clk_rate_range
  - drivers/regulator/core.c:__bpf_trace_regulator_range
  - drivers/char/random.c:__bpf_trace_urandom_read
  - drivers/char/random.c:__bpf_trace_random__mix_pool_bytes
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error
  - drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_block
  - drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx
  - drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip
  - drivers/devfreq/devfreq.c:__bpf_trace_devfreq_frequency
  - drivers/ras/ras.c:__bpf_trace_memory_failure_event
  - net/core/devlink.c:__bpf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:__bpf_trace_devlink_hwerr
```
**Symbols:**

```
ffffffff811e8800-ffffffff811e8898: bpf_trace_run3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_trace_run3(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81219470)
Location: kernel/trace/bpf_trace.c:1903
Inline: False
Direct callers:
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush
  - arch/x86/kernel/irq.c:__bpf_trace_vector_setup
  - arch/x86/kernel/irq.c:__bpf_trace_vector_teardown
  - arch/x86/kernel/irq.c:__bpf_trace_vector_alloc_managed
  - arch/x86/kernel/nmi.c:__bpf_trace_nmi_handler
  - arch/x86/mm/fault.c:__bpf_trace_x86_exceptions
  - kernel/softirq.c:__bpf_trace_irq_handler_exit
  - kernel/signal.c:__bpf_trace_signal_deliver
  - kernel/workqueue.c:__bpf_trace_workqueue_queue_work
  - kernel/sched/core.c:__bpf_trace_sched_move_numa
  - kernel/sched/core.c:__bpf_trace_sched_stat_runtime
  - kernel/sched/core.c:__bpf_trace_sched_process_exec
  - kernel/sched/core.c:__bpf_trace_sched_switch
  - kernel/time/timer.c:__bpf_trace_hrtimer_init
  - kernel/time/timer.c:__bpf_trace_timer_start
  - kernel/module.c:__bpf_trace_module_request
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event
  - kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_update
  - kernel/trace/power-traces.c:__bpf_trace_suspend_resume
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:__bpf_trace_powernv_throttle
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int
  - kernel/bpf/core.c:__bpf_trace_xdp_exception
  - mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake
  - mm/percpu.c:__bpf_trace_percpu_free_percpu
  - mm/slab_common.c:__bpf_trace_rss_stat
  - mm/slab_common.c:__bpf_trace_kmem_cache_free
  - mm/compaction.c:__bpf_trace_kcompactd_wake_template
  - mm/compaction.c:__bpf_trace_mm_compaction_suitable_template
  - mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:__bpf_trace_mm_compaction_migratepages
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page
  - mm/page_isolation.c:__bpf_trace_test_pages_isolated
  - fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:__bpf_trace_flush_foreign
  - fs/fs-writeback.c:__bpf_trace_inode_switch_wbs
  - fs/fs-writeback.c:__bpf_trace_inode_foreign_history
  - fs/io_uring.c:__bpf_trace_io_uring_link
  - fs/io_uring.c:__bpf_trace_io_uring_defer
  - fs/dax.c:__bpf_trace_dax_insert_mapping
  - fs/dax.c:__bpf_trace_dax_pte_fault_class
  - fs/locks.c:__bpf_trace_leases_conflict
  - fs/locks.c:__bpf_trace_filelock_lock
  - fs/locks.c:__bpf_trace_locks_get_lock_context
  - fs/iomap/trace.c:__bpf_trace_iomap_iter
  - fs/iomap/trace.c:__bpf_trace_iomap_range_class
  - fs/ext4/super.c:__bpf_trace_ext4_error
  - fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:__bpf_trace_ext4_read_block_bitmap_load
  - fs/ext4/super.c:__bpf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:__bpf_trace_ext4_discard_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_da_write_pages
  - fs/jbd2/journal.c:__bpf_trace_jbd2_journal_shrink
  - block/blk-core.c:__bpf_trace_block_unplug
  - block/blk-core.c:__bpf_trace_block_rq_complete
  - arch/x86/lib/msr.c:__bpf_trace_msr_trace_class
  - drivers/clk/clk.c:__bpf_trace_clk_rate_range
  - drivers/regulator/core.c:__bpf_trace_regulator_range
  - drivers/char/random.c:__bpf_trace_urandom_read
  - drivers/char/random.c:__bpf_trace_random__mix_pool_bytes
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error
  - drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_block
  - drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx
  - drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip
  - drivers/platform/chrome/cros_ec_trace.c:__bpf_trace_cros_ec_sensorhub_filter
  - drivers/devfreq/devfreq.c:__bpf_trace_devfreq_frequency
  - drivers/ras/ras.c:__bpf_trace_memory_failure_event
  - net/core/net-traces.c:__bpf_trace_qdisc_enqueue
  - net/core/devlink.c:__bpf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:__bpf_trace_devlink_hwerr
```
**Symbols:**

```
ffffffff81219470-ffffffff81219504: bpf_trace_run3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_trace_run3(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81257d10)
Location: kernel/trace/bpf_trace.c:2084
Inline: False
Direct callers:
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush
  - arch/x86/kernel/irq.c:__bpf_trace_vector_setup
  - arch/x86/kernel/irq.c:__bpf_trace_vector_teardown
  - arch/x86/kernel/irq.c:__bpf_trace_vector_alloc_managed
  - arch/x86/kernel/nmi.c:__bpf_trace_nmi_handler
  - arch/x86/mm/fault.c:__bpf_trace_x86_exceptions
  - kernel/softirq.c:__bpf_trace_irq_handler_exit
  - kernel/signal.c:__bpf_trace_signal_deliver
  - kernel/workqueue.c:__bpf_trace_workqueue_queue_work
  - kernel/sched/core.c:__bpf_trace_sched_move_numa
  - kernel/sched/core.c:__bpf_trace_sched_stat_runtime
  - kernel/sched/core.c:__bpf_trace_sched_process_exec
  - kernel/dma/swiotlb.c:__bpf_trace_swiotlb_bounced
  - kernel/module/main.c:__bpf_trace_module_request
  - kernel/time/timer.c:__bpf_trace_hrtimer_init
  - kernel/time/timer.c:__bpf_trace_timer_start
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event
  - kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_update
  - kernel/trace/power-traces.c:__bpf_trace_suspend_resume
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:__bpf_trace_powernv_throttle
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int
  - kernel/bpf/core.c:__bpf_trace_xdp_exception
  - mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake
  - mm/percpu.c:__bpf_trace_percpu_free_percpu
  - mm/slab_common.c:__bpf_trace_rss_stat
  - mm/slab_common.c:__bpf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:__bpf_trace_kmem_cache_free
  - mm/compaction.c:__bpf_trace_kcompactd_wake_template
  - mm/compaction.c:__bpf_trace_mm_compaction_suitable_template
  - mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages
  - mm/mmap_lock.c:__bpf_trace_mmap_lock
  - mm/rmap.c:__bpf_trace_migration_pte
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page
  - mm/page_isolation.c:__bpf_trace_test_pages_isolated
  - fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:__bpf_trace_flush_foreign
  - fs/fs-writeback.c:__bpf_trace_inode_switch_wbs
  - fs/fs-writeback.c:__bpf_trace_inode_foreign_history
  - fs/dax.c:__bpf_trace_dax_insert_mapping
  - fs/dax.c:__bpf_trace_dax_pte_fault_class
  - fs/locks.c:__bpf_trace_leases_conflict
  - fs/locks.c:__bpf_trace_filelock_lock
  - fs/locks.c:__bpf_trace_locks_get_lock_context
  - fs/iomap/trace.c:__bpf_trace_iomap_iter
  - fs/iomap/trace.c:__bpf_trace_iomap_range_class
  - fs/ext4/super.c:__bpf_trace_ext4_fc_cleanup
  - fs/ext4/super.c:__bpf_trace_ext4_error
  - fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:__bpf_trace_ext4_read_block_bitmap_load
  - fs/ext4/super.c:__bpf_trace_ext4_da_write_pages
  - fs/ext4/super.c:__bpf_trace_ext4__write_begin
  - fs/jbd2/journal.c:__bpf_trace_jbd2_journal_shrink
  - block/blk-core.c:__bpf_trace_block_unplug
  - block/blk-core.c:__bpf_trace_block_rq_completion
  - io_uring/io_uring.c:__bpf_trace_io_uring_link
  - arch/x86/lib/msr.c:__bpf_trace_msr_trace_class
  - drivers/clk/clk.c:__bpf_trace_clk_rate_range
  - drivers/regulator/core.c:__bpf_trace_regulator_range
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error
  - drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_block
  - drivers/ata/libata-core.c:__bpf_trace_ata_link_reset_end_template
  - drivers/ata/libata-core.c:__bpf_trace_ata_link_reset_begin_template
  - drivers/ata/libata-core.c:__bpf_trace_ata_exec_command_template
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx
  - drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip
  - drivers/devfreq/devfreq.c:__bpf_trace_devfreq_frequency
  - drivers/ras/ras.c:__bpf_trace_memory_failure_event
  - net/core/net-traces.c:__bpf_trace_qdisc_enqueue
  - net/core/net-traces.c:__bpf_trace_kfree_skb
  - net/core/devlink.c:__bpf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:__bpf_trace_devlink_hwerr
```
**Symbols:**

```
ffffffff81257d10-ffffffff81257db7: bpf_trace_run3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_trace_run3(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a73e0)
Location: kernel/trace/bpf_trace.c:2307
Inline: False
Direct callers:
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush
  - arch/x86/kernel/irq.c:__bpf_trace_vector_setup
  - arch/x86/kernel/irq.c:__bpf_trace_vector_teardown
  - arch/x86/kernel/irq.c:__bpf_trace_vector_alloc_managed
  - arch/x86/kernel/nmi.c:__bpf_trace_nmi_handler
  - arch/x86/mm/fault.c:__bpf_trace_x86_exceptions
  - kernel/softirq.c:__bpf_trace_irq_handler_exit
  - kernel/signal.c:__bpf_trace_signal_deliver
  - kernel/workqueue.c:__bpf_trace_workqueue_queue_work
  - kernel/sched/core.c:__bpf_trace_sched_move_numa
  - kernel/sched/core.c:__bpf_trace_sched_stat_runtime
  - kernel/sched/core.c:__bpf_trace_sched_process_exec
  - kernel/dma/swiotlb.c:__bpf_trace_swiotlb_bounced
  - kernel/module/main.c:__bpf_trace_module_request
  - kernel/time/timer.c:__bpf_trace_hrtimer_init
  - kernel/time/timer.c:__bpf_trace_timer_start
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event
  - kernel/trace/power-traces.c:__bpf_trace_guest_halt_poll_ns
  - kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_update
  - kernel/trace/power-traces.c:__bpf_trace_suspend_resume
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:__bpf_trace_powernv_throttle
  - kernel/trace/power-traces.c:__bpf_trace_cpu_idle_miss
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int
  - kernel/trace/rv/rv.c:__bpf_trace_error_da_monitor_id
  - kernel/bpf/core.c:__bpf_trace_xdp_exception
  - mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake
  - mm/percpu.c:__bpf_trace_percpu_free_percpu
  - mm/slab_common.c:__bpf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:__bpf_trace_kmem_cache_free
  - mm/compaction.c:__bpf_trace_kcompactd_wake_template
  - mm/compaction.c:__bpf_trace_mm_compaction_suitable_template
  - mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages
  - mm/mmap_lock.c:__bpf_trace_mmap_lock
  - mm/mmap.c:__bpf_trace_vma_mas_szero
  - mm/rmap.c:__bpf_trace_migration_pte
  - mm/vmalloc.c:__bpf_trace_free_vmap_area_noflush
  - mm/vmalloc.c:__bpf_trace_purge_vmap_area_lazy
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page
  - mm/page_isolation.c:__bpf_trace_test_pages_isolated
  - fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:__bpf_trace_flush_foreign
  - fs/fs-writeback.c:__bpf_trace_inode_switch_wbs
  - fs/fs-writeback.c:__bpf_trace_inode_foreign_history
  - fs/dax.c:__bpf_trace_dax_insert_mapping
  - fs/dax.c:__bpf_trace_dax_pte_fault_class
  - fs/locks.c:__bpf_trace_leases_conflict
  - fs/locks.c:__bpf_trace_filelock_lock
  - fs/locks.c:__bpf_trace_locks_get_lock_context
  - fs/iomap/trace.c:__bpf_trace_iomap_iter
  - fs/iomap/trace.c:__bpf_trace_iomap_range_class
  - fs/ext4/super.c:__bpf_trace_ext4_fc_cleanup
  - fs/ext4/super.c:__bpf_trace_ext4_error
  - fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:__bpf_trace_ext4_read_block_bitmap_load
  - fs/ext4/super.c:__bpf_trace_ext4_da_write_pages
  - fs/ext4/super.c:__bpf_trace_ext4__write_begin
  - fs/jbd2/journal.c:__bpf_trace_jbd2_journal_shrink
  - block/blk-core.c:__bpf_trace_block_unplug
  - block/blk-core.c:__bpf_trace_block_rq_completion
  - io_uring/io_uring.c:__bpf_trace_io_uring_local_work_run
  - io_uring/io_uring.c:__bpf_trace_io_uring_task_work_run
  - io_uring/io_uring.c:__bpf_trace_io_uring_req_failed
  - io_uring/io_uring.c:__bpf_trace_io_uring_poll_arm
  - arch/x86/lib/msr.c:__bpf_trace_msr_trace_class
  - drivers/pwm/core.c:__bpf_trace_pwm
  - drivers/clk/clk.c:__bpf_trace_clk_rate_range
  - drivers/regulator/core.c:__bpf_trace_regulator_range
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error
  - drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_block
  - drivers/scsi/sd_zbc.c:__bpf_trace_scsi_prepare_zone_append
  - drivers/ata/libata-core.c:__bpf_trace_ata_link_reset_end_template
  - drivers/ata/libata-core.c:__bpf_trace_ata_link_reset_begin_template
  - drivers/ata/libata-core.c:__bpf_trace_ata_exec_command_template
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx
  - drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip
  - drivers/watchdog/watchdog_core.c:__bpf_trace_watchdog_set_timeout
  - drivers/devfreq/devfreq.c:__bpf_trace_devfreq_frequency
  - drivers/ras/ras.c:__bpf_trace_memory_failure_event
  - net/core/net-traces.c:__bpf_trace_qdisc_enqueue
  - net/core/net-traces.c:__bpf_trace_kfree_skb
  - net/core/devlink.c:__bpf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:__bpf_trace_devlink_hwerr
```
**Symbols:**

```
ffffffff812a73e0-ffffffff812a74b0: bpf_trace_run3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_trace_run3(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812c9670)
Location: kernel/trace/bpf_trace.c:2316
Inline: False
Direct callers:
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush
  - arch/x86/kernel/irq.c:__bpf_trace_vector_setup
  - arch/x86/kernel/irq.c:__bpf_trace_vector_teardown
  - arch/x86/kernel/irq.c:__bpf_trace_vector_alloc_managed
  - arch/x86/kernel/nmi.c:__bpf_trace_nmi_handler
  - arch/x86/mm/fault.c:__bpf_trace_x86_exceptions
  - kernel/softirq.c:__bpf_trace_irq_handler_exit
  - kernel/signal.c:__bpf_trace_signal_deliver
  - kernel/workqueue.c:__bpf_trace_workqueue_queue_work
  - kernel/sched/core.c:__bpf_trace_ipi_send_cpumask
  - kernel/sched/core.c:__bpf_trace_ipi_send_cpu
  - kernel/sched/core.c:__bpf_trace_sched_move_numa
  - kernel/sched/core.c:__bpf_trace_sched_stat_runtime
  - kernel/sched/core.c:__bpf_trace_sched_process_exec
  - kernel/dma/swiotlb.c:__bpf_trace_swiotlb_bounced
  - kernel/module/main.c:__bpf_trace_module_request
  - kernel/time/timer.c:__bpf_trace_hrtimer_init
  - kernel/time/timer.c:__bpf_trace_timer_start
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event
  - kernel/trace/trace_osnoise.c:__bpf_trace_sample_threshold
  - kernel/trace/trace_osnoise.c:__bpf_trace_softirq_noise
  - kernel/trace/trace_osnoise.c:__bpf_trace_thread_noise
  - kernel/trace/power-traces.c:__bpf_trace_guest_halt_poll_ns
  - kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_update
  - kernel/trace/power-traces.c:__bpf_trace_suspend_resume
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:__bpf_trace_powernv_throttle
  - kernel/trace/power-traces.c:__bpf_trace_cpu_idle_miss
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int
  - kernel/trace/rv/rv.c:__bpf_trace_error_da_monitor_id
  - kernel/bpf/core.c:__bpf_trace_xdp_exception
  - mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake
  - mm/percpu.c:__bpf_trace_percpu_free_percpu
  - mm/slab_common.c:__bpf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:__bpf_trace_kmem_cache_free
  - mm/compaction.c:__bpf_trace_kcompactd_wake_template
  - mm/compaction.c:__bpf_trace_mm_compaction_suitable_template
  - mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages
  - mm/mmap_lock.c:__bpf_trace_mmap_lock
  - mm/mmap.c:__bpf_trace_vma_mas_szero
  - mm/rmap.c:__bpf_trace_migration_pte
  - mm/vmalloc.c:__bpf_trace_free_vmap_area_noflush
  - mm/vmalloc.c:__bpf_trace_purge_vmap_area_lazy
  - mm/ksm.c:__bpf_trace_ksm_remove_rmap_item
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page
  - mm/page_isolation.c:__bpf_trace_test_pages_isolated
  - fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:__bpf_trace_flush_foreign
  - fs/fs-writeback.c:__bpf_trace_inode_switch_wbs
  - fs/fs-writeback.c:__bpf_trace_inode_foreign_history
  - fs/dax.c:__bpf_trace_dax_insert_mapping
  - fs/dax.c:__bpf_trace_dax_pte_fault_class
  - fs/locks.c:__bpf_trace_leases_conflict
  - fs/locks.c:__bpf_trace_filelock_lock
  - fs/locks.c:__bpf_trace_locks_get_lock_context
  - fs/iomap/trace.c:__bpf_trace_iomap_dio_complete
  - fs/iomap/trace.c:__bpf_trace_iomap_iter
  - fs/iomap/trace.c:__bpf_trace_iomap_range_class
  - fs/ext4/super.c:__bpf_trace_ext4_fc_cleanup
  - fs/ext4/super.c:__bpf_trace_ext4_error
  - fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:__bpf_trace_ext4_read_block_bitmap_load
  - fs/ext4/super.c:__bpf_trace_ext4_da_write_pages
  - fs/ext4/super.c:__bpf_trace_ext4__write_begin
  - fs/jbd2/journal.c:__bpf_trace_jbd2_journal_shrink
  - block/blk-core.c:__bpf_trace_block_unplug
  - block/blk-core.c:__bpf_trace_block_rq_completion
  - io_uring/io_uring.c:__bpf_trace_io_uring_local_work_run
  - io_uring/io_uring.c:__bpf_trace_io_uring_task_work_run
  - io_uring/io_uring.c:__bpf_trace_io_uring_req_failed
  - io_uring/io_uring.c:__bpf_trace_io_uring_poll_arm
  - arch/x86/lib/msr.c:__bpf_trace_msr_trace_class
  - drivers/pwm/core.c:__bpf_trace_pwm
  - drivers/clk/clk.c:__bpf_trace_clk_rate_range
  - drivers/regulator/core.c:__bpf_trace_regulator_range
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error
  - drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_block
  - drivers/scsi/sd_zbc.c:__bpf_trace_scsi_prepare_zone_append
  - drivers/ata/libata-core.c:__bpf_trace_ata_link_reset_end_template
  - drivers/ata/libata-core.c:__bpf_trace_ata_link_reset_begin_template
  - drivers/ata/libata-core.c:__bpf_trace_ata_exec_command_template
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx
  - drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip
  - drivers/watchdog/watchdog_core.c:__bpf_trace_watchdog_set_timeout
  - drivers/devfreq/devfreq.c:__bpf_trace_devfreq_frequency
  - drivers/ras/ras.c:__bpf_trace_memory_failure_event
  - net/core/net-traces.c:__bpf_trace_qdisc_enqueue
  - net/core/net-traces.c:__bpf_trace_kfree_skb
  - net/devlink/leftover.c:__bpf_trace_devlink_health_reporter_state_update
  - net/devlink/leftover.c:__bpf_trace_devlink_hwerr
  - net/handshake/trace.c:__bpf_trace_handshake_event_class
```
**Symbols:**

```
ffffffff812c9670-ffffffff812c9740: bpf_trace_run3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_trace_run3(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e4770)
Location: kernel/trace/bpf_trace.c:2421
Inline: False
Direct callers:
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush
  - arch/x86/kernel/irq.c:__bpf_trace_vector_setup
  - arch/x86/kernel/irq.c:__bpf_trace_vector_teardown
  - arch/x86/kernel/irq.c:__bpf_trace_vector_alloc_managed
  - arch/x86/kernel/nmi.c:__bpf_trace_nmi_handler
  - arch/x86/mm/fault.c:__bpf_trace_x86_exceptions
  - kernel/softirq.c:__bpf_trace_irq_handler_exit
  - kernel/signal.c:__bpf_trace_signal_deliver
  - kernel/workqueue.c:__bpf_trace_workqueue_queue_work
  - kernel/sched/core.c:__bpf_trace_ipi_send_cpumask
  - kernel/sched/core.c:__bpf_trace_ipi_send_cpu
  - kernel/sched/core.c:__bpf_trace_sched_skip_vma_numa
  - kernel/sched/core.c:__bpf_trace_sched_move_numa
  - kernel/sched/core.c:__bpf_trace_sched_process_exec
  - kernel/dma/swiotlb.c:__bpf_trace_swiotlb_bounced
  - kernel/module/main.c:__bpf_trace_module_request
  - kernel/time/timer.c:__bpf_trace_hrtimer_init
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event
  - kernel/trace/trace_osnoise.c:__bpf_trace_sample_threshold
  - kernel/trace/trace_osnoise.c:__bpf_trace_softirq_noise
  - kernel/trace/trace_osnoise.c:__bpf_trace_thread_noise
  - kernel/trace/power-traces.c:__bpf_trace_guest_halt_poll_ns
  - kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_update
  - kernel/trace/power-traces.c:__bpf_trace_suspend_resume
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:__bpf_trace_powernv_throttle
  - kernel/trace/power-traces.c:__bpf_trace_cpu_idle_miss
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int
  - kernel/trace/rv/rv.c:__bpf_trace_error_da_monitor_id
  - kernel/bpf/core.c:__bpf_trace_xdp_exception
  - mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake
  - mm/percpu.c:__bpf_trace_percpu_free_percpu
  - mm/slab_common.c:__bpf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:__bpf_trace_kmem_cache_free
  - mm/compaction.c:__bpf_trace_kcompactd_wake_template
  - mm/compaction.c:__bpf_trace_mm_compaction_suitable_template
  - mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages
  - mm/mmap_lock.c:__bpf_trace_mmap_lock
  - mm/mmap.c:__bpf_trace_vma_mas_szero
  - mm/rmap.c:__bpf_trace_migration_pte
  - mm/vmalloc.c:__bpf_trace_free_vmap_area_noflush
  - mm/vmalloc.c:__bpf_trace_purge_vmap_area_lazy
  - mm/ksm.c:__bpf_trace_ksm_advisor
  - mm/ksm.c:__bpf_trace_ksm_remove_rmap_item
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page
  - mm/page_isolation.c:__bpf_trace_test_pages_isolated
  - fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:__bpf_trace_flush_foreign
  - fs/fs-writeback.c:__bpf_trace_inode_switch_wbs
  - fs/fs-writeback.c:__bpf_trace_inode_foreign_history
  - fs/dax.c:__bpf_trace_dax_insert_mapping
  - fs/dax.c:__bpf_trace_dax_pte_fault_class
  - fs/locks.c:__bpf_trace_leases_conflict
  - fs/locks.c:__bpf_trace_filelock_lock
  - fs/locks.c:__bpf_trace_locks_get_lock_context
  - fs/iomap/trace.c:__bpf_trace_iomap_dio_complete
  - fs/iomap/trace.c:__bpf_trace_iomap_iter
  - fs/iomap/trace.c:__bpf_trace_iomap_range_class
  - fs/ext4/super.c:__bpf_trace_ext4_fc_cleanup
  - fs/ext4/super.c:__bpf_trace_ext4_error
  - fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:__bpf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:__bpf_trace_ext4_read_block_bitmap_load
  - fs/ext4/super.c:__bpf_trace_ext4_da_write_pages
  - fs/ext4/super.c:__bpf_trace_ext4__write_begin
  - fs/jbd2/journal.c:__bpf_trace_jbd2_journal_shrink
  - block/blk-core.c:__bpf_trace_block_unplug
  - block/blk-core.c:__bpf_trace_block_rq_completion
  - io_uring/io_uring.c:__bpf_trace_io_uring_local_work_run
  - io_uring/io_uring.c:__bpf_trace_io_uring_task_work_run
  - io_uring/io_uring.c:__bpf_trace_io_uring_req_failed
  - io_uring/io_uring.c:__bpf_trace_io_uring_poll_arm
  - arch/x86/lib/msr.c:__bpf_trace_msr_trace_class
  - drivers/pwm/core.c:__bpf_trace_pwm
  - drivers/clk/clk.c:__bpf_trace_clk_rate_range
  - drivers/regulator/core.c:__bpf_trace_regulator_range
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error
  - drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_block
  - drivers/scsi/sd_zbc.c:__bpf_trace_scsi_prepare_zone_append
  - drivers/ata/libata-core.c:__bpf_trace_ata_link_reset_end_template
  - drivers/ata/libata-core.c:__bpf_trace_ata_link_reset_begin_template
  - drivers/ata/libata-core.c:__bpf_trace_ata_exec_command_template
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx
  - drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip
  - drivers/watchdog/watchdog_core.c:__bpf_trace_watchdog_set_timeout
  - drivers/devfreq/devfreq.c:__bpf_trace_devfreq_frequency
  - drivers/ras/ras.c:__bpf_trace_memory_failure_event
  - net/core/net-traces.c:__bpf_trace_qdisc_enqueue
  - net/core/net-traces.c:__bpf_trace_kfree_skb
  - net/devlink/core.c:__bpf_trace_devlink_health_reporter_state_update
  - net/devlink/core.c:__bpf_trace_devlink_hwerr
  - net/handshake/trace.c:__bpf_trace_handshake_alert_class
  - net/handshake/trace.c:__bpf_trace_handshake_event_class
```
**Symbols:**

```
ffffffff812e4770-ffffffff812e4840: bpf_trace_run3 (STB_GLOBAL)
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
void bpf_trace_run3(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffff80001024dea0)
Location: kernel/trace/bpf_trace.c:1373
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:__bpf_trace_kvm_set_irq
  - virt/kvm/kvm_main.c:__bpf_trace_kvm_vcpu_wakeup
  - virt/kvm/arm/arm.c:__bpf_trace_kvm_timer_update_irq
  - virt/kvm/arm/arm.c:__bpf_trace_kvm_toggle_cache
  - virt/kvm/arm/arm.c:__bpf_trace_kvm_mmio_emulate
  - virt/kvm/arm/arm.c:__bpf_trace_kvm_exit
  - arch/arm64/kvm/handle_exit.c:__bpf_trace_kvm_sys_access
  - arch/arm64/kvm/handle_exit.c:__bpf_trace_kvm_hvc_arm64
  - virt/kvm/arm/vgic/vgic.c:__bpf_trace_vgic_update_irq_pending
  - kernel/softirq.c:__bpf_trace_irq_handler_exit
  - kernel/signal.c:__bpf_trace_signal_deliver
  - kernel/workqueue.c:__bpf_trace_workqueue_queue_work
  - kernel/sched/core.c:__bpf_trace_sched_move_task_template
  - kernel/sched/core.c:__bpf_trace_sched_stat_runtime
  - kernel/sched/core.c:__bpf_trace_sched_process_exec
  - kernel/sched/core.c:__bpf_trace_sched_switch
  - kernel/time/timer.c:__bpf_trace_itimer_expire
  - kernel/time/timer.c:__bpf_trace_itimer_state
  - kernel/time/timer.c:__bpf_trace_hrtimer_init
  - kernel/time/timer.c:__bpf_trace_timer_start
  - kernel/module.c:__bpf_trace_module_request
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event
  - kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_update
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:__bpf_trace_suspend_resume
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:__bpf_trace_powernv_throttle
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int
  - kernel/bpf/core.c:__bpf_trace_xdp_exception
  - mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake
  - mm/percpu.c:__bpf_trace_percpu_free_percpu
  - mm/compaction.c:__bpf_trace_kcompactd_wake_template
  - mm/compaction.c:__bpf_trace_mm_compaction_suitable_template
  - mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:__bpf_trace_mm_compaction_migratepages
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page
  - mm/page_isolation.c:__bpf_trace_test_pages_isolated
  - mm/cma.c:__bpf_trace_cma_release
  - fs/open.c:__bpf_trace_do_sys_open
  - fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:__bpf_trace_writeback_queue_io
  - fs/fs-writeback.c:__bpf_trace_flush_foreign
  - fs/fs-writeback.c:__bpf_trace_inode_switch_wbs
  - fs/fs-writeback.c:__bpf_trace_inode_foreign_history
  - fs/dax.c:__bpf_trace_dax_insert_mapping
  - fs/dax.c:__bpf_trace_dax_pte_fault_class
  - fs/locks.c:__bpf_trace_leases_conflict
  - fs/locks.c:__bpf_trace_filelock_lock
  - fs/locks.c:__bpf_trace_locks_get_lock_context
  - fs/ext4/super.c:__bpf_trace_ext4_error
  - fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:__bpf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:__bpf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:__bpf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:__bpf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:__bpf_trace_ext4_forget
  - fs/ext4/super.c:__bpf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:__bpf_trace_ext4_discard_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:__bpf_trace_ext4_da_write_pages
  - fs/ext4/super.c:__bpf_trace_ext4_allocate_inode
  - fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:__bpf_trace_jbd2_run_stats
  - block/blk-core.c:__bpf_trace_block_split
  - block/blk-core.c:__bpf_trace_block_unplug
  - block/blk-core.c:__bpf_trace_block_bio_merge
  - block/blk-core.c:__bpf_trace_block_rq_complete
  - drivers/regulator/core.c:__bpf_trace_regulator_range
  - drivers/char/random.c:__bpf_trace_urandom_read
  - drivers/char/random.c:__bpf_trace_push_to_pool
  - drivers/char/random.c:__bpf_trace_random__mix_pool_bytes
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:__bpf_trace_unmap
  - drivers/iommu/iommu-traces.c:__bpf_trace_map
  - drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_block
  - drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx
  - drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip
  - drivers/ras/ras.c:__bpf_trace_memory_failure_event
  - net/core/net-traces.c:__bpf_trace_inet_sock_set_state
  - net/core/net-traces.c:__bpf_trace_napi_poll
  - net/core/devlink.c:__bpf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:__bpf_trace_devlink_health_report
  - net/core/devlink.c:__bpf_trace_devlink_hwerr
```
**Symbols:**

```
ffff80001024dea0-ffff80001024df58: bpf_trace_run3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_trace_run3(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c047ee68)
Location: kernel/trace/bpf_trace.c:1373
Inline: False
Direct callers:
  - kernel/softirq.c:__bpf_trace_irq_handler_exit
  - kernel/signal.c:__bpf_trace_signal_deliver
  - kernel/workqueue.c:__bpf_trace_workqueue_queue_work
  - kernel/sched/core.c:__bpf_trace_sched_move_task_template
  - kernel/sched/core.c:__bpf_trace_sched_stat_runtime
  - kernel/sched/core.c:__bpf_trace_sched_process_exec
  - kernel/sched/core.c:__bpf_trace_sched_switch
  - kernel/time/timer.c:__bpf_trace_itimer_expire
  - kernel/time/timer.c:__bpf_trace_itimer_state
  - kernel/time/timer.c:__bpf_trace_hrtimer_init
  - kernel/time/timer.c:__bpf_trace_timer_start
  - kernel/module.c:__bpf_trace_module_request
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event
  - kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_update
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:__bpf_trace_clock
  - kernel/trace/power-traces.c:__bpf_trace_suspend_resume
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:__bpf_trace_powernv_throttle
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int
  - kernel/bpf/core.c:__bpf_trace_xdp_exception
  - mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake
  - mm/percpu.c:__bpf_trace_percpu_free_percpu
  - mm/slab_common.c:__bpf_trace_mm_page
  - mm/compaction.c:__bpf_trace_kcompactd_wake_template
  - mm/compaction.c:__bpf_trace_mm_compaction_suitable_template
  - mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:__bpf_trace_mm_compaction_migratepages
  - mm/page_isolation.c:__bpf_trace_test_pages_isolated
  - mm/cma.c:__bpf_trace_cma_release
  - fs/open.c:__bpf_trace_do_sys_open
  - fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:__bpf_trace_writeback_queue_io
  - fs/fs-writeback.c:__bpf_trace_flush_foreign
  - fs/fs-writeback.c:__bpf_trace_inode_switch_wbs
  - fs/fs-writeback.c:__bpf_trace_inode_foreign_history
  - fs/locks.c:__bpf_trace_leases_conflict
  - fs/locks.c:__bpf_trace_filelock_lock
  - fs/locks.c:__bpf_trace_locks_get_lock_context
  - fs/ext4/super.c:__bpf_trace_ext4_error
  - fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:__bpf_trace_ext4_collapse_range
  - fs/ext4/super.c:__bpf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:__bpf_trace_ext4_get_reserved_cluster_alloc
  - fs/ext4/super.c:__bpf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:__bpf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:__bpf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:__bpf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:__bpf_trace_ext4_forget
  - fs/ext4/super.c:__bpf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:__bpf_trace_ext4_discard_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:__bpf_trace_ext4_da_write_pages
  - fs/ext4/super.c:__bpf_trace_ext4_allocate_inode
  - fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:__bpf_trace_jbd2_run_stats
  - block/blk-core.c:__bpf_trace_block_split
  - block/blk-core.c:__bpf_trace_block_unplug
  - block/blk-core.c:__bpf_trace_block_bio_merge
  - block/blk-core.c:__bpf_trace_block_bio_complete
  - block/blk-core.c:__bpf_trace_block_rq_complete
  - drivers/gpio/gpiolib.c:__bpf_trace_gpio_direction
  - drivers/dma/tegra20-apb-dma.c:__bpf_trace_tegra_dma_complete_cb
  - drivers/dma/tegra20-apb-dma.c:__bpf_trace_tegra_dma_tx_status
  - drivers/regulator/core.c:__bpf_trace_regulator_range
  - drivers/char/random.c:__bpf_trace_urandom_read
  - drivers/char/random.c:__bpf_trace_push_to_pool
  - drivers/char/random.c:__bpf_trace_random__mix_pool_bytes
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:__bpf_trace_map
  - drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_block
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_reg
  - drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx
  - drivers/usb/gadget/udc/trace.c:__bpf_trace_udc_log_req
  - drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_write
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip
  - sound/soc/soc-core.c:__bpf_trace_snd_soc_jack_report
  - sound/soc/soc-core.c:__bpf_trace_snd_soc_dapm_path
  - net/core/net-traces.c:__bpf_trace_page_pool_state_release
  - net/core/net-traces.c:__bpf_trace_inet_sock_set_state
  - net/core/net-traces.c:__bpf_trace_napi_poll
  - net/core/devlink.c:__bpf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:__bpf_trace_devlink_health_report
  - net/core/devlink.c:__bpf_trace_devlink_hwerr
```
**Symbols:**

```
c047ee68-c047ef7c: bpf_trace_run3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_trace_run3(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0000000002e7ca0)
Location: kernel/trace/bpf_trace.c:1373
Inline: False
Direct callers:
  - arch/powerpc/kernel/irq.c:__bpf_trace_hash_fault
  - arch/powerpc/kernel/irq.c:__bpf_trace_hcall_exit
  - kernel/softirq.c:__bpf_trace_irq_handler_exit
  - kernel/signal.c:__bpf_trace_signal_deliver
  - kernel/workqueue.c:__bpf_trace_workqueue_queue_work
  - kernel/sched/core.c:__bpf_trace_sched_move_task_template
  - kernel/sched/core.c:__bpf_trace_sched_stat_runtime
  - kernel/sched/core.c:__bpf_trace_sched_process_exec
  - kernel/sched/core.c:__bpf_trace_sched_switch
  - kernel/time/timer.c:__bpf_trace_itimer_expire
  - kernel/time/timer.c:__bpf_trace_itimer_state
  - kernel/time/timer.c:__bpf_trace_hrtimer_init
  - kernel/time/timer.c:__bpf_trace_timer_start
  - kernel/module.c:__bpf_trace_module_request
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event
  - kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_update
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:__bpf_trace_power_domain
  - kernel/trace/power-traces.c:__bpf_trace_clock
  - kernel/trace/power-traces.c:__bpf_trace_suspend_resume
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:__bpf_trace_powernv_throttle
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int
  - kernel/bpf/core.c:__bpf_trace_xdp_exception
  - mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake
  - mm/percpu.c:__bpf_trace_percpu_free_percpu
  - mm/slab_common.c:__bpf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:__bpf_trace_mm_page
  - mm/compaction.c:__bpf_trace_kcompactd_wake_template
  - mm/compaction.c:__bpf_trace_mm_compaction_suitable_template
  - mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:__bpf_trace_mm_compaction_migratepages
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page
  - mm/page_isolation.c:__bpf_trace_test_pages_isolated
  - mm/cma.c:__bpf_trace_cma_release
  - fs/open.c:__bpf_trace_do_sys_open
  - fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:__bpf_trace_writeback_queue_io
  - fs/fs-writeback.c:__bpf_trace_flush_foreign
  - fs/fs-writeback.c:__bpf_trace_inode_switch_wbs
  - fs/fs-writeback.c:__bpf_trace_inode_foreign_history
  - fs/dax.c:__bpf_trace_dax_writeback_one
  - fs/dax.c:__bpf_trace_dax_writeback_range_class
  - fs/dax.c:__bpf_trace_dax_insert_mapping
  - fs/dax.c:__bpf_trace_dax_pte_fault_class
  - fs/locks.c:__bpf_trace_leases_conflict
  - fs/locks.c:__bpf_trace_filelock_lock
  - fs/locks.c:__bpf_trace_locks_get_lock_context
  - fs/ext4/super.c:__bpf_trace_ext4_error
  - fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:__bpf_trace_ext4_insert_range
  - fs/ext4/super.c:__bpf_trace_ext4_collapse_range
  - fs/ext4/super.c:__bpf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:__bpf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:__bpf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:__bpf_trace_ext4_get_reserved_cluster_alloc
  - fs/ext4/super.c:__bpf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:__bpf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:__bpf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:__bpf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:__bpf_trace_ext4_forget
  - fs/ext4/super.c:__bpf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:__bpf_trace_ext4_discard_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:__bpf_trace_ext4_da_write_pages
  - fs/ext4/super.c:__bpf_trace_ext4_allocate_inode
  - fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:__bpf_trace_jbd2_run_stats
  - block/blk-core.c:__bpf_trace_block_split
  - block/blk-core.c:__bpf_trace_block_unplug
  - block/blk-core.c:__bpf_trace_block_get_rq
  - block/blk-core.c:__bpf_trace_block_bio_merge
  - block/blk-core.c:__bpf_trace_block_bio_complete
  - block/blk-core.c:__bpf_trace_block_rq_complete
  - drivers/gpio/gpiolib.c:__bpf_trace_gpio_value
  - drivers/gpio/gpiolib.c:__bpf_trace_gpio_direction
  - drivers/regulator/core.c:__bpf_trace_regulator_range
  - drivers/char/random.c:__bpf_trace_urandom_read
  - drivers/char/random.c:__bpf_trace_push_to_pool
  - drivers/char/random.c:__bpf_trace_random__mix_pool_bytes
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:__bpf_trace_unmap
  - drivers/iommu/iommu-traces.c:__bpf_trace_map
  - drivers/base/regmap/regmap.c:__bpf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_block
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_reg
  - drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx
  - drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_write
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip
  - drivers/ras/ras.c:__bpf_trace_memory_failure_event
  - net/core/net-traces.c:__bpf_trace_page_pool_state_hold
  - net/core/net-traces.c:__bpf_trace_page_pool_state_release
  - net/core/net-traces.c:__bpf_trace_inet_sock_set_state
  - net/core/net-traces.c:__bpf_trace_napi_poll
  - net/core/devlink.c:__bpf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:__bpf_trace_devlink_health_report
  - net/core/devlink.c:__bpf_trace_devlink_hwerr
```
**Symbols:**

```
c0000000002e7ca0-c0000000002e7d90: bpf_trace_run3 (STB_GLOBAL)
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
void bpf_trace_run3(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c50c0)
Location: kernel/trace/bpf_trace.c:1373
Inline: False
Direct callers:
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush
  - arch/x86/kernel/irq.c:__bpf_trace_vector_setup
  - arch/x86/kernel/irq.c:__bpf_trace_vector_teardown
  - arch/x86/kernel/irq.c:__bpf_trace_vector_alloc_managed
  - arch/x86/kernel/nmi.c:__bpf_trace_nmi_handler
  - arch/x86/mm/fault.c:__bpf_trace_x86_exceptions
  - kernel/softirq.c:__bpf_trace_irq_handler_exit
  - kernel/signal.c:__bpf_trace_signal_deliver
  - kernel/workqueue.c:__bpf_trace_workqueue_queue_work
  - kernel/sched/core.c:__bpf_trace_sched_move_task_template
  - kernel/sched/core.c:__bpf_trace_sched_stat_runtime
  - kernel/sched/core.c:__bpf_trace_sched_process_exec
  - kernel/sched/core.c:__bpf_trace_sched_switch
  - kernel/time/timer.c:__bpf_trace_itimer_expire
  - kernel/time/timer.c:__bpf_trace_itimer_state
  - kernel/time/timer.c:__bpf_trace_hrtimer_init
  - kernel/time/timer.c:__bpf_trace_timer_start
  - kernel/module.c:__bpf_trace_module_request
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event
  - kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_update
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:__bpf_trace_power_domain
  - kernel/trace/power-traces.c:__bpf_trace_clock
  - kernel/trace/power-traces.c:__bpf_trace_suspend_resume
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:__bpf_trace_powernv_throttle
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int
  - kernel/bpf/core.c:__bpf_trace_xdp_exception
  - mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake
  - mm/percpu.c:__bpf_trace_percpu_free_percpu
  - mm/slab_common.c:__bpf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:__bpf_trace_mm_page
  - mm/compaction.c:__bpf_trace_kcompactd_wake_template
  - mm/compaction.c:__bpf_trace_mm_compaction_suitable_template
  - mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:__bpf_trace_mm_compaction_migratepages
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page
  - mm/page_isolation.c:__bpf_trace_test_pages_isolated
  - mm/cma.c:__bpf_trace_cma_release
  - fs/open.c:__bpf_trace_do_sys_open
  - fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:__bpf_trace_writeback_queue_io
  - fs/fs-writeback.c:__bpf_trace_flush_foreign
  - fs/fs-writeback.c:__bpf_trace_inode_switch_wbs
  - fs/fs-writeback.c:__bpf_trace_inode_foreign_history
  - fs/dax.c:__bpf_trace_dax_writeback_one
  - fs/dax.c:__bpf_trace_dax_writeback_range_class
  - fs/dax.c:__bpf_trace_dax_insert_mapping
  - fs/dax.c:__bpf_trace_dax_pte_fault_class
  - fs/locks.c:__bpf_trace_leases_conflict
  - fs/locks.c:__bpf_trace_filelock_lock
  - fs/locks.c:__bpf_trace_locks_get_lock_context
  - fs/ext4/super.c:__bpf_trace_ext4_error
  - fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:__bpf_trace_ext4_insert_range
  - fs/ext4/super.c:__bpf_trace_ext4_collapse_range
  - fs/ext4/super.c:__bpf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:__bpf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:__bpf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:__bpf_trace_ext4_get_reserved_cluster_alloc
  - fs/ext4/super.c:__bpf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:__bpf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:__bpf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:__bpf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:__bpf_trace_ext4_forget
  - fs/ext4/super.c:__bpf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:__bpf_trace_ext4_discard_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:__bpf_trace_ext4_da_write_pages
  - fs/ext4/super.c:__bpf_trace_ext4_allocate_inode
  - fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:__bpf_trace_jbd2_run_stats
  - block/blk-core.c:__bpf_trace_block_split
  - block/blk-core.c:__bpf_trace_block_unplug
  - block/blk-core.c:__bpf_trace_block_get_rq
  - block/blk-core.c:__bpf_trace_block_bio_merge
  - block/blk-core.c:__bpf_trace_block_bio_complete
  - block/blk-core.c:__bpf_trace_block_rq_complete
  - arch/x86/lib/msr.c:__bpf_trace_msr_trace_class
  - drivers/gpio/gpiolib.c:__bpf_trace_gpio_value
  - drivers/gpio/gpiolib.c:__bpf_trace_gpio_direction
  - drivers/regulator/core.c:__bpf_trace_regulator_range
  - drivers/char/random.c:__bpf_trace_urandom_read
  - drivers/char/random.c:__bpf_trace_push_to_pool
  - drivers/char/random.c:__bpf_trace_random__mix_pool_bytes
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:__bpf_trace_unmap
  - drivers/iommu/iommu-traces.c:__bpf_trace_map
  - drivers/iommu/intel-trace.c:__bpf_trace_dma_unmap
  - drivers/base/regmap/regmap.c:__bpf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_block
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_reg
  - drivers/nvme/host/core.c:__bpf_trace_nvme_sq
  - drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip
  - drivers/ras/ras.c:__bpf_trace_memory_failure_event
  - net/core/net-traces.c:__bpf_trace_page_pool_state_hold
  - net/core/net-traces.c:__bpf_trace_page_pool_state_release
  - net/core/net-traces.c:__bpf_trace_inet_sock_set_state
  - net/core/net-traces.c:__bpf_trace_napi_poll
  - net/core/devlink.c:__bpf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:__bpf_trace_devlink_health_report
  - net/core/devlink.c:__bpf_trace_devlink_hwerr
```
**Symbols:**

```
ffffffff811c50c0-ffffffff811c515a: bpf_trace_run3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_trace_run3(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b7ea0)
Location: kernel/trace/bpf_trace.c:1373
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:__bpf_trace_vector_setup
  - arch/x86/kernel/irq.c:__bpf_trace_vector_teardown
  - arch/x86/kernel/irq.c:__bpf_trace_vector_alloc_managed
  - arch/x86/kernel/nmi.c:__bpf_trace_nmi_handler
  - arch/x86/mm/fault.c:__bpf_trace_x86_exceptions
  - kernel/softirq.c:__bpf_trace_irq_handler_exit
  - kernel/signal.c:__bpf_trace_signal_deliver
  - kernel/workqueue.c:__bpf_trace_workqueue_queue_work
  - kernel/sched/core.c:__bpf_trace_sched_move_task_template
  - kernel/sched/core.c:__bpf_trace_sched_stat_runtime
  - kernel/sched/core.c:__bpf_trace_sched_process_exec
  - kernel/sched/core.c:__bpf_trace_sched_switch
  - kernel/time/timer.c:__bpf_trace_itimer_expire
  - kernel/time/timer.c:__bpf_trace_itimer_state
  - kernel/time/timer.c:__bpf_trace_hrtimer_init
  - kernel/time/timer.c:__bpf_trace_timer_start
  - kernel/module.c:__bpf_trace_module_request
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event
  - kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_update
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:__bpf_trace_power_domain
  - kernel/trace/power-traces.c:__bpf_trace_clock
  - kernel/trace/power-traces.c:__bpf_trace_suspend_resume
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:__bpf_trace_powernv_throttle
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int
  - kernel/bpf/core.c:__bpf_trace_xdp_exception
  - mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake
  - mm/percpu.c:__bpf_trace_percpu_free_percpu
  - mm/slab_common.c:__bpf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:__bpf_trace_mm_page
  - mm/compaction.c:__bpf_trace_kcompactd_wake_template
  - mm/compaction.c:__bpf_trace_mm_compaction_suitable_template
  - mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:__bpf_trace_mm_compaction_migratepages
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page
  - mm/page_isolation.c:__bpf_trace_test_pages_isolated
  - mm/cma.c:__bpf_trace_cma_release
  - fs/open.c:__bpf_trace_do_sys_open
  - fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:__bpf_trace_writeback_queue_io
  - fs/fs-writeback.c:__bpf_trace_flush_foreign
  - fs/fs-writeback.c:__bpf_trace_inode_switch_wbs
  - fs/fs-writeback.c:__bpf_trace_inode_foreign_history
  - fs/dax.c:__bpf_trace_dax_writeback_one
  - fs/dax.c:__bpf_trace_dax_writeback_range_class
  - fs/dax.c:__bpf_trace_dax_insert_mapping
  - fs/dax.c:__bpf_trace_dax_pte_fault_class
  - fs/locks.c:__bpf_trace_leases_conflict
  - fs/locks.c:__bpf_trace_filelock_lock
  - fs/locks.c:__bpf_trace_locks_get_lock_context
  - fs/ext4/super.c:__bpf_trace_ext4_error
  - fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:__bpf_trace_ext4_insert_range
  - fs/ext4/super.c:__bpf_trace_ext4_collapse_range
  - fs/ext4/super.c:__bpf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:__bpf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:__bpf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:__bpf_trace_ext4_get_reserved_cluster_alloc
  - fs/ext4/super.c:__bpf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:__bpf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:__bpf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:__bpf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:__bpf_trace_ext4_forget
  - fs/ext4/super.c:__bpf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:__bpf_trace_ext4_discard_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:__bpf_trace_ext4_da_write_pages
  - fs/ext4/super.c:__bpf_trace_ext4_allocate_inode
  - fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:__bpf_trace_jbd2_run_stats
  - block/blk-core.c:__bpf_trace_block_split
  - block/blk-core.c:__bpf_trace_block_unplug
  - block/blk-core.c:__bpf_trace_block_get_rq
  - block/blk-core.c:__bpf_trace_block_bio_merge
  - block/blk-core.c:__bpf_trace_block_bio_complete
  - block/blk-core.c:__bpf_trace_block_rq_complete
  - arch/x86/lib/msr.c:__bpf_trace_msr_trace_class
  - drivers/gpio/gpiolib.c:__bpf_trace_gpio_value
  - drivers/gpio/gpiolib.c:__bpf_trace_gpio_direction
  - drivers/regulator/core.c:__bpf_trace_regulator_range
  - drivers/char/random.c:__bpf_trace_urandom_read
  - drivers/char/random.c:__bpf_trace_push_to_pool
  - drivers/char/random.c:__bpf_trace_random__mix_pool_bytes
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:__bpf_trace_unmap
  - drivers/iommu/iommu-traces.c:__bpf_trace_map
  - drivers/iommu/intel-trace.c:__bpf_trace_dma_unmap
  - drivers/base/regmap/regmap.c:__bpf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_block
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_reg
  - drivers/nvme/host/core.c:__bpf_trace_nvme_sq
  - drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip
  - drivers/ras/ras.c:__bpf_trace_memory_failure_event
  - net/core/net-traces.c:__bpf_trace_page_pool_state_hold
  - net/core/net-traces.c:__bpf_trace_page_pool_state_release
  - net/core/net-traces.c:__bpf_trace_inet_sock_set_state
  - net/core/net-traces.c:__bpf_trace_napi_poll
  - net/core/devlink.c:__bpf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:__bpf_trace_devlink_health_report
  - net/core/devlink.c:__bpf_trace_devlink_hwerr
```
**Symbols:**

```
ffffffff811b7ea0-ffffffff811b7f3a: bpf_trace_run3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_trace_run3(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c2e90)
Location: kernel/trace/bpf_trace.c:1373
Inline: False
Direct callers:
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush
  - arch/x86/kernel/irq.c:__bpf_trace_vector_setup
  - arch/x86/kernel/irq.c:__bpf_trace_vector_teardown
  - arch/x86/kernel/irq.c:__bpf_trace_vector_alloc_managed
  - arch/x86/kernel/nmi.c:__bpf_trace_nmi_handler
  - arch/x86/mm/fault.c:__bpf_trace_x86_exceptions
  - kernel/softirq.c:__bpf_trace_irq_handler_exit
  - kernel/signal.c:__bpf_trace_signal_deliver
  - kernel/workqueue.c:__bpf_trace_workqueue_queue_work
  - kernel/sched/core.c:__bpf_trace_sched_move_task_template
  - kernel/sched/core.c:__bpf_trace_sched_stat_runtime
  - kernel/sched/core.c:__bpf_trace_sched_process_exec
  - kernel/sched/core.c:__bpf_trace_sched_switch
  - kernel/time/timer.c:__bpf_trace_itimer_expire
  - kernel/time/timer.c:__bpf_trace_itimer_state
  - kernel/time/timer.c:__bpf_trace_hrtimer_init
  - kernel/time/timer.c:__bpf_trace_timer_start
  - kernel/module.c:__bpf_trace_module_request
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event
  - kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_update
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:__bpf_trace_power_domain
  - kernel/trace/power-traces.c:__bpf_trace_clock
  - kernel/trace/power-traces.c:__bpf_trace_suspend_resume
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:__bpf_trace_powernv_throttle
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int
  - kernel/bpf/core.c:__bpf_trace_xdp_exception
  - mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake
  - mm/percpu.c:__bpf_trace_percpu_free_percpu
  - mm/slab_common.c:__bpf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:__bpf_trace_mm_page
  - mm/compaction.c:__bpf_trace_kcompactd_wake_template
  - mm/compaction.c:__bpf_trace_mm_compaction_suitable_template
  - mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:__bpf_trace_mm_compaction_migratepages
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page
  - mm/page_isolation.c:__bpf_trace_test_pages_isolated
  - mm/cma.c:__bpf_trace_cma_release
  - fs/open.c:__bpf_trace_do_sys_open
  - fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:__bpf_trace_writeback_queue_io
  - fs/fs-writeback.c:__bpf_trace_flush_foreign
  - fs/fs-writeback.c:__bpf_trace_inode_switch_wbs
  - fs/fs-writeback.c:__bpf_trace_inode_foreign_history
  - fs/dax.c:__bpf_trace_dax_writeback_one
  - fs/dax.c:__bpf_trace_dax_writeback_range_class
  - fs/dax.c:__bpf_trace_dax_insert_mapping
  - fs/dax.c:__bpf_trace_dax_pte_fault_class
  - fs/locks.c:__bpf_trace_leases_conflict
  - fs/locks.c:__bpf_trace_filelock_lock
  - fs/locks.c:__bpf_trace_locks_get_lock_context
  - fs/ext4/super.c:__bpf_trace_ext4_error
  - fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:__bpf_trace_ext4_insert_range
  - fs/ext4/super.c:__bpf_trace_ext4_collapse_range
  - fs/ext4/super.c:__bpf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:__bpf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:__bpf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:__bpf_trace_ext4_get_reserved_cluster_alloc
  - fs/ext4/super.c:__bpf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:__bpf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:__bpf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:__bpf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:__bpf_trace_ext4_forget
  - fs/ext4/super.c:__bpf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:__bpf_trace_ext4_discard_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:__bpf_trace_ext4_da_write_pages
  - fs/ext4/super.c:__bpf_trace_ext4_allocate_inode
  - fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:__bpf_trace_jbd2_run_stats
  - block/blk-core.c:__bpf_trace_block_split
  - block/blk-core.c:__bpf_trace_block_unplug
  - block/blk-core.c:__bpf_trace_block_get_rq
  - block/blk-core.c:__bpf_trace_block_bio_merge
  - block/blk-core.c:__bpf_trace_block_bio_complete
  - block/blk-core.c:__bpf_trace_block_rq_complete
  - arch/x86/lib/msr.c:__bpf_trace_msr_trace_class
  - drivers/gpio/gpiolib.c:__bpf_trace_gpio_value
  - drivers/gpio/gpiolib.c:__bpf_trace_gpio_direction
  - drivers/regulator/core.c:__bpf_trace_regulator_range
  - drivers/char/random.c:__bpf_trace_urandom_read
  - drivers/char/random.c:__bpf_trace_push_to_pool
  - drivers/char/random.c:__bpf_trace_random__mix_pool_bytes
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:__bpf_trace_unmap
  - drivers/iommu/iommu-traces.c:__bpf_trace_map
  - drivers/iommu/intel-trace.c:__bpf_trace_dma_unmap
  - drivers/base/regmap/regmap.c:__bpf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_block
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_reg
  - drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx
  - drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_write
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip
  - drivers/ras/ras.c:__bpf_trace_memory_failure_event
  - net/core/net-traces.c:__bpf_trace_page_pool_state_hold
  - net/core/net-traces.c:__bpf_trace_page_pool_state_release
  - net/core/net-traces.c:__bpf_trace_inet_sock_set_state
  - net/core/net-traces.c:__bpf_trace_napi_poll
  - net/core/devlink.c:__bpf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:__bpf_trace_devlink_health_report
  - net/core/devlink.c:__bpf_trace_devlink_hwerr
```
**Symbols:**

```
ffffffff811c2e90-ffffffff811c2f2a: bpf_trace_run3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_trace_run3(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811d2230)
Location: kernel/trace/bpf_trace.c:1373
Inline: False
Direct callers:
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_idt_entry
  - arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_ldt_entry
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_release_ptpage
  - arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_extend_args
  - arch/x86/xen/trace.c:__bpf_trace_xen_mc_flush
  - arch/x86/kernel/irq.c:__bpf_trace_vector_setup
  - arch/x86/kernel/irq.c:__bpf_trace_vector_teardown
  - arch/x86/kernel/irq.c:__bpf_trace_vector_alloc_managed
  - arch/x86/kernel/nmi.c:__bpf_trace_nmi_handler
  - arch/x86/mm/fault.c:__bpf_trace_x86_exceptions
  - kernel/softirq.c:__bpf_trace_irq_handler_exit
  - kernel/signal.c:__bpf_trace_signal_deliver
  - kernel/workqueue.c:__bpf_trace_workqueue_queue_work
  - kernel/sched/core.c:__bpf_trace_sched_move_task_template
  - kernel/sched/core.c:__bpf_trace_sched_stat_runtime
  - kernel/sched/core.c:__bpf_trace_sched_process_exec
  - kernel/sched/core.c:__bpf_trace_sched_switch
  - kernel/time/timer.c:__bpf_trace_itimer_expire
  - kernel/time/timer.c:__bpf_trace_itimer_state
  - kernel/time/timer.c:__bpf_trace_hrtimer_init
  - kernel/time/timer.c:__bpf_trace_timer_start
  - kernel/module.c:__bpf_trace_module_request
  - kernel/cgroup/cgroup.c:__bpf_trace_cgroup_event
  - kernel/trace/power-traces.c:__bpf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_update
  - kernel/trace/power-traces.c:__bpf_trace_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:__bpf_trace_power_domain
  - kernel/trace/power-traces.c:__bpf_trace_clock
  - kernel/trace/power-traces.c:__bpf_trace_suspend_resume
  - kernel/trace/power-traces.c:__bpf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:__bpf_trace_powernv_throttle
  - kernel/trace/rpm-traces.c:__bpf_trace_rpm_return_int
  - kernel/bpf/core.c:__bpf_trace_xdp_exception
  - mm/vmscan.c:__bpf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:__bpf_trace_mm_vmscan_kswapd_wake
  - mm/percpu.c:__bpf_trace_percpu_free_percpu
  - mm/slab_common.c:__bpf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:__bpf_trace_mm_page
  - mm/compaction.c:__bpf_trace_kcompactd_wake_template
  - mm/compaction.c:__bpf_trace_mm_compaction_suitable_template
  - mm/compaction.c:__bpf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:__bpf_trace_mm_compaction_migratepages
  - mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page
  - mm/page_isolation.c:__bpf_trace_test_pages_isolated
  - mm/cma.c:__bpf_trace_cma_release
  - fs/open.c:__bpf_trace_do_sys_open
  - fs/fs-writeback.c:__bpf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:__bpf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:__bpf_trace_writeback_queue_io
  - fs/fs-writeback.c:__bpf_trace_flush_foreign
  - fs/fs-writeback.c:__bpf_trace_inode_switch_wbs
  - fs/fs-writeback.c:__bpf_trace_inode_foreign_history
  - fs/dax.c:__bpf_trace_dax_writeback_one
  - fs/dax.c:__bpf_trace_dax_writeback_range_class
  - fs/dax.c:__bpf_trace_dax_insert_mapping
  - fs/dax.c:__bpf_trace_dax_pte_fault_class
  - fs/locks.c:__bpf_trace_leases_conflict
  - fs/locks.c:__bpf_trace_filelock_lock
  - fs/locks.c:__bpf_trace_locks_get_lock_context
  - fs/ext4/super.c:__bpf_trace_ext4_error
  - fs/ext4/super.c:__bpf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:__bpf_trace_ext4_insert_range
  - fs/ext4/super.c:__bpf_trace_ext4_collapse_range
  - fs/ext4/super.c:__bpf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:__bpf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:__bpf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:__bpf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:__bpf_trace_ext4_get_reserved_cluster_alloc
  - fs/ext4/super.c:__bpf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:__bpf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:__bpf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:__bpf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:__bpf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:__bpf_trace_ext4_forget
  - fs/ext4/super.c:__bpf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:__bpf_trace_ext4_discard_blocks
  - fs/ext4/super.c:__bpf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:__bpf_trace_ext4_da_write_pages
  - fs/ext4/super.c:__bpf_trace_ext4_allocate_inode
  - fs/jbd2/journal.c:__bpf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:__bpf_trace_jbd2_run_stats
  - block/blk-core.c:__bpf_trace_block_split
  - block/blk-core.c:__bpf_trace_block_unplug
  - block/blk-core.c:__bpf_trace_block_get_rq
  - block/blk-core.c:__bpf_trace_block_bio_merge
  - block/blk-core.c:__bpf_trace_block_bio_complete
  - block/blk-core.c:__bpf_trace_block_rq_complete
  - arch/x86/lib/msr.c:__bpf_trace_msr_trace_class
  - drivers/gpio/gpiolib.c:__bpf_trace_gpio_value
  - drivers/gpio/gpiolib.c:__bpf_trace_gpio_direction
  - drivers/regulator/core.c:__bpf_trace_regulator_range
  - drivers/char/random.c:__bpf_trace_urandom_read
  - drivers/char/random.c:__bpf_trace_push_to_pool
  - drivers/char/random.c:__bpf_trace_random__mix_pool_bytes
  - drivers/iommu/iommu-traces.c:__bpf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:__bpf_trace_unmap
  - drivers/iommu/iommu-traces.c:__bpf_trace_map
  - drivers/iommu/intel-trace.c:__bpf_trace_dma_unmap
  - drivers/base/regmap/regmap.c:__bpf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:__bpf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_block
  - drivers/base/regmap/regmap.c:__bpf_trace_regmap_reg
  - drivers/ata/libata-core.c:__bpf_trace_ata_eh_link_autopsy
  - drivers/usb/host/xhci-trace.c:__bpf_trace_xhci_log_ctx
  - drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:__bpf_trace_i2c_write
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:__bpf_trace_hwmon_attr_class
  - drivers/thermal/thermal_core.c:__bpf_trace_thermal_zone_trip
  - drivers/ras/ras.c:__bpf_trace_memory_failure_event
  - net/core/net-traces.c:__bpf_trace_page_pool_state_hold
  - net/core/net-traces.c:__bpf_trace_page_pool_state_release
  - net/core/net-traces.c:__bpf_trace_inet_sock_set_state
  - net/core/net-traces.c:__bpf_trace_napi_poll
  - net/core/devlink.c:__bpf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:__bpf_trace_devlink_health_report
  - net/core/devlink.c:__bpf_trace_devlink_hwerr
```
**Symbols:**

```
ffffffff811d2230-ffffffff811d22eb: bpf_trace_run3 (STB_GLOBAL)
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
