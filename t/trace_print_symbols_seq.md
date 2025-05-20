# Function: <code>trace_print_symbols_seq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
const char *trace_print_symbols_seq(struct trace_seq *p, long unsigned int val, const struct trace_print_flags *symbol_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811539d0)
Location: kernel/trace/trace_output.c:101
Inline: False
Direct callers:
  - arch/x86/mm/init.c:trace_raw_output_tlb_flush
  - kernel/softirq.c:trace_raw_output_softirq
  - kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update
  - kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
  - mm/compaction.c:trace_raw_output_mm_compaction_end
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_defer_template
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - fs/fs-writeback.c:trace_raw_output_writeback_work_class
  - fs/fs-writeback.c:trace_raw_output_writeback_queue_io
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_generic_add_lease
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/i2c/i2c-core.c:trace_raw_output_smbus_write
  - drivers/i2c/i2c-core.c:trace_raw_output_smbus_read
  - drivers/i2c/i2c-core.c:trace_raw_output_smbus_reply
  - drivers/i2c/i2c-core.c:trace_raw_output_smbus_result
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
```
**Symbols:**

```
ffffffff811539d0-ffffffff81153a78: trace_print_symbols_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const char *trace_print_symbols_seq(struct trace_seq *p, long unsigned int val, const struct trace_print_flags *symbol_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff8115cb30)
Location: kernel/trace/trace_output.c:101
Inline: False
Direct callers:
  - arch/x86/mm/init.c:trace_raw_output_tlb_flush
  - kernel/softirq.c:trace_raw_output_softirq
  - kernel/time/timer.c:trace_raw_output_tick_stop
  - kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start
  - mm/compaction.c:trace_raw_output_kcompactd_wake_template
  - mm/compaction.c:trace_raw_output_mm_compaction_defer_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_end
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page
  - mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd
  - fs/fs-writeback.c:trace_raw_output_writeback_queue_io
  - fs/fs-writeback.c:trace_raw_output_writeback_work_class
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/locks.c:trace_raw_output_locks_get_lock_context
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/i2c/i2c-core.c:trace_raw_output_smbus_result
  - drivers/i2c/i2c-core.c:trace_raw_output_smbus_reply
  - drivers/i2c/i2c-core.c:trace_raw_output_smbus_read
  - drivers/i2c/i2c-core.c:trace_raw_output_smbus_write
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
```
**Symbols:**

```
ffffffff8115cb30-ffffffff8115cbd8: trace_print_symbols_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const char *trace_print_symbols_seq(struct trace_seq *p, long unsigned int val, const struct trace_print_flags *symbol_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff81167400)
Location: kernel/trace/trace_output.c:101
Inline: False
Direct callers:
  - arch/x86/mm/init.c:trace_raw_output_tlb_flush
  - kernel/softirq.c:trace_raw_output_softirq
  - kernel/time/timer.c:trace_raw_output_tick_stop
  - kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start
  - mm/compaction.c:trace_raw_output_kcompactd_wake_template
  - mm/compaction.c:trace_raw_output_mm_compaction_defer_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_end
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page
  - mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd
  - fs/fs-writeback.c:trace_raw_output_writeback_queue_io
  - fs/fs-writeback.c:trace_raw_output_writeback_work_class
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/locks.c:trace_raw_output_locks_get_lock_context
  - lib/swiotlb.c:trace_raw_output_swiotlb_bounced
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/i2c/i2c-core.c:trace_raw_output_smbus_result
  - drivers/i2c/i2c-core.c:trace_raw_output_smbus_reply
  - drivers/i2c/i2c-core.c:trace_raw_output_smbus_read
  - drivers/i2c/i2c-core.c:trace_raw_output_smbus_write
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
```
**Symbols:**

```
ffffffff81167400-ffffffff811674a8: trace_print_symbols_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const char *trace_print_symbols_seq(struct trace_seq *p, long unsigned int val, const struct trace_print_flags *symbol_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff8116a740)
Location: kernel/trace/trace_output.c:102
Inline: False
Direct callers:
  - arch/x86/mm/init.c:trace_raw_output_tlb_flush
  - kernel/softirq.c:trace_raw_output_softirq
  - kernel/time/timer.c:trace_raw_output_tick_stop
  - kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start
  - kernel/bpf/core.c:trace_raw_output_xdp_exception
  - kernel/bpf/core.c:trace_raw_output_bpf_map_next_key
  - kernel/bpf/core.c:trace_raw_output_bpf_map_delete_elem
  - kernel/bpf/core.c:trace_raw_output_bpf_map_keyval
  - kernel/bpf/core.c:trace_raw_output_bpf_obj_map
  - kernel/bpf/core.c:trace_raw_output_bpf_map_create
  - kernel/bpf/core.c:trace_raw_output_bpf_prog_load
  - kernel/bpf/core.c:trace_raw_output_bpf_prog_event
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_reclaim_retry_zone
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate
  - mm/compaction.c:trace_raw_output_kcompactd_wake_template
  - mm/compaction.c:trace_raw_output_mm_compaction_defer_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_end
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page
  - mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd
  - fs/fs-writeback.c:trace_raw_output_writeback_queue_io
  - fs/fs-writeback.c:trace_raw_output_writeback_work_class
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/locks.c:trace_raw_output_locks_get_lock_context
  - lib/swiotlb.c:trace_raw_output_swiotlb_bounced
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
```
**Symbols:**

```
ffffffff8116a740-ffffffff8116a7e6: trace_print_symbols_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const char *trace_print_symbols_seq(struct trace_seq *p, long unsigned int val, const struct trace_print_flags *symbol_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff81177870)
Location: kernel/trace/trace_output.c:102
Inline: False
Direct callers:
  - arch/x86/mm/init.c:trace_raw_output_tlb_flush
  - kernel/softirq.c:trace_raw_output_softirq
  - kernel/time/timer.c:trace_raw_output_tick_stop
  - kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_template
  - kernel/bpf/core.c:trace_raw_output_xdp_exception
  - kernel/bpf/core.c:trace_raw_output_bpf_map_next_key
  - kernel/bpf/core.c:trace_raw_output_bpf_map_delete_elem
  - kernel/bpf/core.c:trace_raw_output_bpf_map_keyval
  - kernel/bpf/core.c:trace_raw_output_bpf_obj_map
  - kernel/bpf/core.c:trace_raw_output_bpf_map_create
  - kernel/bpf/core.c:trace_raw_output_bpf_prog_load
  - kernel/bpf/core.c:trace_raw_output_bpf_prog_event
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_reclaim_retry_zone
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate
  - mm/compaction.c:trace_raw_output_kcompactd_wake_template
  - mm/compaction.c:trace_raw_output_mm_compaction_defer_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_end
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page
  - mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd
  - fs/fs-writeback.c:trace_raw_output_writeback_queue_io
  - fs/fs-writeback.c:trace_raw_output_writeback_work_class
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/locks.c:trace_raw_output_locks_get_lock_context
  - lib/swiotlb.c:trace_raw_output_swiotlb_bounced
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - net/core/net-traces.c:trace_raw_output_tcp_set_state
  - net/core/net-traces.c:trace_raw_output_tcp_set_state
```
**Symbols:**

```
ffffffff81177870-ffffffff81177916: trace_print_symbols_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const char *trace_print_symbols_seq(struct trace_seq *p, long unsigned int val, const struct trace_print_flags *symbol_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff81186a90)
Location: kernel/trace/trace_output.c:102
Inline: False
Direct callers:
  - arch/x86/mm/init.c:trace_raw_output_tlb_flush
  - kernel/softirq.c:trace_raw_output_softirq
  - kernel/dma/swiotlb.c:trace_raw_output_swiotlb_bounced
  - kernel/time/timer.c:trace_raw_output_tick_stop
  - kernel/time/timer.c:trace_raw_output_hrtimer_start
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start
  - kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_template
  - kernel/bpf/core.c:trace_raw_output_xdp_exception
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_reclaim_retry_zone
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate
  - mm/compaction.c:trace_raw_output_kcompactd_wake_template
  - mm/compaction.c:trace_raw_output_mm_compaction_defer_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_end
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page
  - mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd
  - fs/fs-writeback.c:trace_raw_output_writeback_queue_io
  - fs/fs-writeback.c:trace_raw_output_writeback_work_class
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/locks.c:trace_raw_output_locks_get_lock_context
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
```
**Symbols:**

```
ffffffff81186a90-ffffffff81186b36: trace_print_symbols_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const char *trace_print_symbols_seq(struct trace_seq *p, long unsigned int val, const struct trace_print_flags *symbol_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff81194400)
Location: kernel/trace/trace_output.c:103
Inline: False
Direct callers:
  - arch/x86/mm/init.c:trace_raw_output_tlb_flush
  - kernel/softirq.c:trace_raw_output_softirq
  - kernel/dma/swiotlb.c:trace_raw_output_swiotlb_bounced
  - kernel/time/timer.c:trace_raw_output_tick_stop
  - kernel/time/timer.c:trace_raw_output_hrtimer_start
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start
  - kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_template
  - kernel/bpf/core.c:trace_raw_output_xdp_exception
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_reclaim_retry_zone
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate
  - mm/compaction.c:trace_raw_output_kcompactd_wake_template
  - mm/compaction.c:trace_raw_output_mm_compaction_defer_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_end
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page
  - mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd
  - fs/fs-writeback.c:trace_raw_output_writeback_queue_io
  - fs/fs-writeback.c:trace_raw_output_writeback_work_class
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/locks.c:trace_raw_output_locks_get_lock_context
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit
```
**Symbols:**

```
ffffffff81194400-ffffffff811944a6: trace_print_symbols_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const char *trace_print_symbols_seq(struct trace_seq *p, long unsigned int val, const struct trace_print_flags *symbol_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811a2120)
Location: kernel/trace/trace_output.c:103
Inline: False
Direct callers:
  - arch/x86/mm/init.c:trace_raw_output_tlb_flush
  - kernel/softirq.c:trace_raw_output_softirq
  - kernel/dma/swiotlb.c:trace_raw_output_swiotlb_bounced
  - kernel/time/timer.c:trace_raw_output_tick_stop
  - kernel/time/timer.c:trace_raw_output_hrtimer_start
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start
  - kernel/bpf/core.c:trace_raw_output_mem_return_failed
  - kernel/bpf/core.c:trace_raw_output_mem_connect
  - kernel/bpf/core.c:trace_raw_output_mem_disconnect
  - kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_map_err
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_map
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_template
  - kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx
  - kernel/bpf/core.c:trace_raw_output_xdp_exception
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_reclaim_retry_zone
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate
  - mm/compaction.c:trace_raw_output_kcompactd_wake_template
  - mm/compaction.c:trace_raw_output_mm_compaction_defer_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_end
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page
  - mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd
  - fs/fs-writeback.c:trace_raw_output_writeback_queue_io
  - fs/fs-writeback.c:trace_raw_output_writeback_work_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/locks.c:trace_raw_output_locks_get_lock_context
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip
  - drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_cmd_class
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit
```
**Symbols:**

```
ffffffff811a2120-ffffffff811a21c9: trace_print_symbols_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const char *trace_print_symbols_seq(struct trace_seq *p, long unsigned int val, const struct trace_print_flags *symbol_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811adb00)
Location: kernel/trace/trace_output.c:103
Inline: False
Direct callers:
  - arch/x86/mm/init.c:trace_raw_output_tlb_flush
  - kernel/softirq.c:trace_raw_output_softirq
  - kernel/dma/swiotlb.c:trace_raw_output_swiotlb_bounced
  - kernel/time/timer.c:trace_raw_output_tick_stop
  - kernel/time/timer.c:trace_raw_output_hrtimer_start
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start
  - kernel/bpf/core.c:trace_raw_output_mem_return_failed
  - kernel/bpf/core.c:trace_raw_output_mem_connect
  - kernel/bpf/core.c:trace_raw_output_mem_disconnect
  - kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_map_err
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_map
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_template
  - kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx
  - kernel/bpf/core.c:trace_raw_output_xdp_exception
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_reclaim_retry_zone
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate
  - mm/compaction.c:trace_raw_output_kcompactd_wake_template
  - mm/compaction.c:trace_raw_output_mm_compaction_defer_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_end
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page
  - mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd
  - fs/fs-writeback.c:trace_raw_output_writeback_queue_io
  - fs/fs-writeback.c:trace_raw_output_writeback_work_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/locks.c:trace_raw_output_locks_get_lock_context
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip
  - drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_cmd_class
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit
```
**Symbols:**

```
ffffffff811adb00-ffffffff811adba9: trace_print_symbols_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *trace_print_symbols_seq(struct trace_seq *p, long unsigned int val, const struct trace_print_flags *symbol_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811c5bc0)
Location: kernel/trace/trace_output.c:103
Inline: False
Direct callers:
  - arch/x86/mm/init.c:trace_raw_output_tlb_flush
  - kernel/softirq.c:trace_raw_output_softirq
  - kernel/dma/swiotlb.c:trace_raw_output_swiotlb_bounced
  - kernel/time/timer.c:trace_raw_output_tick_stop
  - kernel/time/timer.c:trace_raw_output_hrtimer_start
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update
  - kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start
  - kernel/bpf/core.c:trace_raw_output_mem_return_failed
  - kernel/bpf/core.c:trace_raw_output_mem_connect
  - kernel/bpf/core.c:trace_raw_output_mem_disconnect
  - kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_template
  - kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx
  - kernel/bpf/core.c:trace_raw_output_xdp_exception
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_reclaim_retry_zone
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate
  - mm/compaction.c:trace_raw_output_kcompactd_wake_template
  - mm/compaction.c:trace_raw_output_mm_compaction_defer_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_end
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page
  - mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd
  - fs/fs-writeback.c:trace_raw_output_writeback_queue_io
  - fs/fs-writeback.c:trace_raw_output_writeback_work_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/locks.c:trace_raw_output_locks_get_lock_context
  - fs/iomap/trace.c:trace_raw_output_iomap_class
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip
  - drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_start
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit
```
**Symbols:**

```
ffffffff811c5bc0-ffffffff811c5c69: trace_print_symbols_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *trace_print_symbols_seq(struct trace_seq *p, long unsigned int val, const struct trace_print_flags *symbol_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811c31f0)
Location: kernel/trace/trace_output.c:103
Inline: False
Direct callers:
  - arch/x86/mm/init.c:trace_raw_output_tlb_flush
  - kernel/softirq.c:trace_raw_output_softirq
  - kernel/dma/swiotlb.c:trace_raw_output_swiotlb_bounced
  - kernel/time/timer.c:trace_raw_output_tick_stop
  - kernel/time/timer.c:trace_raw_output_hrtimer_start
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update
  - kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start
  - kernel/bpf/core.c:trace_raw_output_mem_return_failed
  - kernel/bpf/core.c:trace_raw_output_mem_connect
  - kernel/bpf/core.c:trace_raw_output_mem_disconnect
  - kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_template
  - kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx
  - kernel/bpf/core.c:trace_raw_output_xdp_exception
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_reclaim_retry_zone
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate
  - mm/compaction.c:trace_raw_output_kcompactd_wake_template
  - mm/compaction.c:trace_raw_output_mm_compaction_defer_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_end
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page
  - mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd
  - fs/fs-writeback.c:trace_raw_output_writeback_queue_io
  - fs/fs-writeback.c:trace_raw_output_writeback_work_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/locks.c:trace_raw_output_locks_get_lock_context
  - fs/iomap/trace.c:trace_raw_output_iomap_class
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip
  - drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_start
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit
```
**Symbols:**

```
ffffffff811c31f0-ffffffff811c3299: trace_print_symbols_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *trace_print_symbols_seq(struct trace_seq *p, long unsigned int val, const struct trace_print_flags *symbol_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811c4250)
Location: kernel/trace/trace_output.c:103
Inline: False
Direct callers:
  - arch/x86/mm/init.c:trace_raw_output_tlb_flush
  - kernel/softirq.c:trace_raw_output_softirq
  - kernel/dma/swiotlb.c:trace_raw_output_swiotlb_bounced
  - kernel/time/timer.c:trace_raw_output_tick_stop
  - kernel/time/timer.c:trace_raw_output_hrtimer_start
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/trace/error_report-traces.c:trace_raw_output_error_report_template
  - kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update
  - kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start
  - kernel/bpf/core.c:trace_raw_output_mem_return_failed
  - kernel/bpf/core.c:trace_raw_output_mem_connect
  - kernel/bpf/core.c:trace_raw_output_mem_disconnect
  - kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_template
  - kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx
  - kernel/bpf/core.c:trace_raw_output_xdp_exception
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_reclaim_retry_zone
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate
  - mm/slab_common.c:trace_raw_output_rss_stat
  - mm/compaction.c:trace_raw_output_kcompactd_wake_template
  - mm/compaction.c:trace_raw_output_mm_compaction_defer_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_end
  - mm/migrate.c:trace_raw_output_mm_migrate_pages_start
  - mm/migrate.c:trace_raw_output_mm_migrate_pages_start
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page
  - mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd
  - fs/fs-writeback.c:trace_raw_output_writeback_queue_io
  - fs/fs-writeback.c:trace_raw_output_writeback_work_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/locks.c:trace_raw_output_locks_get_lock_context
  - fs/iomap/trace.c:trace_raw_output_iomap_class
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - drivers/iommu/intel/trace.c:trace_raw_output_qi_submit
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip
  - drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_start
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_tcp_probe
  - net/core/net-traces.c:trace_raw_output_tcp_retransmit_synack
  - net/core/net-traces.c:trace_raw_output_tcp_event_sk
  - net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb
  - net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit
  - net/mptcp/protocol.c:trace_raw_output_subflow_check_data_avail
```
**Symbols:**

```
ffffffff811c4250-ffffffff811c42f6: trace_print_symbols_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *trace_print_symbols_seq(struct trace_seq *p, long unsigned int val, const struct trace_print_flags *symbol_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811ef610)
Location: kernel/trace/trace_output.c:103
Inline: False
Direct callers:
  - arch/x86/mm/init.c:trace_raw_output_tlb_flush
  - kernel/softirq.c:trace_raw_output_softirq
  - kernel/dma/swiotlb.c:trace_raw_output_swiotlb_bounced
  - kernel/time/timer.c:trace_raw_output_tick_stop
  - kernel/time/timer.c:trace_raw_output_hrtimer_start
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/trace/error_report-traces.c:trace_raw_output_error_report_template
  - kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update
  - kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start
  - kernel/bpf/core.c:trace_raw_output_mem_return_failed
  - kernel/bpf/core.c:trace_raw_output_mem_connect
  - kernel/bpf/core.c:trace_raw_output_mem_disconnect
  - kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_template
  - kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx
  - kernel/bpf/core.c:trace_raw_output_xdp_exception
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_reclaim_retry_zone
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate
  - mm/slab_common.c:trace_raw_output_rss_stat
  - mm/compaction.c:trace_raw_output_kcompactd_wake_template
  - mm/compaction.c:trace_raw_output_mm_compaction_defer_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_end
  - mm/migrate.c:trace_raw_output_mm_migrate_pages_start
  - mm/migrate.c:trace_raw_output_mm_migrate_pages_start
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page
  - mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd
  - fs/fs-writeback.c:trace_raw_output_writeback_queue_io
  - fs/fs-writeback.c:trace_raw_output_writeback_work_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/locks.c:trace_raw_output_locks_get_lock_context
  - fs/iomap/trace.c:trace_raw_output_iomap_class
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - drivers/iommu/intel/trace.c:trace_raw_output_qi_submit
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip
  - drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_start
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_tcp_probe
  - net/core/net-traces.c:trace_raw_output_tcp_retransmit_synack
  - net/core/net-traces.c:trace_raw_output_tcp_event_sk
  - net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb
  - net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb
  - net/core/net-traces.c:trace_raw_output_inet_sk_error_report
  - net/core/net-traces.c:trace_raw_output_inet_sk_error_report
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit
  - net/mptcp/protocol.c:trace_raw_output_subflow_check_data_avail
```
**Symbols:**

```
ffffffff811ef610-ffffffff811ef6b6: trace_print_symbols_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *trace_print_symbols_seq(struct trace_seq *p, long unsigned int val, const struct trace_print_flags *symbol_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff81227b10)
Location: kernel/trace/trace_output.c:104
Inline: False
Direct callers:
  - kernel/softirq.c:trace_raw_output_softirq
  - kernel/time/timer.c:trace_raw_output_tick_stop
  - kernel/time/timer.c:trace_raw_output_hrtimer_start
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/trace/error_report-traces.c:trace_raw_output_error_report_template
  - kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update
  - kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start
  - kernel/bpf/core.c:trace_raw_output_mem_return_failed
  - kernel/bpf/core.c:trace_raw_output_mem_connect
  - kernel/bpf/core.c:trace_raw_output_mem_disconnect
  - kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_template
  - kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx
  - kernel/bpf/core.c:trace_raw_output_xdp_exception
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_reclaim_retry_zone
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate
  - mm/slab_common.c:trace_raw_output_rss_stat
  - mm/compaction.c:trace_raw_output_kcompactd_wake_template
  - mm/compaction.c:trace_raw_output_mm_compaction_defer_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_end
  - mm/rmap.c:trace_raw_output_mm_migrate_pages_start
  - mm/rmap.c:trace_raw_output_mm_migrate_pages_start
  - mm/rmap.c:trace_raw_output_mm_migrate_pages
  - mm/rmap.c:trace_raw_output_mm_migrate_pages
  - mm/rmap.c:trace_raw_output_tlb_flush
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page
  - mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd
  - fs/fs-writeback.c:trace_raw_output_writeback_queue_io
  - fs/fs-writeback.c:trace_raw_output_writeback_work_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/locks.c:trace_raw_output_locks_get_lock_context
  - fs/iomap/trace.c:trace_raw_output_iomap_class
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - drivers/iommu/intel/trace.c:trace_raw_output_qi_submit
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ata/libata-core.c:trace_raw_output_ata_sff_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_sff_hsm_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_sff_hsm_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_link_reset_end_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_link_reset_end_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_link_reset_begin_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_link_reset_begin_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_exec_command_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_exec_command_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_tf_load
  - drivers/ata/libata-core.c:trace_raw_output_ata_tf_load
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue_template
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip
  - drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_start
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_tcp_probe
  - net/core/net-traces.c:trace_raw_output_tcp_retransmit_synack
  - net/core/net-traces.c:trace_raw_output_tcp_event_sk
  - net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb
  - net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb
  - net/core/net-traces.c:trace_raw_output_inet_sk_error_report
  - net/core/net-traces.c:trace_raw_output_inet_sk_error_report
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_raw_output_kfree_skb
  - net/mptcp/protocol.c:trace_raw_output_subflow_check_data_avail
  - net/mctp/af_mctp.c:trace_raw_output_mctp_key_release
```
**Symbols:**

```
ffffffff81227b10-ffffffff81227bbe: trace_print_symbols_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *trace_print_symbols_seq(struct trace_seq *p, long unsigned int val, const struct trace_print_flags *symbol_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff81273090)
Location: kernel/trace/trace_output.c:103
Inline: False
Direct callers:
  - kernel/softirq.c:trace_raw_output_softirq
  - kernel/time/timer.c:trace_raw_output_tick_stop
  - kernel/time/timer.c:trace_raw_output_hrtimer_start
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/trace/error_report-traces.c:trace_raw_output_error_report_template
  - kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update
  - kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start
  - kernel/bpf/core.c:trace_raw_output_mem_return_failed
  - kernel/bpf/core.c:trace_raw_output_mem_connect
  - kernel/bpf/core.c:trace_raw_output_mem_disconnect
  - kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_template
  - kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx
  - kernel/bpf/core.c:trace_raw_output_xdp_exception
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_reclaim_retry_zone
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate
  - mm/slab_common.c:trace_raw_output_rss_stat
  - mm/compaction.c:trace_raw_output_kcompactd_wake_template
  - mm/compaction.c:trace_raw_output_mm_compaction_defer_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_end
  - mm/rmap.c:trace_raw_output_mm_migrate_pages_start
  - mm/rmap.c:trace_raw_output_mm_migrate_pages_start
  - mm/rmap.c:trace_raw_output_mm_migrate_pages
  - mm/rmap.c:trace_raw_output_mm_migrate_pages
  - mm/rmap.c:trace_raw_output_tlb_flush
  - mm/khugepaged.c:trace_raw_output_mm_khugepaged_collapse_file
  - mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_file
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page
  - mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd
  - fs/fs-writeback.c:trace_raw_output_writeback_queue_io
  - fs/fs-writeback.c:trace_raw_output_writeback_work_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/locks.c:trace_raw_output_locks_get_lock_context
  - fs/iomap/trace.c:trace_raw_output_iomap_class
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - drivers/iommu/intel/trace.c:trace_raw_output_qi_submit
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ata/libata-core.c:trace_raw_output_ata_sff_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_sff_hsm_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_sff_hsm_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_link_reset_end_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_link_reset_end_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_link_reset_begin_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_link_reset_begin_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_exec_command_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_exec_command_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_tf_load
  - drivers/ata/libata-core.c:trace_raw_output_ata_tf_load
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue_template
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip
  - drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_start
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_tcp_probe
  - net/core/net-traces.c:trace_raw_output_tcp_retransmit_synack
  - net/core/net-traces.c:trace_raw_output_tcp_event_sk
  - net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb
  - net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb
  - net/core/net-traces.c:trace_raw_output_inet_sk_error_report
  - net/core/net-traces.c:trace_raw_output_inet_sk_error_report
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_raw_output_kfree_skb
  - net/mptcp/protocol.c:trace_raw_output_subflow_check_data_avail
  - net/mctp/af_mctp.c:trace_raw_output_mctp_key_release
```
**Symbols:**

```
ffffffff81273090-ffffffff8127313e: trace_print_symbols_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *trace_print_symbols_seq(struct trace_seq *p, long unsigned int val, const struct trace_print_flags *symbol_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff8128a430)
Location: kernel/trace/trace_output.c:103
Inline: False
Direct callers:
  - kernel/softirq.c:trace_raw_output_softirq
  - kernel/time/timer.c:trace_raw_output_tick_stop
  - kernel/time/timer.c:trace_raw_output_hrtimer_start
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/trace/trace_osnoise.c:trace_raw_output_softirq_noise
  - kernel/trace/error_report-traces.c:trace_raw_output_error_report_template
  - kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update
  - kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start
  - kernel/bpf/core.c:trace_raw_output_mem_return_failed
  - kernel/bpf/core.c:trace_raw_output_mem_connect
  - kernel/bpf/core.c:trace_raw_output_mem_disconnect
  - kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_template
  - kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx
  - kernel/bpf/core.c:trace_raw_output_xdp_exception
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_reclaim_retry_zone
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate
  - mm/slab_common.c:trace_raw_output_rss_stat
  - mm/compaction.c:trace_raw_output_kcompactd_wake_template
  - mm/compaction.c:trace_raw_output_mm_compaction_defer_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_end
  - mm/rmap.c:trace_raw_output_mm_migrate_pages_start
  - mm/rmap.c:trace_raw_output_mm_migrate_pages_start
  - mm/rmap.c:trace_raw_output_mm_migrate_pages
  - mm/rmap.c:trace_raw_output_mm_migrate_pages
  - mm/rmap.c:trace_raw_output_tlb_flush
  - mm/khugepaged.c:trace_raw_output_mm_khugepaged_collapse_file
  - mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_file
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page
  - mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd
  - fs/fs-writeback.c:trace_raw_output_writeback_queue_io
  - fs/fs-writeback.c:trace_raw_output_writeback_work_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/locks.c:trace_raw_output_locks_get_lock_context
  - fs/iomap/trace.c:trace_raw_output_iomap_class
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc
  - drivers/iommu/intel/trace.c:trace_raw_output_qi_submit
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ata/libata-core.c:trace_raw_output_ata_sff_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_sff_hsm_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_sff_hsm_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_link_reset_end_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_link_reset_end_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_link_reset_begin_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_link_reset_begin_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_exec_command_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_exec_command_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_tf_load
  - drivers/ata/libata-core.c:trace_raw_output_ata_tf_load
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue_template
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip
  - drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_start
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_tcp_cong_state_set
  - net/core/net-traces.c:trace_raw_output_tcp_probe
  - net/core/net-traces.c:trace_raw_output_tcp_retransmit_synack
  - net/core/net-traces.c:trace_raw_output_tcp_event_sk
  - net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb
  - net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb
  - net/core/net-traces.c:trace_raw_output_sock_msg_length
  - net/core/net-traces.c:trace_raw_output_sock_msg_length
  - net/core/net-traces.c:trace_raw_output_inet_sk_error_report
  - net/core/net-traces.c:trace_raw_output_inet_sk_error_report
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_raw_output_kfree_skb
  - net/mptcp/protocol.c:trace_raw_output_subflow_check_data_avail
  - net/mctp/af_mctp.c:trace_raw_output_mctp_key_release
```
**Symbols:**

```
ffffffff8128a430-ffffffff8128a4e0: trace_print_symbols_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *trace_print_symbols_seq(struct trace_seq *p, long unsigned int val, const struct trace_print_flags *symbol_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff812a57e0)
Location: kernel/trace/trace_output.c:103
Inline: False
Direct callers:
  - kernel/softirq.c:trace_raw_output_softirq
  - kernel/sched/core.c:trace_raw_output_sched_skip_vma_numa
  - kernel/time/timer.c:trace_raw_output_tick_stop
  - kernel/time/timer.c:trace_raw_output_hrtimer_start
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/trace/trace_osnoise.c:trace_raw_output_softirq_noise
  - kernel/trace/error_report-traces.c:trace_raw_output_error_report_template
  - kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update
  - kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start
  - kernel/bpf/core.c:trace_raw_output_mem_return_failed
  - kernel/bpf/core.c:trace_raw_output_mem_connect
  - kernel/bpf/core.c:trace_raw_output_mem_disconnect
  - kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_template
  - kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx
  - kernel/bpf/core.c:trace_raw_output_xdp_exception
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_reclaim_retry_zone
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate
  - mm/slab_common.c:trace_raw_output_rss_stat
  - mm/compaction.c:trace_raw_output_kcompactd_wake_template
  - mm/compaction.c:trace_raw_output_mm_compaction_defer_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_end
  - mm/rmap.c:trace_raw_output_mm_migrate_pages_start
  - mm/rmap.c:trace_raw_output_mm_migrate_pages_start
  - mm/rmap.c:trace_raw_output_mm_migrate_pages
  - mm/rmap.c:trace_raw_output_mm_migrate_pages
  - mm/rmap.c:trace_raw_output_tlb_flush
  - mm/khugepaged.c:trace_raw_output_mm_khugepaged_collapse_file
  - mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_file
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page
  - mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd
  - fs/fs-writeback.c:trace_raw_output_writeback_queue_io
  - fs/fs-writeback.c:trace_raw_output_writeback_work_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/locks.c:trace_raw_output_locks_get_lock_context
  - fs/iomap/trace.c:trace_raw_output_iomap_class
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_fc_stats
  - fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc
  - drivers/iommu/intel/trace.c:trace_raw_output_qi_submit
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ata/libata-core.c:trace_raw_output_ata_sff_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_sff_hsm_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_sff_hsm_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_link_reset_end_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_link_reset_end_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_link_reset_begin_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_link_reset_begin_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_exec_command_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_exec_command_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_tf_load
  - drivers/ata/libata-core.c:trace_raw_output_ata_tf_load
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue_template
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue_template
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip
  - drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_done
  - drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_request_start
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_tcp_cong_state_set
  - net/core/net-traces.c:trace_raw_output_tcp_probe
  - net/core/net-traces.c:trace_raw_output_tcp_retransmit_synack
  - net/core/net-traces.c:trace_raw_output_tcp_event_sk
  - net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb
  - net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb
  - net/core/net-traces.c:trace_raw_output_sock_msg_length
  - net/core/net-traces.c:trace_raw_output_sock_msg_length
  - net/core/net-traces.c:trace_raw_output_inet_sk_error_report
  - net/core/net-traces.c:trace_raw_output_inet_sk_error_report
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_raw_output_kfree_skb
  - net/mptcp/protocol.c:trace_raw_output_subflow_check_data_avail
  - net/mctp/af_mctp.c:trace_raw_output_mctp_key_release
  - net/handshake/trace.c:trace_raw_output_tls_contenttype
  - net/handshake/trace.c:trace_raw_output_handshake_alert_class
  - net/handshake/trace.c:trace_raw_output_handshake_alert_class
```
**Symbols:**

```
ffffffff812a57e0-ffffffff812a5890: trace_print_symbols_seq (STB_GLOBAL)
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
const char *trace_print_symbols_seq(struct trace_seq *p, long unsigned int val, const struct trace_print_flags *symbol_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffff80001022adf8)
Location: kernel/trace/trace_output.c:103
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:trace_raw_output_kvm_fpu
  - virt/kvm/kvm_main.c:trace_raw_output_kvm_mmio
  - virt/kvm/kvm_main.c:trace_raw_output_kvm_userspace_exit
  - virt/kvm/arm/arm.c:trace_raw_output_kvm_exit
  - virt/kvm/arm/arm.c:trace_raw_output_kvm_exit
  - kernel/softirq.c:trace_raw_output_softirq
  - kernel/dma/swiotlb.c:trace_raw_output_swiotlb_bounced
  - kernel/time/timer.c:trace_raw_output_tick_stop
  - kernel/time/timer.c:trace_raw_output_hrtimer_start
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start
  - kernel/bpf/core.c:trace_raw_output_mem_return_failed
  - kernel/bpf/core.c:trace_raw_output_mem_connect
  - kernel/bpf/core.c:trace_raw_output_mem_disconnect
  - kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_map_err
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_map
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_template
  - kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx
  - kernel/bpf/core.c:trace_raw_output_xdp_exception
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_reclaim_retry_zone
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate
  - mm/compaction.c:trace_raw_output_kcompactd_wake_template
  - mm/compaction.c:trace_raw_output_mm_compaction_defer_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_end
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page
  - mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd
  - fs/fs-writeback.c:trace_raw_output_writeback_queue_io
  - fs/fs-writeback.c:trace_raw_output_writeback_work_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/locks.c:trace_raw_output_locks_get_lock_context
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip
  - drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_cmd_class
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit
```
**Symbols:**

```
ffff80001022adf8-ffff80001022aec8: trace_print_symbols_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const char *trace_print_symbols_seq(struct trace_seq *p, long unsigned int val, const struct trace_print_flags *symbol_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (c0468274)
Location: kernel/trace/trace_output.c:103
Inline: False
Direct callers:
  - kernel/softirq.c:trace_raw_output_softirq
  - kernel/time/timer.c:trace_raw_output_tick_stop
  - kernel/time/timer.c:trace_raw_output_hrtimer_start
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start
  - kernel/bpf/core.c:trace_raw_output_mem_return_failed
  - kernel/bpf/core.c:trace_raw_output_mem_connect
  - kernel/bpf/core.c:trace_raw_output_mem_disconnect
  - kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_map_err
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_map
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_template
  - kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx
  - kernel/bpf/core.c:trace_raw_output_xdp_exception
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_reclaim_retry_zone
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate
  - mm/compaction.c:trace_raw_output_kcompactd_wake_template
  - mm/compaction.c:trace_raw_output_mm_compaction_defer_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_end
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - fs/fs-writeback.c:trace_raw_output_writeback_queue_io
  - fs/fs-writeback.c:trace_raw_output_writeback_work_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/locks.c:trace_raw_output_locks_get_lock_context
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip
  - drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_cmd_class
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit
```
**Symbols:**

```
c0468274-c046831c: trace_print_symbols_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const char *trace_print_symbols_seq(struct trace_seq *p, long unsigned int val, const struct trace_print_flags *symbol_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (c0000000002b2a80)
Location: kernel/trace/trace_output.c:103
Inline: False
Direct callers:
  - kernel/softirq.c:trace_raw_output_softirq
  - kernel/dma/swiotlb.c:trace_raw_output_swiotlb_bounced
  - kernel/time/timer.c:trace_raw_output_tick_stop
  - kernel/time/timer.c:trace_raw_output_hrtimer_start
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start
  - kernel/bpf/core.c:trace_raw_output_mem_return_failed
  - kernel/bpf/core.c:trace_raw_output_mem_connect
  - kernel/bpf/core.c:trace_raw_output_mem_disconnect
  - kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_map_err
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_map
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_template
  - kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx
  - kernel/bpf/core.c:trace_raw_output_xdp_exception
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_reclaim_retry_zone
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate
  - mm/compaction.c:trace_raw_output_kcompactd_wake_template
  - mm/compaction.c:trace_raw_output_mm_compaction_defer_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_end
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page
  - mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd
  - fs/fs-writeback.c:trace_raw_output_writeback_queue_io
  - fs/fs-writeback.c:trace_raw_output_writeback_work_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/locks.c:trace_raw_output_locks_get_lock_context
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit
```
**Symbols:**

```
c0000000002b2a80-c0000000002b2bc8: trace_print_symbols_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const char *trace_print_symbols_seq(struct trace_seq *p, long unsigned int val, const struct trace_print_flags *symbol_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffe000185018)
Location: kernel/trace/trace_output.c:103
Inline: False
Direct callers:
  - kernel/softirq.c:trace_raw_output_softirq
  - kernel/dma/swiotlb.c:trace_raw_output_swiotlb_bounced
  - kernel/time/timer.c:trace_raw_output_tick_stop
  - kernel/time/timer.c:trace_raw_output_hrtimer_start
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start
  - kernel/bpf/core.c:trace_raw_output_mem_return_failed
  - kernel/bpf/core.c:trace_raw_output_mem_connect
  - kernel/bpf/core.c:trace_raw_output_mem_disconnect
  - kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_map_err
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_map
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_template
  - kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx
  - kernel/bpf/core.c:trace_raw_output_xdp_exception
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_reclaim_retry_zone
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate
  - mm/compaction.c:trace_raw_output_kcompactd_wake_template
  - mm/compaction.c:trace_raw_output_mm_compaction_defer_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_end
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - fs/fs-writeback.c:trace_raw_output_writeback_queue_io
  - fs/fs-writeback.c:trace_raw_output_writeback_work_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/locks.c:trace_raw_output_locks_get_lock_context
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit
```
**Symbols:**

```
ffffffe000185018-ffffffe0001850b2: trace_print_symbols_seq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
const char *trace_print_symbols_seq(struct trace_seq *p, long unsigned int val, const struct trace_print_flags *symbol_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811a6120)
Location: kernel/trace/trace_output.c:103
Inline: False
Direct callers:
  - arch/x86/mm/init.c:trace_raw_output_tlb_flush
  - kernel/softirq.c:trace_raw_output_softirq
  - kernel/dma/swiotlb.c:trace_raw_output_swiotlb_bounced
  - kernel/time/timer.c:trace_raw_output_tick_stop
  - kernel/time/timer.c:trace_raw_output_hrtimer_start
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start
  - kernel/bpf/core.c:trace_raw_output_mem_return_failed
  - kernel/bpf/core.c:trace_raw_output_mem_connect
  - kernel/bpf/core.c:trace_raw_output_mem_disconnect
  - kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_map_err
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_map
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_template
  - kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx
  - kernel/bpf/core.c:trace_raw_output_xdp_exception
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_reclaim_retry_zone
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate
  - mm/compaction.c:trace_raw_output_kcompactd_wake_template
  - mm/compaction.c:trace_raw_output_mm_compaction_defer_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_end
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page
  - mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd
  - fs/fs-writeback.c:trace_raw_output_writeback_queue_io
  - fs/fs-writeback.c:trace_raw_output_writeback_work_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/locks.c:trace_raw_output_locks_get_lock_context
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/nvme/host/core.c:trace_raw_output_nvme_async_event
  - drivers/nvme/host/core.c:trace_raw_output_nvme_setup_cmd
  - drivers/nvme/host/core.c:trace_raw_output_nvme_setup_cmd
  - drivers/nvme/host/core.c:trace_raw_output_nvme_setup_cmd
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip
  - drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_cmd_class
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit
```
**Symbols:**

```
ffffffff811a6120-ffffffff811a61c9: trace_print_symbols_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const char *trace_print_symbols_seq(struct trace_seq *p, long unsigned int val, const struct trace_print_flags *symbol_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811990a0)
Location: kernel/trace/trace_output.c:103
Inline: False
Direct callers:
  - arch/x86/mm/init.c:trace_raw_output_tlb_flush
  - kernel/softirq.c:trace_raw_output_softirq
  - kernel/dma/swiotlb.c:trace_raw_output_swiotlb_bounced
  - kernel/time/timer.c:trace_raw_output_tick_stop
  - kernel/time/timer.c:trace_raw_output_hrtimer_start
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start
  - kernel/bpf/core.c:trace_raw_output_mem_return_failed
  - kernel/bpf/core.c:trace_raw_output_mem_connect
  - kernel/bpf/core.c:trace_raw_output_mem_disconnect
  - kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_map_err
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_map
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_template
  - kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx
  - kernel/bpf/core.c:trace_raw_output_xdp_exception
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_reclaim_retry_zone
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate
  - mm/compaction.c:trace_raw_output_kcompactd_wake_template
  - mm/compaction.c:trace_raw_output_mm_compaction_defer_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_end
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page
  - mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd
  - fs/fs-writeback.c:trace_raw_output_writeback_queue_io
  - fs/fs-writeback.c:trace_raw_output_writeback_work_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/locks.c:trace_raw_output_locks_get_lock_context
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/nvme/host/core.c:trace_raw_output_nvme_async_event
  - drivers/nvme/host/core.c:trace_raw_output_nvme_setup_cmd
  - drivers/nvme/host/core.c:trace_raw_output_nvme_setup_cmd
  - drivers/nvme/host/core.c:trace_raw_output_nvme_setup_cmd
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit
```
**Symbols:**

```
ffffffff811990a0-ffffffff81199149: trace_print_symbols_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const char *trace_print_symbols_seq(struct trace_seq *p, long unsigned int val, const struct trace_print_flags *symbol_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811a3ef0)
Location: kernel/trace/trace_output.c:103
Inline: False
Direct callers:
  - arch/x86/mm/init.c:trace_raw_output_tlb_flush
  - kernel/softirq.c:trace_raw_output_softirq
  - kernel/dma/swiotlb.c:trace_raw_output_swiotlb_bounced
  - kernel/time/timer.c:trace_raw_output_tick_stop
  - kernel/time/timer.c:trace_raw_output_hrtimer_start
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start
  - kernel/bpf/core.c:trace_raw_output_mem_return_failed
  - kernel/bpf/core.c:trace_raw_output_mem_connect
  - kernel/bpf/core.c:trace_raw_output_mem_disconnect
  - kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_map_err
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_map
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_template
  - kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx
  - kernel/bpf/core.c:trace_raw_output_xdp_exception
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_reclaim_retry_zone
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate
  - mm/compaction.c:trace_raw_output_kcompactd_wake_template
  - mm/compaction.c:trace_raw_output_mm_compaction_defer_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_end
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page
  - mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd
  - fs/fs-writeback.c:trace_raw_output_writeback_queue_io
  - fs/fs-writeback.c:trace_raw_output_writeback_work_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/locks.c:trace_raw_output_locks_get_lock_context
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip
  - drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_cmd_class
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit
```
**Symbols:**

```
ffffffff811a3ef0-ffffffff811a3f99: trace_print_symbols_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const char *trace_print_symbols_seq(struct trace_seq *p, long unsigned int val, const struct trace_print_flags *symbol_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811b1c80)
Location: kernel/trace/trace_output.c:103
Inline: False
Direct callers:
  - arch/x86/mm/init.c:trace_raw_output_tlb_flush
  - kernel/softirq.c:trace_raw_output_softirq
  - kernel/dma/swiotlb.c:trace_raw_output_swiotlb_bounced
  - kernel/time/timer.c:trace_raw_output_tick_stop
  - kernel/time/timer.c:trace_raw_output_hrtimer_start
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/time/timer.c:trace_raw_output_hrtimer_init
  - kernel/trace/power-traces.c:trace_raw_output_dev_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_request
  - kernel/trace/power-traces.c:trace_raw_output_device_pm_callback_start
  - kernel/bpf/core.c:trace_raw_output_mem_return_failed
  - kernel/bpf/core.c:trace_raw_output_mem_connect
  - kernel/bpf/core.c:trace_raw_output_mem_disconnect
  - kernel/bpf/core.c:trace_raw_output_xdp_devmap_xmit
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_enqueue
  - kernel/bpf/core.c:trace_raw_output_xdp_cpumap_kthread
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_map_err
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_map
  - kernel/bpf/core.c:trace_raw_output_xdp_redirect_template
  - kernel/bpf/core.c:trace_raw_output_xdp_bulk_tx
  - kernel/bpf/core.c:trace_raw_output_xdp_exception
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_compact_retry
  - mm/oom_kill.c:trace_raw_output_reclaim_retry_zone
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_isolate
  - mm/compaction.c:trace_raw_output_kcompactd_wake_template
  - mm/compaction.c:trace_raw_output_mm_compaction_defer_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_suitable_template
  - mm/compaction.c:trace_raw_output_mm_compaction_end
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/migrate.c:trace_raw_output_mm_migrate_pages
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:trace_raw_output_mm_collapse_huge_page
  - mm/khugepaged.c:trace_raw_output_mm_khugepaged_scan_pmd
  - fs/fs-writeback.c:trace_raw_output_writeback_queue_io
  - fs/fs-writeback.c:trace_raw_output_writeback_work_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/locks.c:trace_raw_output_locks_get_lock_context
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_raw_output_scsi_dispatch_cmd_start
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/ata/libata-core.c:trace_raw_output_ata_qc_issue
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_urb
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_result
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_read
  - drivers/i2c/i2c-core-smbus.c:trace_raw_output_smbus_write
  - drivers/thermal/thermal_core.c:trace_raw_output_thermal_zone_trip
  - drivers/platform/chrome/cros_ec_trace.c:trace_raw_output_cros_ec_cmd_class
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - drivers/ras/ras.c:trace_raw_output_memory_failure_event
  - net/core/net-traces.c:trace_raw_output_neigh__update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_neigh_update
  - net/core/net-traces.c:trace_raw_output_tcp_event_sk_skb
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_inet_sock_set_state
  - net/core/net-traces.c:trace_raw_output_sock_exceed_buf_limit
```
**Symbols:**

```
ffffffff811b1c80-ffffffff811b1d29: trace_print_symbols_seq (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
