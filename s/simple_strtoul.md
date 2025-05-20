# Function: <code>simple_strtoul</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int simple_strtoul(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff813f2710)
Location: lib/vsprintf.c:75
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
Direct callers:
  - init/do_mounts.c:root_delay_setup
  - init/do_mounts.c:name_to_dev_t
  - init/do_mounts.c:name_to_dev_t
  - init/initramfs.c:parse_header
  - init/calibrate.c:lpj_setup
  - arch/x86/entry/vdso/vma.c:vdso_setup
  - arch/x86/entry/vdso/vdso32-setup.c:vdso32_setup
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_spare_reg
  - arch/x86/kernel/early_printk.c:early_serial_init
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/fork.c:coredump_filter_setup
  - kernel/sysctl_binary.c:bin_intvec
  - kernel/sysctl_binary.c:bin_ulongvec
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_write
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_main.c:kdbgetulenv
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdbgetularg
  - kernel/debug/kdb/kdb_main.c:kdbgetularg
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/watchdog.c:softlockup_panic_setup
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - mm/page_alloc.c:set_hashdist
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - fs/dcache.c:set_dhash_entries
  - fs/inode.c:set_ihash_entries
  - fs/namespace.c:set_mhash_entries
  - fs/namespace.c:set_mphash_entries
  - fs/ext4/super.c:ext4_fill_super
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - block/cfq-iosched.c:cfq_low_latency_store
  - block/cfq-iosched.c:cfq_slice_async_rq_store
  - block/cfq-iosched.c:cfq_back_seek_penalty_store
  - block/cfq-iosched.c:cfq_back_seek_max_store
  - block/cfq-iosched.c:cfq_quantum_store
  - block/cfq-iosched.c:cfq_target_latency_store
  - block/cfq-iosched.c:cfq_group_idle_store
  - block/cfq-iosched.c:cfq_slice_idle_store
  - block/cfq-iosched.c:cfq_slice_async_store
  - block/cfq-iosched.c:cfq_slice_sync_store
  - block/cfq-iosched.c:cfq_fifo_expire_async_store
  - block/cfq-iosched.c:cfq_fifo_expire_sync_store
  - block/blk-integrity.c:integrity_generate_store
  - block/blk-integrity.c:integrity_verify_store
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/swiotlb.c:setup_io_tlb_npages
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/video/console/fbcon.c:fb_console_setup
  - drivers/video/console/fbcon.c:fb_console_setup
  - drivers/video/console/fbcon.c:fb_console_setup
  - drivers/video/console/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/sysfs.c:counter_set
  - drivers/xen/xenbus/xenbus_xs.c:find_watch
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/tty/tty_io.c:tty_find_polling_driver
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/serial/serial_core.c:uart_parse_options
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/base/core.c:device_store_ulong
  - drivers/base/platform.c:early_platform_driver_register
  - drivers/base/devtmpfs.c:mount_param
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_depth
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/sd.c:manage_start_stop_store
  - drivers/scsi/sd.c:allow_restart_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/net/xen-netfront.c:store_rxbuf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/rtc/rtc-sysfs.c:max_user_freq_store
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff813f2710-ffffffff813f271b: simple_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int simple_strtoul(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8143b083)
Location: lib/vsprintf.c:81
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
Direct callers:
  - init/do_mounts.c:root_delay_setup
  - init/do_mounts.c:name_to_dev_t
  - init/do_mounts.c:name_to_dev_t
  - init/initramfs.c:parse_header
  - init/calibrate.c:lpj_setup
  - arch/x86/entry/vdso/vma.c:vdso_setup
  - arch/x86/entry/vdso/vdso32-setup.c:vdso32_setup
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_spare_reg
  - arch/x86/kernel/early_printk.c:early_serial_init
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/fork.c:coredump_filter_setup
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/sysctl_binary.c:bin_ulongvec
  - kernel/sysctl_binary.c:bin_intvec
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_write
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_main.c:kdbgetularg
  - kernel/debug/kdb/kdb_main.c:kdbgetularg
  - kernel/debug/kdb/kdb_main.c:kdbgetulenv
  - kernel/watchdog.c:softlockup_panic_setup
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - mm/page_alloc.c:set_hashdist
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - fs/dcache.c:set_dhash_entries
  - fs/inode.c:set_ihash_entries
  - fs/namespace.c:set_mphash_entries
  - fs/namespace.c:set_mhash_entries
  - fs/ext4/super.c:ext4_fill_super
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - block/cfq-iosched.c:cfq_target_latency_us_store
  - block/cfq-iosched.c:cfq_slice_async_us_store
  - block/cfq-iosched.c:cfq_slice_sync_us_store
  - block/cfq-iosched.c:cfq_group_idle_us_store
  - block/cfq-iosched.c:cfq_slice_idle_us_store
  - block/cfq-iosched.c:cfq_target_latency_store
  - block/cfq-iosched.c:cfq_low_latency_store
  - block/cfq-iosched.c:cfq_slice_async_rq_store
  - block/cfq-iosched.c:cfq_slice_async_store
  - block/cfq-iosched.c:cfq_slice_sync_store
  - block/cfq-iosched.c:cfq_group_idle_store
  - block/cfq-iosched.c:cfq_slice_idle_store
  - block/cfq-iosched.c:cfq_back_seek_penalty_store
  - block/cfq-iosched.c:cfq_back_seek_max_store
  - block/cfq-iosched.c:cfq_fifo_expire_async_store
  - block/cfq-iosched.c:cfq_fifo_expire_sync_store
  - block/cfq-iosched.c:cfq_quantum_store
  - block/blk-integrity.c:integrity_generate_store
  - block/blk-integrity.c:integrity_verify_store
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/swiotlb.c:setup_io_tlb_npages
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/video/console/fbcon.c:fb_console_setup
  - drivers/video/console/fbcon.c:fb_console_setup
  - drivers/video/console/fbcon.c:fb_console_setup
  - drivers/video/console/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/sysfs.c:counter_set
  - drivers/xen/xenbus/xenbus_xs.c:find_watch
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/tty/tty_io.c:tty_find_polling_driver
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/serial/serial_core.c:uart_parse_options
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/base/core.c:device_store_ulong
  - drivers/base/platform.c:early_platform_driver_register
  - drivers/base/devtmpfs.c:mount_param
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_depth
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/sd.c:allow_restart_store
  - drivers/scsi/sd.c:manage_start_stop_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/net/xen-netfront.c:store_rxbuf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff814393b0-ffffffff814393bb: simple_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long unsigned int simple_strtoul(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81458057)
Location: lib/vsprintf.c:81
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
Direct callers:
  - init/do_mounts.c:root_delay_setup
  - init/do_mounts.c:name_to_dev_t
  - init/do_mounts.c:name_to_dev_t
  - init/initramfs.c:parse_header
  - init/calibrate.c:lpj_setup
  - arch/x86/entry/vdso/vma.c:vdso_setup
  - arch/x86/entry/vdso/vdso32-setup.c:vdso32_setup
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_spare_reg
  - arch/x86/kernel/early_printk.c:early_serial_init
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/fork.c:coredump_filter_setup
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/sysctl_binary.c:bin_ulongvec
  - kernel/sysctl_binary.c:bin_intvec
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_write
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_main.c:kdbgetularg
  - kernel/debug/kdb/kdb_main.c:kdbgetularg
  - kernel/debug/kdb/kdb_main.c:kdbgetulenv
  - kernel/watchdog.c:softlockup_panic_setup
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - mm/page_alloc.c:set_hashdist
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - fs/dcache.c:set_dhash_entries
  - fs/inode.c:set_ihash_entries
  - fs/namespace.c:set_mphash_entries
  - fs/namespace.c:set_mhash_entries
  - fs/ext4/super.c:ext4_fill_super
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - block/cfq-iosched.c:cfq_target_latency_us_store
  - block/cfq-iosched.c:cfq_slice_async_us_store
  - block/cfq-iosched.c:cfq_slice_sync_us_store
  - block/cfq-iosched.c:cfq_group_idle_us_store
  - block/cfq-iosched.c:cfq_slice_idle_us_store
  - block/cfq-iosched.c:cfq_target_latency_store
  - block/cfq-iosched.c:cfq_low_latency_store
  - block/cfq-iosched.c:cfq_slice_async_rq_store
  - block/cfq-iosched.c:cfq_slice_async_store
  - block/cfq-iosched.c:cfq_slice_sync_store
  - block/cfq-iosched.c:cfq_group_idle_store
  - block/cfq-iosched.c:cfq_slice_idle_store
  - block/cfq-iosched.c:cfq_back_seek_penalty_store
  - block/cfq-iosched.c:cfq_back_seek_max_store
  - block/cfq-iosched.c:cfq_fifo_expire_async_store
  - block/cfq-iosched.c:cfq_fifo_expire_sync_store
  - block/cfq-iosched.c:cfq_quantum_store
  - block/blk-integrity.c:integrity_generate_store
  - block/blk-integrity.c:integrity_verify_store
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/swiotlb.c:setup_io_tlb_npages
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/video/console/fbcon.c:fb_console_setup
  - drivers/video/console/fbcon.c:fb_console_setup
  - drivers/video/console/fbcon.c:fb_console_setup
  - drivers/video/console/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/sysfs.c:counter_set
  - drivers/xen/xenbus/xenbus_xs.c:find_watch
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/tty/tty_io.c:tty_find_polling_driver
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/serial/serial_core.c:uart_parse_options
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/base/core.c:device_store_ulong
  - drivers/base/platform.c:early_platform_driver_register
  - drivers/base/devtmpfs.c:mount_param
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_depth
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/sd.c:allow_restart_store
  - drivers/scsi/sd.c:manage_start_stop_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/net/xen-netfront.c:store_rxbuf
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff81456390-ffffffff8145639b: simple_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int simple_strtoul(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff818f9b91)
Location: lib/vsprintf.c:82
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
Direct callers:
  - init/do_mounts.c:root_delay_setup
  - init/initramfs.c:parse_header
  - init/calibrate.c:lpj_setup
  - arch/x86/entry/vdso/vma.c:vdso_setup
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/early_printk.c:early_serial_init
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/fork.c:coredump_filter_setup
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/sysctl_binary.c:bin_ulongvec
  - kernel/sysctl_binary.c:bin_intvec
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_write
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_main.c:kdbgetularg
  - kernel/debug/kdb/kdb_main.c:kdbgetularg
  - kernel/debug/kdb/kdb_main.c:kdbgetulenv
  - kernel/watchdog.c:softlockup_panic_setup
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - mm/page_alloc.c:set_hashdist
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/mmap.c:cmdline_parse_stack_guard_gap
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - fs/dcache.c:set_dhash_entries
  - fs/inode.c:set_ihash_entries
  - fs/namespace.c:set_mphash_entries
  - fs/namespace.c:set_mhash_entries
  - fs/ext4/super.c:ext4_fill_super
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - block/cfq-iosched.c:cfq_target_latency_us_store
  - block/cfq-iosched.c:cfq_slice_async_us_store
  - block/cfq-iosched.c:cfq_slice_sync_us_store
  - block/cfq-iosched.c:cfq_group_idle_us_store
  - block/cfq-iosched.c:cfq_slice_idle_us_store
  - block/cfq-iosched.c:cfq_target_latency_store
  - block/cfq-iosched.c:cfq_low_latency_store
  - block/cfq-iosched.c:cfq_slice_async_rq_store
  - block/cfq-iosched.c:cfq_slice_async_store
  - block/cfq-iosched.c:cfq_slice_sync_store
  - block/cfq-iosched.c:cfq_group_idle_store
  - block/cfq-iosched.c:cfq_slice_idle_store
  - block/cfq-iosched.c:cfq_back_seek_penalty_store
  - block/cfq-iosched.c:cfq_back_seek_max_store
  - block/cfq-iosched.c:cfq_fifo_expire_async_store
  - block/cfq-iosched.c:cfq_fifo_expire_sync_store
  - block/cfq-iosched.c:cfq_quantum_store
  - block/blk-integrity.c:integrity_generate_store
  - block/blk-integrity.c:integrity_verify_store
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/swiotlb.c:setup_io_tlb_npages
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/video/console/fbcon.c:fb_console_setup
  - drivers/video/console/fbcon.c:fb_console_setup
  - drivers/video/console/fbcon.c:fb_console_setup
  - drivers/video/console/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/acpi/sysfs.c:counter_set
  - drivers/xen/xenbus/xenbus_xs.c:find_watch
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/tty/tty_io.c:tty_find_polling_driver
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/serial/serial_core.c:uart_parse_options
  - drivers/base/core.c:device_store_ulong
  - drivers/base/platform.c:early_platform_driver_register
  - drivers/base/devtmpfs.c:mount_param
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_depth
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/sd.c:allow_restart_store
  - drivers/scsi/sd.c:manage_start_stop_store
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/net/xen-netfront.c:store_rxbuf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_poll_msec_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_panic_on_ue_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ce_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ue_store
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff818f7c70-ffffffff818f7c7b: simple_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int simple_strtoul(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8198080f)
Location: lib/vsprintf.c:84
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
Direct callers:
  - init/do_mounts.c:root_delay_setup
  - init/initramfs.c:parse_header
  - init/calibrate.c:lpj_setup
  - arch/x86/entry/vdso/vma.c:vdso_setup
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/early_printk.c:early_serial_init
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/fork.c:coredump_filter_setup
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/sysctl_binary.c:bin_ulongvec
  - kernel/sysctl_binary.c:bin_intvec
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_write
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_main.c:kdbgetularg
  - kernel/debug/kdb/kdb_main.c:kdbgetularg
  - kernel/debug/kdb/kdb_main.c:kdbgetulenv
  - kernel/watchdog.c:softlockup_panic_setup
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - mm/page_alloc.c:set_hashdist
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/mmap.c:cmdline_parse_stack_guard_gap
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - fs/dcache.c:set_dhash_entries
  - fs/inode.c:set_ihash_entries
  - fs/namespace.c:set_mphash_entries
  - fs/namespace.c:set_mhash_entries
  - fs/ext4/super.c:ext4_fill_super
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - block/cfq-iosched.c:cfq_target_latency_us_store
  - block/cfq-iosched.c:cfq_slice_async_us_store
  - block/cfq-iosched.c:cfq_slice_sync_us_store
  - block/cfq-iosched.c:cfq_group_idle_us_store
  - block/cfq-iosched.c:cfq_slice_idle_us_store
  - block/cfq-iosched.c:cfq_target_latency_store
  - block/cfq-iosched.c:cfq_low_latency_store
  - block/cfq-iosched.c:cfq_slice_async_rq_store
  - block/cfq-iosched.c:cfq_slice_async_store
  - block/cfq-iosched.c:cfq_slice_sync_store
  - block/cfq-iosched.c:cfq_group_idle_store
  - block/cfq-iosched.c:cfq_slice_idle_store
  - block/cfq-iosched.c:cfq_back_seek_penalty_store
  - block/cfq-iosched.c:cfq_back_seek_max_store
  - block/cfq-iosched.c:cfq_fifo_expire_async_store
  - block/cfq-iosched.c:cfq_fifo_expire_sync_store
  - block/cfq-iosched.c:cfq_quantum_store
  - block/blk-integrity.c:integrity_generate_store
  - block/blk-integrity.c:integrity_verify_store
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/swiotlb.c:setup_io_tlb_npages
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_sleep
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbhistry.c:acpi_db_get_from_history
  - drivers/acpi/acpica/dbmethod.c:acpi_db_disassemble_aml
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_breakpoint
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_references
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/xen/xenbus/xenbus_xs.c:find_watch
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/tty/tty_io.c:tty_find_polling_driver
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/serial/serial_core.c:uart_parse_options
  - drivers/base/core.c:device_store_ulong
  - drivers/base/platform.c:early_platform_driver_register
  - drivers/base/devtmpfs.c:mount_param
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_depth
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/net/xen-netfront.c:store_rxbuf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_poll_msec_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_panic_on_ue_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ce_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ue_store
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff8197e6f0-ffffffff8197e6fb: simple_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long unsigned int simple_strtoul(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff819dc788)
Location: lib/vsprintf.c:83
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
Direct callers:
  - init/do_mounts.c:root_delay_setup
  - init/initramfs.c:parse_header
  - init/calibrate.c:lpj_setup
  - arch/x86/entry/vdso/vma.c:vdso_setup
  - arch/x86/entry/vdso/vdso32-setup.c:vdso32_setup
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_spare_reg
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:early_serial_init
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/fork.c:coredump_filter_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_write
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_main.c:kdbgetularg
  - kernel/debug/kdb/kdb_main.c:kdbgetularg
  - kernel/debug/kdb/kdb_main.c:kdbgetulenv
  - kernel/watchdog.c:softlockup_panic_setup
  - kernel/trace/ftrace.c:set_graph_max_depth_function
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - mm/page_alloc.c:set_hashdist
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/mmap.c:cmdline_parse_stack_guard_gap
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - fs/dcache.c:set_dhash_entries
  - fs/inode.c:set_ihash_entries
  - fs/namespace.c:set_mphash_entries
  - fs/namespace.c:set_mhash_entries
  - fs/ext4/super.c:ext4_fill_super
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - block/cfq-iosched.c:cfq_target_latency_us_store
  - block/cfq-iosched.c:cfq_slice_async_us_store
  - block/cfq-iosched.c:cfq_slice_sync_us_store
  - block/cfq-iosched.c:cfq_group_idle_us_store
  - block/cfq-iosched.c:cfq_slice_idle_us_store
  - block/cfq-iosched.c:cfq_target_latency_store
  - block/cfq-iosched.c:cfq_low_latency_store
  - block/cfq-iosched.c:cfq_slice_async_rq_store
  - block/cfq-iosched.c:cfq_slice_async_store
  - block/cfq-iosched.c:cfq_slice_sync_store
  - block/cfq-iosched.c:cfq_group_idle_store
  - block/cfq-iosched.c:cfq_slice_idle_store
  - block/cfq-iosched.c:cfq_back_seek_penalty_store
  - block/cfq-iosched.c:cfq_back_seek_max_store
  - block/cfq-iosched.c:cfq_fifo_expire_async_store
  - block/cfq-iosched.c:cfq_fifo_expire_sync_store
  - block/cfq-iosched.c:cfq_quantum_store
  - block/blk-integrity.c:integrity_generate_store
  - block/blk-integrity.c:integrity_verify_store
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_sleep
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbhistry.c:acpi_db_get_from_history
  - drivers/acpi/acpica/dbmethod.c:acpi_db_disassemble_aml
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_breakpoint
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_references
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/xen/xenbus/xenbus_xs.c:find_watch
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/tty/tty_io.c:tty_find_polling_driver
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/serial/serial_core.c:uart_parse_options
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/base/core.c:device_store_ulong
  - drivers/base/platform.c:early_platform_driver_register
  - drivers/base/devtmpfs.c:mount_param
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_depth
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/net/xen-netfront.c:store_rxbuf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_poll_msec_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_panic_on_ue_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ce_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ue_store
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff819dac20-ffffffff819dac2b: simple_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long unsigned int simple_strtoul(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a14c77)
Location: lib/vsprintf.c:84
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
Direct callers:
  - init/do_mounts.c:root_delay_setup
  - init/initramfs.c:parse_header
  - init/calibrate.c:lpj_setup
  - arch/x86/entry/vdso/vma.c:vdso_setup
  - arch/x86/entry/vdso/vdso32-setup.c:vdso32_setup
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_spare_reg
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:early_serial_init
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/fork.c:coredump_filter_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_write
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_main.c:kdbgetularg
  - kernel/debug/kdb/kdb_main.c:kdbgetularg
  - kernel/debug/kdb/kdb_main.c:kdbgetulenv
  - kernel/watchdog.c:softlockup_panic_setup
  - kernel/trace/ftrace.c:set_graph_max_depth_function
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - mm/page_alloc.c:set_hashdist
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/mmap.c:cmdline_parse_stack_guard_gap
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - fs/dcache.c:set_dhash_entries
  - fs/inode.c:set_ihash_entries
  - fs/namespace.c:set_mphash_entries
  - fs/namespace.c:set_mhash_entries
  - fs/ext4/super.c:ext4_fill_super
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - block/blk-integrity.c:integrity_generate_store
  - block/blk-integrity.c:integrity_verify_store
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_sleep
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbhistry.c:acpi_db_get_from_history
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_breakpoint
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_references
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/xen/xenbus/xenbus_xs.c:find_watch
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/tty/tty_io.c:tty_find_polling_driver
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/serial/serial_core.c:uart_parse_options
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/base/platform.c:early_platform_driver_register
  - drivers/base/devtmpfs.c:mount_param
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_depth
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/net/xen-netfront.c:store_rxbuf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_poll_msec_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_panic_on_ue_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ce_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ue_store
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff81a12ec0-ffffffff81a12ecb: simple_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long unsigned int simple_strtoul(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a82320)
Location: lib/vsprintf.c:86
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
Direct callers:
  - init/do_mounts.c:root_delay_setup
  - init/initramfs.c:parse_header
  - init/calibrate.c:lpj_setup
  - arch/x86/entry/vdso/vma.c:vdso_setup
  - arch/x86/entry/vdso/vdso32-setup.c:vdso32_setup
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_spare_reg
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:early_serial_init
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/fork.c:coredump_filter_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_write
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_main.c:kdbgetularg
  - kernel/debug/kdb/kdb_main.c:kdbgetularg
  - kernel/debug/kdb/kdb_main.c:kdbgetulenv
  - kernel/watchdog.c:softlockup_panic_setup
  - kernel/trace/ftrace.c:set_graph_max_depth_function
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/mmap.c:cmdline_parse_stack_guard_gap
  - mm/page_alloc.c:set_hashdist
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - fs/dcache.c:set_dhash_entries
  - fs/inode.c:set_ihash_entries
  - fs/namespace.c:set_mphash_entries
  - fs/namespace.c:set_mhash_entries
  - fs/ext4/super.c:ext4_fill_super
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - block/blk-integrity.c:integrity_generate_store
  - block/blk-integrity.c:integrity_verify_store
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_sleep
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbhistry.c:acpi_db_get_from_history
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_breakpoint
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_references
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/xen/xenbus/xenbus_xs.c:find_watch
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/tty/tty_io.c:tty_find_polling_driver
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/serial/serial_core.c:uart_parse_options
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/base/platform.c:early_platform_driver_register
  - drivers/base/devtmpfs.c:mount_param
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_depth
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/net/xen-netfront.c:store_rxbuf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_poll_msec_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_panic_on_ue_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ce_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ue_store
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff81a82320-ffffffff81a8232b: simple_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int simple_strtoul(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ab9530)
Location: lib/vsprintf.c:86
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
Direct callers:
  - init/do_mounts.c:root_delay_setup
  - init/initramfs.c:parse_header
  - init/calibrate.c:lpj_setup
  - arch/x86/entry/vdso/vma.c:vdso_setup
  - arch/x86/entry/vdso/vdso32-setup.c:vdso32_setup
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_spare_reg
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:early_serial_init
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/fork.c:coredump_filter_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_write
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_main.c:kdbgetularg
  - kernel/debug/kdb/kdb_main.c:kdbgetularg
  - kernel/debug/kdb/kdb_main.c:kdbgetulenv
  - kernel/watchdog.c:softlockup_panic_setup
  - kernel/trace/ftrace.c:set_graph_max_depth_function
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - mm/mmap.c:cmdline_parse_stack_guard_gap
  - mm/page_alloc.c:set_hashdist
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - fs/dcache.c:set_dhash_entries
  - fs/inode.c:set_ihash_entries
  - fs/namespace.c:set_mphash_entries
  - fs/namespace.c:set_mhash_entries
  - fs/ext4/super.c:ext4_fill_super
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - block/blk-integrity.c:integrity_generate_store
  - block/blk-integrity.c:integrity_verify_store
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_sleep
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbhistry.c:acpi_db_get_from_history
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_breakpoint
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_references
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/xen/xenbus/xenbus_xs.c:find_watch
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/tty/tty_io.c:tty_find_polling_driver
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/serial/serial_core.c:uart_parse_options
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/base/platform.c:early_platform_driver_register
  - drivers/base/devtmpfs.c:mount_param
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_depth
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/net/xen-netfront.c:store_rxbuf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_poll_msec_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_panic_on_ue_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ce_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ue_store
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff81ab9530-ffffffff81ab953b: simple_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int simple_strtoul(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815f71f2)
Location: lib/vsprintf.c:89
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
Direct callers:
  - init/do_mounts.c:root_delay_setup
  - init/initramfs.c:parse_header
  - init/calibrate.c:lpj_setup
  - arch/x86/entry/vdso/vma.c:vdso_setup
  - arch/x86/entry/vdso/vdso32-setup.c:vdso32_setup
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_spare_reg
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_serial_init
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/fork.c:coredump_filter_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_write
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/trace/ftrace.c:set_graph_max_depth_function
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - mm/mmap.c:cmdline_parse_stack_guard_gap
  - mm/page_alloc.c:set_hashdist
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - fs/dcache.c:set_dhash_entries
  - fs/inode.c:set_ihash_entries
  - fs/namespace.c:set_mphash_entries
  - fs/namespace.c:set_mhash_entries
  - fs/ext4/super.c:ext4_fill_super
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - block/blk-integrity.c:integrity_generate_store
  - block/blk-integrity.c:integrity_verify_store
  - lib/parser.c:match_one
  - lib/parser.c:match_one
  - lib/parser.c:match_one
  - lib/parser.c:match_one
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_in_ignore_list
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_sleep
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbhistry.c:acpi_db_get_from_history
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_breakpoint
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_references
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/tty/tty_io.c:tty_find_polling_driver
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/serial/serial_core.c:uart_parse_options
  - drivers/base/devtmpfs.c:mount_param
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_depth
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-sata.c:ata_scsi_activity_store
  - drivers/net/xen-netfront.c:store_rxbuf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_poll_msec_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_panic_on_ue_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ce_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ue_store
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff815f4a90-ffffffff815f4afd: simple_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long unsigned int simple_strtoul(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8161b605)
Location: lib/vsprintf.c:89
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
Direct callers:
  - init/do_mounts.c:root_delay_setup
  - init/do_mounts.c:devt_from_devnum
  - init/do_mounts.c:devt_from_devname
  - init/initramfs.c:parse_header
  - init/calibrate.c:lpj_setup
  - arch/x86/entry/vdso/vma.c:vdso_setup
  - arch/x86/entry/vdso/vdso32-setup.c:vdso32_setup
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_spare_reg
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_serial_init
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/fork.c:coredump_filter_setup
  - kernel/reboot.c:reboot_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_write
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/trace/ftrace.c:set_graph_max_depth_function
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - mm/mmap.c:cmdline_parse_stack_guard_gap
  - mm/page_alloc.c:set_hashdist
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - fs/dcache.c:set_dhash_entries
  - fs/inode.c:set_ihash_entries
  - fs/namespace.c:set_mphash_entries
  - fs/namespace.c:set_mhash_entries
  - fs/ext4/super.c:ext4_fill_super
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - block/blk-integrity.c:integrity_generate_store
  - block/blk-integrity.c:integrity_verify_store
  - lib/parser.c:match_one
  - lib/parser.c:match_one
  - lib/parser.c:match_one
  - lib/parser.c:match_one
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_in_ignore_list
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_sleep
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbhistry.c:acpi_db_get_from_history
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_breakpoint
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_references
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/tty/tty_io.c:tty_find_polling_driver
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/serial/serial_core.c:uart_parse_options
  - drivers/base/devtmpfs.c:mount_param
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_depth
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-sata.c:ata_scsi_activity_store
  - drivers/net/xen-netfront.c:store_rxbuf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_poll_msec_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_panic_on_ue_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ce_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ue_store
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff81619100-ffffffff8161916d: simple_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int simple_strtoul(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815fd0d0)
Location: lib/vsprintf.c:103
Inline: True
Direct callers:
  - init/do_mounts.c:root_delay_setup
  - init/do_mounts.c:devt_from_devname
  - init/initramfs.c:parse_header
  - init/calibrate.c:lpj_setup
  - arch/x86/entry/vdso/vma.c:vdso_setup
  - arch/x86/entry/vdso/vdso32-setup.c:vdso32_setup
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_spare_reg
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_serial_init
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/fork.c:coredump_filter_setup
  - kernel/reboot.c:reboot_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_write
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/trace/ftrace.c:set_graph_max_depth_function
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - mm/mmap.c:cmdline_parse_stack_guard_gap
  - mm/page_alloc.c:set_hashdist
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - fs/dcache.c:set_dhash_entries
  - fs/inode.c:set_ihash_entries
  - fs/namespace.c:set_mphash_entries
  - fs/namespace.c:set_mhash_entries
  - fs/ext4/super.c:ext4_fill_super
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - block/blk-integrity.c:integrity_generate_store
  - block/blk-integrity.c:integrity_verify_store
  - lib/parser.c:match_one
  - lib/parser.c:match_one
  - lib/parser.c:match_one
  - lib/parser.c:match_one
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_in_ignore_list
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_sleep
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbhistry.c:acpi_db_get_from_history
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_breakpoint
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_references
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/tty/tty_io.c:tty_find_polling_driver
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/serial/serial_core.c:uart_parse_options
  - drivers/base/devtmpfs.c:mount_param
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_depth
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-sata.c:ata_scsi_activity_store
  - drivers/net/xen-netfront.c:store_rxbuf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_poll_msec_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_panic_on_ue_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ce_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ue_store
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff815fd0d0-ffffffff815fd16b: simple_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int simple_strtoul(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8166ad60)
Location: lib/vsprintf.c:104
Inline: True
Direct callers:
  - init/do_mounts.c:root_delay_setup
  - init/do_mounts.c:devt_from_devname
  - init/initramfs.c:parse_header
  - init/calibrate.c:lpj_setup
  - arch/x86/entry/vdso/vma.c:vdso_setup
  - arch/x86/entry/vdso/vdso32-setup.c:vdso32_setup
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_spare_reg
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_serial_init
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/fork.c:coredump_filter_setup
  - kernel/reboot.c:reboot_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_write
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/trace/ftrace.c:set_graph_max_depth_function
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - mm/mmap.c:cmdline_parse_stack_guard_gap
  - mm/page_alloc.c:set_hashdist
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - fs/dcache.c:set_dhash_entries
  - fs/inode.c:set_ihash_entries
  - fs/namespace.c:set_mphash_entries
  - fs/namespace.c:set_mhash_entries
  - fs/ext4/super.c:ext4_fill_super
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - block/blk-integrity.c:integrity_generate_store
  - block/blk-integrity.c:integrity_verify_store
  - lib/parser.c:match_one
  - lib/parser.c:match_one
  - lib/parser.c:match_one
  - lib/parser.c:match_one
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_in_ignore_list
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_sleep
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbhistry.c:acpi_db_get_from_history
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_breakpoint
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_references
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/tty/tty_io.c:tty_find_polling_driver
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/serial/serial_core.c:uart_parse_options
  - drivers/base/devtmpfs.c:mount_param
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_depth
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-sata.c:ata_scsi_activity_store
  - drivers/net/xen-netfront.c:store_rxbuf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_poll_msec_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_panic_on_ue_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ce_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ue_store
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff8166ad60-ffffffff8166ad6b: simple_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long unsigned int simple_strtoul(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81783570)
Location: lib/vsprintf.c:108
Inline: True
Direct callers:
  - init/do_mounts.c:root_delay_setup
  - init/do_mounts.c:devt_from_devname
  - init/initramfs.c:parse_header
  - init/calibrate.c:lpj_setup
  - arch/x86/entry/vdso/vma.c:vdso_setup
  - arch/x86/entry/vdso/vdso32-setup.c:vdso32_setup
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_spare_reg
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_serial_init
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/fork.c:coredump_filter_setup
  - kernel/reboot.c:reboot_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_write
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_main.c:kdbgetulenv
  - kernel/trace/ftrace.c:set_graph_max_depth_function
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - mm/mmap.c:cmdline_parse_stack_guard_gap
  - mm/page_alloc.c:set_hashdist
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - fs/dcache.c:set_dhash_entries
  - fs/inode.c:set_ihash_entries
  - fs/namespace.c:set_mphash_entries
  - fs/namespace.c:set_mhash_entries
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - block/blk-integrity.c:integrity_generate_store
  - block/blk-integrity.c:integrity_verify_store
  - lib/parser.c:match_one
  - lib/parser.c:match_one
  - lib/parser.c:match_one
  - lib/parser.c:match_one
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_in_ignore_list
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_sleep
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbhistry.c:acpi_db_get_from_history
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_breakpoint
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_references
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/tty/tty_io.c:tty_find_polling_driver
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/serial/serial_core.c:uart_parse_options
  - drivers/base/devtmpfs.c:mount_param
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_depth
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-sata.c:ata_scsi_activity_store
  - drivers/net/xen-netfront.c:store_rxbuf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:bitmap_store
  - drivers/md/md.c:bitmap_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_poll_msec_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_panic_on_ue_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ce_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ue_store
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff81783570-ffffffff81783585: simple_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int simple_strtoul(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff82040590)
Location: lib/vsprintf.c:109
Inline: True
Direct callers:
  - init/do_mounts.c:root_delay_setup
  - init/do_mounts.c:devt_from_devname
  - init/initramfs.c:parse_header
  - init/calibrate.c:lpj_setup
  - arch/x86/entry/vdso/vma.c:vdso_setup
  - arch/x86/entry/vdso/vdso32-setup.c:vdso32_setup
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_spare_reg
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_serial_init
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/fork.c:coredump_filter_setup
  - kernel/reboot.c:reboot_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_write
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_main.c:kdbgetulenv
  - kernel/trace/ftrace.c:set_graph_max_depth_function
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - mm/mmap.c:cmdline_parse_stack_guard_gap
  - mm/page_alloc.c:set_hashdist
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - fs/dcache.c:set_dhash_entries
  - fs/inode.c:set_ihash_entries
  - fs/namespace.c:set_mphash_entries
  - fs/namespace.c:set_mhash_entries
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - block/blk-integrity.c:integrity_generate_store
  - block/blk-integrity.c:integrity_verify_store
  - lib/parser.c:match_one
  - lib/parser.c:match_one
  - lib/parser.c:match_one
  - lib/parser.c:match_one
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_in_ignore_list
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_sleep
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbhistry.c:acpi_db_get_from_history
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_breakpoint
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_references
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/tty/tty_io.c:tty_find_polling_driver
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/serial/serial_core.c:uart_parse_options
  - drivers/base/devtmpfs.c:mount_param
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_depth
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-sata.c:ata_scsi_activity_store
  - drivers/net/xen-netfront.c:store_rxbuf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:bitmap_store
  - drivers/md/md.c:bitmap_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_poll_msec_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_panic_on_ue_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ce_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ue_store
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff82040590-ffffffff820405a5: simple_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int simple_strtoul(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff820bea90)
Location: lib/vsprintf.c:109
Inline: True
Direct callers:
  - init/do_mounts.c:root_delay_setup
  - init/initramfs.c:parse_header
  - init/calibrate.c:lpj_setup
  - arch/x86/entry/vdso/vma.c:vdso_setup
  - arch/x86/entry/vdso/vdso32-setup.c:vdso32_setup
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_spare_reg
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_serial_init
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/fork.c:coredump_filter_setup
  - kernel/reboot.c:reboot_setup
  - kernel/power/hibernate.c:resume_store
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_write
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_main.c:kdbgetulenv
  - kernel/trace/ftrace.c:set_graph_max_depth_function
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/trace_probe.c:traceprobe_expand_meta_args
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - mm/mm_init.c:set_hashdist
  - mm/mmap.c:cmdline_parse_stack_guard_gap
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - fs/dcache.c:set_dhash_entries
  - fs/inode.c:set_ihash_entries
  - fs/namespace.c:set_mphash_entries
  - fs/namespace.c:set_mhash_entries
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - block/early-lookup.c:devt_from_devname
  - block/early-lookup.c:early_lookup_bdev
  - block/blk-integrity.c:write_generate_store
  - block/blk-integrity.c:read_verify_store
  - lib/parser.c:match_one
  - lib/parser.c:match_one
  - lib/parser.c:match_one
  - lib/parser.c:match_one
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_in_ignore_list
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_sleep
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbhistry.c:acpi_db_get_from_history
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_breakpoint
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_references
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/tty/tty_io.c:tty_find_polling_driver
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/serial/serial_core.c:uart_parse_options
  - drivers/base/devtmpfs.c:mount_param
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_depth
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-sata.c:ata_scsi_activity_store
  - drivers/net/xen-netfront.c:store_rxbuf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:bitmap_store
  - drivers/md/md.c:bitmap_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_poll_msec_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_panic_on_ue_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ce_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ue_store
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff820bea90-ffffffff820beaa5: simple_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int simple_strtoul(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff82199300)
Location: lib/vsprintf.c:111
Inline: True
Direct callers:
  - init/do_mounts.c:root_delay_setup
  - init/initramfs.c:parse_header
  - init/calibrate.c:lpj_setup
  - arch/x86/entry/vdso/vma.c:vdso_setup
  - arch/x86/entry/vdso/vdso32-setup.c:vdso32_setup
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_spare_reg
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_serial_init
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/fork.c:coredump_filter_setup
  - kernel/reboot.c:reboot_setup
  - kernel/power/hibernate.c:resume_store
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_write
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_main.c:kdbgetulenv
  - kernel/watchdog.c:softlockup_panic_setup
  - kernel/trace/ftrace.c:set_graph_max_depth_function
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/trace_probe.c:traceprobe_expand_meta_args
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - mm/mm_init.c:set_hashdist
  - mm/mmap.c:cmdline_parse_stack_guard_gap
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - fs/dcache.c:set_dhash_entries
  - fs/inode.c:set_ihash_entries
  - fs/namespace.c:set_mphash_entries
  - fs/namespace.c:set_mhash_entries
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - block/early-lookup.c:devt_from_devname
  - block/early-lookup.c:early_lookup_bdev
  - block/blk-integrity.c:write_generate_store
  - block/blk-integrity.c:read_verify_store
  - lib/parser.c:match_one
  - lib/parser.c:match_one
  - lib/parser.c:match_one
  - lib/parser.c:match_one
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_in_ignore_list
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_interrupt
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_interrupt
  - drivers/acpi/acpica/dbcmds.c:acpi_db_sleep
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbhistry.c:acpi_db_get_from_history
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_breakpoint
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_references
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/tty/tty_io.c:tty_find_polling_driver
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/serial/serial_core.c:uart_parse_options
  - drivers/base/devtmpfs.c:mount_param
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_depth
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-sata.c:ata_scsi_activity_store
  - drivers/net/xen-netfront.c:store_rxbuf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:bitmap_store
  - drivers/md/md.c:bitmap_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_poll_msec_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_panic_on_ue_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ce_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ue_store
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff82199300-ffffffff82199315: simple_strtoul (STB_GLOBAL)
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
long unsigned int simple_strtoul(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffff800010d98554)
Location: lib/vsprintf.c:86
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
Direct callers:
  - init/do_mounts.c:root_delay_setup
  - init/initramfs.c:parse_header
  - init/calibrate.c:lpj_setup
  - kernel/fork.c:coredump_filter_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_write
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_main.c:kdbgetularg
  - kernel/debug/kdb/kdb_main.c:kdbgetularg
  - kernel/debug/kdb/kdb_main.c:kdbgetulenv
  - kernel/watchdog.c:softlockup_panic_setup
  - kernel/trace/ftrace.c:set_graph_max_depth_function
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - mm/mmap.c:cmdline_parse_stack_guard_gap
  - mm/page_alloc.c:set_hashdist
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - fs/dcache.c:set_dhash_entries
  - fs/inode.c:set_ihash_entries
  - fs/namespace.c:set_mphash_entries
  - fs/namespace.c:set_mhash_entries
  - fs/ext4/super.c:ext4_fill_super
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - block/blk-integrity.c:integrity_generate_store
  - block/blk-integrity.c:integrity_verify_store
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/mx3fb.c:mx3fb_init
  - drivers/xen/xenbus/xenbus_xs.c:find_watch
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/tty/tty_io.c:tty_find_polling_driver
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/serial/serial_core.c:uart_parse_options
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/base/platform.c:early_platform_driver_register
  - drivers/base/devtmpfs.c:mount_param
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_depth
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/net/xen-netfront.c:store_rxbuf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_poll_msec_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_panic_on_ue_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ce_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ue_store
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
  - drivers/mmc/core/block.c:force_ro_store
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffff800010d93bf8-ffff800010d93c0c: simple_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long unsigned int simple_strtoul(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c0e93694)
Location: lib/vsprintf.c:86
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
Direct callers:
  - init/do_mounts.c:root_delay_setup
  - init/initramfs.c:do_header
  - init/calibrate.c:lpj_setup
  - kernel/fork.c:coredump_filter_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_write
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_main.c:kdbgetularg
  - kernel/debug/kdb/kdb_main.c:kdbgetularg
  - kernel/debug/kdb/kdb_main.c:kdbgetulenv
  - kernel/watchdog.c:softlockup_panic_setup
  - kernel/trace/ftrace.c:set_graph_max_depth_function
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - mm/mmap.c:cmdline_parse_stack_guard_gap
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - fs/dcache.c:set_dhash_entries
  - fs/inode.c:set_ihash_entries
  - fs/namespace.c:set_mphash_entries
  - fs/namespace.c:set_mhash_entries
  - fs/ext4/super.c:ext4_fill_super
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - block/blk-integrity.c:integrity_generate_store
  - block/blk-integrity.c:integrity_verify_store
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - drivers/pci/pci.c:pci_setup
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/mx3fb.c:mx3fb_init
  - drivers/tty/tty_io.c:tty_find_polling_driver
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/serial/serial_core.c:uart_parse_options
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/base/platform.c:early_platform_driver_register
  - drivers/base/devtmpfs.c:mount_param
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_depth
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/mtd/mtdsuper.c:get_tree_mtd
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_poll_msec_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_panic_on_ue_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ce_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ue_store
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
  - drivers/mmc/core/block.c:force_ro_store
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - sound/core/pcm_memory.c:snd_pcm_lib_preallocate_proc_write
```
**Symbols:**

```
c0e8fea0-c0e8feb4: simple_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long unsigned int simple_strtoul(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c000000000ed81c0)
Location: lib/vsprintf.c:86
Inline: True
Direct callers:
  - init/do_mounts.c:root_delay_setup
  - init/initramfs.c:parse_header
  - arch/powerpc/kernel/rtas-proc.c:ppc_rtas_progress_write
  - arch/powerpc/platforms/pseries/reconfig.c:parse_next_property
  - arch/powerpc/platforms/pseries/lparcfg.c:lparcfg_write
  - arch/powerpc/platforms/pseries/lparcfg.c:lparcfg_write
  - arch/powerpc/platforms/pseries/lparcfg.c:lparcfg_write
  - arch/powerpc/platforms/pseries/lparcfg.c:lparcfg_write
  - kernel/fork.c:coredump_filter_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_write
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_main.c:kdbgetularg
  - kernel/debug/kdb/kdb_main.c:kdbgetularg
  - kernel/debug/kdb/kdb_main.c:kdbgetulenv
  - kernel/watchdog.c:softlockup_panic_setup
  - kernel/trace/ftrace.c:set_graph_max_depth_function
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - mm/mmap.c:cmdline_parse_stack_guard_gap
  - mm/page_alloc.c:set_hashdist
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - fs/dcache.c:set_dhash_entries
  - fs/inode.c:set_ihash_entries
  - fs/namespace.c:set_mphash_entries
  - fs/namespace.c:set_mhash_entries
  - fs/ext4/super.c:ext4_fill_super
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - block/blk-integrity.c:integrity_generate_store
  - block/blk-integrity.c:integrity_verify_store
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/tty/tty_io.c:tty_find_polling_driver
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/serial/serial_core.c:uart_parse_options
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/base/platform.c:early_platform_driver_register
  - drivers/base/devtmpfs.c:mount_param
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_depth
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_poll_msec_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_panic_on_ue_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ce_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ue_store
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
```
**Symbols:**

```
c000000000ed81c0-c000000000ed81cc: simple_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long unsigned int simple_strtoul(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffe0008bdc1a)
Location: lib/vsprintf.c:86
Inline: True
Direct callers:
  - init/do_mounts.c:root_delay_setup
  - init/initramfs.c:parse_header
  - init/calibrate.c:lpj_setup
  - kernel/fork.c:coredump_filter_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_write
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/watchdog.c:softlockup_panic_setup
  - kernel/trace/ftrace.c:set_graph_max_depth_function
  - kernel/trace/ftrace.c:match_records
  - mm/mmap.c:cmdline_parse_stack_guard_gap
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - fs/dcache.c:set_dhash_entries
  - fs/inode.c:set_ihash_entries
  - fs/namespace.c:set_mphash_entries
  - fs/namespace.c:set_mhash_entries
  - fs/ext4/super.c:ext4_fill_super
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - block/blk-integrity.c:integrity_generate_store
  - block/blk-integrity.c:integrity_verify_store
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/serial/serial_core.c:uart_parse_options
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/base/platform.c:early_platform_driver_register
  - drivers/base/devtmpfs.c:mount_param
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_depth
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_poll_msec_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_panic_on_ue_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ce_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ue_store
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
  - drivers/mmc/core/block.c:force_ro_store
```
**Symbols:**

```
ffffffe0008bdc1a-ffffffe0008bdc32: simple_strtoul (STB_GLOBAL)
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
long unsigned int simple_strtoul(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a58380)
Location: lib/vsprintf.c:86
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
Direct callers:
  - init/do_mounts.c:root_delay_setup
  - init/initramfs.c:parse_header
  - init/calibrate.c:lpj_setup
  - arch/x86/entry/vdso/vma.c:vdso_setup
  - arch/x86/entry/vdso/vdso32-setup.c:vdso32_setup
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_spare_reg
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:early_serial_init
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/fork.c:coredump_filter_setup
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/sysctl_binary.c:bin_ulongvec
  - kernel/sysctl_binary.c:bin_intvec
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_write
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_main.c:kdbgetularg
  - kernel/debug/kdb/kdb_main.c:kdbgetularg
  - kernel/debug/kdb/kdb_main.c:kdbgetulenv
  - kernel/watchdog.c:softlockup_panic_setup
  - kernel/trace/ftrace.c:set_graph_max_depth_function
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - mm/mmap.c:cmdline_parse_stack_guard_gap
  - mm/page_alloc.c:set_hashdist
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - fs/dcache.c:set_dhash_entries
  - fs/inode.c:set_ihash_entries
  - fs/namespace.c:set_mphash_entries
  - fs/namespace.c:set_mhash_entries
  - fs/ext4/super.c:ext4_fill_super
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - block/blk-integrity.c:integrity_generate_store
  - block/blk-integrity.c:integrity_verify_store
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/sysfs.c:counter_set
  - drivers/xen/xenbus/xenbus_xs.c:find_watch
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/tty/tty_io.c:tty_find_polling_driver
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/serial/serial_core.c:uart_parse_options
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/base/platform.c:early_platform_driver_register
  - drivers/base/devtmpfs.c:mount_param
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_depth
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/net/xen-netfront.c:store_rxbuf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_poll_msec_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_panic_on_ue_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ce_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ue_store
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff81a58380-ffffffff81a5838b: simple_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long unsigned int simple_strtoul(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a15460)
Location: lib/vsprintf.c:86
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
Direct callers:
  - init/do_mounts.c:root_delay_setup
  - init/initramfs.c:parse_header
  - init/calibrate.c:lpj_setup
  - arch/x86/entry/vdso/vma.c:vdso_setup
  - arch/x86/entry/vdso/vdso32-setup.c:vdso32_setup
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_spare_reg
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:early_serial_init
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/fork.c:coredump_filter_setup
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/sysctl_binary.c:bin_dn_node_address
  - kernel/sysctl_binary.c:bin_ulongvec
  - kernel/sysctl_binary.c:bin_intvec
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_write
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_main.c:kdbgetularg
  - kernel/debug/kdb/kdb_main.c:kdbgetularg
  - kernel/debug/kdb/kdb_main.c:kdbgetulenv
  - kernel/watchdog.c:softlockup_panic_setup
  - kernel/trace/ftrace.c:set_graph_max_depth_function
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - mm/mmap.c:cmdline_parse_stack_guard_gap
  - mm/page_alloc.c:set_hashdist
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - fs/dcache.c:set_dhash_entries
  - fs/inode.c:set_ihash_entries
  - fs/namespace.c:set_mphash_entries
  - fs/namespace.c:set_mhash_entries
  - fs/ext4/super.c:ext4_fill_super
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - block/blk-integrity.c:integrity_generate_store
  - block/blk-integrity.c:integrity_verify_store
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/acpi/sysfs.c:counter_set
  - drivers/tty/tty_io.c:tty_find_polling_driver
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/serial/serial_core.c:uart_parse_options
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/base/platform.c:early_platform_driver_register
  - drivers/base/devtmpfs.c:mount_param
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_depth
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_transport_fc.c:store_fc_rport_fast_io_fail_tmo
  - drivers/scsi/scsi_transport_fc.c:fc_str_to_dev_loss
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_poll_msec_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_panic_on_ue_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ce_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ue_store
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff81a15460-ffffffff81a1546b: simple_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long unsigned int simple_strtoul(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ac4770)
Location: lib/vsprintf.c:86
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
Direct callers:
  - init/do_mounts.c:root_delay_setup
  - init/initramfs.c:parse_header
  - init/calibrate.c:lpj_setup
  - arch/x86/entry/vdso/vma.c:vdso_setup
  - arch/x86/entry/vdso/vdso32-setup.c:vdso32_setup
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_spare_reg
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:early_serial_init
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/fork.c:coredump_filter_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_write
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_main.c:kdbgetularg
  - kernel/debug/kdb/kdb_main.c:kdbgetularg
  - kernel/debug/kdb/kdb_main.c:kdbgetulenv
  - kernel/watchdog.c:softlockup_panic_setup
  - kernel/trace/ftrace.c:set_graph_max_depth_function
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - mm/mmap.c:cmdline_parse_stack_guard_gap
  - mm/page_alloc.c:set_hashdist
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - fs/dcache.c:set_dhash_entries
  - fs/inode.c:set_ihash_entries
  - fs/namespace.c:set_mphash_entries
  - fs/namespace.c:set_mhash_entries
  - fs/ext4/super.c:ext4_fill_super
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - block/blk-integrity.c:integrity_generate_store
  - block/blk-integrity.c:integrity_verify_store
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_sleep
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbhistry.c:acpi_db_get_from_history
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_breakpoint
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_references
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/xen/xenbus/xenbus_xs.c:find_watch
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/tty/tty_io.c:tty_find_polling_driver
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/serial/serial_core.c:uart_parse_options
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/base/platform.c:early_platform_driver_register
  - drivers/base/devtmpfs.c:mount_param
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_depth
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/net/xen-netfront.c:store_rxbuf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_poll_msec_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_panic_on_ue_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ce_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ue_store
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff81ac4770-ffffffff81ac477b: simple_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long unsigned int simple_strtoul(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ad0c40)
Location: lib/vsprintf.c:86
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
Direct callers:
  - init/do_mounts.c:root_delay_setup
  - init/initramfs.c:parse_header
  - init/calibrate.c:lpj_setup
  - arch/x86/entry/vdso/vma.c:vdso_setup
  - arch/x86/entry/vdso/vdso32-setup.c:vdso32_setup
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_spare_reg
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:early_serial_init
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/fork.c:coredump_filter_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_write
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_main.c:kdbgetularg
  - kernel/debug/kdb/kdb_main.c:kdbgetularg
  - kernel/debug/kdb/kdb_main.c:kdbgetulenv
  - kernel/watchdog.c:softlockup_panic_setup
  - kernel/trace/ftrace.c:set_graph_max_depth_function
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - mm/mmap.c:cmdline_parse_stack_guard_gap
  - mm/page_alloc.c:set_hashdist
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - fs/dcache.c:set_dhash_entries
  - fs/inode.c:set_ihash_entries
  - fs/namespace.c:set_mphash_entries
  - fs/namespace.c:set_mhash_entries
  - fs/ext4/super.c:ext4_fill_super
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - security/tomoyo/util.c:tomoyo_parse_ulong
  - block/blk-integrity.c:integrity_generate_store
  - block/blk-integrity.c:integrity_verify_store
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - lib/parser.c:match_token
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/pci/pci.c:pci_setup
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_sleep
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbhistry.c:acpi_db_get_from_history
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_breakpoint
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_references
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/xen/xenbus/xenbus_xs.c:find_watch
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/tty/tty_io.c:tty_find_polling_driver
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/serial/serial_core.c:uart_parse_options
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/base/platform.c:early_platform_driver_register
  - drivers/base/devtmpfs.c:mount_param
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_depth
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-scsi.c:ata_scsi_activity_store
  - drivers/net/xen-netfront.c:store_rxbuf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_parse_config
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_poll_msec_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_panic_on_ue_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ce_store
  - drivers/edac/edac_device_sysfs.c:edac_device_ctl_log_ue_store
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff81ad0c40-ffffffff81ad0c4b: simple_strtoul (STB_GLOBAL)
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
