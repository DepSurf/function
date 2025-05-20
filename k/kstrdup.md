# Function: <code>kstrdup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *kstrdup(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811abc20)
Location: mm/util.c:44
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - kernel/kmod.c:__request_module
  - kernel/sched/core.c:register_sched_domain_sysctl
  - kernel/sched/core.c:register_sched_domain_sysctl
  - kernel/module.c:setup_modinfo_srcversion
  - kernel/module.c:setup_modinfo_version
  - kernel/module.c:load_module
  - kernel/cgroup.c:cgroup_release_agent
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditsc.c:audit_filter_rules
  - kernel/auditsc.c:audit_alloc
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_dupe_exe
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:postfix_append_operand
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_symbol_cache
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - mm/util.c:kstrdup_const
  - mm/zsmalloc.c:zs_create_pool
  - fs/exec.c:bprm_change_interp
  - fs/namei.c:vfs_rename
  - fs/namespace.c:do_mount
  - fs/xattr.c:__simple_xattr_set
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_rename
  - security/selinux/ss/sidtab.c:sidtab_insert
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/services.c:get_classes_callback
  - security/selinux/ss/services.c:get_permissions_callback
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/mls.c:mls_from_string
  - security/smack/smack_lsm.c:smack_key_getsecurity
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_inode_init_security
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/kobject.c:kobject_set_name_vargs
  - lib/dynamic_debug.c:dynamic_debug_init
  - drivers/pci/slot.c:make_slot_name
  - drivers/video/fbdev/core/fb_cmdline.c:fb_get_options
  - drivers/video/fbdev/core/fb_cmdline.c:fb_get_options
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/char/misc.c:misc_devnode
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_rename
  - drivers/base/property.c:device_add_property_set
  - drivers/base/property.c:device_add_property_set
  - drivers/base/property.c:device_add_property_set
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
```
**Symbols:**

```
ffffffff811abc20-ffffffff811abc73: kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *kstrdup(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811c46a0)
Location: mm/util.c:44
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - kernel/kmod.c:__request_module
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/module.c:load_module
  - kernel/module.c:setup_modinfo_srcversion
  - kernel/module.c:setup_modinfo_version
  - kernel/cgroup.c:cgroup_release_agent
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditsc.c:audit_alloc
  - kernel/audit_watch.c:audit_dupe_exe
  - kernel/audit_watch.c:audit_update_watch
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:postfix_append_operand
  - kernel/trace/trace_events_trigger.c:save_named_trigger
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_symbol_cache
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/events/core.c:perf_event_set_addr_filter
  - mm/util.c:kstrdup_const
  - mm/zsmalloc.c:zs_create_pool
  - fs/exec.c:bprm_change_interp
  - fs/namei.c:vfs_rename
  - fs/namespace.c:do_mount
  - fs/xattr.c:simple_xattr_set
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_symlink
  - security/selinux/ss/sidtab.c:sidtab_insert
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:get_permissions_callback
  - security/selinux/ss/services.c:get_classes_callback
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/mls.c:mls_from_string
  - security/smack/smack_lsm.c:smack_key_getsecurity
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_inode_init_security
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/kobject.c:kobject_set_name_vargs
  - lib/dynamic_debug.c:dynamic_debug_init
  - drivers/gpio/gpiolib.c:gpiochip_add_data
  - drivers/gpio/gpiolib.c:gpiochip_add_data
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-acpi.c:acpi_can_fallback_to_crs
  - drivers/pci/slot.c:make_slot_name
  - drivers/video/fbdev/core/fb_cmdline.c:fb_get_options
  - drivers/video/fbdev/core/fb_cmdline.c:fb_get_options
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/char/misc.c:misc_devnode
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_rename
  - drivers/base/property.c:device_add_properties
  - drivers/base/property.c:device_add_properties
  - drivers/base/property.c:device_add_properties
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
```
**Symbols:**

```
ffffffff811c46a0-ffffffff811c46fa: kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *kstrdup(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811d4790)
Location: mm/util.c:44
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - kernel/kmod.c:__request_module
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/module.c:load_module
  - kernel/module.c:setup_modinfo_srcversion
  - kernel/module.c:setup_modinfo_version
  - kernel/cgroup.c:cgroup_release_agent
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditsc.c:audit_alloc
  - kernel/audit_watch.c:audit_dupe_exe
  - kernel/audit_watch.c:audit_update_watch
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:postfix_append_operand
  - kernel/trace/trace_events_trigger.c:save_named_trigger
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_symbol_cache
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/events/core.c:perf_event_set_addr_filter
  - mm/util.c:kstrdup_const
  - mm/zsmalloc.c:zs_create_pool
  - fs/exec.c:bprm_change_interp
  - fs/namei.c:vfs_rename
  - fs/namespace.c:do_mount
  - fs/xattr.c:simple_xattr_set
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_symlink
  - security/selinux/ss/sidtab.c:sidtab_insert
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:get_permissions_callback
  - security/selinux/ss/services.c:get_classes_callback
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/mls.c:mls_from_string
  - security/smack/smack_lsm.c:smack_key_getsecurity
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/kobject.c:kobject_set_name_vargs
  - lib/dynamic_debug.c:dynamic_debug_init
  - drivers/gpio/gpiolib.c:gpiochip_add_data
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/pci/slot.c:make_slot_name
  - drivers/video/fbdev/core/fb_cmdline.c:fb_get_options
  - drivers/video/fbdev/core/fb_cmdline.c:fb_get_options
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/char/misc.c:misc_devnode
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_rename
  - drivers/base/property.c:device_add_properties
  - drivers/base/property.c:device_add_properties
  - drivers/base/property.c:device_add_properties
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
```
**Symbols:**

```
ffffffff811d4790-ffffffff811d47ea: kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *kstrdup(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811dd540)
Location: mm/util.c:47
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - kernel/kmod.c:__request_module
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/module.c:load_module
  - kernel/module.c:setup_modinfo_srcversion
  - kernel/module.c:setup_modinfo_version
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditsc.c:audit_alloc
  - kernel/audit_watch.c:audit_dupe_exe
  - kernel/audit_watch.c:audit_update_watch
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:postfix_append_operand
  - kernel/trace/trace_events_trigger.c:save_named_trigger
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_symbol_cache
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/util.c:kstrdup_const
  - mm/zsmalloc.c:zs_create_pool
  - fs/exec.c:bprm_change_interp
  - fs/namespace.c:do_mount
  - fs/xattr.c:simple_xattr_set
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/debugfs/inode.c:debugfs_create_symlink
  - security/security.c:security_getprocattr
  - security/security.c:security_add_hooks
  - security/inode.c:securityfs_create_symlink
  - security/selinux/ss/sidtab.c:sidtab_insert
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:get_permissions_callback
  - security/selinux/ss/services.c:get_classes_callback
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/mls.c:mls_from_string
  - security/smack/smack_lsm.c:smack_key_getsecurity
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/dynamic_debug.c:dynamic_debug_init
  - drivers/gpio/gpiolib.c:gpiochip_add_data
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/pci/slot.c:make_slot_name
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/video/fbdev/core/fb_cmdline.c:fb_get_options
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/char/misc.c:misc_devnode
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_rename
  - drivers/base/property.c:property_entries_dup
  - drivers/base/property.c:property_entries_dup
  - drivers/base/property.c:property_entries_dup
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/dax/super.c:alloc_dax
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff811dd540-ffffffff811dd59a: kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *kstrdup(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811f2fc0)
Location: mm/util.c:47
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - kernel/kmod.c:__request_module
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/module.c:load_module
  - kernel/module.c:setup_modinfo_srcversion
  - kernel/module.c:setup_modinfo_version
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditsc.c:audit_alloc
  - kernel/audit_watch.c:audit_dupe_exe
  - kernel/audit_watch.c:audit_update_watch
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:postfix_append_operand
  - kernel/trace/trace_events_trigger.c:save_named_trigger
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_symbol_cache
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/util.c:kstrdup_const
  - mm/zsmalloc.c:zs_create_pool
  - fs/exec.c:bprm_change_interp
  - fs/namespace.c:do_mount
  - fs/xattr.c:simple_xattr_set
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/debugfs/inode.c:debugfs_create_symlink
  - security/security.c:security_getprocattr
  - security/security.c:security_add_hooks
  - security/inode.c:securityfs_create_symlink
  - security/selinux/ss/sidtab.c:sidtab_insert
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:get_permissions_callback
  - security/selinux/ss/services.c:get_classes_callback
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/mls.c:mls_from_string
  - security/smack/smack_lsm.c:smack_key_getsecurity
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/apparmor/domain.c:profile_transition
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/dynamic_debug.c:dynamic_debug_init
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/pci/slot.c:make_slot_name
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/video/fbdev/core/fb_cmdline.c:fb_get_options
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/char/misc.c:misc_devnode
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_rename
  - drivers/base/property.c:property_entries_dup
  - drivers/base/property.c:property_entries_dup
  - drivers/base/property.c:property_entries_dup
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/dax/super.c:alloc_dax
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff811f2fc0-ffffffff811f301a: kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *kstrdup(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812142b0)
Location: mm/util.c:47
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - kernel/kmod.c:__request_module
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:setup_modinfo_srcversion
  - kernel/module.c:setup_modinfo_version
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - kernel/audit_watch.c:audit_dupe_exe
  - kernel/audit_watch.c:audit_update_watch
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_trigger.c:save_named_trigger
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_synth_event
  - kernel/trace/trace_events_hist.c:create_synth_event
  - kernel/trace/trace_events_hist.c:create_synth_event
  - kernel/trace/trace_events_hist.c:create_synth_event
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_symbol_cache
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/util.c:kstrdup_const
  - mm/zsmalloc.c:zs_create_pool
  - fs/exec.c:bprm_change_interp
  - fs/namespace.c:do_mount
  - fs/xattr.c:simple_xattr_set
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/debugfs/inode.c:debugfs_create_symlink
  - security/security.c:security_add_hooks
  - security/inode.c:securityfs_create_symlink
  - security/selinux/ss/sidtab.c:sidtab_insert
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:get_permissions_callback
  - security/selinux/ss/services.c:get_classes_callback
  - security/selinux/ss/mls.c:mls_from_string
  - security/smack/smack_lsm.c:smack_key_getsecurity
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/apparmor/domain.c:profile_transition
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/dynamic_debug.c:dynamic_debug_init
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/pci/slot.c:make_slot_name
  - drivers/video/fbdev/core/fb_cmdline.c:fb_get_options
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/char/misc.c:misc_devnode
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_rename
  - drivers/base/property.c:property_entries_dup
  - drivers/base/property.c:property_entries_dup
  - drivers/base/property.c:property_entries_dup
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/dax/super.c:alloc_dax
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff812142b0-ffffffff8121430a: kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *kstrdup(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81227180)
Location: mm/util.c:40
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - kernel/kmod.c:__request_module
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:setup_modinfo_srcversion
  - kernel/module.c:setup_modinfo_version
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - kernel/audit_watch.c:audit_dupe_exe
  - kernel/audit_watch.c:audit_update_watch
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_trigger.c:save_named_trigger
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/util.c:kstrdup_const
  - mm/zsmalloc.c:zs_create_pool
  - fs/exec.c:bprm_change_interp
  - fs/namespace.c:do_mount
  - fs/xattr.c:simple_xattr_set
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/debugfs/inode.c:debugfs_create_symlink
  - security/security.c:security_getprocattr
  - security/security.c:security_transfer_creds
  - security/security.c:security_prepare_creds
  - security/security.c:security_add_hooks
  - security/security.c:security_add_hooks
  - security/security.c:ordered_lsm_parse
  - security/inode.c:securityfs_create_symlink
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:get_permissions_callback
  - security/selinux/ss/services.c:get_classes_callback
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/mls.c:mls_from_string
  - security/smack/smack_lsm.c:smack_key_getsecurity
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/apparmor/domain.c:profile_transition
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/dynamic_debug.c:dynamic_debug_init
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/slot.c:make_slot_name
  - drivers/video/fbdev/core/fb_cmdline.c:fb_get_options
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/char/misc.c:misc_devnode
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_rename
  - drivers/base/swnode.c:property_entries_dup
  - drivers/base/swnode.c:property_entries_dup
  - drivers/base/swnode.c:property_entries_dup
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/dax/super.c:alloc_dax
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff81227180-ffffffff812271da: kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *kstrdup(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81236c80)
Location: mm/util.c:44
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - kernel/kmod.c:__request_module
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:setup_modinfo_srcversion
  - kernel/module.c:setup_modinfo_version
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - kernel/audit_watch.c:audit_dupe_exe
  - kernel/audit_watch.c:audit_update_watch
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_trigger.c:save_named_trigger
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/events/core.c:perf_event_set_filter
  - mm/util.c:kstrdup_const
  - mm/zsmalloc.c:zs_create_pool
  - fs/exec.c:bprm_change_interp
  - fs/xattr.c:simple_xattr_set
  - fs/fs_context.c:logfc
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/debugfs/inode.c:debugfs_create_symlink
  - security/security.c:security_getprocattr
  - security/security.c:security_transfer_creds
  - security/security.c:security_prepare_creds
  - security/security.c:security_add_hooks
  - security/security.c:security_add_hooks
  - security/security.c:ordered_lsm_parse
  - security/inode.c:securityfs_create_symlink
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:get_permissions_callback
  - security/selinux/ss/services.c:get_classes_callback
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/mls.c:mls_from_string
  - security/smack/smack_lsm.c:smack_key_getsecurity
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/apparmor/domain.c:profile_transition
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/dynamic_debug.c:dynamic_debug_init
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/slot.c:make_slot_name
  - drivers/video/fbdev/core/fb_cmdline.c:fb_get_options
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/char/misc.c:misc_devnode
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_rename
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/dax/super.c:alloc_dax
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff81236c80-ffffffff81236cdd: kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *kstrdup(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81244e40)
Location: mm/util.c:51
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - kernel/kmod.c:__request_module
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:setup_modinfo_srcversion
  - kernel/module.c:setup_modinfo_version
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - kernel/audit_watch.c:audit_dupe_exe
  - kernel/audit_watch.c:audit_update_watch
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_trigger.c:save_named_trigger
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/events/core.c:perf_event_set_filter
  - mm/util.c:kstrdup_const
  - mm/zsmalloc.c:zs_create_pool
  - fs/exec.c:bprm_change_interp
  - fs/xattr.c:simple_xattr_set
  - fs/fs_context.c:logfc
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/debugfs/inode.c:debugfs_create_symlink
  - security/security.c:security_getprocattr
  - security/security.c:security_transfer_creds
  - security/security.c:security_prepare_creds
  - security/security.c:security_add_hooks
  - security/security.c:ordered_lsm_parse
  - security/inode.c:securityfs_create_symlink
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:get_permissions_callback
  - security/selinux/ss/services.c:get_classes_callback
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/mls.c:mls_from_string
  - security/smack/smack_lsm.c:smack_key_getsecurity
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/apparmor/domain.c:profile_transition
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/dynamic_debug.c:dynamic_debug_init
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/slot.c:make_slot_name
  - drivers/video/fbdev/core/fb_cmdline.c:fb_get_options
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/char/misc.c:misc_devnode
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_rename
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/dax/super.c:alloc_dax
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff81244e40-ffffffff81244e9d: kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *kstrdup(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81272af0)
Location: mm/util.c:51
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - kernel/kmod.c:call_modprobe
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:sd_alloc_ctl_cpu_table
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/livepatch/core.c:klp_add_object_nops
  - kernel/livepatch/core.c:klp_add_object_nops
  - kernel/module.c:add_sect_attrs
  - kernel/module.c:setup_modinfo_srcversion
  - kernel/module.c:setup_modinfo_version
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - kernel/audit_watch.c:audit_dupe_exe
  - kernel/audit_watch.c:audit_update_watch
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_cached_mods
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:cache_mod
  - kernel/trace/ftrace.c:cache_mod
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/blktrace.c:blk_trace_str2mask
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_trigger.c:save_named_trigger
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_synth.c:alloc_synth_event
  - kernel/trace/trace_events_synth.c:register_synth_event
  - kernel/trace/trace_events_synth.c:register_synth_event
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/util.c:kstrdup_const
  - mm/zsmalloc.c:zs_create_pool
  - fs/exec.c:bprm_change_interp
  - fs/xattr.c:simple_xattr_set
  - fs/proc/proc_sysctl.c:do_sysctl_args
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/pstore/platform.c:pstore_register
  - security/security.c:security_getprocattr
  - security/security.c:ordered_lsm_parse
  - security/inode.c:securityfs_create_symlink
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:get_permissions_callback
  - security/selinux/ss/services.c:get_classes_callback
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/mls.c:mls_from_string
  - security/smack/smack_lsm.c:smack_key_getsecurity
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/apparmor/policy_unpack.c:verify_header
  - security/safesetid/securityfs.c:handle_policy_update
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_lsm_copy_rule
  - security/integrity/ima/ima_template.c:restore_template_fmt
  - security/integrity/ima/ima_queue_keys.c:ima_alloc_key_entry
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/string_helpers.c:kstrdup_quotable_file
  - lib/string_helpers.c:kstrdup_quotable_file
  - lib/string_helpers.c:kstrdup_quotable_file
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/kobject.c:kobject_set_name_vargs
  - drivers/gpio/gpiolib.c:lineevent_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/slot.c:make_slot_name
  - drivers/video/fbdev/core/fb_cmdline.c:fb_get_options
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_consumer_device_supply
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/char/misc.c:misc_devnode
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_get_devnode
  - drivers/base/swnode.c:property_entry_copy_data
  - drivers/base/swnode.c:property_entry_copy_data
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/dax/super.c:alloc_dax
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/usb/core/quirks.c:quirks_param_set
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - net/core/drop_monitor.c:net_dm_hw_metadata_clone
  - net/core/drop_monitor.c:net_dm_hw_metadata_clone
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
```
**Symbols:**

```
ffffffff81272af0-ffffffff81272b4d: kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *kstrdup(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8127d1a0)
Location: mm/util.c:51
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_set_mapping
  - kernel/kmod.c:call_modprobe
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:sd_alloc_ctl_cpu_table
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/livepatch/core.c:klp_add_object_nops
  - kernel/livepatch/core.c:klp_add_object_nops
  - kernel/module.c:add_sect_attrs
  - kernel/module.c:setup_modinfo_srcversion
  - kernel/module.c:setup_modinfo_version
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - kernel/audit_watch.c:audit_dupe_exe
  - kernel/audit_watch.c:audit_update_watch
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_cached_mods
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:cache_mod
  - kernel/trace/ftrace.c:cache_mod
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/blktrace.c:blk_trace_str2mask
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_trigger.c:save_named_trigger
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_synth.c:alloc_synth_event
  - kernel/trace/trace_events_synth.c:register_synth_event
  - kernel/trace/trace_events_synth.c:register_synth_event
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/util.c:kstrdup_const
  - mm/zsmalloc.c:zs_create_pool
  - fs/exec.c:bprm_change_interp
  - fs/xattr.c:simple_xattr_set
  - fs/proc/proc_sysctl.c:do_sysctl_args
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/fuse/inode.c:fuse_fill_super_submount
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/pstore/platform.c:pstore_register
  - security/security.c:security_getprocattr
  - security/security.c:ordered_lsm_parse
  - security/inode.c:securityfs_create_symlink
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:get_permissions_callback
  - security/selinux/ss/services.c:get_classes_callback
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/mls.c:mls_from_string
  - security/smack/smack_lsm.c:smack_key_getsecurity
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/apparmor/policy_unpack.c:verify_header
  - security/safesetid/securityfs.c:handle_policy_update
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:restore_template_fmt
  - security/integrity/ima/ima_queue_keys.c:ima_alloc_key_entry
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/string_helpers.c:kstrdup_quotable_file
  - lib/string_helpers.c:kstrdup_quotable_file
  - lib/string_helpers.c:kstrdup_quotable_file
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/kobject.c:kobject_set_name_vargs
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/slot.c:make_slot_name
  - drivers/video/fbdev/core/fb_cmdline.c:fb_get_options
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_consumer_device_supply
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/char/misc.c:misc_devnode
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_get_devnode
  - drivers/base/swnode.c:property_entry_copy_data
  - drivers/base/swnode.c:property_entry_copy_data
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/dax/super.c:alloc_dax
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/usb/core/quirks.c:quirks_param_set
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - net/core/drop_monitor.c:net_dm_hw_metadata_copy
  - net/core/drop_monitor.c:net_dm_hw_metadata_copy
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
```
**Symbols:**

```
ffffffff8127d1a0-ffffffff8127d1fd: kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *kstrdup(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81282330)
Location: mm/util.c:51
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_set_mapping
  - kernel/kmod.c:__request_module
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/livepatch/core.c:klp_add_nops
  - kernel/livepatch/core.c:klp_add_nops
  - kernel/module.c:add_sect_attrs
  - kernel/module.c:setup_modinfo_srcversion
  - kernel/module.c:setup_modinfo_version
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - kernel/audit_watch.c:audit_dupe_exe
  - kernel/audit_watch.c:audit_update_watch
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:cache_mod
  - kernel/trace/ftrace.c:cache_mod
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_trigger.c:save_named_trigger
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_synth.c:check_command
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:alloc_synth_event
  - kernel/trace/trace_events_synth.c:register_synth_event
  - kernel/trace/trace_events_synth.c:register_synth_event
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/util.c:kstrdup_const
  - mm/zsmalloc.c:zs_create_pool
  - fs/exec.c:bprm_change_interp
  - fs/xattr.c:simple_xattr_set
  - fs/proc/proc_sysctl.c:do_sysctl_args
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/fuse/inode.c:fuse_fill_super_submount
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/pstore/platform.c:pstore_register
  - security/security.c:security_getprocattr
  - security/security.c:ordered_lsm_parse
  - security/inode.c:securityfs_create_symlink
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:get_permissions_callback
  - security/selinux/ss/services.c:get_classes_callback
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/mls.c:mls_from_string
  - security/smack/smack_lsm.c:smack_key_getsecurity
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/safesetid/securityfs.c:handle_policy_update
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_queue_keys.c:ima_queue_key
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/string_helpers.c:kstrdup_quotable_file
  - lib/string_helpers.c:kstrdup_quotable_file
  - lib/string_helpers.c:kstrdup_quotable_file
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/kobject.c:kobject_set_name_vargs
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/slot.c:make_slot_name
  - drivers/video/fbdev/core/fb_cmdline.c:fb_get_options
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_consumer_device_supply
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/char/misc.c:misc_devnode
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_get_devnode
  - drivers/base/swnode.c:property_entry_copy_data
  - drivers/base/swnode.c:property_entry_copy_data
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/dax/super.c:alloc_dax
  - drivers/dax/bus.c:mapping_store
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/usb/core/quirks.c:quirks_param_set
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
```
**Symbols:**

```
ffffffff81282330-ffffffff81282389: kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *kstrdup(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812c03a0)
Location: mm/util.c:51
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - arch/x86/events/intel/uncore_snbep.c:pmu_iio_set_mapping
  - kernel/kmod.c:__request_module
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/livepatch/core.c:klp_add_nops
  - kernel/livepatch/core.c:klp_add_nops
  - kernel/module.c:add_sect_attrs
  - kernel/module.c:setup_modinfo_srcversion
  - kernel/module.c:setup_modinfo_version
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - kernel/audit_watch.c:audit_dupe_exe
  - kernel/audit_watch.c:audit_update_watch
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:cache_mod
  - kernel/trace/ftrace.c:cache_mod
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_trigger.c:save_named_trigger
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_events_synth.c:check_command
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:alloc_synth_event
  - kernel/trace/trace_events_synth.c:register_synth_event
  - kernel/trace/trace_events_synth.c:register_synth_event
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/util.c:kstrdup_const
  - mm/zsmalloc.c:zs_create_pool
  - fs/exec.c:bprm_change_interp
  - fs/xattr.c:simple_xattr_set
  - fs/proc/proc_sysctl.c:do_sysctl_args
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/fuse/inode.c:fuse_fill_super_submount
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/pstore/platform.c:pstore_register
  - security/security.c:security_getprocattr
  - security/security.c:ordered_lsm_parse
  - security/inode.c:securityfs_create_symlink
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:get_permissions_callback
  - security/selinux/ss/services.c:get_classes_callback
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/mls.c:mls_from_string
  - security/smack/smack_lsm.c:smack_key_getsecurity
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/safesetid/securityfs.c:handle_policy_update
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_queue_keys.c:ima_queue_key
  - block/partitions/cmdline.c:cmdline_partition
  - lib/string_helpers.c:kstrdup_quotable_file
  - lib/string_helpers.c:kstrdup_quotable_file
  - lib/string_helpers.c:kstrdup_quotable_file
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/kobject.c:kobject_set_name_vargs
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/slot.c:make_slot_name
  - drivers/video/fbdev/core/fb_cmdline.c:fb_get_options
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_consumer_device_supply
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/char/misc.c:misc_devnode
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_get_devnode
  - drivers/base/swnode.c:property_entry_copy_data
  - drivers/base/swnode.c:property_entry_copy_data
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/dax/super.c:alloc_dax
  - drivers/dax/bus.c:mapping_store
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/usb/core/quirks.c:quirks_param_set
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
```
**Symbols:**

```
ffffffff812c03a0-ffffffff812c03f9: kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *kstrdup(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8131ce60)
Location: mm/util.c:52
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:pmu_iio_set_mapping
  - kernel/kmod.c:__request_module
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/livepatch/core.c:klp_add_nops
  - kernel/livepatch/core.c:klp_add_nops
  - kernel/module/main.c:setup_modinfo_srcversion
  - kernel/module/main.c:setup_modinfo_version
  - kernel/module/sysfs.c:add_sect_attrs
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - kernel/audit_watch.c:audit_dupe_exe
  - kernel/audit_watch.c:audit_update_watch
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:cache_mod
  - kernel/trace/ftrace.c:cache_mod
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:update_event_fields
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_trigger.c:save_named_trigger
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
  - kernel/trace/trace_events_synth.c:check_command
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:alloc_synth_event
  - kernel/trace/trace_events_synth.c:register_synth_event
  - kernel/trace/trace_events_synth.c:register_synth_event
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/fprobe.c:register_fprobe
  - kernel/trace/fprobe.c:register_fprobe
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/util.c:kstrdup_const
  - mm/zsmalloc.c:zs_create_pool
  - fs/exec.c:bprm_change_interp
  - fs/xattr.c:simple_xattr_set
  - fs/proc/proc_sysctl.c:do_sysctl_args
  - fs/ext4/super.c:__ext4_remount
  - fs/fuse/inode.c:fuse_fill_super_submount
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/pstore/platform.c:pstore_register
  - security/security.c:security_getprocattr
  - security/security.c:ordered_lsm_parse
  - security/inode.c:securityfs_create_symlink
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:get_permissions_callback
  - security/selinux/ss/services.c:get_classes_callback
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/mls.c:mls_from_string
  - security/smack/smack_lsm.c:smack_key_getsecurity
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/safesetid/securityfs.c:handle_policy_update
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_queue_keys.c:ima_queue_key
  - block/partitions/cmdline.c:cmdline_partition
  - lib/string_helpers.c:kstrdup_quotable_file
  - lib/string_helpers.c:kstrdup_quotable_file
  - lib/string_helpers.c:kstrdup_quotable_file
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/kobject.c:kobject_set_name_vargs
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/slot.c:make_slot_name
  - drivers/video/fbdev/core/fb_cmdline.c:fb_get_options
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_consumer_device_supply
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/char/misc.c:misc_devnode
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_get_devnode
  - drivers/base/swnode.c:property_entry_copy_data
  - drivers/base/swnode.c:property_entry_copy_data
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/dax/bus.c:mapping_store
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/usb/core/quirks.c:quirks_param_set
  - drivers/hwmon/hwmon.c:__hwmon_sanitize_name
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
```
**Symbols:**

```
ffffffff8131ce60-ffffffff8131ced0: kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *kstrdup(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81390f10)
Location: mm/util.c:52
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:pmu_set_mapping
  - kernel/kmod.c:__request_module
  - kernel/irq/irqdomain.c:__irq_domain_create
  - kernel/livepatch/core.c:klp_add_nops
  - kernel/livepatch/core.c:klp_add_nops
  - kernel/module/main.c:setup_modinfo_srcversion
  - kernel/module/main.c:setup_modinfo_version
  - kernel/module/sysfs.c:add_sect_attrs
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - kernel/audit_watch.c:audit_dupe_exe
  - kernel/audit_watch.c:audit_update_watch
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:cache_mod
  - kernel/trace/ftrace.c:cache_mod
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:update_event_fields
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_trigger.c:save_named_trigger
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
  - kernel/trace/trace_events_synth.c:check_command
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:alloc_synth_event
  - kernel/trace/trace_events_synth.c:register_synth_event
  - kernel/trace/trace_events_synth.c:register_synth_event
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/fprobe.c:register_fprobe
  - kernel/trace/fprobe.c:register_fprobe
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/util.c:kstrdup_const
  - mm/zsmalloc.c:zs_create_pool
  - fs/exec.c:bprm_change_interp
  - fs/xattr.c:simple_xattr_set
  - fs/proc/proc_sysctl.c:do_sysctl_args
  - fs/ext4/super.c:__ext4_remount
  - fs/fuse/inode.c:fuse_fill_super_submount
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/pstore/platform.c:pstore_register
  - security/security.c:ordered_lsm_parse
  - security/inode.c:securityfs_create_symlink
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:get_permissions_callback
  - security/selinux/ss/services.c:get_classes_callback
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/mls.c:mls_from_string
  - security/smack/smack_lsm.c:smack_key_getsecurity
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/apparmor/audit.c:aa_dup_audit_data
  - security/apparmor/audit.c:aa_dup_audit_data
  - security/apparmor/audit.c:aa_dup_audit_data
  - security/apparmor/audit.c:aa_dup_audit_data
  - security/apparmor/audit.c:aa_dup_audit_data
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/safesetid/securityfs.c:handle_policy_update
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_queue_keys.c:ima_queue_key
  - block/partitions/cmdline.c:cmdline_partition
  - lib/string_helpers.c:kstrdup_quotable_file
  - lib/string_helpers.c:kstrdup_quotable_file
  - lib/string_helpers.c:kstrdup_quotable_file
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:param_set_dyndbg_classnames
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/slot.c:make_slot_name
  - drivers/video/fbdev/core/fb_cmdline.c:fb_get_options
  - drivers/acpi/utils.c:acpi_get_subsystem_id
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_consumer_device_supply
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/char/misc.c:misc_devnode
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_get_devnode
  - drivers/base/swnode.c:property_entry_copy_data
  - drivers/base/swnode.c:property_entry_copy_data
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/dax/bus.c:mapping_store
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/usb/core/quirks.c:quirks_param_set
  - drivers/hwmon/hwmon.c:__hwmon_sanitize_name
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff81390f10-ffffffff81390f85: kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *kstrdup(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813c3820)
Location: mm/util.c:53
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:pmu_set_mapping
  - kernel/irq/irqdomain.c:__irq_domain_create
  - kernel/livepatch/core.c:klp_add_nops
  - kernel/livepatch/core.c:klp_add_nops
  - kernel/module/main.c:setup_modinfo_srcversion
  - kernel/module/main.c:setup_modinfo_version
  - kernel/module/kmod.c:__request_module
  - kernel/module/sysfs.c:add_sect_attrs
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - kernel/audit_watch.c:audit_dupe_exe
  - kernel/audit_watch.c:audit_update_watch
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:cache_mod
  - kernel/trace/ftrace.c:cache_mod
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:update_event_fields
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_trigger.c:save_named_trigger
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
  - kernel/trace/trace_events_synth.c:check_command
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:alloc_synth_event
  - kernel/trace/trace_events_synth.c:register_synth_event
  - kernel/trace/trace_events_synth.c:register_synth_event
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_user.c:user_event_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/fprobe.c:register_fprobe
  - kernel/trace/fprobe.c:register_fprobe
  - kernel/trace/trace_fprobe.c:__trace_fprobe_create
  - kernel/trace/trace_fprobe.c:alloc_trace_fprobe
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/util.c:kstrdup_const
  - mm/zsmalloc.c:zs_create_pool
  - fs/exec.c:bprm_change_interp
  - fs/xattr.c:simple_xattr_set
  - fs/proc/proc_sysctl.c:do_sysctl_args
  - fs/ext4/super.c:__ext4_remount
  - fs/fuse/inode.c:fuse_fill_super_submount
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/pstore/platform.c:pstore_register
  - security/security.c:ordered_lsm_parse
  - security/inode.c:securityfs_create_symlink
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:get_permissions_callback
  - security/selinux/ss/services.c:get_classes_callback
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/mls.c:mls_from_string
  - security/smack/smack_lsm.c:smack_key_getsecurity
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_fs_context_submount
  - security/smack/smack_lsm.c:smack_fs_context_submount
  - security/smack/smack_lsm.c:smack_fs_context_submount
  - security/smack/smack_lsm.c:smack_fs_context_submount
  - security/apparmor/audit.c:aa_dup_audit_data
  - security/apparmor/audit.c:aa_dup_audit_data
  - security/apparmor/audit.c:aa_dup_audit_data
  - security/apparmor/audit.c:aa_dup_audit_data
  - security/apparmor/audit.c:aa_dup_audit_data
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/safesetid/securityfs.c:handle_policy_update
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_queue_keys.c:ima_queue_key
  - block/partitions/cmdline.c:cmdline_partition
  - lib/string_helpers.c:kstrdup_quotable_file
  - lib/string_helpers.c:kstrdup_quotable_file
  - lib/string_helpers.c:kstrdup_quotable_file
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:param_set_dyndbg_classnames
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/slot.c:make_slot_name
  - drivers/video/fbdev/core/fb_cmdline.c:fb_get_options
  - drivers/acpi/utils.c:acpi_get_subsystem_id
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_consumer_device_supply
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/char/misc.c:misc_devnode
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_get_devnode
  - drivers/base/swnode.c:property_entry_copy_data
  - drivers/base/swnode.c:property_entry_copy_data
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/dax/bus.c:mapping_store
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/usb/core/quirks.c:quirks_param_set
  - drivers/hwmon/hwmon.c:__hwmon_sanitize_name
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff813c3820-ffffffff813c3894: kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *kstrdup(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813ee3e0)
Location: mm/util.c:53
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:pmu_set_mapping
  - kernel/irq/irqdomain.c:__irq_domain_create
  - kernel/livepatch/core.c:klp_add_nops
  - kernel/livepatch/core.c:klp_add_nops
  - kernel/module/main.c:setup_modinfo_srcversion
  - kernel/module/main.c:setup_modinfo_version
  - kernel/module/kmod.c:__request_module
  - kernel/module/sysfs.c:add_sect_attrs
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - kernel/audit_watch.c:audit_dupe_exe
  - kernel/audit_watch.c:audit_update_watch
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:cache_mod
  - kernel/trace/ftrace.c:cache_mod
  - kernel/trace/trace.c:trace_array_create_systems
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:update_event_fields
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_trigger.c:save_named_trigger
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
  - kernel/trace/trace_events_synth.c:check_command
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:alloc_synth_event
  - kernel/trace/trace_events_synth.c:register_synth_event
  - kernel/trace/trace_events_synth.c:register_synth_event
  - kernel/trace/trace_events_hist.c:parse_actions
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_user.c:user_event_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/fprobe.c:register_fprobe
  - kernel/trace/fprobe.c:register_fprobe
  - kernel/trace/trace_fprobe.c:__trace_fprobe_create
  - kernel/trace/trace_fprobe.c:alloc_trace_fprobe
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/util.c:kstrdup_const
  - mm/memory-tiers.c:mt_set_default_dram_perf
  - mm/zsmalloc.c:zs_create_pool
  - fs/exec.c:bprm_change_interp
  - fs/xattr.c:simple_xattr_set
  - fs/proc/proc_sysctl.c:do_sysctl_args
  - fs/ext4/super.c:__ext4_remount
  - fs/fuse/inode.c:fuse_fill_super_submount
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/pstore/platform.c:pstore_register
  - security/security.c:ordered_lsm_parse
  - security/inode.c:securityfs_create_symlink
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:get_permissions_callback
  - security/selinux/ss/services.c:get_classes_callback
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/mls.c:mls_from_string
  - security/smack/smack_lsm.c:smack_key_getsecurity
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_fs_context_submount
  - security/smack/smack_lsm.c:smack_fs_context_submount
  - security/smack/smack_lsm.c:smack_fs_context_submount
  - security/smack/smack_lsm.c:smack_fs_context_submount
  - security/apparmor/audit.c:aa_dup_audit_data
  - security/apparmor/audit.c:aa_dup_audit_data
  - security/apparmor/audit.c:aa_dup_audit_data
  - security/apparmor/audit.c:aa_dup_audit_data
  - security/apparmor/audit.c:aa_dup_audit_data
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/safesetid/securityfs.c:handle_policy_update
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_queue_keys.c:ima_queue_key
  - block/partitions/cmdline.c:cmdline_partition
  - lib/string_helpers.c:kstrdup_and_replace
  - lib/string_helpers.c:kstrdup_quotable_file
  - lib/string_helpers.c:kstrdup_quotable_file
  - lib/string_helpers.c:kstrdup_quotable_file
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:param_set_dyndbg_classnames
  - drivers/gpio/gpiolib.c:gpiochip_dup_line_label
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/slot.c:make_slot_name
  - drivers/video/fbdev/core/fb_cmdline.c:fb_get_options
  - drivers/acpi/utils.c:acpi_get_subsystem_id
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_consumer_device_supply
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/char/misc.c:misc_devnode
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_rename
  - drivers/base/swnode.c:property_entry_copy_data
  - drivers/base/swnode.c:property_entry_copy_data
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/dax/bus.c:mapping_store
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/gpu/drm/drm_crtc.c:__drm_crtc_init_with_planes
  - drivers/gpu/drm/drm_ioctl.c:drm_setversion
  - drivers/gpu/drm/drm_edid_load.c:drm_edid_load_firmware
  - drivers/usb/core/quirks.c:quirks_param_set
  - drivers/hwmon/hwmon.c:__hwmon_sanitize_name
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - drivers/dpll/dpll_core.c:dpll_pin_prop_dup
  - drivers/dpll/dpll_core.c:dpll_pin_prop_dup
  - drivers/dpll/dpll_core.c:dpll_pin_prop_dup
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_alloc_ahash
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff813ee3e0-ffffffff813ee454: kstrdup (STB_GLOBAL)
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
char *kstrdup(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffff8000102d7df8)
Location: mm/util.c:51
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - kernel/kmod.c:__request_module
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:setup_modinfo_srcversion
  - kernel/module.c:setup_modinfo_version
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - kernel/audit_watch.c:audit_dupe_exe
  - kernel/audit_watch.c:audit_update_watch
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_trigger.c:save_named_trigger
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/events/core.c:perf_event_set_filter
  - mm/util.c:kstrdup_const
  - mm/zsmalloc.c:zs_create_pool
  - fs/exec.c:bprm_change_interp
  - fs/xattr.c:simple_xattr_set
  - fs/fs_context.c:logfc
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/debugfs/inode.c:debugfs_create_symlink
  - security/security.c:security_getprocattr
  - security/security.c:security_transfer_creds
  - security/security.c:security_prepare_creds
  - security/security.c:security_add_hooks
  - security/security.c:ordered_lsm_parse
  - security/inode.c:securityfs_create_symlink
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:get_permissions_callback
  - security/selinux/ss/services.c:get_classes_callback
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/mls.c:mls_from_string
  - security/smack/smack_lsm.c:smack_key_getsecurity
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/apparmor/domain.c:profile_transition
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/dynamic_debug.c:dynamic_debug_init
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/slot.c:make_slot_name
  - drivers/video/fbdev/core/fb_cmdline.c:fb_get_options
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/char/misc.c:misc_devnode
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_rename
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/dax/super.c:alloc_dax
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/of/kobj.c:safe_name
  - drivers/of/dynamic.c:__of_node_dup
  - drivers/of/dynamic.c:__of_prop_dup
  - drivers/of/overlay.c:dup_and_fixup_symbol_prop
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffff8000102d7df8-ffff8000102d7e6c: kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *kstrdup(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (c04ff280)
Location: mm/util.c:51
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - arch/arm/mach-mvebu/board-v7.c:mvebu_dt_init
  - arch/arm/mach-mvebu/board-v7.c:mvebu_dt_init
  - arch/arm/mach-mvebu/coherency.c:coherency_init
  - kernel/kmod.c:__request_module
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:setup_modinfo_srcversion
  - kernel/module.c:setup_modinfo_version
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - kernel/audit_watch.c:audit_dupe_exe
  - kernel/audit_watch.c:audit_update_watch
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_trigger.c:save_named_trigger
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/events/core.c:perf_event_set_filter
  - mm/util.c:kstrdup_const
  - mm/zsmalloc.c:zs_create_pool
  - fs/exec.c:bprm_change_interp
  - fs/xattr.c:simple_xattr_set
  - fs/fs_context.c:logfc
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/pstore/ram_core.c:persistent_ram_new
  - security/security.c:security_getprocattr
  - security/security.c:security_transfer_creds
  - security/security.c:security_prepare_creds
  - security/security.c:security_add_hooks
  - security/security.c:ordered_lsm_parse
  - security/inode.c:securityfs_create_symlink
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:get_permissions_callback
  - security/selinux/ss/services.c:get_classes_callback
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/mls.c:mls_from_string
  - security/smack/smack_lsm.c:smack_key_getsecurity
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/apparmor/domain.c:profile_transition
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/dynamic_debug.c:dynamic_debug_init
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/slot.c:make_slot_name
  - drivers/video/fbdev/core/fb_cmdline.c:fb_get_options
  - drivers/soc/tegra/powergate-bpmp.c:tegra_bpmp_init_powergates
  - drivers/soc/tegra/powergate-bpmp.c:tegra_bpmp_init_powergates
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/char/misc.c:misc_devnode
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_rename
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/dax/super.c:alloc_dax
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/mtd/mtdpart.c:allocate_partition
  - drivers/mtd/nand/raw/nand_base.c:nand_detect
  - drivers/mtd/nand/raw/nand_base.c:find_full_id_nand
  - drivers/mtd/nand/raw/nand_onfi.c:nand_onfi_detect
  - drivers/mtd/nand/raw/nand_jedec.c:nand_jedec_detect
  - drivers/usb/gadget/udc/core.c:usb_get_gadget_udc_name
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/of/kobj.c:safe_name
  - drivers/of/dynamic.c:__of_node_dup
  - drivers/of/dynamic.c:__of_prop_dup
  - drivers/of/overlay.c:dup_and_fixup_symbol_prop
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - sound/core/info.c:snd_info_create_entry
  - sound/core/info_oss.c:snd_oss_info_register
  - sound/core/jack.c:snd_jack_new
  - sound/core/timer.c:snd_timer_instance_new
  - sound/soc/soc-core.c:soc_add_dai
  - sound/soc/soc-core.c:fmt_single_name
  - sound/soc/soc-topology.c:soc_tplg_pcm_elems_load
  - sound/soc/soc-topology.c:soc_tplg_pcm_elems_load
  - sound/soc/soc-topology.c:soc_tplg_pcm_elems_load
  - sound/soc/soc-topology.c:soc_tplg_pcm_elems_load
  - sound/soc/soc-topology.c:set_stream_info
  - sound/soc/soc-topology.c:soc_tplg_dapm_widget_create
  - sound/soc/soc-topology.c:soc_tplg_dapm_widget_create
  - sound/soc/soc-topology.c:soc_tplg_dapm_widget_create
  - sound/soc/soc-topology.c:soc_tplg_dapm_widget_create
  - sound/soc/soc-topology.c:soc_tplg_dapm_widget_denum_create
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
c04ff280-c04ff2e0: kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *kstrdup(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (c0000000003978a0)
Location: mm/util.c:51
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - arch/powerpc/platforms/powernv/opal.c:opal_init
  - arch/powerpc/platforms/pseries/reconfig.c:ofdt_write
  - arch/powerpc/platforms/pseries/reconfig.c:new_property
  - arch/powerpc/platforms/pseries/iommu.c:enable_ddw
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_store
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_configure_connector
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_parse_cc_node
  - arch/powerpc/platforms/pseries/mobility.c:pseries_devicetree_update
  - kernel/kmod.c:__request_module
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:setup_modinfo_srcversion
  - kernel/module.c:setup_modinfo_version
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - kernel/audit_watch.c:audit_dupe_exe
  - kernel/audit_watch.c:audit_update_watch
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_trigger.c:save_named_trigger
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/events/core.c:perf_event_set_filter
  - mm/util.c:kstrdup_const
  - mm/zsmalloc.c:zs_create_pool
  - fs/exec.c:bprm_change_interp
  - fs/xattr.c:simple_xattr_set
  - fs/fs_context.c:logfc
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/debugfs/inode.c:debugfs_create_symlink
  - security/security.c:security_getprocattr
  - security/security.c:security_transfer_creds
  - security/security.c:security_prepare_creds
  - security/security.c:security_add_hooks
  - security/security.c:ordered_lsm_parse
  - security/inode.c:securityfs_create_symlink
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:get_permissions_callback
  - security/selinux/ss/services.c:get_classes_callback
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/mls.c:mls_from_string
  - security/smack/smack_lsm.c:smack_key_getsecurity
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/apparmor/domain.c:profile_transition
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/dynamic_debug.c:dynamic_debug_init
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/slot.c:make_slot_name
  - drivers/video/fbdev/core/fb_cmdline.c:fb_get_options
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/char/misc.c:misc_devnode
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_rename
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/dax/super.c:alloc_dax
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/of/kobj.c:safe_name
  - drivers/of/dynamic.c:__of_node_dup
  - drivers/of/dynamic.c:__of_prop_dup
  - drivers/of/overlay.c:dup_and_fixup_symbol_prop
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
c0000000003978a0-c000000000397958: kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *kstrdup(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffe0001f269c)
Location: mm/util.c:51
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - kernel/kmod.c:__request_module
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:setup_modinfo_srcversion
  - kernel/module.c:setup_modinfo_version
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - kernel/audit_watch.c:audit_dupe_exe
  - kernel/audit_watch.c:audit_update_watch
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_trigger.c:save_named_trigger
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/events/core.c:perf_event_set_filter
  - mm/util.c:kstrdup_const
  - mm/zsmalloc.c:zs_create_pool
  - fs/exec.c:bprm_change_interp
  - fs/xattr.c:simple_xattr_set
  - fs/fs_context.c:logfc
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/debugfs/inode.c:debugfs_create_symlink
  - security/security.c:security_getprocattr
  - security/security.c:security_transfer_creds
  - security/security.c:security_prepare_creds
  - security/security.c:security_add_hooks
  - security/security.c:ordered_lsm_parse
  - security/inode.c:securityfs_create_symlink
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:get_permissions_callback
  - security/selinux/ss/services.c:get_classes_callback
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/mls.c:mls_from_string
  - security/smack/smack_lsm.c:smack_key_getsecurity
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/apparmor/domain.c:profile_transition
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/dynamic_debug.c:dynamic_debug_init
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/slot.c:make_slot_name
  - drivers/video/fbdev/core/fb_cmdline.c:fb_get_options
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/char/misc.c:misc_devnode
  - drivers/base/core.c:device_rename
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/dax/super.c:alloc_dax
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/of/kobj.c:safe_name
  - drivers/of/dynamic.c:__of_node_dup
  - drivers/of/dynamic.c:__of_prop_dup
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffe0001f269c-ffffffe0001f2700: kstrdup (STB_GLOBAL)
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
char *kstrdup(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123d490)
Location: mm/util.c:51
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - kernel/kmod.c:__request_module
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:setup_modinfo_srcversion
  - kernel/module.c:setup_modinfo_version
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - kernel/audit_watch.c:audit_dupe_exe
  - kernel/audit_watch.c:audit_update_watch
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_trigger.c:save_named_trigger
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/events/core.c:perf_event_set_filter
  - mm/util.c:kstrdup_const
  - mm/zsmalloc.c:zs_create_pool
  - fs/exec.c:bprm_change_interp
  - fs/xattr.c:simple_xattr_set
  - fs/fs_context.c:logfc
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/debugfs/inode.c:debugfs_create_symlink
  - security/security.c:security_getprocattr
  - security/security.c:security_transfer_creds
  - security/security.c:security_prepare_creds
  - security/security.c:security_add_hooks
  - security/security.c:ordered_lsm_parse
  - security/inode.c:securityfs_create_symlink
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:get_permissions_callback
  - security/selinux/ss/services.c:get_classes_callback
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/mls.c:mls_from_string
  - security/smack/smack_lsm.c:smack_key_getsecurity
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/apparmor/domain.c:profile_transition
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/dynamic_debug.c:dynamic_debug_init
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/slot.c:make_slot_name
  - drivers/video/fbdev/core/fb_cmdline.c:fb_get_options
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/char/misc.c:misc_devnode
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_rename
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/dax/super.c:alloc_dax
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff8123d490-ffffffff8123d4ed: kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *kstrdup(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81230490)
Location: mm/util.c:51
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - kernel/kmod.c:__request_module
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:setup_modinfo_srcversion
  - kernel/module.c:setup_modinfo_version
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - kernel/audit_watch.c:audit_dupe_exe
  - kernel/audit_watch.c:audit_update_watch
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_trigger.c:save_named_trigger
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/events/core.c:perf_event_set_filter
  - mm/util.c:kstrdup_const
  - mm/zsmalloc.c:zs_create_pool
  - fs/exec.c:bprm_change_interp
  - fs/xattr.c:simple_xattr_set
  - fs/fs_context.c:logfc
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/debugfs/inode.c:debugfs_create_symlink
  - security/security.c:security_getprocattr
  - security/security.c:security_transfer_creds
  - security/security.c:security_prepare_creds
  - security/security.c:security_add_hooks
  - security/security.c:ordered_lsm_parse
  - security/inode.c:securityfs_create_symlink
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:get_permissions_callback
  - security/selinux/ss/services.c:get_classes_callback
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/mls.c:mls_from_string
  - security/smack/smack_lsm.c:smack_key_getsecurity
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/apparmor/domain.c:profile_transition
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/dynamic_debug.c:dynamic_debug_init
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/slot.c:make_slot_name
  - drivers/video/fbdev/core/fb_cmdline.c:fb_get_options
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/char/misc.c:misc_devnode
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_rename
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/dax/super.c:alloc_dax
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff81230490-ffffffff812304ed: kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *kstrdup(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123b230)
Location: mm/util.c:51
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - kernel/kmod.c:__request_module
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:setup_modinfo_srcversion
  - kernel/module.c:setup_modinfo_version
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - kernel/audit_watch.c:audit_dupe_exe
  - kernel/audit_watch.c:audit_update_watch
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_trigger.c:save_named_trigger
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/events/core.c:perf_event_set_filter
  - mm/util.c:kstrdup_const
  - mm/zsmalloc.c:zs_create_pool
  - fs/exec.c:bprm_change_interp
  - fs/xattr.c:simple_xattr_set
  - fs/fs_context.c:logfc
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/debugfs/inode.c:debugfs_create_symlink
  - security/security.c:security_getprocattr
  - security/security.c:security_transfer_creds
  - security/security.c:security_prepare_creds
  - security/security.c:security_add_hooks
  - security/security.c:ordered_lsm_parse
  - security/inode.c:securityfs_create_symlink
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:get_permissions_callback
  - security/selinux/ss/services.c:get_classes_callback
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/mls.c:mls_from_string
  - security/smack/smack_lsm.c:smack_key_getsecurity
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/apparmor/domain.c:profile_transition
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/dynamic_debug.c:dynamic_debug_init
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/slot.c:make_slot_name
  - drivers/video/fbdev/core/fb_cmdline.c:fb_get_options
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/char/misc.c:misc_devnode
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_rename
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/dax/super.c:alloc_dax
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff8123b230-ffffffff8123b28d: kstrdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *kstrdup(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8124a940)
Location: mm/util.c:51
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
  - kernel/kmod.c:__request_module
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:setup_modinfo_srcversion
  - kernel/module.c:setup_modinfo_version
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:audit_alloc
  - kernel/audit_watch.c:audit_dupe_exe
  - kernel/audit_watch.c:audit_update_watch
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter_start
  - kernel/trace/trace_events_trigger.c:save_named_trigger
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/events/core.c:perf_event_set_filter
  - mm/util.c:kstrdup_const
  - mm/zsmalloc.c:zs_create_pool
  - fs/exec.c:bprm_change_interp
  - fs/xattr.c:simple_xattr_set
  - fs/fs_context.c:logfc
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/debugfs/inode.c:debugfs_create_symlink
  - security/security.c:security_getprocattr
  - security/security.c:security_transfer_creds
  - security/security.c:security_prepare_creds
  - security/security.c:security_add_hooks
  - security/security.c:ordered_lsm_parse
  - security/inode.c:securityfs_create_symlink
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:get_permissions_callback
  - security/selinux/ss/services.c:get_classes_callback
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/mls.c:mls_from_string
  - security/smack/smack_lsm.c:smack_key_getsecurity
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/smack/smack_lsm.c:smack_fs_context_dup
  - security/apparmor/domain.c:profile_transition
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/dynamic_debug.c:dynamic_debug_init
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/pci.c:pci_realloc_setup_params
  - drivers/pci/slot.c:make_slot_name
  - drivers/video/fbdev/core/fb_cmdline.c:fb_get_options
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/char/misc.c:misc_devnode
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_rename
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/dax/super.c:alloc_dax
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff8124a940-ffffffff8124a99d: kstrdup (STB_GLOBAL)
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
