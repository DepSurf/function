# Function: <code>strsep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *strsep(char **s, const char *ct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff813f1c10)
Location: lib/string.c:589
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - kernel/cgroup.c:parse_cgroupfs_options
  - kernel/cgroup.c:cgroup_disable
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/trace/ftrace.c:set_ftrace_early_graph
  - kernel/trace/ftrace.c:ftrace_set_early_filter
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:ftrace_set_clr_event
  - kernel/trace/trace_events.c:early_enable_events
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - fs/proc/root.c:proc_parse_options
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smackfs.c:smk_parse_label_list
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - block/blk-throttle.c:tg_set_max
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/video/console/fbcon.c:fb_console_setup
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
```
**Symbols:**

```
ffffffff813f1c10-ffffffff813f1c75: strsep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *strsep(char **s, const char *ct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff814385b0)
Location: lib/string.c:589
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - kernel/cgroup.c:cgroup_no_v1
  - kernel/cgroup.c:cgroup_disable
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:parse_cgroupfs_options
  - kernel/trace/ftrace.c:set_ftrace_early_graph
  - kernel/trace/ftrace.c:ftrace_set_early_filter
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:early_enable_events
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:ftrace_set_clr_event
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_write
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
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/events/core.c:perf_event_set_addr_filter
  - mm/memcontrol.c:cgroup_memory
  - fs/proc/root.c:proc_parse_options
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smackfs.c:smk_parse_label_list
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-throttle.c:tg_set_max
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/video/console/fbcon.c:fb_console_setup
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_acpihid
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
```
**Symbols:**

```
ffffffff814385b0-ffffffff81438611: strsep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *strsep(char **s, const char *ct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff814555a0)
Location: lib/string.c:589
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_write
  - kernel/cgroup.c:cgroup_no_v1
  - kernel/cgroup.c:cgroup_disable
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:parse_cgroupfs_options
  - kernel/trace/ftrace.c:set_ftrace_early_graph
  - kernel/trace/ftrace.c:ftrace_set_early_filter
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:early_enable_events
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:ftrace_set_clr_event
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_write
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
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/bpf/inode.c:bpf_fill_super
  - kernel/events/core.c:perf_event_set_addr_filter
  - mm/memcontrol.c:cgroup_memory
  - fs/proc/root.c:proc_parse_options
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smackfs.c:smk_parse_label_list
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-throttle.c:tg_set_max
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/video/console/fbcon.c:fb_console_setup
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_acpihid
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
```
**Symbols:**

```
ffffffff814555a0-ffffffff81455601: strsep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *strsep(char **s, const char *ct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff818f7010)
Location: lib/string.c:589
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - arch/x86/kernel/cpu/intel_rdt.c:set_rdt_options
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - kernel/cgroup/cgroup.c:cgroup_disable
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:parse_cgroup_root_flags
  - kernel/cgroup/cgroup-v1.c:cgroup_no_v1
  - kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/seccomp.c:seccomp_actions_logged_handler
  - kernel/trace/ftrace.c:set_ftrace_early_graph
  - kernel/trace/ftrace.c:ftrace_set_early_filter
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:early_enable_events
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:ftrace_set_clr_event
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_write
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
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/bpf/inode.c:bpf_fill_super
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/memcontrol.c:cgroup_memory
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - fs/proc/root.c:proc_parse_options
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smackfs.c:smk_parse_label_list
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:policy_setup
  - block/blk-throttle.c:tg_set_limit
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/video/console/fbcon.c:fb_console_setup
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_acpihid
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
```
**Symbols:**

```
ffffffff818f7010-ffffffff818f7071: strsep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *strsep(char **s, const char *ct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff8197da10)
Location: lib/string.c:590
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - arch/x86/kernel/cpu/intel_rdt.c:set_rdt_options
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - kernel/cgroup/cgroup.c:cgroup_disable
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:parse_cgroup_root_flags
  - kernel/cgroup/cgroup-v1.c:cgroup_no_v1
  - kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/seccomp.c:seccomp_actions_logged_handler
  - kernel/trace/ftrace.c:set_ftrace_early_graph
  - kernel/trace/ftrace.c:ftrace_set_early_filter
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:early_enable_events
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:ftrace_set_clr_event
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_write
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
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/bpf/inode.c:bpf_fill_super
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/memcontrol.c:cgroup_memory
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - fs/proc/root.c:proc_parse_options
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smackfs.c:smk_parse_label_list
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:policy_setup
  - block/blk-throttle.c:tg_set_limit
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_acpihid
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
```
**Symbols:**

```
ffffffff8197da10-ffffffff8197da71: strsep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *strsep(char **s, const char *ct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff819d9f10)
Location: lib/string.c:590
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - arch/x86/kernel/cpu/intel_rdt.c:set_rdt_options
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - kernel/cgroup/cgroup.c:cgroup_disable
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:parse_cgroup_root_flags
  - kernel/cgroup/cgroup-v1.c:cgroup_no_v1
  - kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/ftrace.c:set_ftrace_early_graph
  - kernel/trace/ftrace.c:ftrace_set_early_filter
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:early_enable_events
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:ftrace_set_clr_event
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_write
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
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/bpf/inode.c:bpf_fill_super
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/memcontrol.c:cgroup_memory
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - fs/proc/root.c:proc_parse_options
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smackfs.c:smk_parse_label_list
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:policy_setup
  - block/blk-throttle.c:tg_set_limit
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_acpihid
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
```
**Symbols:**

```
ffffffff819d9f10-ffffffff819d9f6b: strsep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *strsep(char **s, const char *ct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a12130)
Location: lib/string.c:591
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - arch/x86/kernel/cpu/resctrl/core.c:set_rdt_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - kernel/cgroup/cgroup.c:cgroup_disable
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:parse_cgroup_root_flags
  - kernel/cgroup/cgroup-v1.c:cgroup_no_v1
  - kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/ftrace.c:set_ftrace_early_graph
  - kernel/trace/ftrace.c:ftrace_set_early_filter
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:early_enable_events
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:ftrace_set_clr_event
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/bpf/inode.c:bpf_fill_super
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/memcontrol.c:cgroup_memory
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - fs/proc/root.c:proc_parse_options
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/security.c:ordered_lsm_parse
  - security/smack/smackfs.c:smk_parse_label_list
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:policy_setup
  - block/blk-throttle.c:tg_set_limit
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_acpihid
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/media/cec/cec-core.c:cec_error_inj_write
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
```
**Symbols:**

```
ffffffff81a12130-ffffffff81a1218b: strsep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *strsep(char **s, const char *ct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a815c0)
Location: lib/string.c:633
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - arch/x86/kernel/cpu/resctrl/core.c:set_rdt_options
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - kernel/cgroup/cgroup.c:cgroup_disable
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_no_v1
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/ftrace.c:set_ftrace_early_graph
  - kernel/trace/ftrace.c:ftrace_set_early_filter
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:early_enable_events
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:ftrace_set_clr_event
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/bpf/inode.c:bpf_fill_super
  - kernel/events/core.c:perf_event_set_filter
  - mm/memcontrol.c:cgroup_memory
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - fs/fs_context.c:generic_parse_monolithic
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/fuse/inode.c:fuse_fill_super
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/security.c:ordered_lsm_parse
  - security/smack/smackfs.c:smk_parse_label_list
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:policy_setup
  - block/blk-throttle.c:tg_set_limit
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_acpihid
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/media/cec/cec-core.c:cec_error_inj_write
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
```
**Symbols:**

```
ffffffff81a815c0-ffffffff81a8161b: strsep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *strsep(char **s, const char *ct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81ab8690)
Location: lib/string.c:635
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - arch/x86/kernel/cpu/resctrl/core.c:set_rdt_options
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - kernel/cgroup/cgroup.c:cgroup_disable
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_no_v1
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/ftrace.c:set_ftrace_early_graph
  - kernel/trace/ftrace.c:ftrace_set_early_filter
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:early_enable_events
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:ftrace_set_clr_event
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/events/core.c:perf_event_set_filter
  - mm/memcontrol.c:cgroup_memory
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - fs/fs_context.c:generic_parse_monolithic
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/security.c:ordered_lsm_parse
  - security/smack/smackfs.c:smk_parse_label_list
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:policy_setup
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_acpihid
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_init
  - drivers/media/cec/cec-core.c:cec_error_inj_write
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
```
**Symbols:**

```
ffffffff81ab8690-ffffffff81ab86eb: strsep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *strsep(char **s, const char *ct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff815f32d0)
Location: lib/string.c:676
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - arch/x86/kernel/cpu/resctrl/core.c:set_rdt_options
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - kernel/panic.c:panic_on_taint_setup
  - kernel/cgroup/cgroup.c:cgroup_disable
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_no_v1
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:parse_resource
  - kernel/trace/ftrace.c:set_ftrace_early_graph
  - kernel/trace/ftrace.c:ftrace_set_early_filter
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/trace_functions.c:ftrace_cpudump_callback
  - kernel/trace/trace_functions.c:ftrace_dump_callback
  - kernel/trace/trace_functions.c:ftrace_stacktrace_callback
  - kernel/trace/blktrace.c:blk_trace_str2mask
  - kernel/trace/trace_events.c:early_enable_events
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:ftrace_set_clr_event
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:trigger_process_regex
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:create_val_fields
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/memcontrol.c:cgroup_memory
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - fs/fs_context.c:generic_parse_monolithic
  - fs/kernfs/dir.c:kernfs_walk_ns
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_parse
  - security/keys/trusted-keys/trusted_tpm1.c:datablob_parse
  - security/keys/trusted-keys/trusted_tpm1.c:datablob_parse
  - security/keys/trusted-keys/trusted_tpm1.c:datablob_parse
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/security.c:security_setprocattr
  - security/security.c:ordered_lsm_parse
  - security/smack/smackfs.c:smk_parse_label_list
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_keyring
  - security/integrity/ima/ima_policy.c:policy_setup
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_ids
  - drivers/usb/core/quirks.c:quirks_param_set
  - drivers/usb/core/quirks.c:quirks_param_set
  - drivers/usb/core/quirks.c:quirks_param_set
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
```
**Symbols:**

```
ffffffff815f32d0-ffffffff815f332f: strsep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *strsep(char **s, const char *ct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81617980)
Location: lib/string.c:673
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - arch/x86/kernel/cpu/resctrl/core.c:set_rdt_options
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - kernel/panic.c:panic_on_taint_setup
  - kernel/cgroup/cgroup.c:cgroup_disable
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_no_v1
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:parse_resource
  - kernel/trace/ftrace.c:set_ftrace_early_graph
  - kernel/trace/ftrace.c:ftrace_set_early_filter
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/trace_functions.c:ftrace_cpudump_callback
  - kernel/trace/trace_functions.c:ftrace_dump_callback
  - kernel/trace/trace_functions.c:ftrace_stacktrace_callback
  - kernel/trace/blktrace.c:blk_trace_str2mask
  - kernel/trace/trace_events.c:early_enable_events
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:ftrace_set_clr_event
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:trigger_process_regex
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:create_val_fields
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/memcontrol.c:cgroup_memory
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - fs/fs_context.c:generic_parse_monolithic
  - fs/kernfs/dir.c:kernfs_walk_ns
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_parse
  - security/keys/trusted-keys/trusted_tpm1.c:datablob_parse
  - security/keys/trusted-keys/trusted_tpm1.c:datablob_parse
  - security/keys/trusted-keys/trusted_tpm1.c:datablob_parse
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/security.c:security_setprocattr
  - security/security.c:ordered_lsm_parse
  - security/smack/smackfs.c:smk_parse_label_list
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_alloc_rule_opt_list
  - security/integrity/ima/ima_policy.c:policy_setup
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_ids
  - drivers/usb/core/quirks.c:quirks_param_set
  - drivers/usb/core/quirks.c:quirks_param_set
  - drivers/usb/core/quirks.c:quirks_param_set
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
```
**Symbols:**

```
ffffffff81617980-ffffffff816179df: strsep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *strsep(char **s, const char *ct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff815faff0)
Location: lib/string.c:673
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - arch/x86/kernel/cpu/resctrl/core.c:set_rdt_options
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - kernel/panic.c:panic_on_taint_setup
  - kernel/cgroup/cgroup.c:cgroup_disable
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_no_v1
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_parse_limits
  - kernel/cgroup/rdma.c:rdmacg_parse_limits
  - kernel/cgroup/misc.c:misc_cg_max_write
  - kernel/trace/ftrace.c:set_ftrace_early_graph
  - kernel/trace/ftrace.c:ftrace_set_early_filter
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/trace_functions.c:ftrace_cpudump_callback
  - kernel/trace/trace_functions.c:ftrace_dump_callback
  - kernel/trace/trace_functions.c:ftrace_stacktrace_callback
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:early_enable_events
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:ftrace_set_clr_event
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:trigger_process_regex
  - kernel/trace/trace_events_synth.c:check_command
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:create_val_fields
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/memcontrol.c:cgroup_memory
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - fs/fs_context.c:generic_parse_monolithic
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/security.c:security_setprocattr
  - security/security.c:ordered_lsm_parse
  - security/smack/smackfs.c:smk_parse_label_list
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_alloc_rule_opt_list
  - security/integrity/ima/ima_policy.c:policy_setup
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/dax/bus.c:mapping_store
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_ids
  - drivers/usb/core/quirks.c:quirks_param_set
  - drivers/usb/core/quirks.c:quirks_param_set
  - drivers/usb/core/quirks.c:quirks_param_set
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
```
**Symbols:**

```
ffffffff815faff0-ffffffff815fb04b: strsep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *strsep(char **s, const char *ct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff816688a0)
Location: lib/string.c:674
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - arch/x86/kernel/cpu/resctrl/core.c:set_rdt_options
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - kernel/panic.c:panic_on_taint_setup
  - kernel/cgroup/cgroup.c:cgroup_disable
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_no_v1
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_parse_limits
  - kernel/cgroup/rdma.c:rdmacg_parse_limits
  - kernel/cgroup/misc.c:misc_cg_max_write
  - kernel/trace/ftrace.c:set_ftrace_early_graph
  - kernel/trace/ftrace.c:ftrace_set_early_filter
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/trace_functions.c:ftrace_cpudump_callback
  - kernel/trace/trace_functions.c:ftrace_dump_callback
  - kernel/trace/trace_functions.c:ftrace_stacktrace_callback
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:early_enable_events
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:ftrace_set_clr_event
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:trigger_process_regex
  - kernel/trace/trace_events_synth.c:check_command
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:create_val_fields
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/memcontrol.c:cgroup_memory
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - fs/fs_context.c:generic_parse_monolithic
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/security.c:security_setprocattr
  - security/security.c:ordered_lsm_parse
  - security/smack/smackfs.c:smk_parse_label_list
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_alloc_rule_opt_list
  - security/integrity/ima/ima_policy.c:policy_setup
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - drivers/pci/pci.c:reset_method_store
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/dax/bus.c:mapping_store
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_ids
  - drivers/usb/core/quirks.c:quirks_param_set
  - drivers/usb/core/quirks.c:quirks_param_set
  - drivers/usb/core/quirks.c:quirks_param_set
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
```
**Symbols:**

```
ffffffff816688a0-ffffffff816688fb: strsep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *strsep(char **s, const char *ct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81782030)
Location: lib/string.c:582
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/resctrl/core.c:set_rdt_options
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/sev.c:init_sev_config
  - kernel/panic.c:panic_on_taint_setup
  - kernel/cgroup/cgroup.c:cgroup_disable
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_no_v1
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_parse_limits
  - kernel/cgroup/rdma.c:rdmacg_parse_limits
  - kernel/cgroup/misc.c:misc_cg_max_write
  - kernel/trace/ftrace.c:set_ftrace_early_graph
  - kernel/trace/ftrace.c:ftrace_set_early_filter
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:early_enable_events
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:ftrace_set_clr_event
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_parse_num
  - kernel/trace/trace_events_trigger.c:event_trigger_separate_filter
  - kernel/trace/trace_events_trigger.c:trigger_process_regex
  - kernel/trace/trace_events_synth.c:check_command
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/huge_memory.c:split_huge_pages_write
  - mm/memcontrol.c:cgroup_memory
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - fs/fs_context.c:generic_parse_monolithic
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/security.c:security_setprocattr
  - security/security.c:ordered_lsm_parse
  - security/smack/smackfs.c:smk_parse_label_list
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_alloc_rule_opt_list
  - security/integrity/ima/ima_policy.c:policy_setup
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - drivers/pci/pci.c:reset_method_store
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/dax/bus.c:mapping_store
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_ids
  - drivers/usb/core/quirks.c:quirks_param_set
  - drivers/usb/core/quirks.c:quirks_param_set
  - drivers/usb/core/quirks.c:quirks_param_set
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
```
**Symbols:**

```
ffffffff81782030-ffffffff817820ac: strsep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *strsep(char **s, const char *ct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff8203ee50)
Location: lib/string.c:508
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/resctrl/core.c:set_rdt_options
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/sev.c:init_sev_config
  - kernel/panic.c:panic_on_taint_setup
  - kernel/cgroup/cgroup.c:cgroup_disable
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_no_v1
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_parse_limits
  - kernel/cgroup/rdma.c:rdmacg_parse_limits
  - kernel/cgroup/misc.c:misc_cg_max_write
  - kernel/trace/ftrace.c:set_ftrace_early_graph
  - kernel/trace/ftrace.c:ftrace_set_early_filter
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:early_enable_events
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:setup_trace_triggers
  - kernel/trace/trace_events.c:setup_trace_triggers
  - kernel/trace/trace_events.c:setup_trace_triggers
  - kernel/trace/trace_events.c:ftrace_set_clr_event
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_parse_num
  - kernel/trace/trace_events_trigger.c:event_trigger_separate_filter
  - kernel/trace/trace_events_trigger.c:trigger_process_regex
  - kernel/trace/trace_events_synth.c:check_command
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:create_val_fields
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/vmscan.c:lru_gen_seq_write
  - mm/huge_memory.c:split_huge_pages_write
  - mm/memcontrol.c:cgroup_memory
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - fs/fs_context.c:generic_parse_monolithic
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/security.c:ordered_lsm_parse
  - security/smack/smackfs.c:smk_parse_label_list
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_alloc_rule_opt_list
  - security/integrity/ima/ima_policy.c:policy_setup
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - drivers/pci/pci.c:reset_method_store
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/dax/bus.c:mapping_store
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/usb/core/quirks.c:quirks_param_set
  - drivers/usb/core/quirks.c:quirks_param_set
  - drivers/usb/core/quirks.c:quirks_param_set
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
```
**Symbols:**

```
ffffffff8203ee50-ffffffff8203eecc: strsep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *strsep(char **s, const char *ct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff820bdc10)
Location: lib/string.c:506
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/resctrl/core.c:set_rdt_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mon_config_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mon_config_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/sev.c:init_sev_config
  - kernel/panic.c:panic_on_taint_setup
  - kernel/cgroup/cgroup.c:cgroup_disable
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_no_v1
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:parse_resource
  - kernel/cgroup/misc.c:misc_cg_max_write
  - kernel/trace/ftrace.c:set_ftrace_early_graph
  - kernel/trace/ftrace.c:ftrace_set_early_filter
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:early_enable_events
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:setup_trace_triggers
  - kernel/trace/trace_events.c:setup_trace_triggers
  - kernel/trace/trace_events.c:ftrace_set_clr_event
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_parse_num
  - kernel/trace/trace_events_trigger.c:event_trigger_separate_filter
  - kernel/trace/trace_events_trigger.c:trigger_process_regex
  - kernel/trace/trace_events_synth.c:check_command
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:create_val_fields
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_user.c:user_event_parse
  - kernel/trace/trace_events_user.c:user_event_parse_field
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/vmscan.c:lru_gen_seq_write
  - mm/huge_memory.c:split_huge_pages_write
  - mm/memcontrol.c:cgroup_memory
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - fs/fs_context.c:generic_parse_monolithic
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/security.c:ordered_lsm_parse
  - security/smack/smackfs.c:smk_parse_label_list
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_alloc_rule_opt_list
  - security/integrity/ima/ima_policy.c:policy_setup
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - drivers/pci/pci.c:reset_method_store
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/dax/bus.c:mapping_store
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/usb/core/quirks.c:quirks_param_set
  - drivers/usb/core/quirks.c:quirks_param_set
  - drivers/usb/core/quirks.c:quirks_param_set
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
```
**Symbols:**

```
ffffffff820bdc10-ffffffff820bdc9d: strsep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *strsep(char **s, const char *ct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff82198490)
Location: lib/string.c:491
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/resctrl/core.c:set_rdt_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mon_config_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mon_config_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/sev.c:init_sev_config
  - kernel/panic.c:panic_on_taint_setup
  - kernel/cgroup/cgroup.c:cgroup_disable
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_no_v1
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:parse_resource
  - kernel/cgroup/misc.c:misc_cg_max_write
  - kernel/trace/ftrace.c:set_ftrace_early_graph
  - kernel/trace/ftrace.c:ftrace_set_early_filter
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:early_enable_events
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:setup_trace_triggers
  - kernel/trace/trace_events.c:setup_trace_triggers
  - kernel/trace/trace_events.c:ftrace_set_clr_event
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_parse_num
  - kernel/trace/trace_events_trigger.c:event_trigger_separate_filter
  - kernel/trace/trace_events_trigger.c:trigger_process_regex
  - kernel/trace/trace_events_synth.c:check_command
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:parse_actions
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:create_val_fields
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_user.c:user_event_parse
  - kernel/trace/trace_events_user.c:user_event_parse_field
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/vmscan.c:lru_gen_seq_write
  - mm/huge_memory.c:split_huge_pages_write
  - mm/memcontrol.c:cgroup_memory
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - fs/fs_context.c:vfs_parse_comma_sep
  - fs/kernfs/dir.c:kernfs_walk_ns
  - fs/kernfs/dir.c:kernfs_walk_ns
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/security.c:ordered_lsm_parse
  - security/smack/smackfs.c:smk_parse_label_list
  - security/apparmor/lsm.c:do_setattr
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_fs.c:ima_read_policy
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_alloc_rule_opt_list
  - security/integrity/ima/ima_policy.c:policy_setup
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - drivers/pci/pci.c:reset_method_store
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/dax/bus.c:mapping_store
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/gpu/drm/drm_edid_load.c:drm_edid_load_firmware
  - drivers/usb/core/quirks.c:quirks_param_set
  - drivers/usb/core/quirks.c:quirks_param_set
  - drivers/usb/core/quirks.c:quirks_param_set
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
```
**Symbols:**

```
ffffffff82198490-ffffffff8219851d: strsep (STB_GLOBAL)
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
char *strsep(char **s, const char *ct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffff800010d92b00)
Location: lib/string.c:635
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - kernel/cgroup/cgroup.c:cgroup_disable
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_no_v1
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/ftrace.c:set_ftrace_early_graph
  - kernel/trace/ftrace.c:ftrace_set_early_filter
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:early_enable_events
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:ftrace_set_clr_event
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - mm/memcontrol.c:cgroup_memory
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - fs/fs_context.c:generic_parse_monolithic
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/devpts/inode.c:parse_mount_options
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/security.c:ordered_lsm_parse
  - security/smack/smackfs.c:smk_parse_label_list
  - security/smack/smackfs.c:smk_parse_label_list
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:policy_setup
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/mx3fb.c:mx3fb_init
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/media/cec/cec-core.c:cec_error_inj_write
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
```
**Symbols:**

```
ffff800010d92b00-ffff800010d92b68: strsep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *strsep(char **s, const char *ct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (c0e8f2b8)
Location: lib/string.c:635
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - kernel/cgroup/cgroup.c:cgroup_disable
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_no_v1
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/ftrace.c:set_ftrace_early_graph
  - kernel/trace/ftrace.c:ftrace_set_early_filter
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:early_enable_events
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:ftrace_set_clr_event
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/events/core.c:perf_event_set_filter
  - mm/memcontrol.c:cgroup_memory
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - fs/fs_context.c:generic_parse_monolithic
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:getoptions
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/security.c:ordered_lsm_parse
  - security/smack/smackfs.c:smk_parse_label_list
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:policy_setup
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/mx3fb.c:mx3fb_init
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/media/cec/cec-core.c:cec_error_inj_write
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
```
**Symbols:**

```
c0e8f2b8-c0e8f338: strsep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *strsep(char **s, const char *ct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (c000000000ed6ab0)
Location: lib/string.c:635
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_store
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_store
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_store
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_store
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_store
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_store
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_store
  - kernel/cgroup/cgroup.c:cgroup_disable
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_no_v1
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/ftrace.c:set_ftrace_early_graph
  - kernel/trace/ftrace.c:ftrace_set_early_filter
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:early_enable_events
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:ftrace_set_clr_event
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/events/core.c:perf_event_set_filter
  - mm/memcontrol.c:cgroup_memory
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - fs/fs_context.c:generic_parse_monolithic
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/devpts/inode.c:parse_mount_options
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/security.c:ordered_lsm_parse
  - security/smack/smackfs.c:smk_parse_label_list
  - security/smack/smackfs.c:smk_parse_label_list
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:policy_setup
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_init
  - drivers/media/cec/cec-core.c:cec_error_inj_write
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
```
**Symbols:**

```
c000000000ed6ab0-c000000000ed6b44: strsep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *strsep(char **s, const char *ct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffe0008bcc18)
Location: lib/string.c:635
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - kernel/cgroup/cgroup.c:cgroup_disable
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_no_v1
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/ftrace.c:set_ftrace_early_graph
  - kernel/trace/ftrace.c:ftrace_set_early_filter
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:early_enable_events
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:ftrace_set_clr_event
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/events/core.c:perf_event_set_filter
  - mm/memcontrol.c:cgroup_memory
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - fs/fs_context.c:generic_parse_monolithic
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/devpts/inode.c:parse_mount_options
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/security.c:ordered_lsm_parse
  - security/smack/smackfs.c:smk_parse_label_list
  - security/smack/smackfs.c:smk_parse_label_list
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:policy_setup
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/media/cec/cec-core.c:cec_error_inj_write
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
```
**Symbols:**

```
ffffffe0008bcc18-ffffffe0008bcc68: strsep (STB_GLOBAL)
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
char *strsep(char **s, const char *ct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a574e0)
Location: lib/string.c:635
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - arch/x86/kernel/cpu/resctrl/core.c:set_rdt_options
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - kernel/cgroup/cgroup.c:cgroup_disable
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_no_v1
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/ftrace.c:set_ftrace_early_graph
  - kernel/trace/ftrace.c:ftrace_set_early_filter
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:early_enable_events
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:ftrace_set_clr_event
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/events/core.c:perf_event_set_filter
  - mm/memcontrol.c:cgroup_memory
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - fs/fs_context.c:generic_parse_monolithic
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/security.c:ordered_lsm_parse
  - security/smack/smackfs.c:smk_parse_label_list
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:policy_setup
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_acpihid
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/media/cec/cec-core.c:cec_error_inj_write
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
```
**Symbols:**

```
ffffffff81a574e0-ffffffff81a5753b: strsep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *strsep(char **s, const char *ct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a145c0)
Location: lib/string.c:635
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - arch/x86/kernel/cpu/resctrl/core.c:set_rdt_options
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - kernel/cgroup/cgroup.c:cgroup_disable
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_no_v1
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/ftrace.c:set_ftrace_early_graph
  - kernel/trace/ftrace.c:ftrace_set_early_filter
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:early_enable_events
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:ftrace_set_clr_event
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/events/core.c:perf_event_set_filter
  - mm/memcontrol.c:cgroup_memory
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - fs/fs_context.c:generic_parse_monolithic
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/security.c:ordered_lsm_parse
  - security/smack/smackfs.c:smk_parse_label_list
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:policy_setup
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_acpihid
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_init
  - drivers/media/cec/cec-core.c:cec_error_inj_write
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
```
**Symbols:**

```
ffffffff81a145c0-ffffffff81a1461b: strsep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *strsep(char **s, const char *ct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81ac38d0)
Location: lib/string.c:635
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - arch/x86/kernel/cpu/resctrl/core.c:set_rdt_options
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - kernel/cgroup/cgroup.c:cgroup_disable
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_no_v1
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/ftrace.c:set_ftrace_early_graph
  - kernel/trace/ftrace.c:ftrace_set_early_filter
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:early_enable_events
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:ftrace_set_clr_event
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/events/core.c:perf_event_set_filter
  - mm/memcontrol.c:cgroup_memory
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - fs/fs_context.c:generic_parse_monolithic
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/security.c:ordered_lsm_parse
  - security/smack/smackfs.c:smk_parse_label_list
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:policy_setup
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_acpihid
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_init
  - drivers/media/cec/cec-core.c:cec_error_inj_write
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
```
**Symbols:**

```
ffffffff81ac38d0-ffffffff81ac392b: strsep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *strsep(char **s, const char *ct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81acfda0)
Location: lib/string.c:635
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - arch/x86/kernel/cpu/resctrl/core.c:set_rdt_options
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - kernel/cgroup/cgroup.c:cgroup_disable
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_no_v1
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/trace/ftrace.c:set_ftrace_early_graph
  - kernel/trace/ftrace.c:ftrace_set_early_filter
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events.c:early_enable_events
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:ftrace_set_clr_event
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/events/core.c:perf_event_set_filter
  - mm/memcontrol.c:cgroup_memory
  - mm/vmpressure.c:vmpressure_register_event
  - mm/vmpressure.c:vmpressure_register_event
  - fs/fs_context.c:generic_parse_monolithic
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/security.c:ordered_lsm_parse
  - security/smack/smackfs.c:smk_parse_label_list
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:policy_setup
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/iommu/amd_iommu_init.c:parse_ivrs_acpihid
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_str
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_init
  - drivers/media/cec/cec-core.c:cec_error_inj_write
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
```
**Symbols:**

```
ffffffff81acfda0-ffffffff81acfdfb: strsep (STB_GLOBAL)
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
