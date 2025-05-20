# Function: <code>__builtin_strncpy</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
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
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
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
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
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
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
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
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
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
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
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
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
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
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
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
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_stringify
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
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_stringify
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
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - init/do_mounts.c:do_mount_root
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_stringify
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
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - init/do_mounts.c:do_mount_root
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_stringify
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
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - init/do_mounts.c:do_mount_root
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
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
  - kernel/trace/trace_events_hist.c:add_to_key
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init
  - kernel/bpf/core.c:bpf_get_kallsym
  - kernel/bpf/core.c:__bpf_address_lookup
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
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - init/do_mounts.c:do_mount_root
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
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
  - kernel/trace/trace_events_hist.c:add_to_key
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init
  - kernel/bpf/core.c:bpf_get_kallsym
  - kernel/bpf/core.c:__bpf_address_lookup
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
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
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
  - kernel/trace/trace_events_hist.c:add_to_key
  - kernel/trace/trace_events_hist.c:cond_snapshot_update
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_init
  - kernel/bpf/core.c:bpf_get_kallsym
  - kernel/bpf/core.c:__bpf_address_lookup
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
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
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
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/compat_binfmt_elf.c:fill_psinfo
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
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
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
  - drivers/soc/qcom/cmd-db.c:cmd_db_get_header
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/dax/bus.c:do_id_store
  - drivers/scsi/scsi_devinfo.c:scsi_strcpy_devinfo
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
  - drivers/net/phy/mdio_bus.c:trace_event_raw_event_mdio_access
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
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
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
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
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
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
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
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
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
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
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
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
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
</details>
</li>
</ul>

## Differences
