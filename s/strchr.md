# Function: <code>strchr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *strchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff813f19c0)
Location: lib/string.c:369
Inline: False
Direct callers:
  - init/do_mounts.c:name_to_dev_t
  - init/do_mounts.c:mount_block_root
  - init/do_mounts_md.c:raid_setup
  - init/do_mounts_md.c:md_setup_drive
  - arch/x86/xen/platform-pci-unplug.c:parse_xen_emul_unplug
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/mcheck/mce.c:set_trigger
  - arch/x86/kernel/acpi/sleep.c:acpi_sleep_setup
  - arch/x86/kernel/hpet.c:hpet_setup
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/reboot.c:reboot_setup
  - kernel/printk/printk.c:console_setup
  - kernel/module.c:get_ksymbol
  - kernel/module.c:module_kallsyms_lookup_name
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_main.c:kdbgetenv
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_kprobe.c:__register_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_probes_write
  - kernel/trace/trace_probe.c:traceprobe_probes_write
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - fs/filesystems.c:get_fs_type
  - fs/namespace.c:do_mount
  - fs/seq_file.c:mangle_path
  - fs/binfmt_script.c:load_script
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/crypto_fname.c:ext4_fname_setup_filename
  - security/keys/user_defined.c:logon_vet_description
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_read_token
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/lib.c:aa_split_fqname
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/kobject.c:kobject_set_name_vargs
  - lib/parser.c:match_token
  - lib/string_helpers.c:string_escape_mem
  - lib/dynamic_debug.c:ddebug_exec_query
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/base/platform.c:driver_override_store
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
  - drivers/usb/host/uhci-hcd.c:lprintk
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/i2c/i2c-core.c:i2c_sysfs_new_device
  - drivers/power/power_supply_sysfs.c:power_supply_uevent
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-stats.c:dm_stats_message
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:register_netdevice
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
```
**Symbols:**

```
ffffffff813f19c0-ffffffff813f19ec: strchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *strchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81438380)
Location: lib/string.c:369
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:name_to_dev_t
  - init/do_mounts_md.c:raid_setup
  - init/do_mounts_md.c:md_setup_drive
  - arch/x86/xen/platform-pci-unplug.c:parse_xen_emul_unplug
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/mcheck/mce.c:set_trigger
  - arch/x86/kernel/acpi/sleep.c:acpi_sleep_setup
  - arch/x86/kernel/hpet.c:hpet_setup
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/reboot.c:reboot_setup
  - kernel/printk/printk.c:console_setup
  - kernel/module.c:module_kallsyms_lookup_name
  - kernel/module.c:get_ksymbol
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdbgetenv
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:__register_trace_kprobe
  - kernel/trace/trace_probe.c:traceprobe_probes_write
  - kernel/trace/trace_probe.c:traceprobe_probes_write
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/bpf/inode.c:bpf_lookup
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - fs/filesystems.c:get_fs_type
  - fs/namespace.c:do_mount
  - fs/seq_file.c:mangle_path
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/binfmt_script.c:load_script
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:set_qf_name
  - security/keys/user_defined.c:logon_vet_description
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_read_token
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/lib.c:aa_split_fqname
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/kobject.c:kobject_set_name_vargs
  - lib/parser.c:match_token
  - lib/kasprintf.c:kvasprintf_const
  - lib/string_helpers.c:string_escape_mem
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/base/platform.c:driver_override_store
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
  - drivers/usb/host/uhci-hcd.c:lprintk
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/i2c/i2c-core.c:i2c_sysfs_new_device
  - drivers/power/power_supply_sysfs.c:power_supply_uevent
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-stats.c:dm_stats_message
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
```
**Symbols:**

```
ffffffff81438380-ffffffff814383ac: strchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *strchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81455370)
Location: lib/string.c:369
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:name_to_dev_t
  - init/do_mounts_md.c:raid_setup
  - init/do_mounts_md.c:md_setup_drive
  - arch/x86/xen/platform-pci-unplug.c:parse_xen_emul_unplug
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/mcheck/mce.c:set_trigger
  - arch/x86/kernel/acpi/sleep.c:acpi_sleep_setup
  - arch/x86/kernel/hpet.c:hpet_setup
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/reboot.c:reboot_setup
  - kernel/printk/printk.c:console_setup
  - kernel/module.c:module_kallsyms_lookup_name
  - kernel/module.c:get_ksymbol
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdbgetenv
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_parse_regex
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:__register_trace_kprobe
  - kernel/trace/trace_probe.c:traceprobe_probes_write
  - kernel/trace/trace_probe.c:traceprobe_probes_write
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/bpf/inode.c:bpf_lookup
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - fs/filesystems.c:get_fs_type
  - fs/namespace.c:do_mount
  - fs/seq_file.c:mangle_path
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/binfmt_script.c:load_script
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:set_qf_name
  - security/keys/user_defined.c:logon_vet_description
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_read_token
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/lib.c:aa_split_fqname
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/kobject.c:kobject_set_name_vargs
  - lib/parser.c:match_token
  - lib/kasprintf.c:kvasprintf_const
  - lib/string_helpers.c:string_escape_mem
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/base/platform.c:driver_override_store
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
  - drivers/usb/host/uhci-hcd.c:lprintk
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/i2c/i2c-core.c:i2c_sysfs_new_device
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-stats.c:dm_stats_message
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
```
**Symbols:**

```
ffffffff81455370-ffffffff8145539c: strchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *strchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff818f6e30)
Location: lib/string.c:369
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts_md.c:raid_setup
  - init/do_mounts_md.c:md_setup_drive
  - arch/x86/xen/platform-pci-unplug.c:parse_xen_emul_unplug
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:set_trigger
  - arch/x86/kernel/acpi/sleep.c:acpi_sleep_setup
  - arch/x86/kernel/hpet.c:hpet_setup
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/reboot.c:reboot_setup
  - kernel/printk/printk.c:console_setup
  - kernel/module.c:get_ksymbol
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdbgetenv
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_parse_regex
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_probe.c:traceprobe_probes_write
  - kernel/trace/trace_probe.c:traceprobe_probes_write
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/bpf/inode.c:bpf_lookup
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:register_filesystem
  - fs/namespace.c:do_mount
  - fs/seq_file.c:mangle_path
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/binfmt_script.c:load_script
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:set_qf_name
  - security/keys/user_defined.c:logon_vet_description
  - security/security.c:security_setprocattr
  - security/security.c:security_module_enable
  - security/security.c:security_module_enable
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_read_token
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/lib.c:aa_split_fqname
  - security/apparmor/lsm.c:apparmor_getprocattr
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/parser.c:match_token
  - lib/kasprintf.c:kvasprintf_const
  - lib/string_helpers.c:string_escape_mem
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/base/platform.c:driver_override_store
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
  - drivers/usb/host/uhci-hcd.c:lprintk
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-stats.c:dm_stats_message
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff818f6e30-ffffffff818f6e5c: strchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *strchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff8197d830)
Location: lib/string.c:370
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts_md.c:raid_setup
  - init/do_mounts_md.c:md_setup_drive
  - arch/x86/xen/platform-pci-unplug.c:parse_xen_emul_unplug
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:set_trigger
  - arch/x86/kernel/acpi/sleep.c:acpi_sleep_setup
  - arch/x86/kernel/hpet.c:hpet_setup
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/reboot.c:reboot_setup
  - kernel/printk/printk.c:console_setup
  - kernel/module.c:get_ksymbol
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdbgetenv
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_parse_regex
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/bpf/inode.c:bpf_lookup
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:register_filesystem
  - fs/namespace.c:do_mount
  - fs/seq_file.c:mangle_path
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/binfmt_script.c:load_script
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:set_qf_name
  - security/keys/user_defined.c:logon_vet_description
  - security/security.c:security_module_enable
  - security/security.c:security_module_enable
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_read_token
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/lib.c:aa_split_fqname
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/parser.c:match_token
  - lib/kasprintf.c:kvasprintf_const
  - lib/string_helpers.c:string_escape_mem
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/base/platform.c:driver_override_store
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
  - drivers/usb/host/uhci-hcd.c:lprintk
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-stats.c:dm_stats_message
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff8197d830-ffffffff8197d85c: strchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *strchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff819d9d30)
Location: lib/string.c:370
Inline: False
Direct callers:
  - init/main.c:unknown_bootoption
  - init/do_mounts.c:mount_block_root
  - init/do_mounts_md.c:raid_setup
  - init/do_mounts_md.c:md_setup_drive
  - arch/x86/xen/platform-pci-unplug.c:parse_xen_emul_unplug
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:set_trigger
  - arch/x86/kernel/acpi/sleep.c:acpi_sleep_setup
  - arch/x86/kernel/hpet.c:hpet_setup
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/params.c:param_sysfs_init
  - kernel/reboot.c:reboot_setup
  - kernel/printk/printk.c:console_setup
  - kernel/module.c:get_ksymbol
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdbgetenv
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_parse_regex
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_synth_event
  - kernel/trace/trace_events_hist.c:create_synth_event
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/bpf/inode.c:bpf_lookup
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:register_filesystem
  - fs/namespace.c:do_mount
  - fs/seq_file.c:mangle_path
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/binfmt_script.c:load_script
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:set_qf_name
  - security/keys/user_defined.c:logon_vet_description
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_read_token
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/lib.c:aa_split_fqname
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/parser.c:match_token
  - lib/kasprintf.c:kvasprintf_const
  - lib/string_helpers.c:string_escape_mem
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/video/fbdev/core/fb_cmdline.c:video_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/base/platform.c:driver_override_store
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-stats.c:dm_stats_message
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff819d9d30-ffffffff819d9d52: strchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *strchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a11f50)
Location: lib/string.c:371
Inline: False
Direct callers:
  - init/main.c:unknown_bootoption
  - init/do_mounts.c:mount_block_root
  - init/do_mounts_md.c:raid_setup
  - init/do_mounts_md.c:md_setup_drive
  - arch/x86/xen/platform-pci-unplug.c:parse_xen_emul_unplug
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/acpi/sleep.c:acpi_sleep_setup
  - arch/x86/kernel/hpet.c:hpet_setup
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/params.c:param_sysfs_init
  - kernel/reboot.c:reboot_setup
  - kernel/printk/printk.c:console_setup
  - kernel/module.c:find_kallsyms_symbol
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdbgetenv
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_parse_regex
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:synth_event_create
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_lookup
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/slub.c:kmem_cache_flags
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:register_filesystem
  - fs/namespace.c:do_mount
  - fs/seq_file.c:mangle_path
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:set_qf_name
  - security/keys/user_defined.c:logon_vet_description
  - security/selinux/hooks.c:show_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_read_token
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/lib.c:aa_split_fqname
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/parser.c:match_token
  - lib/kasprintf.c:kvasprintf_const
  - lib/string_helpers.c:string_escape_mem
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/video/fbdev/core/fb_cmdline.c:video_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/base/platform.c:driver_override_store
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-stats.c:dm_stats_message
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff81a11f50-ffffffff81a11f72: strchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *strchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a81420)
Location: lib/string.c:407
Inline: False
Direct callers:
  - init/main.c:unknown_bootoption
  - init/do_mounts.c:mount_block_root
  - init/do_mounts_md.c:raid_setup
  - init/do_mounts_md.c:md_setup_drive
  - arch/x86/xen/platform-pci-unplug.c:parse_xen_emul_unplug
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/acpi/sleep.c:acpi_sleep_setup
  - arch/x86/kernel/hpet.c:hpet_setup
  - kernel/params.c:param_sysfs_init
  - kernel/reboot.c:reboot_setup
  - kernel/printk/printk.c:console_setup
  - kernel/module.c:find_kallsyms_symbol
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdbgetenv
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_parse_regex
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:synth_event_create
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_lookup
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:register_filesystem
  - fs/namespace.c:do_mount
  - fs/seq_file.c:mangle_path
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:logfc
  - fs/fs_context.c:generic_parse_monolithic
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:set_qf_name
  - security/keys/user_defined.c:logon_vet_description
  - security/selinux/hooks.c:show_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_read_token
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/lib.c:aa_split_fqname
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/parser.c:match_token
  - lib/kasprintf.c:kvasprintf_const
  - lib/string_helpers.c:string_escape_mem
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/video/fbdev/core/fb_cmdline.c:video_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/base/platform.c:driver_override_store
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/usb/host/uhci-hcd.c:lprintk
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/md/dm-init.c:str_field_delimit
  - drivers/md/dm-ioctl.c:check_name
  - drivers/md/dm-stats.c:parse_histogram
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff81a81420-ffffffff81a81443: strchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *strchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81ab84f0)
Location: lib/string.c:409
Inline: False
Direct callers:
  - init/main.c:unknown_bootoption
  - init/do_mounts.c:mount_block_root
  - init/do_mounts_md.c:raid_setup
  - init/do_mounts_md.c:md_setup_drive
  - arch/x86/xen/platform-pci-unplug.c:parse_xen_emul_unplug
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/acpi/sleep.c:acpi_sleep_setup
  - arch/x86/kernel/hpet.c:hpet_setup
  - arch/x86/platform/uv/uv_nmi.c:param_set_action
  - kernel/params.c:param_sysfs_init
  - kernel/reboot.c:reboot_setup
  - kernel/printk/printk.c:console_setup
  - kernel/module.c:find_kallsyms_symbol
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdbgetenv
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_parse_regex
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:synth_event_create
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:within_notrace_func
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_lookup
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:register_filesystem
  - fs/namespace.c:do_mount
  - fs/seq_file.c:mangle_path
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:logfc
  - fs/fs_context.c:generic_parse_monolithic
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:set_qf_name
  - security/keys/user_defined.c:logon_vet_description
  - security/selinux/hooks.c:show_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_read_token
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/lib.c:aa_split_fqname
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
  - block/blk-iocost.c:ioc_weight_write
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/parser.c:match_token
  - lib/kasprintf.c:kvasprintf_const
  - lib/string_helpers.c:string_escape_mem
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/video/fbdev/core/fb_cmdline.c:video_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/base/platform.c:driver_override_store
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/usb/host/uhci-hcd.c:lprintk
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/md/dm-init.c:str_field_delimit
  - drivers/md/dm-ioctl.c:check_name
  - drivers/md/dm-stats.c:parse_histogram
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff81ab84f0-ffffffff81ab8513: strchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *strchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff815f3130)
Location: lib/string.c:433
Inline: False
Direct callers:
  - init/do_mounts.c:get_fs_names
  - init/do_mounts.c:devt_from_partuuid
  - init/do_mounts_md.c:raid_setup
  - init/do_mounts_md.c:md_setup_drive
  - arch/x86/xen/platform-pci-unplug.c:parse_xen_emul_unplug
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir
  - arch/x86/kernel/acpi/sleep.c:acpi_sleep_setup
  - arch/x86/kernel/hpet.c:hpet_setup
  - arch/x86/platform/uv/uv_nmi.c:param_set_action
  - kernel/params.c:param_sysfs_builtin
  - kernel/reboot.c:reboot_setup
  - kernel/printk/printk.c:console_setup
  - kernel/module.c:find_kallsyms_symbol
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:kdbgetenv
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_parse_regex
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:synth_field_string_size
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_kprobe.c:within_notrace_func
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_lookup
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:register_filesystem
  - fs/namespace.c:do_new_mount
  - fs/seq_file.c:mangle_path
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:generic_parse_monolithic
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/proc/root.c:proc_parse_param
  - fs/proc/base.c:timens_offsets_write
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:set_qf_name
  - security/keys/user_defined.c:logon_vet_description
  - security/selinux/hooks.c:show_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_transit_preference
  - security/tomoyo/condition.c:tomoyo_scan_bprm
  - security/tomoyo/environ.c:tomoyo_write_env
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_read_token
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/lib.c:aa_split_fqname
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:parse_policy_line
  - block/blk-iocost.c:ioc_weight_write
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:parse_parts
  - block/cmdline-parser.c:parse_parts
  - block/cmdline-parser.c:parse_subpart
  - lib/parser.c:match_one
  - lib/kasprintf.c:kvasprintf_const
  - lib/string_helpers.c:kstrdup_quotable
  - lib/string_helpers.c:string_escape_mem
  - lib/dynamic_debug.c:ddebug_dyndbg_module_param_cb
  - lib/dynamic_debug.c:ddebug_dyndbg_boot_param_cb
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:ddebug_parse_query
  - lib/bootconfig.c:__xbc_parse_keys
  - lib/bootconfig.c:__xbc_parse_value
  - lib/bootconfig.c:__xbc_parse_value
  - lib/kobject.c:kobject_set_name_vargs
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_in_ignore_list
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_in_ignore_list
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/video/fbdev/core/fb_cmdline.c:video_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/base/core.c:device_get_devnode
  - drivers/base/platform.c:driver_override_store
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/i2c/i2c-core-base.c:new_device_store
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/md/dm-init.c:str_field_delimit
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-stats.c:parse_histogram
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_sync_lower_features
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ethtool/netlink.c:ethtool_notify
  - net/ethtool/privflags.c:ethnl_get_priv_flags_info
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
```
**Symbols:**

```
ffffffff815f3130-ffffffff815f3153: strchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *strchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff816177e0)
Location: lib/string.c:430
Inline: False
Direct callers:
  - init/do_mounts.c:get_fs_names
  - init/do_mounts.c:devt_from_partuuid
  - arch/x86/xen/platform-pci-unplug.c:parse_xen_emul_unplug
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir
  - arch/x86/kernel/acpi/sleep.c:acpi_sleep_setup
  - arch/x86/kernel/hpet.c:hpet_setup
  - arch/x86/platform/uv/uv_nmi.c:param_set_action
  - kernel/params.c:param_sysfs_builtin
  - kernel/reboot.c:reboot_setup
  - kernel/printk/printk.c:console_setup
  - kernel/module.c:find_kallsyms_symbol
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:kdbgetenv
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_parse_regex
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:synth_field_string_size
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_kprobe.c:within_notrace_func
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_lookup
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:register_filesystem
  - fs/namespace.c:do_new_mount
  - fs/seq_file.c:mangle_path
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:generic_parse_monolithic
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/proc/root.c:proc_parse_param
  - fs/proc/base.c:timens_offsets_write
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:set_qf_name
  - security/keys/user_defined.c:logon_vet_description
  - security/selinux/hooks.c:show_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_transit_preference
  - security/tomoyo/condition.c:tomoyo_scan_bprm
  - security/tomoyo/environ.c:tomoyo_write_env
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_read_token
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/lib.c:aa_split_fqname
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:parse_policy_line
  - block/blk-iocost.c:ioc_weight_write
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:parse_parts
  - block/cmdline-parser.c:parse_parts
  - block/cmdline-parser.c:parse_subpart
  - lib/parser.c:match_one
  - lib/kasprintf.c:kvasprintf_const
  - lib/string_helpers.c:kstrdup_quotable
  - lib/string_helpers.c:string_escape_mem
  - lib/dynamic_debug.c:ddebug_dyndbg_module_param_cb
  - lib/dynamic_debug.c:ddebug_dyndbg_boot_param_cb
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:ddebug_parse_query
  - lib/dynamic_debug.c:parse_linerange
  - lib/bootconfig.c:__xbc_parse_keys
  - lib/bootconfig.c:__xbc_parse_value
  - lib/bootconfig.c:__xbc_parse_value
  - lib/kobject.c:kobject_set_name_vargs
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_in_ignore_list
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_in_ignore_list
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/video/fbdev/core/fb_cmdline.c:video_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/base/core.c:device_get_devnode
  - drivers/base/platform.c:driver_override_store
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/i2c/i2c-core-base.c:new_device_store
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/md/md-autodetect.c:raid_setup
  - drivers/md/md-autodetect.c:md_setup_drive
  - drivers/md/dm-init.c:str_field_delimit
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-stats.c:parse_histogram
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_sync_lower_features
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/sched/sch_frag.c:sch_fragment
  - net/ethtool/netlink.c:ethtool_notify
  - net/ethtool/privflags.c:ethnl_get_priv_flags_info
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
```
**Symbols:**

```
ffffffff816177e0-ffffffff81617803: strchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *strchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff815fae60)
Location: lib/string.c:430
Inline: False
Direct callers:
  - init/do_mounts.c:get_fs_names
  - init/do_mounts.c:devt_from_partuuid
  - arch/x86/events/core.c:events_hybrid_sysfs_show
  - arch/x86/xen/platform-pci-unplug.c:parse_xen_emul_unplug
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir
  - arch/x86/kernel/acpi/sleep.c:acpi_sleep_setup
  - arch/x86/kernel/hpet.c:hpet_setup
  - arch/x86/platform/uv/uv_nmi.c:param_set_action
  - kernel/params.c:param_sysfs_builtin
  - kernel/reboot.c:reboot_setup
  - kernel/printk/printk.c:console_setup
  - kernel/module.c:find_kallsyms_symbol
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:kdbgetenv
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_parse_regex
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:synth_field_string_size
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_kprobe.c:within_notrace_func
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/bpf/inode.c:bpf_lookup
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:register_filesystem
  - fs/namespace.c:do_new_mount
  - fs/seq_file.c:mangle_path
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:generic_parse_monolithic
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/proc/root.c:proc_parse_param
  - fs/proc/base.c:timens_offsets_write
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:set_qf_name
  - security/keys/user_defined.c:logon_vet_description
  - security/selinux/hooks.c:show_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_scan_bprm
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_read_token
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/lib.c:aa_split_fqname
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
  - block/blk-iocost.c:ioc_weight_write
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:parse_parts
  - block/cmdline-parser.c:parse_parts
  - block/cmdline-parser.c:parse_subpart
  - lib/parser.c:match_one
  - lib/kasprintf.c:kvasprintf_const
  - lib/string_helpers.c:kstrdup_quotable
  - lib/string_helpers.c:string_escape_mem
  - lib/dynamic_debug.c:ddebug_dyndbg_module_param_cb
  - lib/dynamic_debug.c:ddebug_dyndbg_boot_param_cb
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:ddebug_parse_query
  - lib/dynamic_debug.c:parse_linerange
  - lib/bootconfig.c:__xbc_parse_keys
  - lib/bootconfig.c:__xbc_parse_value
  - lib/bootconfig.c:__xbc_parse_value
  - lib/kobject.c:kobject_set_name_vargs
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_in_ignore_list
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_in_ignore_list
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/video/fbdev/core/fb_cmdline.c:video_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/base/core.c:device_get_devnode
  - drivers/base/platform.c:driver_override_store
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/i2c/i2c-core-base.c:new_device_store
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/md/md-autodetect.c:raid_setup
  - drivers/md/md-autodetect.c:md_setup_drive
  - drivers/md/dm-init.c:str_field_delimit
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-stats.c:parse_histogram
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/sched/sch_frag.c:sch_fragment
  - net/ethtool/netlink.c:ethtool_notify
  - net/ethtool/privflags.c:ethnl_get_priv_flags_info
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
```
**Symbols:**

```
ffffffff815fae60-ffffffff815fae83: strchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *strchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81668710)
Location: lib/string.c:431
Inline: False
Direct callers:
  - init/do_mounts.c:devt_from_partuuid
  - arch/x86/events/core.c:events_hybrid_sysfs_show
  - arch/x86/xen/platform-pci-unplug.c:parse_xen_emul_unplug
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir
  - arch/x86/kernel/acpi/sleep.c:acpi_sleep_setup
  - arch/x86/kernel/hpet.c:hpet_setup
  - arch/x86/platform/uv/uv_nmi.c:param_set_action
  - kernel/params.c:param_sysfs_builtin
  - kernel/reboot.c:reboot_setup
  - kernel/printk/printk.c:console_setup
  - kernel/module.c:find_kallsyms_symbol
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:kdbgetenv
  - kernel/debug/kdb/kdb_support.c:kdb_task_state
  - kernel/debug/kdb/kdb_support.c:kdb_task_state
  - kernel/debug/kdb/kdb_support.c:kdb_task_state
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_parse_regex
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_match
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_match
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:synth_field_string_size
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_kprobe.c:within_notrace_func
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/bpf/inode.c:bpf_lookup
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:register_filesystem
  - fs/namespace.c:do_new_mount
  - fs/seq_file.c:mangle_path
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:generic_parse_monolithic
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/proc/root.c:proc_parse_param
  - fs/proc/base.c:timens_offsets_write
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:set_qf_name
  - security/keys/user_defined.c:logon_vet_description
  - security/selinux/hooks.c:show_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_scan_bprm
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_read_token
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/lib.c:aa_split_fqname
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/cmdline.c:parse_parts
  - block/partitions/cmdline.c:parse_parts
  - block/partitions/cmdline.c:parse_subpart
  - block/blk-iocost.c:ioc_weight_write
  - lib/parser.c:match_one
  - lib/kasprintf.c:kvasprintf_const
  - lib/string_helpers.c:string_escape_mem
  - lib/dynamic_debug.c:ddebug_dyndbg_module_param_cb
  - lib/dynamic_debug.c:ddebug_dyndbg_boot_param_cb
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:ddebug_parse_query
  - lib/dynamic_debug.c:parse_linerange
  - lib/bootconfig.c:__xbc_parse_keys
  - lib/bootconfig.c:__xbc_parse_value
  - lib/bootconfig.c:__xbc_parse_value
  - lib/kobject.c:kobject_set_name_vargs
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_in_ignore_list
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_in_ignore_list
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:resource_alignment_store
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/video/fbdev/core/fb_cmdline.c:video_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/base/core.c:device_get_devnode
  - drivers/base/platform.c:driver_override_store
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/i2c/i2c-core-base.c:new_device_store
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/md/md-autodetect.c:raid_setup
  - drivers/md/md-autodetect.c:md_setup_drive
  - drivers/md/dm-init.c:str_field_delimit
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-stats.c:parse_histogram
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/sched/sch_frag.c:sch_fragment
  - net/ethtool/netlink.c:ethtool_notify
  - net/ethtool/privflags.c:ethnl_get_priv_flags_info
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
```
**Symbols:**

```
ffffffff81668710-ffffffff81668733: strchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
char *strchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81781d50)
Location: lib/string.c:392
Inline: True
Inline callers:
  - lib/string.c:strcspn
  - lib/string.c:strspn
Direct callers:
  - init/do_mounts.c:devt_from_partuuid
  - arch/x86/events/core.c:events_hybrid_sysfs_show
  - arch/x86/xen/platform-pci-unplug.c:parse_xen_emul_unplug
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/bugs.c:retbleed_parse_cmdline
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir
  - arch/x86/kernel/acpi/sleep.c:acpi_sleep_setup
  - arch/x86/kernel/hpet.c:hpet_setup
  - arch/x86/platform/uv/uv_nmi.c:param_set_action
  - kernel/sys.c:prctl_set_vma
  - kernel/params.c:param_sysfs_builtin
  - kernel/reboot.c:reboot_setup
  - kernel/printk/printk.c:console_setup
  - kernel/module/kallsyms.c:find_kallsyms_symbol
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/user_namespace.c:map_write
  - kernel/kprobes.c:within_kprobe_blacklist
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:kdbgetenv
  - kernel/debug/kdb/kdb_support.c:kdb_task_state
  - kernel/debug/kdb/kdb_support.c:kdb_task_state
  - kernel/debug/kdb/kdb_support.c:kdb_task_state
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace_events.c:update_event_fields
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_parse_regex
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_match
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_match
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:synth_field_string_size
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_kprobe.c:within_notrace_func
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/bpf/inode.c:bpf_lookup
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:register_filesystem
  - fs/namespace.c:do_new_mount
  - fs/seq_file.c:mangle_path
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:generic_parse_monolithic
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/proc/root.c:proc_parse_param
  - fs/proc/base.c:timens_offsets_write
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
  - fs/ext4/super.c:parse_options
  - security/keys/user_defined.c:logon_vet_description
  - security/selinux/hooks.c:show_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_scan_bprm
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_domain_def
  - security/tomoyo/util.c:tomoyo_correct_domain
  - security/tomoyo/util.c:tomoyo_correct_domain
  - security/tomoyo/util.c:tomoyo_read_token
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/lib.c:aa_split_fqname
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/cmdline.c:parse_parts
  - block/partitions/cmdline.c:parse_parts
  - block/partitions/cmdline.c:parse_subpart
  - block/blk-iocost.c:ioc_weight_write
  - lib/parser.c:match_one
  - lib/kasprintf.c:kvasprintf_const
  - lib/string_helpers.c:string_escape_mem
  - lib/dynamic_debug.c:ddebug_dyndbg_module_param_cb
  - lib/dynamic_debug.c:ddebug_dyndbg_boot_param_cb
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:ddebug_parse_query
  - lib/dynamic_debug.c:parse_linerange
  - lib/bootconfig.c:__xbc_parse_keys
  - lib/bootconfig.c:__xbc_parse_value
  - lib/bootconfig.c:__xbc_parse_value
  - lib/kobject.c:kobject_set_name_vargs
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_in_ignore_list
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_in_ignore_list
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:resource_alignment_store
  - drivers/video/fbdev/core/fb_cmdline.c:video_setup
  - drivers/acpi/bus.c:acpi_set_modalias
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/base/core.c:device_get_devnode
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/i2c/i2c-core-base.c:new_device_store
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/md/md-autodetect.c:raid_setup
  - drivers/md/md-autodetect.c:md_setup_drive
  - drivers/md/dm-init.c:str_field_delimit
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-stats.c:parse_histogram
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev_addr_lists.c:dev_addr_check
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/sched/sch_frag.c:sch_fragment
  - net/ethtool/netlink.c:ethtool_notify
  - net/ethtool/privflags.c:ethnl_get_priv_flags_info
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
```
**Symbols:**

```
ffffffff81781d50-ffffffff81781d87: strchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
char *strchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff8203eae0)
Location: lib/string.c:327
Inline: True
Inline callers:
  - lib/string.c:strcspn
  - lib/string.c:strspn
Direct callers:
  - init/do_mounts.c:devt_from_partuuid
  - arch/x86/events/core.c:events_hybrid_sysfs_show
  - arch/x86/xen/platform-pci-unplug.c:parse_xen_emul_unplug
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/bugs.c:retbleed_parse_cmdline
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir
  - arch/x86/kernel/acpi/sleep.c:acpi_sleep_setup
  - arch/x86/kernel/hpet.c:hpet_setup
  - arch/x86/platform/uv/uv_nmi.c:param_set_action
  - kernel/sys.c:prctl_set_vma
  - kernel/params.c:param_sysfs_builtin
  - kernel/reboot.c:reboot_setup
  - kernel/printk/printk.c:console_setup
  - kernel/module/kallsyms.c:find_kallsyms_symbol
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/user_namespace.c:map_write
  - kernel/kprobes.c:within_kprobe_blacklist
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:kdbgetenv
  - kernel/debug/kdb/kdb_support.c:kdb_task_state
  - kernel/debug/kdb/kdb_support.c:kdb_task_state
  - kernel/debug/kdb/kdb_support.c:kdb_task_state
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace_events.c:update_event_fields
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_parse_regex
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_match
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_match
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:synth_field_string_size
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_kprobe.c:within_notrace_func
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/bpf/inode.c:bpf_lookup
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:register_filesystem
  - fs/namespace.c:do_new_mount
  - fs/seq_file.c:mangle_path
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:generic_parse_monolithic
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/proc/root.c:proc_parse_param
  - fs/proc/base.c:timens_offsets_write
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
  - fs/ext4/super.c:parse_options
  - security/keys/user_defined.c:logon_vet_description
  - security/selinux/hooks.c:show_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_scan_bprm
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_domain_def
  - security/tomoyo/util.c:tomoyo_correct_domain
  - security/tomoyo/util.c:tomoyo_correct_domain
  - security/tomoyo/util.c:tomoyo_read_token
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/lib.c:aa_split_fqname
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/cmdline.c:parse_parts
  - block/partitions/cmdline.c:parse_parts
  - block/partitions/cmdline.c:parse_subpart
  - block/blk-iocost.c:ioc_weight_write
  - lib/parser.c:match_one
  - lib/kasprintf.c:kvasprintf_const
  - lib/base64.c:base64_decode
  - lib/string_helpers.c:string_escape_mem
  - lib/dynamic_debug.c:ddebug_dyndbg_module_param_cb
  - lib/dynamic_debug.c:ddebug_dyndbg_boot_param_cb
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:param_set_dyndbg_classnames
  - lib/dynamic_debug.c:param_set_dyndbg_classnames
  - lib/dynamic_debug.c:ddebug_parse_query
  - lib/dynamic_debug.c:parse_linerange
  - lib/bootconfig.c:xbc_parse_tree
  - lib/bootconfig.c:__xbc_parse_keys
  - lib/bootconfig.c:__xbc_parse_value
  - lib/bootconfig.c:__xbc_parse_value
  - lib/bootconfig.c:__xbc_parse_value
  - lib/bootconfig.c:__xbc_parse_value
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_in_ignore_list
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_in_ignore_list
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:resource_alignment_store
  - drivers/video/fbdev/core/fb_cmdline.c:video_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/base/core.c:device_get_devnode
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_port_debugfs
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/i2c/i2c-core-base.c:new_device_store
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/md/md-autodetect.c:raid_setup
  - drivers/md/md-autodetect.c:md_setup_drive
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-stats.c:parse_histogram
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev_addr_lists.c:dev_addr_check
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/sched/sch_frag.c:sch_fragment
  - net/ethtool/netlink.c:ethtool_notify
  - net/ethtool/privflags.c:ethnl_get_priv_flags_info
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff8203eae0-ffffffff8203eb17: strchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
char *strchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff820bcfe0)
Location: lib/string.c:327
Inline: True
Inline callers:
  - lib/string.c:strsep
  - lib/string.c:strcspn
  - lib/string.c:strspn
Direct callers:
  - arch/x86/events/core.c:events_hybrid_sysfs_show
  - arch/x86/xen/platform-pci-unplug.c:parse_xen_emul_unplug
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/bugs.c:retbleed_parse_cmdline
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir
  - arch/x86/kernel/acpi/sleep.c:acpi_sleep_setup
  - arch/x86/kernel/hpet.c:hpet_setup
  - arch/x86/platform/uv/uv_nmi.c:param_set_action
  - kernel/sys.c:prctl_set_vma
  - kernel/params.c:param_sysfs_builtin
  - kernel/reboot.c:reboot_setup
  - kernel/printk/printk.c:console_setup
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/user_namespace.c:map_write
  - kernel/kprobes.c:within_kprobe_blacklist
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:kdbgetenv
  - kernel/debug/kdb/kdb_support.c:kdb_task_state
  - kernel/debug/kdb/kdb_support.c:kdb_task_state
  - kernel/debug/kdb/kdb_support.c:kdb_task_state
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace_events.c:update_event_fields
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_parse_regex
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_match
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_match
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:synth_field_string_size
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_user.c:user_dyn_field_set_string
  - kernel/trace/trace_events_user.c:user_field_array_size
  - kernel/trace/trace_events_user.c:user_field_array_size
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_kprobe.c:within_notrace_func
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_fprobe.c:__trace_fprobe_create
  - kernel/trace/trace_fprobe.c:__trace_fprobe_create
  - kernel/bpf/inode.c:bpf_lookup
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:register_filesystem
  - fs/namespace.c:do_new_mount
  - fs/seq_file.c:mangle_path
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:generic_parse_monolithic
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/proc/root.c:proc_parse_param
  - fs/proc/base.c:timens_offsets_write
  - fs/proc/proc_sysctl.c:sysctl_mkdir_p
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
  - fs/ext4/super.c:parse_options
  - security/keys/user_defined.c:logon_vet_description
  - security/selinux/hooks.c:show_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_scan_bprm
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_domain_def
  - security/tomoyo/util.c:tomoyo_correct_domain
  - security/tomoyo/util.c:tomoyo_correct_domain
  - security/tomoyo/util.c:tomoyo_read_token
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/lib.c:aa_split_fqname
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/cmdline.c:parse_parts
  - block/partitions/cmdline.c:parse_parts
  - block/partitions/cmdline.c:parse_subpart
  - block/early-lookup.c:devt_from_partuuid
  - block/blk-iocost.c:ioc_weight_write
  - lib/parser.c:match_one
  - lib/kasprintf.c:kvasprintf_const
  - lib/base64.c:base64_decode
  - lib/string_helpers.c:string_escape_mem
  - lib/dynamic_debug.c:ddebug_dyndbg_module_param_cb
  - lib/dynamic_debug.c:ddebug_dyndbg_boot_param_cb
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:param_set_dyndbg_classnames
  - lib/dynamic_debug.c:param_set_dyndbg_classnames
  - lib/dynamic_debug.c:ddebug_parse_query
  - lib/dynamic_debug.c:parse_linerange
  - lib/bootconfig.c:xbc_parse_tree
  - lib/bootconfig.c:__xbc_parse_keys
  - lib/bootconfig.c:__xbc_parse_value
  - lib/bootconfig.c:__xbc_parse_value
  - lib/bootconfig.c:__xbc_parse_value
  - lib/bootconfig.c:__xbc_parse_value
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_in_ignore_list
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_in_ignore_list
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:resource_alignment_store
  - drivers/video/cmdline.c:video_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/base/core.c:device_get_devnode
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_port_debugfs
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/i2c/i2c-core-base.c:new_device_store
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/md/md-autodetect.c:raid_setup
  - drivers/md/md-autodetect.c:md_setup_drive
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/md/dm-ioctl.c:check_name
  - drivers/md/dm-stats.c:parse_histogram
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev_addr_lists.c:dev_addr_check
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/sched/sch_frag.c:sch_fragment
  - net/ethtool/netlink.c:ethtool_notify
  - net/ethtool/privflags.c:ethnl_get_priv_flags_info
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff820bcfe0-ffffffff820bd017: strchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
char *strchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff821978e0)
Location: lib/string.c:312
Inline: True
Inline callers:
  - lib/string.c:strsep
  - lib/string.c:strcspn
  - lib/string.c:strspn
Direct callers:
  - arch/x86/events/core.c:events_hybrid_sysfs_show
  - arch/x86/xen/platform-pci-unplug.c:parse_xen_emul_unplug
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/bugs.c:retbleed_parse_cmdline
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir
  - arch/x86/kernel/acpi/sleep.c:acpi_sleep_setup
  - arch/x86/kernel/hpet.c:hpet_setup
  - kernel/sys.c:prctl_set_vma
  - kernel/params.c:param_sysfs_builtin
  - kernel/reboot.c:reboot_setup
  - kernel/printk/printk.c:console_setup
  - kernel/crash_core.c:__parse_crashkernel
  - kernel/crash_core.c:__parse_crashkernel
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/user_namespace.c:map_write
  - kernel/kprobes.c:within_kprobe_blacklist
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:kdbgetenv
  - kernel/debug/kdb/kdb_support.c:kdb_task_state
  - kernel/debug/kdb/kdb_support.c:kdb_task_state
  - kernel/debug/kdb/kdb_support.c:kdb_task_state
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace_events.c:update_event_fields
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_parse_regex
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_match
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_match
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:synth_field_string_size
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_user.c:user_dyn_field_set_string
  - kernel/trace/trace_events_user.c:user_field_array_size
  - kernel/trace/trace_events_user.c:user_field_array_size
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_kprobe.c:within_notrace_func
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_fprobe.c:__trace_fprobe_create
  - kernel/trace/trace_fprobe.c:__trace_fprobe_create
  - kernel/bpf/inode.c:bpf_lookup
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:register_filesystem
  - fs/namespace.c:do_new_mount
  - fs/seq_file.c:mangle_path
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:vfs_parse_monolithic_sep
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/proc/root.c:proc_parse_param
  - fs/proc/base.c:timens_offsets_write
  - fs/proc/proc_sysctl.c:sysctl_mkdir_p
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
  - fs/ext4/super.c:parse_options
  - security/keys/user_defined.c:logon_vet_description
  - security/selinux/hooks.c:show_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_add_entry
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_scan_bprm
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_domain_def
  - security/tomoyo/util.c:tomoyo_correct_domain
  - security/tomoyo/util.c:tomoyo_correct_domain
  - security/tomoyo/util.c:tomoyo_read_token
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/lib.c:aa_split_fqname
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/cmdline.c:parse_parts
  - block/partitions/cmdline.c:parse_parts
  - block/partitions/cmdline.c:parse_subpart
  - block/early-lookup.c:devt_from_partuuid
  - block/blk-iocost.c:ioc_weight_write
  - lib/parser.c:match_one
  - lib/kasprintf.c:kvasprintf_const
  - lib/base64.c:base64_decode
  - lib/string_helpers.c:string_escape_mem
  - lib/dynamic_debug.c:ddebug_dyndbg_module_param_cb
  - lib/dynamic_debug.c:ddebug_dyndbg_boot_param_cb
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:param_set_dyndbg_classnames
  - lib/dynamic_debug.c:param_set_dyndbg_classnames
  - lib/dynamic_debug.c:ddebug_parse_query
  - lib/dynamic_debug.c:parse_linerange
  - lib/bootconfig.c:xbc_parse_tree
  - lib/bootconfig.c:__xbc_parse_keys
  - lib/bootconfig.c:__xbc_parse_value
  - lib/bootconfig.c:__xbc_parse_value
  - lib/bootconfig.c:__xbc_parse_value
  - lib/bootconfig.c:__xbc_parse_value
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_in_ignore_list
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_in_ignore_list
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci.c:resource_alignment_store
  - drivers/video/cmdline.c:video_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/iommu/amd/init.c:parse_ivrs_acpihid
  - drivers/base/core.c:device_get_devnode
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/gpu/drm/drm_modes.c:drm_mode_parse_command_line_for_connector
  - drivers/gpu/drm/drm_modes.c:drm_mode_parse_panel_orientation
  - drivers/gpu/drm/drm_edid_load.c:drm_edid_load_firmware
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_port_debugfs
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/i2c/i2c-core-base.c:new_device_store
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/md/md-autodetect.c:raid_setup
  - drivers/md/md-autodetect.c:md_setup_drive
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/md/dm-ioctl.c:check_name
  - drivers/md/dm-stats.c:parse_histogram
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev_addr_lists.c:dev_addr_check
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/sched/sch_frag.c:sch_fragment
  - net/ethtool/netlink.c:ethtool_notify
  - net/ethtool/privflags.c:ethnl_get_priv_flags_info
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff821978e0-ffffffff82197917: strchr (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - init/main.c:unknown_bootoption
  - init/do_mounts.c:mount_block_root
  - init/do_mounts_md.c:raid_setup
  - init/do_mounts_md.c:md_setup_drive
  - kernel/params.c:param_sysfs_init
  - kernel/reboot.c:reboot_setup
  - kernel/printk/printk.c:console_setup
  - kernel/module.c:find_kallsyms_symbol
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdbgetenv
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_parse_regex
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:synth_event_create
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_lookup
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:register_filesystem
  - fs/namespace.c:do_mount
  - fs/seq_file.c:mangle_path
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:logfc
  - fs/fs_context.c:generic_parse_monolithic
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:set_qf_name
  - security/keys/user_defined.c:logon_vet_description
  - security/selinux/hooks.c:show_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_read_token
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/lib.c:aa_split_fqname
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
  - block/blk-iocost.c:ioc_weight_write
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/kasprintf.c:kvasprintf_const
  - lib/string_helpers.c:string_escape_mem
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/video/fbdev/core/fb_cmdline.c:video_setup
  - drivers/amba/bus.c:driver_override_store
  - drivers/clk/sunxi/clk-sunxi.c:sunxi_divs_clk_setup
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/base/platform.c:driver_override_store
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/usb/host/uhci-hcd.c:lprintk
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/i2c/i2c-core-of.c:i2c_of_match_device
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/md/dm-init.c:str_field_delimit
  - drivers/md/dm-ioctl.c:check_name
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/of/base.c:of_modalias_node
  - drivers/of/base.c:of_find_node_opts_by_path
  - drivers/of/base.c:__of_find_node_by_full_path
  - drivers/of/device.c:of_device_get_modalias
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/of/resolver.c:of_resolve_phandles
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffff800010d82f88-ffff800010d82fac: strchr (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - init/main.c:unknown_bootoption
  - init/do_mounts.c:mount_block_root
  - init/do_mounts_md.c:raid_setup
  - init/do_mounts_md.c:md_setup_drive
  - arch/arm/kernel/vdso.c:find_symbol
  - kernel/params.c:param_sysfs_init
  - kernel/reboot.c:reboot_setup
  - kernel/printk/printk.c:console_setup
  - kernel/module.c:find_kallsyms_symbol
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdbgetenv
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_parse_regex
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_lookup
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:register_filesystem
  - fs/namespace.c:do_mount
  - fs/seq_file.c:mangle_path
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:logfc
  - fs/fs_context.c:generic_parse_monolithic
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:set_qf_name
  - security/keys/user_defined.c:logon_vet_description
  - security/selinux/hooks.c:show_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_read_token
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/lib.c:aa_split_fqname
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
  - block/blk-iocost.c:ioc_weight_write
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/parser.c:match_token
  - lib/kasprintf.c:kvasprintf_const
  - lib/string_helpers.c:string_escape_mem
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:ddebug_exec_queries
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinconf_config_dbg_show
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinconf_group_dbg_show
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/video/fbdev/core/fb_cmdline.c:video_setup
  - drivers/amba/bus.c:driver_override_store
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/base/platform.c:driver_override_store
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/mtd/parsers/cmdlinepart.c:parse_cmdline_partitions
  - drivers/mtd/parsers/cmdlinepart.c:newpart
  - drivers/usb/host/uhci-hcd.c:lprintk
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/i2c/i2c-core-of.c:i2c_of_match_device
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/md/dm-init.c:str_field_delimit
  - drivers/md/dm-ioctl.c:check_name
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/of/base.c:of_modalias_node
  - drivers/of/base.c:of_find_node_opts_by_path
  - drivers/of/base.c:__of_find_node_by_full_path
  - drivers/of/device.c:of_device_get_modalias
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/of/resolver.c:of_resolve_phandles
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
c0e7e8e0-c0e7e904: strchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *strchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (c000000000ed6840)
Location: lib/string.c:409
Inline: False
Direct callers:
  - init/main.c:unknown_bootoption
  - init/do_mounts.c:mount_block_root
  - init/do_mounts_md.c:raid_setup
  - init/do_mounts_md.c:md_setup_drive
  - arch/powerpc/kernel/vdso.c:find_symbol64
  - arch/powerpc/platforms/pseries/reconfig.c:ofdt_write
  - arch/powerpc/platforms/pseries/reconfig.c:ofdt_write
  - arch/powerpc/platforms/pseries/reconfig.c:ofdt_write
  - arch/powerpc/platforms/pseries/reconfig.c:parse_next_property
  - arch/powerpc/platforms/pseries/lparcfg.c:lparcfg_write
  - arch/powerpc/xmon/nonstdio.c:xmon_write
  - kernel/params.c:param_sysfs_init
  - kernel/reboot.c:reboot_setup
  - kernel/printk/printk.c:console_setup
  - kernel/module.c:find_kallsyms_symbol
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdbgetenv
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_parse_regex
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:synth_event_create
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:within_notrace_func
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_lookup
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:register_filesystem
  - fs/namespace.c:do_mount
  - fs/seq_file.c:mangle_path
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:logfc
  - fs/fs_context.c:generic_parse_monolithic
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:set_qf_name
  - security/keys/user_defined.c:logon_vet_description
  - security/selinux/hooks.c:show_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_read_token
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/lib.c:aa_split_fqname
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
  - block/blk-iocost.c:ioc_weight_write
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/parser.c:match_token
  - lib/kasprintf.c:kvasprintf_const
  - lib/string_helpers.c:string_escape_mem
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/video/fbdev/core/fb_cmdline.c:video_setup
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/base/platform.c:driver_override_store
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/usb/host/uhci-hcd.c:lprintk
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/i2c/i2c-core-of.c:i2c_of_match_device
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/md/dm-init.c:str_field_delimit
  - drivers/md/dm-ioctl.c:check_name
  - drivers/md/dm-stats.c:parse_histogram
  - drivers/of/base.c:of_modalias_node
  - drivers/of/base.c:of_find_node_opts_by_path
  - drivers/of/base.c:__of_find_node_by_full_path
  - drivers/of/device.c:of_device_get_modalias
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/of/resolver.c:of_resolve_phandles
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
c000000000ed6840-c000000000ed687c: strchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *strchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffe0008bca46)
Location: lib/string.c:409
Inline: False
Direct callers:
  - init/main.c:unknown_bootoption
  - init/do_mounts.c:mount_block_root
  - init/do_mounts_md.c:raid_setup
  - init/do_mounts_md.c:md_setup_drive
  - kernel/params.c:param_sysfs_init
  - kernel/reboot.c:reboot_setup
  - kernel/printk/printk.c:console_setup
  - kernel/module.c:find_kallsyms_symbol
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/user_namespace.c:map_write
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_parse_regex
  - kernel/bpf/inode.c:bpf_lookup
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:register_filesystem
  - fs/namespace.c:do_mount
  - fs/seq_file.c:mangle_path
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:logfc
  - fs/fs_context.c:generic_parse_monolithic
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:set_qf_name
  - security/keys/user_defined.c:logon_vet_description
  - security/selinux/hooks.c:show_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_read_token
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/lib.c:aa_split_fqname
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
  - block/blk-iocost.c:ioc_weight_write
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/parser.c:match_token
  - lib/kasprintf.c:kvasprintf_const
  - lib/string_helpers.c:string_escape_mem
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/video/fbdev/core/fb_cmdline.c:video_setup
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/base/platform.c:driver_override_store
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/usb/host/uhci-hcd.c:lprintk
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/i2c/i2c-core-of.c:i2c_of_match_device
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/md/dm-init.c:str_field_delimit
  - drivers/md/dm-ioctl.c:check_name
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/of/base.c:of_modalias_node
  - drivers/of/base.c:of_find_node_opts_by_path
  - drivers/of/base.c:__of_find_node_by_full_path
  - drivers/of/device.c:of_device_get_modalias
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/of/resolver.c:of_resolve_phandles
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_change_name
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffe0008bca46-ffffffe0008bca6e: strchr (STB_GLOBAL)
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
char *strchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a57340)
Location: lib/string.c:409
Inline: False
Direct callers:
  - init/main.c:unknown_bootoption
  - init/do_mounts.c:mount_block_root
  - init/do_mounts_md.c:raid_setup
  - init/do_mounts_md.c:md_setup_drive
  - arch/x86/xen/platform-pci-unplug.c:parse_xen_emul_unplug
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/acpi/sleep.c:acpi_sleep_setup
  - arch/x86/kernel/hpet.c:hpet_setup
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/params.c:param_sysfs_init
  - kernel/reboot.c:reboot_setup
  - kernel/printk/printk.c:console_setup
  - kernel/module.c:find_kallsyms_symbol
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdbgetenv
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_parse_regex
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:synth_event_create
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:within_notrace_func
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_lookup
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:register_filesystem
  - fs/namespace.c:do_mount
  - fs/seq_file.c:mangle_path
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:logfc
  - fs/fs_context.c:generic_parse_monolithic
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:set_qf_name
  - security/keys/user_defined.c:logon_vet_description
  - security/selinux/hooks.c:show_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_read_token
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/lib.c:aa_split_fqname
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
  - block/blk-iocost.c:ioc_weight_write
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/parser.c:match_token
  - lib/kasprintf.c:kvasprintf_const
  - lib/string_helpers.c:string_escape_mem
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/video/fbdev/core/fb_cmdline.c:video_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/base/platform.c:driver_override_store
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/usb/host/uhci-hcd.c:lprintk
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/md/dm-init.c:str_field_delimit
  - drivers/md/dm-ioctl.c:check_name
  - drivers/md/dm-stats.c:parse_histogram
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff81a57340-ffffffff81a57363: strchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *strchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a14420)
Location: lib/string.c:409
Inline: False
Direct callers:
  - init/main.c:unknown_bootoption
  - init/do_mounts.c:mount_block_root
  - init/do_mounts_md.c:raid_setup
  - init/do_mounts_md.c:md_setup_drive
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/acpi/sleep.c:acpi_sleep_setup
  - arch/x86/kernel/hpet.c:hpet_setup
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/params.c:param_sysfs_init
  - kernel/reboot.c:reboot_setup
  - kernel/printk/printk.c:console_setup
  - kernel/module.c:find_kallsyms_symbol
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdbgetenv
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_parse_regex
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:synth_event_create
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:within_notrace_func
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_lookup
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:register_filesystem
  - fs/namespace.c:do_mount
  - fs/seq_file.c:mangle_path
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:logfc
  - fs/fs_context.c:generic_parse_monolithic
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:set_qf_name
  - security/keys/user_defined.c:logon_vet_description
  - security/selinux/hooks.c:show_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_read_token
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/lib.c:aa_split_fqname
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
  - block/blk-iocost.c:ioc_weight_write
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/parser.c:match_token
  - lib/kasprintf.c:kvasprintf_const
  - lib/string_helpers.c:string_escape_mem
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/video/fbdev/core/fb_cmdline.c:video_setup
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/base/platform.c:driver_override_store
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/md/dm-init.c:str_field_delimit
  - drivers/md/dm-ioctl.c:check_name
  - drivers/md/dm-stats.c:parse_histogram
  - drivers/hv/vmbus_drv.c:driver_override_store
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff81a14420-ffffffff81a14443: strchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *strchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81ac3730)
Location: lib/string.c:409
Inline: False
Direct callers:
  - init/main.c:unknown_bootoption
  - init/do_mounts.c:mount_block_root
  - init/do_mounts_md.c:raid_setup
  - init/do_mounts_md.c:md_setup_drive
  - arch/x86/xen/platform-pci-unplug.c:parse_xen_emul_unplug
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/acpi/sleep.c:acpi_sleep_setup
  - arch/x86/kernel/hpet.c:hpet_setup
  - kernel/params.c:param_sysfs_init
  - kernel/reboot.c:reboot_setup
  - kernel/printk/printk.c:console_setup
  - kernel/module.c:find_kallsyms_symbol
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdbgetenv
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_parse_regex
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:synth_event_create
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:within_notrace_func
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_lookup
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:register_filesystem
  - fs/namespace.c:do_mount
  - fs/seq_file.c:mangle_path
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:logfc
  - fs/fs_context.c:generic_parse_monolithic
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:set_qf_name
  - security/keys/user_defined.c:logon_vet_description
  - security/selinux/hooks.c:show_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_read_token
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/lib.c:aa_split_fqname
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
  - block/blk-iocost.c:ioc_weight_write
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/parser.c:match_token
  - lib/kasprintf.c:kvasprintf_const
  - lib/string_helpers.c:string_escape_mem
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/video/fbdev/core/fb_cmdline.c:video_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/base/platform.c:driver_override_store
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/usb/host/uhci-hcd.c:lprintk
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/md/dm-ioctl.c:check_name
  - drivers/md/dm-stats.c:parse_histogram
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff81ac3730-ffffffff81ac3753: strchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *strchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81acfc00)
Location: lib/string.c:409
Inline: False
Direct callers:
  - init/main.c:unknown_bootoption
  - init/do_mounts.c:mount_block_root
  - init/do_mounts_md.c:raid_setup
  - init/do_mounts_md.c:md_setup_drive
  - arch/x86/xen/platform-pci-unplug.c:parse_xen_emul_unplug
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/acpi/sleep.c:acpi_sleep_setup
  - arch/x86/kernel/hpet.c:hpet_setup
  - arch/x86/platform/uv/uv_nmi.c:param_set_action
  - kernel/params.c:param_sysfs_init
  - kernel/reboot.c:reboot_setup
  - kernel/printk/printk.c:console_setup
  - kernel/module.c:find_kallsyms_symbol
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdbgetenv
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_filter.c:filter_assign_type
  - kernel/trace/trace_events_filter.c:filter_parse_regex
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:synth_event_create
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:within_notrace_func
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_dynevent.c:dyn_event_release
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:find_fetch_type
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_lookup
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - fs/filesystems.c:get_fs_type
  - fs/filesystems.c:register_filesystem
  - fs/namespace.c:do_mount
  - fs/seq_file.c:mangle_path
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:logfc
  - fs/fs_context.c:generic_parse_monolithic
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:set_qf_name
  - security/keys/user_defined.c:logon_vet_description
  - security/selinux/hooks.c:show_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/tomoyo/common.c:tomoyo_parse_policy
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/network.c:tomoyo_parse_ipaddr_union
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_path_matches_pattern2
  - security/tomoyo/util.c:tomoyo_read_token
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/apparmorfs.c:mangle_name
  - security/apparmor/lib.c:aa_split_fqname
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
  - block/blk-iocost.c:ioc_weight_write
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/parser.c:match_token
  - lib/kasprintf.c:kvasprintf_const
  - lib/string_helpers.c:string_escape_mem
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/video/fbdev/core/fb_cmdline.c:video_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/base/platform.c:driver_override_store
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/usb/host/uhci-hcd.c:lprintk
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/md/dm-init.c:str_field_delimit
  - drivers/md/dm-ioctl.c:check_name
  - drivers/md/dm-stats.c:parse_histogram
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:netpoll_parse_ip_addr
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff81acfc00-ffffffff81acfc23: strchr (STB_GLOBAL)
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
