# Function: <code>try_module_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool try_module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811058f0)
Location: kernel/module.c:1077
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/irq/manage.c:__setup_irq
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/clockevents.c:__clockevents_unbind
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/module.c:__symbol_get
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - mm/zpool.c:zpool_get_driver
  - fs/open.c:do_dentry_open
  - fs/char_dev.c:cdev_get
  - fs/char_dev.c:chrdev_open
  - fs/exec.c:SyS_uselib
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:SyS_sysfs
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/nls/nls_base.c:find_nls
  - fs/pstore/platform.c:pstore_register
  - crypto/api.c:crypto_mod_get
  - crypto/algapi.c:__crypto_lookup_template
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - block/elevator.c:elevator_get
  - block/genhd.c:get_disk
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
  - drivers/gpio/gpiolib.c:gpiod_request
  - drivers/pwm/core.c:pwm_device_request
  - drivers/pci/pci.c:pci_reset_hotplug_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
  - drivers/pci/hotplug/acpiphp_core.c:get_attention_status
  - drivers/pci/hotplug/acpiphp_core.c:set_attention_status
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_mport_scan
  - drivers/video/console/fbcon.c:fbcon_startup
  - drivers/video/console/fbcon.c:con2fb_acquire_newinfo
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:_regulator_get
  - drivers/tty/tty_ldisc.c:get_ldops
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/serial/kgdboc.c:kgdboc_pre_exp_handler
  - drivers/char/misc.c:misc_open
  - drivers/char/misc.c:misc_open
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/char/tpm/tpm-chip.c:tpm_chip_find_get
  - drivers/base/map.c:kobj_lookup
  - drivers/base/firmware_class.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/loop.c:loop_set_status
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/ppp/ppp_generic.c:find_compressor
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/usb/phy/phy.c:usb_get_phy_dev
  - drivers/input/serio/serio.c:serio_queue_event
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/rtc/rtc-proc.c:rtc_proc_open
  - drivers/i2c/i2c-core.c:i2c_get_adapter
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/md/md.c:level_store
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:dm_create
  - drivers/md/dm-target.c:get_target_type
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
  - drivers/clk/clk.c:__clk_get
  - net/socket.c:__sock_create
  - net/socket.c:__sock_create
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
  - net/core/fib_rules.c:lookup_rules_ops
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_api.c:qdisc_lookup_default
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/cls_api.c:tcf_proto_lookup_ops
  - net/sched/act_api.c:tc_lookup_action_n
  - net/sched/act_api.c:tc_lookup_action
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netfilter/nf_log.c:nf_logger_find_get
  - net/netfilter/nf_sockopt.c:nf_sockopt_find
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/xfrm/xfrm_state.c:xfrm_register_mode
  - net/xfrm/xfrm_state.c:xfrm_get_mode
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffff811058f0-ffffffff811059c2: try_module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool try_module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8110d1c0)
Location: kernel/module.c:1082
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/clockevents.c:__clockevents_unbind
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/module.c:__symbol_get
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - mm/zpool.c:zpool_get_driver
  - fs/open.c:do_dentry_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:cdev_get
  - fs/exec.c:SyS_uselib
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:SyS_sysfs
  - fs/mbcache.c:mb_cache_create
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/nls/nls_base.c:find_nls
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:open_proxy_open
  - fs/pstore/platform.c:pstore_register
  - crypto/api.c:crypto_mod_get
  - crypto/algapi.c:__crypto_lookup_template
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - block/elevator.c:elevator_get
  - block/genhd.c:get_disk
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/gpio/gpiolib.c:gpiod_request
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
  - drivers/pwm/core.c:pwm_device_request
  - drivers/pci/pci.c:pci_reset_hotplug_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
  - drivers/pci/hotplug/acpiphp_core.c:get_attention_status
  - drivers/pci/hotplug/acpiphp_core.c:set_attention_status
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_mport_scan
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/video/console/fbcon.c:fbcon_startup
  - drivers/video/console/fbcon.c:con2fb_acquire_newinfo
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/tty/tty_ldisc.c:get_ldops
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/serial/kgdboc.c:kgdboc_pre_exp_handler
  - drivers/char/misc.c:misc_open
  - drivers/char/misc.c:misc_open
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/base/map.c:kobj_lookup
  - drivers/base/firmware_class.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/loop.c:loop_set_status
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/ppp/ppp_generic.c:find_compressor
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/phy/phy.c:usb_get_phy_dev
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/serio/serio.c:serio_queue_event
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/rtc/rtc-proc.c:rtc_proc_open
  - drivers/i2c/i2c-core.c:i2c_get_adapter
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/dm.c:dm_create
  - drivers/md/dm-target.c:get_target_type
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
  - drivers/clk/clk.c:__clk_get
  - net/socket.c:__sock_create
  - net/socket.c:__sock_create
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:lookup_rules_ops
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_lookup_default
  - net/sched/cls_api.c:tcf_proto_lookup_ops
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:xfrm_get_mode
  - net/xfrm/xfrm_state.c:xfrm_register_mode
```
**Symbols:**

```
ffffffff8110d1c0-ffffffff8110d29c: try_module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool try_module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81114c30)
Location: kernel/module.c:1085
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/clockevents.c:__clockevents_unbind
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/module.c:__symbol_get
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - mm/zpool.c:zpool_get_driver
  - fs/open.c:do_dentry_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:cdev_get
  - fs/exec.c:SyS_uselib
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:SyS_sysfs
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/nls/nls_base.c:find_nls
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:open_proxy_open
  - fs/pstore/platform.c:pstore_register
  - crypto/api.c:crypto_mod_get
  - crypto/algapi.c:__crypto_lookup_template
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - block/elevator.c:elevator_get
  - block/genhd.c:get_disk
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/gpio/gpiolib.c:gpiod_request
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
  - drivers/pwm/core.c:pwm_device_request
  - drivers/pci/pci.c:pci_reset_hotplug_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
  - drivers/pci/hotplug/acpiphp_core.c:get_attention_status
  - drivers/pci/hotplug/acpiphp_core.c:set_attention_status
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_mport_scan
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/video/console/fbcon.c:fbcon_startup
  - drivers/video/console/fbcon.c:con2fb_acquire_newinfo
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/clk/clk.c:__clk_get
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/tty/tty_ldisc.c:get_ldops
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/serial/kgdboc.c:kgdboc_pre_exp_handler
  - drivers/char/misc.c:misc_open
  - drivers/char/misc.c:misc_open
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/base/map.c:kobj_lookup
  - drivers/base/firmware_class.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/loop.c:loop_set_status
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/ppp/ppp_generic.c:find_compressor
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/phy/phy.c:usb_get_phy_dev
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/serio/serio.c:serio_queue_event
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/rtc/rtc-proc.c:rtc_proc_open
  - drivers/i2c/i2c-core.c:i2c_get_adapter
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/dm.c:dm_create
  - drivers/md/dm-target.c:get_target_type
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
  - net/socket.c:__sock_create
  - net/socket.c:__sock_create
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:lookup_rules_ops
  - net/core/lwtunnel.c:lwtunnel_build_state
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_lookup_default
  - net/sched/cls_api.c:tcf_proto_lookup_ops
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:xfrm_get_mode
  - net/xfrm/xfrm_state.c:xfrm_register_mode
```
**Symbols:**

```
ffffffff81114c30-ffffffff81114d0c: try_module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool try_module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81115ba0)
Location: kernel/module.c:1107
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/clockevents.c:__clockevents_unbind
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/module.c:__symbol_get
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - mm/zpool.c:zpool_get_driver
  - fs/open.c:do_dentry_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:cdev_get
  - fs/exec.c:SyS_uselib
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:SyS_sysfs
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/nls/nls_base.c:find_nls
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:open_proxy_open
  - fs/pstore/platform.c:pstore_register
  - crypto/api.c:crypto_mod_get
  - crypto/algapi.c:__crypto_lookup_template
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - block/elevator.c:elevator_get
  - block/genhd.c:get_disk
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
  - drivers/pci/pci.c:pci_reset_hotplug_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
  - drivers/pci/hotplug/acpiphp_core.c:get_attention_status
  - drivers/pci/hotplug/acpiphp_core.c:set_attention_status
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:disc_work_handler
  - drivers/rapidio/rio.c:rio_mport_scan
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/video/console/fbcon.c:fbcon_startup
  - drivers/video/console/fbcon.c:con2fb_acquire_newinfo
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/clk/clk.c:__clk_get
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/tty/tty_ldisc.c:get_ldops
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/serial/kgdboc.c:kgdboc_pre_exp_handler
  - drivers/char/misc.c:misc_open
  - drivers/char/misc.c:misc_open
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/base/map.c:kobj_lookup
  - drivers/base/firmware_class.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/loop.c:loop_set_status
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/ppp/ppp_generic.c:find_compressor
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/phy/phy.c:usb_get_phy_dev
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/serio/serio.c:serio_queue_event
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/rtc/rtc-proc.c:rtc_proc_open
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/dm.c:dm_create
  - drivers/md/dm-target.c:get_target_type
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
  - net/socket.c:__sock_create
  - net/socket.c:__sock_create
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:lookup_rules_ops
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_lookup_default
  - net/sched/cls_api.c:tcf_proto_lookup_ops
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:xfrm_register_mode
```
**Symbols:**

```
ffffffff81115ba0-ffffffff81115c5b: try_module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool try_module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81121130)
Location: kernel/module.c:1115
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/clockevents.c:__clockevents_unbind
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/module.c:__symbol_get
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - mm/zpool.c:zpool_get_driver
  - fs/open.c:do_dentry_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:cdev_get
  - fs/exec.c:SyS_uselib
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:SyS_sysfs
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/nls/nls_base.c:find_nls
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:open_proxy_open
  - fs/pstore/platform.c:pstore_register
  - crypto/api.c:crypto_mod_get
  - crypto/algapi.c:__crypto_lookup_template
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - block/elevator.c:elevator_get
  - block/genhd.c:get_disk
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
  - drivers/pci/pci.c:pci_reset_hotplug_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
  - drivers/pci/hotplug/acpiphp_core.c:get_attention_status
  - drivers/pci/hotplug/acpiphp_core.c:set_attention_status
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:disc_work_handler
  - drivers/rapidio/rio.c:rio_mport_scan
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/video/fbdev/core/fbcon.c:con2fb_acquire_newinfo
  - drivers/acpi/osl.c:acpi_debugger_notify_command_complete
  - drivers/acpi/osl.c:acpi_debugger_wait_command_ready
  - drivers/acpi/osl.c:acpi_debugger_read_cmd
  - drivers/acpi/osl.c:acpi_debugger_write_log
  - drivers/acpi/osl.c:acpi_debugger_create_thread
  - drivers/clk/clk.c:__clk_get
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/tty/tty_ldisc.c:get_ldops
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/serial/kgdboc.c:kgdboc_pre_exp_handler
  - drivers/char/misc.c:misc_open
  - drivers/char/misc.c:misc_open
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/base/map.c:kobj_lookup
  - drivers/base/firmware_class.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/loop.c:loop_set_status
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/ppp/ppp_generic.c:find_compressor
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/phy/phy.c:usb_get_phy_dev
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/serio/serio.c:serio_queue_event
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/rtc/rtc-proc.c:rtc_proc_open
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/dm.c:dm_create
  - drivers/md/dm-target.c:get_target_type
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
  - net/socket.c:__sock_create
  - net/socket.c:__sock_create
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:lookup_rules_ops
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_lookup_default
  - net/sched/cls_api.c:tcf_proto_lookup_ops
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:xfrm_register_mode
```
**Symbols:**

```
ffffffff81121130-ffffffff811211ee: try_module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool try_module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8112ea50)
Location: kernel/module.c:1114
Inline: False
Direct callers:
  - kernel/fork.c:copy_mm
  - kernel/irq/manage.c:__setup_irq
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/clockevents.c:__clockevents_unbind
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/module.c:__symbol_get
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - mm/zpool.c:zpool_get_driver
  - fs/open.c:do_dentry_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:cdev_get
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:fs_name
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/nls/nls_base.c:find_nls
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:open_proxy_open
  - fs/pstore/platform.c:pstore_register
  - crypto/api.c:crypto_mod_get
  - crypto/algapi.c:__crypto_lookup_template
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - block/elevator.c:elevator_get
  - block/genhd.c:get_disk_and_module
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
  - drivers/pwm/core.c:pwm_device_request
  - drivers/pci/pci.c:pci_reset_hotplug_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
  - drivers/pci/hotplug/acpiphp_core.c:get_attention_status
  - drivers/pci/hotplug/acpiphp_core.c:set_attention_status
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_mport_scan
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/video/fbdev/core/fbcon.c:con2fb_acquire_newinfo
  - drivers/acpi/osl.c:acpi_debugger_notify_command_complete
  - drivers/acpi/osl.c:acpi_debugger_wait_command_ready
  - drivers/acpi/osl.c:acpi_debugger_read_cmd
  - drivers/acpi/osl.c:acpi_debugger_write_log
  - drivers/acpi/osl.c:acpi_debugger_create_thread
  - drivers/clk/clk.c:__clk_get
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/reset/core.c:__reset_control_get_from_lookup
  - drivers/tty/tty_ldisc.c:get_ldops
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/serial/kgdboc.c:kgdboc_pre_exp_handler
  - drivers/char/misc.c:misc_open
  - drivers/char/misc.c:misc_open
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/base/map.c:kobj_lookup
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/loop.c:loop_set_status
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/ppp/ppp_generic.c:find_compressor
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/serio/serio.c:serio_queue_event
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/dm.c:dm_create
  - drivers/md/dm-target.c:get_target_type
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
  - net/socket.c:__sock_create
  - net/socket.c:__sock_create
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:lookup_rules_ops
  - net/core/lwtunnel.c:lwtunnel_build_state
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_lookup_default
  - net/sched/cls_api.c:tcf_proto_lookup_ops
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_set_ulp_id
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:xfrm_register_mode
```
**Symbols:**

```
ffffffff8112ea50-ffffffff8112eb08: try_module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool try_module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113a630)
Location: kernel/module.c:1115
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/clockevents.c:__clockevents_unbind
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/module.c:__symbol_get
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/bpf_trace.c:bpf_get_raw_tracepoint
  - mm/zpool.c:zpool_get_driver
  - fs/open.c:do_dentry_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:cdev_get
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:fs_name
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/nls/nls_base.c:find_nls
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:open_proxy_open
  - fs/pstore/platform.c:pstore_register
  - crypto/api.c:crypto_mod_get
  - crypto/algapi.c:__crypto_lookup_template
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - block/genhd.c:get_disk_and_module
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/gpio/gpiolib.c:gpiochip_reqres_irq
  - drivers/pwm/core.c:pwm_device_request
  - drivers/pci/pci.c:pci_reset_hotplug_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
  - drivers/pci/hotplug/acpiphp_core.c:get_attention_status
  - drivers/pci/hotplug/acpiphp_core.c:set_attention_status
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_mport_scan
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/video/fbdev/core/fbcon.c:con2fb_acquire_newinfo
  - drivers/acpi/osl.c:acpi_debugger_notify_command_complete
  - drivers/acpi/osl.c:acpi_debugger_wait_command_ready
  - drivers/acpi/osl.c:acpi_debugger_read_cmd
  - drivers/acpi/osl.c:acpi_debugger_write_log
  - drivers/acpi/osl.c:acpi_debugger_create_thread
  - drivers/clk/clk.c:__clk_get
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/reset/core.c:__reset_control_get_from_lookup
  - drivers/tty/tty_ldisc.c:get_ldops
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/serial/kgdboc.c:kgdboc_pre_exp_handler
  - drivers/char/misc.c:misc_open
  - drivers/char/misc.c:misc_open
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/base/map.c:kobj_lookup
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/loop.c:loop_set_status
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/ppp/ppp_generic.c:find_compressor
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/serio/serio.c:serio_queue_event
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/dm.c:dm_create
  - drivers/md/dm-target.c:get_target_type
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - net/socket.c:__sock_create
  - net/socket.c:__sock_create
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:lookup_rules_ops
  - net/core/lwtunnel.c:lwtunnel_build_state
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_lookup_default
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:xfrm_register_mode
```
**Symbols:**

```
ffffffff8113a630-ffffffff8113a6e8: try_module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool try_module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81145f10)
Location: kernel/module.c:1111
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
  - kernel/irq/manage.c:__setup_irq
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/clockevents.c:__clockevents_unbind
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/module.c:__symbol_get
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/bpf_trace.c:bpf_get_raw_tracepoint
  - kernel/events/core.c:perf_try_init_event
  - mm/zpool.c:zpool_get_driver
  - fs/open.c:do_dentry_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:cdev_get
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:fs_name
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/nls/nls_base.c:find_nls
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:open_proxy_open
  - fs/pstore/platform.c:pstore_register
  - crypto/api.c:crypto_mod_get
  - crypto/algapi.c:__crypto_lookup_template
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - block/genhd.c:get_disk_and_module
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/gpio/gpiolib.c:gpiochip_reqres_irq
  - drivers/pwm/core.c:pwm_device_request
  - drivers/pci/pci.c:pci_reset_hotplug_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
  - drivers/pci/hotplug/acpiphp_core.c:get_attention_status
  - drivers/pci/hotplug/acpiphp_core.c:set_attention_status
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_mport_scan
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/video/fbdev/core/fbcon.c:con2fb_acquire_newinfo
  - drivers/acpi/osl.c:acpi_debugger_notify_command_complete
  - drivers/acpi/osl.c:acpi_debugger_wait_command_ready
  - drivers/acpi/osl.c:acpi_debugger_read_cmd
  - drivers/acpi/osl.c:acpi_debugger_write_log
  - drivers/acpi/osl.c:acpi_debugger_create_thread
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/tty/tty_ldisc.c:get_ldops
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/serial/kgdboc.c:kgdboc_pre_exp_handler
  - drivers/char/misc.c:misc_open
  - drivers/char/misc.c:misc_open
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/base/map.c:kobj_lookup
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/loop.c:loop_set_status
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/ppp/ppp_generic.c:find_compressor
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/serio/serio.c:serio_queue_event
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-target.c:get_target_type
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
  - net/socket.c:__sock_create
  - net/socket.c:__sock_create
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:lookup_rules_ops
  - net/core/lwtunnel.c:lwtunnel_build_state
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_lookup_default
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffff81145f10-ffffffff81145fd8: try_module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool try_module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81151aa0)
Location: kernel/module.c:1125
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
  - kernel/irq/manage.c:__setup_irq
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/clockevents.c:__clockevents_unbind
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/module.c:__symbol_get
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/bpf_trace.c:bpf_get_raw_tracepoint
  - kernel/events/core.c:perf_try_init_event
  - mm/zpool.c:zpool_get_driver
  - fs/open.c:do_dentry_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:cdev_get
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:fs_name
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/nls/nls_base.c:find_nls
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:open_proxy_open
  - fs/pstore/platform.c:pstore_register
  - crypto/api.c:crypto_mod_get
  - crypto/algapi.c:__crypto_lookup_template
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - block/elevator.c:elevator_init_mq
  - block/elevator.c:elevator_get
  - block/genhd.c:get_disk_and_module
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/gpio/gpiolib.c:gpiochip_reqres_irq
  - drivers/pwm/core.c:pwm_device_request
  - drivers/pci/pci.c:pci_reset_hotplug_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
  - drivers/pci/hotplug/acpiphp_core.c:get_attention_status
  - drivers/pci/hotplug/acpiphp_core.c:set_attention_status
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_mport_scan
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/video/fbdev/core/fbcon.c:con2fb_acquire_newinfo
  - drivers/acpi/osl.c:acpi_debugger_notify_command_complete
  - drivers/acpi/osl.c:acpi_debugger_wait_command_ready
  - drivers/acpi/osl.c:acpi_debugger_read_cmd
  - drivers/acpi/osl.c:acpi_debugger_write_log
  - drivers/acpi/osl.c:acpi_debugger_create_thread
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/tty/tty_ldisc.c:get_ldops
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/serial/kgdboc.c:kgdboc_pre_exp_handler
  - drivers/char/misc.c:misc_open
  - drivers/char/misc.c:misc_open
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/base/map.c:kobj_lookup
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/loop.c:loop_set_status
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/ppp/ppp_generic.c:find_compressor
  - drivers/vfio/vfio.c:vfio_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_ioctl_check_extension
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_open
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/serio/serio.c:serio_queue_event
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-target.c:get_target_type
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
  - net/socket.c:__sock_create
  - net/socket.c:__sock_create
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:lookup_rules_ops
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/lwtunnel.c:lwtunnel_build_state
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_lookup_default
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffff81151aa0-ffffffff81151b68: try_module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool try_module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811636a0)
Location: kernel/module.c:1128
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
  - kernel/irq/manage.c:__setup_irq
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/clockevents.c:clockevents_replace
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/module.c:__symbol_get
  - kernel/kprobes.c:check_kprobe_address_safe
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/bpf_trace.c:bpf_get_raw_tracepoint
  - kernel/events/core.c:perf_try_init_event
  - mm/zpool.c:zpool_get_driver
  - fs/open.c:do_dentry_open
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/exec.c:search_binary_handler
  - fs/exec.c:search_binary_handler
  - fs/exec.c:__do_sys_uselib
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:fs_name
  - fs/quota/dquot.c:find_quota_format
  - fs/quota/dquot.c:find_quota_format
  - fs/configfs/file.c:__configfs_open_file
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/nls/nls_base.c:find_nls
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:open_proxy_open
  - crypto/api.c:crypto_mod_get
  - crypto/algapi.c:__crypto_lookup_template
  - crypto/algboss.c:cryptomgr_schedule_test
  - crypto/algboss.c:cryptomgr_schedule_probe
  - block/elevator.c:elevator_init_mq
  - block/elevator.c:elevator_get
  - block/genhd.c:exact_lock
  - drivers/phy/phy-core.c:phy_get
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
  - drivers/pwm/core.c:pwm_device_request
  - drivers/pci/pci.c:pci_reset_hotplug_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
  - drivers/pci/hotplug/acpiphp_core.c:get_attention_status
  - drivers/pci/hotplug/acpiphp_core.c:set_attention_status
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_bind
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:disc_work_handler
  - drivers/rapidio/rio.c:rio_mport_scan
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/video/fbdev/core/fbcon.c:con2fb_acquire_newinfo
  - drivers/acpi/osl.c:acpi_debugger_notify_command_complete
  - drivers/acpi/osl.c:acpi_debugger_wait_command_ready
  - drivers/acpi/osl.c:acpi_debugger_read_cmd
  - drivers/acpi/osl.c:acpi_debugger_write_log
  - drivers/acpi/osl.c:acpi_debugger_create_thread
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/reset/core.c:__reset_control_get_internal
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_ldisc.c:get_ldops
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/vt/vt.c:do_register_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/serial/kgdboc.c:kgdboc_pre_exp_handler
  - drivers/char/misc.c:misc_open
  - drivers/char/misc.c:misc_open
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/base/map.c:kobj_lookup
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/loop.c:loop_set_status_from_info
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/ppp/ppp_generic.c:find_compressor
  - drivers/vfio/vfio.c:vfio_ioctl_set_iommu
  - drivers/vfio/vfio.c:vfio_ioctl_check_extension
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_open
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/serio/serio.c:serio_queue_event
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-target.c:get_target_type
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_main_kobj_setup
  - drivers/cpufreq/cpufreq.c:get_governor
  - drivers/cpuidle/cpuidle.c:__cpuidle_register_device
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_get
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
  - drivers/nvmem/core.c:__nvmem_device_get
  - net/socket.c:__sock_create
  - net/socket.c:__sock_create
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_rules_seq_read
  - net/core/fib_rules.c:fib_rules_dump
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/lwtunnel.c:lwtunnel_build_state
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
  - net/sched/ematch.c:tcf_em_lookup
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_create
  - net/netfilter/nf_log.c:nf_logger_find_get
  - net/ipv4/tcp_output.c:tcp_ca_dst_init
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - virt/lib/irqbypass.c:irq_bypass_register_consumer
  - virt/lib/irqbypass.c:irq_bypass_register_producer
```
**Symbols:**

```
ffffffff811636a0-ffffffff81163768: try_module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool try_module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8115dde0)
Location: kernel/module.c:1161
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
  - kernel/irq/manage.c:__setup_irq
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/clockevents.c:clockevents_replace
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/module.c:__symbol_get
  - kernel/module.c:resolve_symbol
  - kernel/kprobes.c:check_kprobe_address_safe
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/bpf_trace.c:bpf_get_raw_tracepoint
  - kernel/static_call.c:__static_call_mod_text_reserved
  - kernel/events/core.c:perf_try_init_event
  - kernel/jump_label.c:__jump_label_mod_text_reserved
  - mm/zpool.c:zpool_get_driver
  - fs/open.c:do_dentry_open
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/exec.c:search_binary_handler
  - fs/exec.c:search_binary_handler
  - fs/exec.c:__do_sys_uselib
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:fs_name
  - fs/block_dev.c:blkdev_get_no_open
  - fs/quota/dquot.c:find_quota_format
  - fs/quota/dquot.c:find_quota_format
  - fs/configfs/file.c:__configfs_open_file
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/nls/nls_base.c:find_nls
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:open_proxy_open
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:__crypto_lookup_template
  - crypto/algboss.c:cryptomgr_schedule_test
  - crypto/algboss.c:cryptomgr_schedule_probe
  - block/elevator.c:elevator_init_mq
  - block/elevator.c:elevator_get
  - drivers/phy/phy-core.c:phy_get
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
  - drivers/pwm/core.c:pwm_device_request
  - drivers/pci/pci.c:pci_reset_hotplug_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
  - drivers/pci/hotplug/acpiphp_core.c:get_attention_status
  - drivers/pci/hotplug/acpiphp_core.c:set_attention_status
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_bind
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:disc_work_handler
  - drivers/rapidio/rio.c:rio_mport_scan
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/video/fbdev/core/fbcon.c:con2fb_acquire_newinfo
  - drivers/acpi/osl.c:acpi_debugger_notify_command_complete
  - drivers/acpi/osl.c:acpi_debugger_wait_command_ready
  - drivers/acpi/osl.c:acpi_debugger_read_cmd
  - drivers/acpi/osl.c:acpi_debugger_write_log
  - drivers/acpi/osl.c:acpi_debugger_create_thread
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/reset/core.c:__reset_control_get_internal
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_ldisc.c:get_ldops
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/vt/vt.c:do_register_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/serial/kgdboc.c:kgdboc_pre_exp_handler
  - drivers/char/misc.c:misc_open
  - drivers/char/misc.c:misc_open
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/base/map.c:kobj_lookup
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/loop.c:loop_set_status_from_info
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/ppp/ppp_generic.c:find_compressor
  - drivers/vfio/vfio.c:vfio_ioctl_set_iommu
  - drivers/vfio/vfio.c:vfio_ioctl_check_extension
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_open
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/usb/roles/class.c:fwnode_usb_role_switch_get
  - drivers/usb/roles/class.c:usb_role_switch_get
  - drivers/input/serio/serio.c:serio_queue_event
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-target.c:get_target_type
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_main_kobj_setup
  - drivers/cpufreq/cpufreq.c:get_governor
  - drivers/cpuidle/cpuidle.c:__cpuidle_register_device
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_get
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
  - drivers/nvmem/core.c:__nvmem_device_get
  - net/socket.c:__sock_create
  - net/socket.c:__sock_create
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:lookup_rules_ops
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/lwtunnel.c:lwtunnel_build_state
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
  - net/sched/ematch.c:tcf_em_lookup
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_create
  - net/netfilter/nf_log.c:nf_logger_find_get
  - net/ipv4/tcp_output.c:tcp_ca_dst_init
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - virt/lib/irqbypass.c:irq_bypass_register_consumer
  - virt/lib/irqbypass.c:irq_bypass_register_producer
```
**Symbols:**

```
ffffffff8115dde0-ffffffff8115de6f: try_module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool try_module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811600a0)
Location: kernel/module.c:1069
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
  - kernel/irq/manage.c:__setup_irq
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/clockevents.c:__clockevents_unbind
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/module.c:__symbol_get
  - kernel/module.c:ref_module
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/bpf_trace.c:bpf_get_raw_tracepoint
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/btf.c:btf_try_get_module
  - kernel/static_call.c:static_call_text_reserved
  - kernel/events/core.c:perf_try_init_event
  - kernel/jump_label.c:jump_label_text_reserved
  - mm/zpool.c:zpool_get_driver
  - fs/open.c:do_dentry_open
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/exec.c:search_binary_handler
  - fs/exec.c:search_binary_handler
  - fs/exec.c:__do_sys_uselib
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:fs_name
  - fs/block_dev.c:blkdev_get_no_open
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/configfs/file.c:__configfs_open_file
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/nls/nls_base.c:find_nls
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:open_proxy_open
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:__crypto_lookup_template
  - crypto/algboss.c:cryptomgr_schedule_test
  - crypto/algboss.c:cryptomgr_schedule_probe
  - block/elevator.c:elevator_init_mq
  - block/elevator.c:elevator_get
  - drivers/phy/phy-core.c:phy_get
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
  - drivers/pwm/core.c:pwm_device_request
  - drivers/pci/pci.c:pci_reset_hotplug_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
  - drivers/pci/hotplug/acpiphp_core.c:get_attention_status
  - drivers/pci/hotplug/acpiphp_core.c:set_attention_status
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_bind
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:disc_work_handler
  - drivers/rapidio/rio.c:rio_mport_scan
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/video/fbdev/core/fbcon.c:con2fb_acquire_newinfo
  - drivers/acpi/osl.c:acpi_debugger_notify_command_complete
  - drivers/acpi/osl.c:acpi_debugger_wait_command_ready
  - drivers/acpi/osl.c:acpi_debugger_read_cmd
  - drivers/acpi/osl.c:acpi_debugger_write_log
  - drivers/acpi/osl.c:acpi_debugger_create_thread
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/reset/core.c:__reset_control_get_internal
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_ldisc.c:get_ldops
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/vt/vt.c:do_register_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/serial/kgdboc.c:kgdboc_pre_exp_handler
  - drivers/char/misc.c:misc_open
  - drivers/char/misc.c:misc_open
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/base/map.c:kobj_lookup
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/loop.c:loop_set_status_from_info
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/ppp/ppp_generic.c:find_compressor
  - drivers/vfio/vfio.c:vfio_ioctl_set_iommu
  - drivers/vfio/vfio.c:vfio_ioctl_check_extension
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_open
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/usb/roles/class.c:usb_role_switch_find_by_fwnode
  - drivers/usb/roles/class.c:fwnode_usb_role_switch_get
  - drivers/usb/roles/class.c:usb_role_switch_get
  - drivers/input/serio/serio.c:serio_queue_event
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-target.c:get_target_type
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:get_governor
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_get
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
  - drivers/nvmem/core.c:__nvmem_device_get
  - net/socket.c:__sock_create
  - net/socket.c:__sock_create
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:lookup_rules_ops
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/lwtunnel.c:lwtunnel_build_state
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
  - net/sched/ematch.c:tcf_em_lookup
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - virt/lib/irqbypass.c:irq_bypass_register_consumer
  - virt/lib/irqbypass.c:irq_bypass_register_producer
```
**Symbols:**

```
ffffffff811600a0-ffffffff8116012f: try_module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool try_module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81185250)
Location: kernel/module.c:1069
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
  - kernel/irq/manage.c:__setup_irq
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/clockevents.c:__clockevents_unbind
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/module.c:__symbol_get
  - kernel/module.c:ref_module
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/bpf_trace.c:bpf_get_raw_tracepoint
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/btf.c:btf_try_get_module
  - kernel/static_call.c:static_call_text_reserved
  - kernel/events/core.c:perf_try_init_event
  - kernel/jump_label.c:jump_label_text_reserved
  - mm/zpool.c:zpool_get_driver
  - fs/open.c:do_dentry_open
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/exec.c:search_binary_handler
  - fs/exec.c:search_binary_handler
  - fs/exec.c:__do_sys_uselib
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:fs_name
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/configfs/file.c:__configfs_open_file
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/nls/nls_base.c:find_nls
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:open_proxy_open
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:__crypto_lookup_template
  - crypto/algboss.c:cryptomgr_schedule_test
  - crypto/algboss.c:cryptomgr_schedule_probe
  - block/bdev.c:blkdev_get_no_open
  - block/elevator.c:elevator_init_mq
  - block/elevator.c:elevator_get
  - drivers/phy/phy-core.c:phy_get
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
  - drivers/pwm/core.c:pwm_device_request
  - drivers/pci/pci.c:pci_reset_hotplug_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
  - drivers/pci/hotplug/acpiphp_core.c:get_attention_status
  - drivers/pci/hotplug/acpiphp_core.c:set_attention_status
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_bind
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:disc_work_handler
  - drivers/rapidio/rio.c:rio_mport_scan
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/video/fbdev/core/fbcon.c:con2fb_acquire_newinfo
  - drivers/acpi/osl.c:acpi_debugger_notify_command_complete
  - drivers/acpi/osl.c:acpi_debugger_wait_command_ready
  - drivers/acpi/osl.c:acpi_debugger_read_cmd
  - drivers/acpi/osl.c:acpi_debugger_write_log
  - drivers/acpi/osl.c:acpi_debugger_create_thread
  - drivers/acpi/processor_perflib.c:acpi_processor_notify_smm
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/reset/core.c:__reset_control_get_internal
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_ldisc.c:tty_ldiscs_seq_show
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/vt/vt.c:do_register_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/serial/kgdboc.c:kgdboc_pre_exp_handler
  - drivers/char/misc.c:misc_open
  - drivers/char/misc.c:misc_open
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/base/map.c:kobj_lookup
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/loop.c:loop_set_status_from_info
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/ppp/ppp_generic.c:find_compressor
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - drivers/vfio/vfio.c:vfio_ioctl_set_iommu
  - drivers/vfio/vfio.c:vfio_ioctl_check_extension
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/usb/roles/class.c:usb_role_switch_find_by_fwnode
  - drivers/usb/roles/class.c:fwnode_usb_role_switch_get
  - drivers/usb/roles/class.c:usb_role_switch_get
  - drivers/input/serio/serio.c:serio_queue_event
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-target.c:get_target_type
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:get_governor
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_get
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
  - drivers/nvmem/core.c:__nvmem_device_get
  - net/socket.c:__sock_create
  - net/socket.c:__sock_create
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:lookup_rules_ops
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/lwtunnel.c:lwtunnel_build_state
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
  - net/sched/ematch.c:tcf_em_lookup
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - virt/lib/irqbypass.c:irq_bypass_register_consumer
  - virt/lib/irqbypass.c:irq_bypass_register_producer
```
**Symbols:**

```
ffffffff81185250-ffffffff811852dc: try_module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool try_module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff8118be20)
Location: kernel/module/main.c:823
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
  - kernel/irq/manage.c:__setup_irq
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/module/main.c:__symbol_get
  - kernel/module/main.c:ref_module
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/clockevents.c:__clockevents_unbind
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/kprobes.c:check_kprobe_address_safe
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/bpf_trace.c:bpf_get_raw_tracepoint
  - kernel/bpf/syscall.c:bpf_map_copy_kptr_off_tab
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/btf.c:btf_try_get_module
  - kernel/static_call_inline.c:static_call_text_reserved
  - kernel/events/core.c:perf_try_init_event
  - kernel/jump_label.c:jump_label_text_reserved
  - mm/zpool.c:zpool_get_driver
  - fs/open.c:do_dentry_open
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/exec.c:search_binary_handler
  - fs/exec.c:search_binary_handler
  - fs/exec.c:__do_sys_uselib
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:fs_name
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/configfs/file.c:__configfs_open_file
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/nls/nls_base.c:find_nls
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:open_proxy_open
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:__crypto_lookup_template
  - crypto/algboss.c:cryptomgr_schedule_test
  - crypto/algboss.c:cryptomgr_schedule_probe
  - block/elevator.c:elevator_init_mq
  - block/elevator.c:elevator_get
  - drivers/phy/phy-core.c:phy_get
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
  - drivers/pwm/core.c:pwm_device_request
  - drivers/pci/pci.c:pci_reset_hotplug_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
  - drivers/pci/hotplug/acpiphp_core.c:get_attention_status
  - drivers/pci/hotplug/acpiphp_core.c:set_attention_status
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_bind
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:disc_work_handler
  - drivers/rapidio/rio.c:rio_mport_scan
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_open
  - drivers/acpi/osl.c:acpi_debugger_notify_command_complete
  - drivers/acpi/osl.c:acpi_debugger_wait_command_ready
  - drivers/acpi/osl.c:acpi_debugger_read_cmd
  - drivers/acpi/osl.c:acpi_debugger_write_log
  - drivers/acpi/osl.c:acpi_debugger_create_thread
  - drivers/acpi/processor_perflib.c:acpi_processor_notify_smm
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/reset/core.c:__reset_control_get_internal
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_ldisc.c:tty_ldiscs_seq_show
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/vt/vt.c:do_register_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/char/misc.c:misc_open
  - drivers/char/misc.c:misc_open
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/base/map.c:kobj_lookup
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/ppp/ppp_generic.c:find_compressor
  - drivers/vfio/vfio.c:vfio_device_open
  - drivers/vfio/vfio.c:vfio_ioctl_set_iommu
  - drivers/vfio/vfio.c:vfio_ioctl_check_extension
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/usb/roles/class.c:usb_role_switch_find_by_fwnode
  - drivers/usb/roles/class.c:fwnode_usb_role_switch_get
  - drivers/usb/roles/class.c:usb_role_switch_get
  - drivers/input/serio/serio.c:serio_queue_event
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-target.c:get_target_type
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_init_governor
  - drivers/cpufreq/cpufreq.c:get_governor
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_get
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
  - drivers/nvmem/core.c:__nvmem_device_get
  - drivers/hte/hte.c:hte_ts_get
  - net/socket.c:__sock_create
  - net/socket.c:__sock_create
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_rules_seq_read
  - net/core/fib_rules.c:fib_rules_dump
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/lwtunnel.c:lwtunnel_build_state
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
  - net/sched/ematch.c:tcf_em_lookup
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - virt/lib/irqbypass.c:irq_bypass_register_consumer
  - virt/lib/irqbypass.c:irq_bypass_register_producer
```
**Symbols:**

```
ffffffff8118be20-ffffffff8118bed1: try_module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool try_module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811c8550)
Location: kernel/module/main.c:826
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/module/main.c:__symbol_get
  - kernel/module/main.c:ref_module
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/clockevents.c:__clockevents_unbind
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/kprobes.c:check_kprobe_address_safe
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/bpf_trace.c:module_callback
  - kernel/trace/bpf_trace.c:bpf_get_raw_tracepoint
  - kernel/bpf/syscall.c:btf_record_dup
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/btf.c:btf_try_get_module
  - kernel/static_call_inline.c:static_call_text_reserved
  - kernel/events/core.c:perf_try_init_event
  - kernel/jump_label.c:jump_label_text_reserved
  - mm/zpool.c:zpool_get_driver
  - fs/open.c:do_dentry_open
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/exec.c:search_binary_handler
  - fs/exec.c:search_binary_handler
  - fs/exec.c:__do_sys_uselib
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:fs_name
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/configfs/file.c:__configfs_open_file
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/nls/nls_base.c:find_nls
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:open_proxy_open
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:__crypto_lookup_template
  - crypto/algboss.c:cryptomgr_schedule_probe
  - block/elevator.c:elevator_init_mq
  - block/elevator.c:elevator_find_get
  - drivers/phy/phy-core.c:phy_get
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/gpio/gpiolib.c:gpiochip_reqres_irq
  - drivers/pwm/core.c:pwm_device_request
  - drivers/pci/pci.c:pci_reset_hotplug_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
  - drivers/pci/hotplug/acpiphp_core.c:get_attention_status
  - drivers/pci/hotplug/acpiphp_core.c:set_attention_status
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_bind
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:disc_work_handler
  - drivers/rapidio/rio.c:rio_mport_scan
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_open
  - drivers/acpi/osl.c:acpi_debugger_notify_command_complete
  - drivers/acpi/osl.c:acpi_debugger_wait_command_ready
  - drivers/acpi/osl.c:acpi_debugger_read_cmd
  - drivers/acpi/osl.c:acpi_debugger_write_log
  - drivers/acpi/osl.c:acpi_debugger_create_thread
  - drivers/acpi/processor_perflib.c:acpi_processor_notify_smm
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/reset/core.c:__reset_control_get_internal
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_ldisc.c:tty_ldiscs_seq_show
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/vt/vt.c:do_register_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/char/misc.c:misc_open
  - drivers/char/misc.c:misc_open
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/base/map.c:kobj_lookup
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/ppp/ppp_generic.c:find_compressor
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/usb/roles/class.c:usb_role_switch_find_by_fwnode
  - drivers/usb/roles/class.c:fwnode_usb_role_switch_get
  - drivers/usb/roles/class.c:usb_role_switch_get
  - drivers/input/serio/serio.c:serio_queue_event
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-target.c:get_target_type
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_init_governor
  - drivers/cpufreq/cpufreq.c:get_governor
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_get
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
  - drivers/nvmem/core.c:__nvmem_device_get
  - drivers/hte/hte.c:hte_ts_get
  - net/socket.c:__sock_create
  - net/socket.c:__sock_create
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_rules_seq_read
  - net/core/fib_rules.c:fib_rules_dump
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/lwtunnel.c:lwtunnel_build_state
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
  - net/sched/ematch.c:tcf_em_lookup
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
**Symbols:**

```
ffffffff811c8550-ffffffff811c8601: try_module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool try_module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811db4c0)
Location: kernel/module/main.c:829
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/module/main.c:__symbol_get
  - kernel/module/main.c:resolve_symbol
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/clockevents.c:__clockevents_unbind
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/kprobes.c:check_kprobe_address_safe
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/bpf_trace.c:get_modules_for_addrs
  - kernel/trace/bpf_trace.c:bpf_get_raw_tracepoint
  - kernel/bpf/syscall.c:btf_record_dup
  - kernel/bpf/btf.c:btf_try_get_module
  - kernel/static_call_inline.c:static_call_text_reserved
  - kernel/events/core.c:perf_try_init_event
  - kernel/jump_label.c:jump_label_text_reserved
  - mm/zpool.c:zpool_get_driver
  - fs/open.c:do_dentry_open
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/exec.c:search_binary_handler
  - fs/exec.c:search_binary_handler
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:fs_name
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/configfs/file.c:__configfs_open_file
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/nls/nls_base.c:find_nls
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:open_proxy_open
  - crypto/api.c:crypto_clone_tfm
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:__crypto_lookup_template
  - crypto/algboss.c:cryptomgr_schedule_probe
  - block/elevator.c:elevator_init_mq
  - block/elevator.c:elevator_find_get
  - drivers/phy/phy-core.c:phy_get
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/gpio/gpiolib.c:gpiochip_reqres_irq
  - drivers/pwm/core.c:pwm_device_request
  - drivers/pci/pci.c:pci_reset_hotplug_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
  - drivers/pci/hotplug/acpiphp_core.c:get_attention_status
  - drivers/pci/hotplug/acpiphp_core.c:set_attention_status
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_bind
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:disc_work_handler
  - drivers/rapidio/rio.c:rio_mport_scan
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_open
  - drivers/acpi/osl.c:acpi_debugger_notify_command_complete
  - drivers/acpi/osl.c:acpi_debugger_wait_command_ready
  - drivers/acpi/osl.c:acpi_debugger_read_cmd
  - drivers/acpi/osl.c:acpi_debugger_write_log
  - drivers/acpi/osl.c:acpi_debugger_create_thread
  - drivers/acpi/processor_perflib.c:acpi_processor_notify_smm
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/reset/core.c:__reset_control_get_internal
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_ldisc.c:tty_ldiscs_seq_show
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/vt/vt.c:do_register_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/char/misc.c:misc_open
  - drivers/char/misc.c:misc_open
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/base/map.c:kobj_lookup
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/sysfs_upload.c:firmware_upload_register
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/ppp/ppp_generic.c:find_compressor
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/usb/roles/class.c:usb_role_switch_find_by_fwnode
  - drivers/usb/roles/class.c:fwnode_usb_role_switch_get
  - drivers/usb/roles/class.c:usb_role_switch_get
  - drivers/input/serio/serio.c:serio_queue_event
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter_by_fwnode
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-target.c:get_target_type
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_init_governor
  - drivers/cpufreq/cpufreq.c:get_governor
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
  - drivers/leds/led-class.c:led_get
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_get
  - drivers/mailbox/mailbox.c:mbox_bind_client
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
  - drivers/nvmem/core.c:__nvmem_device_get
  - drivers/hte/hte.c:hte_ts_get
  - net/socket.c:__sock_create
  - net/socket.c:__sock_create
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_rules_seq_read
  - net/core/fib_rules.c:fib_rules_dump
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/lwtunnel.c:lwtunnel_build_state
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
  - net/sched/ematch.c:tcf_em_lookup
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
**Symbols:**

```
ffffffff811db4c0-ffffffff811db57c: try_module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool try_module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811f1170)
Location: kernel/module/main.c:829
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/module/main.c:__symbol_get
  - kernel/module/main.c:ref_module
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/clockevents.c:__clockevents_unbind
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/kprobes.c:check_kprobe_address_safe
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/bpf_trace.c:get_modules_for_addrs
  - kernel/trace/bpf_trace.c:bpf_get_raw_tracepoint
  - kernel/bpf/syscall.c:btf_record_dup
  - kernel/bpf/btf.c:btf_try_get_module
  - kernel/static_call_inline.c:static_call_text_reserved
  - kernel/events/core.c:perf_try_init_event
  - kernel/jump_label.c:jump_label_text_reserved
  - mm/zpool.c:zpool_get_driver
  - fs/open.c:do_dentry_open
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/exec.c:search_binary_handler
  - fs/exec.c:search_binary_handler
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:fs_name
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/configfs/file.c:__configfs_open_file
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/nls/nls_base.c:find_nls
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:open_proxy_open
  - crypto/api.c:crypto_clone_tfm
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:__crypto_lookup_template
  - crypto/algboss.c:cryptomgr_schedule_probe
  - block/bdev.c:bdev_open_by_dev
  - block/bdev.c:bdev_open_by_dev
  - block/elevator.c:elevator_init_mq
  - block/elevator.c:elevator_find_get
  - drivers/phy/phy-core.c:phy_get
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/gpio/gpiolib.c:gpiochip_reqres_irq
  - drivers/pwm/core.c:pwm_device_request
  - drivers/pci/pci.c:pci_reset_hotplug_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
  - drivers/pci/hotplug/acpiphp_core.c:get_attention_status
  - drivers/pci/hotplug/acpiphp_core.c:set_attention_status
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_bind
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:disc_work_handler
  - drivers/rapidio/rio.c:rio_mport_scan
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/video/fbdev/core/fb_chrdev.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_open
  - drivers/acpi/osl.c:acpi_debugger_notify_command_complete
  - drivers/acpi/osl.c:acpi_debugger_wait_command_ready
  - drivers/acpi/osl.c:acpi_debugger_read_cmd
  - drivers/acpi/osl.c:acpi_debugger_write_log
  - drivers/acpi/osl.c:acpi_debugger_create_thread
  - drivers/acpi/processor_perflib.c:acpi_processor_notify_smm
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/reset/core.c:__reset_control_get_internal
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_ldisc.c:tty_ldiscs_seq_show
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/vt/vt.c:do_register_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/char/misc.c:misc_open
  - drivers/char/misc.c:misc_open
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/iommu/iommu.c:iommu_init_device
  - drivers/base/map.c:kobj_lookup
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/sysfs_upload.c:firmware_upload_register
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/gpu/drm/drm_drv.c:drm_stub_open
  - drivers/accel/drm_accel.c:accel_stub_open
  - drivers/gpu/drm/drm_encoder_slave.c:drm_i2c_encoder_init
  - drivers/gpu/drm/drm_fbdev_generic.c:drm_fbdev_generic_fb_open
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/ppp/ppp_generic.c:find_compressor
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/usb/roles/class.c:usb_role_switch_find_by_fwnode
  - drivers/usb/roles/class.c:fwnode_usb_role_switch_get
  - drivers/usb/roles/class.c:usb_role_switch_get
  - drivers/input/serio/serio.c:serio_queue_event
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter_by_fwnode
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-target.c:get_target_type
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_init_governor
  - drivers/cpufreq/cpufreq.c:get_governor
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
  - drivers/leds/led-class.c:led_get
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_get
  - drivers/mailbox/mailbox.c:mbox_bind_client
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
  - drivers/nvmem/core.c:__nvmem_device_get
  - drivers/hte/hte.c:hte_ts_get
  - net/socket.c:__sock_create
  - net/socket.c:__sock_create
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_rules_seq_read
  - net/core/fib_rules.c:fib_rules_dump
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/lwtunnel.c:lwtunnel_build_state
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
  - net/sched/ematch.c:tcf_em_lookup
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_create
  - net/netfilter/nf_bpf_link.c:get_proto_defrag_hook
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/mptcp/sched.c:mptcp_init_sched
```
**Symbols:**

```
ffffffff811f1170-ffffffff811f122c: try_module_get (STB_GLOBAL)
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
bool try_module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101c2780)
Location: kernel/module.c:1125
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
  - kernel/irq/manage.c:__setup_irq
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/clockevents.c:__clockevents_unbind
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/module.c:__symbol_get
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/bpf_trace.c:bpf_get_raw_tracepoint
  - kernel/events/core.c:perf_try_init_event
  - mm/zpool.c:zpool_get_driver
  - fs/open.c:do_dentry_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:cdev_get
  - fs/exec.c:__arm64_sys_uselib
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:fs_name
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/nls/nls_base.c:find_nls
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:open_proxy_open
  - fs/pstore/platform.c:pstore_register
  - crypto/api.c:crypto_mod_get
  - crypto/algapi.c:__crypto_lookup_template
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - block/elevator.c:elevator_init_mq
  - block/genhd.c:get_disk_and_module
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:of_phy_get
  - drivers/phy/phy-core.c:_of_phy_get
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_reqres
  - drivers/gpio/gpiolib.c:gpiochip_reqres_irq
  - drivers/pwm/core.c:pwm_device_request
  - drivers/pci/pci.c:pci_reset_hotplug_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
  - drivers/pci/hotplug/acpiphp_core.c:get_attention_status
  - drivers/pci/hotplug/acpiphp_core.c:set_attention_status
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_mport_scan
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/video/fbdev/core/fbcon.c:con2fb_acquire_newinfo
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/reset/core.c:__reset_control_get_internal
  - drivers/tty/tty_ldisc.c:get_ldops
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/serial/kgdboc.c:kgdboc_pre_exp_handler
  - drivers/char/misc.c:misc_open
  - drivers/char/misc.c:misc_open
  - drivers/base/map.c:kobj_lookup
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/loop.c:loop_set_status
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/ppp/ppp_generic.c:find_compressor
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/phy/phy.c:devm_usb_get_phy_by_node
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/usb/roles/class.c:fwnode_usb_role_switch_get
  - drivers/usb/roles/class.c:usb_role_switch_get
  - drivers/input/serio/serio.c:serio_queue_event
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/i2c/i2c-core-of.c:of_get_i2c_adapter_by_node
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-target.c:get_target_type
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
  - drivers/mmc/core/pwrseq.c:mmc_pwrseq_alloc
  - drivers/mailbox/mailbox.c:mbox_request_channel
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
  - drivers/remoteproc/remoteproc_core.c:rproc_get_by_phandle
  - drivers/nvmem/core.c:__nvmem_device_get
  - net/socket.c:__sock_create
  - net/socket.c:__sock_create
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:lookup_rules_ops
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/lwtunnel.c:lwtunnel_build_state
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_lookup_default
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffff8000101c2780-ffff8000101c2890: try_module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool try_module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c0408ab0)
Location: kernel/module.c:1125
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
  - kernel/irq/manage.c:__setup_irq
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/clockevents.c:__clockevents_unbind
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/module.c:__symbol_get
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/bpf_trace.c:bpf_get_raw_tracepoint
  - kernel/events/core.c:perf_try_init_event
  - mm/zpool.c:zpool_get_driver
  - fs/open.c:do_dentry_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:cdev_get
  - fs/exec.c:__se_sys_uselib
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:__se_sys_sysfs
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/configfs/file.c:__configfs_open_file
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/nls/nls_base.c:find_nls
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:open_proxy_open
  - fs/pstore/platform.c:pstore_register
  - crypto/api.c:crypto_mod_get
  - crypto/algapi.c:__crypto_lookup_template
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - block/elevator.c:elevator_init_mq
  - block/elevator.c:elevator_get
  - block/genhd.c:get_disk_and_module
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:of_phy_get
  - drivers/phy/phy-core.c:_of_phy_get
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_reqres
  - drivers/gpio/gpiolib.c:gpiochip_reqres_irq
  - drivers/pwm/core.c:pwm_device_request
  - drivers/pci/pci.c:pci_reset_hotplug_slot
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_mport_scan
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/video/fbdev/core/fbcon.c:con2fb_acquire_newinfo
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/reset/core.c:__reset_control_get_internal
  - drivers/tty/tty_ldisc.c:get_ldops
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/serial/kgdboc.c:kgdboc_pre_exp_handler
  - drivers/char/misc.c:misc_open
  - drivers/char/misc.c:misc_open
  - drivers/base/map.c:kobj_lookup
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/loop.c:loop_set_status
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/mtd/mtdcore.c:__get_mtd_device
  - drivers/mtd/mtdpart.c:parse_mtd_partitions
  - drivers/mtd/mtdpart.c:mtd_part_parser_get
  - drivers/mtd/chips/chipreg.c:get_mtd_chip_driver
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/ppp/ppp_generic.c:find_compressor
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/phy/phy.c:devm_usb_get_phy_by_node
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/usb/roles/class.c:fwnode_usb_role_switch_get
  - drivers/usb/roles/class.c:usb_role_switch_get
  - drivers/input/serio/serio.c:serio_queue_event
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/i2c/i2c-core-of.c:of_get_i2c_adapter_by_node
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-target.c:get_target_type
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
  - drivers/mmc/core/pwrseq.c:mmc_pwrseq_alloc
  - drivers/mailbox/mailbox.c:mbox_request_channel
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
  - drivers/remoteproc/remoteproc_core.c:rproc_get_by_phandle
  - drivers/nvmem/core.c:__nvmem_device_get
  - sound/sound_core.c:soundcore_open
  - sound/sound_core.c:soundcore_open
  - sound/core/sound.c:snd_open
  - sound/core/init.c:snd_card_disconnect
  - sound/core/info.c:alloc_info_private
  - sound/core/timer.c:snd_timer_instance_new
  - sound/soc/soc-component.c:snd_soc_component_module_get
  - net/socket.c:__sock_create
  - net/socket.c:__sock_create
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:lookup_rules_ops
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/lwtunnel.c:lwtunnel_build_state
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_lookup_default
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
c0408ab0-c0408bb0: try_module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool try_module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c000000000226d30)
Location: kernel/module.c:1125
Inline: False
Direct callers:
  - arch/powerpc/kernel/eeh_driver.c:eeh_rmv_device
  - arch/powerpc/kernel/eeh_driver.c:eeh_add_virt_device
  - kernel/fork.c:dup_mm
  - kernel/irq/manage.c:__setup_irq
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/clockevents.c:__clockevents_unbind
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/module.c:__symbol_get
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/bpf_trace.c:bpf_get_raw_tracepoint
  - kernel/events/core.c:perf_try_init_event
  - mm/zpool.c:zpool_get_driver
  - fs/open.c:do_dentry_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:cdev_get
  - fs/exec.c:__se_sys_uselib
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:__se_sys_sysfs
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/configfs/file.c:__configfs_open_file
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/nls/nls_base.c:find_nls
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:open_proxy_open
  - fs/pstore/platform.c:pstore_register
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:__crypto_lookup_template
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - block/elevator.c:elevator_init_mq
  - block/elevator.c:elevator_get
  - block/genhd.c:get_disk_and_module
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:of_phy_get
  - drivers/phy/phy-core.c:_of_phy_get
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/gpio/gpiolib.c:gpiochip_reqres_irq
  - drivers/pwm/core.c:pwm_device_request
  - drivers/pci/pci.c:pci_reset_hotplug_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_mport_scan
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/video/fbdev/core/fbcon.c:con2fb_acquire_newinfo
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/reset/core.c:__reset_control_get_internal
  - drivers/tty/tty_ldisc.c:get_ldops
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/serial/kgdboc.c:kgdboc_pre_exp_handler
  - drivers/char/misc.c:misc_open
  - drivers/char/misc.c:misc_open
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/base/map.c:kobj_lookup
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/loop.c:loop_set_status
  - drivers/misc/cxl/base.c:cxl_slbia
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/ppp/ppp_generic.c:find_compressor
  - drivers/vfio/vfio.c:vfio_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_ioctl_check_extension
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_open
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/phy/phy.c:devm_usb_get_phy_by_node
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/serio/serio.c:serio_queue_event
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/i2c/i2c-core-of.c:of_get_i2c_adapter_by_node
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-target.c:get_target_type
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
  - drivers/mmc/core/pwrseq.c:mmc_pwrseq_alloc
  - drivers/mailbox/mailbox.c:mbox_request_channel
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
  - drivers/remoteproc/remoteproc_core.c:rproc_get_by_phandle
  - drivers/nvmem/core.c:__nvmem_device_get
  - net/socket.c:__sock_create
  - net/socket.c:__sock_create
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:lookup_rules_ops
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/lwtunnel.c:lwtunnel_build_state
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_lookup_default
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
c000000000226d30-c000000000226e58: try_module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool try_module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe000142e30)
Location: kernel/module.c:1125
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
  - kernel/irq/manage.c:__setup_irq
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/clockevents.c:__clockevents_unbind
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/module.c:__symbol_get
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/events/core.c:perf_try_init_event
  - mm/zpool.c:zpool_get_driver
  - fs/open.c:do_dentry_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:cdev_get
  - fs/exec.c:__se_sys_uselib
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:__se_sys_sysfs
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/configfs/file.c:__configfs_open_file
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/nls/nls_base.c:find_nls
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:open_proxy_open
  - fs/pstore/platform.c:pstore_register
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:__crypto_lookup_template
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - block/elevator.c:elevator_init_mq
  - block/elevator.c:elevator_get
  - block/genhd.c:get_disk_and_module
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:of_phy_get
  - drivers/phy/phy-core.c:_of_phy_get
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/gpio/gpiolib.c:gpiochip_reqres_irq
  - drivers/pwm/core.c:pwm_device_request
  - drivers/pci/pci.c:pci_reset_hotplug_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_mport_scan
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/video/fbdev/core/fbcon.c:con2fb_acquire_newinfo
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/reset/core.c:__reset_control_get_internal
  - drivers/tty/tty_ldisc.c:get_ldops
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/char/misc.c:misc_open
  - drivers/char/misc.c:misc_open
  - drivers/base/map.c:kobj_lookup
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/loop.c:loop_set_status
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/ppp/ppp_generic.c:find_compressor
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/phy/phy.c:devm_usb_get_phy_by_node
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/serio/serio.c:serio_queue_event
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/i2c/i2c-core-of.c:of_get_i2c_adapter_by_node
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-target.c:get_target_type
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/mmc/core/pwrseq.c:mmc_pwrseq_alloc
  - drivers/mailbox/mailbox.c:mbox_request_channel
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
  - drivers/nvmem/core.c:__nvmem_device_get
  - net/socket.c:__sock_create
  - net/socket.c:__sock_create
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:lookup_rules_ops
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/lwtunnel.c:lwtunnel_build_state
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_lookup_default
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffe000142e30-ffffffe000142ee8: try_module_get (STB_GLOBAL)
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
bool try_module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114a0c0)
Location: kernel/module.c:1125
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
  - kernel/irq/manage.c:__setup_irq
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/clockevents.c:__clockevents_unbind
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/module.c:__symbol_get
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/bpf_trace.c:bpf_get_raw_tracepoint
  - kernel/events/core.c:perf_try_init_event
  - mm/zpool.c:zpool_get_driver
  - fs/open.c:do_dentry_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:cdev_get
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:fs_name
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/nls/nls_base.c:find_nls
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:open_proxy_open
  - fs/pstore/platform.c:pstore_register
  - crypto/api.c:crypto_mod_get
  - crypto/algapi.c:__crypto_lookup_template
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - block/elevator.c:elevator_init_mq
  - block/elevator.c:elevator_get
  - block/genhd.c:get_disk_and_module
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/gpio/gpiolib.c:gpiochip_reqres_irq
  - drivers/pwm/core.c:pwm_device_request
  - drivers/pci/pci.c:pci_reset_hotplug_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
  - drivers/pci/hotplug/acpiphp_core.c:get_attention_status
  - drivers/pci/hotplug/acpiphp_core.c:set_attention_status
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_mport_scan
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/video/fbdev/core/fbcon.c:con2fb_acquire_newinfo
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/tty/tty_ldisc.c:get_ldops
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/serial/kgdboc.c:kgdboc_pre_exp_handler
  - drivers/char/misc.c:misc_open
  - drivers/char/misc.c:misc_open
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/base/map.c:kobj_lookup
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/loop.c:loop_set_status
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/nvme/host/core.c:nvme_open
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/ppp/ppp_generic.c:find_compressor
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/serio/serio.c:serio_queue_event
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-target.c:get_target_type
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
  - net/socket.c:__sock_create
  - net/socket.c:__sock_create
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:lookup_rules_ops
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/lwtunnel.c:lwtunnel_build_state
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_lookup_default
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffff8114a0c0-ffffffff8114a188: try_module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool try_module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113d370)
Location: kernel/module.c:1125
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
  - kernel/irq/manage.c:__setup_irq
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/clockevents.c:__clockevents_unbind
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/module.c:__symbol_get
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/bpf_trace.c:bpf_get_raw_tracepoint
  - kernel/events/core.c:perf_try_init_event
  - mm/zpool.c:zpool_get_driver
  - fs/open.c:do_dentry_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:cdev_get
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:fs_name
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/nls/nls_base.c:find_nls
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:open_proxy_open
  - fs/pstore/platform.c:pstore_register
  - crypto/api.c:crypto_mod_get
  - crypto/algapi.c:__crypto_lookup_template
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - block/elevator.c:elevator_init_mq
  - block/elevator.c:elevator_get
  - block/genhd.c:get_disk_and_module
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/gpio/gpiolib.c:gpiochip_reqres_irq
  - drivers/pci/pci.c:pci_reset_hotplug_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
  - drivers/pci/hotplug/acpiphp_core.c:get_attention_status
  - drivers/pci/hotplug/acpiphp_core.c:set_attention_status
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_mport_scan
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/video/fbdev/core/fbcon.c:con2fb_acquire_newinfo
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/tty/tty_ldisc.c:get_ldops
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/serial/kgdboc.c:kgdboc_pre_exp_handler
  - drivers/char/misc.c:misc_open
  - drivers/char/misc.c:misc_open
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/base/map.c:kobj_lookup
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/block/loop.c:loop_set_status
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/nvme/host/core.c:nvme_open
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/ppp/ppp_generic.c:find_compressor
  - drivers/vfio/vfio.c:vfio_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_ioctl_check_extension
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_open
  - drivers/usb/core/file.c:usb_open
  - drivers/input/serio/serio.c:serio_queue_event
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-target.c:get_target_type
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
  - net/socket.c:__sock_create
  - net/socket.c:__sock_create
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:lookup_rules_ops
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/lwtunnel.c:lwtunnel_build_state
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_lookup_default
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffff8113d370-ffffffff8113d438: try_module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool try_module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81147f70)
Location: kernel/module.c:1125
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
  - kernel/irq/manage.c:__setup_irq
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/clockevents.c:__clockevents_unbind
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/module.c:__symbol_get
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/bpf_trace.c:bpf_get_raw_tracepoint
  - kernel/events/core.c:perf_try_init_event
  - mm/zpool.c:zpool_get_driver
  - fs/open.c:do_dentry_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:cdev_get
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:fs_name
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/nls/nls_base.c:find_nls
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:open_proxy_open
  - fs/pstore/platform.c:pstore_register
  - crypto/api.c:crypto_mod_get
  - crypto/algapi.c:__crypto_lookup_template
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - block/elevator.c:elevator_init_mq
  - block/elevator.c:elevator_get
  - block/genhd.c:get_disk_and_module
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/gpio/gpiolib.c:gpiochip_reqres_irq
  - drivers/pwm/core.c:pwm_device_request
  - drivers/pci/pci.c:pci_reset_hotplug_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
  - drivers/pci/hotplug/acpiphp_core.c:get_attention_status
  - drivers/pci/hotplug/acpiphp_core.c:set_attention_status
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_mport_scan
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/video/fbdev/core/fbcon.c:con2fb_acquire_newinfo
  - drivers/acpi/osl.c:acpi_debugger_notify_command_complete
  - drivers/acpi/osl.c:acpi_debugger_wait_command_ready
  - drivers/acpi/osl.c:acpi_debugger_read_cmd
  - drivers/acpi/osl.c:acpi_debugger_write_log
  - drivers/acpi/osl.c:acpi_debugger_create_thread
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/tty/tty_ldisc.c:get_ldops
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/serial/kgdboc.c:kgdboc_pre_exp_handler
  - drivers/char/misc.c:misc_open
  - drivers/char/misc.c:misc_open
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/base/map.c:kobj_lookup
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/loop.c:loop_set_status
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/ppp/ppp_generic.c:find_compressor
  - drivers/vfio/vfio.c:vfio_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_ioctl_check_extension
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_open
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/serio/serio.c:serio_queue_event
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-target.c:get_target_type
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
  - net/socket.c:__sock_create
  - net/socket.c:__sock_create
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:lookup_rules_ops
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/lwtunnel.c:lwtunnel_build_state
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_lookup_default
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_create
  - net/netfilter/nfnetlink.c:nfnetlink_rcv_batch
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_config
  - net/netfilter/nfnetlink_log.c:nfulnl_recv_config
  - net/netfilter/nf_conntrack_helper.c:nf_nat_helper_try_module_get
  - net/netfilter/nf_conntrack_helper.c:nf_conntrack_helper_try_module_get
  - net/netfilter/nf_conntrack_proto.c:nf_ct_netns_do_get
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffff81147f70-ffffffff81148038: try_module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool try_module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81154b80)
Location: kernel/module.c:1125
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
  - kernel/irq/manage.c:__setup_irq
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/clockevents.c:__clockevents_unbind
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/module.c:__symbol_get
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/bpf_trace.c:bpf_get_raw_tracepoint
  - kernel/events/core.c:perf_try_init_event
  - mm/zpool.c:zpool_get_driver
  - fs/open.c:do_dentry_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:cdev_get
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:fs_name
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/nls/nls_base.c:find_nls
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:open_proxy_open
  - fs/pstore/platform.c:pstore_register
  - crypto/api.c:crypto_mod_get
  - crypto/algapi.c:__crypto_lookup_template
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - block/elevator.c:elevator_init_mq
  - block/elevator.c:elevator_get
  - block/genhd.c:get_disk_and_module
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/gpio/gpiolib.c:gpiochip_reqres_irq
  - drivers/pwm/core.c:pwm_device_request
  - drivers/pci/pci.c:pci_reset_hotplug_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:test_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:presence_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:latch_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:attention_read_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_write_file
  - drivers/pci/hotplug/pci_hotplug_core.c:power_read_file
  - drivers/pci/hotplug/acpiphp_core.c:get_attention_status
  - drivers/pci/hotplug/acpiphp_core.c:set_attention_status
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_mport_scan
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/video/fbdev/core/fbcon.c:con2fb_acquire_newinfo
  - drivers/acpi/osl.c:acpi_debugger_notify_command_complete
  - drivers/acpi/osl.c:acpi_debugger_wait_command_ready
  - drivers/acpi/osl.c:acpi_debugger_read_cmd
  - drivers/acpi/osl.c:acpi_debugger_write_log
  - drivers/acpi/osl.c:acpi_debugger_create_thread
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/tty/tty_ldisc.c:get_ldops
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/serial/kgdboc.c:kgdboc_pre_exp_handler
  - drivers/char/misc.c:misc_open
  - drivers/char/misc.c:misc_open
  - drivers/char/agp/backend.c:agp_add_bridge
  - drivers/base/map.c:kobj_lookup
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/loop.c:loop_set_status
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/ppp/ppp_generic.c:find_compressor
  - drivers/vfio/vfio.c:vfio_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_ioctl_check_extension
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_open
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/serio/serio.c:serio_queue_event
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-target.c:get_target_type
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
  - net/socket.c:__sock_create
  - net/socket.c:__sock_create
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sk_prot_alloc
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:lookup_rules_ops
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/lwtunnel.c:lwtunnel_build_state
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_lookup_default
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
  - net/sched/ematch.c:tcf_em_lookup
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffff81154b80-ffffffff81154c57: try_module_get (STB_GLOBAL)
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
