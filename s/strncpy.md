# Function: <code>strncpy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *strncpy(char *dest, const char *src, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff813f1790)
Location: lib/string.c:112
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:set_trigger
  - kernel/sys.c:parse_compat_uts_machine
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:console_setup
  - kernel/module.c:module_address_lookup
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_next
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/trace_stack.c:enable_stacktrace
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - mm/page_alloc.c:numa_zonelist_order_handler
  - fs/exec.c:get_task_comm
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_page
  - fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/kernfs/symlink.c:kernfs_iop_follow_link
  - fs/ext4/super.c:__save_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok
  - security/security.c:choose_lsm
  - security/smack/smack_access.c:smk_parse_smack
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - crypto/ablkcipher.c:crypto_ablkcipher_report
  - crypto/ablkcipher.c:crypto_givcipher_report
  - crypto/blkcipher.c:crypto_blkcipher_report
  - block/elevator.c:elevator_setup
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/bsg.c:bsg_open
  - block/blk-throttle.c:blk_throtl_bio
  - block/cfq-iosched.c:check_blkcg_changed
  - block/cfq-iosched.c:check_blkcg_changed
  - block/cfq-iosched.c:cfq_arm_slice_timer
  - block/cfq-iosched.c:cfq_arm_slice_timer
  - block/cfq-iosched.c:cfq_completed_request
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/kobject.c:kobject_get_path
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pci/pci.c:pci_set_resource_alignment_param
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/battery.c:extract_package
  - drivers/acpi/battery.c:extract_package
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/sysblk.c:nvm_sysblk_to_cpu
  - drivers/lightnvm/sysblk.c:nvm_cpu_to_sysblk
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/cpufreq/cpufreq.c:cpufreq_offline_prepare
  - drivers/leds/led-triggers.c:led_trigger_store
  - drivers/devfreq/devfreq.c:governor_store
  - net/socket.c:sockfs_getxattr
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key
  - net/ipv4/tcp_cong.c:tcp_get_default_congestion_control
```
**Symbols:**

```
ffffffff813f1790-ffffffff813f17ba: strncpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *strncpy(char *dest, const char *src, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81438120)
Location: lib/string.c:112
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:set_trigger
  - kernel/sys.c:parse_compat_uts_machine
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/module.c:module_address_lookup
  - kernel/cgroup.c:cgroup_file_name
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_next
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/trace_stack.c:enable_stacktrace
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/bpf/helpers.c:bpf_get_current_comm
  - mm/page_alloc.c:numa_zonelist_order_handler
  - fs/exec.c:get_task_comm
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_page
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page
  - fs/kernfs/symlink.c:kernfs_iop_get_link
  - fs/ext4/super.c:__save_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok
  - security/security.c:choose_lsm
  - security/smack/smack_access.c:smk_parse_smack
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - crypto/ablkcipher.c:crypto_givcipher_report
  - crypto/ablkcipher.c:crypto_ablkcipher_report
  - crypto/blkcipher.c:crypto_blkcipher_report
  - block/elevator.c:elevator_setup
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/bsg.c:bsg_open
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_extend_slice
  - block/blk-throttle.c:throtl_start_new_slice
  - block/blk-throttle.c:throtl_start_new_slice_with_credit
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:check_blkcg_changed
  - block/cfq-iosched.c:check_blkcg_changed
  - block/cfq-iosched.c:cfq_arm_slice_timer
  - block/cfq-iosched.c:cfq_arm_slice_timer
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - lib/kobject.c:kobject_get_path
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/pci/pci.c:pci_set_resource_alignment_param
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/battery.c:extract_package
  - drivers/acpi/battery.c:extract_package
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/sysblk.c:nvm_get_sysblock
  - drivers/lightnvm/sysblk.c:nvm_write_and_verify
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/devfreq/devfreq.c:governor_store
  - net/socket.c:sockfs_getxattr
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/ipv4/tcp_cong.c:tcp_get_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key
```
**Symbols:**

```
ffffffff81438120-ffffffff8143814a: strncpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *strncpy(char *dest, const char *src, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81455110)
Location: lib/string.c:112
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:set_trigger
  - kernel/sys.c:parse_compat_uts_machine
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/module.c:module_address_lookup
  - kernel/cgroup.c:cgroup_file_name
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_next
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/trace_stack.c:enable_stacktrace
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/bpf/helpers.c:bpf_get_current_comm
  - mm/page_alloc.c:numa_zonelist_order_handler
  - fs/exec.c:get_task_comm
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_page
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page
  - fs/kernfs/symlink.c:kernfs_iop_get_link
  - fs/ext4/super.c:__save_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok
  - security/security.c:choose_lsm
  - security/smack/smack_access.c:smk_parse_smack
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - crypto/ablkcipher.c:crypto_givcipher_report
  - crypto/ablkcipher.c:crypto_ablkcipher_report
  - crypto/blkcipher.c:crypto_blkcipher_report
  - block/elevator.c:elevator_setup
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/bsg.c:bsg_open
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
  - lib/kobject.c:kobject_get_path
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/pci/pci.c:pci_set_resource_alignment_param
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/battery.c:extract_package
  - drivers/acpi/battery.c:extract_package
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/sysblk.c:nvm_get_sysblock
  - drivers/lightnvm/sysblk.c:nvm_write_and_verify
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
  - drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/devfreq/devfreq.c:governor_store
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/ipv4/tcp_cong.c:tcp_get_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key
```
**Symbols:**

```
ffffffff81455110-ffffffff8145513a: strncpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
char *strncpy(char *p, const char *q, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/efi.c (ffffffff820a8dcc)
Location: include/linux/string.h:206
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:set_trigger
  - kernel/sys.c:parse_compat_uts_machine
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/module.c:module_address_lookup
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_next
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/trace_stack.c:enable_stacktrace
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/bpf/helpers.c:bpf_get_current_comm
  - mm/page_alloc.c:numa_zonelist_order_handler
  - mm/vmpressure.c:vmpressure_register_event
  - fs/exec.c:get_task_comm
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_page
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page
  - fs/ext4/super.c:__save_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok
  - security/security.c:set_lsm_of_current
  - security/security.c:choose_display_lsm
  - security/security.c:choose_lsm
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/smack/smack_access.c:smk_parse_smack
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - crypto/aead.c:crypto_aead_report
  - crypto/aead.c:crypto_aead_report
  - crypto/ablkcipher.c:crypto_givcipher_report
  - crypto/ablkcipher.c:crypto_givcipher_report
  - crypto/ablkcipher.c:crypto_ablkcipher_report
  - crypto/ablkcipher.c:crypto_ablkcipher_report
  - crypto/blkcipher.c:crypto_blkcipher_report
  - crypto/blkcipher.c:crypto_blkcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/ahash.c:crypto_ahash_report
  - crypto/shash.c:crypto_shash_report
  - crypto/akcipher.c:crypto_akcipher_report
  - crypto/kpp.c:crypto_kpp_report
  - crypto/acompress.c:crypto_acomp_report
  - crypto/scompress.c:crypto_scomp_report
  - crypto/rng.c:crypto_rng_report
  - block/elevator.c:elevator_setup
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/bsg.c:bsg_open
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/pci/pci.c:pci_set_resource_alignment_param
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo
  - drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
  - drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/edac/edac_mc_sysfs.c:dimmdev_label_store
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/devfreq/devfreq.c:governor_store
  - net/core/filter.c:bpf_setsockopt
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/ipv4/tcp_cong.c:tcp_get_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key
  - lib/kobject.c:kobject_get_path
```
**Symbols:**

```
ffffffff818f6930-ffffffff818f695c: strncpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
char *strncpy(char *p, const char *q, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/efi.c (ffffffff826af3bb)
Location: include/linux/string.h:238
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:set_trigger
  - kernel/sys.c:parse_compat_uts_machine
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/module.c:module_address_lookup
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_next
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/trace_stack.c:enable_stacktrace
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/bpf/helpers.c:bpf_get_current_comm
  - mm/vmpressure.c:vmpressure_register_event
  - fs/exec.c:__get_task_comm
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_page
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page
  - fs/ext4/super.c:__save_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok
  - security/security.c:set_lsm_of_current
  - security/security.c:choose_display_lsm
  - security/security.c:choose_lsm
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/smack/smack_access.c:smk_parse_smack
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - crypto/aead.c:crypto_aead_report
  - crypto/aead.c:crypto_aead_report
  - crypto/ablkcipher.c:crypto_givcipher_report
  - crypto/ablkcipher.c:crypto_givcipher_report
  - crypto/ablkcipher.c:crypto_ablkcipher_report
  - crypto/ablkcipher.c:crypto_ablkcipher_report
  - crypto/blkcipher.c:crypto_blkcipher_report
  - crypto/blkcipher.c:crypto_blkcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/ahash.c:crypto_ahash_report
  - crypto/shash.c:crypto_shash_report
  - crypto/akcipher.c:crypto_akcipher_report
  - crypto/kpp.c:crypto_kpp_report
  - crypto/acompress.c:crypto_acomp_report
  - crypto/scompress.c:crypto_scomp_report
  - crypto/rng.c:crypto_rng_report
  - block/elevator.c:elevator_setup
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/bsg.c:bsg_open
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/pci/pci.c:pci_set_resource_alignment_param
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/psutils.c:acpi_ps_init_op
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
  - drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/edac/edac_mc_sysfs.c:dimmdev_label_store
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/devfreq/devfreq.c:governor_store
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/ipv4/tcp_cong.c:tcp_get_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key
  - lib/kobject.c:kobject_get_path
```
**Symbols:**

```
ffffffff8197d330-ffffffff8197d35c: strncpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
char *strncpy(char *p, const char *q, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/efi.c (ffffffff826d864e)
Location: include/linux/string.h:239
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:set_trigger
  - kernel/sys.c:parse_compat_uts_machine
  - kernel/power/hibernate.c:resume_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/module.c:module_address_lookup
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_next
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/trace_stack.c:enable_stacktrace
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_synth_event
  - kernel/bpf/helpers.c:bpf_get_current_comm
  - fs/exec.c:__get_task_comm
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_page
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/ext4/super.c:__save_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok
  - security/security.c:choose_lsm
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/smack/smack_access.c:smk_parse_smack
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - crypto/aead.c:crypto_aead_report
  - crypto/aead.c:crypto_aead_report
  - crypto/ablkcipher.c:crypto_givcipher_report
  - crypto/ablkcipher.c:crypto_givcipher_report
  - crypto/ablkcipher.c:crypto_ablkcipher_report
  - crypto/ablkcipher.c:crypto_ablkcipher_report
  - crypto/blkcipher.c:crypto_blkcipher_report
  - crypto/blkcipher.c:crypto_blkcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/ahash.c:crypto_ahash_report
  - crypto/shash.c:crypto_shash_report
  - crypto/akcipher.c:crypto_akcipher_report
  - crypto/kpp.c:crypto_kpp_report
  - crypto/acompress.c:crypto_acomp_report
  - crypto/scompress.c:crypto_scomp_report
  - crypto/rng.c:crypto_rng_report
  - block/elevator.c:elevator_setup
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/bsg.c:bsg_open
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/pci/pci.c:pci_set_resource_alignment_param
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/acpi/osi.c:acpi_osi_setup
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncpy
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
  - drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/edac/edac_mc_sysfs.c:dimmdev_label_store
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/devfreq/devfreq.c:governor_store
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/ipv4/tcp_cong.c:tcp_get_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key
  - lib/kobject.c:kobject_get_path
```
**Symbols:**

```
ffffffff819d9880-ffffffff819d98a7: strncpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
char *strncpy(char *p, const char *q, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/efi.c (ffffffff8288e68d)
Location: include/linux/string.h:246
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - kernel/sys.c:parse_compat_uts_machine
  - kernel/power/hibernate.c:resume_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/module.c:module_address_lookup
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/trace_stack.c:enable_stacktrace
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/bpf/helpers.c:bpf_get_current_comm
  - fs/exec.c:__get_task_comm
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_page
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/ext4/super.c:__save_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/smack/smack_access.c:smk_parse_smack
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - block/elevator.c:elevator_setup
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/bsg.c:bsg_open
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_write
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/pci/pci.c:pci_set_resource_alignment_param
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/acpi/osi.c:acpi_osi_setup
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncpy
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
  - drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/edac/edac_mc_sysfs.c:dimmdev_label_store
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/devfreq/devfreq.c:governor_store
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/ipv4/tcp_cong.c:tcp_get_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key
```
**Symbols:**

```
ffffffff81a11aa0-ffffffff81a11ac7: strncpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
char *strncpy(char *p, const char *q, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/efi.c (ffffffff828a5c33)
Location: include/linux/string.h:253
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/hpet.c:hpet_enable
  - kernel/sys.c:parse_compat_uts_machine
  - kernel/power/hibernate.c:resume_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/module.c:module_address_lookup
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_stack.c:enable_stacktrace
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/bpf/helpers.c:bpf_get_current_comm
  - fs/exec.c:__get_task_comm
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/ext4/super.c:__save_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/unicode/utf8-core.c:utf8_parse_version
  - security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/smack/smack_access.c:smk_parse_smack
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - block/elevator.c:elevator_setup
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/bsg.c:bsg_open
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/pci/pci.c:pci_set_resource_alignment_param
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/acpi/osi.c:acpi_osi_setup
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncpy
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
  - drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/edac/edac_mc_sysfs.c:dimmdev_label_store
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/ipv4/tcp_cong.c:tcp_get_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key
```
**Symbols:**

```
ffffffff81a81000-ffffffff81a81025: strncpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
char *strncpy(char *p, const char *q, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/efi.c (ffffffff828a8c3b)
Location: include/linux/string.h:274
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:param_set_action
  - kernel/sys.c:parse_compat_uts_machine
  - kernel/power/hibernate.c:resume_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/module.c:module_address_lookup
  - kernel/module.c:resolve_symbol
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_stack.c:enable_stacktrace
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/bpf/helpers.c:bpf_get_current_comm
  - fs/exec.c:__get_task_comm
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/ext4/super.c:__save_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/unicode/utf8-core.c:utf8_load
  - security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/smack/smack_access.c:smk_parse_smack
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/bsg.c:bsg_open
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/acpi/osi.c:acpi_osi_setup
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncpy
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
  - drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/edac/edac_mc_sysfs.c:dimmdev_label_store
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/ipv4/tcp_cong.c:tcp_get_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key
```
**Symbols:**

```
ffffffff81ab8200-ffffffff81ab8225: strncpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
char *strncpy(char *p, const char *q, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff82cc3cb1)
Location: include/linux/string.h:300
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
  - arch/x86/xen/efi.c:xen_efi_init
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/hpet.c:hpet_legacy_clockevent_register
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:param_set_action
  - kernel/sys.c:parse_compat_uts_machine
  - kernel/power/hibernate.c:resume_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/module.c:module_address_lookup
  - kernel/module.c:resolve_symbol
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_stack.c:enable_stacktrace
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_synth.c:synth_field_string_size
  - kernel/trace/trace_events_hist.c:add_to_key
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init
  - kernel/bpf/core.c:bpf_get_kallsym
  - kernel/bpf/core.c:__bpf_address_lookup
  - kernel/bpf/helpers.c:bpf_get_current_comm
  - fs/exec.c:__get_task_comm
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/ext4/super.c:__save_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/squashfs/namei.c:get_dir_index_using_name
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/unicode/utf8-core.c:utf8_load
  - security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/smack/smack_access.c:smk_parse_smack
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/cmdline-parser.c:parse_parts
  - block/cmdline-parser.c:parse_parts
  - block/cmdline-parser.c:parse_subpart
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_desc_to_lineinfo
  - drivers/gpio/gpiolib.c:gpio_desc_to_lineinfo
  - drivers/video/hdmi.c:hdmi_spd_infoframe_log
  - drivers/video/hdmi.c:hdmi_spd_infoframe_log
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/acpi/osi.c:acpi_osi_setup
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncpy
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
  - drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:uevent_notify
  - drivers/power/supply/charger-manager.c:uevent_notify
  - drivers/power/supply/charger-manager.c:uevent_notify
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/edac/edac_mc_sysfs.c:dimmdev_label_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:governor_store
  - net/core/filter.c:_bpf_getsockopt
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:_bpf_setsockopt
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/ipv4/tcp_cong.c:tcp_get_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key
```
**Symbols:**

```
ffffffff815f2e20-ffffffff815f2e48: strncpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
char *strncpy(char *p, const char *q, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff82fafddf)
Location: include/linux/string.h:294
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
  - arch/x86/xen/efi.c:xen_efi_init
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_stringify
  - arch/x86/kernel/hpet.c:hpet_legacy_clockevent_register
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:param_set_action
  - kernel/sys.c:parse_compat_uts_machine
  - kernel/power/hibernate.c:resume_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/module.c:module_address_lookup
  - kernel/module.c:resolve_symbol
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_stack.c:enable_stacktrace
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_synth.c:save_cmdstr
  - kernel/trace/trace_events_synth.c:synth_field_string_size
  - kernel/trace/trace_events_hist.c:add_to_key
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init
  - kernel/bpf/core.c:bpf_get_kallsym
  - kernel/bpf/core.c:__bpf_address_lookup
  - kernel/bpf/helpers.c:bpf_get_current_comm
  - fs/exec.c:__get_task_comm
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_update_super
  - fs/squashfs/namei.c:get_dir_index_using_name
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/unicode/utf8-core.c:utf8_load
  - security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/smack/smack_access.c:smk_parse_smack
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/cmdline-parser.c:parse_parts
  - block/cmdline-parser.c:parse_parts
  - block/cmdline-parser.c:parse_subpart
  - drivers/video/hdmi.c:hdmi_spd_infoframe_log
  - drivers/video/hdmi.c:hdmi_spd_infoframe_log
  - drivers/acpi/osi.c:acpi_osi_setup
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncpy
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
  - drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/edac/edac_mc_sysfs.c:dimmdev_label_store
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - net/core/filter.c:_bpf_getsockopt
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:_bpf_setsockopt
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/ipv4/tcp_cong.c:tcp_get_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key
```
**Symbols:**

```
ffffffff816174d0-ffffffff816174f8: strncpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
char *strncpy(char *p, const char *q, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff831b9e42)
Location: include/linux/fortify-string.h:30
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
  - arch/x86/xen/efi.c:xen_efi_init
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_stringify
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:param_set_action
  - kernel/sys.c:parse_compat_uts_machine
  - kernel/power/hibernate.c:resume_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/module.c:module_address_lookup
  - kernel/module.c:resolve_symbol
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/trace.c:trace_check_vprintf
  - kernel/trace/trace.c:trace_check_vprintf
  - kernel/trace/trace.c:trace_save_cmdline
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_stack.c:enable_stacktrace
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
  - kernel/trace/trace_events_synth.c:synth_field_string_size
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init
  - kernel/bpf/core.c:bpf_get_kallsym
  - kernel/bpf/core.c:__bpf_address_lookup
  - kernel/bpf/helpers.c:bpf_get_current_comm
  - fs/exec.c:__get_task_comm
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_update_super
  - fs/squashfs/namei.c:get_dir_index_using_name
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/unicode/utf8-core.c:utf8_load
  - security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/smack/smack_access.c:smk_parse_smack
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/cmdline-parser.c:parse_parts
  - block/cmdline-parser.c:parse_parts
  - block/cmdline-parser.c:parse_subpart
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/acpi/osi.c:acpi_osi_setup
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncpy
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
  - drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/edac/edac_mc_sysfs.c:dimmdev_label_store
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - net/core/filter.c:_bpf_getsockopt
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:_bpf_setsockopt
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/ipv4/tcp_cong.c:tcp_get_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key
```
**Symbols:**

```
ffffffff815fab50-ffffffff815fab77: strncpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
char *strncpy(char *p, const char *q, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff8329a086)
Location: include/linux/fortify-string.h:30
Inline: True
Inline callers:
  - init/do_mounts.c:do_mount_root
  - arch/x86/xen/efi.c:xen_efi_init
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_stringify
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:param_set_action
  - kernel/sys.c:parse_compat_uts_machine
  - kernel/power/hibernate.c:resume_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/module.c:module_address_lookup
  - kernel/module.c:resolve_symbol
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/trace.c:trace_check_vprintf
  - kernel/trace/trace.c:trace_check_vprintf
  - kernel/trace/trace.c:trace_save_cmdline
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_stack.c:enable_stacktrace
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
  - kernel/trace/trace_events_synth.c:synth_field_string_size
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init
  - kernel/bpf/core.c:bpf_get_kallsym
  - kernel/bpf/core.c:__bpf_address_lookup
  - kernel/bpf/helpers.c:bpf_get_current_comm
  - fs/exec.c:__get_task_comm
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_update_super
  - fs/squashfs/namei.c:get_dir_index_using_name
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/unicode/utf8-core.c:utf8_load
  - security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok
  - security/smack/smack_access.c:smk_parse_smack
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/cmdline.c:parse_parts
  - block/partitions/cmdline.c:parse_parts
  - block/partitions/cmdline.c:parse_subpart
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/acpi/osi.c:acpi_osi_setup
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncpy
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
  - drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/edac/edac_mc_sysfs.c:dimmdev_label_store
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - net/core/filter.c:_bpf_getsockopt
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:_bpf_setsockopt
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/ipv4/tcp_cong.c:tcp_get_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key
```
**Symbols:**

```
ffffffff816683f0-ffffffff81668417: strncpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
char *strncpy(const char * p, const char *q, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff83448344)
Location: include/linux/fortify-string.h:81
Inline: True
Inline callers:
  - init/do_mounts.c:do_mount_root
  - arch/x86/xen/efi.c:xen_efi_init
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_stringify
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:param_set_action
  - kernel/sys.c:parse_compat_uts_machine
  - kernel/power/hibernate.c:resume_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/module/main.c:resolve_symbol
  - kernel/module/kallsyms.c:module_address_lookup
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/trace.c:trace_check_vprintf
  - kernel/trace/trace.c:trace_check_vprintf
  - kernel/trace/trace.c:trace_save_cmdline
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_stack.c:enable_stacktrace
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_synth.c:synth_field_string_size
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init
  - kernel/bpf/core.c:bpf_get_kallsym
  - kernel/bpf/core.c:__bpf_address_lookup
  - kernel/bpf/verifier.c:map_kptr_match_type
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_update_super
  - fs/squashfs/namei.c:get_dir_index_using_name
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok
  - security/smack/smack_access.c:smk_parse_smack
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/cmdline.c:parse_parts
  - block/partitions/cmdline.c:parse_parts
  - block/partitions/cmdline.c:parse_subpart
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/acpi/osi.c:acpi_osi_setup
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncpy
  - drivers/acpi/battery.c:extract_package
  - drivers/acpi/battery.c:extract_package
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
  - drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/edac/edac_mc_sysfs.c:dimmdev_label_store
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
  - net/core/filter.c:_bpf_getsockopt
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:_bpf_setsockopt
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/ipv4/tcp_cong.c:tcp_get_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key
```
**Symbols:**

```
ffffffff81781c20-ffffffff81781c56: strncpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
char *strncpy(const char * p, const char *q, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff83e61f20)
Location: include/linux/fortify-string.h:136
Inline: True
Inline callers:
  - init/do_mounts.c:do_mount_root
  - arch/x86/xen/efi.c:xen_efi_init
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:param_set_action
  - kernel/sys.c:parse_compat_uts_machine
  - kernel/power/hibernate.c:resume_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/module/main.c:resolve_symbol
  - kernel/module/kallsyms.c:module_address_lookup
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/trace.c:trace_check_vprintf
  - kernel/trace/trace.c:trace_check_vprintf
  - kernel/trace/trace.c:trace_save_cmdline
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_stack.c:enable_stacktrace
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_synth.c:synth_field_string_size
  - kernel/trace/trace_events_hist.c:add_to_key
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init
  - kernel/bpf/core.c:bpf_get_kallsym
  - kernel/bpf/core.c:__bpf_address_lookup
  - kernel/bpf/verifier.c:reg_type_str
  - fs/proc/vmcore.c:vmcoredd_write_header
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_update_super
  - fs/squashfs/namei.c:get_dir_index_using_name
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/cmdline.c:parse_parts
  - block/partitions/cmdline.c:parse_parts
  - block/partitions/cmdline.c:parse_subpart
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_tocblock
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/acpi/osi.c:acpi_osi_setup
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncpy
  - drivers/acpi/battery.c:extract_package
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
  - drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/edac/edac_mc_sysfs.c:dimmdev_label_store
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/ipv4/tcp_cong.c:tcp_get_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key
```
**Symbols:**

```
ffffffff8203e960-ffffffff8203e996: strncpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
char *strncpy(const char * p, const char *q, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff83682340)
Location: include/linux/fortify-string.h:143
Inline: True
Inline callers:
  - init/do_mounts.c:do_mount_root
  - arch/x86/xen/efi.c:xen_efi_init
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:param_set_action
  - kernel/sys.c:parse_compat_uts_machine
  - kernel/power/hibernate.c:resume_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/module/main.c:resolve_symbol
  - kernel/module/kallsyms.c:module_address_lookup
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/trace.c:trace_check_vprintf
  - kernel/trace/trace.c:trace_check_vprintf
  - kernel/trace/trace.c:trace_save_cmdline
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_stack.c:enable_stacktrace
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_synth.c:synth_field_string_size
  - kernel/trace/trace_events_hist.c:add_to_key
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init
  - kernel/bpf/core.c:bpf_get_kallsym
  - kernel/bpf/core.c:__bpf_address_lookup
  - kernel/bpf/verifier.c:reg_type_str
  - fs/proc/vmcore.c:vmcoredd_write_header
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_update_super
  - fs/squashfs/namei.c:get_dir_index_using_name
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - block/partitions/cmdline.c:add_part
  - block/partitions/cmdline.c:parse_parts
  - block/partitions/cmdline.c:parse_parts
  - block/partitions/cmdline.c:parse_subpart
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_tocblock
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/acpi/osi.c:acpi_osi_setup
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncpy
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
  - drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/edac/edac_mc_sysfs.c:dimmdev_label_store
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/ipv4/tcp_cong.c:tcp_get_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key
```
**Symbols:**

```
ffffffff820bce60-ffffffff820bce96: strncpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
char *strncpy(const char * p, const char *q, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff838b13d0)
Location: include/linux/fortify-string.h:139
Inline: True
Inline callers:
  - init/do_mounts.c:do_mount_root
  - kernel/sys.c:parse_compat_uts_machine
  - kernel/power/hibernate.c:resume_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/module/main.c:resolve_symbol
  - kernel/module/kallsyms.c:module_address_lookup
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/trace.c:trace_check_vprintf
  - kernel/trace/trace.c:trace_check_vprintf
  - kernel/trace/trace.c:trace_save_cmdline
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_stack.c:enable_stacktrace
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_synth.c:synth_field_string_size
  - kernel/trace/trace_events_hist.c:add_to_key
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init
  - kernel/bpf/core.c:bpf_get_kallsym
  - kernel/bpf/core.c:__bpf_address_lookup
  - kernel/bpf/log.c:reg_type_str
  - fs/proc/vmcore.c:vmcoredd_write_header
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_update_super
  - fs/squashfs/namei.c:get_dir_index_using_name
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_tocblock
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncpy
  - drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
  - drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/ipv4/tcp_cong.c:tcp_get_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key
```
**Symbols:**

```
ffffffff82197760-ffffffff82197796: strncpy (STB_GLOBAL)
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
char *strncpy(char *p, const char *q, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffff800011442cd0)
Location: include/linux/string.h:274
Inline: True
Inline callers:
  - kernel/sys.c:parse_compat_uts_machine
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/module.c:module_address_lookup
  - kernel/module.c:resolve_symbol
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_stack.c:enable_stacktrace
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/bpf/helpers.c:bpf_get_current_comm
  - fs/exec.c:__get_task_comm
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/compat_binfmt_elf.c:fill_psinfo
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/ext4/super.c:__save_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/unicode/utf8-core.c:utf8_load
  - security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/smack/smack_access.c:smk_parse_smack
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/bsg.c:bsg_open
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - drivers/bus/fsl-mc/dprc.c:dprc_get_obj_region
  - drivers/bus/fsl-mc/dprc.c:dprc_set_obj_irq
  - drivers/bus/fsl-mc/dprc.c:dprc_get_obj
  - drivers/bus/fsl-mc/dprc.c:dprc_get_obj
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/video/fbdev/amba-clcd.c:clcdfb_register
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/acpi/osi.c:acpi_osi_setup
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/clk/zynqmp/clkc.c:zynqmp_get_clock_info
  - drivers/clk/zynqmp/clkc.c:zynqmp_get_clock_name
  - drivers/soc/qcom/cmd-db.c:cmd_db_get_header
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
  - drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/edac/edac_mc_sysfs.c:dimmdev_label_store
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
  - drivers/firmware/ti_sci.c:ti_sci_probe
  - drivers/of/base.c:of_alias_scan
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/ipv4/tcp_cong.c:tcp_get_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key
```
**Symbols:**

```
ffff800010d92728-ffff800010d92754: strncpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
char *strncpy(char *p, const char *q, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (c151fe18)
Location: include/linux/string.h:274
Inline: True
Inline callers:
  - kernel/power/hibernate.c:resume_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/module.c:module_address_lookup
  - kernel/module.c:resolve_symbol
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_stack.c:enable_stacktrace
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/bpf/helpers.c:bpf_get_current_comm
  - fs/exec.c:__get_task_comm
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/binfmt_elf.c:fill_psinfo
  - fs/binfmt_elf_fdpic.c:fill_psinfo
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/ext4/super.c:__save_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/unicode/utf8-core.c:utf8_load
  - security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/smack/smack_access.c:smk_parse_smack
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/bsg.c:bsg_open
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/video/fbdev/amba-clcd.c:clcdfb_probe
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/soc/qcom/cmd-db.c:cmd_db_get_header
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
  - drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/edac/edac_mc_sysfs.c:dimmdev_label_store
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
  - drivers/firmware/tegra/bpmp-debugfs.c:debugfs_store
  - drivers/firmware/tegra/bpmp-debugfs.c:debugfs_show
  - drivers/of/base.c:of_alias_scan
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/ipv4/tcp_cong.c:tcp_get_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key
```
**Symbols:**

```
c0e8ecc0-c0e8ecfc: strncpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
char *strncpy(char *p, const char *q, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c000000001366b80)
Location: include/linux/string.h:274
Inline: True
Inline callers:
  - kernel/sys.c:parse_compat_uts_machine
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/module.c:module_address_lookup
  - kernel/module.c:resolve_symbol
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_stack.c:enable_stacktrace
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/bpf/helpers.c:bpf_get_current_comm
  - fs/exec.c:__get_task_comm
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/ext4/super.c:__save_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/unicode/utf8-core.c:utf8_load
  - security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/smack/smack_access.c:smk_parse_smack
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/bsg.c:bsg_open
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
  - drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/edac/edac_mc_sysfs.c:dimmdev_label_store
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/of/base.c:of_alias_scan
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/ipv4/tcp_cong.c:tcp_get_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key
```
**Symbols:**

```
c0000000000a8070-c0000000000a8070: strncpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *strncpy(char *dest, const char *src, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffe0008bc976)
Location: lib/string.c:114
Inline: False
Direct callers:
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/module.c:module_address_lookup
  - kernel/module.c:resolve_symbol
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_stack.c:enable_stacktrace
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/bpf/helpers.c:bpf_get_current_comm
  - fs/exec.c:__get_task_comm
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/ext4/super.c:__save_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/unicode/utf8-core.c:utf8_load
  - security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/smack/smack_access.c:smk_parse_smack
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/bsg.c:bsg_open
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/dax/bus.c:do_id_store
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
  - drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/edac/edac_mc_sysfs.c:dimmdev_label_store
  - drivers/of/base.c:of_alias_scan
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/ipv4/tcp_cong.c:tcp_get_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key
```
**Symbols:**

```
ffffffe0008bc976-ffffffe0008bc99c: strncpy (STB_GLOBAL)
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
char *strncpy(char *p, const char *q, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/efi.c (ffffffff82896c4b)
Location: include/linux/string.h:274
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/hpet.c:hpet_enable
  - kernel/sys.c:parse_compat_uts_machine
  - kernel/power/hibernate.c:resume_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/module.c:module_address_lookup
  - kernel/module.c:resolve_symbol
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_stack.c:enable_stacktrace
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/bpf/helpers.c:bpf_get_current_comm
  - fs/exec.c:__get_task_comm
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/ext4/super.c:__save_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/unicode/utf8-core.c:utf8_load
  - security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/smack/smack_access.c:smk_parse_smack
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/bsg.c:bsg_open
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/acpi/osi.c:acpi_osi_setup
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
  - drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/edac/edac_mc_sysfs.c:dimmdev_label_store
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/ipv4/tcp_cong.c:tcp_get_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key
```
**Symbols:**

```
ffffffff81a57050-ffffffff81a57075: strncpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
char *strncpy(char *p, const char *q, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81043175)
Location: include/linux/string.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/hpet.c:hpet_enable
  - kernel/sys.c:parse_compat_uts_machine
  - kernel/power/hibernate.c:resume_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/module.c:module_address_lookup
  - kernel/module.c:resolve_symbol
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_stack.c:enable_stacktrace
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/bpf/helpers.c:bpf_get_current_comm
  - fs/exec.c:__get_task_comm
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/ext4/super.c:__save_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/unicode/utf8-core.c:utf8_load
  - security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/smack/smack_access.c:smk_parse_smack
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/bsg.c:bsg_open
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/acpi/osi.c:acpi_osi_setup
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/nvdimm/btt.c:btt_meta_init
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
  - drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/edac/edac_mc_sysfs.c:dimmdev_label_store
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/ipv4/tcp_cong.c:tcp_get_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key
```
**Symbols:**

```
ffffffff81a14130-ffffffff81a14155: strncpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
char *strncpy(char *p, const char *q, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/efi.c (ffffffff828a9c3b)
Location: include/linux/string.h:274
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/hpet.c:hpet_enable
  - kernel/sys.c:parse_compat_uts_machine
  - kernel/power/hibernate.c:resume_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/module.c:module_address_lookup
  - kernel/module.c:resolve_symbol
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_stack.c:enable_stacktrace
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/bpf/helpers.c:bpf_get_current_comm
  - fs/exec.c:__get_task_comm
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/ext4/super.c:__save_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/smack/smack_access.c:smk_parse_smack
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/bsg.c:bsg_open
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/acpi/osi.c:acpi_osi_setup
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncpy
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
  - drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/edac/edac_mc_sysfs.c:dimmdev_label_store
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/ipv4/tcp_cong.c:tcp_get_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key
```
**Symbols:**

```
ffffffff81ac3440-ffffffff81ac3465: strncpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
char *strncpy(char *p, const char *q, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/efi.c (ffffffff828a9c4b)
Location: include/linux/string.h:274
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:param_set_action
  - kernel/sys.c:parse_compat_uts_machine
  - kernel/power/hibernate.c:resume_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:console_setup
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/module.c:module_address_lookup
  - kernel/module.c:resolve_symbol
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_stack.c:enable_stacktrace
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/bpf/helpers.c:bpf_get_current_comm
  - fs/exec.c:__get_task_comm
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/compat_binfmt_elf.c:fill_psinfo
  - fs/proc/vmcore.c:vmcore_add_device_dump
  - fs/ext4/super.c:__save_error_info
  - fs/ext4/super.c:__save_error_info
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/unicode/utf8-core.c:utf8_load
  - security/keys/encrypted-keys/ecryptfs_format.c:ecryptfs_fill_auth_tok
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/smack/smack_access.c:smk_parse_smack
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/bsg.c:bsg_open
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/video/hdmi.c:hdmi_spd_infoframe_init
  - drivers/acpi/osi.c:acpi_osi_setup
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncpy
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
  - drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/edac/edac_mc_sysfs.c:dimmdev_label_store
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/ipv4/tcp_cong.c:tcp_get_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_ca_get_name_by_key
```
**Symbols:**

```
ffffffff81acf910-ffffffff81acf935: strncpy (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>char *p</code>
</li>
<li>
<b>Param added. </b>
<code>const char *q</code>
</li>
<li>
<b>Param added. </b>
<code>__kernel_size_t size</code>
</li>
<li>
<b>Param removed. </b>
<code>char *dest</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *src</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t count</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *p</code> ➡️ <code>const char * p</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>char *dest</code>
</li>
<li>
<b>Param added. </b>
<code>const char *src</code>
</li>
<li>
<b>Param added. </b>
<code>size_t count</code>
</li>
<li>
<b>Param removed. </b>
<code>char *p</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *q</code>
</li>
<li>
<b>Param removed. </b>
<code>__kernel_size_t size</code>
</li>
</ul>
</details>
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
