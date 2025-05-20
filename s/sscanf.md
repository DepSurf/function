# Function: <code>sscanf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sscanf(const char *buf, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff813f37e0)
Location: lib/vsprintf.c:2688
Inline: False
Direct callers:
  - init/do_mounts.c:name_to_dev_t
  - init/do_mounts.c:name_to_dev_t
  - init/do_mounts.c:name_to_dev_t
  - kernel/workqueue.c:max_active_store
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/power/main.c:wakeup_count_store
  - kernel/power/main.c:pm_trace_store
  - kernel/power/hibernate.c:reserved_size_store
  - kernel/power/hibernate.c:image_size_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - mm/hugetlb.c:hugetlb_nrpages_setup
  - fs/proc/base.c:proc_map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_map_files_lookup
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_disable
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_create
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_answer
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - block/genhd.c:disk_events_poll_msecs_store
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-throttle.c:tg_set_conf
  - block/blk-throttle.c:tg_set_max
  - block/blk-throttle.c:tg_set_max
  - block/cfq-iosched.c:__cfqg_set_weight_device
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci-driver.c:store_remove_id
  - drivers/pci/pci-driver.c:store_new_id
  - drivers/video/fbdev/core/fbsysfs.c:store_bl_curve
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/battery.c:acpi_battery_alarm_store
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_ioapic
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_hpet
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/scsi/scsi_sysfs.c:sdev_store_timeout
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/usb/core/hcd.c:authorized_default_store
  - drivers/usb/core/driver.c:remove_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:authorized_store
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/usb/host/ehci-hcd.c:store_companion
  - drivers/i2c/i2c-core.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core.c:i2c_sysfs_new_device
  - drivers/power/charger-manager.c:charger_externally_control_store
  - drivers/thermal/thermal_core.c:thermal_cooling_device_cur_state_store
  - drivers/thermal/thermal_core.c:trip_point_hyst_store
  - drivers/thermal/thermal_core.c:trip_point_hyst_show
  - drivers/thermal/thermal_core.c:trip_point_temp_show
  - drivers/thermal/thermal_core.c:trip_point_type_show
  - drivers/thermal/thermal_core.c:trip_point_temp_store
  - drivers/thermal/thermal_core.c:passive_store
  - drivers/md/md.c:badblocks_store
  - drivers/md/dm-table.c:dm_read_arg_group
  - drivers/md/dm-table.c:dm_read_arg
  - drivers/md/dm-linear.c:linear_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/cpufreq/cpufreq.c:store_scaling_setspeed
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_boost
  - drivers/cpufreq/cpufreq_ondemand.c:store_sampling_rate_gov_sys
  - drivers/cpufreq/cpufreq_ondemand.c:store_up_threshold_gov_pol
  - drivers/cpufreq/cpufreq_ondemand.c:store_sampling_rate_gov_pol
  - drivers/cpufreq/cpufreq_ondemand.c:store_up_threshold_gov_sys
  - drivers/cpufreq/cpufreq_conservative.c:store_sampling_rate_gov_pol
  - drivers/cpufreq/cpufreq_conservative.c:store_sampling_rate_gov_sys
  - drivers/cpufreq/cpufreq_conservative.c:store_freq_step_gov_pol
  - drivers/cpufreq/cpufreq_conservative.c:store_up_threshold_gov_pol
  - drivers/cpufreq/cpufreq_conservative.c:store_sampling_down_factor_gov_pol
  - drivers/cpufreq/cpufreq_conservative.c:store_up_threshold_gov_sys
  - drivers/cpufreq/cpufreq_conservative.c:store_sampling_down_factor_gov_sys
  - drivers/cpufreq/cpufreq_conservative.c:store_freq_step_gov_sys
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:polling_interval_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/governor_userspace.c:store_freq
  - drivers/extcon/extcon.c:state_store
  - drivers/powercap/powercap_sys.c:show_constraint_min_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_max_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_min_power_uw
  - drivers/powercap/powercap_sys.c:show_constraint_max_power_uw
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:show_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:show_constraint_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/netprio_cgroup.c:write_priomap
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff813f37e0-ffffffff813f3845: sscanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sscanf(const char *buf, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8143b6a0)
Location: lib/vsprintf.c:2882
Inline: False
Direct callers:
  - init/do_mounts.c:name_to_dev_t
  - init/do_mounts.c:name_to_dev_t
  - init/do_mounts.c:name_to_dev_t
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:max_active_store
  - kernel/power/main.c:pm_trace_store
  - kernel/power/main.c:wakeup_count_store
  - kernel/power/hibernate.c:reserved_size_store
  - kernel/power/hibernate.c:image_size_store
  - kernel/livepatch/core.c:klp_write_object_relocations
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_disable
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_answer
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/integrity/evm/evm_secfs.c:evm_write_key
  - block/genhd.c:disk_events_poll_msecs_store
  - block/badblocks.c:badblocks_store
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-throttle.c:tg_set_max
  - block/blk-throttle.c:tg_set_max
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci-driver.c:store_remove_id
  - drivers/pci/pci-driver.c:store_new_id
  - drivers/video/fbdev/core/fbsysfs.c:store_bl_curve
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/battery.c:acpi_battery_alarm_store
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_acpihid
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_hpet
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_ioapic
  - drivers/scsi/scsi_sysfs.c:sdev_store_timeout
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/usb/core/hcd.c:authorized_default_store
  - drivers/usb/core/driver.c:remove_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/usb/core/sysfs.c:authorized_store
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/host/ehci-hcd.c:store_companion
  - drivers/i2c/i2c-core.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core.c:i2c_sysfs_new_device
  - drivers/power/charger-manager.c:charger_externally_control_store
  - drivers/thermal/thermal_core.c:thermal_cooling_device_cur_state_store
  - drivers/thermal/thermal_core.c:passive_store
  - drivers/thermal/thermal_core.c:trip_point_hyst_show
  - drivers/thermal/thermal_core.c:trip_point_hyst_store
  - drivers/thermal/thermal_core.c:trip_point_temp_show
  - drivers/thermal/thermal_core.c:trip_point_temp_store
  - drivers/thermal/thermal_core.c:trip_point_type_show
  - drivers/md/dm-table.c:dm_read_arg_group
  - drivers/md/dm-table.c:dm_read_arg
  - drivers/md/dm-linear.c:linear_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/cpufreq/cpufreq.c:store_scaling_setspeed
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/cpufreq.c:store_boost
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_ondemand.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_ondemand.c:store_up_threshold
  - drivers/cpufreq/cpufreq_ondemand.c:store_io_is_busy
  - drivers/cpufreq/cpufreq_conservative.c:store_freq_step
  - drivers/cpufreq/cpufreq_conservative.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_conservative.c:store_down_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_up_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_governor.c:store_sampling_rate
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:polling_interval_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/governor_userspace.c:store_freq
  - drivers/extcon/extcon.c:state_store
  - drivers/powercap/powercap_sys.c:show_constraint_name
  - drivers/powercap/powercap_sys.c:show_constraint_min_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_max_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_min_power_uw
  - drivers/powercap/powercap_sys.c:show_constraint_max_power_uw
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:show_constraint_power_limit_uw
  - net/core/dev.c:__dev_alloc_name
  - net/core/netprio_cgroup.c:write_priomap
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff8143b6a0-ffffffff8143b705: sscanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sscanf(const char *buf, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81458680)
Location: lib/vsprintf.c:2910
Inline: False
Direct callers:
  - init/do_mounts.c:name_to_dev_t
  - init/do_mounts.c:name_to_dev_t
  - init/do_mounts.c:name_to_dev_t
  - arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:max_active_store
  - kernel/power/main.c:pm_trace_store
  - kernel/power/main.c:wakeup_count_store
  - kernel/power/hibernate.c:reserved_size_store
  - kernel/power/hibernate.c:image_size_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_disable
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_answer
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/integrity/evm/evm_secfs.c:evm_write_key
  - block/genhd.c:disk_events_poll_msecs_store
  - block/badblocks.c:badblocks_store
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-throttle.c:tg_set_max
  - block/blk-throttle.c:tg_set_max
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci-driver.c:store_remove_id
  - drivers/pci/pci-driver.c:store_new_id
  - drivers/video/fbdev/core/fbsysfs.c:store_bl_curve
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/battery.c:acpi_battery_alarm_store
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_acpihid
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_hpet
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_ioapic
  - drivers/scsi/scsi_sysfs.c:sdev_store_timeout
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/usb/core/hcd.c:authorized_default_store
  - drivers/usb/core/driver.c:remove_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/usb/core/sysfs.c:authorized_store
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/host/ehci-hcd.c:store_companion
  - drivers/i2c/i2c-core.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core.c:i2c_sysfs_new_device
  - drivers/power/supply/charger-manager.c:charger_externally_control_store
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_cur_state_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_show
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_show
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_type_show
  - drivers/md/dm-table.c:dm_read_arg_group
  - drivers/md/dm-table.c:dm_read_arg
  - drivers/md/dm-linear.c:linear_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/cpufreq/cpufreq.c:store_scaling_setspeed
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/cpufreq.c:store_boost
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_ondemand.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_ondemand.c:store_up_threshold
  - drivers/cpufreq/cpufreq_ondemand.c:store_io_is_busy
  - drivers/cpufreq/cpufreq_conservative.c:store_freq_step
  - drivers/cpufreq/cpufreq_conservative.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_conservative.c:store_down_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_up_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_governor.c:store_sampling_rate
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:polling_interval_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/governor_userspace.c:store_freq
  - drivers/powercap/powercap_sys.c:show_constraint_name
  - drivers/powercap/powercap_sys.c:show_constraint_min_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_max_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_min_power_uw
  - drivers/powercap/powercap_sys.c:show_constraint_max_power_uw
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:show_constraint_power_limit_uw
  - net/core/dev.c:__dev_alloc_name
  - net/core/netprio_cgroup.c:write_priomap
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81458680-ffffffff814586e5: sscanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sscanf(const char *buf, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff818fa040)
Location: lib/vsprintf.c:3049
Inline: False
Direct callers:
  - arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:max_active_store
  - kernel/power/main.c:pm_trace_store
  - kernel/power/main.c:wakeup_count_store
  - kernel/power/hibernate.c:reserved_size_store
  - kernel/power/hibernate.c:image_size_store
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_answer
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/integrity/evm/evm_secfs.c:evm_write_key
  - block/genhd.c:disk_events_poll_msecs_store
  - block/badblocks.c:badblocks_store
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci-driver.c:remove_id_store
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/video/fbdev/core/fbsysfs.c:store_bl_curve
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/battery.c:acpi_battery_alarm_store
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_acpihid
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_hpet
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_ioapic
  - drivers/scsi/scsi_sysfs.c:sdev_store_timeout
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/spi/spi.c:spi_slave_store
  - drivers/usb/core/hcd.c:authorized_default_store
  - drivers/usb/core/driver.c:remove_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/usb/core/sysfs.c:authorized_store
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/host/ehci-hcd.c:store_companion
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/power/supply/charger-manager.c:charger_externally_control_store
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_cur_state_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_show
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_show
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_type_show
  - drivers/md/dm-table.c:dm_read_arg_group
  - drivers/md/dm-table.c:dm_read_arg
  - drivers/md/dm-linear.c:linear_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/cpufreq/cpufreq.c:store_scaling_setspeed
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/cpufreq.c:store_boost
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_ondemand.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_ondemand.c:store_up_threshold
  - drivers/cpufreq/cpufreq_ondemand.c:store_io_is_busy
  - drivers/cpufreq/cpufreq_conservative.c:store_freq_step
  - drivers/cpufreq/cpufreq_conservative.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_conservative.c:store_down_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_up_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_governor.c:store_sampling_rate
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:polling_interval_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/governor_userspace.c:store_freq
  - drivers/powercap/powercap_sys.c:show_constraint_name
  - drivers/powercap/powercap_sys.c:show_constraint_min_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_max_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_min_power_uw
  - drivers/powercap/powercap_sys.c:show_constraint_max_power_uw
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:show_constraint_power_limit_uw
  - net/core/dev.c:__dev_alloc_name
  - net/core/netprio_cgroup.c:write_priomap
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff818fa040-ffffffff818fa0a5: sscanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sscanf(const char *buf, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81980cc0)
Location: lib/vsprintf.c:3147
Inline: False
Direct callers:
  - arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:max_active_store
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_write
  - kernel/power/main.c:pm_trace_store
  - kernel/power/main.c:wakeup_count_store
  - kernel/power/hibernate.c:reserved_size_store
  - kernel/power/hibernate.c:image_size_store
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_answer
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - block/genhd.c:disk_events_poll_msecs_store
  - block/badblocks.c:badblocks_store
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci-driver.c:remove_id_store
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/video/fbdev/core/fbsysfs.c:store_bl_curve
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/battery.c:acpi_battery_alarm_store
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_acpihid
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_hpet
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_ioapic
  - drivers/scsi/scsi_sysfs.c:sdev_store_timeout
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/spi/spi.c:spi_slave_store
  - drivers/usb/core/hcd.c:authorized_default_store
  - drivers/usb/core/driver.c:remove_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/usb/core/sysfs.c:authorized_store
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/host/ehci-hcd.c:store_companion
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/power/supply/charger-manager.c:charger_externally_control_store
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_cur_state_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_show
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_show
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_type_show
  - drivers/md/dm-table.c:dm_read_arg_group
  - drivers/md/dm-table.c:dm_read_arg
  - drivers/md/dm-linear.c:linear_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/cpufreq/cpufreq.c:store_scaling_setspeed
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/cpufreq.c:store_boost
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_ondemand.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_ondemand.c:store_up_threshold
  - drivers/cpufreq/cpufreq_ondemand.c:store_io_is_busy
  - drivers/cpufreq/cpufreq_conservative.c:store_freq_step
  - drivers/cpufreq/cpufreq_conservative.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_conservative.c:store_down_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_up_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_governor.c:store_sampling_rate
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:polling_interval_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/governor_userspace.c:store_freq
  - drivers/powercap/powercap_sys.c:show_constraint_name
  - drivers/powercap/powercap_sys.c:show_constraint_min_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_max_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_min_power_uw
  - drivers/powercap/powercap_sys.c:show_constraint_max_power_uw
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:show_constraint_power_limit_uw
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/netprio_cgroup.c:write_priomap
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81980cc0-ffffffff81980d25: sscanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sscanf(const char *buf, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff819dca00)
Location: lib/vsprintf.c:3195
Inline: False
Direct callers:
  - arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:max_active_store
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_write
  - kernel/power/main.c:pm_trace_store
  - kernel/power/main.c:wakeup_count_store
  - kernel/power/hibernate.c:resume_offset_setup
  - kernel/power/hibernate.c:reserved_size_store
  - kernel/power/hibernate.c:image_size_store
  - mm/hugetlb.c:hugetlb_nrpages_setup
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_answer
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - block/genhd.c:disk_events_poll_msecs_store
  - block/badblocks.c:badblocks_store
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci-driver.c:remove_id_store
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/video/fbdev/core/fbsysfs.c:store_bl_curve
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/battery.c:acpi_battery_alarm_store
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_acpihid
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_hpet
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_ioapic
  - drivers/scsi/scsi_sysfs.c:sdev_store_timeout
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/spi/spi.c:spi_slave_store
  - drivers/usb/core/hcd.c:authorized_default_store
  - drivers/usb/core/driver.c:remove_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/usb/core/sysfs.c:authorized_store
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:pps_enable_store
  - drivers/ptp/ptp_sysfs.c:period_store
  - drivers/ptp/ptp_sysfs.c:extts_enable_store
  - drivers/power/supply/charger-manager.c:charger_externally_control_store
  - drivers/thermal/thermal_sysfs.c:cur_state_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_show
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_show
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_type_show
  - drivers/md/dm-table.c:dm_read_arg_group
  - drivers/md/dm-table.c:dm_read_arg
  - drivers/md/dm-linear.c:linear_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/cpufreq/cpufreq.c:store_scaling_setspeed
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/cpufreq.c:store_boost
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_ondemand.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_ondemand.c:store_up_threshold
  - drivers/cpufreq/cpufreq_ondemand.c:store_io_is_busy
  - drivers/cpufreq/cpufreq_conservative.c:store_freq_step
  - drivers/cpufreq/cpufreq_conservative.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_conservative.c:store_down_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_up_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_governor.c:store_sampling_rate
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:polling_interval_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/governor_userspace.c:store_freq
  - drivers/powercap/powercap_sys.c:show_constraint_name
  - drivers/powercap/powercap_sys.c:show_constraint_min_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_max_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_min_power_uw
  - drivers/powercap/powercap_sys.c:show_constraint_max_power_uw
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:show_constraint_power_limit_uw
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/netprio_cgroup.c:write_priomap
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff819dca00-ffffffff819dca65: sscanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sscanf(const char *buf, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a14ed0)
Location: lib/vsprintf.c:3323
Inline: False
Direct callers:
  - arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:max_active_store
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_write
  - kernel/power/main.c:pm_trace_store
  - kernel/power/main.c:wakeup_count_store
  - kernel/power/hibernate.c:resume_offset_setup
  - kernel/power/hibernate.c:reserved_size_store
  - kernel/power/hibernate.c:image_size_store
  - mm/hugetlb.c:hugetlb_nrpages_setup
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_answer
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - block/genhd.c:disk_events_poll_msecs_store
  - block/badblocks.c:badblocks_store
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci-driver.c:remove_id_store
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/video/fbdev/core/fbsysfs.c:store_bl_curve
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/battery.c:acpi_battery_alarm_store
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_acpihid
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_hpet
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_ioapic
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_timeout
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/spi/spi.c:spi_slave_store
  - drivers/usb/core/hcd.c:authorized_default_store
  - drivers/usb/core/driver.c:remove_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/usb/core/sysfs.c:authorized_store
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:pps_enable_store
  - drivers/ptp/ptp_sysfs.c:period_store
  - drivers/ptp/ptp_sysfs.c:extts_enable_store
  - drivers/power/supply/charger-manager.c:charger_externally_control_store
  - drivers/thermal/thermal_sysfs.c:cur_state_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_show
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_show
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_type_show
  - drivers/md/dm-table.c:dm_read_arg_group
  - drivers/md/dm-table.c:dm_read_arg
  - drivers/md/dm-linear.c:linear_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/cpufreq/cpufreq.c:store_scaling_setspeed
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/cpufreq.c:store_boost
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_ondemand.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_ondemand.c:store_up_threshold
  - drivers/cpufreq/cpufreq_ondemand.c:store_io_is_busy
  - drivers/cpufreq/cpufreq_conservative.c:store_freq_step
  - drivers/cpufreq/cpufreq_conservative.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_conservative.c:store_down_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_up_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_governor.c:store_sampling_rate
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:polling_interval_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/governor_userspace.c:store_freq
  - drivers/powercap/powercap_sys.c:show_constraint_name
  - drivers/powercap/powercap_sys.c:show_constraint_min_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_max_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_min_power_uw
  - drivers/powercap/powercap_sys.c:show_constraint_max_power_uw
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:show_constraint_power_limit_uw
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/netprio_cgroup.c:write_priomap
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81a14ed0-ffffffff81a14f35: sscanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sscanf(const char *buf, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a84760)
Location: lib/vsprintf.c:3432
Inline: False
Direct callers:
  - arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:max_active_store
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_write
  - kernel/power/main.c:pm_trace_store
  - kernel/power/main.c:wakeup_count_store
  - kernel/power/hibernate.c:resume_offset_setup
  - kernel/power/hibernate.c:reserved_size_store
  - kernel/power/hibernate.c:image_size_store
  - kernel/cgroup/cgroup.c:cgroup_parse_float
  - mm/hugetlb.c:hugetlb_nrpages_setup
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_answer
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - block/genhd.c:disk_events_poll_msecs_store
  - block/badblocks.c:badblocks_store
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci-driver.c:remove_id_store
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/video/fbdev/core/fbsysfs.c:store_bl_curve
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/battery.c:acpi_battery_alarm_store
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_acpihid
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_hpet
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_ioapic
  - drivers/nvdimm/dimm_devs.c:__security_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_timeout
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/spi/spi.c:spi_slave_store
  - drivers/usb/core/driver.c:remove_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/usb/core/sysfs.c:authorized_default_store
  - drivers/usb/core/sysfs.c:authorized_store
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:pps_enable_store
  - drivers/ptp/ptp_sysfs.c:period_store
  - drivers/ptp/ptp_sysfs.c:extts_enable_store
  - drivers/power/supply/charger-manager.c:charger_externally_control_store
  - drivers/thermal/thermal_sysfs.c:cur_state_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_show
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_show
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_type_show
  - drivers/md/dm-table.c:dm_read_arg_group
  - drivers/md/dm-table.c:dm_read_arg
  - drivers/md/dm-linear.c:linear_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:parse_histogram
  - drivers/cpufreq/cpufreq.c:store_scaling_setspeed
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/cpufreq.c:store_boost
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_ondemand.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_ondemand.c:store_up_threshold
  - drivers/cpufreq/cpufreq_ondemand.c:store_io_is_busy
  - drivers/cpufreq/cpufreq_conservative.c:store_freq_step
  - drivers/cpufreq/cpufreq_conservative.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_conservative.c:store_down_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_up_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_governor.c:store_sampling_rate
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:polling_interval_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/governor_userspace.c:store_freq
  - drivers/powercap/powercap_sys.c:show_constraint_name
  - drivers/powercap/powercap_sys.c:show_constraint_min_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_max_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_min_power_uw
  - drivers/powercap/powercap_sys.c:show_constraint_max_power_uw
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:show_constraint_power_limit_uw
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/netprio_cgroup.c:write_priomap
  - net/ipv4/sysctl_net_ipv4.c:sscanf_key
```
**Symbols:**

```
ffffffff81a84760-ffffffff81a847c5: sscanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sscanf(const char *buf, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81abb9d0)
Location: lib/vsprintf.c:3439
Inline: False
Direct callers:
  - arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:max_active_store
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_write
  - kernel/power/main.c:pm_trace_store
  - kernel/power/main.c:wakeup_count_store
  - kernel/power/hibernate.c:resume_offset_setup
  - kernel/power/hibernate.c:reserved_size_store
  - kernel/power/hibernate.c:image_size_store
  - kernel/cgroup/cgroup.c:cgroup_parse_float
  - mm/hugetlb.c:hugetlb_nrpages_setup
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_answer
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - block/genhd.c:disk_events_poll_msecs_store
  - block/badblocks.c:badblocks_store
  - block/blk-cgroup.c:blkcg_conf_get_disk
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci-driver.c:remove_id_store
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/video/fbdev/core/fbsysfs.c:store_bl_curve
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/battery.c:acpi_battery_alarm_store
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_acpihid
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_hpet
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_ioapic
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_timeout
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/spi/spi.c:slave_store
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_init
  - drivers/usb/core/driver.c:remove_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/usb/core/sysfs.c:authorized_default_store
  - drivers/usb/core/sysfs.c:authorized_store
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:pps_enable_store
  - drivers/ptp/ptp_sysfs.c:period_store
  - drivers/ptp/ptp_sysfs.c:extts_enable_store
  - drivers/power/supply/charger-manager.c:charger_externally_control_store
  - drivers/thermal/thermal_sysfs.c:cur_state_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_show
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_show
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_type_show
  - drivers/md/dm-table.c:dm_read_arg_group
  - drivers/md/dm-table.c:dm_read_arg
  - drivers/md/dm-linear.c:linear_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:parse_histogram
  - drivers/cpufreq/cpufreq.c:store_scaling_setspeed
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/cpufreq.c:store_boost
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_ondemand.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_ondemand.c:store_up_threshold
  - drivers/cpufreq/cpufreq_ondemand.c:store_io_is_busy
  - drivers/cpufreq/cpufreq_conservative.c:store_freq_step
  - drivers/cpufreq/cpufreq_conservative.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_conservative.c:store_down_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_up_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_governor.c:store_sampling_rate
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:polling_interval_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/governor_userspace.c:store_freq
  - drivers/powercap/powercap_sys.c:show_constraint_name
  - drivers/powercap/powercap_sys.c:show_constraint_min_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_max_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_min_power_uw
  - drivers/powercap/powercap_sys.c:show_constraint_max_power_uw
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:show_constraint_power_limit_uw
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/netprio_cgroup.c:write_priomap
  - net/ipv4/sysctl_net_ipv4.c:sscanf_key
```
**Symbols:**

```
ffffffff81abb9d0-ffffffff81abba35: sscanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sscanf(const char *buf, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815f7520)
Location: lib/vsprintf.c:3549
Inline: False
Direct callers:
  - init/do_mounts.c:devt_from_partuuid
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:max_active_store
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_write
  - kernel/power/main.c:pm_trace_store
  - kernel/power/main.c:wakeup_count_store
  - kernel/power/hibernate.c:resume_offset_setup
  - kernel/power/hibernate.c:reserved_size_store
  - kernel/power/hibernate.c:image_size_store
  - kernel/livepatch/core.c:klp_apply_section_relocs
  - kernel/livepatch/core.c:klp_resolve_symbols
  - kernel/cgroup/cgroup.c:cgroup_parse_float
  - mm/hugetlb.c:hugepages_setup
  - fs/proc/base.c:timens_offsets_write
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_answer
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - block/genhd.c:disk_events_poll_msecs_store
  - block/badblocks.c:badblocks_store
  - block/blk-cgroup.c:blkcg_conf_get_disk
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/pci/pci-driver.c:remove_id_store
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/video/fbdev/core/fbsysfs.c:store_bl_curve
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/battery.c:acpi_battery_alarm_store
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/iommu/amd/init.c:parse_ivrs_hpet
  - drivers/iommu/amd/init.c:parse_ivrs_ioapic
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_timeout
  - drivers/scsi/scsi_sysfs.c:scsi_scan
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/spi/spi.c:slave_store
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_ids
  - drivers/usb/core/driver.c:remove_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/usb/core/sysfs.c:authorized_default_store
  - drivers/usb/core/sysfs.c:authorized_store
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/i2c/i2c-core-base.c:delete_device_store
  - drivers/i2c/i2c-core-base.c:new_device_store
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:pps_enable_store
  - drivers/ptp/ptp_sysfs.c:period_store
  - drivers/ptp/ptp_sysfs.c:extts_enable_store
  - drivers/power/supply/charger-manager.c:charger_externally_control_store
  - drivers/thermal/thermal_sysfs.c:cur_state_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_show
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_show
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_type_show
  - drivers/md/dm-table.c:dm_read_arg_group
  - drivers/md/dm-table.c:dm_read_arg
  - drivers/md/dm-linear.c:linear_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:parse_histogram
  - drivers/cpufreq/cpufreq.c:store_scaling_setspeed
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/cpufreq.c:store_boost
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_ondemand.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_ondemand.c:store_up_threshold
  - drivers/cpufreq/cpufreq_ondemand.c:store_io_is_busy
  - drivers/cpufreq/cpufreq_conservative.c:store_freq_step
  - drivers/cpufreq/cpufreq_conservative.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_conservative.c:store_down_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_up_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_governor.c:store_sampling_rate
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpuidle/sysfs.c:store_current_governor
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:polling_interval_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/governor_userspace.c:store_freq
  - drivers/powercap/powercap_sys.c:show_constraint_name
  - drivers/powercap/powercap_sys.c:show_constraint_min_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_max_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_min_power_uw
  - drivers/powercap/powercap_sys.c:show_constraint_max_power_uw
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:show_constraint_power_limit_uw
  - net/core/dev.c:__dev_alloc_name
  - net/core/netprio_cgroup.c:write_priomap
  - net/ipv4/sysctl_net_ipv4.c:sscanf_key
```
**Symbols:**

```
ffffffff815f7520-ffffffff815f7585: sscanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sscanf(const char *buf, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8161b970)
Location: lib/vsprintf.c:3548
Inline: False
Direct callers:
  - init/do_mounts.c:devt_from_devnum
  - init/do_mounts.c:devt_from_devnum
  - init/do_mounts.c:devt_from_partuuid
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:max_active_store
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_write
  - kernel/power/main.c:pm_trace_store
  - kernel/power/main.c:wakeup_count_store
  - kernel/power/hibernate.c:resume_offset_setup
  - kernel/power/hibernate.c:reserved_size_store
  - kernel/power/hibernate.c:image_size_store
  - kernel/livepatch/core.c:klp_apply_section_relocs
  - kernel/livepatch/core.c:klp_resolve_symbols
  - kernel/cgroup/cgroup.c:cgroup_parse_float
  - mm/hugetlb.c:hugepages_setup
  - fs/proc/base.c:timens_offsets_write
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_answer
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - block/genhd.c:disk_events_poll_msecs_store
  - block/badblocks.c:badblocks_store
  - block/blk-cgroup.c:blkcg_conf_open_bdev
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/pci/pci-driver.c:remove_id_store
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/video/fbdev/core/fbsysfs.c:store_bl_curve
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/battery.c:acpi_battery_alarm_store
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/iommu/amd/init.c:parse_ivrs_hpet
  - drivers/iommu/amd/init.c:parse_ivrs_ioapic
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_timeout
  - drivers/scsi/scsi_sysfs.c:scsi_scan
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/spi/spi.c:slave_store
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_ids
  - drivers/usb/core/driver.c:remove_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/usb/core/sysfs.c:authorized_default_store
  - drivers/usb/core/sysfs.c:authorized_store
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/i2c/i2c-core-base.c:delete_device_store
  - drivers/i2c/i2c-core-base.c:new_device_store
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:pps_enable_store
  - drivers/ptp/ptp_sysfs.c:period_store
  - drivers/ptp/ptp_sysfs.c:extts_enable_store
  - drivers/power/supply/charger-manager.c:charger_externally_control_store
  - drivers/thermal/thermal_sysfs.c:cur_state_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_show
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_show
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_type_show
  - drivers/md/dm-table.c:dm_read_arg_group
  - drivers/md/dm-table.c:dm_read_arg
  - drivers/md/dm-table.c:dm_get_device
  - drivers/md/dm-linear.c:linear_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:parse_histogram
  - drivers/cpufreq/cpufreq.c:store_scaling_setspeed
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/cpufreq.c:store_boost
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_ondemand.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_ondemand.c:store_up_threshold
  - drivers/cpufreq/cpufreq_ondemand.c:store_io_is_busy
  - drivers/cpufreq/cpufreq_conservative.c:store_freq_step
  - drivers/cpufreq/cpufreq_conservative.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_conservative.c:store_down_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_up_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_governor.c:store_sampling_rate
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpuidle/sysfs.c:store_current_governor
  - drivers/devfreq/devfreq.c:timer_store
  - drivers/devfreq/devfreq.c:polling_interval_store
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/governor_userspace.c:store_freq
  - drivers/powercap/powercap_sys.c:show_constraint_name
  - drivers/powercap/powercap_sys.c:show_constraint_min_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_max_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_min_power_uw
  - drivers/powercap/powercap_sys.c:show_constraint_max_power_uw
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:show_constraint_power_limit_uw
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/netprio_cgroup.c:write_priomap
  - net/ipv4/sysctl_net_ipv4.c:sscanf_key
```
**Symbols:**

```
ffffffff8161b970-ffffffff8161b9d5: sscanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sscanf(const char *buf, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815fcfc0)
Location: lib/vsprintf.c:3665
Inline: False
Direct callers:
  - init/do_mounts.c:devt_from_partuuid
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:max_active_store
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_write
  - kernel/power/main.c:pm_trace_store
  - kernel/power/main.c:wakeup_count_store
  - kernel/power/hibernate.c:resume_offset_setup
  - kernel/power/hibernate.c:reserved_size_store
  - kernel/power/hibernate.c:image_size_store
  - kernel/livepatch/core.c:klp_apply_section_relocs
  - kernel/livepatch/core.c:klp_resolve_symbols
  - kernel/cgroup/cgroup.c:cgroup_parse_float
  - mm/hugetlb.c:hugepages_setup
  - fs/proc/base.c:timens_offsets_write
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_answer
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - block/genhd.c:disk_events_poll_msecs_store
  - block/badblocks.c:badblocks_store
  - block/blk-cgroup.c:blkcg_conf_open_bdev
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/pci/pci-driver.c:remove_id_store
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/video/fbdev/core/fbsysfs.c:store_bl_curve
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/battery.c:acpi_battery_alarm_store
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/iommu/amd/init.c:parse_ivrs_hpet
  - drivers/iommu/amd/init.c:parse_ivrs_ioapic
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_timeout
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/spi/spi.c:slave_store
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_ids
  - drivers/usb/core/driver.c:remove_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/usb/core/sysfs.c:authorized_default_store
  - drivers/usb/core/sysfs.c:authorized_store
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/i2c/i2c-core-base.c:delete_device_store
  - drivers/i2c/i2c-core-base.c:new_device_store
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:pps_enable_store
  - drivers/ptp/ptp_sysfs.c:period_store
  - drivers/ptp/ptp_sysfs.c:extts_enable_store
  - drivers/power/supply/charger-manager.c:charger_externally_control_store
  - drivers/thermal/thermal_sysfs.c:cur_state_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_show
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_show
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_type_show
  - drivers/md/dm-table.c:dm_read_arg_group
  - drivers/md/dm-table.c:dm_read_arg
  - drivers/md/dm-table.c:dm_get_device
  - drivers/md/dm-linear.c:linear_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:parse_histogram
  - drivers/cpufreq/cpufreq.c:store_scaling_setspeed
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/cpufreq.c:store_boost
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_ondemand.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_ondemand.c:store_up_threshold
  - drivers/cpufreq/cpufreq_ondemand.c:store_io_is_busy
  - drivers/cpufreq/cpufreq_conservative.c:store_freq_step
  - drivers/cpufreq/cpufreq_conservative.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_conservative.c:store_down_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_up_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_governor.c:store_sampling_rate
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpuidle/sysfs.c:store_current_governor
  - drivers/devfreq/devfreq.c:timer_store
  - drivers/devfreq/devfreq.c:polling_interval_store
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/governor_userspace.c:store_freq
  - drivers/powercap/powercap_sys.c:show_constraint_name
  - drivers/powercap/powercap_sys.c:show_constraint_min_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_max_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_min_power_uw
  - drivers/powercap/powercap_sys.c:show_constraint_max_power_uw
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:show_constraint_power_limit_uw
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/netprio_cgroup.c:write_priomap
  - net/ipv4/sysctl_net_ipv4.c:sscanf_key
```
**Symbols:**

```
ffffffff815fcfc0-ffffffff815fd025: sscanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sscanf(const char *buf, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8166ac50)
Location: lib/vsprintf.c:3688
Inline: False
Direct callers:
  - init/do_mounts.c:devt_from_partuuid
  - arch/x86/kernel/cpu/intel.c:sld_state_setup
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:max_active_store
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_write
  - kernel/power/main.c:pm_trace_store
  - kernel/power/main.c:wakeup_count_store
  - kernel/power/hibernate.c:resume_offset_setup
  - kernel/power/hibernate.c:reserved_size_store
  - kernel/power/hibernate.c:image_size_store
  - kernel/livepatch/core.c:klp_apply_section_relocs
  - kernel/livepatch/core.c:klp_resolve_symbols
  - kernel/cgroup/cgroup.c:cgroup_parse_float
  - mm/hugetlb.c:hugepages_setup
  - fs/proc/base.c:timens_offsets_write
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_answer
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - block/badblocks.c:badblocks_store
  - block/disk-events.c:disk_events_poll_msecs_store
  - block/blk-cgroup.c:blkcg_conf_open_bdev
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/pci/pci-driver.c:remove_id_store
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/video/fbdev/core/fbsysfs.c:store_bl_curve
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/battery.c:acpi_battery_alarm_store
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/iommu/amd/init.c:parse_ivrs_hpet
  - drivers/iommu/amd/init.c:parse_ivrs_ioapic
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_timeout
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/spi/spi.c:slave_store
  - drivers/net/phy/phy_device.c:fwnode_get_phy_id
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_ids
  - drivers/usb/core/driver.c:remove_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/usb/core/sysfs.c:authorized_default_store
  - drivers/usb/core/sysfs.c:authorized_store
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/i2c/i2c-core-base.c:delete_device_store
  - drivers/i2c/i2c-core-base.c:new_device_store
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:pps_enable_store
  - drivers/ptp/ptp_sysfs.c:period_store
  - drivers/ptp/ptp_sysfs.c:extts_enable_store
  - drivers/power/supply/charger-manager.c:charger_externally_control_store
  - drivers/thermal/thermal_sysfs.c:cur_state_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_show
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_show
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_type_show
  - drivers/md/dm-table.c:dm_read_arg_group
  - drivers/md/dm-table.c:dm_read_arg
  - drivers/md/dm-table.c:dm_get_device
  - drivers/md/dm-linear.c:linear_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:parse_histogram
  - drivers/cpufreq/cpufreq.c:store_scaling_setspeed
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/cpufreq.c:store_boost
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_ondemand.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_ondemand.c:store_up_threshold
  - drivers/cpufreq/cpufreq_ondemand.c:store_io_is_busy
  - drivers/cpufreq/cpufreq_conservative.c:store_freq_step
  - drivers/cpufreq/cpufreq_conservative.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_conservative.c:store_down_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_up_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_governor.c:store_sampling_rate
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpuidle/sysfs.c:store_current_governor
  - drivers/devfreq/devfreq.c:timer_store
  - drivers/devfreq/devfreq.c:polling_interval_store
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/governor_userspace.c:set_freq_store
  - drivers/powercap/powercap_sys.c:show_constraint_name
  - drivers/powercap/powercap_sys.c:show_constraint_min_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_max_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_min_power_uw
  - drivers/powercap/powercap_sys.c:show_constraint_max_power_uw
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:show_constraint_power_limit_uw
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/netprio_cgroup.c:write_priomap
  - net/ipv4/sysctl_net_ipv4.c:sscanf_key
```
**Symbols:**

```
ffffffff8166ac50-ffffffff8166acb5: sscanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sscanf(const char *buf, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81784ae0)
Location: lib/vsprintf.c:3675
Inline: False
Direct callers:
  - init/do_mounts.c:devt_from_partuuid
  - arch/x86/kernel/cpu/intel.c:sld_state_setup
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:max_active_store
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/power/main.c:pm_trace_store
  - kernel/power/main.c:wakeup_count_store
  - kernel/power/hibernate.c:resume_offset_setup
  - kernel/power/hibernate.c:reserved_size_store
  - kernel/power/hibernate.c:image_size_store
  - kernel/livepatch/core.c:klp_apply_section_relocs
  - kernel/livepatch/core.c:klp_resolve_symbols
  - kernel/cgroup/cgroup.c:cgroup_parse_float
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - mm/hugetlb.c:hugepages_setup
  - mm/hugetlb.c:hugepages_setup
  - mm/huge_memory.c:split_huge_pages_write
  - mm/huge_memory.c:split_huge_pages_write
  - fs/proc/base.c:timens_offsets_write
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_answer
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - block/badblocks.c:badblocks_store
  - block/disk-events.c:disk_events_poll_msecs_store
  - block/blk-cgroup.c:blkcg_conf_open_bdev
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/pci/pci-driver.c:remove_id_store
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/pci/vgaarb.c:vga_arb_write
  - drivers/video/fbdev/core/fbsysfs.c:store_bl_curve
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/battery.c:acpi_battery_alarm_store
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/iommu/amd/init.c:parse_ivrs_hpet
  - drivers/iommu/amd/init.c:parse_ivrs_ioapic
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_timeout
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/spi/spi.c:slave_store
  - drivers/net/phy/phy_device.c:fwnode_get_phy_id
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_ids
  - drivers/usb/core/driver.c:remove_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/usb/core/sysfs.c:authorized_default_store
  - drivers/usb/core/sysfs.c:authorized_store
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/i2c/i2c-core-base.c:delete_device_store
  - drivers/i2c/i2c-core-base.c:new_device_store
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:pps_enable_store
  - drivers/ptp/ptp_sysfs.c:period_store
  - drivers/ptp/ptp_sysfs.c:extts_enable_store
  - drivers/power/supply/charger-manager.c:charger_externally_control_store
  - drivers/thermal/thermal_sysfs.c:cur_state_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_show
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_show
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_type_show
  - drivers/md/dm-table.c:dm_read_arg_group
  - drivers/md/dm-table.c:dm_read_arg
  - drivers/md/dm-table.c:dm_get_device
  - drivers/md/dm-linear.c:linear_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_delete
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:parse_histogram
  - drivers/cpufreq/cpufreq.c:store_scaling_setspeed
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/cpufreq.c:store_boost
  - drivers/cpufreq/cpufreq_ondemand.c:powersave_bias_store
  - drivers/cpufreq/cpufreq_ondemand.c:ignore_nice_load_store
  - drivers/cpufreq/cpufreq_ondemand.c:sampling_down_factor_store
  - drivers/cpufreq/cpufreq_ondemand.c:up_threshold_store
  - drivers/cpufreq/cpufreq_ondemand.c:io_is_busy_store
  - drivers/cpufreq/cpufreq_conservative.c:freq_step_store
  - drivers/cpufreq/cpufreq_conservative.c:ignore_nice_load_store
  - drivers/cpufreq/cpufreq_conservative.c:down_threshold_store
  - drivers/cpufreq/cpufreq_conservative.c:up_threshold_store
  - drivers/cpufreq/cpufreq_conservative.c:sampling_down_factor_store
  - drivers/cpufreq/cpufreq_governor.c:sampling_rate_store
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpuidle/sysfs.c:store_current_governor
  - drivers/devfreq/devfreq.c:timer_store
  - drivers/devfreq/devfreq.c:polling_interval_store
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/governor_userspace.c:set_freq_store
  - drivers/powercap/powercap_sys.c:show_constraint_name
  - drivers/powercap/powercap_sys.c:show_constraint_min_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_max_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_min_power_uw
  - drivers/powercap/powercap_sys.c:show_constraint_max_power_uw
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:show_constraint_power_limit_uw
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/netprio_cgroup.c:write_priomap
  - net/ipv4/sysctl_net_ipv4.c:sscanf_key
```
**Symbols:**

```
ffffffff81784ae0-ffffffff81784b5f: sscanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sscanf(const char *buf, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff82041ac0)
Location: lib/vsprintf.c:3689
Inline: False
Direct callers:
  - init/do_mounts.c:devt_from_partuuid
  - arch/x86/kernel/cpu/intel.c:sld_state_setup
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:max_active_store
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/power/main.c:pm_trace_store
  - kernel/power/main.c:wakeup_count_store
  - kernel/power/hibernate.c:resume_offset_setup
  - kernel/power/hibernate.c:reserved_size_store
  - kernel/power/hibernate.c:image_size_store
  - kernel/livepatch/core.c:klp_apply_section_relocs
  - kernel/livepatch/core.c:klp_resolve_symbols
  - kernel/cgroup/cgroup.c:cgroup_parse_float
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - mm/vmscan.c:lru_gen_seq_write
  - mm/hugetlb.c:hugepages_setup
  - mm/hugetlb.c:hugepages_setup
  - mm/huge_memory.c:split_huge_pages_write
  - mm/huge_memory.c:split_huge_pages_write
  - fs/proc/base.c:timens_offsets_write
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_answer
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - block/badblocks.c:badblocks_store
  - block/disk-events.c:disk_events_poll_msecs_store
  - block/blk-cgroup.c:blkcg_conf_open_bdev
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/pci/pci-driver.c:remove_id_store
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/pci/vgaarb.c:vga_arb_write
  - drivers/video/fbdev/core/fbsysfs.c:store_bl_curve
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/battery.c:acpi_battery_alarm_store
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/iommu/amd/init.c:parse_ivrs_hpet
  - drivers/iommu/amd/init.c:parse_ivrs_hpet
  - drivers/iommu/amd/init.c:parse_ivrs_hpet
  - drivers/iommu/amd/init.c:parse_ivrs_hpet
  - drivers/iommu/amd/init.c:parse_ivrs_ioapic
  - drivers/iommu/amd/init.c:parse_ivrs_ioapic
  - drivers/iommu/amd/init.c:parse_ivrs_ioapic
  - drivers/iommu/amd/init.c:parse_ivrs_ioapic
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_timeout
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/spi/spi.c:slave_store
  - drivers/net/phy/phy_device.c:fwnode_get_phy_id
  - drivers/usb/core/driver.c:remove_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/usb/core/sysfs.c:authorized_default_store
  - drivers/usb/core/sysfs.c:authorized_store
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/i2c/i2c-core-base.c:delete_device_store
  - drivers/i2c/i2c-core-base.c:new_device_store
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:pps_enable_store
  - drivers/ptp/ptp_sysfs.c:period_store
  - drivers/ptp/ptp_sysfs.c:extts_enable_store
  - drivers/power/supply/charger-manager.c:charger_externally_control_store
  - drivers/thermal/thermal_sysfs.c:cur_state_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_show
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_show
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_type_show
  - drivers/md/dm-table.c:dm_read_arg_group
  - drivers/md/dm-table.c:dm_read_arg
  - drivers/md/dm-table.c:dm_get_device
  - drivers/md/dm-linear.c:linear_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_delete
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:parse_histogram
  - drivers/cpufreq/cpufreq.c:store_scaling_setspeed
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/cpufreq.c:store_boost
  - drivers/cpufreq/cpufreq_ondemand.c:powersave_bias_store
  - drivers/cpufreq/cpufreq_ondemand.c:ignore_nice_load_store
  - drivers/cpufreq/cpufreq_ondemand.c:sampling_down_factor_store
  - drivers/cpufreq/cpufreq_ondemand.c:up_threshold_store
  - drivers/cpufreq/cpufreq_ondemand.c:io_is_busy_store
  - drivers/cpufreq/cpufreq_conservative.c:freq_step_store
  - drivers/cpufreq/cpufreq_conservative.c:ignore_nice_load_store
  - drivers/cpufreq/cpufreq_conservative.c:down_threshold_store
  - drivers/cpufreq/cpufreq_conservative.c:up_threshold_store
  - drivers/cpufreq/cpufreq_conservative.c:sampling_down_factor_store
  - drivers/cpufreq/cpufreq_governor.c:sampling_rate_store
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpuidle/sysfs.c:store_current_governor
  - drivers/devfreq/devfreq.c:timer_store
  - drivers/devfreq/devfreq.c:polling_interval_store
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/governor_userspace.c:set_freq_store
  - drivers/powercap/powercap_sys.c:show_constraint_name
  - drivers/powercap/powercap_sys.c:show_constraint_min_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_max_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_min_power_uw
  - drivers/powercap/powercap_sys.c:show_constraint_max_power_uw
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:show_constraint_power_limit_uw
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/netprio_cgroup.c:write_priomap
  - net/ipv4/sysctl_net_ipv4.c:sscanf_key
```
**Symbols:**

```
ffffffff82041ac0-ffffffff82041b3f: sscanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sscanf(const char *buf, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff820c0010)
Location: lib/vsprintf.c:3710
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:sld_state_setup
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:max_active_store
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/power/main.c:pm_trace_store
  - kernel/power/main.c:wakeup_count_store
  - kernel/power/hibernate.c:resume_offset_setup
  - kernel/power/hibernate.c:reserved_size_store
  - kernel/power/hibernate.c:image_size_store
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:resume_store
  - kernel/livepatch/core.c:klp_write_section_relocs
  - kernel/livepatch/core.c:klp_resolve_symbols
  - kernel/cgroup/cgroup.c:cgroup_parse_float
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - mm/vmscan.c:lru_gen_seq_write
  - mm/hugetlb.c:hugepages_setup
  - mm/hugetlb.c:hugepages_setup
  - mm/huge_memory.c:split_huge_pages_write
  - mm/huge_memory.c:split_huge_pages_write
  - fs/proc/base.c:timens_offsets_write
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_disable
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_answer
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - block/badblocks.c:badblocks_store
  - block/disk-events.c:disk_events_poll_msecs_store
  - block/early-lookup.c:devt_from_partuuid
  - block/early-lookup.c:early_lookup_bdev
  - block/early-lookup.c:early_lookup_bdev
  - block/blk-cgroup.c:blkg_conf_open_bdev
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/pci/pci-driver.c:remove_id_store
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/pci/vgaarb.c:vga_arb_write
  - drivers/video/fbdev/core/fbsysfs.c:store_bl_curve
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/battery.c:acpi_battery_alarm_store
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/iommu/amd/init.c:parse_ivrs_hpet
  - drivers/iommu/amd/init.c:parse_ivrs_hpet
  - drivers/iommu/amd/init.c:parse_ivrs_hpet
  - drivers/iommu/amd/init.c:parse_ivrs_hpet
  - drivers/iommu/amd/init.c:parse_ivrs_ioapic
  - drivers/iommu/amd/init.c:parse_ivrs_ioapic
  - drivers/iommu/amd/init.c:parse_ivrs_ioapic
  - drivers/iommu/amd/init.c:parse_ivrs_ioapic
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_timeout
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/spi/spi.c:slave_store
  - drivers/net/phy/phy_device.c:fwnode_get_phy_id
  - drivers/usb/core/driver.c:remove_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/usb/core/sysfs.c:authorized_default_store
  - drivers/usb/core/sysfs.c:authorized_store
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/i2c/i2c-core-base.c:delete_device_store
  - drivers/i2c/i2c-core-base.c:new_device_store
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:pps_enable_store
  - drivers/ptp/ptp_sysfs.c:period_store
  - drivers/ptp/ptp_sysfs.c:extts_enable_store
  - drivers/power/supply/charger-manager.c:charger_externally_control_store
  - drivers/thermal/thermal_sysfs.c:cur_state_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_show
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_show
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_type_show
  - drivers/md/dm-table.c:dm_read_arg_group
  - drivers/md/dm-table.c:dm_read_arg
  - drivers/md/dm-table.c:dm_get_device
  - drivers/md/dm-linear.c:linear_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_delete
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:parse_histogram
  - drivers/cpufreq/cpufreq.c:store_scaling_setspeed
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_boost
  - drivers/cpufreq/cpufreq_ondemand.c:powersave_bias_store
  - drivers/cpufreq/cpufreq_ondemand.c:ignore_nice_load_store
  - drivers/cpufreq/cpufreq_ondemand.c:sampling_down_factor_store
  - drivers/cpufreq/cpufreq_ondemand.c:up_threshold_store
  - drivers/cpufreq/cpufreq_ondemand.c:io_is_busy_store
  - drivers/cpufreq/cpufreq_conservative.c:freq_step_store
  - drivers/cpufreq/cpufreq_conservative.c:ignore_nice_load_store
  - drivers/cpufreq/cpufreq_conservative.c:down_threshold_store
  - drivers/cpufreq/cpufreq_conservative.c:up_threshold_store
  - drivers/cpufreq/cpufreq_conservative.c:sampling_down_factor_store
  - drivers/cpufreq/cpufreq_governor.c:sampling_rate_store
  - drivers/cpufreq/amd-pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpuidle/sysfs.c:store_current_governor
  - drivers/devfreq/devfreq.c:timer_store
  - drivers/devfreq/devfreq.c:polling_interval_store
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/governor_userspace.c:set_freq_store
  - drivers/powercap/powercap_sys.c:show_constraint_name
  - drivers/powercap/powercap_sys.c:show_constraint_min_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_max_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_min_power_uw
  - drivers/powercap/powercap_sys.c:show_constraint_max_power_uw
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:show_constraint_power_limit_uw
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/netprio_cgroup.c:write_priomap
  - net/ipv4/sysctl_net_ipv4.c:sscanf_key
```
**Symbols:**

```
ffffffff820c0010-ffffffff820c008f: sscanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sscanf(const char *buf, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8219a0d0)
Location: lib/vsprintf.c:3715
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:sld_state_setup
  - kernel/workqueue.c:wq_affinity_strict_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:max_active_store
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/power/main.c:pm_trace_store
  - kernel/power/main.c:wakeup_count_store
  - kernel/power/hibernate.c:resume_offset_setup
  - kernel/power/hibernate.c:reserved_size_store
  - kernel/power/hibernate.c:image_size_store
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:resume_store
  - kernel/livepatch/core.c:klp_write_section_relocs
  - kernel/livepatch/core.c:klp_resolve_symbols
  - kernel/cgroup/cgroup.c:cgroup_parse_float
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - mm/vmscan.c:lru_gen_seq_write
  - mm/hugetlb.c:hugepages_setup
  - mm/hugetlb.c:hugepages_setup
  - mm/huge_memory.c:split_huge_pages_write
  - mm/huge_memory.c:split_huge_pages_write
  - fs/proc/base.c:timens_offsets_write
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_disable
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_answer
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - block/badblocks.c:badblocks_store
  - block/disk-events.c:disk_events_poll_msecs_store
  - block/early-lookup.c:devt_from_partuuid
  - block/early-lookup.c:early_lookup_bdev
  - block/early-lookup.c:early_lookup_bdev
  - block/blk-cgroup.c:blkg_conf_open_bdev
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/pci/pci-driver.c:remove_id_store
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/pci/vgaarb.c:vga_arb_write
  - drivers/video/fbdev/core/fbsysfs.c:store_bl_curve
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/battery.c:acpi_battery_alarm_store
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/iommu/amd/init.c:parse_ivrs_hpet
  - drivers/iommu/amd/init.c:parse_ivrs_hpet
  - drivers/iommu/amd/init.c:parse_ivrs_hpet
  - drivers/iommu/amd/init.c:parse_ivrs_hpet
  - drivers/iommu/amd/init.c:parse_ivrs_ioapic
  - drivers/iommu/amd/init.c:parse_ivrs_ioapic
  - drivers/iommu/amd/init.c:parse_ivrs_ioapic
  - drivers/iommu/amd/init.c:parse_ivrs_ioapic
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_timeout
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/spi/spi.c:slave_store
  - drivers/net/phy/phy_device.c:fwnode_get_phy_id
  - drivers/usb/core/driver.c:remove_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/usb/core/sysfs.c:authorized_default_store
  - drivers/usb/core/sysfs.c:authorized_store
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/i2c/i2c-core-base.c:delete_device_store
  - drivers/i2c/i2c-core-base.c:new_device_store
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:pps_enable_store
  - drivers/ptp/ptp_sysfs.c:period_store
  - drivers/ptp/ptp_sysfs.c:extts_enable_store
  - drivers/power/supply/charger-manager.c:charger_externally_control_store
  - drivers/thermal/thermal_sysfs.c:cur_state_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_show
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_show
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_type_show
  - drivers/md/dm-table.c:dm_read_arg_group
  - drivers/md/dm-table.c:dm_read_arg
  - drivers/md/dm-table.c:dm_get_device
  - drivers/md/dm-target.c:io_err_ctr
  - drivers/md/dm-linear.c:linear_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_delete
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:parse_histogram
  - drivers/cpufreq/cpufreq.c:store_scaling_setspeed
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_boost
  - drivers/cpufreq/cpufreq_ondemand.c:powersave_bias_store
  - drivers/cpufreq/cpufreq_ondemand.c:ignore_nice_load_store
  - drivers/cpufreq/cpufreq_ondemand.c:sampling_down_factor_store
  - drivers/cpufreq/cpufreq_ondemand.c:up_threshold_store
  - drivers/cpufreq/cpufreq_ondemand.c:io_is_busy_store
  - drivers/cpufreq/cpufreq_conservative.c:freq_step_store
  - drivers/cpufreq/cpufreq_conservative.c:ignore_nice_load_store
  - drivers/cpufreq/cpufreq_conservative.c:down_threshold_store
  - drivers/cpufreq/cpufreq_conservative.c:up_threshold_store
  - drivers/cpufreq/cpufreq_conservative.c:sampling_down_factor_store
  - drivers/cpufreq/cpufreq_governor.c:sampling_rate_store
  - drivers/cpufreq/amd-pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpuidle/sysfs.c:store_current_governor
  - drivers/devfreq/devfreq.c:timer_store
  - drivers/devfreq/devfreq.c:polling_interval_store
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/governor_userspace.c:set_freq_store
  - drivers/powercap/powercap_sys.c:show_constraint_name
  - drivers/powercap/powercap_sys.c:show_constraint_min_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_max_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_min_power_uw
  - drivers/powercap/powercap_sys.c:show_constraint_max_power_uw
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:show_constraint_power_limit_uw
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/netprio_cgroup.c:write_priomap
  - net/ipv4/sysctl_net_ipv4.c:sscanf_key
```
**Symbols:**

```
ffffffff8219a0d0-ffffffff8219a14f: sscanf (STB_GLOBAL)
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
int sscanf(const char *buf, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffff800010d98928)
Location: lib/vsprintf.c:3439
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:max_active_store
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_write
  - kernel/power/main.c:wakeup_count_store
  - kernel/cgroup/cgroup.c:cgroup_parse_float
  - mm/hugetlb.c:hugetlb_nrpages_setup
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_answer
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - block/genhd.c:disk_events_poll_msecs_store
  - block/badblocks.c:badblocks_store
  - block/blk-cgroup.c:blkcg_conf_get_disk
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci-driver.c:remove_id_store
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/video/fbdev/core/fbsysfs.c:store_bl_curve
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/battery.c:acpi_battery_alarm_store
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_timeout
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/spi/spi.c:slave_store
  - drivers/usb/core/driver.c:remove_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/usb/core/sysfs.c:authorized_default_store
  - drivers/usb/core/sysfs.c:authorized_store
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:pps_enable_store
  - drivers/ptp/ptp_sysfs.c:period_store
  - drivers/ptp/ptp_sysfs.c:extts_enable_store
  - drivers/power/supply/charger-manager.c:charger_externally_control_store
  - drivers/thermal/thermal_sysfs.c:cur_state_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_show
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_show
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_type_show
  - drivers/md/dm-table.c:dm_read_arg_group
  - drivers/md/dm-table.c:dm_read_arg
  - drivers/md/dm-linear.c:linear_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/cpufreq/cpufreq.c:store_scaling_setspeed
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/cpufreq.c:store_boost
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_ondemand.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_ondemand.c:store_up_threshold
  - drivers/cpufreq/cpufreq_ondemand.c:store_io_is_busy
  - drivers/cpufreq/cpufreq_conservative.c:store_freq_step
  - drivers/cpufreq/cpufreq_conservative.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_conservative.c:store_down_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_up_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_governor.c:store_sampling_rate
  - drivers/of/of_mdio.c:of_get_phy_id
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:polling_interval_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/governor_userspace.c:store_freq
  - drivers/powercap/powercap_sys.c:show_constraint_name
  - drivers/powercap/powercap_sys.c:show_constraint_min_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_max_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_min_power_uw
  - drivers/powercap/powercap_sys.c:show_constraint_max_power_uw
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:show_constraint_power_limit_uw
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/netprio_cgroup.c:write_priomap
  - net/ipv4/sysctl_net_ipv4.c:sscanf_key
```
**Symbols:**

```
ffff800010d98928-ffff800010d989a0: sscanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sscanf(const char *buf, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c0e9380c)
Location: lib/vsprintf.c:3439
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:max_active_store
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_write
  - kernel/power/main.c:wakeup_count_store
  - kernel/power/hibernate.c:resume_offset_setup
  - kernel/power/hibernate.c:reserved_size_store
  - kernel/power/hibernate.c:image_size_store
  - kernel/cgroup/cgroup.c:cgroup_parse_float
  - fs/pstore/ram.c:ramoops_pstore_read
  - fs/pstore/ram.c:ramoops_pstore_read
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_answer
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - block/genhd.c:disk_events_poll_msecs_store
  - block/badblocks.c:badblocks_store
  - block/blk-cgroup.c:blkcg_conf_get_disk
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci-driver.c:remove_id_store
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/video/fbdev/core/fbsysfs.c:store_bl_curve
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_timeout
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/spi/spi.c:slave_store
  - drivers/usb/core/driver.c:remove_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/usb/core/sysfs.c:authorized_default_store
  - drivers/usb/core/sysfs.c:authorized_store
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/musb/musb_core.c:srp_store
  - drivers/usb/musb/musb_core.c:vbus_store
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:pps_enable_store
  - drivers/ptp/ptp_sysfs.c:period_store
  - drivers/ptp/ptp_sysfs.c:extts_enable_store
  - drivers/power/supply/charger-manager.c:charger_externally_control_store
  - drivers/thermal/thermal_sysfs.c:cur_state_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_show
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_show
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_type_show
  - drivers/md/dm-table.c:dm_read_arg_group
  - drivers/md/dm-table.c:dm_read_arg
  - drivers/md/dm-linear.c:linear_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/cpufreq/cpufreq.c:store_scaling_setspeed
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/cpufreq.c:store_boost
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_ondemand.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_ondemand.c:store_up_threshold
  - drivers/cpufreq/cpufreq_ondemand.c:store_io_is_busy
  - drivers/cpufreq/cpufreq_conservative.c:store_freq_step
  - drivers/cpufreq/cpufreq_conservative.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_conservative.c:store_down_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_up_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_governor.c:store_sampling_rate
  - drivers/of/of_mdio.c:of_get_phy_id
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:polling_interval_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/governor_userspace.c:store_freq
  - drivers/powercap/powercap_sys.c:show_constraint_name
  - drivers/powercap/powercap_sys.c:show_constraint_min_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_max_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_min_power_uw
  - drivers/powercap/powercap_sys.c:show_constraint_max_power_uw
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:show_constraint_power_limit_uw
  - sound/soc/soc-core.c:fmt_single_name
  - sound/soc/soc-core.c:fmt_single_name
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/netprio_cgroup.c:write_priomap
  - net/ipv4/sysctl_net_ipv4.c:sscanf_key
```
**Symbols:**

```
c0e9380c-c0e93868: sscanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sscanf(const char *buf, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c000000000edbfa0)
Location: lib/vsprintf.c:3439
Inline: False
Direct callers:
  - arch/powerpc/kernel/sysfs.c:store_tsr3
  - arch/powerpc/kernel/sysfs.c:store_tsr2
  - arch/powerpc/kernel/sysfs.c:store_tsr1
  - arch/powerpc/kernel/sysfs.c:store_tsr0
  - arch/powerpc/kernel/sysfs.c:store_siar
  - arch/powerpc/kernel/sysfs.c:store_sier
  - arch/powerpc/kernel/sysfs.c:store_ier
  - arch/powerpc/kernel/sysfs.c:store_ber
  - arch/powerpc/kernel/sysfs.c:store_mer
  - arch/powerpc/kernel/sysfs.c:store_der
  - arch/powerpc/kernel/sysfs.c:store_rpccr
  - arch/powerpc/kernel/sysfs.c:store_pccr
  - arch/powerpc/kernel/sysfs.c:store_btcr
  - arch/powerpc/kernel/sysfs.c:store_imaat
  - arch/powerpc/kernel/sysfs.c:store_ima9
  - arch/powerpc/kernel/sysfs.c:store_ima8
  - arch/powerpc/kernel/sysfs.c:store_ima7
  - arch/powerpc/kernel/sysfs.c:store_ima6
  - arch/powerpc/kernel/sysfs.c:store_ima5
  - arch/powerpc/kernel/sysfs.c:store_ima4
  - arch/powerpc/kernel/sysfs.c:store_ima3
  - arch/powerpc/kernel/sysfs.c:store_ima2
  - arch/powerpc/kernel/sysfs.c:store_ima1
  - arch/powerpc/kernel/sysfs.c:store_ima0
  - arch/powerpc/kernel/sysfs.c:store_hid5
  - arch/powerpc/kernel/sysfs.c:store_hid4
  - arch/powerpc/kernel/sysfs.c:store_hid1
  - arch/powerpc/kernel/sysfs.c:store_hid0
  - arch/powerpc/kernel/sysfs.c:store_pa6t_pmc5
  - arch/powerpc/kernel/sysfs.c:store_pa6t_pmc4
  - arch/powerpc/kernel/sysfs.c:store_pa6t_pmc3
  - arch/powerpc/kernel/sysfs.c:store_pa6t_pmc2
  - arch/powerpc/kernel/sysfs.c:store_pa6t_pmc1
  - arch/powerpc/kernel/sysfs.c:store_pa6t_pmc0
  - arch/powerpc/kernel/sysfs.c:store_dscr_default
  - arch/powerpc/kernel/sysfs.c:store_dscr
  - arch/powerpc/kernel/sysfs.c:store_tscr
  - arch/powerpc/kernel/sysfs.c:store_pir
  - arch/powerpc/kernel/sysfs.c:store_spurr
  - arch/powerpc/kernel/sysfs.c:store_purr
  - arch/powerpc/kernel/sysfs.c:store_mmcra
  - arch/powerpc/kernel/sysfs.c:store_pmc8
  - arch/powerpc/kernel/sysfs.c:store_pmc7
  - arch/powerpc/kernel/sysfs.c:store_pmc6
  - arch/powerpc/kernel/sysfs.c:store_pmc5
  - arch/powerpc/kernel/sysfs.c:store_pmc4
  - arch/powerpc/kernel/sysfs.c:store_pmc3
  - arch/powerpc/kernel/sysfs.c:store_pmc2
  - arch/powerpc/kernel/sysfs.c:store_pmc1
  - arch/powerpc/kernel/sysfs.c:store_mmcr1
  - arch/powerpc/kernel/sysfs.c:store_mmcr0
  - arch/powerpc/kernel/sysfs.c:store_smt_snooze_delay
  - arch/powerpc/kernel/eeh.c:eeh_dev_break_write
  - arch/powerpc/kernel/eeh.c:eeh_dev_check_write
  - arch/powerpc/kernel/eeh.c:eeh_force_recover_write
  - arch/powerpc/platforms/powernv/subcore.c:store_subcores_per_core
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_ei_write
  - arch/powerpc/platforms/pseries/power.c:auto_poweron_store
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:max_active_store
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_write
  - kernel/power/main.c:wakeup_count_store
  - kernel/cgroup/cgroup.c:cgroup_parse_float
  - mm/hugetlb.c:hugetlb_nrpages_setup
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_answer
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - block/genhd.c:disk_events_poll_msecs_store
  - block/badblocks.c:badblocks_store
  - block/blk-cgroup.c:blkcg_conf_get_disk
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci-driver.c:remove_id_store
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/video/fbdev/core/fbsysfs.c:store_bl_curve
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_timeout
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/spi/spi.c:slave_store
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_init
  - drivers/usb/core/driver.c:remove_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/usb/core/sysfs.c:authorized_default_store
  - drivers/usb/core/sysfs.c:authorized_store
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:pps_enable_store
  - drivers/ptp/ptp_sysfs.c:period_store
  - drivers/ptp/ptp_sysfs.c:extts_enable_store
  - drivers/power/supply/charger-manager.c:charger_externally_control_store
  - drivers/thermal/thermal_sysfs.c:cur_state_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_show
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_show
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_type_show
  - drivers/md/dm-table.c:dm_read_arg_group
  - drivers/md/dm-table.c:dm_read_arg
  - drivers/md/dm-linear.c:linear_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:parse_histogram
  - drivers/cpufreq/cpufreq.c:store_scaling_setspeed
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/cpufreq.c:store_boost
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_ondemand.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_ondemand.c:store_up_threshold
  - drivers/cpufreq/cpufreq_ondemand.c:store_io_is_busy
  - drivers/cpufreq/cpufreq_conservative.c:store_freq_step
  - drivers/cpufreq/cpufreq_conservative.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_conservative.c:store_down_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_up_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_governor.c:store_sampling_rate
  - drivers/of/of_mdio.c:of_get_phy_id
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:polling_interval_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/governor_userspace.c:store_freq
  - drivers/powercap/powercap_sys.c:show_constraint_name
  - drivers/powercap/powercap_sys.c:show_constraint_min_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_max_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_min_power_uw
  - drivers/powercap/powercap_sys.c:show_constraint_max_power_uw
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:show_constraint_power_limit_uw
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/netprio_cgroup.c:write_priomap
  - net/ipv4/sysctl_net_ipv4.c:sscanf_key
```
**Symbols:**

```
c000000000edbfa0-c000000000edbfe4: sscanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sscanf(const char *buf, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffe0008c0132)
Location: lib/vsprintf.c:3439
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:max_active_store
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_write
  - kernel/cgroup/cgroup.c:cgroup_parse_float
  - mm/hugetlb.c:hugetlb_nrpages_setup
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_answer
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - block/genhd.c:disk_events_poll_msecs_store
  - block/badblocks.c:badblocks_store
  - block/blk-cgroup.c:blkcg_conf_get_disk
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci-driver.c:remove_id_store
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/video/fbdev/core/fbsysfs.c:store_bl_curve
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_timeout
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/spi/spi.c:slave_store
  - drivers/usb/core/driver.c:remove_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/usb/core/sysfs.c:authorized_default_store
  - drivers/usb/core/sysfs.c:authorized_store
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:pps_enable_store
  - drivers/ptp/ptp_sysfs.c:period_store
  - drivers/ptp/ptp_sysfs.c:extts_enable_store
  - drivers/power/supply/charger-manager.c:charger_externally_control_store
  - drivers/thermal/thermal_sysfs.c:cur_state_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_show
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_show
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_type_show
  - drivers/md/dm-table.c:dm_read_arg_group
  - drivers/md/dm-table.c:dm_read_arg
  - drivers/md/dm-linear.c:linear_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/of/of_mdio.c:of_get_phy_id
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:polling_interval_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/governor_userspace.c:store_freq
  - drivers/powercap/powercap_sys.c:show_constraint_name
  - drivers/powercap/powercap_sys.c:show_constraint_min_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_max_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_min_power_uw
  - drivers/powercap/powercap_sys.c:show_constraint_max_power_uw
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:show_constraint_power_limit_uw
  - net/core/netprio_cgroup.c:write_priomap
  - net/ipv4/sysctl_net_ipv4.c:sscanf_key
```
**Symbols:**

```
ffffffe0008c0132-ffffffe0008c0160: sscanf (STB_GLOBAL)
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
int sscanf(const char *buf, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a5a820)
Location: lib/vsprintf.c:3439
Inline: False
Direct callers:
  - arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:max_active_store
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_write
  - kernel/power/main.c:pm_trace_store
  - kernel/power/main.c:wakeup_count_store
  - kernel/power/hibernate.c:resume_offset_setup
  - kernel/power/hibernate.c:reserved_size_store
  - kernel/power/hibernate.c:image_size_store
  - kernel/cgroup/cgroup.c:cgroup_parse_float
  - mm/hugetlb.c:hugetlb_nrpages_setup
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_answer
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - block/genhd.c:disk_events_poll_msecs_store
  - block/badblocks.c:badblocks_store
  - block/blk-cgroup.c:blkcg_conf_get_disk
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci-driver.c:remove_id_store
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/video/fbdev/core/fbsysfs.c:store_bl_curve
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_acpihid
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_hpet
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_ioapic
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_timeout
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/spi/spi.c:slave_store
  - drivers/usb/core/driver.c:remove_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/usb/core/sysfs.c:authorized_default_store
  - drivers/usb/core/sysfs.c:authorized_store
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:pps_enable_store
  - drivers/ptp/ptp_sysfs.c:period_store
  - drivers/ptp/ptp_sysfs.c:extts_enable_store
  - drivers/thermal/thermal_sysfs.c:cur_state_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_show
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_show
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_type_show
  - drivers/md/dm-table.c:dm_read_arg_group
  - drivers/md/dm-table.c:dm_read_arg
  - drivers/md/dm-linear.c:linear_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:parse_histogram
  - drivers/cpufreq/cpufreq.c:store_scaling_setspeed
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/cpufreq.c:store_boost
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_ondemand.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_ondemand.c:store_up_threshold
  - drivers/cpufreq/cpufreq_ondemand.c:store_io_is_busy
  - drivers/cpufreq/cpufreq_conservative.c:store_freq_step
  - drivers/cpufreq/cpufreq_conservative.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_conservative.c:store_down_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_up_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_governor.c:store_sampling_rate
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:polling_interval_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/governor_userspace.c:store_freq
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/netprio_cgroup.c:write_priomap
  - net/ipv4/sysctl_net_ipv4.c:sscanf_key
```
**Symbols:**

```
ffffffff81a5a820-ffffffff81a5a885: sscanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sscanf(const char *buf, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a17900)
Location: lib/vsprintf.c:3439
Inline: False
Direct callers:
  - arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:max_active_store
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_write
  - kernel/power/main.c:pm_trace_store
  - kernel/power/main.c:wakeup_count_store
  - kernel/power/hibernate.c:resume_offset_setup
  - kernel/power/hibernate.c:reserved_size_store
  - kernel/power/hibernate.c:image_size_store
  - kernel/cgroup/cgroup.c:cgroup_parse_float
  - mm/hugetlb.c:hugetlb_nrpages_setup
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_answer
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - block/genhd.c:disk_events_poll_msecs_store
  - block/badblocks.c:badblocks_store
  - block/blk-cgroup.c:blkcg_conf_get_disk
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci-driver.c:remove_id_store
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_acpihid
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_hpet
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_ioapic
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/dax/bus.c:do_id_store
  - drivers/dax/pmem/core.c:__dax_pmem_probe
  - drivers/scsi/scsi_sysfs.c:sdev_store_timeout
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/spi/spi.c:slave_store
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_init
  - drivers/usb/core/driver.c:remove_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/usb/core/sysfs.c:authorized_default_store
  - drivers/usb/core/sysfs.c:authorized_store
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:pps_enable_store
  - drivers/ptp/ptp_sysfs.c:period_store
  - drivers/ptp/ptp_sysfs.c:extts_enable_store
  - drivers/thermal/thermal_sysfs.c:cur_state_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_show
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_show
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_type_show
  - drivers/md/dm-table.c:dm_read_arg_group
  - drivers/md/dm-table.c:dm_read_arg
  - drivers/md/dm-linear.c:linear_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:parse_histogram
  - drivers/cpufreq/cpufreq.c:store_scaling_setspeed
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/cpufreq.c:store_boost
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_ondemand.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_ondemand.c:store_up_threshold
  - drivers/cpufreq/cpufreq_ondemand.c:store_io_is_busy
  - drivers/cpufreq/cpufreq_conservative.c:store_freq_step
  - drivers/cpufreq/cpufreq_conservative.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_conservative.c:store_down_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_up_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_governor.c:store_sampling_rate
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:polling_interval_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/governor_userspace.c:store_freq
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/netprio_cgroup.c:write_priomap
  - net/ipv4/sysctl_net_ipv4.c:sscanf_key
```
**Symbols:**

```
ffffffff81a17900-ffffffff81a17965: sscanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sscanf(const char *buf, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ac6c10)
Location: lib/vsprintf.c:3439
Inline: False
Direct callers:
  - arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:max_active_store
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_write
  - kernel/power/main.c:pm_trace_store
  - kernel/power/main.c:wakeup_count_store
  - kernel/power/hibernate.c:resume_offset_setup
  - kernel/power/hibernate.c:reserved_size_store
  - kernel/power/hibernate.c:image_size_store
  - kernel/cgroup/cgroup.c:cgroup_parse_float
  - mm/hugetlb.c:hugetlb_nrpages_setup
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_answer
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - block/genhd.c:disk_events_poll_msecs_store
  - block/badblocks.c:badblocks_store
  - block/blk-cgroup.c:blkcg_conf_get_disk
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci-driver.c:remove_id_store
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/video/fbdev/core/fbsysfs.c:store_bl_curve
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/battery.c:acpi_battery_alarm_store
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_acpihid
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_hpet
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_ioapic
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_timeout
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/spi/spi.c:slave_store
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_init
  - drivers/usb/core/driver.c:remove_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/usb/core/sysfs.c:authorized_default_store
  - drivers/usb/core/sysfs.c:authorized_store
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:pps_enable_store
  - drivers/ptp/ptp_sysfs.c:period_store
  - drivers/ptp/ptp_sysfs.c:extts_enable_store
  - drivers/power/supply/charger-manager.c:charger_externally_control_store
  - drivers/thermal/thermal_sysfs.c:cur_state_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_show
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_show
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_type_show
  - drivers/md/dm-table.c:dm_read_arg_group
  - drivers/md/dm-table.c:dm_read_arg
  - drivers/md/dm-linear.c:linear_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:parse_histogram
  - drivers/cpufreq/cpufreq.c:store_scaling_setspeed
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/cpufreq.c:store_boost
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_ondemand.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_ondemand.c:store_up_threshold
  - drivers/cpufreq/cpufreq_ondemand.c:store_io_is_busy
  - drivers/cpufreq/cpufreq_conservative.c:store_freq_step
  - drivers/cpufreq/cpufreq_conservative.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_conservative.c:store_down_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_up_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_governor.c:store_sampling_rate
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:polling_interval_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/governor_userspace.c:store_freq
  - drivers/powercap/powercap_sys.c:show_constraint_name
  - drivers/powercap/powercap_sys.c:show_constraint_min_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_max_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_min_power_uw
  - drivers/powercap/powercap_sys.c:show_constraint_max_power_uw
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:show_constraint_power_limit_uw
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/netprio_cgroup.c:write_priomap
  - net/ipv4/sysctl_net_ipv4.c:sscanf_key
```
**Symbols:**

```
ffffffff81ac6c10-ffffffff81ac6c75: sscanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sscanf(const char *buf, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ad30f0)
Location: lib/vsprintf.c:3439
Inline: False
Direct callers:
  - arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:max_active_store
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_write
  - kernel/power/main.c:pm_trace_store
  - kernel/power/main.c:wakeup_count_store
  - kernel/power/hibernate.c:resume_offset_setup
  - kernel/power/hibernate.c:reserved_size_store
  - kernel/power/hibernate.c:image_size_store
  - kernel/cgroup/cgroup.c:cgroup_parse_float
  - mm/hugetlb.c:hugetlb_nrpages_setup
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_answer
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_write_profile
  - block/genhd.c:disk_events_poll_msecs_store
  - block/badblocks.c:badblocks_store
  - block/blk-cgroup.c:blkcg_conf_get_disk
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/pci-driver.c:remove_id_store
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/video/fbdev/core/fbsysfs.c:store_bl_curve
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/battery.c:acpi_battery_alarm_store
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_acpihid
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_hpet
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_ioapic
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_timeout
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/spi/spi.c:slave_store
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_init
  - drivers/usb/core/driver.c:remove_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/usb/core/sysfs.c:authorized_default_store
  - drivers/usb/core/sysfs.c:authorized_store
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:pps_enable_store
  - drivers/ptp/ptp_sysfs.c:period_store
  - drivers/ptp/ptp_sysfs.c:extts_enable_store
  - drivers/power/supply/charger-manager.c:charger_externally_control_store
  - drivers/thermal/thermal_sysfs.c:cur_state_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_show
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_show
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_type_show
  - drivers/md/dm-table.c:dm_read_arg_group
  - drivers/md/dm-table.c:dm_read_arg
  - drivers/md/dm-linear.c:linear_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_print
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/md/dm-stats.c:parse_histogram
  - drivers/cpufreq/cpufreq.c:store_scaling_setspeed
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/cpufreq.c:store_boost
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_ondemand.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_ondemand.c:store_up_threshold
  - drivers/cpufreq/cpufreq_ondemand.c:store_io_is_busy
  - drivers/cpufreq/cpufreq_conservative.c:store_freq_step
  - drivers/cpufreq/cpufreq_conservative.c:store_ignore_nice_load
  - drivers/cpufreq/cpufreq_conservative.c:store_down_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_up_threshold
  - drivers/cpufreq/cpufreq_conservative.c:store_sampling_down_factor
  - drivers/cpufreq/cpufreq_governor.c:store_sampling_rate
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/devfreq/devfreq.c:max_freq_store
  - drivers/devfreq/devfreq.c:min_freq_store
  - drivers/devfreq/devfreq.c:polling_interval_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/governor_userspace.c:store_freq
  - drivers/powercap/powercap_sys.c:show_constraint_name
  - drivers/powercap/powercap_sys.c:show_constraint_min_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_max_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_min_power_uw
  - drivers/powercap/powercap_sys.c:show_constraint_max_power_uw
  - drivers/powercap/powercap_sys.c:store_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:show_constraint_time_window_us
  - drivers/powercap/powercap_sys.c:store_constraint_power_limit_uw
  - drivers/powercap/powercap_sys.c:show_constraint_power_limit_uw
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/netprio_cgroup.c:write_priomap
  - net/ipv4/sysctl_net_ipv4.c:sscanf_key
```
**Symbols:**

```
ffffffff81ad30f0-ffffffff81ad3155: sscanf (STB_GLOBAL)
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
