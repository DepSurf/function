# Function: <code>kstrtoull</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int kstrtoull(const char *s, unsigned int base, long long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81401dd0)
Location: lib/kstrtox.c:122
Inline: True
Inline callers:
  - lib/kstrtox.c:_kstrtoul
  - lib/kstrtox.c:kstrtouint
  - lib/kstrtox.c:kstrtou16
  - lib/kstrtox.c:kstrtou8
  - lib/kstrtox.c:kstrtoul_from_user
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/dumpstack.c:kstack_setup
  - arch/x86/kernel/dumpstack.c:code_bytes_setup
  - arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/mcheck/mce.c:set_bank
  - arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/check.c:set_corruption_check
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/pci-calgary_64.c:calgary_parse_options
  - kernel/params.c:param_set_ullong
  - kernel/ksysfs.c:kexec_crash_size_store
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:pm_async_store
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/livepatch/core.c:enabled_store
  - kernel/cgroup.c:cgroup_file_write
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events_filter.c:replace_preds
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - mm/backing-dev.c:read_ahead_kb_store
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store_common
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/ksm.c:run_store
  - mm/slub.c:remote_node_defrag_ratio_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:min_partial_store
  - mm/slub.c:order_store
  - mm/huge_memory.c:alloc_sleep_millisecs_store
  - mm/huge_memory.c:scan_sleep_millisecs_store
  - mm/huge_memory.c:pages_to_scan_store
  - mm/huge_memory.c:khugepaged_max_ptes_none_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - security/selinux/hooks.c:enforcing_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/selinuxfs.c:checkreqprot_setup
  - security/apparmor/lsm.c:apparmor_enabled_setup
  - security/integrity/integrity_audit.c:integrity_audit_setup
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_discard_max_store
  - block/blk-sysfs.c:queue_ra_store
  - block/blk-sysfs.c:queue_requests_store
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_max_sectors_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:dev_bus_rescan_store
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/msi.c:msi_mode_show
  - drivers/video/backlight/backlight.c:bl_power_store
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/acpi/osl.c:setup_acpi_rsdp
  - drivers/acpi/sysfs.c:counter_set
  - drivers/xen/pcpu.c:store_online
  - drivers/xen/xen-selfballoon.c:store_frontswap_inertia
  - drivers/xen/xen-selfballoon.c:store_frontswap_hysteresis
  - drivers/xen/xen-selfballoon.c:store_selfballoon_reserved_mb
  - drivers/xen/xen-selfballoon.c:store_selfballoon_min_usable_mb
  - drivers/xen/xen-selfballoon.c:store_selfballoon_uphys
  - drivers/xen/xen-selfballoon.c:store_selfballoon_downhys
  - drivers/xen/xen-selfballoon.c:store_selfballoon_interval
  - drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking
  - drivers/xen/xen-selfballoon.c:store_selfballooning
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
  - drivers/base/memory.c:store_hard_offline_page
  - drivers/base/memory.c:store_soft_offline_page
  - drivers/base/memory.c:memory_probe_store
  - drivers/misc/bmp085.c:set_oversampling
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/nvdimm/core.c:nd_sector_size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
  - drivers/scsi/sd.c:max_write_same_blocks_store
  - drivers/thermal/thermal_core.c:trip_point_temp_store
  - drivers/thermal/thermal_core.c:emul_temp_store
  - drivers/md/md.c:min_sync_store
  - drivers/md/md.c:strict_blocks_to_sectors
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:new_offset_store
  - drivers/md/md.c:offset_store
  - drivers/md/md.c:max_sync_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/bitmap.c:backlog_store
  - drivers/md/bitmap.c:space_store
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
  - drivers/cpuidle/sysfs.c:store_state_disable
  - drivers/leds/led-class.c:brightness_store
  - drivers/powercap/powercap_sys.c:energy_uj_store
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/ipv4/tcp.c:set_thash_entries
  - net/rfkill/core.c:soft_store
  - net/rfkill/core.c:state_store
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff81401dd0-ffffffff81401de6: kstrtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int kstrtoull(const char *s, unsigned int base, long long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81449d25)
Location: lib/kstrtox.c:122
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
  - lib/kstrtox.c:kstrtoull_from_user
  - lib/kstrtox.c:kstrtou8
  - lib/kstrtox.c:kstrtou16
  - lib/kstrtox.c:kstrtouint
  - lib/kstrtox.c:_kstrtoul
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/dumpstack.c:code_bytes_setup
  - arch/x86/kernel/dumpstack.c:kstack_setup
  - arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce
  - arch/x86/kernel/cpu/mcheck/mce.c:set_bank
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
  - arch/x86/kernel/pci-calgary_64.c:calgary_parse_options
  - kernel/params.c:param_set_ullong
  - kernel/ksysfs.c:kexec_crash_size_store
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:pm_async_store
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/livepatch/core.c:enabled_store
  - kernel/cgroup.c:cgroup_file_write
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events_filter.c:replace_preds
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/events/core.c:perf_event_set_addr_filter
  - kernel/events/core.c:perf_event_set_addr_filter
  - mm/backing-dev.c:read_ahead_kb_store
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store_common
  - mm/ksm.c:merge_across_nodes_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
  - mm/slub.c:remote_node_defrag_ratio_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:min_partial_store
  - mm/slub.c:order_store
  - mm/huge_memory.c:single_hugepage_flag_store
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
  - security/selinux/selinuxfs.c:checkreqprot_setup
  - security/apparmor/lsm.c:apparmor_enabled_setup
  - security/integrity/integrity_audit.c:integrity_audit_setup
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-sysfs.c:queue_max_sectors_store
  - block/blk-sysfs.c:queue_discard_max_store
  - block/blk-sysfs.c:queue_ra_store
  - block/blk-sysfs.c:queue_requests_store
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:dev_bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
  - drivers/pci/msi.c:msi_mode_show
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
  - drivers/acpi/osl.c:setup_acpi_rsdp
  - drivers/acpi/sysfs.c:counter_set
  - drivers/xen/pcpu.c:store_online
  - drivers/xen/xen-selfballoon.c:store_frontswap_hysteresis
  - drivers/xen/xen-selfballoon.c:store_frontswap_inertia
  - drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking
  - drivers/xen/xen-selfballoon.c:store_selfballoon_reserved_mb
  - drivers/xen/xen-selfballoon.c:store_selfballoon_min_usable_mb
  - drivers/xen/xen-selfballoon.c:store_selfballoon_uphys
  - drivers/xen/xen-selfballoon.c:store_selfballoon_downhys
  - drivers/xen/xen-selfballoon.c:store_selfballoon_interval
  - drivers/xen/xen-selfballoon.c:store_selfballooning
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
  - drivers/base/memory.c:store_hard_offline_page
  - drivers/base/memory.c:store_soft_offline_page
  - drivers/base/memory.c:memory_probe_store
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/nvdimm/core.c:nd_sector_size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
  - drivers/scsi/sd.c:max_write_same_blocks_store
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
  - drivers/rtc/rtc-sysfs.c:max_user_freq_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:max_sync_store
  - drivers/md/md.c:min_sync_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:strict_blocks_to_sectors
  - drivers/md/md.c:new_offset_store
  - drivers/md/md.c:offset_store
  - drivers/md/bitmap.c:backlog_store
  - drivers/md/bitmap.c:space_store
  - drivers/cpuidle/sysfs.c:store_state_disable
  - drivers/leds/led-class.c:brightness_store
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:energy_uj_store
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/ipv4/tcp.c:set_thash_entries
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff81449880-ffffffff81449896: kstrtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int kstrtoull(const char *s, unsigned int base, long long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff814686e5)
Location: lib/kstrtox.c:118
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
  - lib/kstrtox.c:kstrtoull_from_user
  - lib/kstrtox.c:kstrtou8
  - lib/kstrtox.c:kstrtou16
  - lib/kstrtox.c:kstrtouint
  - lib/kstrtox.c:_kstrtoul
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/kernel/dumpstack.c:code_bytes_setup
  - arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce
  - arch/x86/kernel/cpu/mcheck/mce.c:set_bank
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
  - arch/x86/kernel/pci-calgary_64.c:calgary_parse_options
  - kernel/params.c:param_set_ullong
  - kernel/ksysfs.c:kexec_crash_size_store
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:pm_async_store
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/livepatch/core.c:enabled_store
  - kernel/cgroup.c:cgroup_file_write
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events_filter.c:replace_preds
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/events/core.c:perf_event_set_addr_filter
  - kernel/events/core.c:perf_event_set_addr_filter
  - mm/backing-dev.c:read_ahead_kb_store
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store_common
  - mm/ksm.c:merge_across_nodes_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
  - mm/slub.c:remote_node_defrag_ratio_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:min_partial_store
  - mm/slub.c:order_store
  - mm/huge_memory.c:single_hugepage_flag_store
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
  - security/selinux/selinuxfs.c:checkreqprot_setup
  - security/apparmor/lsm.c:apparmor_enabled_setup
  - security/integrity/integrity_audit.c:integrity_audit_setup
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-sysfs.c:queue_max_sectors_store
  - block/blk-sysfs.c:queue_discard_max_store
  - block/blk-sysfs.c:queue_ra_store
  - block/blk-sysfs.c:queue_requests_store
  - lib/parser.c:match_u64
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:dev_bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
  - drivers/pci/msi.c:msi_mode_show
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
  - drivers/acpi/osl.c:setup_acpi_rsdp
  - drivers/acpi/sysfs.c:counter_set
  - drivers/xen/pcpu.c:store_online
  - drivers/xen/xen-selfballoon.c:store_frontswap_hysteresis
  - drivers/xen/xen-selfballoon.c:store_frontswap_inertia
  - drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking
  - drivers/xen/xen-selfballoon.c:store_selfballoon_reserved_mb
  - drivers/xen/xen-selfballoon.c:store_selfballoon_min_usable_mb
  - drivers/xen/xen-selfballoon.c:store_selfballoon_uphys
  - drivers/xen/xen-selfballoon.c:store_selfballoon_downhys
  - drivers/xen/xen-selfballoon.c:store_selfballoon_interval
  - drivers/xen/xen-selfballoon.c:store_selfballooning
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
  - drivers/base/memory.c:store_hard_offline_page
  - drivers/base/memory.c:store_soft_offline_page
  - drivers/base/memory.c:memory_probe_store
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/nvdimm/core.c:nd_sector_size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
  - drivers/scsi/sd.c:max_write_same_blocks_store
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
  - drivers/rtc/rtc-sysfs.c:max_user_freq_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:max_sync_store
  - drivers/md/md.c:min_sync_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:strict_blocks_to_sectors
  - drivers/md/md.c:new_offset_store
  - drivers/md/md.c:offset_store
  - drivers/md/bitmap.c:backlog_store
  - drivers/md/bitmap.c:space_store
  - drivers/cpuidle/sysfs.c:store_state_disable
  - drivers/leds/led-class.c:brightness_store
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:energy_uj_store
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/ipv4/tcp.c:set_thash_entries
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff81468240-ffffffff81468256: kstrtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int kstrtoull(const char *s, unsigned int base, long long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8146ddeb)
Location: lib/kstrtox.c:120
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
  - lib/kstrtox.c:kstrtoull_from_user
  - lib/kstrtox.c:kstrtou8
  - lib/kstrtox.c:kstrtou16
  - lib/kstrtox.c:kstrtouint
  - lib/kstrtox.c:_kstrtoul
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/kernel/dumpstack.c:code_bytes_setup
  - arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce
  - arch/x86/kernel/cpu/mcheck/mce.c:set_bank
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_interrupt_enable
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
  - arch/x86/kernel/pci-calgary_64.c:calgary_parse_options
  - kernel/params.c:param_set_ulong
  - kernel/ksysfs.c:kexec_crash_size_store
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:pm_async_store
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events_filter.c:replace_preds
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/backing-dev.c:read_ahead_kb_store
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store_common
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
  - mm/slub.c:remote_node_defrag_ratio_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:min_partial_store
  - mm/slub.c:order_store
  - mm/huge_memory.c:single_hugepage_flag_store
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
  - security/selinux/selinuxfs.c:checkreqprot_setup
  - security/apparmor/lsm.c:apparmor_enabled_setup
  - security/integrity/integrity_audit.c:integrity_audit_setup
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-sysfs.c:queue_max_sectors_store
  - block/blk-sysfs.c:queue_discard_max_store
  - block/blk-sysfs.c:queue_ra_store
  - block/blk-sysfs.c:queue_requests_store
  - lib/parser.c:match_u64
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:dev_bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
  - drivers/pci/msi.c:msi_mode_show
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
  - drivers/acpi/osl.c:setup_acpi_rsdp
  - drivers/acpi/sysfs.c:counter_set
  - drivers/xen/pcpu.c:store_online
  - drivers/xen/xen-selfballoon.c:store_frontswap_hysteresis
  - drivers/xen/xen-selfballoon.c:store_frontswap_inertia
  - drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking
  - drivers/xen/xen-selfballoon.c:store_selfballoon_reserved_mb
  - drivers/xen/xen-selfballoon.c:store_selfballoon_min_usable_mb
  - drivers/xen/xen-selfballoon.c:store_selfballoon_uphys
  - drivers/xen/xen-selfballoon.c:store_selfballoon_downhys
  - drivers/xen/xen-selfballoon.c:store_selfballoon_interval
  - drivers/xen/xen-selfballoon.c:store_selfballooning
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
  - drivers/base/memory.c:store_hard_offline_page
  - drivers/base/memory.c:store_soft_offline_page
  - drivers/base/memory.c:memory_probe_store
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/nvdimm/core.c:nd_sector_size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
  - drivers/scsi/sd.c:max_write_same_blocks_store
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
  - drivers/rtc/rtc-sysfs.c:max_user_freq_store
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:max_sync_store
  - drivers/md/md.c:min_sync_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:ppl_sector_store
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:strict_blocks_to_sectors
  - drivers/md/md.c:new_offset_store
  - drivers/md/md.c:offset_store
  - drivers/md/bitmap.c:chunksize_store
  - drivers/md/bitmap.c:backlog_store
  - drivers/md/bitmap.c:space_store
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
  - drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec
  - drivers/cpuidle/sysfs.c:store_state_disable
  - drivers/leds/led-class.c:brightness_store
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:energy_uj_store
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff8146d940-ffffffff8146d956: kstrtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int kstrtoull(const char *s, unsigned int base, long long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8149a11b)
Location: lib/kstrtox.c:121
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
  - lib/kstrtox.c:kstrtoull_from_user
  - lib/kstrtox.c:kstrtou8
  - lib/kstrtox.c:kstrtou16
  - lib/kstrtox.c:kstrtouint
  - lib/kstrtox.c:_kstrtoul
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/kernel/dumpstack.c:code_bytes_setup
  - arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce
  - arch/x86/kernel/cpu/mcheck/mce.c:set_bank
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_interrupt_enable
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
  - arch/x86/kernel/pci-calgary_64.c:calgary_parse_options
  - kernel/params.c:param_set_ulong
  - kernel/ksysfs.c:kexec_crash_size_store
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:pm_async_store
  - kernel/power/hibernate.c:resume_offset_store
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events_filter.c:replace_preds
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/backing-dev.c:read_ahead_kb_store
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store_common
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
  - mm/slub.c:remote_node_defrag_ratio_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:min_partial_store
  - mm/slub.c:order_store
  - mm/huge_memory.c:single_hugepage_flag_store
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
  - security/selinux/selinuxfs.c:checkreqprot_setup
  - security/apparmor/lsm.c:apparmor_enabled_setup
  - security/integrity/integrity_audit.c:integrity_audit_setup
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-sysfs.c:queue_max_sectors_store
  - block/blk-sysfs.c:queue_discard_max_store
  - block/blk-sysfs.c:queue_ra_store
  - block/blk-sysfs.c:queue_requests_store
  - lib/parser.c:match_u64
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:dev_bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
  - drivers/pci/msi.c:msi_mode_show
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
  - drivers/acpi/osl.c:setup_acpi_rsdp
  - drivers/acpi/sysfs.c:counter_set
  - drivers/xen/pcpu.c:store_online
  - drivers/xen/xen-selfballoon.c:store_frontswap_hysteresis
  - drivers/xen/xen-selfballoon.c:store_frontswap_inertia
  - drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking
  - drivers/xen/xen-selfballoon.c:store_selfballoon_reserved_mb
  - drivers/xen/xen-selfballoon.c:store_selfballoon_min_usable_mb
  - drivers/xen/xen-selfballoon.c:store_selfballoon_uphys
  - drivers/xen/xen-selfballoon.c:store_selfballoon_downhys
  - drivers/xen/xen-selfballoon.c:store_selfballoon_interval
  - drivers/xen/xen-selfballoon.c:store_selfballooning
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
  - drivers/base/memory.c:store_hard_offline_page
  - drivers/base/memory.c:store_soft_offline_page
  - drivers/base/memory.c:memory_probe_store
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/nvdimm/core.c:nd_size_select_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
  - drivers/scsi/sd.c:max_write_same_blocks_store
  - drivers/rtc/rtc-sysfs.c:max_user_freq_store
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:max_sync_store
  - drivers/md/md.c:min_sync_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:ppl_sector_store
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:strict_blocks_to_sectors
  - drivers/md/md.c:new_offset_store
  - drivers/md/md.c:offset_store
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
  - drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec
  - drivers/cpuidle/sysfs.c:store_state_disable
  - drivers/leds/led-class.c:brightness_store
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:energy_uj_store
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff81499c70-ffffffff81499c86: kstrtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int kstrtoull(const char *s, unsigned int base, long long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff814cf3cb)
Location: lib/kstrtox.c:121
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
  - lib/kstrtox.c:kstrtoull_from_user
  - lib/kstrtox.c:kstrtou8
  - lib/kstrtox.c:kstrtou16
  - lib/kstrtox.c:kstrtouint
  - lib/kstrtox.c:_kstrtoul
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce
  - arch/x86/kernel/cpu/mcheck/mce.c:set_bank
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_interrupt_enable
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
  - arch/x86/kernel/pci-calgary_64.c:calgary_parse_options
  - kernel/params.c:param_set_ulong
  - kernel/ksysfs.c:kexec_crash_size_store
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:pm_async_store
  - kernel/power/hibernate.c:resume_offset_store
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/backing-dev.c:read_ahead_kb_store
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store_common
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
  - mm/slub.c:min_partial_store
  - mm/huge_memory.c:single_hugepage_flag_store
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
  - security/apparmor/lsm.c:apparmor_enabled_setup
  - security/integrity/integrity_audit.c:integrity_audit_setup
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-sysfs.c:queue_max_sectors_store
  - block/blk-sysfs.c:queue_discard_max_store
  - block/blk-sysfs.c:queue_ra_store
  - block/blk-sysfs.c:queue_requests_store
  - lib/parser.c:match_u64
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:dev_bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
  - drivers/pci/msi.c:msi_mode_show
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
  - drivers/acpi/osl.c:setup_acpi_rsdp
  - drivers/acpi/sysfs.c:counter_set
  - drivers/xen/pcpu.c:store_online
  - drivers/xen/xen-selfballoon.c:store_frontswap_hysteresis
  - drivers/xen/xen-selfballoon.c:store_frontswap_inertia
  - drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking
  - drivers/xen/xen-selfballoon.c:store_selfballoon_reserved_mb
  - drivers/xen/xen-selfballoon.c:store_selfballoon_min_usable_mb
  - drivers/xen/xen-selfballoon.c:store_selfballoon_uphys
  - drivers/xen/xen-selfballoon.c:store_selfballoon_downhys
  - drivers/xen/xen-selfballoon.c:store_selfballoon_interval
  - drivers/xen/xen-selfballoon.c:store_selfballooning
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
  - drivers/base/memory.c:store_hard_offline_page
  - drivers/base/memory.c:store_soft_offline_page
  - drivers/base/memory.c:memory_probe_store
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/nvdimm/core.c:nd_size_select_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/sd.c:max_write_same_blocks_store
  - drivers/rtc/rtc-sysfs.c:max_user_freq_store
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:max_sync_store
  - drivers/md/md.c:min_sync_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:ppl_sector_store
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:strict_blocks_to_sectors
  - drivers/md/md.c:new_offset_store
  - drivers/md/md.c:offset_store
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
  - drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec
  - drivers/cpuidle/sysfs.c:store_state_disable
  - drivers/leds/led-class.c:brightness_store
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:energy_uj_store
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/ipv4/tcp.c:set_thash_entries
  - net/ipv4/udp.c:set_uhash_entries
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff814cef20-ffffffff814cef36: kstrtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int kstrtoull(const char *s, unsigned int base, long long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff814e3cdb)
Location: lib/kstrtox.c:121
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
  - lib/kstrtox.c:kstrtoull_from_user
  - lib/kstrtox.c:kstrtou8
  - lib/kstrtox.c:kstrtou16
  - lib/kstrtox.c:kstrtouint
  - lib/kstrtox.c:_kstrtoul
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
  - arch/x86/kernel/pci-calgary_64.c:calgary_parse_options
  - kernel/params.c:param_set_ulong
  - kernel/ksysfs.c:kexec_crash_size_store
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:pm_async_store
  - kernel/power/hibernate.c:resume_offset_store
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/backing-dev.c:read_ahead_kb_store
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store_common
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
  - mm/slub.c:min_partial_store
  - mm/huge_memory.c:single_hugepage_flag_store
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
  - security/apparmor/lsm.c:apparmor_enabled_setup
  - security/integrity/integrity_audit.c:integrity_audit_setup
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-sysfs.c:queue_max_sectors_store
  - block/blk-sysfs.c:queue_discard_max_store
  - block/blk-sysfs.c:queue_ra_store
  - block/blk-sysfs.c:queue_requests_store
  - lib/parser.c:match_u64
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:dev_bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
  - drivers/pci/msi.c:msi_mode_show
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
  - drivers/acpi/osl.c:setup_acpi_rsdp
  - drivers/acpi/sysfs.c:counter_set
  - drivers/xen/pcpu.c:store_online
  - drivers/xen/xen-selfballoon.c:store_frontswap_hysteresis
  - drivers/xen/xen-selfballoon.c:store_frontswap_inertia
  - drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking
  - drivers/xen/xen-selfballoon.c:store_selfballoon_reserved_mb
  - drivers/xen/xen-selfballoon.c:store_selfballoon_min_usable_mb
  - drivers/xen/xen-selfballoon.c:store_selfballoon_uphys
  - drivers/xen/xen-selfballoon.c:store_selfballoon_downhys
  - drivers/xen/xen-selfballoon.c:store_selfballoon_interval
  - drivers/xen/xen-selfballoon.c:store_selfballooning
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
  - drivers/base/core.c:device_store_ulong
  - drivers/base/memory.c:hard_offline_page_store
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:probe_store
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/nvdimm/core.c:nd_size_select_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/sd.c:max_write_same_blocks_store
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/rtc/sysfs.c:max_user_freq_store
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:max_sync_store
  - drivers/md/md.c:min_sync_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:ppl_sector_store
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:strict_blocks_to_sectors
  - drivers/md/md.c:new_offset_store
  - drivers/md/md.c:offset_store
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
  - drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec
  - drivers/cpuidle/sysfs.c:store_state_disable
  - drivers/leds/led-class.c:brightness_store
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:energy_uj_store
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/ipv4/tcp.c:set_thash_entries
  - net/ipv4/udp.c:set_uhash_entries
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff814e3830-ffffffff814e3846: kstrtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int kstrtoull(const char *s, unsigned int base, long long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff815100bb)
Location: lib/kstrtox.c:121
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
  - lib/kstrtox.c:kstrtoull_from_user
  - lib/kstrtox.c:kstrtou8
  - lib/kstrtox.c:kstrtou16
  - lib/kstrtox.c:kstrtouint
  - lib/kstrtox.c:_kstrtoul
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
  - arch/x86/kernel/pci-calgary_64.c:calgary_parse_options
  - kernel/params.c:param_set_ullong
  - kernel/params.c:param_set_ulong
  - kernel/ksysfs.c:kexec_crash_size_store
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:pm_async_store
  - kernel/power/hibernate.c:resume_offset_store
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - mm/backing-dev.c:read_ahead_kb_store
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store_common
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
  - mm/slub.c:min_partial_store
  - mm/huge_memory.c:single_hugepage_flag_store
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
  - fs/fs_parser.c:fs_parse
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
  - security/apparmor/lsm.c:apparmor_enabled_setup
  - security/integrity/integrity_audit.c:integrity_audit_setup
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-sysfs.c:queue_max_sectors_store
  - block/blk-sysfs.c:queue_discard_max_store
  - block/blk-sysfs.c:queue_ra_store
  - block/blk-sysfs.c:queue_requests_store
  - lib/parser.c:match_u64
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:dev_bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
  - drivers/pci/msi.c:msi_mode_show
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
  - drivers/acpi/osl.c:setup_acpi_rsdp
  - drivers/acpi/sysfs.c:counter_set
  - drivers/xen/pcpu.c:store_online
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
  - drivers/base/core.c:device_store_ulong
  - drivers/base/memory.c:hard_offline_page_store
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:probe_store
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/nvdimm/core.c:nd_size_select_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/sd.c:max_write_same_blocks_store
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/rtc/sysfs.c:max_user_freq_store
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:max_sync_store
  - drivers/md/md.c:min_sync_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:ppl_sector_store
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:strict_blocks_to_sectors
  - drivers/md/md.c:new_offset_store
  - drivers/md/md.c:offset_store
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
  - drivers/cpuidle/sysfs.c:store_state_disable
  - drivers/leds/led-class.c:brightness_store
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:energy_uj_store
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/ipv4/tcp.c:set_thash_entries
  - net/ipv4/udp.c:set_uhash_entries
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff8150fc10-ffffffff8150fc26: kstrtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int kstrtoull(const char *s, unsigned int base, long long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8152dfbb)
Location: lib/kstrtox.c:121
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
  - lib/kstrtox.c:kstrtoull_from_user
  - lib/kstrtox.c:kstrtou8
  - lib/kstrtox.c:kstrtou16
  - lib/kstrtox.c:kstrtouint
  - lib/kstrtox.c:_kstrtoul
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
  - arch/x86/kernel/pci-calgary_64.c:calgary_parse_options
  - kernel/params.c:param_set_ullong
  - kernel/params.c:param_set_ulong
  - kernel/ksysfs.c:kexec_crash_size_store
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:pm_async_store
  - kernel/power/hibernate.c:resume_offset_store
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - mm/backing-dev.c:read_ahead_kb_store
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store_common
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
  - mm/slub.c:min_partial_store
  - mm/huge_memory.c:single_hugepage_flag_store
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
  - fs/fs_parser.c:fs_parse
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
  - security/apparmor/lsm.c:apparmor_enabled_setup
  - security/integrity/integrity_audit.c:integrity_audit_setup
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-sysfs.c:queue_max_sectors_store
  - block/blk-sysfs.c:queue_discard_max_store
  - block/blk-sysfs.c:queue_ra_store
  - block/blk-sysfs.c:queue_requests_store
  - lib/parser.c:match_u64
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
  - drivers/pci/msi.c:msi_mode_show
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
  - drivers/acpi/osl.c:setup_acpi_rsdp
  - drivers/acpi/sysfs.c:counter_set
  - drivers/xen/pcpu.c:store_online
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
  - drivers/base/core.c:device_store_ulong
  - drivers/base/memory.c:hard_offline_page_store
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:probe_store
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/nvdimm/core.c:nd_size_select_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/sd.c:max_write_same_blocks_store
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/rtc/sysfs.c:max_user_freq_store
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:max_sync_store
  - drivers/md/md.c:min_sync_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:ppl_sector_store
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:strict_blocks_to_sectors
  - drivers/md/md.c:new_offset_store
  - drivers/md/md.c:offset_store
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
  - drivers/cpuidle/sysfs.c:store_state_disable
  - drivers/leds/led-class.c:brightness_store
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:energy_uj_store
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/ipv4/tcp.c:set_thash_entries
  - net/ipv4/udp.c:set_uhash_entries
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff8152db10-ffffffff8152db26: kstrtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int kstrtoull(const char *s, unsigned int base, long long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81591d2b)
Location: lib/kstrtox.c:121
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtou8_from_user
  - lib/kstrtox.c:kstrtou16_from_user
  - lib/kstrtox.c:kstrtouint_from_user
  - lib/kstrtox.c:kstrtoul_from_user
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:kstrtoull_from_user
  - lib/kstrtox.c:_kstrtol
  - lib/kstrtox.c:_kstrtoul
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
  - kernel/panic.c:panic_on_taint_setup
  - kernel/ksysfs.c:kexec_crash_size_store
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:sync_on_suspend_store
  - kernel/power/main.c:pm_async_store
  - kernel/power/hibernate.c:resume_offset_store
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace_functions.c:ftrace_cpudump_callback
  - kernel/trace/trace_functions.c:ftrace_dump_callback
  - kernel/trace/trace_functions.c:ftrace_stacktrace_callback
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_inject.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/backing-dev.c:read_ahead_kb_store
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_mempolicy_store
  - mm/hugetlb.c:nr_hugepages_store
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
  - mm/slub.c:min_partial_store
  - mm/huge_memory.c:use_zero_page_store
  - mm/khugepaged.c:khugepaged_max_ptes_shared_store
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
  - fs/fs_parser.c:fs_param_is_u64
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
  - security/apparmor/lsm.c:apparmor_enabled_setup
  - security/integrity/integrity_audit.c:integrity_audit_setup
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-sysfs.c:queue_max_sectors_store
  - block/blk-sysfs.c:queue_discard_max_store
  - block/blk-sysfs.c:queue_ra_store
  - block/blk-sysfs.c:queue_requests_store
  - lib/parser.c:match_u64
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
  - drivers/pci/msi.c:msi_mode_show
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
  - drivers/acpi/osl.c:setup_acpi_rsdp
  - drivers/acpi/sysfs.c:counter_set
  - drivers/xen/pcpu.c:store_online
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
  - drivers/base/core.c:device_store_ulong
  - drivers/base/memory.c:hard_offline_page_store
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:probe_store
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/nvdimm/core.c:nd_size_select_store
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/sd.c:max_write_same_blocks_store
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/rtc/sysfs.c:max_user_freq_store
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:max_sync_store
  - drivers/md/md.c:min_sync_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:ppl_sector_store
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:rdev_size_store
  - drivers/md/md.c:new_offset_store
  - drivers/md/md.c:offset_store
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
  - drivers/leds/led-class.c:brightness_store
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:energy_uj_store
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:carrier_store
  - net/ipv4/tcp.c:set_thash_entries
  - net/ipv4/udp.c:set_uhash_entries
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff81591900-ffffffff81591916: kstrtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int kstrtoull(const char *s, unsigned int base, long long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff815ae86b)
Location: lib/kstrtox.c:120
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtou8_from_user
  - lib/kstrtox.c:kstrtou16_from_user
  - lib/kstrtox.c:kstrtouint_from_user
  - lib/kstrtox.c:kstrtoul_from_user
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:kstrtoull_from_user
  - lib/kstrtox.c:_kstrtol
  - lib/kstrtox.c:_kstrtoul
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
  - kernel/panic.c:panic_on_taint_setup
  - kernel/ksysfs.c:kexec_crash_size_store
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:sync_on_suspend_store
  - kernel/power/main.c:pm_async_store
  - kernel/power/hibernate.c:resume_offset_store
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace_functions.c:ftrace_cpudump_callback
  - kernel/trace/trace_functions.c:ftrace_dump_callback
  - kernel/trace/trace_functions.c:ftrace_stacktrace_callback
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_inject.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/backing-dev.c:read_ahead_kb_store
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_mempolicy_store
  - mm/hugetlb.c:nr_hugepages_store
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/slub.c:min_partial_store
  - mm/huge_memory.c:use_zero_page_store
  - mm/khugepaged.c:khugepaged_max_ptes_shared_store
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - fs/libfs.c:simple_attr_write
  - fs/fs_parser.c:fs_param_is_u64
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
  - security/apparmor/lsm.c:apparmor_enabled_setup
  - security/integrity/integrity_audit.c:integrity_audit_setup
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_stable_writes_store
  - block/blk-sysfs.c:queue_iostats_store
  - block/blk-sysfs.c:queue_random_store
  - block/blk-sysfs.c:queue_nonrot_store
  - block/blk-sysfs.c:queue_max_sectors_store
  - block/blk-sysfs.c:queue_discard_max_store
  - block/blk-sysfs.c:queue_ra_store
  - block/blk-sysfs.c:queue_requests_store
  - lib/parser.c:match_u64
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
  - drivers/pci/msi.c:msi_mode_show
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
  - drivers/acpi/osl.c:setup_acpi_rsdp
  - drivers/acpi/sysfs.c:counter_set
  - drivers/xen/pcpu.c:store_online
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
  - drivers/base/core.c:device_store_ulong
  - drivers/base/memory.c:hard_offline_page_store
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:probe_store
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/nvdimm/core.c:nd_size_select_store
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:size_store
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/sd.c:max_write_same_blocks_store
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/rtc/sysfs.c:max_user_freq_store
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:max_sync_store
  - drivers/md/md.c:min_sync_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:ppl_sector_store
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:rdev_size_store
  - drivers/md/md.c:new_offset_store
  - drivers/md/md.c:offset_store
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
  - drivers/leds/led-class.c:brightness_store
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:energy_uj_store
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:carrier_store
  - net/ipv4/tcp.c:set_thash_entries
  - net/ipv4/udp.c:set_uhash_entries
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff815ae440-ffffffff815ae456: kstrtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int kstrtoull(const char *s, unsigned int base, long long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff815b92ab)
Location: lib/kstrtox.c:127
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtou8_from_user
  - lib/kstrtox.c:kstrtou16_from_user
  - lib/kstrtox.c:kstrtouint_from_user
  - lib/kstrtox.c:kstrtoul_from_user
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:kstrtoull_from_user
  - lib/kstrtox.c:_kstrtol
  - lib/kstrtox.c:_kstrtoul
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
  - kernel/panic.c:panic_on_taint_setup
  - kernel/ksysfs.c:kexec_crash_size_store
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:sync_on_suspend_store
  - kernel/power/main.c:pm_async_store
  - kernel/power/hibernate.c:resume_offset_store
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/misc.c:misc_cg_max_write
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace_functions.c:ftrace_cpudump_callback
  - kernel/trace/trace_functions.c:ftrace_dump_callback
  - kernel/trace/trace_functions.c:ftrace_stacktrace_callback
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_inject.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/backing-dev.c:read_ahead_kb_store
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_mempolicy_store
  - mm/hugetlb.c:nr_hugepages_store
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/slub.c:min_partial_store
  - mm/huge_memory.c:use_zero_page_store
  - mm/khugepaged.c:khugepaged_max_ptes_shared_store
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - fs/libfs.c:simple_attr_write
  - fs/fs_parser.c:fs_param_is_u64
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
  - security/apparmor/lsm.c:apparmor_enabled_setup
  - security/integrity/integrity_audit.c:integrity_audit_setup
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_stable_writes_store
  - block/blk-sysfs.c:queue_iostats_store
  - block/blk-sysfs.c:queue_random_store
  - block/blk-sysfs.c:queue_nonrot_store
  - block/blk-sysfs.c:queue_max_sectors_store
  - block/blk-sysfs.c:queue_discard_max_store
  - block/blk-sysfs.c:queue_ra_store
  - block/blk-sysfs.c:queue_requests_store
  - lib/parser.c:match_u64
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
  - drivers/pci/msi.c:msi_mode_show
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
  - drivers/acpi/osl.c:setup_acpi_rsdp
  - drivers/acpi/sysfs.c:counter_set
  - drivers/xen/pcpu.c:store_online
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
  - drivers/base/core.c:device_store_ulong
  - drivers/base/memory.c:hard_offline_page_store
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:probe_store
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/nvdimm/core.c:nd_size_select_store
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:size_store
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/sd.c:max_write_same_blocks_store
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/rtc/sysfs.c:max_user_freq_store
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:max_sync_store
  - drivers/md/md.c:min_sync_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:ppl_sector_store
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:rdev_size_store
  - drivers/md/md.c:new_offset_store
  - drivers/md/md.c:offset_store
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
  - drivers/leds/led-class.c:brightness_store
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:energy_uj_store
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/ipv4/tcp.c:set_thash_entries
  - net/ipv4/udp.c:set_uhash_entries
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff815b8f40-ffffffff815b8f56: kstrtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int kstrtoull(const char *s, unsigned int base, long long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8161fb41)
Location: lib/kstrtox.c:128
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtou8_from_user
  - lib/kstrtox.c:kstrtou16_from_user
  - lib/kstrtox.c:kstrtouint_from_user
  - lib/kstrtox.c:kstrtoul_from_user
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:kstrtoull_from_user
  - lib/kstrtox.c:_kstrtol
  - lib/kstrtox.c:_kstrtoul
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
  - kernel/panic.c:panic_on_taint_setup
  - kernel/ksysfs.c:kexec_crash_size_store
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:sync_on_suspend_store
  - kernel/power/main.c:pm_async_store
  - kernel/power/hibernate.c:resume_offset_store
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/irq/msi.c:msi_mode_show
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/misc.c:misc_cg_max_write
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace_functions.c:ftrace_cpudump_callback
  - kernel/trace/trace_functions.c:ftrace_dump_callback
  - kernel/trace/trace_functions.c:ftrace_stacktrace_callback
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_inject.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/backing-dev.c:read_ahead_kb_store
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_mempolicy_store
  - mm/hugetlb.c:nr_hugepages_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/slub.c:min_partial_store
  - mm/kfence/core.c:param_set_sample_interval
  - mm/huge_memory.c:use_zero_page_store
  - mm/khugepaged.c:khugepaged_max_ptes_shared_store
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - fs/libfs.c:simple_attr_write
  - fs/fs_parser.c:fs_param_is_u64
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
  - security/apparmor/lsm.c:apparmor_enabled_setup
  - security/integrity/integrity_audit.c:integrity_audit_setup
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_stable_writes_store
  - block/blk-sysfs.c:queue_iostats_store
  - block/blk-sysfs.c:queue_random_store
  - block/blk-sysfs.c:queue_nonrot_store
  - block/blk-sysfs.c:queue_max_sectors_store
  - block/blk-sysfs.c:queue_discard_max_store
  - block/blk-sysfs.c:queue_ra_store
  - block/blk-sysfs.c:queue_requests_store
  - lib/parser.c:match_u64
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
  - drivers/acpi/osl.c:setup_acpi_rsdp
  - drivers/acpi/sysfs.c:counter_set
  - drivers/xen/pcpu.c:online_store
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
  - drivers/base/core.c:device_store_ulong
  - drivers/base/memory.c:hard_offline_page_store
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:probe_store
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/nvdimm/core.c:nd_size_select_store
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:size_store
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/sd.c:max_write_same_blocks_store
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/rtc/sysfs.c:max_user_freq_store
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:max_sync_store
  - drivers/md/md.c:min_sync_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:ppl_sector_store
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:rdev_size_store
  - drivers/md/md.c:new_offset_store
  - drivers/md/md.c:offset_store
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
  - drivers/leds/led-class.c:brightness_store
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:energy_uj_store
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/ipv4/tcp.c:set_thash_entries
  - net/ipv4/udp.c:set_uhash_entries
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff8161f790-ffffffff8161f7a6: kstrtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kstrtoull(const char *s, unsigned int base, long long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff816edc90)
Location: lib/kstrtox.c:132
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
  - kernel/panic.c:panic_on_taint_setup
  - kernel/ksysfs.c:kexec_crash_size_store
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:sync_on_suspend_store
  - kernel/power/main.c:pm_async_store
  - kernel/power/hibernate.c:resume_offset_store
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/misc.c:misc_cg_max_write
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_trigger.c:event_trigger_parse_num
  - kernel/trace/trace_events_inject.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/backing-dev.c:read_ahead_kb_store
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_mempolicy_store
  - mm/hugetlb.c:nr_hugepages_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/slub.c:min_partial_store
  - mm/kfence/core.c:param_set_sample_interval
  - mm/huge_memory.c:use_zero_page_store
  - mm/khugepaged.c:khugepaged_max_ptes_shared_store
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - fs/libfs.c:simple_attr_write
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
  - security/apparmor/lsm.c:apparmor_enabled_setup
  - security/integrity/integrity_audit.c:integrity_audit_setup
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_stable_writes_store
  - block/blk-sysfs.c:queue_iostats_store
  - block/blk-sysfs.c:queue_random_store
  - block/blk-sysfs.c:queue_nonrot_store
  - block/blk-sysfs.c:queue_max_sectors_store
  - block/blk-sysfs.c:queue_discard_max_store
  - block/blk-sysfs.c:queue_ra_store
  - block/blk-sysfs.c:queue_requests_store
  - lib/parser.c:match_u64
  - lib/kstrtox.c:kstrtoull_from_user
  - lib/kstrtox.c:kstrtou8
  - lib/kstrtox.c:kstrtou16
  - lib/kstrtox.c:kstrtouint
  - lib/kstrtox.c:_kstrtoul
  - lib/kstrtox.c:kstrtoll
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
  - drivers/acpi/osl.c:setup_acpi_rsdp
  - drivers/acpi/sysfs.c:counter_set
  - drivers/xen/pcpu.c:online_store
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
  - drivers/base/core.c:device_store_ulong
  - drivers/base/memory.c:hard_offline_page_store
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:probe_store
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/nvdimm/core.c:nd_size_select_store
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:size_store
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/sd.c:max_write_same_blocks_store
  - drivers/rtc/sysfs.c:max_user_freq_store
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:max_sync_store
  - drivers/md/md.c:min_sync_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:ppl_sector_store
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:rdev_size_store
  - drivers/md/md.c:new_offset_store
  - drivers/md/md.c:offset_store
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
  - drivers/leds/led-class.c:brightness_store
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:energy_uj_store
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/core/net-sysfs.c:threaded_store
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:tx_queue_len_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:carrier_store
  - net/ipv4/tcp.c:set_thash_entries
  - net/ipv4/udp.c:set_uhash_entries
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff816edc90-ffffffff816edcb0: kstrtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kstrtoull(const char *s, unsigned int base, long long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff817de700)
Location: lib/kstrtox.c:132
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
  - kernel/panic.c:panic_on_taint_setup
  - kernel/ksysfs.c:kexec_crash_size_store
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:sync_on_suspend_store
  - kernel/power/main.c:pm_async_store
  - kernel/power/hibernate.c:resume_offset_store
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/misc.c:misc_cg_max_write
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_trigger.c:event_trigger_parse_num
  - kernel/trace/trace_events_inject.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/backing-dev.c:max_bytes_store
  - mm/backing-dev.c:min_bytes_store
  - mm/backing-dev.c:read_ahead_kb_store
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_mempolicy_store
  - mm/hugetlb.c:nr_hugepages_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/slub.c:min_partial_store
  - mm/kfence/core.c:param_set_sample_interval
  - mm/huge_memory.c:use_zero_page_store
  - mm/khugepaged.c:max_ptes_shared_store
  - mm/khugepaged.c:max_ptes_swap_store
  - mm/khugepaged.c:max_ptes_none_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/squashfs/super.c:squashfs_parse_param
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
  - security/apparmor/lsm.c:apparmor_enabled_setup
  - security/integrity/integrity_audit.c:integrity_audit_setup
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_stable_writes_store
  - block/blk-sysfs.c:queue_iostats_store
  - block/blk-sysfs.c:queue_random_store
  - block/blk-sysfs.c:queue_nonrot_store
  - block/blk-sysfs.c:queue_max_sectors_store
  - block/blk-sysfs.c:queue_discard_max_store
  - block/blk-sysfs.c:queue_ra_store
  - block/blk-sysfs.c:queue_requests_store
  - lib/parser.c:match_u64
  - lib/kstrtox.c:kstrtoull_from_user
  - lib/kstrtox.c:kstrtou8
  - lib/kstrtox.c:kstrtou16
  - lib/kstrtox.c:kstrtouint
  - lib/kstrtox.c:_kstrtoul
  - lib/kstrtox.c:kstrtoll
  - lib/dynamic_debug.c:param_set_dyndbg_classes
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
  - drivers/pci/pci-sysfs.c:resource5_resize_store
  - drivers/pci/pci-sysfs.c:resource4_resize_store
  - drivers/pci/pci-sysfs.c:resource3_resize_store
  - drivers/pci/pci-sysfs.c:resource2_resize_store
  - drivers/pci/pci-sysfs.c:resource1_resize_store
  - drivers/pci/pci-sysfs.c:resource0_resize_store
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
  - drivers/acpi/osl.c:setup_acpi_rsdp
  - drivers/acpi/utils.c:acpi_dev_uid_to_integer
  - drivers/acpi/sysfs.c:counter_set
  - drivers/xen/pcpu.c:online_store
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
  - drivers/base/core.c:device_store_ulong
  - drivers/base/memory.c:hard_offline_page_store
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:probe_store
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/nvdimm/core.c:nd_size_select_store
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:size_store
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/sd.c:max_write_same_blocks_store
  - drivers/rtc/sysfs.c:max_user_freq_store
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:max_sync_store
  - drivers/md/md.c:min_sync_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:ppl_sector_store
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:rdev_size_store
  - drivers/md/md.c:new_offset_store
  - drivers/md/md.c:offset_store
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
  - drivers/leds/led-class.c:brightness_store
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:energy_uj_store
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/core/net-sysfs.c:threaded_store
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:tx_queue_len_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:carrier_store
  - net/ipv4/tcp.c:set_thash_entries
  - net/ipv4/udp.c:set_uhash_entries
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff817de700-ffffffff817de720: kstrtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kstrtoull(const char *s, unsigned int base, long long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8181dee0)
Location: lib/kstrtox.c:132
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mon_config_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mon_config_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
  - kernel/panic.c:panic_on_taint_setup
  - kernel/ksysfs.c:kexec_crash_size_store
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:sync_on_suspend_store
  - kernel/power/main.c:pm_async_store
  - kernel/power/hibernate.c:resume_offset_store
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/misc.c:misc_cg_max_write
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_trigger.c:event_trigger_parse_num
  - kernel/trace/trace_events_inject.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/backing-dev.c:max_bytes_store
  - mm/backing-dev.c:min_bytes_store
  - mm/backing-dev.c:read_ahead_kb_store
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_mempolicy_store
  - mm/hugetlb.c:nr_hugepages_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/slub.c:min_partial_store
  - mm/kfence/core.c:param_set_sample_interval
  - mm/huge_memory.c:use_zero_page_store
  - mm/khugepaged.c:max_ptes_shared_store
  - mm/khugepaged.c:max_ptes_swap_store
  - mm/khugepaged.c:max_ptes_none_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/squashfs/super.c:squashfs_parse_param
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
  - security/apparmor/lsm.c:apparmor_enabled_setup
  - security/integrity/integrity_audit.c:integrity_audit_setup
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_stable_writes_store
  - block/blk-sysfs.c:queue_iostats_store
  - block/blk-sysfs.c:queue_random_store
  - block/blk-sysfs.c:queue_nonrot_store
  - block/blk-sysfs.c:queue_max_sectors_store
  - block/blk-sysfs.c:queue_discard_max_store
  - block/blk-sysfs.c:queue_ra_store
  - block/blk-sysfs.c:queue_requests_store
  - lib/parser.c:match_u64
  - lib/kstrtox.c:kstrtoull_from_user
  - lib/kstrtox.c:kstrtou8
  - lib/kstrtox.c:kstrtou16
  - lib/kstrtox.c:kstrtouint
  - lib/kstrtox.c:_kstrtoul
  - lib/kstrtox.c:kstrtoll
  - lib/dynamic_debug.c:param_set_dyndbg_classes
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
  - drivers/pci/pci-sysfs.c:resource5_resize_store
  - drivers/pci/pci-sysfs.c:resource4_resize_store
  - drivers/pci/pci-sysfs.c:resource3_resize_store
  - drivers/pci/pci-sysfs.c:resource2_resize_store
  - drivers/pci/pci-sysfs.c:resource1_resize_store
  - drivers/pci/pci-sysfs.c:resource0_resize_store
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
  - drivers/acpi/osl.c:setup_acpi_rsdp
  - drivers/acpi/utils.c:acpi_dev_uid_to_integer
  - drivers/acpi/sysfs.c:counter_set
  - drivers/xen/pcpu.c:online_store
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
  - drivers/base/core.c:device_store_ulong
  - drivers/base/memory.c:hard_offline_page_store
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:probe_store
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/nvdimm/core.c:nd_size_select_store
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:size_store
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/sd.c:max_write_same_blocks_store
  - drivers/rtc/sysfs.c:max_user_freq_store
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:max_sync_store
  - drivers/md/md.c:min_sync_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:ppl_sector_store
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:rdev_size_store
  - drivers/md/md.c:new_offset_store
  - drivers/md/md.c:offset_store
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/leds/led-class.c:brightness_store
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:energy_uj_store
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/core/net-sysfs.c:threaded_store
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:tx_queue_len_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:carrier_store
  - net/ipv4/tcp.c:set_thash_entries
  - net/ipv4/udp.c:set_uhash_entries
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff8181dee0-ffffffff8181df00: kstrtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kstrtoull(const char *s, unsigned int base, long long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81863d50)
Location: lib/kstrtox.c:132
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mon_config_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mon_config_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
  - kernel/panic.c:panic_on_taint_setup
  - kernel/ksysfs.c:kexec_crash_size_store
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:sync_on_suspend_store
  - kernel/power/main.c:pm_async_store
  - kernel/power/hibernate.c:resume_offset_store
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/misc.c:misc_cg_max_write
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_trigger.c:event_trigger_parse_num
  - kernel/trace/trace_events_inject.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/backing-dev.c:max_bytes_store
  - mm/backing-dev.c:min_bytes_store
  - mm/backing-dev.c:read_ahead_kb_store
  - mm/slub.c:min_partial_store
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_mempolicy_store
  - mm/hugetlb.c:nr_hugepages_store
  - mm/ksm.c:advisor_target_scan_time_store
  - mm/ksm.c:advisor_max_pages_to_scan_store
  - mm/ksm.c:advisor_min_pages_to_scan_store
  - mm/ksm.c:advisor_max_cpu_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/kfence/core.c:param_set_sample_interval
  - mm/huge_memory.c:use_zero_page_store
  - mm/khugepaged.c:max_ptes_shared_store
  - mm/khugepaged.c:max_ptes_swap_store
  - mm/khugepaged.c:max_ptes_none_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/squashfs/super.c:squashfs_parse_param
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
  - security/apparmor/lsm.c:apparmor_enabled_setup
  - security/integrity/integrity_audit.c:integrity_audit_setup
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_stable_writes_store
  - block/blk-sysfs.c:queue_iostats_store
  - block/blk-sysfs.c:queue_random_store
  - block/blk-sysfs.c:queue_nonrot_store
  - block/blk-sysfs.c:queue_max_sectors_store
  - block/blk-sysfs.c:queue_discard_max_store
  - block/blk-sysfs.c:queue_ra_store
  - block/blk-sysfs.c:queue_requests_store
  - lib/parser.c:match_u64
  - lib/kstrtox.c:kstrtoull_from_user
  - lib/kstrtox.c:kstrtou8
  - lib/kstrtox.c:kstrtou16
  - lib/kstrtox.c:kstrtouint
  - lib/kstrtox.c:_kstrtoul
  - lib/kstrtox.c:kstrtoll
  - lib/dynamic_debug.c:param_set_dyndbg_classes
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
  - drivers/pci/pci-sysfs.c:resource5_resize_store
  - drivers/pci/pci-sysfs.c:resource4_resize_store
  - drivers/pci/pci-sysfs.c:resource3_resize_store
  - drivers/pci/pci-sysfs.c:resource2_resize_store
  - drivers/pci/pci-sysfs.c:resource1_resize_store
  - drivers/pci/pci-sysfs.c:resource0_resize_store
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
  - drivers/acpi/osl.c:setup_acpi_rsdp
  - drivers/acpi/utils.c:acpi_dev_uid_to_integer
  - drivers/acpi/sysfs.c:counter_set
  - drivers/xen/pcpu.c:online_store
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
  - drivers/base/core.c:device_store_ulong
  - drivers/base/memory.c:hard_offline_page_store
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:probe_store
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/nvdimm/core.c:nd_size_select_store
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:size_store
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/sd.c:max_write_same_blocks_store
  - drivers/rtc/sysfs.c:max_user_freq_store
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:max_sync_store
  - drivers/md/md.c:min_sync_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:ppl_sector_store
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:rdev_size_store
  - drivers/md/md.c:new_offset_store
  - drivers/md/md.c:offset_store
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/leds/led-class.c:brightness_store
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:energy_uj_store
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/core/net-sysfs.c:threaded_store
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:tx_queue_len_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:carrier_store
  - net/ipv4/tcp.c:set_thash_entries
  - net/ipv4/udp.c:set_uhash_entries
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff81863d50-ffffffff81863d70: kstrtoull (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int kstrtoull(const char *s, unsigned int base, long long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffff80001063a44c)
Location: lib/kstrtox.c:121
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
  - lib/kstrtox.c:kstrtoull_from_user
  - lib/kstrtox.c:kstrtou8
  - lib/kstrtox.c:kstrtou16
  - lib/kstrtox.c:kstrtouint
  - lib/kstrtox.c:_kstrtoul
Direct callers:
  - kernel/params.c:param_set_ulong
  - kernel/ksysfs.c:kexec_crash_size_store
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:pm_async_store
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - mm/backing-dev.c:read_ahead_kb_store
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store_common
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
  - mm/slub.c:min_partial_store
  - mm/huge_memory.c:single_hugepage_flag_store
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
  - fs/fs_parser.c:fs_parse
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
  - security/apparmor/lsm.c:apparmor_enabled_setup
  - security/integrity/integrity_audit.c:integrity_audit_setup
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-sysfs.c:queue_max_sectors_store
  - block/blk-sysfs.c:queue_discard_max_store
  - block/blk-sysfs.c:queue_ra_store
  - block/blk-sysfs.c:queue_requests_store
  - lib/parser.c:match_u64
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
  - drivers/pci/msi.c:msi_mode_show
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
  - drivers/acpi/osl.c:setup_acpi_rsdp
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
  - drivers/base/core.c:device_store_ulong
  - drivers/base/memory.c:hard_offline_page_store
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/nvdimm/core.c:nd_size_select_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/sd.c:max_write_same_blocks_store
  - drivers/rtc/sysfs.c:max_user_freq_store
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:max_sync_store
  - drivers/md/md.c:min_sync_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:ppl_sector_store
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:strict_blocks_to_sectors
  - drivers/md/md.c:new_offset_store
  - drivers/md/md.c:offset_store
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
  - drivers/md/dm-init.c:dm_init_init
  - drivers/md/dm-init.c:dm_init_init
  - drivers/md/dm-init.c:dm_init_init
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
  - drivers/cpuidle/sysfs.c:store_state_disable
  - drivers/leds/led-class.c:brightness_store
  - drivers/memory/brcmstb_dpfe.c:store_refresh
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:energy_uj_store
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_cmp_mask_store
  - drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_probe_cluster
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/ipv4/tcp.c:set_thash_entries
  - net/ipv4/udp.c:set_uhash_entries
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffff800010639f08-ffff800010639f28: kstrtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int kstrtoull(const char *s, unsigned int base, long long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (c07dff68)
Location: lib/kstrtox.c:121
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoull_from_user
  - lib/kstrtox.c:kstrtou8
  - lib/kstrtox.c:kstrtou16
  - lib/kstrtox.c:kstrtouint
  - lib/kstrtox.c:_kstrtoul
Direct callers:
  - kernel/params.c:param_set_ullong
  - kernel/power/hibernate.c:resume_offset_store
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:parse_pred
  - fs/fs_parser.c:fs_parse
  - fs/ext4/sysfs.c:ext4_attr_store
  - lib/parser.c:match_u64
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:max_sync_store
  - drivers/md/md.c:min_sync_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:ppl_sector_store
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:strict_blocks_to_sectors
  - drivers/md/md.c:new_offset_store
  - drivers/md/md.c:offset_store
  - drivers/md/dm-init.c:dm_init_init
  - drivers/md/dm-init.c:dm_init_init
  - drivers/md/dm-init.c:dm_init_init
  - drivers/cpuidle/sysfs.c:store_state_disable
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:energy_uj_store
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_cmp_mask_store
```
**Symbols:**

```
c07df8bc-c07df8dc: kstrtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int kstrtoull(const char *s, unsigned int base, long long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (c0000000007e121c)
Location: lib/kstrtox.c:121
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
  - lib/kstrtox.c:kstrtoull_from_user
  - lib/kstrtox.c:kstrtou8
  - lib/kstrtox.c:kstrtou16
  - lib/kstrtox.c:kstrtouint
  - lib/kstrtox.c:_kstrtoul
Direct callers:
  - arch/powerpc/platforms/pseries/mobility.c:migration_store
  - arch/powerpc/platforms/pseries/vio.c:cmo_desired_store
  - arch/powerpc/kvm/book3s_hv_builtin.c:early_parse_kvm_cma_resv
  - kernel/params.c:param_set_ullong
  - kernel/params.c:param_set_ulong
  - kernel/ksysfs.c:kexec_crash_size_store
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:pm_async_store
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - mm/backing-dev.c:read_ahead_kb_store
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store_common
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
  - mm/slub.c:min_partial_store
  - mm/huge_memory.c:single_hugepage_flag_store
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
  - fs/fs_parser.c:fs_parse
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
  - security/apparmor/lsm.c:apparmor_enabled_setup
  - security/integrity/integrity_audit.c:integrity_audit_setup
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-sysfs.c:queue_max_sectors_store
  - block/blk-sysfs.c:queue_discard_max_store
  - block/blk-sysfs.c:queue_ra_store
  - block/blk-sysfs.c:queue_requests_store
  - lib/parser.c:match_u64
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
  - drivers/pci/msi.c:msi_mode_show
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
  - drivers/base/core.c:device_store_ulong
  - drivers/base/memory.c:hard_offline_page_store
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:probe_store
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/nvdimm/core.c:nd_size_select_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/sd.c:max_write_same_blocks_store
  - drivers/rtc/sysfs.c:max_user_freq_store
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:max_sync_store
  - drivers/md/md.c:min_sync_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:ppl_sector_store
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:strict_blocks_to_sectors
  - drivers/md/md.c:new_offset_store
  - drivers/md/md.c:offset_store
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
  - drivers/cpuidle/sysfs.c:store_state_disable
  - drivers/leds/led-class.c:brightness_store
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:energy_uj_store
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/ipv4/tcp.c:set_thash_entries
  - net/ipv4/udp.c:set_uhash_entries
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
c0000000007e0b70-c0000000007e0b90: kstrtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int kstrtoull(const char *s, unsigned int base, long long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffe000466b4c)
Location: lib/kstrtox.c:121
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
  - lib/kstrtox.c:kstrtoull_from_user
  - lib/kstrtox.c:kstrtou8
  - lib/kstrtox.c:kstrtou16
  - lib/kstrtox.c:kstrtouint
  - lib/kstrtox.c:_kstrtoul
Direct callers:
  - kernel/params.c:param_set_ulong
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - mm/backing-dev.c:read_ahead_kb_store
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
  - mm/slub.c:min_partial_store
  - fs/fs_parser.c:fs_parse
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
  - security/apparmor/lsm.c:apparmor_enabled_setup
  - security/integrity/integrity_audit.c:integrity_audit_setup
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-sysfs.c:queue_max_sectors_store
  - block/blk-sysfs.c:queue_discard_max_store
  - block/blk-sysfs.c:queue_ra_store
  - block/blk-sysfs.c:queue_requests_store
  - lib/parser.c:match_u64
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
  - drivers/pci/msi.c:msi_mode_show
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
  - drivers/base/core.c:device_store_ulong
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/nvdimm/core.c:nd_size_select_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/sd.c:max_write_same_blocks_store
  - drivers/rtc/sysfs.c:max_user_freq_store
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:max_sync_store
  - drivers/md/md.c:min_sync_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:ppl_sector_store
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:strict_blocks_to_sectors
  - drivers/md/md.c:new_offset_store
  - drivers/md/md.c:offset_store
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
  - drivers/leds/led-class.c:brightness_store
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:energy_uj_store
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/ipv4/tcp.c:set_thash_entries
  - net/ipv4/udp.c:set_uhash_entries
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffe0004667d4-ffffffe0004667fa: kstrtoull (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int kstrtoull(const char *s, unsigned int base, long long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8152659b)
Location: lib/kstrtox.c:121
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
  - lib/kstrtox.c:kstrtoull_from_user
  - lib/kstrtox.c:kstrtou8
  - lib/kstrtox.c:kstrtou16
  - lib/kstrtox.c:kstrtouint
  - lib/kstrtox.c:_kstrtoul
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
  - arch/x86/kernel/pci-calgary_64.c:calgary_parse_options
  - kernel/params.c:param_set_ullong
  - kernel/params.c:param_set_ulong
  - kernel/ksysfs.c:kexec_crash_size_store
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:pm_async_store
  - kernel/power/hibernate.c:resume_offset_store
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - mm/backing-dev.c:read_ahead_kb_store
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store_common
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
  - mm/slub.c:min_partial_store
  - mm/huge_memory.c:single_hugepage_flag_store
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
  - fs/fs_parser.c:fs_parse
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
  - security/apparmor/lsm.c:apparmor_enabled_setup
  - security/integrity/integrity_audit.c:integrity_audit_setup
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-sysfs.c:queue_max_sectors_store
  - block/blk-sysfs.c:queue_discard_max_store
  - block/blk-sysfs.c:queue_ra_store
  - block/blk-sysfs.c:queue_requests_store
  - lib/parser.c:match_u64
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
  - drivers/pci/msi.c:msi_mode_show
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
  - drivers/acpi/osl.c:setup_acpi_rsdp
  - drivers/acpi/sysfs.c:counter_set
  - drivers/xen/pcpu.c:store_online
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
  - drivers/base/core.c:device_store_ulong
  - drivers/base/memory.c:hard_offline_page_store
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:probe_store
  - drivers/nvdimm/core.c:nd_size_select_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/sd.c:max_write_same_blocks_store
  - drivers/rtc/sysfs.c:max_user_freq_store
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:max_sync_store
  - drivers/md/md.c:min_sync_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:ppl_sector_store
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:strict_blocks_to_sectors
  - drivers/md/md.c:new_offset_store
  - drivers/md/md.c:offset_store
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
  - drivers/cpuidle/sysfs.c:store_state_disable
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/ipv4/tcp.c:set_thash_entries
  - net/ipv4/udp.c:set_uhash_entries
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff815260f0-ffffffff81526106: kstrtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int kstrtoull(const char *s, unsigned int base, long long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8151687b)
Location: lib/kstrtox.c:121
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
  - lib/kstrtox.c:kstrtoull_from_user
  - lib/kstrtox.c:kstrtou8
  - lib/kstrtox.c:kstrtou16
  - lib/kstrtox.c:kstrtouint
  - lib/kstrtox.c:_kstrtoul
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
  - arch/x86/kernel/pci-calgary_64.c:calgary_parse_options
  - kernel/params.c:param_set_ullong
  - kernel/params.c:param_set_ulong
  - kernel/ksysfs.c:kexec_crash_size_store
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:pm_async_store
  - kernel/power/hibernate.c:resume_offset_store
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - mm/backing-dev.c:read_ahead_kb_store
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store_common
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
  - mm/slub.c:min_partial_store
  - mm/huge_memory.c:single_hugepage_flag_store
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
  - fs/fs_parser.c:fs_parse
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
  - security/apparmor/lsm.c:apparmor_enabled_setup
  - security/integrity/integrity_audit.c:integrity_audit_setup
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-sysfs.c:queue_max_sectors_store
  - block/blk-sysfs.c:queue_discard_max_store
  - block/blk-sysfs.c:queue_ra_store
  - block/blk-sysfs.c:queue_requests_store
  - lib/parser.c:match_u64
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
  - drivers/pci/msi.c:msi_mode_show
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
  - drivers/acpi/osl.c:setup_acpi_rsdp
  - drivers/acpi/sysfs.c:counter_set
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
  - drivers/base/core.c:device_store_ulong
  - drivers/base/memory.c:hard_offline_page_store
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:probe_store
  - drivers/nvdimm/core.c:nd_size_select_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/sd.c:max_write_same_blocks_store
  - drivers/rtc/sysfs.c:max_user_freq_store
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:max_sync_store
  - drivers/md/md.c:min_sync_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:ppl_sector_store
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:strict_blocks_to_sectors
  - drivers/md/md.c:new_offset_store
  - drivers/md/md.c:offset_store
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
  - drivers/cpuidle/sysfs.c:store_state_disable
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/ipv4/tcp.c:set_thash_entries
  - net/ipv4/udp.c:set_uhash_entries
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff815163d0-ffffffff815163e6: kstrtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int kstrtoull(const char *s, unsigned int base, long long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8152262b)
Location: lib/kstrtox.c:121
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
  - lib/kstrtox.c:kstrtoull_from_user
  - lib/kstrtox.c:kstrtou8
  - lib/kstrtox.c:kstrtou16
  - lib/kstrtox.c:kstrtouint
  - lib/kstrtox.c:_kstrtoul
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
  - arch/x86/kernel/pci-calgary_64.c:calgary_parse_options
  - kernel/params.c:param_set_ullong
  - kernel/params.c:param_set_ulong
  - kernel/ksysfs.c:kexec_crash_size_store
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:pm_async_store
  - kernel/power/hibernate.c:resume_offset_store
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - mm/backing-dev.c:read_ahead_kb_store
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store_common
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
  - mm/slub.c:min_partial_store
  - mm/huge_memory.c:single_hugepage_flag_store
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
  - fs/fs_parser.c:fs_parse
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
  - security/apparmor/lsm.c:apparmor_enabled_setup
  - security/integrity/integrity_audit.c:integrity_audit_setup
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-sysfs.c:queue_max_sectors_store
  - block/blk-sysfs.c:queue_discard_max_store
  - block/blk-sysfs.c:queue_ra_store
  - block/blk-sysfs.c:queue_requests_store
  - lib/parser.c:match_u64
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
  - drivers/pci/msi.c:msi_mode_show
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
  - drivers/acpi/osl.c:setup_acpi_rsdp
  - drivers/acpi/sysfs.c:counter_set
  - drivers/xen/pcpu.c:store_online
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
  - drivers/base/core.c:device_store_ulong
  - drivers/base/memory.c:hard_offline_page_store
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:probe_store
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/nvdimm/core.c:nd_size_select_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/sd.c:max_write_same_blocks_store
  - drivers/rtc/sysfs.c:max_user_freq_store
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:max_sync_store
  - drivers/md/md.c:min_sync_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:ppl_sector_store
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:strict_blocks_to_sectors
  - drivers/md/md.c:new_offset_store
  - drivers/md/md.c:offset_store
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
  - drivers/cpuidle/sysfs.c:store_state_disable
  - drivers/leds/led-class.c:brightness_store
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:energy_uj_store
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/ipv4/tcp.c:set_thash_entries
  - net/ipv4/udp.c:set_uhash_entries
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff81522180-ffffffff81522196: kstrtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int kstrtoull(const char *s, unsigned int base, long long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8153bfab)
Location: lib/kstrtox.c:121
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
  - lib/kstrtox.c:kstrtoull_from_user
  - lib/kstrtox.c:kstrtou8
  - lib/kstrtox.c:kstrtou16
  - lib/kstrtox.c:kstrtouint
  - lib/kstrtox.c:_kstrtoul
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
  - arch/x86/kernel/pci-calgary_64.c:calgary_parse_options
  - kernel/params.c:param_set_ullong
  - kernel/params.c:param_set_ulong
  - kernel/ksysfs.c:kexec_crash_size_store
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:pm_async_store
  - kernel/power/hibernate.c:resume_offset_store
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - mm/backing-dev.c:read_ahead_kb_store
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store_common
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
  - mm/slub.c:min_partial_store
  - mm/huge_memory.c:single_hugepage_flag_store
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
  - fs/fs_parser.c:fs_parse
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
  - security/apparmor/lsm.c:apparmor_enabled_setup
  - security/integrity/integrity_audit.c:integrity_audit_setup
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-sysfs.c:queue_max_sectors_store
  - block/blk-sysfs.c:queue_discard_max_store
  - block/blk-sysfs.c:queue_ra_store
  - block/blk-sysfs.c:queue_requests_store
  - lib/parser.c:match_u64
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
  - drivers/pci/msi.c:msi_mode_show
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
  - drivers/acpi/osl.c:setup_acpi_rsdp
  - drivers/acpi/sysfs.c:counter_set
  - drivers/xen/pcpu.c:store_online
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
  - drivers/base/core.c:device_store_ulong
  - drivers/base/memory.c:hard_offline_page_store
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:probe_store
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/nvdimm/core.c:nd_size_select_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/sd.c:max_write_same_blocks_store
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/rtc/sysfs.c:max_user_freq_store
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:max_sync_store
  - drivers/md/md.c:min_sync_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:ppl_sector_store
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:strict_blocks_to_sectors
  - drivers/md/md.c:new_offset_store
  - drivers/md/md.c:offset_store
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
  - drivers/cpuidle/sysfs.c:store_state_disable
  - drivers/leds/led-class.c:brightness_store
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:energy_uj_store
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/ipv4/tcp.c:set_thash_entries
  - net/ipv4/udp.c:set_uhash_entries
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff8153bb00-ffffffff8153bb16: kstrtoull (STB_GLOBAL)
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
