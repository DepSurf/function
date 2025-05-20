# Function: <code>simple_read_from_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t simple_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81234160)
Location: fs/libfs.c:585
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:tlbflush_read_file
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/user.c:snapshot_read
  - kernel/kprobes.c:read_enabled_file_bool
  - kernel/trace/ftrace.c:ftrace_profile_read
  - kernel/trace/trace.c:trace_options_read
  - kernel/trace/trace.c:tracing_readme_read
  - kernel/trace/trace.c:trace_options_core_read
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_set_trace_read
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:tracing_cpumask_read
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_read_dyn_info
  - kernel/trace/trace_stack.c:stack_max_size_read
  - kernel/trace/trace_functions_graph.c:graph_depth_read
  - kernel/trace/blktrace.c:blk_dropped_read
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/trace_events.c:subsystem_filter_read
  - fs/libfs.c:simple_transaction_read
  - fs/libfs.c:simple_attr_read
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:u32_array_read
  - fs/pstore/inode.c:pstore_file_read
  - fs/efivarfs/file.c:efivarfs_file_read
  - ipc/mqueue.c:mqueue_read_file
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_read_checkreqprot
  - security/selinux/selinuxfs.c:sel_read_policyvers
  - security/selinux/selinuxfs.c:sel_read_enforce
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/selinuxfs.c:sel_read_mls
  - security/selinux/selinuxfs.c:sel_read_class
  - security/selinux/selinuxfs.c:sel_read_perm
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_read_policycap
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - drivers/regulator/core.c:supply_map_read_file
  - drivers/char/virtio_console.c:debugfs_read
  - drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_read_file
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/usb/host/uhci-hcd.c:uhci_debug_read
  - drivers/mmc/core/debugfs.c:mmc_ext_csd_read
```
**Symbols:**

```
ffffffff81234160-ffffffff812341cf: simple_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t simple_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8125d1d0)
Location: fs/libfs.c:613
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:tlbflush_read_file
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/user.c:snapshot_read
  - kernel/kprobes.c:read_enabled_file_bool
  - kernel/trace/ftrace.c:ftrace_profile_read
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:trace_options_core_read
  - kernel/trace/trace.c:trace_options_read
  - kernel/trace/trace.c:tracing_read_dyn_info
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_set_trace_read
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:tracing_readme_read
  - kernel/trace/trace.c:tracing_cpumask_read
  - kernel/trace/trace_stack.c:stack_max_size_read
  - kernel/trace/trace_functions_graph.c:graph_depth_read
  - kernel/trace/blktrace.c:blk_dropped_read
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - fs/libfs.c:simple_attr_read
  - fs/libfs.c:simple_transaction_read
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/debugfs/file.c:u32_array_read
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/pstore/inode.c:pstore_file_read
  - fs/efivarfs/file.c:efivarfs_file_read
  - ipc/mqueue.c:mqueue_read_file
  - security/selinux/selinuxfs.c:sel_read_policycap
  - security/selinux/selinuxfs.c:sel_read_perm
  - security/selinux/selinuxfs.c:sel_read_class
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_read_checkreqprot
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_read_mls
  - security/selinux/selinuxfs.c:sel_read_policyvers
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/selinuxfs.c:sel_read_enforce
  - security/apparmor/apparmorfs.c:rawdata_read
  - security/apparmor/apparmorfs.c:rawdata_read
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
  - drivers/regulator/core.c:supply_map_read_file
  - drivers/regulator/core.c:constraint_flags_read_file
  - drivers/char/virtio_console.c:debugfs_read
  - drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_read_file
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/usb/host/uhci-hcd.c:uhci_debug_read
  - drivers/mmc/core/debugfs.c:mmc_ext_csd_read
```
**Symbols:**

```
ffffffff8125d1d0-ffffffff8125d264: simple_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t simple_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81270700)
Location: fs/libfs.c:621
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:tlbflush_read_file
  - arch/x86/mm/pkeys.c:init_pkru_read_file
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/user.c:snapshot_read
  - kernel/kprobes.c:read_enabled_file_bool
  - kernel/trace/ftrace.c:ftrace_profile_read
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:trace_options_core_read
  - kernel/trace/trace.c:trace_options_read
  - kernel/trace/trace.c:tracing_read_dyn_info
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_set_trace_read
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:tracing_readme_read
  - kernel/trace/trace.c:tracing_cpumask_read
  - kernel/trace/trace_hwlat.c:hwlat_read
  - kernel/trace/trace_stack.c:stack_max_size_read
  - kernel/trace/trace_functions_graph.c:graph_depth_read
  - kernel/trace/blktrace.c:blk_dropped_read
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - fs/libfs.c:simple_attr_read
  - fs/libfs.c:simple_transaction_read
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:auxv_read
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/debugfs/file.c:u32_array_read
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/pstore/inode.c:pstore_file_read
  - fs/efivarfs/file.c:efivarfs_file_read
  - ipc/mqueue.c:mqueue_read_file
  - security/selinux/selinuxfs.c:sel_read_policycap
  - security/selinux/selinuxfs.c:sel_read_perm
  - security/selinux/selinuxfs.c:sel_read_class
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_read_checkreqprot
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_read_mls
  - security/selinux/selinuxfs.c:sel_read_policyvers
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/selinuxfs.c:sel_read_enforce
  - security/apparmor/apparmorfs.c:rawdata_read
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
  - drivers/regulator/core.c:supply_map_read_file
  - drivers/regulator/core.c:constraint_flags_read_file
  - drivers/char/virtio_console.c:debugfs_read
  - drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_read_file
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/usb/host/uhci-hcd.c:uhci_debug_read
  - drivers/mmc/core/debugfs.c:mmc_ext_csd_read
```
**Symbols:**

```
ffffffff81270700-ffffffff81270794: simple_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t simple_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8127e100)
Location: fs/libfs.c:622
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:tlbflush_read_file
  - arch/x86/mm/pkeys.c:init_pkru_read_file
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/user.c:snapshot_read
  - kernel/kprobes.c:read_enabled_file_bool
  - kernel/trace/ftrace.c:ftrace_profile_read
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:trace_options_core_read
  - kernel/trace/trace.c:trace_options_read
  - kernel/trace/trace.c:tracing_read_dyn_info
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_set_trace_read
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:tracing_readme_read
  - kernel/trace/trace.c:tracing_cpumask_read
  - kernel/trace/trace_hwlat.c:hwlat_read
  - kernel/trace/trace_stack.c:stack_max_size_read
  - kernel/trace/trace_functions_graph.c:graph_depth_read
  - kernel/trace/blktrace.c:blk_dropped_read
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - fs/libfs.c:simple_attr_read
  - fs/libfs.c:simple_transaction_read
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:auxv_read
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/configfs/file.c:configfs_read_file
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/debugfs/file.c:u32_array_read
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/pstore/inode.c:pstore_file_read
  - fs/efivarfs/file.c:efivarfs_file_read
  - ipc/mqueue.c:mqueue_read_file
  - security/inode.c:lsm_read
  - security/selinux/selinuxfs.c:sel_read_policycap
  - security/selinux/selinuxfs.c:sel_read_perm
  - security/selinux/selinuxfs.c:sel_read_class
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_read_checkreqprot
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_read_mls
  - security/selinux/selinuxfs.c:sel_read_policyvers
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/selinuxfs.c:sel_read_enforce
  - security/apparmor/apparmorfs.c:rawdata_read
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
  - drivers/regulator/core.c:constraint_flags_read_file
  - drivers/char/virtio_console.c:debugfs_read
  - drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_read_file
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/usb/host/uhci-hcd.c:uhci_debug_read
  - drivers/mmc/core/debugfs.c:mmc_ext_csd_read
```
**Symbols:**

```
ffffffff8127e100-ffffffff8127e195: simple_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t simple_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812a0be0)
Location: fs/libfs.c:622
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:tlbflush_read_file
  - arch/x86/mm/pkeys.c:init_pkru_read_file
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/user.c:snapshot_read
  - kernel/kprobes.c:read_enabled_file_bool
  - kernel/trace/ftrace.c:ftrace_profile_read
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:trace_options_core_read
  - kernel/trace/trace.c:trace_options_read
  - kernel/trace/trace.c:tracing_read_dyn_info
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_set_trace_read
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:tracing_readme_read
  - kernel/trace/trace.c:tracing_cpumask_read
  - kernel/trace/trace_hwlat.c:hwlat_read
  - kernel/trace/trace_stack.c:stack_max_size_read
  - kernel/trace/trace_functions_graph.c:graph_depth_read
  - kernel/trace/blktrace.c:blk_dropped_read
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - fs/libfs.c:simple_attr_read
  - fs/libfs.c:simple_transaction_read
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:auxv_read
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/configfs/file.c:configfs_read_file
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/debugfs/file.c:u32_array_read
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/pstore/inode.c:pstore_file_read
  - fs/efivarfs/file.c:efivarfs_file_read
  - ipc/mqueue.c:mqueue_read_file
  - security/inode.c:lsm_read
  - security/selinux/selinuxfs.c:sel_read_policycap
  - security/selinux/selinuxfs.c:sel_read_perm
  - security/selinux/selinuxfs.c:sel_read_class
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_read_checkreqprot
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_read_mls
  - security/selinux/selinuxfs.c:sel_read_policyvers
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/selinuxfs.c:sel_read_enforce
  - security/apparmor/apparmorfs.c:rawdata_read
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
  - drivers/regulator/core.c:constraint_flags_read_file
  - drivers/char/virtio_console.c:debugfs_read
  - drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_read_file
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/usb/host/uhci-hcd.c:uhci_debug_read
```
**Symbols:**

```
ffffffff812a0be0-ffffffff812a0c75: simple_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t simple_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812c7740)
Location: fs/libfs.c:622
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:tlbflush_read_file
  - arch/x86/mm/pkeys.c:init_pkru_read_file
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/user.c:snapshot_read
  - kernel/kprobes.c:read_enabled_file_bool
  - kernel/trace/ftrace.c:ftrace_profile_read
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:trace_options_core_read
  - kernel/trace/trace.c:trace_options_read
  - kernel/trace/trace.c:tracing_read_dyn_info
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_set_trace_read
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:tracing_readme_read
  - kernel/trace/trace.c:tracing_cpumask_read
  - kernel/trace/trace_hwlat.c:hwlat_read
  - kernel/trace/trace_stack.c:stack_max_size_read
  - kernel/trace/trace_functions_graph.c:graph_depth_read
  - kernel/trace/blktrace.c:blk_dropped_read
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - fs/libfs.c:simple_attr_read
  - fs/libfs.c:simple_transaction_read
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:auxv_read
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/configfs/file.c:configfs_read_file
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/debugfs/file.c:u32_array_read
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/pstore/inode.c:pstore_file_read
  - fs/efivarfs/file.c:efivarfs_file_read
  - ipc/mqueue.c:mqueue_read_file
  - security/inode.c:lsm_read
  - security/selinux/selinuxfs.c:sel_read_policycap
  - security/selinux/selinuxfs.c:sel_read_perm
  - security/selinux/selinuxfs.c:sel_read_class
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_read_checkreqprot
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_read_mls
  - security/selinux/selinuxfs.c:sel_read_policyvers
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/selinuxfs.c:sel_read_enforce
  - security/apparmor/apparmorfs.c:rawdata_read
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
  - drivers/regulator/core.c:constraint_flags_read_file
  - drivers/char/virtio_console.c:debugfs_read
  - drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_read_file
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/usb/host/uhci-hcd.c:uhci_debug_read
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_debugfs_read
```
**Symbols:**

```
ffffffff812c7740-ffffffff812c77d5: simple_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t simple_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812dc940)
Location: fs/libfs.c:622
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:tlbflush_read_file
  - arch/x86/mm/pkeys.c:init_pkru_read_file
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/user.c:snapshot_read
  - kernel/kprobes.c:read_enabled_file_bool
  - kernel/trace/ftrace.c:ftrace_profile_read
  - kernel/trace/trace.c:buffer_percent_read
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:trace_options_core_read
  - kernel/trace/trace.c:trace_options_read
  - kernel/trace/trace.c:tracing_read_dyn_info
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_set_trace_read
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:tracing_readme_read
  - kernel/trace/trace.c:tracing_cpumask_read
  - kernel/trace/trace_hwlat.c:hwlat_read
  - kernel/trace/trace_stack.c:stack_max_size_read
  - kernel/trace/trace_functions_graph.c:graph_depth_read
  - kernel/trace/blktrace.c:blk_dropped_read
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - fs/libfs.c:simple_attr_read
  - fs/libfs.c:simple_transaction_read
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:auxv_read
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/configfs/file.c:configfs_read_file
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/debugfs/file.c:u32_array_read
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/pstore/inode.c:pstore_file_read
  - fs/efivarfs/file.c:efivarfs_file_read
  - ipc/mqueue.c:mqueue_read_file
  - security/inode.c:lsm_read
  - security/selinux/selinuxfs.c:sel_read_policycap
  - security/selinux/selinuxfs.c:sel_read_perm
  - security/selinux/selinuxfs.c:sel_read_class
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_read_checkreqprot
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_read_mls
  - security/selinux/selinuxfs.c:sel_read_policyvers
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/selinuxfs.c:sel_read_enforce
  - security/apparmor/apparmorfs.c:attr_read
  - security/apparmor/apparmorfs.c:rawdata_read
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
  - drivers/regulator/core.c:constraint_flags_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_read_file
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/usb/host/uhci-hcd.c:uhci_debug_read
```
**Symbols:**

```
ffffffff812dc940-ffffffff812dc9d5: simple_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t simple_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812fb000)
Location: fs/libfs.c:641
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:tlbflush_read_file
  - arch/x86/mm/pkeys.c:init_pkru_read_file
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/user.c:snapshot_read
  - kernel/kprobes.c:read_enabled_file_bool
  - kernel/trace/ftrace.c:ftrace_profile_read
  - kernel/trace/trace.c:buffer_percent_read
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:trace_options_core_read
  - kernel/trace/trace.c:trace_options_read
  - kernel/trace/trace.c:tracing_read_dyn_info
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_set_trace_read
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:tracing_readme_read
  - kernel/trace/trace.c:tracing_cpumask_read
  - kernel/trace/trace_hwlat.c:hwlat_read
  - kernel/trace/trace_stack.c:stack_max_size_read
  - kernel/trace/trace_functions_graph.c:graph_depth_read
  - kernel/trace/blktrace.c:blk_dropped_read
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - fs/libfs.c:simple_attr_read
  - fs/libfs.c:simple_transaction_read
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:auxv_read
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/configfs/file.c:configfs_read_file
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/debugfs/file.c:u32_array_read
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/pstore/inode.c:pstore_file_read
  - fs/efivarfs/file.c:efivarfs_file_read
  - ipc/mqueue.c:mqueue_read_file
  - security/inode.c:lsm_read
  - security/selinux/selinuxfs.c:sel_read_policycap
  - security/selinux/selinuxfs.c:sel_read_perm
  - security/selinux/selinuxfs.c:sel_read_class
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_read_checkreqprot
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_read_mls
  - security/selinux/selinuxfs.c:sel_read_policyvers
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/selinuxfs.c:sel_read_enforce
  - security/apparmor/apparmorfs.c:attr_read
  - security/apparmor/apparmorfs.c:rawdata_read
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/safesetid/securityfs.c:safesetid_file_read
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
  - drivers/regulator/core.c:constraint_flags_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_read_file
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/usb/host/uhci-hcd.c:uhci_debug_read
```
**Symbols:**

```
ffffffff812fb000-ffffffff812fb095: simple_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t simple_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8130c390)
Location: fs/libfs.c:646
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:tlbflush_read_file
  - arch/x86/mm/pkeys.c:init_pkru_read_file
  - arch/x86/platform/uv/tlb_uv.c:tunables_read
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/user.c:snapshot_read
  - kernel/kprobes.c:read_enabled_file_bool
  - kernel/trace/ftrace.c:ftrace_profile_read
  - kernel/trace/trace.c:buffer_percent_read
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:trace_options_core_read
  - kernel/trace/trace.c:trace_options_read
  - kernel/trace/trace.c:tracing_read_dyn_info
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_set_trace_read
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:tracing_readme_read
  - kernel/trace/trace.c:tracing_cpumask_read
  - kernel/trace/trace_hwlat.c:hwlat_read
  - kernel/trace/trace_stack.c:stack_max_size_read
  - kernel/trace/trace_functions_graph.c:graph_depth_read
  - kernel/trace/blktrace.c:blk_dropped_read
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - fs/libfs.c:simple_attr_read
  - fs/libfs.c:simple_transaction_read
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:auxv_read
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/configfs/file.c:configfs_read_file
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/debugfs/file.c:u32_array_read
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/pstore/inode.c:pstore_file_read
  - fs/efivarfs/file.c:efivarfs_file_read
  - ipc/mqueue.c:mqueue_read_file
  - security/inode.c:lsm_read
  - security/selinux/selinuxfs.c:sel_read_policycap
  - security/selinux/selinuxfs.c:sel_read_perm
  - security/selinux/selinuxfs.c:sel_read_class
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_read_checkreqprot
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_read_mls
  - security/selinux/selinuxfs.c:sel_read_policyvers
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/selinuxfs.c:sel_read_enforce
  - security/apparmor/apparmorfs.c:attr_read
  - security/apparmor/apparmorfs.c:rawdata_read
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/safesetid/securityfs.c:safesetid_file_read
  - security/lockdown/lockdown.c:lockdown_read
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
  - drivers/regulator/core.c:constraint_flags_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_read_file
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/usb/host/uhci-hcd.c:uhci_debug_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_name_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read
```
**Symbols:**

```
ffffffff8130c390-ffffffff8130c439: simple_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t simple_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81345bc0)
Location: fs/libfs.c:715
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:tlbflush_read_file
  - arch/x86/mm/pkeys.c:init_pkru_read_file
  - arch/x86/platform/uv/tlb_uv.c:tunables_read
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/user.c:snapshot_read
  - kernel/kprobes.c:read_enabled_file_bool
  - kernel/trace/ftrace.c:ftrace_profile_read
  - kernel/trace/trace.c:buffer_percent_read
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:trace_options_core_read
  - kernel/trace/trace.c:trace_options_read
  - kernel/trace/trace.c:tracing_read_dyn_info
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_max_lat_read
  - kernel/trace/trace.c:tracing_thresh_read
  - kernel/trace/trace.c:tracing_set_trace_read
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:tracing_readme_read
  - kernel/trace/trace.c:tracing_cpumask_read
  - kernel/trace/trace_hwlat.c:hwlat_read
  - kernel/trace/trace_stack.c:stack_max_size_read
  - kernel/trace/trace_functions_graph.c:graph_depth_read
  - kernel/trace/blktrace.c:blk_dropped_read
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - fs/libfs.c:simple_attr_read
  - fs/libfs.c:simple_transaction_read
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:auxv_read
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/configfs/file.c:configfs_read_file
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/debugfs/file.c:u32_array_read
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/pstore/inode.c:pstore_file_read
  - fs/efivarfs/file.c:efivarfs_file_read
  - ipc/mqueue.c:mqueue_read_file
  - security/inode.c:lsm_read
  - security/selinux/selinuxfs.c:sel_read_policycap
  - security/selinux/selinuxfs.c:sel_read_perm
  - security/selinux/selinuxfs.c:sel_read_class
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_read_sidtab_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_read_checkreqprot
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_read_mls
  - security/selinux/selinuxfs.c:sel_read_policyvers
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/selinuxfs.c:sel_read_enforce
  - security/apparmor/apparmorfs.c:rawdata_read
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/safesetid/securityfs.c:safesetid_file_read
  - security/lockdown/lockdown.c:lockdown_read
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
  - drivers/regulator/core.c:constraint_flags_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_read_file
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/usb/host/uhci-hcd.c:uhci_debug_read
  - drivers/opp/debugfs.c:bw_name_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_name_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read
```
**Symbols:**

```
ffffffff81345bc0-ffffffff81345c70: simple_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t simple_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81352070)
Location: fs/libfs.c:717
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:tlbflush_read_file
  - arch/x86/mm/pkeys.c:init_pkru_read_file
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/user.c:snapshot_read
  - kernel/kprobes.c:read_enabled_file_bool
  - kernel/trace/ftrace.c:ftrace_profile_read
  - kernel/trace/trace.c:buffer_percent_read
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:trace_options_core_read
  - kernel/trace/trace.c:trace_options_read
  - kernel/trace/trace.c:tracing_read_dyn_info
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_max_lat_read
  - kernel/trace/trace.c:tracing_thresh_read
  - kernel/trace/trace.c:tracing_set_trace_read
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:tracing_readme_read
  - kernel/trace/trace.c:tracing_cpumask_read
  - kernel/trace/trace_hwlat.c:hwlat_read
  - kernel/trace/trace_stack.c:stack_max_size_read
  - kernel/trace/trace_functions_graph.c:graph_depth_read
  - kernel/trace/blktrace.c:blk_dropped_read
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - fs/libfs.c:simple_attr_read
  - fs/libfs.c:simple_transaction_read
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:auxv_read
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/configfs/file.c:configfs_read_file
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/debugfs/file.c:u32_array_read
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/pstore/inode.c:pstore_file_read
  - fs/efivarfs/file.c:efivarfs_file_read
  - ipc/mqueue.c:mqueue_read_file
  - security/inode.c:lsm_read
  - security/selinux/selinuxfs.c:sel_read_policycap
  - security/selinux/selinuxfs.c:sel_read_perm
  - security/selinux/selinuxfs.c:sel_read_class
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_read_sidtab_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_read_checkreqprot
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_read_mls
  - security/selinux/selinuxfs.c:sel_read_policyvers
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/selinuxfs.c:sel_read_enforce
  - security/apparmor/apparmorfs.c:rawdata_read
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/lockdown/lockdown.c:lockdown_read
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
  - drivers/regulator/core.c:constraint_flags_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_read_file
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/usb/host/uhci-hcd.c:uhci_debug_read
  - drivers/opp/debugfs.c:bw_name_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_name_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_coredump_read
```
**Symbols:**

```
ffffffff81352070-ffffffff81352120: simple_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t simple_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81358ff0)
Location: fs/libfs.c:720
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:tlbflush_read_file
  - arch/x86/mm/pkeys.c:init_pkru_read_file
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/user.c:snapshot_read
  - kernel/kprobes.c:read_enabled_file_bool
  - kernel/trace/ftrace.c:ftrace_profile_read
  - kernel/trace/trace.c:buffer_percent_read
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:trace_options_core_read
  - kernel/trace/trace.c:trace_options_read
  - kernel/trace/trace.c:tracing_read_dyn_info
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_max_lat_read
  - kernel/trace/trace.c:tracing_thresh_read
  - kernel/trace/trace.c:tracing_set_trace_read
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:tracing_readme_read
  - kernel/trace/trace.c:tracing_cpumask_read
  - kernel/trace/trace_hwlat.c:hwlat_read
  - kernel/trace/trace_stack.c:stack_max_size_read
  - kernel/trace/trace_functions_graph.c:graph_depth_read
  - kernel/trace/blktrace.c:blk_dropped_read
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - fs/libfs.c:simple_attr_read
  - fs/libfs.c:simple_transaction_read
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:auxv_read
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/configfs/file.c:configfs_read_file
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/debugfs/file.c:u32_array_read
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_read_file_str
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/pstore/inode.c:pstore_file_read
  - fs/efivarfs/file.c:efivarfs_file_read
  - ipc/mqueue.c:mqueue_read_file
  - security/inode.c:lsm_read
  - security/selinux/selinuxfs.c:sel_read_policycap
  - security/selinux/selinuxfs.c:sel_read_perm
  - security/selinux/selinuxfs.c:sel_read_class
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_read_sidtab_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_read_checkreqprot
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_read_mls
  - security/selinux/selinuxfs.c:sel_read_policyvers
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/selinuxfs.c:sel_read_enforce
  - security/apparmor/apparmorfs.c:rawdata_read
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/lockdown/lockdown.c:lockdown_read
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
  - drivers/regulator/core.c:constraint_flags_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_read_file
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/usb/host/uhci-hcd.c:uhci_debug_read
  - drivers/opp/debugfs.c:bw_name_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_name_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_coredump_read
```
**Symbols:**

```
ffffffff81358ff0-ffffffff81359099: simple_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t simple_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813a7390)
Location: fs/libfs.c:729
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:tlbflush_read_file
  - arch/x86/mm/pkeys.c:init_pkru_read_file
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/user.c:snapshot_read
  - kernel/kprobes.c:read_enabled_file_bool
  - kernel/trace/ftrace.c:ftrace_profile_read
  - kernel/trace/trace.c:buffer_percent_read
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:trace_options_core_read
  - kernel/trace/trace.c:trace_options_read
  - kernel/trace/trace.c:tracing_read_dyn_info
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:trace_min_max_read
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_max_lat_read
  - kernel/trace/trace.c:tracing_thresh_read
  - kernel/trace/trace.c:tracing_set_trace_read
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:tracing_readme_read
  - kernel/trace/trace.c:tracing_cpumask_read
  - kernel/trace/trace_stack.c:stack_max_size_read
  - kernel/trace/trace_functions_graph.c:graph_depth_read
  - kernel/trace/blktrace.c:blk_dropped_read
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - fs/libfs.c:simple_attr_read
  - fs/libfs.c:simple_transaction_read
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:auxv_read
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/debugfs/file.c:u32_array_read
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_read_file_str
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/pstore/inode.c:pstore_file_read
  - fs/efivarfs/file.c:efivarfs_file_read
  - ipc/mqueue.c:mqueue_read_file
  - security/inode.c:lsm_read
  - security/selinux/selinuxfs.c:sel_read_policycap
  - security/selinux/selinuxfs.c:sel_read_perm
  - security/selinux/selinuxfs.c:sel_read_class
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_read_sidtab_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_read_checkreqprot
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_read_mls
  - security/selinux/selinuxfs.c:sel_read_policyvers
  - security/selinux/selinuxfs.c:sel_read_handle_status
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/selinuxfs.c:sel_read_enforce
  - security/apparmor/apparmorfs.c:rawdata_read
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/lockdown/lockdown.c:lockdown_read
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
  - drivers/regulator/core.c:constraint_flags_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_read_file
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/usb/host/uhci-hcd.c:uhci_debug_read
  - drivers/opp/debugfs.c:bw_name_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_name_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_coredump_read
```
**Symbols:**

```
ffffffff813a7390-ffffffff813a7439: simple_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t simple_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8142b1f0)
Location: fs/libfs.c:756
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:tlbflush_read_file
  - arch/x86/mm/pkeys.c:init_pkru_read_file
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/user.c:snapshot_read
  - kernel/kprobes.c:read_enabled_file_bool
  - kernel/trace/ftrace.c:ftrace_profile_read
  - kernel/trace/trace.c:buffer_percent_read
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:trace_options_core_read
  - kernel/trace/trace.c:trace_options_read
  - kernel/trace/trace.c:tracing_read_dyn_info
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:trace_min_max_read
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_max_lat_read
  - kernel/trace/trace.c:tracing_thresh_read
  - kernel/trace/trace.c:tracing_set_trace_read
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:tracing_readme_read
  - kernel/trace/trace.c:tracing_cpumask_read
  - kernel/trace/trace_stack.c:stack_max_size_read
  - kernel/trace/trace_functions_graph.c:graph_depth_read
  - kernel/trace/blktrace.c:blk_dropped_read
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - fs/libfs.c:simple_attr_read
  - fs/libfs.c:simple_transaction_read
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:auxv_read
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/debugfs/file.c:u32_array_read
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_read_file_str
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/pstore/inode.c:pstore_file_read
  - fs/efivarfs/file.c:efivarfs_file_read
  - ipc/mqueue.c:mqueue_read_file
  - security/inode.c:lsm_read
  - security/selinux/selinuxfs.c:sel_read_policycap
  - security/selinux/selinuxfs.c:sel_read_perm
  - security/selinux/selinuxfs.c:sel_read_class
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_read_sidtab_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_read_checkreqprot
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_read_mls
  - security/selinux/selinuxfs.c:sel_read_policyvers
  - security/selinux/selinuxfs.c:sel_read_handle_status
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/selinuxfs.c:sel_read_enforce
  - security/smack/smackfs.c:smk_read_ptrace
  - security/smack/smackfs.c:smk_read_logging
  - security/smack/smackfs.c:smk_read_mapped
  - security/smack/smackfs.c:smk_read_direct
  - security/smack/smackfs.c:smk_read_doi
  - security/apparmor/apparmorfs.c:rawdata_read
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/lockdown/lockdown.c:lockdown_read
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
  - security/integrity/evm/evm_secfs.c:evm_read_key
  - drivers/regulator/core.c:constraint_flags_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_read_file
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/usb/host/uhci-hcd.c:uhci_debug_read
  - drivers/opp/debugfs.c:bw_name_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_name_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_coredump_read
```
**Symbols:**

```
ffffffff8142b1f0-ffffffff8142b2b2: simple_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t simple_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814b83e0)
Location: fs/libfs.c:757
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:tlbflush_read_file
  - arch/x86/mm/pkeys.c:init_pkru_read_file
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/user.c:snapshot_read
  - kernel/kprobes.c:read_enabled_file_bool
  - kernel/trace/ftrace.c:ftrace_profile_read
  - kernel/trace/trace.c:buffer_percent_read
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:trace_options_core_read
  - kernel/trace/trace.c:trace_options_read
  - kernel/trace/trace.c:tracing_read_dyn_info
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:trace_min_max_read
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_max_lat_read
  - kernel/trace/trace.c:tracing_thresh_read
  - kernel/trace/trace.c:tracing_set_trace_read
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:tracing_readme_read
  - kernel/trace/trace.c:tracing_cpumask_read
  - kernel/trace/trace_stack.c:stack_max_size_read
  - kernel/trace/trace_functions_graph.c:graph_depth_read
  - kernel/trace/blktrace.c:blk_dropped_read
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/rv/rv.c:monitoring_on_read_data
  - kernel/trace/rv/rv.c:monitor_desc_read_data
  - kernel/trace/rv/rv.c:monitor_enable_read_data
  - kernel/trace/rv/rv_reactors.c:reacting_on_read_data
  - fs/libfs.c:simple_attr_read
  - fs/libfs.c:simple_transaction_read
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:auxv_read
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/debugfs/file.c:u32_array_read
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_read_file_str
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/pstore/inode.c:pstore_file_read
  - fs/efivarfs/file.c:efivarfs_file_read
  - ipc/mqueue.c:mqueue_read_file
  - security/inode.c:lsm_read
  - security/selinux/selinuxfs.c:sel_read_policycap
  - security/selinux/selinuxfs.c:sel_read_perm
  - security/selinux/selinuxfs.c:sel_read_class
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_read_sidtab_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_read_checkreqprot
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_read_mls
  - security/selinux/selinuxfs.c:sel_read_policyvers
  - security/selinux/selinuxfs.c:sel_read_handle_status
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/selinuxfs.c:sel_read_enforce
  - security/smack/smackfs.c:smk_read_ptrace
  - security/smack/smackfs.c:smk_read_logging
  - security/smack/smackfs.c:smk_read_mapped
  - security/smack/smackfs.c:smk_read_direct
  - security/smack/smackfs.c:smk_read_doi
  - security/apparmor/apparmorfs.c:rawdata_read
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/lockdown/lockdown.c:lockdown_read
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
  - security/integrity/evm/evm_secfs.c:evm_read_key
  - drivers/regulator/core.c:constraint_flags_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_read_file
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/usb/host/uhci-hcd.c:uhci_debug_read
  - drivers/opp/debugfs.c:bw_name_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_name_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_coredump_read
```
**Symbols:**

```
ffffffff814b83e0-ffffffff814b84a2: simple_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t simple_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814ed5f0)
Location: fs/libfs.c:752
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:tlbflush_read_file
  - arch/x86/mm/pkeys.c:init_pkru_read_file
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/user.c:snapshot_read
  - kernel/kprobes.c:read_enabled_file_bool
  - kernel/trace/ftrace.c:ftrace_profile_read
  - kernel/trace/trace.c:buffer_percent_read
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:trace_options_core_read
  - kernel/trace/trace.c:trace_options_read
  - kernel/trace/trace.c:tracing_read_dyn_info
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:trace_min_max_read
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_max_lat_read
  - kernel/trace/trace.c:tracing_thresh_read
  - kernel/trace/trace.c:tracing_set_trace_read
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:tracing_readme_read
  - kernel/trace/trace.c:tracing_cpumask_read
  - kernel/trace/trace_osnoise.c:osnoise_cpus_read
  - kernel/trace/trace_stack.c:stack_max_size_read
  - kernel/trace/trace_functions_graph.c:graph_depth_read
  - kernel/trace/blktrace.c:blk_dropped_read
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/rv/rv.c:monitoring_on_read_data
  - kernel/trace/rv/rv.c:monitor_desc_read_data
  - kernel/trace/rv/rv.c:monitor_enable_read_data
  - kernel/trace/rv/rv_reactors.c:reacting_on_read_data
  - fs/libfs.c:simple_attr_read
  - fs/libfs.c:simple_transaction_read
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:auxv_read
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/debugfs/file.c:u32_array_read
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_read_file_str
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/pstore/inode.c:pstore_file_read
  - fs/efivarfs/file.c:efivarfs_file_read
  - ipc/mqueue.c:mqueue_read_file
  - security/inode.c:lsm_read
  - security/selinux/selinuxfs.c:sel_read_policycap
  - security/selinux/selinuxfs.c:sel_read_perm
  - security/selinux/selinuxfs.c:sel_read_class
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_read_sidtab_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_read_checkreqprot
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_read_mls
  - security/selinux/selinuxfs.c:sel_read_policyvers
  - security/selinux/selinuxfs.c:sel_read_handle_status
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/selinuxfs.c:sel_read_enforce
  - security/smack/smackfs.c:smk_read_ptrace
  - security/smack/smackfs.c:smk_read_logging
  - security/smack/smackfs.c:smk_read_mapped
  - security/smack/smackfs.c:smk_read_direct
  - security/smack/smackfs.c:smk_read_doi
  - security/apparmor/apparmorfs.c:rawdata_read
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/lockdown/lockdown.c:lockdown_read
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
  - security/integrity/evm/evm_secfs.c:evm_read_key
  - drivers/regulator/core.c:constraint_flags_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_read_file
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/usb/host/uhci-hcd.c:uhci_debug_read
  - drivers/opp/debugfs.c:bw_name_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_name_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_coredump_read
```
**Symbols:**

```
ffffffff814ed5f0-ffffffff814ed6b2: simple_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t simple_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81521350)
Location: fs/libfs.c:1022
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:tlbflush_read_file
  - arch/x86/mm/pkeys.c:init_pkru_read_file
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/user.c:snapshot_read
  - kernel/kprobes.c:read_enabled_file_bool
  - kernel/trace/ftrace.c:ftrace_profile_read
  - kernel/trace/trace.c:buffer_subbuf_size_read
  - kernel/trace/trace.c:buffer_percent_read
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:trace_options_core_read
  - kernel/trace/trace.c:trace_options_read
  - kernel/trace/trace.c:tracing_read_dyn_info
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:trace_min_max_read
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_max_lat_read
  - kernel/trace/trace.c:tracing_thresh_read
  - kernel/trace/trace.c:tracing_set_trace_read
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:tracing_readme_read
  - kernel/trace/trace.c:tracing_cpumask_read
  - kernel/trace/trace_osnoise.c:osnoise_cpus_read
  - kernel/trace/trace_stack.c:stack_max_size_read
  - kernel/trace/trace_functions_graph.c:graph_depth_read
  - kernel/trace/blktrace.c:blk_dropped_read
  - kernel/trace/trace_events.c:show_header_page_file
  - kernel/trace/trace_events.c:subsystem_filter_read
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - kernel/trace/rv/rv.c:monitoring_on_read_data
  - kernel/trace/rv/rv.c:monitor_desc_read_data
  - kernel/trace/rv/rv.c:monitor_enable_read_data
  - kernel/trace/rv/rv_reactors.c:reacting_on_read_data
  - fs/libfs.c:simple_attr_read
  - fs/libfs.c:simple_transaction_read
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:auxv_read
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/debugfs/file.c:u32_array_read
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_read_file_str
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/pstore/inode.c:pstore_file_read
  - fs/efivarfs/file.c:efivarfs_file_read
  - ipc/mqueue.c:mqueue_read_file
  - security/inode.c:lsm_read
  - security/selinux/selinuxfs.c:sel_read_policycap
  - security/selinux/selinuxfs.c:sel_read_perm
  - security/selinux/selinuxfs.c:sel_read_class
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_read_sidtab_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_read_checkreqprot
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_read_mls
  - security/selinux/selinuxfs.c:sel_read_policyvers
  - security/selinux/selinuxfs.c:sel_read_handle_status
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/selinuxfs.c:sel_read_enforce
  - security/smack/smackfs.c:smk_read_ptrace
  - security/smack/smackfs.c:smk_read_logging
  - security/smack/smackfs.c:smk_read_mapped
  - security/smack/smackfs.c:smk_read_direct
  - security/smack/smackfs.c:smk_read_doi
  - security/apparmor/apparmorfs.c:rawdata_read
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/lockdown/lockdown.c:lockdown_read
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
  - security/integrity/evm/evm_secfs.c:evm_read_key
  - drivers/regulator/core.c:constraint_flags_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_read_file
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/usb/host/uhci-hcd.c:uhci_debug_read
  - drivers/opp/debugfs.c:bw_name_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_name_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_coredump_read
```
**Symbols:**

```
ffffffff81521350-ffffffff81521412: simple_read_from_buffer (STB_GLOBAL)
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
ssize_t simple_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffff8000103c1ab8)
Location: fs/libfs.c:646
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/kprobes.c:read_enabled_file_bool
  - kernel/trace/ftrace.c:ftrace_profile_read
  - kernel/trace/trace.c:buffer_percent_read
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:trace_options_core_read
  - kernel/trace/trace.c:trace_options_read
  - kernel/trace/trace.c:tracing_read_dyn_info
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_set_trace_read
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:tracing_readme_read
  - kernel/trace/trace.c:tracing_cpumask_read
  - kernel/trace/trace_hwlat.c:hwlat_read
  - kernel/trace/trace_stack.c:stack_max_size_read
  - kernel/trace/trace_functions_graph.c:graph_depth_read
  - kernel/trace/blktrace.c:blk_dropped_read
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - fs/libfs.c:simple_attr_read
  - fs/libfs.c:simple_transaction_read
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:auxv_read
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/configfs/file.c:configfs_read_file
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/debugfs/file.c:u32_array_read
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/pstore/inode.c:pstore_file_read
  - fs/efivarfs/file.c:efivarfs_file_read
  - ipc/mqueue.c:mqueue_read_file
  - security/inode.c:lsm_read
  - security/selinux/selinuxfs.c:sel_read_policycap
  - security/selinux/selinuxfs.c:sel_read_perm
  - security/selinux/selinuxfs.c:sel_read_class
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_read_checkreqprot
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_read_mls
  - security/selinux/selinuxfs.c:sel_read_policyvers
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/selinuxfs.c:sel_read_enforce
  - security/apparmor/apparmorfs.c:attr_read
  - security/apparmor/apparmorfs.c:rawdata_read
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/safesetid/securityfs.c:safesetid_file_read
  - security/lockdown/lockdown.c:lockdown_read
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
  - drivers/regulator/core.c:constraint_flags_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_read_file
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/usb/host/uhci-hcd.c:uhci_debug_read
  - drivers/mmc/core/block.c:mmc_ext_csd_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_name_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read
```
**Symbols:**

```
ffff8000103c1ab8-ffff8000103c1cc0: simple_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t simple_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c059e1d8)
Location: fs/libfs.c:646
Inline: False
Direct callers:
  - arch/arm/kernel/atags_proc.c:atags_read
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/user.c:snapshot_read
  - kernel/kprobes.c:read_enabled_file_bool
  - kernel/trace/ftrace.c:ftrace_profile_read
  - kernel/trace/trace.c:buffer_percent_read
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:trace_options_core_read
  - kernel/trace/trace.c:trace_options_read
  - kernel/trace/trace.c:tracing_read_dyn_info
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_nsecs_read
  - kernel/trace/trace.c:tracing_set_trace_read
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:tracing_readme_read
  - kernel/trace/trace.c:tracing_cpumask_read
  - kernel/trace/trace_hwlat.c:hwlat_read
  - kernel/trace/trace_stack.c:stack_max_size_read
  - kernel/trace/trace_functions_graph.c:graph_depth_read
  - kernel/trace/blktrace.c:blk_dropped_read
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - fs/libfs.c:simple_attr_read
  - fs/libfs.c:simple_transaction_read
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:auxv_read
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/configfs/file.c:configfs_read_file
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/debugfs/file.c:u32_array_read
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/pstore/inode.c:pstore_file_read
  - fs/efivarfs/file.c:efivarfs_file_read
  - ipc/mqueue.c:mqueue_read_file
  - security/inode.c:lsm_read
  - security/selinux/selinuxfs.c:sel_read_policycap
  - security/selinux/selinuxfs.c:sel_read_perm
  - security/selinux/selinuxfs.c:sel_read_class
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_read_checkreqprot
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_read_mls
  - security/selinux/selinuxfs.c:sel_read_policyvers
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/selinuxfs.c:sel_read_enforce
  - security/apparmor/apparmorfs.c:attr_read
  - security/apparmor/apparmorfs.c:rawdata_read
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/safesetid/securityfs.c:safesetid_file_read
  - security/lockdown/lockdown.c:lockdown_read
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
  - drivers/regulator/core.c:constraint_flags_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_read_file
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/usb/host/uhci-hcd.c:uhci_debug_read
  - drivers/mmc/core/block.c:mmc_ext_csd_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_name_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read
  - sound/soc/soc-dapm.c:dapm_bias_read_file
  - sound/soc/soc-dapm.c:dapm_widget_power_read_file
  - sound/soc/soc-pcm.c:dpcm_state_read_file
  - sound/soc/fsl/imx-audmux.c:audmux_read_file
```
**Symbols:**

```
c059e1d8-c059e340: simple_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t simple_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c0000000004c0e40)
Location: fs/libfs.c:646
Inline: False
Direct callers:
  - arch/powerpc/kernel/proc_powerpc.c:page_map_read
  - arch/powerpc/kernel/eeh.c:eeh_debugfs_dev_usage
  - arch/powerpc/platforms/powernv/memtrace.c:memtrace_read
  - arch/powerpc/platforms/pseries/lpar.c:vpa_file_read
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/kprobes.c:read_enabled_file_bool
  - kernel/trace/ftrace.c:ftrace_profile_read
  - kernel/trace/trace.c:buffer_percent_read
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:trace_options_core_read
  - kernel/trace/trace.c:trace_options_core_read
  - kernel/trace/trace.c:trace_options_read
  - kernel/trace/trace.c:trace_options_read
  - kernel/trace/trace.c:tracing_read_dyn_info
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_set_trace_read
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:tracing_readme_read
  - kernel/trace/trace.c:tracing_cpumask_read
  - kernel/trace/trace_hwlat.c:hwlat_read
  - kernel/trace/trace_stack.c:stack_max_size_read
  - kernel/trace/trace_functions_graph.c:graph_depth_read
  - kernel/trace/blktrace.c:blk_dropped_read
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - fs/libfs.c:simple_attr_read
  - fs/libfs.c:simple_transaction_read
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:auxv_read
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/configfs/file.c:configfs_read_file
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/debugfs/file.c:u32_array_read
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/pstore/inode.c:pstore_file_read
  - ipc/mqueue.c:mqueue_read_file
  - security/inode.c:lsm_read
  - security/selinux/selinuxfs.c:sel_read_policycap
  - security/selinux/selinuxfs.c:sel_read_perm
  - security/selinux/selinuxfs.c:sel_read_class
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_read_checkreqprot
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_read_mls
  - security/selinux/selinuxfs.c:sel_read_policyvers
  - security/selinux/selinuxfs.c:sel_read_handle_status
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/selinuxfs.c:sel_read_enforce
  - security/apparmor/apparmorfs.c:attr_read
  - security/apparmor/apparmorfs.c:rawdata_read
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/safesetid/securityfs.c:safesetid_file_read
  - security/lockdown/lockdown.c:lockdown_read
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
  - drivers/regulator/core.c:constraint_flags_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_read_file
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/usb/host/uhci-hcd.c:uhci_debug_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_name_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read
```
**Symbols:**

```
c0000000004c0e40-c0000000004c0f5c: simple_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t simple_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffe000281f0e)
Location: fs/libfs.c:646
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/trace/ftrace.c:ftrace_profile_read
  - kernel/trace/trace.c:buffer_percent_read
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:trace_options_core_read
  - kernel/trace/trace.c:trace_options_read
  - kernel/trace/trace.c:tracing_read_dyn_info
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_set_trace_read
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:tracing_readme_read
  - kernel/trace/trace.c:tracing_cpumask_read
  - kernel/trace/trace_hwlat.c:hwlat_read
  - kernel/trace/trace_stack.c:stack_max_size_read
  - kernel/trace/trace_functions_graph.c:graph_depth_read
  - kernel/trace/blktrace.c:blk_dropped_read
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - fs/libfs.c:simple_attr_read
  - fs/libfs.c:simple_transaction_read
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:auxv_read
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/configfs/file.c:configfs_read_file
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/debugfs/file.c:u32_array_read
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/pstore/inode.c:pstore_file_read
  - ipc/mqueue.c:mqueue_read_file
  - security/inode.c:lsm_read
  - security/selinux/selinuxfs.c:sel_read_policycap
  - security/selinux/selinuxfs.c:sel_read_perm
  - security/selinux/selinuxfs.c:sel_read_class
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_read_checkreqprot
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_read_mls
  - security/selinux/selinuxfs.c:sel_read_policyvers
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/selinuxfs.c:sel_read_enforce
  - security/apparmor/apparmorfs.c:attr_read
  - security/apparmor/apparmorfs.c:rawdata_read
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/safesetid/securityfs.c:safesetid_file_read
  - security/lockdown/lockdown.c:lockdown_read
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
  - drivers/regulator/core.c:constraint_flags_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_read_file
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/usb/host/uhci-hcd.c:uhci_debug_read
  - drivers/mmc/core/block.c:mmc_ext_csd_read
```
**Symbols:**

```
ffffffe000281f0e-ffffffe000281fac: simple_read_from_buffer (STB_GLOBAL)
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
ssize_t simple_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81304970)
Location: fs/libfs.c:646
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:tlbflush_read_file
  - arch/x86/mm/pkeys.c:init_pkru_read_file
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/user.c:snapshot_read
  - kernel/kprobes.c:read_enabled_file_bool
  - kernel/trace/ftrace.c:ftrace_profile_read
  - kernel/trace/trace.c:buffer_percent_read
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:trace_options_core_read
  - kernel/trace/trace.c:trace_options_read
  - kernel/trace/trace.c:tracing_read_dyn_info
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_set_trace_read
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:tracing_readme_read
  - kernel/trace/trace.c:tracing_cpumask_read
  - kernel/trace/trace_hwlat.c:hwlat_read
  - kernel/trace/trace_stack.c:stack_max_size_read
  - kernel/trace/trace_functions_graph.c:graph_depth_read
  - kernel/trace/blktrace.c:blk_dropped_read
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - fs/libfs.c:simple_attr_read
  - fs/libfs.c:simple_transaction_read
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:auxv_read
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/configfs/file.c:configfs_read_file
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/debugfs/file.c:u32_array_read
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/pstore/inode.c:pstore_file_read
  - fs/efivarfs/file.c:efivarfs_file_read
  - ipc/mqueue.c:mqueue_read_file
  - security/inode.c:lsm_read
  - security/selinux/selinuxfs.c:sel_read_policycap
  - security/selinux/selinuxfs.c:sel_read_perm
  - security/selinux/selinuxfs.c:sel_read_class
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_read_checkreqprot
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_read_mls
  - security/selinux/selinuxfs.c:sel_read_policyvers
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/selinuxfs.c:sel_read_enforce
  - security/apparmor/apparmorfs.c:attr_read
  - security/apparmor/apparmorfs.c:rawdata_read
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/safesetid/securityfs.c:safesetid_file_read
  - security/lockdown/lockdown.c:lockdown_read
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
  - drivers/regulator/core.c:constraint_flags_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/usb/host/uhci-hcd.c:uhci_debug_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_name_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read
```
**Symbols:**

```
ffffffff81304970-ffffffff81304a19: simple_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t simple_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812f5590)
Location: fs/libfs.c:646
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:tlbflush_read_file
  - arch/x86/mm/pkeys.c:init_pkru_read_file
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/user.c:snapshot_read
  - kernel/kprobes.c:read_enabled_file_bool
  - kernel/trace/ftrace.c:ftrace_profile_read
  - kernel/trace/trace.c:buffer_percent_read
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:trace_options_core_read
  - kernel/trace/trace.c:trace_options_read
  - kernel/trace/trace.c:tracing_read_dyn_info
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_set_trace_read
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:tracing_readme_read
  - kernel/trace/trace.c:tracing_cpumask_read
  - kernel/trace/trace_hwlat.c:hwlat_read
  - kernel/trace/trace_stack.c:stack_max_size_read
  - kernel/trace/trace_functions_graph.c:graph_depth_read
  - kernel/trace/blktrace.c:blk_dropped_read
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - fs/libfs.c:simple_attr_read
  - fs/libfs.c:simple_transaction_read
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:auxv_read
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/configfs/file.c:configfs_read_file
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/debugfs/file.c:u32_array_read
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/pstore/inode.c:pstore_file_read
  - fs/efivarfs/file.c:efivarfs_file_read
  - ipc/mqueue.c:mqueue_read_file
  - security/inode.c:lsm_read
  - security/selinux/selinuxfs.c:sel_read_policycap
  - security/selinux/selinuxfs.c:sel_read_perm
  - security/selinux/selinuxfs.c:sel_read_class
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_read_checkreqprot
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_read_mls
  - security/selinux/selinuxfs.c:sel_read_policyvers
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/selinuxfs.c:sel_read_enforce
  - security/apparmor/apparmorfs.c:attr_read
  - security/apparmor/apparmorfs.c:rawdata_read
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/safesetid/securityfs.c:safesetid_file_read
  - security/lockdown/lockdown.c:lockdown_read
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
  - drivers/regulator/core.c:constraint_flags_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file
```
**Symbols:**

```
ffffffff812f5590-ffffffff812f5639: simple_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t simple_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81302760)
Location: fs/libfs.c:646
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:tlbflush_read_file
  - arch/x86/mm/pkeys.c:init_pkru_read_file
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/user.c:snapshot_read
  - kernel/kprobes.c:read_enabled_file_bool
  - kernel/trace/ftrace.c:ftrace_profile_read
  - kernel/trace/trace.c:buffer_percent_read
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:trace_options_core_read
  - kernel/trace/trace.c:trace_options_read
  - kernel/trace/trace.c:tracing_read_dyn_info
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_set_trace_read
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:tracing_readme_read
  - kernel/trace/trace.c:tracing_cpumask_read
  - kernel/trace/trace_hwlat.c:hwlat_read
  - kernel/trace/trace_stack.c:stack_max_size_read
  - kernel/trace/trace_functions_graph.c:graph_depth_read
  - kernel/trace/blktrace.c:blk_dropped_read
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - fs/libfs.c:simple_attr_read
  - fs/libfs.c:simple_transaction_read
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:auxv_read
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/configfs/file.c:configfs_read_file
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/debugfs/file.c:u32_array_read
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/pstore/inode.c:pstore_file_read
  - fs/efivarfs/file.c:efivarfs_file_read
  - ipc/mqueue.c:mqueue_read_file
  - security/inode.c:lsm_read
  - security/selinux/selinuxfs.c:sel_read_policycap
  - security/selinux/selinuxfs.c:sel_read_perm
  - security/selinux/selinuxfs.c:sel_read_class
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_read_checkreqprot
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_read_mls
  - security/selinux/selinuxfs.c:sel_read_policyvers
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/selinuxfs.c:sel_read_enforce
  - security/apparmor/apparmorfs.c:attr_read
  - security/apparmor/apparmorfs.c:rawdata_read
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/safesetid/securityfs.c:safesetid_file_read
  - security/lockdown/lockdown.c:lockdown_read
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
  - drivers/regulator/core.c:constraint_flags_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_read_file
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/usb/host/uhci-hcd.c:uhci_debug_read
```
**Symbols:**

```
ffffffff81302760-ffffffff81302809: simple_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t simple_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81314470)
Location: fs/libfs.c:646
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:tlbflush_read_file
  - arch/x86/mm/pkeys.c:init_pkru_read_file
  - arch/x86/platform/uv/tlb_uv.c:tunables_read
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/user.c:snapshot_read
  - kernel/kprobes.c:read_enabled_file_bool
  - kernel/trace/ftrace.c:ftrace_profile_read
  - kernel/trace/trace.c:buffer_percent_read
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:trace_options_core_read
  - kernel/trace/trace.c:trace_options_read
  - kernel/trace/trace.c:tracing_read_dyn_info
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:tracing_set_trace_read
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:tracing_readme_read
  - kernel/trace/trace.c:tracing_cpumask_read
  - kernel/trace/trace_hwlat.c:hwlat_read
  - kernel/trace/trace_stack.c:stack_max_size_read
  - kernel/trace/trace_functions_graph.c:graph_depth_read
  - kernel/trace/blktrace.c:blk_dropped_read
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:event_enable_read
  - fs/libfs.c:simple_attr_read
  - fs/libfs.c:simple_transaction_read
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:auxv_read
  - fs/configfs/file.c:configfs_read_bin_file
  - fs/configfs/file.c:configfs_read_file
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/debugfs/file.c:u32_array_read
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/pstore/inode.c:pstore_file_read
  - fs/efivarfs/file.c:efivarfs_file_read
  - ipc/mqueue.c:mqueue_read_file
  - security/inode.c:lsm_read
  - security/selinux/selinuxfs.c:sel_read_policycap
  - security/selinux/selinuxfs.c:sel_read_perm
  - security/selinux/selinuxfs.c:sel_read_class
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_read_checkreqprot
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_read_mls
  - security/selinux/selinuxfs.c:sel_read_policyvers
  - security/selinux/selinuxfs.c:sel_read_handle_unknown
  - security/selinux/selinuxfs.c:sel_read_enforce
  - security/apparmor/apparmorfs.c:attr_read
  - security/apparmor/apparmorfs.c:rawdata_read
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/safesetid/securityfs.c:safesetid_file_read
  - security/lockdown/lockdown.c:lockdown_read
  - security/integrity/ima/ima_fs.c:ima_show_measurements_count
  - security/integrity/ima/ima_fs.c:ima_show_htable_violations
  - drivers/regulator/core.c:constraint_flags_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_read_file
  - drivers/usb/host/ehci-hcd.c:debug_output
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/usb/host/uhci-hcd.c:uhci_debug_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_name_read
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read
```
**Symbols:**

```
ffffffff81314470-ffffffff81314519: simple_read_from_buffer (STB_GLOBAL)
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
