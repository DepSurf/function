# Function: <code>kstrtoul</code>

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
In arch/x86/events/core.c (ffffffff81005599)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - arch/x86/events/core.c:set_attr_rdpmc
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81f65b50)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:kstack_setup
  - arch/x86/kernel/dumpstack.c:code_bytes_setup
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103e904)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81047fdb)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_interrupt_enable
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_threshold_limit
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104c889)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
```
```
In arch/x86/kernel/early_printk.c (ffffffff81f73d78)
Location: include/linux/kernel.h:290
Inline: True
```
```
In arch/x86/kernel/check.c (ffffffff81f74a98)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:set_corruption_check
  - arch/x86/kernel/check.c:set_corruption_check_period
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81f7637e)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_parse_options
```
```
In kernel/params.c (0)
Location: include/linux/kernel.h:290
Inline: True
```
```
In kernel/ksysfs.c (ffffffff810a1db9)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - kernel/ksysfs.c:kexec_crash_size_store
```
```
In kernel/power/main.c (ffffffff810cceb9)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:pm_async_store
```
```
In kernel/livepatch/core.c (ffffffff810e93f6)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - kernel/livepatch/core.c:enabled_store
```
```
In kernel/trace/trace.c (ffffffff81f83985)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
```
```
In kernel/trace/trace_functions.c (ffffffff81156dc6)
Location: include/linux/kernel.h:290
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff8115f366)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:event_enable_func
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81166777)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
```
```
In kernel/trace/trace_kprobe.c (ffffffff81168f12)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff8116d716)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
```
```
In kernel/trace/trace_uprobe.c (ffffffff811704d1)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
```
In mm/backing-dev.c (ffffffff811ae089)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - mm/backing-dev.c:read_ahead_kb_store
```
```
In mm/hugetlb.c (ffffffff811da654)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store_common
```
```
In mm/ksm.c (ffffffff811e4329)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/ksm.c:run_store
```
```
In mm/slub.c (ffffffff811e78af)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - mm/slub.c:remote_node_defrag_ratio_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:min_partial_store
  - mm/slub.c:order_store
```
```
In mm/huge_memory.c (ffffffff811f3959)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - mm/huge_memory.c:alloc_sleep_millisecs_store
  - mm/huge_memory.c:scan_sleep_millisecs_store
  - mm/huge_memory.c:pages_to_scan_store
  - mm/huge_memory.c:khugepaged_max_ptes_none_store
```
```
In fs/ext4/sysfs.c (ffffffff812e381e)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In security/keys/trusted.c (ffffffff81336c89)
Location: include/linux/kernel.h:290
Inline: True
```
```
In security/selinux/hooks.c (ffffffff81f984d9)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - security/selinux/hooks.c:enforcing_setup
  - security/selinux/hooks.c:selinux_enabled_setup
```
```
In security/selinux/selinuxfs.c (ffffffff81f98725)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:checkreqprot_setup
```
```
In security/apparmor/lsm.c (ffffffff81f994d3)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_enabled_setup
```
```
In security/integrity/integrity_audit.c (ffffffff81f99a48)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_setup
```
```
In security/integrity/ima/ima_policy.c (ffffffff813992ca)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/blk-sysfs.c (ffffffff813bc39f)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
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
```
```
In lib/kstrtox.c (ffffffff81402162)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
```
```
In drivers/pci/pci-sysfs.c (ffffffff8143b0a9)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:dev_bus_rescan_store
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:remove_store
```
```
In drivers/pci/msi.c (ffffffff81453979)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
```
```
In drivers/video/backlight/backlight.c (ffffffff8146b946)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:bl_power_store
  - drivers/video/backlight/backlight.c:brightness_store
```
```
In drivers/acpi/osl.c (ffffffff81fa0fff)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - drivers/acpi/osl.c:setup_acpi_rsdp
```
```
In drivers/acpi/sysfs.c (ffffffff81489fce)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:counter_set
```
```
In drivers/xen/xen-selfballoon.c (ffffffff814d2cba)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - drivers/xen/xen-selfballoon.c:store_frontswap_inertia
  - drivers/xen/xen-selfballoon.c:store_frontswap_hysteresis
  - drivers/xen/xen-selfballoon.c:store_selfballoon_reserved_mb
  - drivers/xen/xen-selfballoon.c:store_selfballoon_min_usable_mb
  - drivers/xen/xen-selfballoon.c:store_selfballoon_uphys
  - drivers/xen/xen-selfballoon.c:store_selfballoon_downhys
  - drivers/xen/xen-selfballoon.c:store_selfballoon_interval
  - drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking
  - drivers/xen/xen-selfballoon.c:store_selfballooning
```
```
In drivers/tty/sysrq.c (ffffffff814edabd)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
```
```
In drivers/misc/bmp085.c (ffffffff81578f69)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - drivers/misc/bmp085.c:set_oversampling
```
```
In drivers/mfd/aat2870-core.c (ffffffff81594545)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
```
```
In drivers/nvdimm/core.c (ffffffff815973f6)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nd_sector_size_store
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff815b4b02)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/scsi/sd.c (ffffffff815ba07f)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - drivers/scsi/sd.c:max_write_same_blocks_store
```
```
In drivers/thermal/thermal_core.c (ffffffff81684834)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:trip_point_temp_store
  - drivers/thermal/thermal_core.c:emul_temp_store
```
```
In drivers/md/md.c (ffffffff8168e2ff)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - drivers/md/md.c:chunk_size_store
```
```
In drivers/md/bitmap.c (ffffffff8169beaf)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - drivers/md/bitmap.c:backlog_store
  - drivers/md/bitmap.c:space_store
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff816b62b1)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
```
```
In drivers/leds/led-class.c (ffffffff816cdfd1)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - drivers/leds/led-class.c:brightness_store
```
```
In net/core/net-sysfs.c (ffffffff81735ca3)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
```
```
In net/ipv4/tcp.c (ffffffff81fbcb5f)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - net/ipv4/tcp.c:set_thash_entries
```
```
In net/ipv4/udp.c (ffffffff81fbcf8b)
Location: include/linux/kernel.h:290
Inline: True
```
```
In net/rfkill/core.c (ffffffff81811b9f)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - net/rfkill/core.c:soft_store
  - net/rfkill/core.c:state_store
```
```
In net/dns_resolver/dns_key.c (ffffffff81816815)
Location: include/linux/kernel.h:290
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
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
In arch/x86/events/core.c (ffffffff81005739)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - arch/x86/events/core.c:set_attr_rdpmc
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81f8da0f)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:code_bytes_setup
  - arch/x86/kernel/dumpstack.c:kstack_setup
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103e734)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104820f)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_interrupt_enable
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104c909)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
```
```
In arch/x86/kernel/early_printk.c (ffffffff81f9c5a3)
Location: include/linux/kernel.h:297
Inline: True
```
```
In arch/x86/kernel/check.c (ffffffff81f9d268)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81f9eada)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_parse_options
```
```
In kernel/params.c (0)
Location: include/linux/kernel.h:297
Inline: True
```
```
In kernel/ksysfs.c (ffffffff810a5539)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - kernel/ksysfs.c:kexec_crash_size_store
```
```
In kernel/power/main.c (ffffffff810d1959)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:pm_async_store
```
```
In kernel/livepatch/core.c (ffffffff810f0036)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - kernel/livepatch/core.c:enabled_store
```
```
In kernel/trace/trace.c (ffffffff8115516c)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
```
```
In kernel/trace/trace_functions.c (ffffffff81161645)
Location: include/linux/kernel.h:297
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff8116b9f5)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81170e79)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_events_hist.c (ffffffff81173cac)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
```
In kernel/trace/trace_kprobe.c (ffffffff811765d2)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff8117b359)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - kernel/trace/trace_probe.c:find_fetch_type
```
```
In kernel/trace/trace_uprobe.c (ffffffff8117dbf3)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
```
In kernel/events/core.c (ffffffff8118bcba)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_addr_filter
  - kernel/events/core.c:perf_event_set_addr_filter
```
```
In mm/backing-dev.c (ffffffff811c74b9)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - mm/backing-dev.c:read_ahead_kb_store
```
```
In mm/hugetlb.c (ffffffff811f86ae)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store_common
```
```
In mm/ksm.c (ffffffff81203869)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - mm/ksm.c:merge_across_nodes_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
```
```
In mm/slub.c (ffffffff81206b1f)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - mm/slub.c:remote_node_defrag_ratio_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:min_partial_store
  - mm/slub.c:order_store
```
```
In mm/huge_memory.c (ffffffff81214129)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - mm/huge_memory.c:single_hugepage_flag_store
```
```
In mm/khugepaged.c (ffffffff812190b9)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
```
```
In fs/ext4/sysfs.c (ffffffff813137ee)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In security/keys/trusted.c (ffffffff8136c19e)
Location: include/linux/kernel.h:297
Inline: True
```
```
In security/selinux/hooks.c (ffffffff81fc31be)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
```
```
In security/selinux/selinuxfs.c (ffffffff81fc33bd)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:checkreqprot_setup
```
```
In security/apparmor/lsm.c (ffffffff81fc4246)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_enabled_setup
```
```
In security/integrity/integrity_audit.c (ffffffff81fc47bd)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_setup
```
```
In security/integrity/ima/ima_policy.c (ffffffff813d578b)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/blk-sysfs.c (ffffffff81400faa)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
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
```
```
In lib/kstrtox.c (ffffffff81449d25)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
```
```
In drivers/pci/pci-sysfs.c (ffffffff81488016)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:dev_bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
```
```
In drivers/pci/msi.c (ffffffff814a0289)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
```
```
In drivers/video/backlight/backlight.c (ffffffff814b9c36)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
```
```
In drivers/acpi/osl.c (ffffffff81fcd0cf)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - drivers/acpi/osl.c:setup_acpi_rsdp
```
```
In drivers/acpi/sysfs.c (ffffffff814d8d7e)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:counter_set
```
```
In drivers/xen/xen-selfballoon.c (ffffffff81523a7a)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - drivers/xen/xen-selfballoon.c:store_frontswap_hysteresis
  - drivers/xen/xen-selfballoon.c:store_frontswap_inertia
  - drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking
  - drivers/xen/xen-selfballoon.c:store_selfballoon_reserved_mb
  - drivers/xen/xen-selfballoon.c:store_selfballoon_min_usable_mb
  - drivers/xen/xen-selfballoon.c:store_selfballoon_uphys
  - drivers/xen/xen-selfballoon.c:store_selfballoon_downhys
  - drivers/xen/xen-selfballoon.c:store_selfballoon_interval
  - drivers/xen/xen-selfballoon.c:store_selfballooning
```
```
In drivers/tty/sysrq.c (ffffffff8153e73d)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
```
```
In drivers/mfd/aat2870-core.c (ffffffff815e93e8)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
```
```
In drivers/nvdimm/core.c (ffffffff815ec5c6)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nd_sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff815f8b6b)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:align_store
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8160c792)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/scsi/sd.c (ffffffff816127cf)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - drivers/scsi/sd.c:max_write_same_blocks_store
```
```
In drivers/rtc/rtc-sysfs.c (ffffffff816d6de5)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
  - drivers/rtc/rtc-sysfs.c:max_user_freq_store
```
```
In drivers/md/md.c (ffffffff816ef83f)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - drivers/md/md.c:chunk_size_store
```
```
In drivers/md/bitmap.c (ffffffff816fcfdf)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - drivers/md/bitmap.c:backlog_store
  - drivers/md/bitmap.c:space_store
```
```
In drivers/leds/led-class.c (ffffffff817310a1)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - drivers/leds/led-class.c:brightness_store
```
```
In net/core/net-sysfs.c (ffffffff817a1e53)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
```
```
In net/ipv4/tcp.c (ffffffff81fea9c2)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - net/ipv4/tcp.c:set_thash_entries
```
```
In net/ipv4/udp.c (ffffffff81feadee)
Location: include/linux/kernel.h:297
Inline: True
```
```
In net/rfkill/core.c (ffffffff81884caf)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
```
```
In net/dns_resolver/dns_key.c (ffffffff818896d5)
Location: include/linux/kernel.h:297
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
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
In arch/x86/events/core.c (ffffffff81005769)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - arch/x86/events/core.c:set_attr_rdpmc
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81fc8dd3)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:code_bytes_setup
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103e0a6)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/intel_rdt_schemata.c (ffffffff81044b98)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_write
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104a3cf)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_interrupt_enable
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104edf9)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
```
```
In arch/x86/kernel/early_printk.c (ffffffff81fd7aee)
Location: include/linux/kernel.h:299
Inline: True
```
```
In arch/x86/kernel/check.c (ffffffff81fd87f7)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81fda05d)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_parse_options
```
```
In kernel/params.c (0)
Location: include/linux/kernel.h:299
Inline: True
```
```
In kernel/ksysfs.c (ffffffff810ab199)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - kernel/ksysfs.c:kexec_crash_size_store
```
```
In kernel/power/main.c (ffffffff810d83b9)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:pm_async_store
```
```
In kernel/livepatch/core.c (ffffffff810f6be6)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - kernel/livepatch/core.c:enabled_store
```
```
In kernel/trace/trace.c (ffffffff8115f5fc)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
```
```
In kernel/trace/trace_functions.c (ffffffff8116c0a5)
Location: include/linux/kernel.h:299
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff81176ce5)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8117c5e9)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_events_hist.c (ffffffff8117d734)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_map_size
```
```
In kernel/trace/trace_kprobe.c (ffffffff81182061)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff81186f69)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - kernel/trace/trace_probe.c:find_fetch_type
```
```
In kernel/trace/trace_uprobe.c (ffffffff811897ec)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
```
In kernel/events/core.c (ffffffff8119b18a)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_addr_filter
  - kernel/events/core.c:perf_event_set_addr_filter
```
```
In mm/backing-dev.c (ffffffff811d75d9)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - mm/backing-dev.c:read_ahead_kb_store
```
```
In mm/hugetlb.c (ffffffff8120905e)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store_common
```
```
In mm/ksm.c (ffffffff81215889)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - mm/ksm.c:merge_across_nodes_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
```
```
In mm/slub.c (ffffffff81218b3f)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - mm/slub.c:remote_node_defrag_ratio_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:min_partial_store
  - mm/slub.c:order_store
```
```
In mm/huge_memory.c (ffffffff81226569)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - mm/huge_memory.c:single_hugepage_flag_store
```
```
In mm/khugepaged.c (ffffffff8122b639)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
```
```
In fs/ext4/sysfs.c (ffffffff8132978e)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In security/keys/trusted.c (ffffffff813829be)
Location: include/linux/kernel.h:299
Inline: True
```
```
In security/selinux/hooks.c (ffffffff81fffc0a)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
```
```
In security/selinux/selinuxfs.c (ffffffff81fffe09)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:checkreqprot_setup
```
```
In security/apparmor/lsm.c (ffffffff82000c75)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_enabled_setup
```
```
In security/integrity/integrity_audit.c (ffffffff820011f4)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_setup
```
```
In security/integrity/ima/ima_policy.c (ffffffff813ed05b)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/blk-sysfs.c (ffffffff8141abda)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
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
```
```
In lib/kstrtox.c (ffffffff814686e5)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
```
```
In drivers/pci/pci-sysfs.c (ffffffff814a97f6)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:dev_bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
```
```
In drivers/pci/msi.c (ffffffff814c1e09)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
```
```
In drivers/video/backlight/backlight.c (ffffffff814dbc36)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
```
```
In drivers/acpi/osl.c (ffffffff8200a0c9)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - drivers/acpi/osl.c:setup_acpi_rsdp
```
```
In drivers/acpi/sysfs.c (ffffffff814fb50e)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:counter_set
```
```
In drivers/xen/xen-selfballoon.c (ffffffff8154ff3a)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - drivers/xen/xen-selfballoon.c:store_frontswap_hysteresis
  - drivers/xen/xen-selfballoon.c:store_frontswap_inertia
  - drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking
  - drivers/xen/xen-selfballoon.c:store_selfballoon_reserved_mb
  - drivers/xen/xen-selfballoon.c:store_selfballoon_min_usable_mb
  - drivers/xen/xen-selfballoon.c:store_selfballoon_uphys
  - drivers/xen/xen-selfballoon.c:store_selfballoon_downhys
  - drivers/xen/xen-selfballoon.c:store_selfballoon_interval
  - drivers/xen/xen-selfballoon.c:store_selfballooning
```
```
In drivers/tty/sysrq.c (ffffffff8156ad8d)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
```
```
In drivers/mfd/aat2870-core.c (ffffffff816161f8)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
```
```
In drivers/nvdimm/core.c (ffffffff816193a6)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nd_sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81626deb)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:align_store
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8163c032)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/scsi/sd.c (ffffffff81641fda)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - drivers/scsi/sd.c:max_write_same_blocks_store
```
```
In drivers/rtc/rtc-sysfs.c (ffffffff81706ac5)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
  - drivers/rtc/rtc-sysfs.c:max_user_freq_store
```
```
In drivers/md/md.c (ffffffff81720c1f)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - drivers/md/md.c:chunk_size_store
```
```
In drivers/md/bitmap.c (ffffffff8172ebaf)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - drivers/md/bitmap.c:backlog_store
  - drivers/md/bitmap.c:space_store
```
```
In drivers/leds/led-class.c (ffffffff81764031)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - drivers/leds/led-class.c:brightness_store
```
```
In net/core/net-sysfs.c (ffffffff817d0773)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
```
```
In net/ipv4/tcp.c (ffffffff82029275)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - net/ipv4/tcp.c:set_thash_entries
```
```
In net/ipv4/udp.c (ffffffff8202966e)
Location: include/linux/kernel.h:299
Inline: True
```
```
In net/rfkill/core.c (ffffffff818b951f)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
```
```
In net/dns_resolver/dns_key.c (ffffffff818bdee5)
Location: include/linux/kernel.h:299
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
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
In arch/x86/events/core.c (ffffffff81005579)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - arch/x86/events/core.c:set_attr_rdpmc
```
```
In arch/x86/events/intel/core.c (ffffffff8100ac49)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/kernel/dumpstack.c (ffffffff820a94dc)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:code_bytes_setup
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103c0ae)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c (ffffffff81044c93)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_bw
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81049d8f)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_interrupt_enable
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104f0d9)
Location: include/linux/kernel.h:312
Inline: True
```
```
In arch/x86/kernel/early_printk.c (ffffffff820b891d)
Location: include/linux/kernel.h:312
Inline: True
```
```
In arch/x86/kernel/check.c (ffffffff820b9627)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff820baed2)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_parse_options
```
```
In kernel/params.c (ffffffff810a4576)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - kernel/params.c:param_set_ulong
```
```
In kernel/ksysfs.c (ffffffff810a7d59)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - kernel/ksysfs.c:kexec_crash_size_store
```
```
In kernel/power/main.c (ffffffff810d73c9)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:pm_async_store
```
```
In kernel/trace/trace.c (ffffffff81162b13)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:trace_pid_write
```
```
In kernel/trace/trace_functions.c (ffffffff8116f1d4)
Location: include/linux/kernel.h:312
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff81179a88)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8117f2ba)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_events_hist.c (ffffffff811802b4)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_map_size
```
```
In kernel/trace/trace_kprobe.c (ffffffff81184e64)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff81189bef)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - kernel/trace/trace_probe.c:find_fetch_type
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118c37e)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
```
In kernel/events/core.c (ffffffff811a2c19)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
```
```
In mm/backing-dev.c (ffffffff811e0409)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - mm/backing-dev.c:read_ahead_kb_store
```
```
In mm/hugetlb.c (ffffffff81214697)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store_common
```
```
In mm/ksm.c (ffffffff81220319)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
```
```
In mm/slub.c (ffffffff812246ef)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - mm/slub.c:remote_node_defrag_ratio_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:min_partial_store
  - mm/slub.c:order_store
```
```
In mm/huge_memory.c (ffffffff81232409)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - mm/huge_memory.c:single_hugepage_flag_store
```
```
In mm/khugepaged.c (ffffffff81237169)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
```
```
In fs/ext4/sysfs.c (ffffffff8133937e)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In security/keys/trusted.c (ffffffff813970b4)
Location: include/linux/kernel.h:312
Inline: True
```
```
In security/selinux/hooks.c (ffffffff820e3312)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
```
```
In security/selinux/selinuxfs.c (ffffffff820e34f2)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:checkreqprot_setup
```
```
In security/apparmor/lsm.c (ffffffff820e44aa)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_enabled_setup
```
```
In security/integrity/integrity_audit.c (ffffffff820e4a37)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_setup
```
```
In security/integrity/ima/ima_policy.c (ffffffff813f94f7)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/blk-sysfs.c (ffffffff81428c72)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
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
```
```
In lib/kstrtox.c (ffffffff8146ddeb)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
```
```
In drivers/pci/pci-sysfs.c (ffffffff814b3396)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:dev_bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
```
```
In drivers/pci/msi.c (ffffffff814cc4b9)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
```
```
In drivers/video/backlight/backlight.c (ffffffff814e7826)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
```
```
In drivers/acpi/osl.c (ffffffff820eb7a2)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - drivers/acpi/osl.c:setup_acpi_rsdp
```
```
In drivers/acpi/sysfs.c (ffffffff8150ab65)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:counter_set
```
```
In drivers/xen/xen-selfballoon.c (ffffffff815646a3)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - drivers/xen/xen-selfballoon.c:store_frontswap_hysteresis
  - drivers/xen/xen-selfballoon.c:store_frontswap_inertia
  - drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking
  - drivers/xen/xen-selfballoon.c:store_selfballoon_reserved_mb
  - drivers/xen/xen-selfballoon.c:store_selfballoon_min_usable_mb
  - drivers/xen/xen-selfballoon.c:store_selfballoon_uphys
  - drivers/xen/xen-selfballoon.c:store_selfballoon_downhys
  - drivers/xen/xen-selfballoon.c:store_selfballoon_interval
  - drivers/xen/xen-selfballoon.c:store_selfballooning
```
```
In drivers/tty/sysrq.c (ffffffff8157f3bd)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
```
```
In drivers/mfd/aat2870-core.c (ffffffff8162a148)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
```
```
In drivers/nvdimm/core.c (ffffffff8162d1e6)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nd_sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8163ba8b)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:align_store
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81650aa2)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/scsi/sd.c (ffffffff8165694a)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - drivers/scsi/sd.c:max_write_same_blocks_store
```
```
In drivers/rtc/rtc-sysfs.c (ffffffff8171c675)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
  - drivers/rtc/rtc-sysfs.c:max_user_freq_store
```
```
In drivers/md/md.c (ffffffff8173f865)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:chunk_size_store
```
```
In drivers/md/bitmap.c (ffffffff81747bb6)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - drivers/md/bitmap.c:chunksize_store
  - drivers/md/bitmap.c:backlog_store
  - drivers/md/bitmap.c:space_store
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff8175e2b6)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
  - drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec
```
```
In drivers/leds/led-class.c (ffffffff817826b8)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - drivers/leds/led-class.c:brightness_store
```
```
In net/core/net-sysfs.c (ffffffff817efb5e)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
```
```
In net/ipv4/tcp.c (ffffffff8210c7f1)
Location: include/linux/kernel.h:312
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8210cbf9)
Location: include/linux/kernel.h:312
Inline: True
```
```
In net/rfkill/core.c (ffffffff818dfcc8)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
```
```
In net/dns_resolver/dns_key.c (ffffffff818e4816)
Location: include/linux/kernel.h:312
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
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
In arch/x86/events/core.c (ffffffff81005849)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - arch/x86/events/core.c:set_attr_rdpmc
```
```
In arch/x86/events/intel/core.c (ffffffff8100b209)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/kernel/dumpstack.c (ffffffff826b0054)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:code_bytes_setup
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103ecbe)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c (ffffffff81048565)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_bw
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104d7df)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_interrupt_enable
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81052b49)
Location: include/linux/kernel.h:349
Inline: True
```
```
In arch/x86/kernel/early_printk.c (ffffffff826bf167)
Location: include/linux/kernel.h:349
Inline: True
```
```
In arch/x86/kernel/check.c (ffffffff826bffc3)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff826c18b3)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_parse_options
```
```
In kernel/params.c (ffffffff810aabc6)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - kernel/params.c:param_set_ulong
```
```
In kernel/ksysfs.c (ffffffff810ae4d9)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - kernel/ksysfs.c:kexec_crash_size_store
```
```
In kernel/power/main.c (ffffffff810df369)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:pm_async_store
```
```
In kernel/trace/trace.c (ffffffff8116f803)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:trace_pid_write
```
```
In kernel/trace/trace_functions.c (ffffffff8117c2c4)
Location: include/linux/kernel.h:349
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff811871e8)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8118cb97)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_events_hist.c (ffffffff8118db54)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_map_size
```
```
In kernel/trace/trace_kprobe.c (ffffffff81192b44)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff81197875)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:find_fetch_type
```
```
In kernel/trace/trace_uprobe.c (ffffffff81199e3e)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
```
In kernel/events/core.c (ffffffff811b6df1)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
```
```
In mm/backing-dev.c (ffffffff811f63f9)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - mm/backing-dev.c:read_ahead_kb_store
```
```
In mm/hugetlb.c (ffffffff8122f227)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store_common
```
```
In mm/ksm.c (ffffffff8123b559)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
```
```
In mm/slub.c (ffffffff8123fd7f)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - mm/slub.c:remote_node_defrag_ratio_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:min_partial_store
  - mm/slub.c:order_store
```
```
In mm/huge_memory.c (ffffffff8124fac9)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - mm/huge_memory.c:single_hugepage_flag_store
```
```
In mm/khugepaged.c (ffffffff812564f9)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
```
```
In fs/ext4/sysfs.c (ffffffff8135d6ee)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In security/keys/trusted.c (ffffffff813bc89a)
Location: include/linux/kernel.h:349
Inline: True
```
```
In security/selinux/hooks.c (ffffffff826ebfa5)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
```
```
In security/selinux/selinuxfs.c (ffffffff826ec185)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:checkreqprot_setup
```
```
In security/apparmor/lsm.c (ffffffff826ed15a)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_enabled_setup
```
```
In security/integrity/integrity_audit.c (ffffffff826ed61a)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_setup
```
```
In security/integrity/ima/ima_policy.c (ffffffff81421980)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/blk-sysfs.c (ffffffff81453d42)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
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
```
```
In lib/kstrtox.c (ffffffff8149a11b)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
```
```
In drivers/pci/pci-sysfs.c (ffffffff814f2b36)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:dev_bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
```
```
In drivers/pci/msi.c (ffffffff8150c9e9)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
```
```
In drivers/video/backlight/backlight.c (ffffffff8151c326)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
```
```
In drivers/acpi/osl.c (ffffffff826f4623)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - drivers/acpi/osl.c:setup_acpi_rsdp
```
```
In drivers/acpi/sysfs.c (ffffffff8154d535)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:counter_set
```
```
In drivers/xen/xen-selfballoon.c (ffffffff815c8833)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - drivers/xen/xen-selfballoon.c:store_frontswap_hysteresis
  - drivers/xen/xen-selfballoon.c:store_frontswap_inertia
  - drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking
  - drivers/xen/xen-selfballoon.c:store_selfballoon_reserved_mb
  - drivers/xen/xen-selfballoon.c:store_selfballoon_min_usable_mb
  - drivers/xen/xen-selfballoon.c:store_selfballoon_uphys
  - drivers/xen/xen-selfballoon.c:store_selfballoon_downhys
  - drivers/xen/xen-selfballoon.c:store_selfballoon_interval
  - drivers/xen/xen-selfballoon.c:store_selfballooning
```
```
In drivers/tty/sysrq.c (ffffffff815e3f2d)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
```
```
In drivers/mfd/aat2870-core.c (ffffffff81692a68)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
```
```
In drivers/nvdimm/core.c (ffffffff81695986)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nd_size_select_store
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff816b9db2)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/scsi/sd.c (ffffffff816c197a)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - drivers/scsi/sd.c:max_write_same_blocks_store
```
```
In drivers/rtc/rtc-sysfs.c (ffffffff8178d9b6)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - drivers/rtc/rtc-sysfs.c:max_user_freq_store
```
```
In drivers/md/md.c (ffffffff817b1885)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:chunk_size_store
```
```
In drivers/md/md-bitmap.c (ffffffff817b9e46)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff817d0316)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
  - drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec
```
```
In drivers/leds/led-class.c (ffffffff817f8a68)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - drivers/leds/led-class.c:brightness_store
```
```
In net/core/net-sysfs.c (ffffffff8186b17e)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
```
```
In net/ipv4/tcp.c (ffffffff82716b07)
Location: include/linux/kernel.h:349
Inline: True
```
```
In net/ipv4/udp.c (ffffffff82716f0d)
Location: include/linux/kernel.h:349
Inline: True
```
```
In net/rfkill/core.c (ffffffff819659d8)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
```
```
In net/dns_resolver/dns_key.c (ffffffff8196a63a)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
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
In arch/x86/events/core.c (ffffffff81005ff9)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - arch/x86/events/core.c:set_attr_rdpmc
```
```
In arch/x86/events/intel/core.c (ffffffff8100b969)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8104028e)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c (ffffffff8104ae2e)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_bw
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8105020e)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:store_interrupt_enable
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81055704)
Location: include/linux/kernel.h:365
Inline: True
```
```
In arch/x86/kernel/early_printk.c (ffffffff826e8f46)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:setup_early_printk
```
```
In arch/x86/kernel/check.c (ffffffff826ea1f3)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff826ebe40)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_parse_options
```
```
In kernel/params.c (ffffffff810b1835)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - kernel/params.c:param_set_ulong
```
```
In kernel/ksysfs.c (ffffffff810b5369)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - kernel/ksysfs.c:kexec_crash_size_store
```
```
In kernel/power/main.c (ffffffff810e7a2c)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:pm_async_store
```
```
In kernel/trace/trace.c (ffffffff8117ed78)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
```
```
In kernel/trace/trace_functions.c (ffffffff8118b404)
Location: include/linux/kernel.h:365
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff81196272)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8119b502)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_events_hist.c (ffffffff8119cdd4)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_map_size
```
```
In kernel/trace/trace_kprobe.c (ffffffff811a82b6)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811ad078)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:find_fetch_type
```
```
In kernel/trace/trace_uprobe.c (ffffffff811af822)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
```
In kernel/events/core.c (ffffffff811d6730)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
```
```
In mm/backing-dev.c (ffffffff81217708)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - mm/backing-dev.c:read_ahead_kb_store
```
```
In mm/hugetlb.c (ffffffff81252913)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store_common
```
```
In mm/ksm.c (ffffffff8125e9fc)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
```
```
In mm/slub.c (ffffffff81263991)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - mm/slub.c:min_partial_store
```
```
In mm/huge_memory.c (ffffffff81274051)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - mm/huge_memory.c:single_hugepage_flag_store
```
```
In mm/khugepaged.c (ffffffff8127a49c)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
```
```
In fs/ext4/sysfs.c (ffffffff8138bf2d)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In security/keys/trusted.c (ffffffff813ed650)
Location: include/linux/kernel.h:365
Inline: True
```
```
In security/selinux/hooks.c (ffffffff82716279)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
```
```
In security/apparmor/lsm.c (ffffffff827174bd)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_enabled_setup
```
```
In security/integrity/integrity_audit.c (ffffffff827179d2)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_setup
```
```
In security/integrity/ima/ima_policy.c (ffffffff81453eb2)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/blk-sysfs.c (ffffffff8148667b)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
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
```
```
In lib/kstrtox.c (ffffffff814cf3cb)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
```
```
In drivers/pci/pci-sysfs.c (ffffffff81522e5e)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:dev_bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
```
```
In drivers/pci/msi.c (ffffffff8154185f)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
```
```
In drivers/video/backlight/backlight.c (ffffffff8155201e)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
```
```
In drivers/acpi/osl.c (ffffffff8271e683)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - drivers/acpi/osl.c:setup_acpi_rsdp
```
```
In drivers/acpi/sysfs.c (ffffffff81583c7e)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:counter_set
```
```
In drivers/xen/xen-selfballoon.c (ffffffff816010c3)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - drivers/xen/xen-selfballoon.c:store_frontswap_hysteresis
  - drivers/xen/xen-selfballoon.c:store_frontswap_inertia
  - drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking
  - drivers/xen/xen-selfballoon.c:store_selfballoon_reserved_mb
  - drivers/xen/xen-selfballoon.c:store_selfballoon_min_usable_mb
  - drivers/xen/xen-selfballoon.c:store_selfballoon_uphys
  - drivers/xen/xen-selfballoon.c:store_selfballoon_downhys
  - drivers/xen/xen-selfballoon.c:store_selfballoon_interval
  - drivers/xen/xen-selfballoon.c:store_selfballooning
```
```
In drivers/tty/sysrq.c (ffffffff8161d1e6)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
```
```
In drivers/mfd/aat2870-core.c (ffffffff816ceb78)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
```
```
In drivers/nvdimm/core.c (ffffffff816d1a3b)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nd_size_select_store
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff816f618e)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/scsi/sd.c (ffffffff816fdfd2)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - drivers/scsi/sd.c:max_write_same_blocks_store
```
```
In drivers/rtc/rtc-sysfs.c (ffffffff817cfffe)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - drivers/rtc/rtc-sysfs.c:max_user_freq_store
```
```
In drivers/md/md.c (ffffffff817f98cc)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:chunk_size_store
```
```
In drivers/md/md-bitmap.c (ffffffff81801ef9)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff81819109)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
  - drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec
```
```
In drivers/leds/led-class.c (ffffffff81842058)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - drivers/leds/led-class.c:brightness_store
```
```
In net/core/net-sysfs.c (ffffffff818bc870)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
```
```
In net/ipv4/tcp.c (ffffffff82740edc)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - net/ipv4/tcp.c:set_thash_entries
```
```
In net/ipv4/udp.c (ffffffff82741308)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - net/ipv4/udp.c:set_uhash_entries
```
```
In net/rfkill/core.c (ffffffff819bf258)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
```
```
In net/dns_resolver/dns_key.c (ffffffff819c3fde)
Location: include/linux/kernel.h:365
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
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
In arch/x86/events/core.c (ffffffff81005ef9)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - arch/x86/events/core.c:set_attr_rdpmc
```
```
In arch/x86/events/intel/core.c (ffffffff8100ba29)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8104184e)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8104dade)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81052da4)
Location: include/linux/kernel.h:398
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105b631)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
```
```
In arch/x86/kernel/early_printk.c (ffffffff8289fadd)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:setup_early_printk
```
```
In arch/x86/kernel/check.c (ffffffff828a0e8a)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828a2a42)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_parse_options
```
```
In kernel/params.c (ffffffff810ba975)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - kernel/params.c:param_set_ulong
```
```
In kernel/ksysfs.c (ffffffff810be4b9)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - kernel/ksysfs.c:kexec_crash_size_store
```
```
In kernel/power/main.c (ffffffff810f303c)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:pm_async_store
```
```
In kernel/rcu/tree.c (ffffffff81110846)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
```
In kernel/trace/trace.c (ffffffff8118c678)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
```
```
In kernel/trace/trace_functions.c (ffffffff81198d34)
Location: include/linux/kernel.h:398
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff811a43d2)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811a9702)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_events_hist.c (ffffffff811ab424)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_map_size
```
```
In kernel/trace/trace_kprobe.c (ffffffff811b542a)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
```
In kernel/trace/trace_probe.c (ffffffff811bb012)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:find_fetch_type
```
```
In kernel/trace/trace_uprobe.c (ffffffff811bde71)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In kernel/events/core.c (ffffffff811e4ea0)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
```
```
In mm/backing-dev.c (ffffffff8122a618)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - mm/backing-dev.c:read_ahead_kb_store
```
```
In mm/hugetlb.c (ffffffff81266b73)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store_common
```
```
In mm/ksm.c (ffffffff8127320c)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
```
```
In mm/slub.c (ffffffff812781f1)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - mm/slub.c:min_partial_store
```
```
In mm/huge_memory.c (ffffffff81289081)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - mm/huge_memory.c:single_hugepage_flag_store
```
```
In mm/khugepaged.c (ffffffff8128ea9c)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
```
```
In fs/ext4/sysfs.c (ffffffff813a4abd)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In security/keys/trusted.c (ffffffff81408e33)
Location: include/linux/kernel.h:398
Inline: True
```
```
In security/selinux/hooks.c (ffffffff828cddb5)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
```
```
In security/apparmor/lsm.c (ffffffff828cef82)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_enabled_setup
```
```
In security/integrity/integrity_audit.c (ffffffff828cf433)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_setup
```
```
In security/integrity/ima/ima_policy.c (ffffffff814710f6)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/blk-sysfs.c (ffffffff814a09e1)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
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
```
```
In lib/kstrtox.c (ffffffff814e3cdb)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
```
```
In drivers/pci/pci-sysfs.c (ffffffff81538ca0)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:dev_bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
```
```
In drivers/pci/msi.c (ffffffff81558baf)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
```
```
In drivers/video/backlight/backlight.c (ffffffff815698ae)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
```
```
In drivers/acpi/osl.c (ffffffff828d66ae)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - drivers/acpi/osl.c:setup_acpi_rsdp
```
```
In drivers/acpi/sysfs.c (ffffffff8159bdae)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:counter_set
```
```
In drivers/xen/xen-selfballoon.c (ffffffff8161c1b3)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - drivers/xen/xen-selfballoon.c:store_frontswap_hysteresis
  - drivers/xen/xen-selfballoon.c:store_frontswap_inertia
  - drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking
  - drivers/xen/xen-selfballoon.c:store_selfballoon_reserved_mb
  - drivers/xen/xen-selfballoon.c:store_selfballoon_min_usable_mb
  - drivers/xen/xen-selfballoon.c:store_selfballoon_uphys
  - drivers/xen/xen-selfballoon.c:store_selfballoon_downhys
  - drivers/xen/xen-selfballoon.c:store_selfballoon_interval
  - drivers/xen/xen-selfballoon.c:store_selfballooning
```
```
In drivers/tty/sysrq.c (ffffffff8163a446)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
```
```
In drivers/base/core.c (ffffffff8169c34e)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_ulong
```
```
In drivers/mfd/aat2870-core.c (ffffffff816f0198)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
```
```
In drivers/nvdimm/core.c (ffffffff816f30cb)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nd_size_select_store
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81718a9e)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/scsi/sd.c (ffffffff81720ba2)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - drivers/scsi/sd.c:max_write_same_blocks_store
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff828ea769)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
```
In drivers/rtc/sysfs.c (ffffffff817f6f8e)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:max_user_freq_store
```
```
In drivers/md/md.c (ffffffff8182589c)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:chunk_size_store
```
```
In drivers/md/md-bitmap.c (ffffffff8182e109)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff818449a9)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
  - drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec
```
```
In drivers/leds/led-class.c (ffffffff8186df78)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - drivers/leds/led-class.c:brightness_store
```
```
In net/core/net-sysfs.c (ffffffff818e3b30)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
```
```
In net/ipv4/tcp.c (ffffffff828fb111)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - net/ipv4/tcp.c:set_thash_entries
```
```
In net/ipv4/udp.c (ffffffff828fb56e)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - net/ipv4/udp.c:set_uhash_entries
```
```
In net/rfkill/core.c (ffffffff819f6818)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
```
```
In net/dns_resolver/dns_key.c (ffffffff819fb39b)
Location: include/linux/kernel.h:398
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
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
In arch/x86/events/core.c (ffffffff81005eb9)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - arch/x86/events/core.c:set_attr_rdpmc
```
```
In arch/x86/events/intel/core.c (ffffffff8100be59)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81043cfb)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81050a3e)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81055f53)
Location: include/linux/kernel.h:357
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105e9a4)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
```
```
In arch/x86/kernel/early_printk.c (ffffffff828b7a2f)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:setup_early_printk
```
```
In arch/x86/kernel/check.c (ffffffff828b90db)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828baaab)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_parse_options
```
```
In kernel/params.c (ffffffff810c0885)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - kernel/params.c:param_set_ulong
```
```
In kernel/ksysfs.c (ffffffff810c44d9)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - kernel/ksysfs.c:kexec_crash_size_store
```
```
In kernel/power/main.c (ffffffff810fb50c)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:pm_async_store
```
```
In kernel/rcu/tree.c (ffffffff8111a266)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
```
In kernel/trace/trace.c (ffffffff81199eaf)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
```
```
In kernel/trace/trace_functions.c (ffffffff811a6926)
Location: include/linux/kernel.h:357
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff811b2218)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811b767d)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_events_hist.c (ffffffff811b98a4)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_map_size
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c41f5)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
```
In kernel/trace/trace_probe.c (ffffffff811ca0c0)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:find_fetch_type
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ccdd9)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In kernel/events/core.c (ffffffff811fc513)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
```
```
In mm/backing-dev.c (ffffffff8123a285)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - mm/backing-dev.c:read_ahead_kb_store
```
```
In mm/hugetlb.c (ffffffff81281f8b)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store_common
```
```
In mm/ksm.c (ffffffff8128ea0c)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
```
```
In mm/slub.c (ffffffff812938c1)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - mm/slub.c:min_partial_store
```
```
In mm/huge_memory.c (ffffffff812a3d31)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - mm/huge_memory.c:single_hugepage_flag_store
```
```
In mm/khugepaged.c (ffffffff812a93bc)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
```
```
In fs/ext4/sysfs.c (ffffffff813ceca8)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In security/keys/trusted.c (ffffffff814359f2)
Location: include/linux/kernel.h:357
Inline: True
```
```
In security/selinux/hooks.c (ffffffff828e780a)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
```
```
In security/apparmor/lsm.c (ffffffff828e8a08)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_enabled_setup
```
```
In security/integrity/integrity_audit.c (ffffffff828e8f40)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_setup
```
```
In security/integrity/ima/ima_policy.c (ffffffff8149ec97)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/blk-sysfs.c (ffffffff814cef92)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
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
```
```
In lib/kstrtox.c (ffffffff815100bb)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
```
```
In drivers/pci/pci-sysfs.c (ffffffff81568680)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:dev_bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
```
```
In drivers/pci/msi.c (ffffffff81588c50)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
```
```
In drivers/video/backlight/backlight.c (ffffffff8159a13e)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
```
```
In drivers/acpi/osl.c (ffffffff828f0501)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - drivers/acpi/osl.c:setup_acpi_rsdp
```
```
In drivers/acpi/sysfs.c (ffffffff815cd41e)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:counter_set
```
```
In drivers/tty/sysrq.c (ffffffff8166e796)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
```
```
In drivers/base/core.c (ffffffff816d50fe)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_ulong
```
```
In drivers/mfd/aat2870-core.c (ffffffff8172987b)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
```
```
In drivers/nvdimm/core.c (ffffffff8172c601)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nd_size_select_store
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8175421b)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/scsi/sd.c (ffffffff8175c272)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - drivers/scsi/sd.c:max_write_same_blocks_store
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8290519e)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
```
In drivers/rtc/sysfs.c (ffffffff81837c9e)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:max_user_freq_store
```
```
In drivers/md/md.c (ffffffff81867d52)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:chunk_size_store
```
```
In drivers/md/md-bitmap.c (ffffffff81870782)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff81887789)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
```
```
In drivers/leds/led-class.c (ffffffff818b2212)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - drivers/leds/led-class.c:brightness_store
```
```
In net/core/net-sysfs.c (ffffffff81933080)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
```
```
In net/ipv4/tcp.c (ffffffff82917b13)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - net/ipv4/tcp.c:set_thash_entries
```
```
In net/ipv4/udp.c (ffffffff82917f76)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - net/ipv4/udp.c:set_uhash_entries
```
```
In net/rfkill/core.c (ffffffff81a657a8)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
```
```
In net/dns_resolver/dns_key.c (ffffffff81a6aa2f)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
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
In arch/x86/events/core.c (ffffffff81005e69)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/events/core.c:set_attr_rdpmc
```
```
In arch/x86/events/intel/core.c (ffffffff8100c269)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8104444b)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810513ce)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056893)
Location: include/linux/kernel.h:361
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105f224)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
```
```
In arch/x86/kernel/early_printk.c (ffffffff828bdf2d)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:setup_early_printk
```
```
In arch/x86/kernel/check.c (ffffffff828bf5c9)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828c0f6d)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_parse_options
```
```
In kernel/params.c (ffffffff810c6c85)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/params.c:param_set_ulong
```
```
In kernel/ksysfs.c (ffffffff810cd5e9)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/ksysfs.c:kexec_crash_size_store
```
```
In kernel/power/main.c (ffffffff81107bac)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:pm_async_store
```
```
In kernel/rcu/tree.c (ffffffff81126676)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
```
In kernel/trace/trace.c (ffffffff811a585f)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
```
```
In kernel/trace/trace_functions.c (ffffffff811b2116)
Location: include/linux/kernel.h:361
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff811bd898)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811c2ced)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c4eb9)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_map_size
```
```
In kernel/trace/trace_kprobe.c (ffffffff811d0115)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
```
In kernel/trace/trace_probe.c (ffffffff811d5e80)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:find_fetch_type
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d939a)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In kernel/events/core.c (ffffffff812095eb)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
```
```
In mm/backing-dev.c (ffffffff81248585)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/backing-dev.c:read_ahead_kb_store
```
```
In mm/hugetlb.c (ffffffff812919fb)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store_common
```
```
In mm/ksm.c (ffffffff8129e7ec)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
```
```
In mm/slub.c (ffffffff812a3641)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/slub.c:min_partial_store
```
```
In mm/huge_memory.c (ffffffff812b5231)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/huge_memory.c:single_hugepage_flag_store
```
```
In mm/khugepaged.c (ffffffff812ba92c)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
```
```
In fs/ext4/sysfs.c (ffffffff813e8378)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In security/keys/trusted.c (ffffffff8144f792)
Location: include/linux/kernel.h:361
Inline: True
```
```
In security/selinux/hooks.c (ffffffff828f02f6)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
```
```
In security/apparmor/lsm.c (ffffffff828f14f4)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_enabled_setup
```
```
In security/integrity/integrity_audit.c (ffffffff828f1b2d)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_setup
```
```
In security/integrity/ima/ima_policy.c (ffffffff814b8f44)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/blk-sysfs.c (ffffffff814e82f2)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
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
```
```
In lib/kstrtox.c (ffffffff8152dfbb)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
```
```
In drivers/pci/pci-sysfs.c (ffffffff815898c0)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
```
```
In drivers/pci/msi.c (ffffffff815aa570)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
```
```
In drivers/video/backlight/backlight.c (ffffffff815bb54e)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
```
```
In drivers/acpi/osl.c (ffffffff828f9672)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/acpi/osl.c:setup_acpi_rsdp
```
```
In drivers/acpi/sysfs.c (ffffffff815ee69e)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:counter_set
```
```
In drivers/tty/sysrq.c (ffffffff81690dd6)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
```
```
In drivers/base/core.c (ffffffff816f8eae)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_ulong
```
```
In drivers/mfd/aat2870-core.c (ffffffff8174dabb)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
```
```
In drivers/nvdimm/core.c (ffffffff81750841)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nd_size_select_store
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8177849b)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/scsi/sd.c (ffffffff81780112)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/scsi/sd.c:max_write_same_blocks_store
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8290ebd9)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
```
In drivers/rtc/sysfs.c (ffffffff8186960e)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:max_user_freq_store
```
```
In drivers/md/md.c (ffffffff81899ae2)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:chunk_size_store
```
```
In drivers/md/md-bitmap.c (ffffffff818a2572)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff818b9739)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
```
```
In drivers/leds/led-class.c (ffffffff818e49d2)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/leds/led-class.c:brightness_store
```
```
In net/core/net-sysfs.c (ffffffff81965bc0)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
```
```
In net/ipv4/tcp.c (ffffffff82921982)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/ipv4/tcp.c:set_thash_entries
```
```
In net/ipv4/udp.c (ffffffff82921de5)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/ipv4/udp.c:set_uhash_entries
```
```
In net/rfkill/core.c (ffffffff81a9c308)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
```
```
In net/dns_resolver/dns_key.c (ffffffff81aa141f)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
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
In arch/x86/events/core.c (ffffffff81006d59)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - arch/x86/events/core.c:set_attr_rdpmc
```
```
In arch/x86/events/intel/core.c (ffffffff8100d419)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810481fb)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8105560e)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105b7c3)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81064d84)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
```
```
In arch/x86/kernel/early_printk.c (ffffffff82ce221d)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
```
```
In arch/x86/kernel/check.c (ffffffff82ce38bc)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
```
```
In kernel/panic.c (ffffffff82ceceb2)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - kernel/panic.c:panic_on_taint_setup
```
```
In kernel/params.c (ffffffff810ceca5)
Location: include/linux/kernel.h:351
Inline: True
```
```
In kernel/ksysfs.c (ffffffff810d7289)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - kernel/ksysfs.c:kexec_crash_size_store
```
```
In kernel/power/main.c (ffffffff811126cc)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:sync_on_suspend_store
  - kernel/power/main.c:pm_async_store
```
```
In kernel/rcu/tree.c (ffffffff811343c6)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
```
In kernel/trace/trace.c (ffffffff811bc7b3)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
```
```
In kernel/trace/trace_functions.c (ffffffff811ca829)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_cpudump_callback
  - kernel/trace/trace_functions.c:ftrace_dump_callback
  - kernel/trace/trace_functions.c:ftrace_stacktrace_callback
```
```
In kernel/trace/trace_events.c (ffffffff811d6dfd)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811dc5b5)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e17c9)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_map_size
```
```
In kernel/trace/trace_kprobe.c (ffffffff811edf3f)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
```
In kernel/trace/trace_probe.c (ffffffff811f2720)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:find_fetch_type
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f606a)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In kernel/events/core.c (ffffffff812341a1)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
```
```
In mm/backing-dev.c (ffffffff81276745)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - mm/backing-dev.c:read_ahead_kb_store
```
```
In mm/hugetlb.c (ffffffff812c4a03)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_mempolicy_store
  - mm/hugetlb.c:nr_hugepages_store
```
```
In mm/ksm.c (ffffffff812d2dfc)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
```
```
In mm/slub.c (ffffffff812d7d41)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - mm/slub.c:min_partial_store
```
```
In mm/huge_memory.c (ffffffff812e8a4c)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - mm/huge_memory.c:use_zero_page_store
```
```
In mm/khugepaged.c (ffffffff812ef70c)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_max_ptes_shared_store
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
```
```
In fs/ext4/sysfs.c (ffffffff814353cb)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814a0f3d)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
```
```
In security/selinux/hooks.c (ffffffff82d054da)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
```
```
In security/apparmor/lsm.c (ffffffff82d06564)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_enabled_setup
```
```
In security/integrity/integrity_audit.c (ffffffff82d06b84)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_setup
```
```
In security/integrity/ima/ima_policy.c (ffffffff815192c6)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/blk-sysfs.c (ffffffff815478a0)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
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
```
```
In lib/kstrtox.c (ffffffff81591a7b)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
```
```
In drivers/pci/pci-sysfs.c (ffffffff816307c0)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
```
```
In drivers/pci/msi.c (ffffffff81653600)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
```
```
In drivers/video/backlight/backlight.c (ffffffff8166547e)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
```
```
In drivers/acpi/osl.c (ffffffff82d107ae)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - drivers/acpi/osl.c:setup_acpi_rsdp
```
```
In drivers/acpi/sysfs.c (ffffffff8169a50e)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:counter_set
```
```
In drivers/tty/sysrq.c (ffffffff81743486)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
```
```
In drivers/base/core.c (ffffffff817b1d7e)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_ulong
```
```
In drivers/mfd/aat2870-core.c (ffffffff8180bcbb)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
```
```
In drivers/nvdimm/core.c (ffffffff8180f0a1)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nd_size_select_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff818150e9)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:align_store
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8183b429)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/scsi/sd.c (ffffffff81842052)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - drivers/scsi/sd.c:max_write_same_blocks_store
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff82d22f06)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
```
In drivers/rtc/sysfs.c (ffffffff8193d26e)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:max_user_freq_store
```
```
In drivers/md/md.c (ffffffff819690bb)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:chunk_size_store
```
```
In drivers/md/md-bitmap.c (ffffffff81971fb2)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff8198a0e9)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
```
```
In drivers/leds/led-class.c (ffffffff819b7ae2)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - drivers/leds/led-class.c:brightness_store
```
```
In net/core/net-sysfs.c (ffffffff81a37690)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:carrier_store
```
```
In net/ipv4/tcp.c (ffffffff82d2df35)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - net/ipv4/tcp.c:set_thash_entries
```
```
In net/ipv4/udp.c (ffffffff82d2e39d)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - net/ipv4/udp.c:set_uhash_entries
```
```
In net/rfkill/core.c (ffffffff81b98568)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
```
```
In net/dns_resolver/dns_key.c (ffffffff81b9cd99)
Location: include/linux/kernel.h:351
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
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
In arch/x86/events/core.c (ffffffff81005b99)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - arch/x86/events/core.c:set_attr_rdpmc
```
```
In arch/x86/events/intel/core.c (ffffffff8100c479)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810476ab)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8105452e)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105a213)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81062f74)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
```
```
In arch/x86/kernel/early_printk.c (ffffffff82fcf441)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
```
```
In arch/x86/kernel/check.c (ffffffff82fd0bb5)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
```
```
In kernel/panic.c (ffffffff82fd950c)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - kernel/panic.c:panic_on_taint_setup
```
```
In kernel/params.c (ffffffff810c97d5)
Location: include/linux/kernel.h:203
Inline: True
```
```
In kernel/ksysfs.c (ffffffff810d2049)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - kernel/ksysfs.c:kexec_crash_size_store
```
```
In kernel/power/main.c (ffffffff8110f79c)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:sync_on_suspend_store
  - kernel/power/main.c:pm_async_store
```
```
In kernel/rcu/tree.c (ffffffff8112fe66)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
```
In kernel/trace/trace.c (ffffffff811ba3c3)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
```
```
In kernel/trace/trace_functions.c (ffffffff811c7ea9)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_cpudump_callback
  - kernel/trace/trace_functions.c:ftrace_dump_callback
  - kernel/trace/trace_functions.c:ftrace_stacktrace_callback
```
```
In kernel/trace/trace_events.c (ffffffff811d417d)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811d96e5)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_events_hist.c (ffffffff811df3e9)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_map_size
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ec09f)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
```
In kernel/trace/trace_probe.c (ffffffff811f10d0)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:find_fetch_type
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f49fa)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In kernel/trace/trace_boot.c (ffffffff82fe3b04)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
```
In kernel/events/core.c (ffffffff8123e673)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
```
```
In mm/backing-dev.c (ffffffff81281055)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - mm/backing-dev.c:read_ahead_kb_store
```
```
In mm/hugetlb.c (ffffffff812d06a3)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_mempolicy_store
  - mm/hugetlb.c:nr_hugepages_store
```
```
In mm/ksm.c (ffffffff812de7bc)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:merge_across_nodes_store
```
```
In mm/slub.c (ffffffff812e3821)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - mm/slub.c:min_partial_store
```
```
In mm/huge_memory.c (ffffffff812f3ebc)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - mm/huge_memory.c:use_zero_page_store
```
```
In mm/khugepaged.c (ffffffff812fb02c)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_max_ptes_shared_store
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
```
```
In fs/ext4/sysfs.c (ffffffff8144ddfb)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814be8ed)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
```
```
In security/selinux/hooks.c (ffffffff82ff28a7)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
```
```
In security/apparmor/lsm.c (ffffffff82ff3901)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_enabled_setup
```
```
In security/integrity/integrity_audit.c (ffffffff82ff3fa8)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_setup
```
```
In security/integrity/ima/ima_policy.c (ffffffff81536369)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/blk-sysfs.c (ffffffff815635d0)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
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
```
```
In lib/kstrtox.c (ffffffff815ae5bb)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
```
```
In drivers/pci/pci-sysfs.c (ffffffff81655e60)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
```
```
In drivers/pci/msi.c (ffffffff8165d500)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
```
```
In drivers/video/backlight/backlight.c (ffffffff816860fe)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
```
```
In drivers/acpi/osl.c (ffffffff82ffe27e)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - drivers/acpi/osl.c:setup_acpi_rsdp
```
```
In drivers/acpi/sysfs.c (ffffffff816b758e)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:counter_set
```
```
In drivers/tty/sysrq.c (ffffffff8175f306)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
```
```
In drivers/base/core.c (ffffffff817c66de)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_ulong
```
```
In drivers/mfd/aat2870-core.c (ffffffff8181affb)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
```
```
In drivers/nvdimm/core.c (ffffffff8181e011)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nd_size_select_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff818242d9)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:align_store
```
```
In drivers/dax/bus.c (ffffffff81832f78)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - drivers/dax/bus.c:align_store
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8184c349)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/scsi/sd.c (ffffffff81852802)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - drivers/scsi/sd.c:max_write_same_blocks_store
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff83010d06)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
```
In drivers/rtc/sysfs.c (ffffffff8194327e)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:max_user_freq_store
```
```
In drivers/md/md.c (ffffffff8196fbcb)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:chunk_size_store
```
```
In drivers/md/md-bitmap.c (ffffffff81976ec2)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff8198dcb9)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
```
```
In drivers/leds/led-class.c (ffffffff819b9f62)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - drivers/leds/led-class.c:brightness_store
```
```
In net/core/net-sysfs.c (ffffffff81a39a50)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:carrier_store
```
```
In net/ipv4/tcp.c (ffffffff8301ca8b)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - net/ipv4/tcp.c:set_thash_entries
```
```
In net/ipv4/udp.c (ffffffff8301cf25)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - net/ipv4/udp.c:set_uhash_entries
```
```
In net/rfkill/core.c (ffffffff81ba8288)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
```
```
In net/dns_resolver/dns_key.c (ffffffff81baca89)
Location: include/linux/kernel.h:203
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
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
In arch/x86/events/core.c (ffffffff81005ae9)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - arch/x86/events/core.c:set_attr_rdpmc
```
```
In arch/x86/events/intel/core.c (ffffffff8100ce89)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8104917b)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81055d2e)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105abb5)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81063643)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
```
```
In arch/x86/kernel/early_printk.c (ffffffff831d9ed7)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
```
```
In arch/x86/kernel/check.c (ffffffff831db887)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
```
```
In kernel/panic.c (ffffffff831e3e60)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - kernel/panic.c:panic_on_taint_setup
```
```
In kernel/params.c (ffffffff810cb2e5)
Location: include/linux/kernel.h:213
Inline: True
```
```
In kernel/ksysfs.c (ffffffff810d3c29)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - kernel/ksysfs.c:kexec_crash_size_store
```
```
In kernel/power/main.c (ffffffff8111023c)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:sync_on_suspend_store
  - kernel/power/main.c:pm_async_store
```
```
In kernel/rcu/tree.c (ffffffff81130386)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
```
In kernel/cgroup/misc.c (ffffffff81180f27)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_max_write
```
```
In kernel/trace/trace.c (ffffffff811ba830)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
```
```
In kernel/trace/trace_functions.c (ffffffff811c8da2)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_cpudump_callback
  - kernel/trace/trace_functions.c:ftrace_dump_callback
  - kernel/trace/trace_functions.c:ftrace_stacktrace_callback
```
```
In kernel/trace/trace_events.c (ffffffff811d5865)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811dac40)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e0599)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_map_size
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ecd2d)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
```
```
In kernel/trace/trace_probe.c (ffffffff811f2003)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:find_fetch_type
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f5928)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
```
```
In kernel/trace/trace_boot.c (ffffffff831ee23e)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
```
In kernel/events/core.c (ffffffff81242c15)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
```
```
In mm/backing-dev.c (ffffffff81286185)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - mm/backing-dev.c:read_ahead_kb_store
```
```
In mm/hugetlb.c (ffffffff812d7643)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_mempolicy_store
  - mm/hugetlb.c:nr_hugepages_store
```
```
In mm/ksm.c (ffffffff812e5f9c)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:merge_across_nodes_store
```
```
In mm/slub.c (ffffffff812eafd1)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - mm/slub.c:min_partial_store
```
```
In mm/huge_memory.c (ffffffff812f9f4c)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - mm/huge_memory.c:use_zero_page_store
```
```
In mm/khugepaged.c (ffffffff81301dec)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_max_ptes_shared_store
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
```
```
In fs/ext4/sysfs.c (ffffffff814538bb)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814c4c1e)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
```
```
In security/selinux/hooks.c (ffffffff831fd283)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
```
```
In security/apparmor/lsm.c (ffffffff831fe41e)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_enabled_setup
```
```
In security/integrity/integrity_audit.c (ffffffff831feb56)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_setup
```
```
In security/integrity/ima/ima_policy.c (ffffffff8153eb5f)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/blk-sysfs.c (ffffffff8156bd25)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
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
```
```
In lib/kstrtox.c (ffffffff815b90bb)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
```
```
In drivers/pci/pci-sysfs.c (ffffffff816380b0)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
```
```
In drivers/pci/msi.c (ffffffff8163f960)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
```
```
In drivers/video/backlight/backlight.c (ffffffff81668efe)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
```
```
In drivers/acpi/osl.c (ffffffff83209032)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - drivers/acpi/osl.c:setup_acpi_rsdp
```
```
In drivers/acpi/sysfs.c (ffffffff81699615)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:counter_set
```
```
In drivers/tty/sysrq.c (ffffffff81743176)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
```
```
In drivers/base/core.c (ffffffff817a9bce)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_ulong
```
```
In drivers/mfd/aat2870-core.c (ffffffff817fe73a)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
```
```
In drivers/nvdimm/core.c (ffffffff81801361)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nd_size_select_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff81807509)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:align_store
```
```
In drivers/dax/bus.c (ffffffff818160f9)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - drivers/dax/bus.c:align_store
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8182f769)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/scsi/sd.c (ffffffff81835892)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - drivers/scsi/sd.c:max_write_same_blocks_store
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8321bb1d)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
```
In drivers/rtc/sysfs.c (ffffffff81926a9e)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:max_user_freq_store
```
```
In drivers/md/md.c (ffffffff81952f7b)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:chunk_size_store
```
```
In drivers/md/md-bitmap.c (ffffffff8195b122)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff81972349)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
```
```
In drivers/leds/led-class.c (ffffffff8199e752)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - drivers/leds/led-class.c:brightness_store
```
```
In net/core/net-sysfs.c (ffffffff81a20e10)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
```
```
In net/ipv4/tcp.c (ffffffff83227b8f)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - net/ipv4/tcp.c:set_thash_entries
```
```
In net/ipv4/udp.c (ffffffff83228011)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - net/ipv4/udp.c:set_uhash_entries
```
```
In net/rfkill/core.c (ffffffff81b97418)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
```
```
In net/dns_resolver/dns_key.c (ffffffff81b9bd2b)
Location: include/linux/kernel.h:213
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
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
In arch/x86/events/core.c (ffffffff810060b9)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/events/core.c:set_attr_rdpmc
```
```
In arch/x86/events/intel/core.c (ffffffff8100d329)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8104fb3b)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8105e61e)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810640f5)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8106d5f6)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
```
```
In arch/x86/kernel/early_printk.c (ffffffff832bcf58)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
```
```
In arch/x86/kernel/check.c (ffffffff832bec20)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
```
```
In kernel/panic.c (ffffffff832c7a37)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/panic.c:panic_on_taint_setup
```
```
In kernel/params.c (ffffffff810de445)
Location: include/linux/kstrtox.h:30
Inline: True
```
```
In kernel/ksysfs.c (ffffffff810e6da9)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/ksysfs.c:kexec_crash_size_store
```
```
In kernel/power/main.c (ffffffff8112fbec)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:sync_on_suspend_store
  - kernel/power/main.c:pm_async_store
```
```
In kernel/irq/msi.c (ffffffff81149564)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_mode_show
```
```
In kernel/rcu/tree.c (ffffffff81151c06)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
```
In kernel/cgroup/misc.c (ffffffff811a8d47)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_max_write
```
```
In kernel/trace/trace.c (ffffffff811e52ee)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
```
```
In kernel/trace/trace_functions.c (ffffffff811f4772)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_cpudump_callback
  - kernel/trace/trace_functions.c:ftrace_dump_callback
  - kernel/trace/trace_functions.c:ftrace_stacktrace_callback
```
```
In kernel/trace/trace_events.c (ffffffff812026c5)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81208210)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_events_hist.c (ffffffff8120fb93)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_assignment
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121ddd8)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
```
```
In kernel/trace/trace_probe.c (ffffffff812231ba)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:find_fetch_type
```
```
In kernel/trace/trace_uprobe.c (ffffffff81227a57)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
```
```
In kernel/trace/trace_boot.c (ffffffff832d2f05)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
```
In kernel/events/core.c (ffffffff8127d41c)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
```
```
In mm/backing-dev.c (ffffffff812c5395)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/backing-dev.c:read_ahead_kb_store
```
```
In mm/hugetlb.c (ffffffff8131d133)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_mempolicy_store
  - mm/hugetlb.c:nr_hugepages_store
```
```
In mm/ksm.c (ffffffff8132effc)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/ksm.c:merge_across_nodes_store
```
```
In mm/slub.c (ffffffff81332ed1)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/slub.c:min_partial_store
```
```
In mm/kfence/core.c (ffffffff8133bbe8)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/kfence/core.c:param_set_sample_interval
```
```
In mm/huge_memory.c (ffffffff81343dac)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/huge_memory.c:use_zero_page_store
```
```
In mm/khugepaged.c (ffffffff8134b9dc)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_max_ptes_shared_store
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
```
```
In fs/ext4/sysfs.c (ffffffff814a792b)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8151d5fd)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
```
```
In security/selinux/hooks.c (ffffffff832e4488)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
```
```
In security/apparmor/lsm.c (ffffffff832e5730)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_enabled_setup
```
```
In security/integrity/integrity_audit.c (ffffffff832e5e68)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_setup
```
```
In security/integrity/ima/ima_policy.c (ffffffff8159de1a)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/blk-sysfs.c (ffffffff815cffb5)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
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
```
```
In lib/kstrtox.c (ffffffff8161f931)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
```
```
In drivers/pci/pci-sysfs.c (ffffffff816a83b0)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
```
```
In drivers/video/backlight/backlight.c (ffffffff816dc21e)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
```
```
In drivers/acpi/osl.c (ffffffff832f1300)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/acpi/osl.c:setup_acpi_rsdp
```
```
In drivers/acpi/sysfs.c (ffffffff8170f4a5)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:counter_set
```
```
In drivers/tty/sysrq.c (ffffffff817c3ba6)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
```
```
In drivers/base/core.c (ffffffff81832d4e)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_ulong
```
```
In drivers/mfd/aat2870-core.c (ffffffff81888314)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
```
```
In drivers/nvdimm/core.c (ffffffff8188b791)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nd_size_select_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff818905c9)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:align_store
```
```
In drivers/dax/bus.c (ffffffff818a0729)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/dax/bus.c:align_store
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff818bb5b9)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/scsi/sd.c (ffffffff818c1c72)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/scsi/sd.c:max_write_same_blocks_store
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8330576c)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
```
In drivers/rtc/sysfs.c (ffffffff819c99de)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:max_user_freq_store
```
```
In drivers/md/md.c (ffffffff819f84fb)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:chunk_size_store
```
```
In drivers/md/md-bitmap.c (ffffffff81a00912)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff81a1aff9)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
```
```
In drivers/leds/led-class.c (ffffffff81a4b402)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/leds/led-class.c:brightness_store
```
```
In net/core/net-sysfs.c (ffffffff81ad5290)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
```
```
In net/ipv4/tcp.c (ffffffff83311f55)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp.c:set_thash_entries
```
```
In net/ipv4/udp.c (ffffffff8331242c)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - net/ipv4/udp.c:set_uhash_entries
```
```
In net/rfkill/core.c (ffffffff81c636c8)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
```
```
In net/dns_resolver/dns_key.c (ffffffff81c68c75)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
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
In arch/x86/events/core.c (ffffffff810054b1)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/events/core.c:set_attr_rdpmc
```
```
In arch/x86/events/intel/core.c (ffffffff8100e481)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8105b343)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8106aa2e)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8107ab2a)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
```
```
In arch/x86/kernel/early_printk.c (ffffffff8346e8ee)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
```
```
In arch/x86/kernel/check.c (ffffffff83470a1a)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
```
```
In kernel/panic.c (ffffffff8347a97f)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/panic.c:panic_on_taint_setup
```
```
In kernel/params.c (ffffffff810f8175)
Location: include/linux/kstrtox.h:30
Inline: True
```
```
In kernel/ksysfs.c (ffffffff81100f11)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/ksysfs.c:kexec_crash_size_store
```
```
In kernel/power/main.c (ffffffff81151234)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:sync_on_suspend_store
  - kernel/power/main.c:pm_async_store
```
```
In kernel/rcu/tree.c (ffffffff8117a2be)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
```
In kernel/cgroup/misc.c (ffffffff811da018)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_max_write
```
```
In kernel/trace/trace.c (ffffffff8121cf1d)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
```
```
In kernel/trace/trace_functions.c (ffffffff8122daf0)
Location: include/linux/kstrtox.h:30
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff8123daa2)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812445c9)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_parse_num
```
```
In kernel/trace/trace_events_hist.c (ffffffff812513ba)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_assignment
```
```
In kernel/trace/trace_kprobe.c (ffffffff8125d380)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
```
```
In kernel/trace/trace_probe.c (ffffffff81263116)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:find_fetch_type
```
```
In kernel/trace/trace_uprobe.c (ffffffff81267c4b)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
```
```
In kernel/trace/trace_boot.c (ffffffff834873a5)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
```
In kernel/events/core.c (ffffffff812d16b0)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
```
```
In mm/backing-dev.c (ffffffff8132297d)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/backing-dev.c:read_ahead_kb_store
```
```
In mm/hugetlb.c (ffffffff81389ce8)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_mempolicy_store
  - mm/hugetlb.c:nr_hugepages_store
```
```
In mm/ksm.c (ffffffff8139f1f4)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/ksm.c:merge_across_nodes_store
```
```
In mm/slub.c (ffffffff813a45f9)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/slub.c:min_partial_store
```
```
In mm/kfence/core.c (ffffffff813af1a2)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/kfence/core.c:param_set_sample_interval
```
```
In mm/huge_memory.c (ffffffff813b93f4)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/huge_memory.c:use_zero_page_store
```
```
In mm/khugepaged.c (ffffffff813c3114)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_max_ptes_shared_store
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
```
```
In fs/ext4/sysfs.c (ffffffff8152f193)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff815b09c1)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
```
```
In security/selinux/hooks.c (ffffffff8349b045)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
```
```
In security/apparmor/lsm.c (ffffffff8349c4b6)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_enabled_setup
```
```
In security/integrity/integrity_audit.c (ffffffff8349ccdf)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_setup
```
```
In security/integrity/ima/ima_policy.c (ffffffff816431c0)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/blk-sysfs.c (ffffffff8167b7b9)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
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
```
```
In lib/kstrtox.c (0)
Location: include/linux/kstrtox.h:30
Inline: True
```
```
In drivers/pci/pci-sysfs.c (ffffffff817caf88)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
```
```
In drivers/video/backlight/backlight.c (ffffffff81805f76)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
```
```
In drivers/acpi/osl.c (ffffffff834a9352)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/acpi/osl.c:setup_acpi_rsdp
```
```
In drivers/acpi/sysfs.c (ffffffff8183df5c)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:counter_set
```
```
In drivers/tty/sysrq.c (ffffffff8190090e)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
```
```
In drivers/base/core.c (ffffffff81974596)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_ulong
```
```
In drivers/mfd/aat2870-core.c (ffffffff819d1443)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
```
```
In drivers/nvdimm/core.c (ffffffff819d4a3d)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nd_size_select_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff819da506)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:align_store
```
```
In drivers/dax/bus.c (ffffffff819e9d61)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/dax/bus.c:align_store
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81a07263)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/scsi/sd.c (ffffffff81a0e68a)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/scsi/sd.c:max_write_same_blocks_store
```
```
In drivers/rtc/sysfs.c (ffffffff81b2ae26)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:max_user_freq_store
```
```
In drivers/md/md.c (ffffffff81b5e389)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:chunk_size_store
```
```
In drivers/md/md-bitmap.c (ffffffff81b6821a)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff81b83e19)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
```
```
In drivers/leds/led-class.c (ffffffff81bb9bba)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/leds/led-class.c:brightness_store
```
```
In net/core/net-sysfs.c (ffffffff81c555f8)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
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
```
```
In net/ipv4/tcp.c (ffffffff834cbebc)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp.c:set_thash_entries
```
```
In net/ipv4/udp.c (ffffffff834cc4d3)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - net/ipv4/udp.c:set_uhash_entries
```
```
In net/rfkill/core.c (ffffffff81e060c0)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
```
```
In net/dns_resolver/dns_key.c (ffffffff81e0be71)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
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
In arch/x86/events/core.c (ffffffff810060c1)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/events/core.c:set_attr_rdpmc
```
```
In arch/x86/events/intel/core.c (ffffffff810119e1)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81068cf3)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107a93e)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8108bdac)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
```
```
In arch/x86/kernel/early_printk.c (ffffffff83e94ab2)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
```
```
In arch/x86/kernel/check.c (ffffffff83e97859)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
```
```
In kernel/panic.c (ffffffff83ea531e)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/panic.c:panic_on_taint_setup
```
```
In kernel/params.c (ffffffff8111ab55)
Location: include/linux/kstrtox.h:30
Inline: True
```
```
In kernel/ksysfs.c (ffffffff81125f31)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/ksysfs.c:kexec_crash_size_store
```
```
In kernel/power/main.c (ffffffff8117fdc4)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:sync_on_suspend_store
  - kernel/power/main.c:pm_async_store
```
```
In kernel/rcu/tree.c (ffffffff811b0840)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
```
In kernel/cgroup/misc.c (ffffffff8121f568)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_max_write
```
```
In kernel/trace/trace.c (ffffffff8126790d)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
```
```
In kernel/trace/trace_functions.c (ffffffff81279910)
Location: include/linux/kstrtox.h:30
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff8128b1d2)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812922b9)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_parse_num
```
```
In kernel/trace/trace_events_hist.c (ffffffff812a069d)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_assignment
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ac648)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
```
```
In kernel/trace/trace_probe.c (ffffffff812b4743)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:find_fetch_type
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b9ddb)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
```
```
In kernel/trace/trace_boot.c (ffffffff83eb7041)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
```
In kernel/events/core.c (ffffffff8133a470)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
```
```
In mm/backing-dev.c (ffffffff81396a4d)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/backing-dev.c:read_ahead_kb_store
```
```
In mm/hugetlb.c (ffffffff8140aa68)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_mempolicy_store
  - mm/hugetlb.c:nr_hugepages_store
```
```
In mm/ksm.c (ffffffff8141f774)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/ksm.c:merge_across_nodes_store
```
```
In mm/slub.c (ffffffff814246a9)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/slub.c:min_partial_store
```
```
In mm/kfence/core.c (ffffffff8142f702)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/kfence/core.c:param_set_sample_interval
```
```
In mm/huge_memory.c (ffffffff8143b744)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/huge_memory.c:use_zero_page_store
```
```
In mm/khugepaged.c (ffffffff814457f4)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/khugepaged.c:max_ptes_shared_store
  - mm/khugepaged.c:max_ptes_swap_store
  - mm/khugepaged.c:max_ptes_none_store
```
```
In fs/ext4/sysfs.c (ffffffff815ccea3)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/squashfs/super.c (ffffffff815f0d16)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_parse_param
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8165b381)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
```
```
In security/selinux/hooks.c (ffffffff83ed1e7a)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
```
```
In security/apparmor/lsm.c (ffffffff83ed38fa)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_enabled_setup
```
```
In security/integrity/integrity_audit.c (ffffffff83ed45aa)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_setup
```
```
In security/integrity/ima/ima_policy.c (ffffffff816fb480)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/blk-sysfs.c (ffffffff81738029)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
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
```
```
In lib/kstrtox.c (0)
Location: include/linux/kstrtox.h:30
Inline: True
```
```
In lib/dynamic_debug.c (ffffffff8188eeb4)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - lib/dynamic_debug.c:param_set_dyndbg_classes
```
```
In drivers/pci/pci-sysfs.c (ffffffff818eabd2)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
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
```
```
In drivers/video/backlight/backlight.c (ffffffff819349a6)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
```
```
In drivers/acpi/osl.c (ffffffff83ee0c65)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/acpi/osl.c:setup_acpi_rsdp
```
```
In drivers/acpi/sysfs.c (ffffffff81973bcc)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:counter_set
```
```
In drivers/tty/sysrq.c (ffffffff81a5a56e)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
```
```
In drivers/base/core.c (ffffffff81adfce6)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_ulong
```
```
In drivers/mfd/aat2870-core.c (ffffffff81b4ae03)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
```
```
In drivers/nvdimm/core.c (ffffffff81b4f30d)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nd_size_select_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff81b55876)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:align_store
```
```
In drivers/dax/bus.c (ffffffff81b66771)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/dax/bus.c:align_store
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81b861a3)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/scsi/sd.c (ffffffff81b8e70a)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/scsi/sd.c:max_write_same_blocks_store
```
```
In drivers/rtc/sysfs.c (ffffffff81cbeae6)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:max_user_freq_store
```
```
In drivers/md/md.c (ffffffff81cfe3f5)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:chunk_size_store
```
```
In drivers/md/md-bitmap.c (ffffffff81d03c8a)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff81d22a79)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
```
```
In drivers/leds/led-class.c (ffffffff81d5efca)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/leds/led-class.c:brightness_store
```
```
In net/core/net-sysfs.c (ffffffff81e0af78)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
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
```
```
In net/ipv4/tcp.c (ffffffff83f0e65a)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp.c:set_thash_entries
```
```
In net/ipv4/udp.c (ffffffff83f0ee8a)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - net/ipv4/udp.c:set_uhash_entries
```
```
In net/rfkill/core.c (ffffffff81fdb3b0)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
```
```
In net/dns_resolver/dns_key.c (ffffffff81fe1bf1)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
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
In arch/x86/events/core.c (ffffffff81005861)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/events/core.c:set_attr_rdpmc
```
```
In arch/x86/events/intel/core.c (ffffffff81011071)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106a603)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107cbde)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810873f4)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mon_config_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mon_config_write
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8108ec6d)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
```
```
In arch/x86/kernel/early_printk.c (ffffffff836b8612)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
```
```
In arch/x86/kernel/check.c (ffffffff836bb409)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
```
```
In kernel/panic.c (ffffffff836c96be)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/panic.c:panic_on_taint_setup
```
```
In kernel/params.c (ffffffff81127dc5)
Location: include/linux/kstrtox.h:30
Inline: True
```
```
In kernel/ksysfs.c (ffffffff81133421)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/ksysfs.c:kexec_crash_size_store
```
```
In kernel/power/main.c (ffffffff81190b94)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:sync_on_suspend_store
  - kernel/power/main.c:pm_async_store
```
```
In kernel/rcu/tree.c (ffffffff811c2810)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
```
In kernel/cgroup/misc.c (ffffffff81235698)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_max_write
```
```
In kernel/trace/trace.c (ffffffff8127e71d)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
```
```
In kernel/trace/trace_functions.c (ffffffff81291350)
Location: include/linux/kstrtox.h:30
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff812a8122)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
```
```
In kernel/trace/trace_events_filter.c (ffffffff812abaef)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812af519)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_parse_num
```
```
In kernel/trace/trace_events_hist.c (ffffffff812be489)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_assignment
```
```
In kernel/trace/trace_kprobe.c (ffffffff812d02f6)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
```
```
In kernel/trace/trace_probe.c (ffffffff812d70b3)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:find_fetch_type
```
```
In kernel/trace/trace_uprobe.c (ffffffff812dd5c8)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
```
```
In kernel/trace/trace_boot.c (ffffffff836dc5dd)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
```
In kernel/events/core.c (ffffffff8136b3e8)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
```
```
In mm/backing-dev.c (ffffffff813c9bed)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/backing-dev.c:read_ahead_kb_store
```
```
In mm/hugetlb.c (ffffffff8143e118)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_mempolicy_store
  - mm/hugetlb.c:nr_hugepages_store
```
```
In mm/ksm.c (ffffffff81454764)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/ksm.c:merge_across_nodes_store
```
```
In mm/slub.c (ffffffff81459949)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/slub.c:min_partial_store
```
```
In mm/kfence/core.c (ffffffff81464922)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/kfence/core.c:param_set_sample_interval
```
```
In mm/huge_memory.c (ffffffff81471154)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/huge_memory.c:use_zero_page_store
```
```
In mm/khugepaged.c (ffffffff8147ae54)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/khugepaged.c:max_ptes_shared_store
  - mm/khugepaged.c:max_ptes_swap_store
  - mm/khugepaged.c:max_ptes_none_store
```
```
In fs/ext4/sysfs.c (ffffffff81604e59)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/squashfs/super.c (ffffffff81628d72)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_parse_param
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff81693d09)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
```
```
In security/selinux/hooks.c (ffffffff836f6f5a)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
```
```
In security/apparmor/lsm.c (ffffffff836f877a)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_enabled_setup
```
```
In security/integrity/integrity_audit.c (ffffffff836f96ea)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_setup
```
```
In security/integrity/ima/ima_policy.c (ffffffff817355b2)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/blk-sysfs.c (ffffffff817745e9)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
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
```
```
In lib/kstrtox.c (0)
Location: include/linux/kstrtox.h:30
Inline: True
```
```
In lib/dynamic_debug.c (ffffffff818d1417)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - lib/dynamic_debug.c:param_set_dyndbg_classes
```
```
In drivers/pci/pci-sysfs.c (ffffffff8192e1a2)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
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
```
```
In drivers/video/backlight/backlight.c (ffffffff81978e66)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
```
```
In drivers/acpi/osl.c (ffffffff83706705)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/acpi/osl.c:setup_acpi_rsdp
```
```
In drivers/acpi/sysfs.c (ffffffff819ba38c)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:counter_set
```
```
In drivers/tty/sysrq.c (ffffffff81aa4b9e)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
```
```
In drivers/base/core.c (ffffffff81b2df06)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_ulong
```
```
In drivers/mfd/aat2870-core.c (ffffffff81b9e253)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
```
```
In drivers/nvdimm/core.c (ffffffff81ba275d)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nd_size_select_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff81ba8dc6)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:align_store
```
```
In drivers/dax/bus.c (ffffffff81bb9b61)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/dax/bus.c:align_store
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81bd9f73)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/scsi/sd.c (ffffffff81be478a)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/scsi/sd.c:max_write_same_blocks_store
```
```
In drivers/rtc/sysfs.c (ffffffff81d263f6)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:max_user_freq_store
```
```
In drivers/md/md.c (ffffffff81d65565)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:chunk_size_store
```
```
In drivers/md/md-bitmap.c (ffffffff81d6cb3a)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff81d8bc79)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d95dd6)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
```
```
In drivers/leds/led-class.c (ffffffff81dc9eba)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/leds/led-class.c:brightness_store
```
```
In net/core/net-sysfs.c (ffffffff81e7e308)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
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
```
```
In net/ipv4/tcp.c (ffffffff83734c6a)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp.c:set_thash_entries
```
```
In net/ipv4/udp.c (ffffffff8373549a)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - net/ipv4/udp.c:set_uhash_entries
```
```
In net/rfkill/core.c (ffffffff82057090)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
```
```
In net/dns_resolver/dns_key.c (ffffffff8205de74)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
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
In arch/x86/events/core.c (ffffffff8100af61)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/events/core.c:set_attr_rdpmc
```
```
In arch/x86/events/intel/core.c (ffffffff810167c1)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81071ad3)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810840be)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108e204)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mon_config_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mon_config_write
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81095ffd)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
```
```
In arch/x86/kernel/early_printk.c (ffffffff838e8f22)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
```
```
In arch/x86/kernel/check.c (ffffffff838ebde9)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
```
```
In kernel/panic.c (ffffffff838fa30e)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/panic.c:panic_on_taint_setup
```
```
In kernel/params.c (ffffffff811323a5)
Location: include/linux/kstrtox.h:30
Inline: True
```
```
In kernel/ksysfs.c (ffffffff8113e381)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/ksysfs.c:kexec_crash_size_store
```
```
In kernel/power/main.c (ffffffff8119f554)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:sync_on_suspend_store
  - kernel/power/main.c:pm_async_store
```
```
In kernel/rcu/tree.c (ffffffff811d2d80)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
```
In kernel/trace/trace.c (ffffffff8129cc3c)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
```
```
In kernel/trace/trace_functions.c (ffffffff812ac960)
Location: include/linux/kstrtox.h:30
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff812c3df2)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
```
```
In kernel/trace/trace_events_filter.c (ffffffff812c7c5b)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812cba59)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_parse_num
```
```
In kernel/trace/trace_events_hist.c (ffffffff812daae9)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_assignment
```
```
In kernel/trace/trace_kprobe.c (ffffffff812edcd3)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
```
```
In kernel/trace/trace_probe.c (ffffffff812f4bc3)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:find_fetch_type
```
```
In kernel/trace/trace_uprobe.c (ffffffff812fb6ac)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
```
```
In kernel/trace/trace_boot.c (ffffffff8390ec0d)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
```
In kernel/events/core.c (ffffffff81394059)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
```
```
In mm/backing-dev.c (ffffffff813f457d)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/backing-dev.c:read_ahead_kb_store
```
```
In mm/slub.c (ffffffff814548c9)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/slub.c:min_partial_store
```
```
In mm/hugetlb.c (ffffffff81477da8)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_mempolicy_store
  - mm/hugetlb.c:nr_hugepages_store
```
```
In mm/ksm.c (ffffffff8148be34)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/ksm.c:advisor_target_scan_time_store
  - mm/ksm.c:advisor_max_pages_to_scan_store
  - mm/ksm.c:advisor_min_pages_to_scan_store
  - mm/ksm.c:advisor_max_cpu_store
  - mm/ksm.c:merge_across_nodes_store
```
```
In mm/kfence/core.c (ffffffff81494312)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/kfence/core.c:param_set_sample_interval
```
```
In mm/huge_memory.c (ffffffff814a0884)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/huge_memory.c:use_zero_page_store
```
```
In mm/khugepaged.c (ffffffff814aa2d4)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - mm/khugepaged.c:max_ptes_shared_store
  - mm/khugepaged.c:max_ptes_swap_store
  - mm/khugepaged.c:max_ptes_none_store
```
```
In fs/ext4/sysfs.c (ffffffff8163db19)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/squashfs/super.c (ffffffff81661f62)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_parse_param
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff816d0309)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
```
```
In security/selinux/hooks.c (ffffffff8392a2ca)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
```
```
In security/apparmor/lsm.c (ffffffff8392bb4a)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_enabled_setup
```
```
In security/integrity/integrity_audit.c (ffffffff8392cb4a)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_setup
```
```
In security/integrity/ima/ima_policy.c (ffffffff81776092)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/blk-sysfs.c (ffffffff817b6979)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
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
```
```
In lib/kstrtox.c (0)
Location: include/linux/kstrtox.h:30
Inline: True
```
```
In lib/dynamic_debug.c (ffffffff81923407)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - lib/dynamic_debug.c:param_set_dyndbg_classes
```
```
In drivers/pci/pci-sysfs.c (ffffffff81976b22)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
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
```
```
In drivers/video/backlight/backlight.c (ffffffff819c2f86)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
```
```
In drivers/acpi/osl.c (ffffffff83939c85)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/acpi/osl.c:setup_acpi_rsdp
```
```
In drivers/acpi/sysfs.c (ffffffff81a049cc)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:counter_set
```
```
In drivers/tty/sysrq.c (ffffffff81af759e)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
```
```
In drivers/base/core.c (ffffffff81b85706)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_ulong
```
```
In drivers/mfd/aat2870-core.c (ffffffff81bf2383)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
```
```
In drivers/nvdimm/core.c (ffffffff81bf691d)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nd_size_select_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff81bfd106)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:align_store
```
```
In drivers/dax/bus.c (ffffffff81c0e1c1)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/dax/bus.c:align_store
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81c2eca3)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/scsi/sd.c (ffffffff81c399fa)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/scsi/sd.c:max_write_same_blocks_store
```
```
In drivers/rtc/sysfs.c (ffffffff81ddc166)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:max_user_freq_store
```
```
In drivers/md/md.c (ffffffff81e1c2e5)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:chunk_size_store
```
```
In drivers/md/md-bitmap.c (ffffffff81e23d6a)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff81e43529)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81e4d8c6)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
```
```
In drivers/leds/led-class.c (ffffffff81e8274a)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - drivers/leds/led-class.c:brightness_store
```
```
In net/core/net-sysfs.c (ffffffff81f3f218)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
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
```
```
In net/ipv4/tcp.c (ffffffff8396922a)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp.c:set_thash_entries
```
```
In net/ipv4/udp.c (ffffffff83969b0a)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - net/ipv4/udp.c:set_uhash_entries
```
```
In net/rfkill/core.c (ffffffff82129954)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
```
```
In net/dns_resolver/dns_key.c (ffffffff82130b04)
Location: include/linux/kstrtox.h:30
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
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
In kernel/params.c (ffff800010125afc)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/params.c:param_set_ulong
```
```
In kernel/ksysfs.c (ffff80001012c838)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/ksysfs.c:kexec_crash_size_store
```
```
In kernel/power/main.c (ffff80001016ede0)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:pm_async_store
```
```
In kernel/rcu/tree.c (ffff80001018bfbc)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
```
In kernel/trace/trace.c (ffff8000102208e0)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
```
```
In kernel/trace/trace_functions.c (ffff80001022fcdc)
Location: include/linux/kernel.h:361
Inline: True
```
```
In kernel/trace/trace_events.c (ffff80001023cbec)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
```
```
In kernel/trace/trace_events_trigger.c (ffff8000102425bc)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_events_hist.c (ffff800010244c4c)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_map_size
```
```
In kernel/trace/trace_kprobe.c (ffff8000102509a4)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
```
In kernel/trace/trace_probe.c (ffff800010256210)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:find_fetch_type
```
```
In kernel/trace/trace_uprobe.c (ffff800010258da8)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In kernel/events/core.c (ffff800010294604)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
```
```
In mm/backing-dev.c (ffff8000102dd5c4)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/backing-dev.c:read_ahead_kb_store
```
```
In mm/hugetlb.c (ffff80001032f3b8)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store_common
```
```
In mm/ksm.c (ffff80001033dfc0)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
```
```
In mm/slub.c (ffff800010343c34)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/slub.c:min_partial_store
```
```
In mm/huge_memory.c (ffff8000103566cc)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/huge_memory.c:single_hugepage_flag_store
```
```
In mm/khugepaged.c (ffff80001035b868)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
```
```
In fs/ext4/sysfs.c (ffff8000104c1088)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In security/keys/trusted.c (ffff80001053addc)
Location: include/linux/kernel.h:361
Inline: True
```
```
In security/selinux/hooks.c (ffff80001146a2ac)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
```
```
In security/apparmor/lsm.c (ffff80001146b6a4)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_enabled_setup
```
```
In security/integrity/integrity_audit.c (ffff80001146be10)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_setup
```
```
In security/integrity/ima/ima_policy.c (ffff8000105b17bc)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/blk-sysfs.c (ffff8000105e6130)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
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
```
```
In lib/kstrtox.c (ffff80001063a44c)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
```
```
In drivers/pci/pci-sysfs.c (ffff8000106ee214)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
```
```
In drivers/pci/msi.c (ffff800010713b28)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
```
```
In drivers/video/backlight/backlight.c (ffff8000107421c4)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
```
```
In drivers/acpi/osl.c (ffff80001147c890)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/acpi/osl.c:setup_acpi_rsdp
```
```
In drivers/acpi/sysfs.c (0)
Location: include/linux/kernel.h:361
Inline: True
```
```
In drivers/tty/sysrq.c (ffff800010863c40)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
```
```
In drivers/base/core.c (ffff8000108e2ed4)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_ulong
```
```
In drivers/mfd/aat2870-core.c (ffff80001094c7c4)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
```
```
In drivers/nvdimm/core.c (ffff80001095070c)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nd_size_select_store
```
```
In drivers/scsi/scsi_sysfs.c (ffff80001097f35c)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/scsi/sd.c (ffff800010986760)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/scsi/sd.c:max_write_same_blocks_store
```
```
In drivers/rtc/sysfs.c (ffff800010aabed4)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:max_user_freq_store
```
```
In drivers/md/md.c (ffff800010aeb9e8)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:chunk_size_store
```
```
In drivers/md/md-bitmap.c (ffff800010af6544)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
```
```
In drivers/edac/edac_mc_sysfs.c (ffff800010b117d4)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
```
```
In drivers/mmc/core/block.c (ffff800010b404c4)
Location: include/linux/kernel.h:361
Inline: True
```
```
In drivers/leds/led-class.c (ffff800010b49780)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/leds/led-class.c:brightness_store
```
```
In drivers/memory/brcmstb_dpfe.c (ffff800010b8a954)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/memory/brcmstb_dpfe.c:store_refresh
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b98bd0)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_probe_cluster
```
```
In net/core/net-sysfs.c (ffff800010c0a158)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
```
```
In net/ipv4/tcp.c (ffff8000114b24b0)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/ipv4/tcp.c:set_thash_entries
```
```
In net/ipv4/udp.c (ffff8000114b2a08)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/ipv4/udp.c:set_uhash_entries
```
```
In net/rfkill/core.c (ffff800010d6cd1c)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
```
```
In net/dns_resolver/dns_key.c (ffff800010d72a50)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
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
In kernel/params.c (c0378718)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/params.c:param_set_ulong
```
```
In kernel/ksysfs.c (c037ca64)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/ksysfs.c:kexec_crash_size_store
```
```
In kernel/power/main.c (c03b99ac)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:pm_async_store
```
```
In kernel/rcu/tree.c (c03dc250)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
```
In kernel/trace/trace.c (c045e664)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
```
```
In kernel/trace/trace_functions.c (c046baac)
Location: include/linux/kernel.h:361
Inline: True
```
```
In kernel/trace/trace_events.c (c04784ec)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
```
```
In kernel/trace/trace_events_trigger.c (c047df24)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_kprobe.c (c04840c4)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
```
In kernel/trace/trace_probe.c (c0489ab0)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:find_fetch_type
```
```
In kernel/trace/trace_uprobe.c (c048c850)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In kernel/events/core.c (c04c3eac)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
```
```
In mm/backing-dev.c (c0502a90)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/backing-dev.c:read_ahead_kb_store
```
```
In mm/ksm.c (c05443b4)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
```
```
In mm/slub.c (c0548fa4)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/slub.c:min_partial_store
```
```
In fs/ext4/sysfs.c (c0684cf0)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In security/keys/trusted.c (c06f0948)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/keys/trusted.c:getoptions
  - security/keys/trusted.c:getoptions
  - security/keys/trusted.c:getoptions
```
```
In security/selinux/hooks.c (c1542e84)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
```
```
In security/apparmor/lsm.c (c1544364)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_enabled_setup
```
```
In security/integrity/integrity_audit.c (c1544ac0)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_setup
```
```
In security/integrity/ima/ima_policy.c (c0760af8)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/blk-sysfs.c (c0792ee0)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
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
```
```
In lib/kstrtox.c (c07dfa20)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
```
```
In drivers/pci/pci-sysfs.c (c08892cc)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
```
```
In drivers/pci/msi.c (c089e5c4)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
```
```
In drivers/video/backlight/backlight.c (c08c6b74)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
```
```
In drivers/tty/sysrq.c (c09698a8)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
```
```
In drivers/base/core.c (c09d1a90)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_ulong
```
```
In drivers/mfd/aat2870-core.c (c0a36778)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
```
```
In drivers/scsi/scsi_sysfs.c (c0a50784)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/scsi/sd.c (c0a575f0)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/scsi/sd.c:max_write_same_blocks_store
```
```
In drivers/rtc/sysfs.c (c0b8a4ac)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:max_user_freq_store
```
```
In drivers/watchdog/aspeed_wdt.c (c0bc2a3c)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/watchdog/aspeed_wdt.c:access_cs0_store
```
```
In drivers/md/md.c (c0bcbf50)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:chunk_size_store
```
```
In drivers/md/md-bitmap.c (c0bd7ff8)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
```
```
In drivers/edac/edac_mc_sysfs.c (c0befc00)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
```
```
In drivers/mmc/core/block.c (c0c1aad8)
Location: include/linux/kernel.h:361
Inline: True
```
```
In drivers/leds/led-class.c (c0c32c08)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/leds/led-class.c:brightness_store
```
```
In net/core/net-sysfs.c (c0d22508)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
```
```
In net/ipv4/tcp.c (c15b7784)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/ipv4/tcp.c:set_thash_entries
```
```
In net/ipv4/udp.c (c15b7cc0)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/ipv4/udp.c:set_uhash_entries
```
```
In net/rfkill/core.c (c0e6a6fc)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
```
```
In net/dns_resolver/dns_key.c (c0e6f920)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
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
In arch/powerpc/platforms/pseries/vio.c (c000000000100f64)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/vio.c:cmo_desired_store
```
```
In arch/powerpc/kvm/book3s_hv_builtin.c (c000000001365130)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_builtin.c:early_parse_kvm_cma_resv
```
```
In kernel/params.c (c00000000016fa0c)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/params.c:param_set_ulong
```
```
In kernel/ksysfs.c (c00000000017562c)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/ksysfs.c:kexec_crash_size_store
```
```
In kernel/power/main.c (c0000000001c69cc)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:pm_async_store
```
```
In kernel/rcu/tree.c (c0000000001e9458)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
```
In kernel/trace/trace.c (c0000000002a4ab0)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
```
```
In kernel/trace/trace_functions.c (c0000000002b9c50)
Location: include/linux/kernel.h:361
Inline: True
```
```
In kernel/trace/trace_events.c (c0000000002cc060)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
```
```
In kernel/trace/trace_events_trigger.c (c0000000002d4b40)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_events_hist.c (c0000000002d89d8)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_map_size
```
```
In kernel/trace/trace_kprobe.c (c0000000002ef250)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
```
In kernel/trace/trace_probe.c (c0000000002f6cb4)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:find_fetch_type
```
```
In kernel/trace/trace_uprobe.c (c0000000002fc6a0)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In kernel/events/core.c (c000000000342fd8)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
```
```
In mm/backing-dev.c (c00000000039cdcc)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/backing-dev.c:read_ahead_kb_store
```
```
In mm/hugetlb.c (c000000000406150)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store_common
```
```
In mm/ksm.c (c0000000004197fc)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
```
```
In mm/slub.c (c0000000004214b8)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/slub.c:min_partial_store
```
```
In mm/huge_memory.c (c00000000043da44)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/huge_memory.c:single_hugepage_flag_store
```
```
In mm/khugepaged.c (c0000000004452cc)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
```
```
In fs/ext4/sysfs.c (c0000000005f79fc)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In security/keys/trusted.c (c0000000006895e4)
Location: include/linux/kernel.h:361
Inline: True
```
```
In security/selinux/hooks.c (c000000001398790)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
```
```
In security/apparmor/lsm.c (c00000000139a13c)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_enabled_setup
```
```
In security/integrity/integrity_audit.c (c00000000139ab20)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_setup
```
```
In security/integrity/ima/ima_policy.c (c000000000731878)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/blk-sysfs.c (c00000000077a630)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
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
```
```
In lib/kstrtox.c (c0000000007e121c)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
```
```
In drivers/pci/pci-sysfs.c (c00000000086a89c)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
```
```
In drivers/pci/msi.c (c00000000088347c)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
```
```
In drivers/video/backlight/backlight.c (c0000000008a2984)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
```
```
In drivers/tty/sysrq.c (c000000000902e98)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
```
```
In drivers/base/core.c (c000000000977c24)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_ulong
```
```
In drivers/mfd/aat2870-core.c (c0000000009f85bc)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
```
```
In drivers/nvdimm/core.c (c0000000009fd09c)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nd_size_select_store
```
```
In drivers/scsi/scsi_sysfs.c (c000000000a38360)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/scsi/sd.c (c000000000a43f90)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/scsi/sd.c:max_write_same_blocks_store
```
```
In drivers/rtc/sysfs.c (c000000000b8e084)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:max_user_freq_store
```
```
In drivers/md/md.c (c000000000bd8ed8)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:chunk_size_store
```
```
In drivers/md/md-bitmap.c (c000000000be3d44)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
```
```
In drivers/edac/edac_mc_sysfs.c (c000000000c058c4)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
```
```
In drivers/leds/led-class.c (c000000000c3ddd0)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/leds/led-class.c:brightness_store
```
```
In net/core/net-sysfs.c (c000000000cf6c64)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
```
```
In net/ipv4/tcp.c (c0000000013c3458)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/ipv4/tcp.c:set_thash_entries
```
```
In net/ipv4/udp.c (c0000000013c3b5c)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/ipv4/udp.c:set_uhash_entries
```
```
In net/rfkill/core.c (c000000000eaa914)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
```
```
In net/dns_resolver/dns_key.c (c000000000eb1ac4)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
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
In kernel/params.c (ffffffe0000dd72e)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/params.c:param_set_ulong
```
```
In kernel/power/main.c (ffffffe00010d72e)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/power/main.c:pm_freeze_timeout_store
```
```
In kernel/rcu/tree.c (ffffffe0001210ea)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
```
In kernel/trace/trace.c (ffffffe00017d294)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
```
```
In kernel/trace/trace_functions.c (ffffffe000187ec8)
Location: include/linux/kernel.h:361
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffe000192cd6)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
```
```
In kernel/trace/trace_events_trigger.c (ffffffe0001972ac)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/events/core.c (ffffffe0001c4d04)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
```
```
In mm/backing-dev.c (ffffffe0001f5b64)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/backing-dev.c:read_ahead_kb_store
```
```
In mm/hugetlb.c (ffffffe00022d004)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store
```
```
In mm/ksm.c (ffffffe000233364)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
```
```
In mm/slub.c (ffffffe00023746e)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/slub.c:min_partial_store
```
```
In fs/ext4/sysfs.c (ffffffe00033c6aa)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In security/keys/trusted.c (ffffffe000398d36)
Location: include/linux/kernel.h:361
Inline: True
```
```
In security/selinux/hooks.c (ffffffe000025340)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
```
```
In security/apparmor/lsm.c (ffffffe0000266f2)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_enabled_setup
```
```
In security/integrity/integrity_audit.c (ffffffe000026df8)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_setup
```
```
In security/integrity/ima/ima_policy.c (ffffffe0003f8f5a)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/blk-sysfs.c (ffffffe0004272f4)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
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
```
```
In lib/kstrtox.c (ffffffe000466b4c)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
```
```
In drivers/pci/pci-sysfs.c (ffffffe0004c2650)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
```
```
In drivers/pci/msi.c (ffffffe0004dd6aa)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
```
```
In drivers/tty/sysrq.c (ffffffe00053a74a)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
```
```
In drivers/base/core.c (ffffffe0005783ae)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_ulong
```
```
In drivers/mfd/aat2870-core.c (ffffffe0005bd9d6)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
```
```
In drivers/nvdimm/core.c (ffffffe0005c08cc)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nd_size_select_store
```
```
In drivers/scsi/scsi_sysfs.c (ffffffe0005e3b42)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/scsi/sd.c (ffffffe0005ecbe8)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/scsi/sd.c:max_write_same_blocks_store
```
```
In drivers/rtc/sysfs.c (ffffffe0006b67d6)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:max_user_freq_store
```
```
In drivers/md/md.c (ffffffe0006e247e)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:chunk_size_store
```
```
In drivers/md/md-bitmap.c (ffffffe0006e91b8)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffe0006fe5cc)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
```
```
In drivers/mmc/core/block.c (ffffffe000717266)
Location: include/linux/kernel.h:361
Inline: True
```
```
In drivers/leds/led-class.c (ffffffe00071cdca)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/leds/led-class.c:brightness_store
```
```
In net/core/net-sysfs.c (ffffffe0007877f8)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
```
```
In net/ipv4/tcp.c (ffffffe00004118a)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/ipv4/tcp.c:set_thash_entries
```
```
In net/ipv4/udp.c (ffffffe0000416d0)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/ipv4/udp.c:set_uhash_entries
```
```
In net/rfkill/core.c (ffffffe00089eaea)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
```
```
In net/dns_resolver/dns_key.c (ffffffe0008a2fea)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
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
In arch/x86/events/core.c (ffffffff81005e69)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/events/core.c:set_attr_rdpmc
```
```
In arch/x86/events/intel/core.c (ffffffff8100c269)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810445cb)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810514ce)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056413)
Location: include/linux/kernel.h:361
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105eda4)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
```
```
In arch/x86/kernel/early_printk.c (ffffffff828a8f24)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:setup_early_printk
```
```
In arch/x86/kernel/check.c (ffffffff828aa59f)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828abf43)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_parse_options
```
```
In kernel/params.c (ffffffff810c1005)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/params.c:param_set_ulong
```
```
In kernel/ksysfs.c (ffffffff810c7969)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/ksysfs.c:kexec_crash_size_store
```
```
In kernel/power/main.c (ffffffff81100e3c)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:pm_async_store
```
```
In kernel/rcu/tree.c (ffffffff8111ec56)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
```
In kernel/trace/trace.c (ffffffff8119de7f)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
```
```
In kernel/trace/trace_functions.c (ffffffff811aa736)
Location: include/linux/kernel.h:361
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff811b5eb8)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811bb30d)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_events_hist.c (ffffffff811bd4d9)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_map_size
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c8735)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
```
In kernel/trace/trace_probe.c (ffffffff811ce4a0)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:find_fetch_type
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d19ba)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In kernel/events/core.c (ffffffff81201c0b)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
```
```
In mm/backing-dev.c (ffffffff81240bd5)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/backing-dev.c:read_ahead_kb_store
```
```
In mm/hugetlb.c (ffffffff81289fdb)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store_common
```
```
In mm/ksm.c (ffffffff81296dcc)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
```
```
In mm/slub.c (ffffffff8129bc21)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/slub.c:min_partial_store
```
```
In mm/huge_memory.c (ffffffff812ad811)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/huge_memory.c:single_hugepage_flag_store
```
```
In mm/khugepaged.c (ffffffff812b2f0c)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
```
```
In fs/ext4/sysfs.c (ffffffff813e0958)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In security/keys/trusted.c (ffffffff81447d72)
Location: include/linux/kernel.h:361
Inline: True
```
```
In security/selinux/hooks.c (ffffffff828d91aa)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
```
```
In security/apparmor/lsm.c (ffffffff828da3a8)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_enabled_setup
```
```
In security/integrity/integrity_audit.c (ffffffff828da9e1)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_setup
```
```
In security/integrity/ima/ima_policy.c (ffffffff814b1524)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/blk-sysfs.c (ffffffff814e08d2)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
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
```
```
In lib/kstrtox.c (ffffffff8152659b)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157d750)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
```
```
In drivers/pci/msi.c (ffffffff8159dd40)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
```
```
In drivers/video/backlight/backlight.c (ffffffff815af69e)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
```
```
In drivers/acpi/osl.c (ffffffff828e23de)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/acpi/osl.c:setup_acpi_rsdp
```
```
In drivers/acpi/sysfs.c (ffffffff815dd35e)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:counter_set
```
```
In drivers/tty/sysrq.c (ffffffff81656856)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
```
```
In drivers/base/core.c (ffffffff816be69e)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_ulong
```
```
In drivers/nvdimm/core.c (ffffffff81704f31)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nd_size_select_store
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8172cb8b)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/scsi/sd.c (ffffffff81734802)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/scsi/sd.c:max_write_same_blocks_store
```
```
In drivers/rtc/sysfs.c (ffffffff8181c2be)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:max_user_freq_store
```
```
In drivers/md/md.c (ffffffff8183f962)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:chunk_size_store
```
```
In drivers/md/md-bitmap.c (ffffffff818483f2)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff8185f5b9)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
```
```
In net/core/net-sysfs.c (ffffffff81905b90)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
```
```
In net/ipv4/tcp.c (ffffffff82906686)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/ipv4/tcp.c:set_thash_entries
```
```
In net/ipv4/udp.c (ffffffff82906ae9)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/ipv4/udp.c:set_uhash_entries
```
```
In net/rfkill/core.c (ffffffff81a3b698)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
```
```
In net/dns_resolver/dns_key.c (ffffffff81a407af)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
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
In arch/x86/events/core.c (ffffffff810045e9)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/events/core.c:set_attr_rdpmc
```
```
In arch/x86/events/intel/core.c (ffffffff8100aa99)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81033beb)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8104062e)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81046623)
Location: include/linux/kernel.h:361
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8104f0d4)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
```
```
In arch/x86/kernel/early_printk.c (ffffffff828a0ff7)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:setup_early_printk
```
```
In arch/x86/kernel/check.c (ffffffff828a2868)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828a420a)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_parse_options
```
```
In kernel/params.c (ffffffff810af7f5)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/params.c:param_set_ulong
```
```
In kernel/ksysfs.c (ffffffff810b6189)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/ksysfs.c:kexec_crash_size_store
```
```
In kernel/power/main.c (ffffffff810f10ac)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:pm_async_store
```
```
In kernel/rcu/tree.c (ffffffff8110fc16)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
```
In kernel/trace/trace.c (ffffffff81190edf)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
```
```
In kernel/trace/trace_functions.c (ffffffff8119d696)
Location: include/linux/kernel.h:361
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff811a8cb8)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811ae0ed)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_events_hist.c (ffffffff811b02b9)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_map_size
```
```
In kernel/trace/trace_kprobe.c (ffffffff811bb515)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
```
In kernel/trace/trace_probe.c (ffffffff811c1270)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:find_fetch_type
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c478a)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In kernel/events/core.c (ffffffff811f495b)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
```
```
In mm/backing-dev.c (ffffffff81233bd5)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/backing-dev.c:read_ahead_kb_store
```
```
In mm/hugetlb.c (ffffffff8127be0b)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store_common
```
```
In mm/ksm.c (ffffffff812889dc)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
```
```
In mm/slub.c (ffffffff8128d7e1)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/slub.c:min_partial_store
```
```
In mm/huge_memory.c (ffffffff8129ee91)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/huge_memory.c:single_hugepage_flag_store
```
```
In mm/khugepaged.c (ffffffff812a428c)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
```
```
In fs/ext4/sysfs.c (ffffffff813d13d8)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In security/keys/trusted.c (ffffffff814387c2)
Location: include/linux/kernel.h:361
Inline: True
```
```
In security/selinux/hooks.c (ffffffff828d18c6)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
```
```
In security/apparmor/lsm.c (ffffffff828d2ac4)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_enabled_setup
```
```
In security/integrity/integrity_audit.c (ffffffff828d30fd)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_setup
```
```
In security/integrity/ima/ima_policy.c (ffffffff814a1f44)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/blk-sysfs.c (ffffffff814d1272)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
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
```
```
In lib/kstrtox.c (ffffffff8151687b)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
```
```
In drivers/pci/pci-sysfs.c (ffffffff8156c520)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
```
```
In drivers/pci/msi.c (ffffffff8158ced0)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
```
```
In drivers/video/backlight/backlight.c (ffffffff8159e82e)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
```
```
In drivers/acpi/osl.c (ffffffff828da3f7)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/acpi/osl.c:setup_acpi_rsdp
```
```
In drivers/acpi/sysfs.c (ffffffff815c899e)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:counter_set
```
```
In drivers/tty/sysrq.c (ffffffff81636be6)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
```
```
In drivers/base/core.c (ffffffff8169994e)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_ulong
```
```
In drivers/nvdimm/core.c (ffffffff816d89b1)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nd_size_select_store
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81705fab)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/scsi/sd.c (ffffffff817164a2)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/scsi/sd.c:max_write_same_blocks_store
```
```
In drivers/rtc/sysfs.c (ffffffff817e39ae)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:max_user_freq_store
```
```
In drivers/md/md.c (ffffffff81806fc2)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:chunk_size_store
```
```
In drivers/md/md-bitmap.c (ffffffff8180fa52)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff81826b89)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
```
```
In net/core/net-sysfs.c (ffffffff818bf9c0)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
```
```
In net/ipv4/tcp.c (ffffffff828fe9d4)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/ipv4/tcp.c:set_thash_entries
```
```
In net/ipv4/udp.c (ffffffff828fee37)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/ipv4/udp.c:set_uhash_entries
```
```
In net/rfkill/core.c (ffffffff819f82b8)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
```
```
In net/dns_resolver/dns_key.c (ffffffff819fd39f)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
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
In arch/x86/events/core.c (ffffffff81005e29)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/events/core.c:set_attr_rdpmc
```
```
In arch/x86/events/intel/core.c (ffffffff8100c229)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8104440b)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8105137e)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056843)
Location: include/linux/kernel.h:361
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105f1d4)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
```
```
In arch/x86/kernel/early_printk.c (ffffffff828bbe23)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:setup_early_printk
```
```
In arch/x86/kernel/check.c (ffffffff828bd49e)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828bee42)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_parse_options
```
```
In kernel/params.c (ffffffff810c0555)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/params.c:param_set_ulong
```
```
In kernel/ksysfs.c (ffffffff810c6eb9)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/ksysfs.c:kexec_crash_size_store
```
```
In kernel/power/main.c (ffffffff810fe07c)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:pm_async_store
```
```
In kernel/rcu/tree.c (ffffffff8111cb46)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
```
In kernel/trace/trace.c (ffffffff8119bc4f)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
```
```
In kernel/trace/trace_functions.c (ffffffff811a8506)
Location: include/linux/kernel.h:361
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff811b3c88)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811b90dd)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_events_hist.c (ffffffff811bb2a9)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_map_size
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c6505)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
```
In kernel/trace/trace_probe.c (ffffffff811cc270)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:find_fetch_type
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cf78a)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In kernel/events/core.c (ffffffff811ff9db)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
```
```
In mm/backing-dev.c (ffffffff8123e975)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/backing-dev.c:read_ahead_kb_store
```
```
In mm/hugetlb.c (ffffffff81287deb)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store_common
```
```
In mm/ksm.c (ffffffff81294bdc)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
```
```
In mm/slub.c (ffffffff81299a31)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/slub.c:min_partial_store
```
```
In mm/huge_memory.c (ffffffff812ab621)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/huge_memory.c:single_hugepage_flag_store
```
```
In mm/khugepaged.c (ffffffff812b0d1c)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
```
```
In fs/ext4/sysfs.c (ffffffff813ddcd8)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In security/keys/trusted.c (ffffffff81443e12)
Location: include/linux/kernel.h:361
Inline: True
```
```
In security/selinux/hooks.c (ffffffff828ebf2a)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
```
```
In security/apparmor/lsm.c (ffffffff828ed11c)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_enabled_setup
```
```
In security/integrity/integrity_audit.c (ffffffff828ed755)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_setup
```
```
In security/integrity/ima/ima_policy.c (ffffffff814ad5b4)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/blk-sysfs.c (ffffffff814dc962)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
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
```
```
In lib/kstrtox.c (ffffffff8152262b)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157d610)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
```
```
In drivers/pci/msi.c (ffffffff8159e2c0)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
```
```
In drivers/video/backlight/backlight.c (ffffffff815afc2e)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
```
```
In drivers/acpi/osl.c (ffffffff828f526e)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/acpi/osl.c:setup_acpi_rsdp
```
```
In drivers/acpi/sysfs.c (ffffffff815e297e)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:counter_set
```
```
In drivers/tty/sysrq.c (ffffffff81684c16)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
```
```
In drivers/base/core.c (ffffffff816ecb6e)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_ulong
```
```
In drivers/mfd/aat2870-core.c (ffffffff81740f7b)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
```
```
In drivers/nvdimm/core.c (ffffffff81743d01)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nd_size_select_store
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8176b95b)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/scsi/sd.c (ffffffff81774f92)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/scsi/sd.c:max_write_same_blocks_store
```
```
In drivers/rtc/sysfs.c (ffffffff8185d79e)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:max_user_freq_store
```
```
In drivers/md/md.c (ffffffff8188ef92)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:chunk_size_store
```
```
In drivers/md/md-bitmap.c (ffffffff81897a22)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff818aebe9)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
```
```
In drivers/leds/led-class.c (ffffffff818d9832)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/leds/led-class.c:brightness_store
```
```
In net/core/net-sysfs.c (ffffffff81956bc0)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
```
```
In net/ipv4/tcp.c (ffffffff8291bf69)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/ipv4/tcp.c:set_thash_entries
```
```
In net/ipv4/udp.c (ffffffff8291c3cc)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/ipv4/udp.c:set_uhash_entries
```
```
In net/rfkill/core.c (ffffffff81aa7548)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
```
```
In net/dns_resolver/dns_key.c (ffffffff81aac65f)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
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
In arch/x86/events/core.c (ffffffff81005f89)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/events/core.c:set_attr_rdpmc
```
```
In arch/x86/events/intel/core.c (ffffffff8100c459)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8104580b)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810527be)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:store_threshold_limit
  - arch/x86/kernel/cpu/mce/amd.c:store_interrupt_enable
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81057d93)
Location: include/linux/kernel.h:361
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81060734)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
```
```
In arch/x86/kernel/early_printk.c (ffffffff828bef5a)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:setup_early_printk
```
```
In arch/x86/kernel/check.c (ffffffff828c05eb)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:set_corruption_check_period
  - arch/x86/kernel/check.c:set_corruption_check
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828c1f8f)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_parse_options
```
```
In kernel/params.c (ffffffff810c8985)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/params.c:param_set_ulong
```
```
In kernel/ksysfs.c (ffffffff810cf379)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/ksysfs.c:kexec_crash_size_store
```
```
In kernel/power/main.c (ffffffff8110933c)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/power/main.c:pm_freeze_timeout_store
  - kernel/power/main.c:pm_debug_messages_store
  - kernel/power/main.c:pm_print_times_store
  - kernel/power/main.c:pm_async_store
```
```
In kernel/rcu/tree.c (ffffffff811296c6)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
```
In kernel/trace/trace.c (ffffffff811a98ef)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:set_tracing_thresh
  - kernel/trace/trace.c:trace_pid_write
```
```
In kernel/trace/trace_functions.c (ffffffff811b62c6)
Location: include/linux/kernel.h:361
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff811c1d28)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811c717d)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c9349)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_map_size
```
```
In kernel/trace/trace_kprobe.c (ffffffff811d4765)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
```
In kernel/trace/trace_probe.c (ffffffff811da4d0)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:find_fetch_type
```
```
In kernel/trace/trace_uprobe.c (ffffffff811dda2a)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In kernel/events/core.c (ffffffff8120ea6b)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
```
```
In mm/backing-dev.c (ffffffff8124e0a5)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/backing-dev.c:read_ahead_kb_store
```
```
In mm/hugetlb.c (ffffffff81296e7b)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store_common
```
```
In mm/ksm.c (ffffffff812a4a4c)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:merge_across_nodes_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
```
```
In mm/slub.c (ffffffff812a9851)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/slub.c:min_partial_store
```
```
In mm/huge_memory.c (ffffffff812bb991)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/huge_memory.c:single_hugepage_flag_store
```
```
In mm/khugepaged.c (ffffffff812c105c)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_max_ptes_swap_store
  - mm/khugepaged.c:khugepaged_max_ptes_none_store
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
```
```
In fs/ext4/sysfs.c (ffffffff813f30f8)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In security/keys/trusted.c (ffffffff8145b142)
Location: include/linux/kernel.h:361
Inline: True
```
```
In security/selinux/hooks.c (ffffffff828f1340)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/selinux/hooks.c:checkreqprot_setup
  - security/selinux/hooks.c:selinux_enabled_setup
  - security/selinux/hooks.c:enforcing_setup
```
```
In security/apparmor/lsm.c (ffffffff828f253e)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_enabled_setup
```
```
In security/integrity/integrity_audit.c (ffffffff828f2b77)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_setup
```
```
In security/integrity/ima/ima_policy.c (ffffffff814c6004)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/blk-sysfs.c (ffffffff814f57d2)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
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
```
```
In lib/kstrtox.c (ffffffff8153bfab)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoul_from_user
```
```
In drivers/pci/pci-sysfs.c (ffffffff81597ac0)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:remove_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/pci-sysfs.c:msi_bus_store
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:broken_parity_status_store
```
```
In drivers/pci/msi.c (ffffffff815b86f0)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
```
```
In drivers/video/backlight/backlight.c (ffffffff815c969e)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:brightness_store
  - drivers/video/backlight/backlight.c:bl_power_store
```
```
In drivers/acpi/osl.c (ffffffff828fa6c6)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/acpi/osl.c:setup_acpi_rsdp
```
```
In drivers/acpi/sysfs.c (ffffffff815fc83e)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:counter_set
```
```
In drivers/tty/sysrq.c (ffffffff8169f226)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_reset_seq_param_set
```
```
In drivers/base/core.c (ffffffff817073ae)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_ulong
```
```
In drivers/mfd/aat2870-core.c (ffffffff8175c3bb)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
```
```
In drivers/nvdimm/core.c (ffffffff8175f151)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nd_size_select_store
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8178709b)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/scsi/sd.c (ffffffff8178ed72)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/scsi/sd.c:max_write_same_blocks_store
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8290fc3b)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
```
In drivers/rtc/sysfs.c (ffffffff81878a0e)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:max_user_freq_store
```
```
In drivers/md/md.c (ffffffff818a9ce2)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:chunk_size_store
```
```
In drivers/md/md-bitmap.c (ffffffff818b3c02)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:space_store
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff818cae79)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:mci_sdram_scrub_rate_store
```
```
In drivers/leds/led-class.c (ffffffff818f6352)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - drivers/leds/led-class.c:brightness_store
```
```
In net/core/net-sysfs.c (ffffffff81977c90)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
```
```
In net/ipv4/tcp.c (ffffffff829229e4)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/ipv4/tcp.c:set_thash_entries
```
```
In net/ipv4/udp.c (ffffffff82922e47)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/ipv4/udp.c:set_uhash_entries
```
```
In net/rfkill/core.c (ffffffff81ab38e8)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
```
```
In net/dns_resolver/dns_key.c (ffffffff81ab89cf)
Location: include/linux/kernel.h:361
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
</details>
</li>
</ul>

## Differences
