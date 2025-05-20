# Function: <code>kstrtouint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kstrtouint(const char *s, unsigned int base, unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81401e50)
Location: lib/kstrtox.c:218
Inline: False
Direct callers:
  - arch/x86/events/intel/cqm.c:max_recycle_threshold_store
  - kernel/params.c:param_set_uint
  - kernel/power/hibernate.c:resumedelay_setup
  - kernel/hung_task.c:hung_task_panic_setup
  - mm/backing-dev.c:max_ratio_store
  - mm/backing-dev.c:min_ratio_store
  - fs/fuse/inode.c:fuse_match_uint
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - lib/kstrtox.c:kstrtouint_from_user
  - lib/dynamic_debug.c:ddebug_exec_query
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pwm/sysfs.c:unexport_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/pcie/aspm.c:link_state_store
  - drivers/acpi/sysfs.c:hotplug_enabled_store
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout
  - drivers/scsi/sd.c:max_medium_access_timeouts_store
  - drivers/scsi/sd.c:protection_type_store
  - drivers/usb/host/ehci-hcd.c:store_uframe_periodic_max
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/thermal/thermal_core.c:sustainable_power_store
  - drivers/md/md.c:sync_max_store
  - drivers/md/md.c:sync_min_store
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:errors_store
  - drivers/md/md.c:set_ro
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:slot_store
  - drivers/md/dm.c:dm_attr_rq_based_seq_io_merge_deadline_store
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/clocksource/acpi_pm.c:parse_pmtmr
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/net-sysfs.c:bql_set
  - net/core/net-sysfs.c:set_tx_maxrate
  - net/ipv4/tcp_metrics.c:set_tcpmhash_entries
```
**Symbols:**

```
ffffffff81401e50-ffffffff81401eb2: kstrtouint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kstrtouint(const char *s, unsigned int base, unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81449900)
Location: lib/kstrtox.c:218
Inline: False
Direct callers:
  - arch/x86/events/intel/cqm.c:max_recycle_threshold_store
  - kernel/params.c:param_set_uint
  - kernel/power/hibernate.c:resumedelay_setup
  - kernel/hung_task.c:hung_task_panic_setup
  - mm/backing-dev.c:max_ratio_store
  - mm/backing-dev.c:min_ratio_store
  - fs/fuse/inode.c:fuse_match_uint
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - lib/kstrtox.c:kstrtouint_from_user
  - lib/dynamic_debug.c:ddebug_exec_query
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pwm/sysfs.c:unexport_store
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
  - drivers/pci/pcie/aspm.c:link_state_store
  - drivers/acpi/sysfs.c:hotplug_enabled_store
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout
  - drivers/scsi/sd.c:max_medium_access_timeouts_store
  - drivers/scsi/sd.c:protection_type_store
  - drivers/usb/host/ehci-hcd.c:store_uframe_periodic_max
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/thermal/thermal_core.c:sustainable_power_store
  - drivers/md/md.c:set_ro
  - drivers/md/md.c:sync_max_store
  - drivers/md/md.c:sync_min_store
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:errors_store
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-rq.c:dm_attr_rq_based_seq_io_merge_deadline_store
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
  - drivers/clocksource/acpi_pm.c:parse_pmtmr
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/net-sysfs.c:bql_set
  - net/core/net-sysfs.c:set_tx_maxrate
  - net/ipv4/tcp_metrics.c:set_tcpmhash_entries
```
**Symbols:**

```
ffffffff81449900-ffffffff81449962: kstrtouint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kstrtouint(const char *s, unsigned int base, unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff814682c0)
Location: lib/kstrtox.c:214
Inline: False
Direct callers:
  - arch/x86/events/intel/cqm.c:max_recycle_threshold_store
  - arch/x86/mm/pkeys.c:setup_init_pkru
  - arch/x86/mm/pkeys.c:init_pkru_write_file
  - kernel/params.c:param_set_uint
  - kernel/sched/cpufreq_schedutil.c:rate_limit_us_store
  - kernel/power/hibernate.c:resumedelay_setup
  - kernel/hung_task.c:hung_task_panic_setup
  - mm/backing-dev.c:max_ratio_store
  - mm/backing-dev.c:min_ratio_store
  - fs/fuse/inode.c:fuse_match_uint
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - lib/kstrtox.c:kstrtouint_from_user
  - lib/dynamic_debug.c:ddebug_exec_query
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pwm/sysfs.c:unexport_store
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
  - drivers/pci/pcie/aspm.c:link_state_store
  - drivers/acpi/sysfs.c:hotplug_enabled_store
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout
  - drivers/scsi/sd.c:max_medium_access_timeouts_store
  - drivers/scsi/sd.c:protection_type_store
  - drivers/usb/host/ehci-hcd.c:store_uframe_periodic_max
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
  - drivers/md/md.c:set_ro
  - drivers/md/md.c:sync_max_store
  - drivers/md/md.c:sync_min_store
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:errors_store
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-rq.c:dm_attr_rq_based_seq_io_merge_deadline_store
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
  - drivers/clocksource/acpi_pm.c:parse_pmtmr
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/net-sysfs.c:bql_set
  - net/core/net-sysfs.c:set_tx_maxrate
  - net/ipv4/tcp_metrics.c:set_tcpmhash_entries
```
**Symbols:**

```
ffffffff814682c0-ffffffff81468322: kstrtouint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kstrtouint(const char *s, unsigned int base, unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8146d9c0)
Location: lib/kstrtox.c:216
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:max_threshold_occ_write
  - arch/x86/mm/pkeys.c:setup_init_pkru
  - arch/x86/mm/pkeys.c:init_pkru_write_file
  - kernel/params.c:param_set_uint
  - kernel/sched/cpufreq_schedutil.c:rate_limit_us_store
  - kernel/power/hibernate.c:resumedelay_setup
  - kernel/hung_task.c:hung_task_panic_setup
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - mm/backing-dev.c:max_ratio_store
  - mm/backing-dev.c:min_ratio_store
  - fs/fuse/inode.c:fuse_match_uint
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - lib/kstrtox.c:kstrtouint_from_user
  - lib/dynamic_debug.c:ddebug_exec_query
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pwm/sysfs.c:unexport_store
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
  - drivers/pci/pcie/aspm.c:link_state_store
  - drivers/acpi/sysfs.c:hotplug_enabled_store
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout
  - drivers/scsi/sd.c:max_medium_access_timeouts_store
  - drivers/scsi/sd.c:protection_type_store
  - drivers/usb/host/ehci-hcd.c:store_uframe_periodic_max
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
  - drivers/md/md.c:set_ro
  - drivers/md/md.c:sync_max_store
  - drivers/md/md.c:sync_min_store
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:ppl_size_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:errors_store
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-rq.c:dm_attr_rq_based_seq_io_merge_deadline_store
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
  - drivers/clocksource/acpi_pm.c:parse_pmtmr
  - net/core/utils.c:inet6_pton
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/net-sysfs.c:bql_set
  - net/core/net-sysfs.c:set_tx_maxrate
```
**Symbols:**

```
ffffffff8146d9c0-ffffffff8146da24: kstrtouint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kstrtouint(const char *s, unsigned int base, unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81499cf0)
Location: lib/kstrtox.c:217
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:max_threshold_occ_write
  - arch/x86/mm/pkeys.c:setup_init_pkru
  - arch/x86/mm/pkeys.c:init_pkru_write_file
  - kernel/params.c:param_set_uint
  - kernel/sched/cpufreq_schedutil.c:rate_limit_us_store
  - kernel/power/hibernate.c:resumedelay_setup
  - kernel/hung_task.c:hung_task_panic_setup
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - mm/backing-dev.c:max_ratio_store
  - mm/backing-dev.c:min_ratio_store
  - fs/fuse/inode.c:fuse_match_uint
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - lib/kstrtox.c:kstrtouint_from_user
  - lib/dynamic_debug.c:ddebug_exec_query
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pwm/sysfs.c:unexport_store
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
  - drivers/pci/pcie/aspm.c:link_state_store
  - drivers/acpi/sysfs.c:hotplug_enabled_store
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout
  - drivers/scsi/sd.c:max_medium_access_timeouts_store
  - drivers/scsi/sd.c:protection_type_store
  - drivers/usb/host/ehci-hcd.c:store_uframe_periodic_max
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
  - drivers/md/md.c:set_ro
  - drivers/md/md.c:sync_max_store
  - drivers/md/md.c:sync_min_store
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:ppl_size_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:errors_store
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-rq.c:dm_attr_rq_based_seq_io_merge_deadline_store
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
  - drivers/clocksource/acpi_pm.c:parse_pmtmr
  - net/core/utils.c:inet6_pton
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/net-sysfs.c:bql_set
  - net/core/net-sysfs.c:tx_maxrate_store
```
**Symbols:**

```
ffffffff81499cf0-ffffffff81499d54: kstrtouint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kstrtouint(const char *s, unsigned int base, unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff814cefa0)
Location: lib/kstrtox.c:217
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:max_threshold_occ_write
  - arch/x86/mm/pkeys.c:setup_init_pkru
  - arch/x86/mm/pkeys.c:init_pkru_write_file
  - kernel/params.c:param_set_uint
  - kernel/sched/cpufreq_schedutil.c:rate_limit_us_store
  - kernel/power/hibernate.c:resumedelay_setup
  - kernel/audit.c:audit_backlog_limit_set
  - kernel/hung_task.c:hung_task_panic_setup
  - kernel/trace/trace_events_hist.c:create_synth_event
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - mm/backing-dev.c:max_ratio_store
  - mm/backing-dev.c:min_ratio_store
  - mm/slub.c:remote_node_defrag_ratio_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:order_store
  - mm/memtest.c:parse_memtest
  - fs/fuse/inode.c:fuse_match_uint
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - lib/kstrtox.c:kstrtouint_from_user
  - lib/dynamic_debug.c:ddebug_exec_query
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pwm/sysfs.c:unexport_store
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
  - drivers/pci/pcie/aspm.c:link_state_store
  - drivers/acpi/sysfs.c:hotplug_enabled_store
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout
  - drivers/scsi/sd.c:max_medium_access_timeouts_store
  - drivers/scsi/sd.c:protection_type_store
  - drivers/usb/core/port.c:quirks_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
  - drivers/md/md.c:set_ro
  - drivers/md/md.c:sync_max_store
  - drivers/md/md.c:sync_min_store
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:ppl_size_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:errors_store
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-rq.c:dm_attr_rq_based_seq_io_merge_deadline_store
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/clocksource/acpi_pm.c:parse_pmtmr
  - net/core/utils.c:inet6_pton
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/net-sysfs.c:bql_set
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/ipv4/tcp_metrics.c:set_tcpmhash_entries
```
**Symbols:**

```
ffffffff814cefa0-ffffffff814cf004: kstrtouint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kstrtouint(const char *s, unsigned int base, unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff814e38b0)
Location: lib/kstrtox.c:217
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:max_threshold_occ_write
  - arch/x86/mm/pkeys.c:setup_init_pkru
  - arch/x86/mm/pkeys.c:init_pkru_write_file
  - kernel/params.c:param_set_uint
  - kernel/sched/cpufreq_schedutil.c:rate_limit_us_store
  - kernel/power/hibernate.c:resumedelay_setup
  - kernel/audit.c:audit_backlog_limit_set
  - kernel/hung_task.c:hung_task_panic_setup
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - mm/backing-dev.c:max_ratio_store
  - mm/backing-dev.c:min_ratio_store
  - mm/slub.c:remote_node_defrag_ratio_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:order_store
  - mm/memtest.c:parse_memtest
  - fs/fuse/inode.c:fuse_match_uint
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - block/blk-sysfs.c:queue_io_timeout_store
  - lib/kstrtox.c:kstrtouint_from_user
  - lib/dynamic_debug.c:ddebug_exec_query
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pwm/sysfs.c:unexport_store
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
  - drivers/pci/pcie/aspm.c:link_state_store
  - drivers/acpi/sysfs.c:hotplug_enabled_store
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout
  - drivers/scsi/sd.c:max_medium_access_timeouts_store
  - drivers/scsi/sd.c:protection_type_store
  - drivers/usb/core/port.c:quirks_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
  - drivers/md/md.c:set_ro
  - drivers/md/md.c:sync_max_store
  - drivers/md/md.c:sync_min_store
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:ppl_size_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:errors_store
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/clocksource/acpi_pm.c:parse_pmtmr
  - net/core/utils.c:inet6_pton
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/net-sysfs.c:bql_set
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/ipv4/tcp_metrics.c:set_tcpmhash_entries
```
**Symbols:**

```
ffffffff814e38b0-ffffffff814e3914: kstrtouint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kstrtouint(const char *s, unsigned int base, unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8150fc90)
Location: lib/kstrtox.c:217
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:max_threshold_occ_write
  - arch/x86/mm/pkeys.c:setup_init_pkru
  - arch/x86/mm/pkeys.c:init_pkru_write_file
  - kernel/params.c:param_set_uint
  - kernel/sched/cpufreq_schedutil.c:rate_limit_us_store
  - kernel/power/hibernate.c:resumedelay_setup
  - kernel/audit.c:audit_backlog_limit_set
  - kernel/hung_task.c:hung_task_panic_setup
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - mm/backing-dev.c:max_ratio_store
  - mm/backing-dev.c:min_ratio_store
  - mm/slub.c:remote_node_defrag_ratio_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:order_store
  - mm/memtest.c:parse_memtest
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/fuse/inode.c:fuse_match_uint
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - block/blk-sysfs.c:queue_io_timeout_store
  - lib/kstrtox.c:kstrtouint_from_user
  - lib/dynamic_debug.c:ddebug_exec_query
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pwm/sysfs.c:unexport_store
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
  - drivers/pci/pcie/aspm.c:link_state_store
  - drivers/acpi/sysfs.c:hotplug_enabled_store
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/nvdimm/dimm_devs.c:__security_store
  - drivers/nvdimm/dimm_devs.c:__security_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout
  - drivers/scsi/sd.c:max_medium_access_timeouts_store
  - drivers/scsi/sd.c:protection_type_store
  - drivers/usb/core/port.c:quirks_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
  - drivers/md/md.c:set_ro
  - drivers/md/md.c:sync_max_store
  - drivers/md/md.c:sync_min_store
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:ppl_size_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:errors_store
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/clocksource/acpi_pm.c:parse_pmtmr
  - net/core/utils.c:inet6_pton
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/net-sysfs.c:bql_set
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/ipv4/tcp_metrics.c:set_tcpmhash_entries
```
**Symbols:**

```
ffffffff8150fc90-ffffffff8150fcf4: kstrtouint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kstrtouint(const char *s, unsigned int base, unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8152db90)
Location: lib/kstrtox.c:217
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:max_threshold_occ_write
  - arch/x86/mm/pkeys.c:setup_init_pkru
  - arch/x86/mm/pkeys.c:init_pkru_write_file
  - kernel/params.c:param_set_uint
  - kernel/sched/cpufreq_schedutil.c:rate_limit_us_store
  - kernel/power/hibernate.c:resumedelay_setup
  - kernel/audit.c:audit_backlog_limit_set
  - kernel/hung_task.c:hung_task_panic_setup
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - mm/backing-dev.c:max_ratio_store
  - mm/backing-dev.c:min_ratio_store
  - mm/slub.c:remote_node_defrag_ratio_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:order_store
  - mm/memtest.c:parse_memtest
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - block/blk-sysfs.c:queue_io_timeout_store
  - lib/kstrtox.c:kstrtouint_from_user
  - lib/dynamic_debug.c:ddebug_exec_query
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pwm/sysfs.c:unexport_store
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
  - drivers/acpi/sysfs.c:hotplug_enabled_store
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout
  - drivers/scsi/sd.c:max_medium_access_timeouts_store
  - drivers/scsi/sd.c:protection_type_store
  - drivers/usb/core/port.c:quirks_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/input/input-poller.c:input_dev_set_poll_interval
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
  - drivers/md/md.c:set_ro
  - drivers/md/md.c:sync_max_store
  - drivers/md/md.c:sync_min_store
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:ppl_size_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:errors_store
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/clocksource/acpi_pm.c:parse_pmtmr
  - net/core/utils.c:inet6_pton
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/net-sysfs.c:bql_set
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/ipv4/tcp_metrics.c:set_tcpmhash_entries
```
**Symbols:**

```
ffffffff8152db90-ffffffff8152dbf4: kstrtouint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int kstrtouint(const char *s, unsigned int base, unsigned int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81591deb)
Location: lib/kstrtox.c:217
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtouint_from_user
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_early_khz_setup
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:max_threshold_occ_write
  - arch/x86/mm/pkeys.c:setup_init_pkru
  - arch/x86/mm/pkeys.c:init_pkru_write_file
  - kernel/params.c:param_set_uint
  - kernel/sched/cpufreq_schedutil.c:rate_limit_us_store
  - kernel/power/hibernate.c:resumedelay_setup
  - kernel/audit.c:audit_backlog_limit_set
  - kernel/trace/trace_events_synth.c:synth_field_string_size
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - mm/backing-dev.c:max_ratio_store
  - mm/backing-dev.c:min_ratio_store
  - mm/slub.c:remote_node_defrag_ratio_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:order_store
  - mm/memtest.c:parse_memtest
  - fs/fs_parser.c:fs_param_is_fd
  - fs/fs_parser.c:fs_param_is_u32
  - fs/proc/root.c:proc_parse_param
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/safesetid/securityfs.c:parse_policy_line
  - security/safesetid/securityfs.c:parse_policy_line
  - security/device_cgroup.c:devcgroup_update_access
  - security/device_cgroup.c:devcgroup_update_access
  - block/blk-sysfs.c:queue_io_timeout_store
  - lib/dynamic_debug.c:ddebug_parse_query
  - lib/dynamic_debug.c:ddebug_parse_query
  - drivers/pwm/sysfs.c:unexport_store
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
  - drivers/acpi/sysfs.c:hotplug_enabled_store
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout
  - drivers/scsi/sd.c:max_medium_access_timeouts_store
  - drivers/scsi/sd.c:protection_type_store
  - drivers/usb/core/port.c:quirks_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/input/input-poller.c:input_dev_set_poll_interval
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
  - drivers/watchdog/watchdog_dev.c:nowayout_store
  - drivers/md/md.c:set_ro
  - drivers/md/md.c:sync_max_store
  - drivers/md/md.c:sync_min_store
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:ppl_size_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:errors_store
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpuidle/sysfs.c:store_state_disable
  - drivers/clocksource/acpi_pm.c:parse_pmtmr
  - net/core/utils.c:inet6_pton
  - net/core/net-sysfs.c:bql_set_limit_min
  - net/core/net-sysfs.c:bql_set_limit_max
  - net/core/net-sysfs.c:bql_set_limit
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/ipv4/tcp_metrics.c:set_tcpmhash_entries
```
**Symbols:**

```
ffffffff81591ac0-ffffffff81591b23: kstrtouint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int kstrtouint(const char *s, unsigned int base, unsigned int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff815ae92b)
Location: lib/kstrtox.c:214
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtouint_from_user
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_early_khz_setup
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:max_threshold_occ_write
  - arch/x86/mm/pkeys.c:setup_init_pkru
  - arch/x86/mm/pkeys.c:init_pkru_write_file
  - kernel/reboot.c:cpu_store
  - kernel/sched/cpufreq_schedutil.c:rate_limit_us_store
  - kernel/power/hibernate.c:resumedelay_setup
  - kernel/audit.c:audit_backlog_limit_set
  - kernel/trace/trace_events_synth.c:synth_field_string_size
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - mm/backing-dev.c:max_ratio_store
  - mm/backing-dev.c:min_ratio_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
  - mm/slub.c:remote_node_defrag_ratio_store
  - mm/slub.c:cpu_partial_store
  - mm/memtest.c:parse_memtest
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
  - fs/fs_parser.c:fs_param_is_fd
  - fs/fs_parser.c:fs_param_is_u32
  - fs/proc/root.c:proc_parse_param
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/safesetid/securityfs.c:parse_policy_line
  - security/safesetid/securityfs.c:parse_policy_line
  - security/device_cgroup.c:devcgroup_update_access
  - security/device_cgroup.c:devcgroup_update_access
  - block/blk-sysfs.c:queue_io_timeout_store
  - lib/dynamic_debug.c:parse_linerange
  - lib/dynamic_debug.c:parse_linerange
  - drivers/pwm/sysfs.c:unexport_store
  - drivers/pwm/sysfs.c:export_store
  - drivers/acpi/sysfs.c:hotplug_enabled_store
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout
  - drivers/scsi/sd.c:max_medium_access_timeouts_store
  - drivers/scsi/sd.c:protection_type_store
  - drivers/usb/core/port.c:quirks_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/input/input-poller.c:input_dev_set_poll_interval
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
  - drivers/watchdog/watchdog_dev.c:nowayout_store
  - drivers/md/md.c:set_ro
  - drivers/md/md.c:sync_max_store
  - drivers/md/md.c:sync_min_store
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:ppl_size_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:errors_store
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpuidle/sysfs.c:store_state_disable
  - drivers/clocksource/acpi_pm.c:parse_pmtmr
  - net/core/utils.c:inet6_pton
  - net/core/net-sysfs.c:bql_set_limit_min
  - net/core/net-sysfs.c:bql_set_limit_max
  - net/core/net-sysfs.c:bql_set_limit
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/ipv4/tcp_metrics.c:set_tcpmhash_entries
```
**Symbols:**

```
ffffffff815ae600-ffffffff815ae663: kstrtouint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int kstrtouint(const char *s, unsigned int base, unsigned int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff815b936b)
Location: lib/kstrtox.c:221
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtouint_from_user
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_early_khz_setup
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:max_threshold_occ_write
  - arch/x86/mm/pkeys.c:setup_init_pkru
  - arch/x86/mm/pkeys.c:init_pkru_write_file
  - kernel/reboot.c:cpu_store
  - kernel/sched/debug.c:sched_scaling_write
  - kernel/sched/cpufreq_schedutil.c:rate_limit_us_store
  - kernel/power/hibernate.c:resumedelay_setup
  - kernel/audit.c:audit_backlog_limit_set
  - kernel/trace/trace_events_synth.c:synth_field_string_size
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - mm/backing-dev.c:max_ratio_store
  - mm/backing-dev.c:min_ratio_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
  - mm/slub.c:remote_node_defrag_ratio_store
  - mm/slub.c:cpu_partial_store
  - mm/memtest.c:parse_memtest
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
  - fs/fs_parser.c:fs_param_is_fd
  - fs/fs_parser.c:fs_param_is_u32
  - fs/proc/root.c:proc_parse_param
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
  - security/device_cgroup.c:devcgroup_update_access
  - security/device_cgroup.c:devcgroup_update_access
  - block/blk-sysfs.c:queue_io_timeout_store
  - lib/parser.c:match_uint
  - lib/dynamic_debug.c:parse_linerange
  - lib/dynamic_debug.c:parse_linerange
  - drivers/pwm/sysfs.c:unexport_store
  - drivers/pwm/sysfs.c:export_store
  - drivers/acpi/sysfs.c:hotplug_enabled_store
  - drivers/xen/xenbus/xenbus_probe.c:set_spurious_threshold
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/base/swnode.c:software_node_graph_parse_endpoint
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout
  - drivers/scsi/sd.c:max_medium_access_timeouts_store
  - drivers/scsi/sd.c:protection_type_store
  - drivers/usb/core/port.c:quirks_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/input/input-poller.c:input_dev_set_poll_interval
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
  - drivers/watchdog/watchdog_dev.c:nowayout_store
  - drivers/md/md.c:set_ro
  - drivers/md/md.c:sync_max_store
  - drivers/md/md.c:sync_min_store
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:ppl_size_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:errors_store
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpuidle/sysfs.c:store_state_disable
  - drivers/clocksource/acpi_pm.c:parse_pmtmr
  - drivers/platform/x86/intel_pmc_core.c:etr3_store
  - net/core/utils.c:inet6_pton
  - net/core/net-sysfs.c:bql_set_limit_min
  - net/core/net-sysfs.c:bql_set_limit_max
  - net/core/net-sysfs.c:bql_set_limit
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/ipv4/tcp_metrics.c:set_tcpmhash_entries
```
**Symbols:**

```
ffffffff815b91e0-ffffffff815b9243: kstrtouint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int kstrtouint(const char *s, unsigned int base, unsigned int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8161fc21)
Location: lib/kstrtox.c:222
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtouint_from_user
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_early_khz_setup
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:max_threshold_occ_write
  - arch/x86/mm/pkeys.c:setup_init_pkru
  - arch/x86/mm/pkeys.c:init_pkru_write_file
  - kernel/params.c:param_set_uint_minmax
  - kernel/reboot.c:cpu_store
  - kernel/sched/debug.c:sched_scaling_write
  - kernel/sched/cpufreq_schedutil.c:rate_limit_us_store
  - kernel/power/hibernate.c:resumedelay_setup
  - kernel/audit.c:audit_backlog_limit_set
  - kernel/trace/trace_events_synth.c:synth_field_string_size
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - mm/backing-dev.c:max_ratio_store
  - mm/backing-dev.c:min_ratio_store
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
  - mm/slub.c:remote_node_defrag_ratio_store
  - mm/slub.c:cpu_partial_store
  - mm/memtest.c:parse_memtest
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
  - fs/fs_parser.c:fs_param_is_fd
  - fs/fs_parser.c:fs_param_is_u32
  - fs/proc/root.c:proc_parse_param
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
  - security/device_cgroup.c:devcgroup_update_access
  - security/device_cgroup.c:devcgroup_update_access
  - block/blk-sysfs.c:queue_io_timeout_store
  - lib/parser.c:match_uint
  - lib/dynamic_debug.c:parse_linerange
  - lib/dynamic_debug.c:parse_linerange
  - drivers/pwm/sysfs.c:unexport_store
  - drivers/pwm/sysfs.c:export_store
  - drivers/acpi/sysfs.c:enabled_store
  - drivers/xen/xenbus/xenbus_probe.c:spurious_threshold_store
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/base/swnode.c:software_node_graph_parse_endpoint
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout
  - drivers/scsi/sd.c:max_medium_access_timeouts_store
  - drivers/scsi/sd.c:protection_type_store
  - drivers/usb/core/port.c:quirks_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/input/input-poller.c:input_dev_set_poll_interval
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/ptp/ptp_sysfs.c:max_vclocks_store
  - drivers/ptp/ptp_sysfs.c:n_vclocks_store
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
  - drivers/watchdog/watchdog_dev.c:nowayout_store
  - drivers/md/md.c:set_ro
  - drivers/md/md.c:sync_max_store
  - drivers/md/md.c:sync_min_store
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:ppl_size_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:errors_store
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpuidle/sysfs.c:store_state_disable
  - drivers/clocksource/acpi_pm.c:parse_pmtmr
  - drivers/platform/x86/intel/pmc/core.c:etr3_store
  - net/core/utils.c:inet6_pton
  - net/core/net-sysfs.c:bql_set_limit_min
  - net/core/net-sysfs.c:bql_set_limit_max
  - net/core/net-sysfs.c:bql_set_limit
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/ipv4/tcp_metrics.c:set_tcpmhash_entries
```
**Symbols:**

```
ffffffff8161fa70-ffffffff8161fad3: kstrtouint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kstrtouint(const char *s, unsigned int base, unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff816edd10)
Location: lib/kstrtox.c:228
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_early_khz_setup
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:max_threshold_occ_write
  - arch/x86/mm/pkeys.c:setup_init_pkru
  - arch/x86/mm/pkeys.c:init_pkru_write_file
  - kernel/params.c:param_set_uint_minmax
  - kernel/reboot.c:cpu_store
  - kernel/sched/build_utility.c:sched_scaling_write
  - kernel/sched/build_utility.c:rate_limit_us_store
  - kernel/power/hibernate.c:resumedelay_setup
  - kernel/audit.c:audit_backlog_limit_set
  - kernel/trace/trace_events_synth.c:synth_field_string_size
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - mm/backing-dev.c:max_ratio_store
  - mm/backing-dev.c:min_ratio_store
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
  - mm/slub.c:remote_node_defrag_ratio_store
  - mm/slub.c:cpu_partial_store
  - mm/memtest.c:parse_memtest
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
  - fs/fs_parser.c:fs_param_is_fd
  - fs/fs_parser.c:fs_param_is_u32
  - fs/proc/root.c:proc_parse_param
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
  - security/device_cgroup.c:devcgroup_update_access
  - security/device_cgroup.c:devcgroup_update_access
  - block/blk-sysfs.c:queue_io_timeout_store
  - lib/parser.c:match_uint
  - lib/kstrtox.c:kstrtouint_from_user
  - lib/dynamic_debug.c:parse_linerange
  - lib/dynamic_debug.c:parse_linerange
  - lib/dynamic_debug.c:parse_linerange
  - drivers/pwm/sysfs.c:unexport_store
  - drivers/pwm/sysfs.c:export_store
  - drivers/acpi/sysfs.c:enabled_store
  - drivers/xen/xenbus/xenbus_probe.c:spurious_threshold_store
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/base/swnode.c:software_node_graph_parse_endpoint
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout
  - drivers/scsi/sd.c:max_medium_access_timeouts_store
  - drivers/scsi/sd.c:protection_type_store
  - drivers/usb/core/port.c:quirks_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/input/input-poller.c:input_dev_set_poll_interval
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/ptp/ptp_sysfs.c:max_vclocks_store
  - drivers/ptp/ptp_sysfs.c:n_vclocks_store
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
  - drivers/watchdog/watchdog_dev.c:nowayout_store
  - drivers/md/md.c:set_ro
  - drivers/md/md.c:sync_max_store
  - drivers/md/md.c:sync_min_store
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:ppl_size_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:errors_store
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpuidle/sysfs.c:store_state_disable
  - drivers/clocksource/acpi_pm.c:parse_pmtmr
  - drivers/platform/x86/intel/pmc/core.c:etr3_store
  - net/core/utils.c:inet6_pton
  - net/core/net-sysfs.c:bql_set_limit_min
  - net/core/net-sysfs.c:bql_set_limit_max
  - net/core/net-sysfs.c:bql_set_limit
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/ipv4/tcp_metrics.c:set_tcpmhash_entries
```
**Symbols:**

```
ffffffff816edd10-ffffffff816edd7e: kstrtouint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kstrtouint(const char *s, unsigned int base, unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff817de7a0)
Location: lib/kstrtox.c:228
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_early_khz_setup
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:max_threshold_occ_write
  - arch/x86/mm/pkeys.c:setup_init_pkru
  - arch/x86/mm/pkeys.c:init_pkru_write_file
  - kernel/params.c:param_set_uint_minmax
  - kernel/reboot.c:cpu_store
  - kernel/sched/build_utility.c:sched_scaling_write
  - kernel/sched/build_utility.c:rate_limit_us_store
  - kernel/power/hibernate.c:resumedelay_setup
  - kernel/audit.c:audit_backlog_limit_set
  - kernel/trace/trace_events_synth.c:synth_field_string_size
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - mm/vmscan.c:store_enabled
  - mm/vmscan.c:store_min_ttl
  - mm/backing-dev.c:strict_limit_store
  - mm/backing-dev.c:max_ratio_fine_store
  - mm/backing-dev.c:max_ratio_store
  - mm/backing-dev.c:min_ratio_fine_store
  - mm/backing-dev.c:min_ratio_store
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
  - mm/slub.c:remote_node_defrag_ratio_store
  - mm/slub.c:cpu_partial_store
  - mm/memtest.c:parse_memtest
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
  - fs/fs_parser.c:fs_param_is_fd
  - fs/fs_parser.c:fs_param_is_u32
  - fs/proc/root.c:proc_parse_param
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
  - security/device_cgroup.c:devcgroup_update_access
  - security/device_cgroup.c:devcgroup_update_access
  - block/blk-sysfs.c:queue_io_timeout_store
  - lib/parser.c:match_uint
  - lib/kstrtox.c:kstrtouint_from_user
  - lib/dynamic_debug.c:parse_linerange
  - lib/dynamic_debug.c:parse_linerange
  - lib/dynamic_debug.c:parse_linerange
  - drivers/pwm/sysfs.c:unexport_store
  - drivers/pwm/sysfs.c:export_store
  - drivers/acpi/sysfs.c:enabled_store
  - drivers/xen/xenbus/xenbus_probe.c:spurious_threshold_store
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/base/swnode.c:software_node_graph_parse_endpoint
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout
  - drivers/scsi/sd.c:max_medium_access_timeouts_store
  - drivers/scsi/sd.c:protection_type_store
  - drivers/usb/core/port.c:quirks_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/input/input-poller.c:input_dev_set_poll_interval
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/ptp/ptp_sysfs.c:max_vclocks_store
  - drivers/ptp/ptp_sysfs.c:n_vclocks_store
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
  - drivers/watchdog/watchdog_dev.c:nowayout_store
  - drivers/md/md.c:set_ro
  - drivers/md/md.c:sync_max_store
  - drivers/md/md.c:sync_min_store
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:ppl_size_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:errors_store
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpuidle/sysfs.c:store_state_disable
  - drivers/clocksource/acpi_pm.c:parse_pmtmr
  - drivers/platform/x86/intel/pmc/core.c:etr3_store
  - net/core/utils.c:inet6_pton
  - net/core/net-sysfs.c:bql_set_limit_min
  - net/core/net-sysfs.c:bql_set_limit_max
  - net/core/net-sysfs.c:bql_set_limit
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/ipv4/tcp_metrics.c:set_tcpmhash_entries
```
**Symbols:**

```
ffffffff817de7a0-ffffffff817de80e: kstrtouint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kstrtouint(const char *s, unsigned int base, unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8181df80)
Location: lib/kstrtox.c:228
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:debug_alt
  - arch/x86/kernel/tsc.c:tsc_early_khz_setup
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:max_threshold_occ_write
  - arch/x86/mm/pkeys.c:setup_init_pkru
  - arch/x86/mm/pkeys.c:init_pkru_write_file
  - kernel/params.c:param_set_uint_minmax
  - kernel/reboot.c:cpu_store
  - kernel/sched/build_utility.c:sched_scaling_write
  - kernel/sched/build_utility.c:rate_limit_us_store
  - kernel/power/hibernate.c:resumedelay_setup
  - kernel/audit.c:audit_backlog_limit_set
  - kernel/trace/trace_events_synth.c:synth_field_string_size
  - kernel/trace/trace_events_user.c:user_event_parse_field
  - kernel/trace/trace_events_user.c:user_field_array_size
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_fprobe.c:__trace_fprobe_create
  - mm/vmscan.c:enabled_store
  - mm/vmscan.c:min_ttl_ms_store
  - mm/backing-dev.c:strict_limit_store
  - mm/backing-dev.c:max_ratio_fine_store
  - mm/backing-dev.c:max_ratio_store
  - mm/backing-dev.c:min_ratio_fine_store
  - mm/backing-dev.c:min_ratio_store
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
  - mm/slub.c:remote_node_defrag_ratio_store
  - mm/slub.c:cpu_partial_store
  - mm/memtest.c:parse_memtest
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
  - fs/fs_parser.c:fs_param_is_fd
  - fs/fs_parser.c:fs_param_is_u32
  - fs/proc/root.c:proc_parse_param
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
  - security/device_cgroup.c:devcgroup_update_access
  - security/device_cgroup.c:devcgroup_update_access
  - block/blk-sysfs.c:queue_io_timeout_store
  - lib/parser.c:match_uint
  - lib/kstrtox.c:kstrtouint_from_user
  - lib/dynamic_debug.c:parse_linerange
  - lib/dynamic_debug.c:parse_linerange
  - lib/dynamic_debug.c:parse_linerange
  - drivers/pwm/sysfs.c:unexport_store
  - drivers/pwm/sysfs.c:export_store
  - drivers/acpi/sysfs.c:enabled_store
  - drivers/xen/xenbus/xenbus_probe.c:spurious_threshold_store
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/base/swnode.c:software_node_graph_parse_endpoint
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout
  - drivers/scsi/sd.c:max_medium_access_timeouts_store
  - drivers/scsi/sd.c:protection_type_store
  - drivers/usb/core/port.c:quirks_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/input/input-poller.c:input_dev_set_poll_interval
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/ptp/ptp_sysfs.c:max_vclocks_store
  - drivers/ptp/ptp_sysfs.c:n_vclocks_store
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
  - drivers/watchdog/watchdog_dev.c:nowayout_store
  - drivers/md/md.c:set_ro
  - drivers/md/md.c:sync_max_store
  - drivers/md/md.c:sync_min_store
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:ppl_size_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:errors_store
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpuidle/sysfs.c:store_state_disable
  - drivers/clocksource/acpi_pm.c:parse_pmtmr
  - drivers/platform/x86/intel/pmc/core.c:etr3_store
  - net/core/utils.c:inet6_pton
  - net/core/net-sysfs.c:bql_set_limit_min
  - net/core/net-sysfs.c:bql_set_limit_max
  - net/core/net-sysfs.c:bql_set_limit
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/ipv4/tcp_metrics.c:set_tcpmhash_entries
```
**Symbols:**

```
ffffffff8181df80-ffffffff8181dfee: kstrtouint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kstrtouint(const char *s, unsigned int base, unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81863df0)
Location: lib/kstrtox.c:228
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:debug_alt
  - arch/x86/kernel/tsc.c:tsc_early_khz_setup
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:max_threshold_occ_write
  - arch/x86/mm/pkeys.c:setup_init_pkru
  - arch/x86/mm/pkeys.c:init_pkru_write_file
  - kernel/params.c:param_set_uint_minmax
  - kernel/reboot.c:cpu_store
  - kernel/sched/build_utility.c:sched_scaling_write
  - kernel/sched/build_utility.c:rate_limit_us_store
  - kernel/power/hibernate.c:resumedelay_setup
  - kernel/audit.c:audit_backlog_limit_set
  - kernel/trace/trace_events_synth.c:synth_field_string_size
  - kernel/trace/trace_events_user.c:user_event_parse_field
  - kernel/trace/trace_events_user.c:user_field_array_size
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_fprobe.c:__trace_fprobe_create
  - mm/vmscan.c:enabled_store
  - mm/vmscan.c:min_ttl_ms_store
  - mm/backing-dev.c:strict_limit_store
  - mm/backing-dev.c:max_ratio_fine_store
  - mm/backing-dev.c:max_ratio_store
  - mm/backing-dev.c:min_ratio_fine_store
  - mm/backing-dev.c:min_ratio_store
  - mm/slub.c:remote_node_defrag_ratio_store
  - mm/slub.c:cpu_partial_store
  - mm/ksm.c:stable_node_chains_prune_millisecs_store
  - mm/ksm.c:run_store
  - mm/ksm.c:pages_to_scan_store
  - mm/ksm.c:sleep_millisecs_store
  - mm/memtest.c:parse_memtest
  - mm/khugepaged.c:pages_to_scan_store
  - mm/khugepaged.c:alloc_sleep_millisecs_store
  - mm/khugepaged.c:scan_sleep_millisecs_store
  - fs/fs_parser.c:fs_param_is_fd
  - fs/fs_parser.c:fs_param_is_u32
  - fs/proc/root.c:proc_parse_param
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
  - security/device_cgroup.c:devcgroup_update_access
  - security/device_cgroup.c:devcgroup_update_access
  - block/blk-sysfs.c:queue_io_timeout_store
  - lib/parser.c:match_uint
  - lib/kstrtox.c:kstrtouint_from_user
  - lib/dynamic_debug.c:parse_linerange
  - lib/dynamic_debug.c:parse_linerange
  - lib/dynamic_debug.c:parse_linerange
  - drivers/pwm/sysfs.c:unexport_store
  - drivers/pwm/sysfs.c:export_store
  - drivers/acpi/sysfs.c:enabled_store
  - drivers/xen/xenbus/xenbus_probe.c:spurious_threshold_store
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/base/swnode.c:software_node_graph_parse_endpoint
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout
  - drivers/scsi/sd.c:max_medium_access_timeouts_store
  - drivers/scsi/sd.c:protection_type_store
  - drivers/usb/core/port.c:quirks_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/input/input-poller.c:input_dev_set_poll_interval
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/ptp/ptp_sysfs.c:max_vclocks_store
  - drivers/ptp/ptp_sysfs.c:n_vclocks_store
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
  - drivers/watchdog/watchdog_dev.c:nowayout_store
  - drivers/md/md.c:set_ro
  - drivers/md/md.c:sync_max_store
  - drivers/md/md.c:sync_min_store
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:ppl_size_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:errors_store
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpuidle/sysfs.c:store_state_disable
  - drivers/clocksource/acpi_pm.c:parse_pmtmr
  - net/core/utils.c:inet6_pton
  - net/core/net-sysfs.c:bql_set_limit_min
  - net/core/net-sysfs.c:bql_set_limit_max
  - net/core/net-sysfs.c:bql_set_limit
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/ipv4/tcp_metrics.c:set_tcpmhash_entries
```
**Symbols:**

```
ffffffff81863df0-ffffffff81863e5e: kstrtouint (STB_GLOBAL)
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
int kstrtouint(const char *s, unsigned int base, unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffff800010639f90)
Location: lib/kstrtox.c:217
Inline: False
Direct callers:
  - kernel/params.c:param_set_uint
  - kernel/sched/cpufreq_schedutil.c:rate_limit_us_store
  - kernel/audit.c:audit_backlog_limit_set
  - kernel/hung_task.c:hung_task_panic_setup
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - mm/backing-dev.c:max_ratio_store
  - mm/backing-dev.c:min_ratio_store
  - mm/slub.c:remote_node_defrag_ratio_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:order_store
  - mm/memtest.c:parse_memtest
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - block/blk-sysfs.c:queue_io_timeout_store
  - lib/kstrtox.c:kstrtouint_from_user
  - lib/dynamic_debug.c:ddebug_exec_query
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pwm/sysfs.c:unexport_store
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
  - drivers/acpi/sysfs.c:hotplug_enabled_store
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout
  - drivers/scsi/sd.c:max_medium_access_timeouts_store
  - drivers/scsi/sd.c:protection_type_store
  - drivers/ata/libahci.c:ahci_led_store
  - drivers/usb/core/port.c:quirks_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/input/input-poller.c:input_dev_set_poll_interval
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
  - drivers/md/md.c:set_ro
  - drivers/md/md.c:sync_max_store
  - drivers/md/md.c:sync_min_store
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:ppl_size_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:errors_store
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec
  - net/core/utils.c:inet6_pton
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/net-sysfs.c:bql_set
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/ipv4/tcp_metrics.c:set_tcpmhash_entries
```
**Symbols:**

```
ffff800010639f90-ffff80001063a008: kstrtouint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kstrtouint(const char *s, unsigned int base, unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (c07dfa50)
Location: lib/kstrtox.c:217
Inline: False
Direct callers:
  - kernel/params.c:param_set_uint
  - kernel/sched/cpufreq_schedutil.c:rate_limit_us_store
  - kernel/power/hibernate.c:resumedelay_setup
  - kernel/audit.c:audit_backlog_limit_set
  - kernel/hung_task.c:hung_task_panic_setup
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - mm/backing-dev.c:max_ratio_store
  - mm/backing-dev.c:min_ratio_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:order_store
  - mm/memtest.c:parse_memtest
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - block/blk-sysfs.c:queue_io_timeout_store
  - lib/kstrtox.c:kstrtouint_from_user
  - lib/dynamic_debug.c:ddebug_exec_queries
  - lib/dynamic_debug.c:ddebug_exec_queries
  - drivers/pwm/sysfs.c:unexport_store
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout
  - drivers/scsi/sd.c:max_medium_access_timeouts_store
  - drivers/scsi/sd.c:protection_type_store
  - drivers/ata/libahci.c:ahci_led_store
  - drivers/mtd/mtdcore.c:mtd_bitflip_threshold_store
  - drivers/usb/core/port.c:quirks_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/input/input-poller.c:input_dev_set_poll_interval
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
  - drivers/md/md.c:set_ro
  - drivers/md/md.c:sync_max_store
  - drivers/md/md.c:sync_min_store
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:ppl_size_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:errors_store
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec
  - net/core/utils.c:inet6_pton
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/net-sysfs.c:bql_set
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/ipv4/tcp_metrics.c:set_tcpmhash_entries
```
**Symbols:**

```
c07dfa50-c07dfad0: kstrtouint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kstrtouint(const char *s, unsigned int base, unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (c0000000007e0c20)
Location: lib/kstrtox.c:217
Inline: False
Direct callers:
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_store
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_store
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_store
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_store
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_probe
  - kernel/params.c:param_set_uint
  - kernel/sched/cpufreq_schedutil.c:rate_limit_us_store
  - kernel/audit.c:audit_backlog_limit_set
  - kernel/hung_task.c:hung_task_panic_setup
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - mm/backing-dev.c:max_ratio_store
  - mm/backing-dev.c:min_ratio_store
  - mm/slub.c:remote_node_defrag_ratio_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:order_store
  - mm/memtest.c:parse_memtest
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - block/blk-sysfs.c:queue_io_timeout_store
  - lib/kstrtox.c:kstrtouint_from_user
  - lib/dynamic_debug.c:ddebug_exec_query
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pwm/sysfs.c:unexport_store
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout
  - drivers/scsi/sd.c:max_medium_access_timeouts_store
  - drivers/scsi/sd.c:protection_type_store
  - drivers/usb/core/port.c:quirks_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/input/input-poller.c:input_dev_set_poll_interval
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
  - drivers/md/md.c:set_ro
  - drivers/md/md.c:sync_max_store
  - drivers/md/md.c:sync_min_store
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:ppl_size_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:errors_store
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec
  - net/core/utils.c:inet6_pton
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/net-sysfs.c:bql_set
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/ipv4/tcp_metrics.c:set_tcpmhash_entries
```
**Symbols:**

```
c0000000007e0c20-c0000000007e0cc0: kstrtouint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kstrtouint(const char *s, unsigned int base, unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffe000466836)
Location: lib/kstrtox.c:217
Inline: False
Direct callers:
  - kernel/params.c:param_set_uint
  - kernel/audit.c:audit_backlog_limit_set
  - kernel/hung_task.c:hung_task_panic_setup
  - mm/backing-dev.c:max_ratio_store
  - mm/backing-dev.c:min_ratio_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:order_store
  - mm/memtest.c:parse_memtest
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - block/blk-sysfs.c:queue_io_timeout_store
  - lib/kstrtox.c:kstrtouint_from_user
  - lib/dynamic_debug.c:ddebug_exec_query
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pwm/sysfs.c:unexport_store
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout
  - drivers/scsi/sd.c:max_medium_access_timeouts_store
  - drivers/scsi/sd.c:protection_type_store
  - drivers/usb/core/port.c:quirks_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/input/input-poller.c:input_dev_set_poll_interval
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
  - drivers/md/md.c:set_ro
  - drivers/md/md.c:sync_max_store
  - drivers/md/md.c:sync_min_store
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:ppl_size_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:errors_store
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec
  - net/core/utils.c:inet6_pton
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/net-sysfs.c:bql_set
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/ipv4/tcp_metrics.c:set_tcpmhash_entries
```
**Symbols:**

```
ffffffe000466836-ffffffe000466886: kstrtouint (STB_GLOBAL)
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
int kstrtouint(const char *s, unsigned int base, unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81526170)
Location: lib/kstrtox.c:217
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:max_threshold_occ_write
  - arch/x86/mm/pkeys.c:setup_init_pkru
  - arch/x86/mm/pkeys.c:init_pkru_write_file
  - kernel/params.c:param_set_uint
  - kernel/sched/cpufreq_schedutil.c:rate_limit_us_store
  - kernel/power/hibernate.c:resumedelay_setup
  - kernel/audit.c:audit_backlog_limit_set
  - kernel/hung_task.c:hung_task_panic_setup
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - mm/backing-dev.c:max_ratio_store
  - mm/backing-dev.c:min_ratio_store
  - mm/slub.c:remote_node_defrag_ratio_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:order_store
  - mm/memtest.c:parse_memtest
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - block/blk-sysfs.c:queue_io_timeout_store
  - lib/kstrtox.c:kstrtouint_from_user
  - lib/dynamic_debug.c:ddebug_exec_query
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pwm/sysfs.c:unexport_store
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
  - drivers/acpi/sysfs.c:hotplug_enabled_store
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout
  - drivers/scsi/sd.c:max_medium_access_timeouts_store
  - drivers/scsi/sd.c:protection_type_store
  - drivers/usb/core/port.c:quirks_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/input/input-poller.c:input_dev_set_poll_interval
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
  - drivers/md/md.c:set_ro
  - drivers/md/md.c:sync_max_store
  - drivers/md/md.c:sync_min_store
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:ppl_size_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:errors_store
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/clocksource/acpi_pm.c:parse_pmtmr
  - net/core/utils.c:inet6_pton
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/net-sysfs.c:bql_set
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/ipv4/tcp_metrics.c:set_tcpmhash_entries
```
**Symbols:**

```
ffffffff81526170-ffffffff815261d4: kstrtouint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kstrtouint(const char *s, unsigned int base, unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81516450)
Location: lib/kstrtox.c:217
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:max_threshold_occ_write
  - arch/x86/mm/pkeys.c:setup_init_pkru
  - arch/x86/mm/pkeys.c:init_pkru_write_file
  - kernel/params.c:param_set_uint
  - kernel/sched/cpufreq_schedutil.c:rate_limit_us_store
  - kernel/power/hibernate.c:resumedelay_setup
  - kernel/audit.c:audit_backlog_limit_set
  - kernel/hung_task.c:hung_task_panic_setup
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - mm/backing-dev.c:max_ratio_store
  - mm/backing-dev.c:min_ratio_store
  - mm/slub.c:remote_node_defrag_ratio_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:order_store
  - mm/memtest.c:parse_memtest
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - block/blk-sysfs.c:queue_io_timeout_store
  - lib/kstrtox.c:kstrtouint_from_user
  - lib/dynamic_debug.c:ddebug_exec_query
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/acpi/sysfs.c:hotplug_enabled_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout
  - drivers/scsi/sd.c:max_medium_access_timeouts_store
  - drivers/scsi/sd.c:protection_type_store
  - drivers/usb/core/port.c:quirks_store
  - drivers/input/input-poller.c:input_dev_set_poll_interval
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
  - drivers/md/md.c:set_ro
  - drivers/md/md.c:sync_max_store
  - drivers/md/md.c:sync_min_store
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:ppl_size_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:errors_store
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/clocksource/acpi_pm.c:parse_pmtmr
  - net/core/utils.c:inet6_pton
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/net-sysfs.c:bql_set
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/ipv4/tcp_metrics.c:set_tcpmhash_entries
```
**Symbols:**

```
ffffffff81516450-ffffffff815164b4: kstrtouint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kstrtouint(const char *s, unsigned int base, unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81522200)
Location: lib/kstrtox.c:217
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:max_threshold_occ_write
  - arch/x86/mm/pkeys.c:setup_init_pkru
  - arch/x86/mm/pkeys.c:init_pkru_write_file
  - kernel/params.c:param_set_uint
  - kernel/sched/cpufreq_schedutil.c:rate_limit_us_store
  - kernel/power/hibernate.c:resumedelay_setup
  - kernel/audit.c:audit_backlog_limit_set
  - kernel/hung_task.c:hung_task_panic_setup
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - mm/backing-dev.c:max_ratio_store
  - mm/backing-dev.c:min_ratio_store
  - mm/slub.c:remote_node_defrag_ratio_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:order_store
  - mm/memtest.c:parse_memtest
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - block/blk-sysfs.c:queue_io_timeout_store
  - lib/kstrtox.c:kstrtouint_from_user
  - lib/dynamic_debug.c:ddebug_exec_query
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pwm/sysfs.c:unexport_store
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
  - drivers/acpi/sysfs.c:hotplug_enabled_store
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout
  - drivers/scsi/sd.c:max_medium_access_timeouts_store
  - drivers/scsi/sd.c:protection_type_store
  - drivers/usb/core/port.c:quirks_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/input/input-poller.c:input_dev_set_poll_interval
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
  - drivers/md/md.c:set_ro
  - drivers/md/md.c:sync_max_store
  - drivers/md/md.c:sync_min_store
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:ppl_size_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:errors_store
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/clocksource/acpi_pm.c:parse_pmtmr
  - net/core/utils.c:inet6_pton
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/net-sysfs.c:bql_set
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_set_hashsize
  - net/ipv4/tcp_metrics.c:set_tcpmhash_entries
```
**Symbols:**

```
ffffffff81522200-ffffffff81522264: kstrtouint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kstrtouint(const char *s, unsigned int base, unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8153bb80)
Location: lib/kstrtox.c:217
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:max_threshold_occ_write
  - arch/x86/mm/pkeys.c:setup_init_pkru
  - arch/x86/mm/pkeys.c:init_pkru_write_file
  - kernel/params.c:param_set_uint
  - kernel/sched/cpufreq_schedutil.c:rate_limit_us_store
  - kernel/power/hibernate.c:resumedelay_setup
  - kernel/audit.c:audit_backlog_limit_set
  - kernel/hung_task.c:hung_task_panic_setup
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - mm/backing-dev.c:max_ratio_store
  - mm/backing-dev.c:min_ratio_store
  - mm/slub.c:remote_node_defrag_ratio_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:order_store
  - mm/memtest.c:parse_memtest
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - block/blk-sysfs.c:queue_io_timeout_store
  - lib/kstrtox.c:kstrtouint_from_user
  - lib/dynamic_debug.c:ddebug_exec_query
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pwm/sysfs.c:unexport_store
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
  - drivers/acpi/sysfs.c:hotplug_enabled_store
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout
  - drivers/scsi/sd.c:max_medium_access_timeouts_store
  - drivers/scsi/sd.c:protection_type_store
  - drivers/usb/core/port.c:quirks_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/input/input-poller.c:input_dev_set_poll_interval
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
  - drivers/md/md.c:set_ro
  - drivers/md/md.c:sync_max_store
  - drivers/md/md.c:sync_min_store
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:ppl_size_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:errors_store
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec
  - drivers/cpufreq/acpi-cpufreq.c:store_cpb
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/clocksource/acpi_pm.c:parse_pmtmr
  - net/core/utils.c:inet6_pton
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/net-sysfs.c:bql_set
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/ipv4/tcp_metrics.c:set_tcpmhash_entries
```
**Symbols:**

```
ffffffff8153bb80-ffffffff8153bbe4: kstrtouint (STB_GLOBAL)
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
