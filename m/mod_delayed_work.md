# Function: <code>mod_delayed_work</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81112bda)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_pidlist_stop
  - kernel/cgroup.c:css_free_work_fn
```
```
In mm/backing-dev.c (ffffffff811ae1b2)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_shutdown
```
```
In fs/fs-writeback.c (ffffffff81235cc6)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_wakeup
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:dirtytime_interval_handler
```
```
In block/blk-core.c (ffffffff813b56af)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - block/blk-core.c:blk_run_queue_async
```
```
In block/genhd.c (ffffffff813cba7c)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - block/genhd.c:disk_flush_events
```
```
In drivers/base/devcoredump.c (ffffffff8156c7bd)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
```
```
In drivers/power/charger-manager.c (ffffffff81680c47)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/power/charger-manager.c:_setup_polling
  - drivers/power/charger-manager.c:cm_notify_event
```
```
In drivers/thermal/thermal_core.c (ffffffff81685094)
Location: include/linux/workqueue.h:498
Inline: True
```
```
In net/core/dst.c (ffffffff81723ab3)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - net/core/dst.c:__dst_free
```
```
In net/core/link_watch.c (ffffffff817306b2)
Location: include/linux/workqueue.h:498
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff817c9e18)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_init
```
```
In net/rfkill/input.c (ffffffff81812630)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_global_op
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111f10a)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_pidlist_stop
```
```
In mm/backing-dev.c (ffffffff811c7de5)
Location: include/linux/workqueue.h:499
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81264b4f)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In block/blk-core.c (ffffffff813fa52f)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - block/blk-core.c:blk_run_queue_async
```
```
In block/genhd.c (ffffffff8140fd2c)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - block/genhd.c:disk_flush_events
```
```
In drivers/base/devcoredump.c (ffffffff815c1b7d)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
```
```
In drivers/power/charger-manager.c (ffffffff816e2649)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/power/charger-manager.c:cm_notify_event
  - drivers/power/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffff816e6494)
Location: include/linux/workqueue.h:499
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff816ec4d2)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In net/core/dst.c (ffffffff8178d503)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - net/core/dst.c:__dst_free
```
```
In net/core/link_watch.c (ffffffff8179ae18)
Location: include/linux/workqueue.h:499
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81febce8)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
```
```
In net/rfkill/input.c (ffffffff81885510)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_global_op
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8112749a)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_pidlist_stop
```
```
In mm/backing-dev.c (ffffffff811d7f05)
Location: include/linux/workqueue.h:513
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81277f8f)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In block/blk-core.c (ffffffff81413eaf)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - block/blk-core.c:blk_run_queue_async
```
```
In block/genhd.c (ffffffff8142b0bc)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - block/genhd.c:disk_flush_events
```
```
In drivers/base/devcoredump.c (ffffffff815f0fcd)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816e5db8)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
```
In drivers/power/supply/charger-manager.c (ffffffff81712ab9)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_notify_event
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffff81715a54)
Location: include/linux/workqueue.h:513
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8171d4c5)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In net/core/dst.c (ffffffff817badd3)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - net/core/dst.c:__dst_free
```
```
In net/core/link_watch.c (ffffffff817c8bb8)
Location: include/linux/workqueue.h:513
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8202a5eb)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
```
```
In net/rfkill/input.c (ffffffff818b9d80)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_global_op
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff8112915a)
Location: include/linux/workqueue.h:515
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
```
```
In mm/backing-dev.c (ffffffff811e0b30)
Location: include/linux/workqueue.h:515
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_shutdown
```
```
In fs/fs-writeback.c (ffffffff8128528f)
Location: include/linux/workqueue.h:515
Inline: True
Inline callers:
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In block/blk-core.c (ffffffff814218f9)
Location: include/linux/workqueue.h:515
Inline: True
Inline callers:
  - block/blk-core.c:blk_run_queue_async
```
```
In block/genhd.c (ffffffff814392fc)
Location: include/linux/workqueue.h:515
Inline: True
Inline callers:
  - block/genhd.c:disk_flush_events
```
```
In drivers/base/devcoredump.c (ffffffff8160511d)
Location: include/linux/workqueue.h:515
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816fa70a)
Location: include/linux/workqueue.h:515
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
```
In drivers/power/supply/charger-manager.c (ffffffff8172a27b)
Location: include/linux/workqueue.h:515
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffff8172d598)
Location: include/linux/workqueue.h:515
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817356a5)
Location: include/linux/workqueue.h:515
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/edac/wq.c (ffffffff8175f7d9)
Location: include/linux/workqueue.h:515
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_mod_work
```
```
In net/core/link_watch.c (ffffffff817e7789)
Location: include/linux/workqueue.h:515
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8210dc89)
Location: include/linux/workqueue.h:515
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
```
```
In net/rfkill/input.c (ffffffff818e0790)
Location: include/linux/workqueue.h:515
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_global_op
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff81135dda)
Location: include/linux/workqueue.h:515
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
```
```
In mm/backing-dev.c (ffffffff811f6b20)
Location: include/linux/workqueue.h:515
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_shutdown
```
```
In fs/fs-writeback.c (ffffffff812a7d0f)
Location: include/linux/workqueue.h:515
Inline: True
Inline callers:
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In block/blk-core.c (ffffffff8144c44c)
Location: include/linux/workqueue.h:515
Inline: True
Inline callers:
  - block/blk-core.c:blk_run_queue_async
```
```
In block/genhd.c (ffffffff8146530c)
Location: include/linux/workqueue.h:515
Inline: True
Inline callers:
  - block/genhd.c:disk_flush_events
```
```
In drivers/regulator/core.c (ffffffff815d1b4e)
Location: include/linux/workqueue.h:515
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/base/devcoredump.c (ffffffff8166d51d)
Location: include/linux/workqueue.h:515
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8176714d)
Location: include/linux/workqueue.h:515
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81773617)
Location: include/linux/workqueue.h:515
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/power/supply/charger-manager.c (ffffffff8179ba0b)
Location: include/linux/workqueue.h:515
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffff8179ebe8)
Location: include/linux/workqueue.h:515
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817a73a5)
Location: include/linux/workqueue.h:515
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/edac/wq.c (ffffffff817d1869)
Location: include/linux/workqueue.h:515
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_mod_work
```
```
In net/core/link_watch.c (ffffffff818626c9)
Location: include/linux/workqueue.h:515
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff82718061)
Location: include/linux/workqueue.h:515
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
```
```
In net/strparser/strparser.c (ffffffff8195b43f)
Location: include/linux/workqueue.h:515
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/rfkill/input.c (ffffffff819664a0)
Location: include/linux/workqueue.h:515
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_global_op
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff811445fa)
Location: include/linux/workqueue.h:538
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
```
```
In mm/backing-dev.c (ffffffff81217df8)
Location: include/linux/workqueue.h:538
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812ce896)
Location: include/linux/workqueue.h:538
Inline: True
Inline callers:
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In block/blk-core.c (ffffffff8147f6ec)
Location: include/linux/workqueue.h:538
Inline: True
Inline callers:
  - block/blk-core.c:blk_run_queue_async
```
```
In block/genhd.c (ffffffff81498c8c)
Location: include/linux/workqueue.h:538
Inline: True
Inline callers:
  - block/genhd.c:disk_flush_events
```
```
In drivers/regulator/core.c (ffffffff81609c18)
Location: include/linux/workqueue.h:538
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/base/devcoredump.c (ffffffff816a8f55)
Location: include/linux/workqueue.h:538
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817a7e39)
Location: include/linux/workqueue.h:538
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817b3c17)
Location: include/linux/workqueue.h:538
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/power/supply/charger-manager.c (ffffffff817e2f96)
Location: include/linux/workqueue.h:538
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffff817e6198)
Location: include/linux/workqueue.h:538
Inline: True
```
```
In drivers/edac/wq.c (ffffffff8181a615)
Location: include/linux/workqueue.h:538
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_mod_work
```
```
In net/core/link_watch.c (ffffffff818ae377)
Location: include/linux/workqueue.h:538
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff82742468)
Location: include/linux/workqueue.h:538
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
```
```
In net/strparser/strparser.c (ffffffff819b4a41)
Location: include/linux/workqueue.h:538
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/rfkill/input.c (ffffffff819bfd80)
Location: include/linux/workqueue.h:538
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_global_op
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff8115010a)
Location: include/linux/workqueue.h:538
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
```
```
In mm/backing-dev.c (ffffffff8122afa8)
Location: include/linux/workqueue.h:538
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812e3c06)
Location: include/linux/workqueue.h:538
Inline: True
Inline callers:
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In block/genhd.c (ffffffff814b2dcc)
Location: include/linux/workqueue.h:538
Inline: True
Inline callers:
  - block/genhd.c:disk_flush_events
```
```
In drivers/regulator/core.c (ffffffff81626d02)
Location: include/linux/workqueue.h:538
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/base/devcoredump.c (ffffffff816c9b35)
Location: include/linux/workqueue.h:538
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
```
```
In drivers/net/phy/phy.c (ffffffff81757cc5)
Location: include/linux/workqueue.h:538
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817cdd09)
Location: include/linux/workqueue.h:538
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817da152)
Location: include/linux/workqueue.h:538
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/power/supply/charger-manager.c (ffffffff8180e7e3)
Location: include/linux/workqueue.h:538
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffff81812618)
Location: include/linux/workqueue.h:538
Inline: True
```
```
In drivers/edac/wq.c (ffffffff81845e05)
Location: include/linux/workqueue.h:538
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_mod_work
```
```
In net/core/link_watch.c (ffffffff818d25f7)
Location: include/linux/workqueue.h:538
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff828fc75b)
Location: include/linux/workqueue.h:538
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
```
```
In net/strparser/strparser.c (ffffffff819eba2d)
Location: include/linux/workqueue.h:538
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/rfkill/input.c (ffffffff819f6f20)
Location: include/linux/workqueue.h:538
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_global_op
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff8115c00a)
Location: include/linux/workqueue.h:516
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
```
```
In mm/backing-dev.c (ffffffff8123a978)
Location: include/linux/workqueue.h:516
Inline: True
```
```
In fs/fs-writeback.c (ffffffff813023a6)
Location: include/linux/workqueue.h:516
Inline: True
Inline callers:
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In block/genhd.c (ffffffff814e12ac)
Location: include/linux/workqueue.h:516
Inline: True
Inline callers:
  - block/genhd.c:disk_flush_events
```
```
In drivers/regulator/core.c (ffffffff8165a37a)
Location: include/linux/workqueue.h:516
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/base/devcoredump.c (ffffffff817050e5)
Location: include/linux/workqueue.h:516
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
```
```
In drivers/net/phy/phy.c (ffffffff817943e5)
Location: include/linux/workqueue.h:516
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8180e3ef)
Location: include/linux/workqueue.h:516
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8181adaf)
Location: include/linux/workqueue.h:516
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/power/supply/charger-manager.c (ffffffff818503ea)
Location: include/linux/workqueue.h:516
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffff818545b9)
Location: include/linux/workqueue.h:516
Inline: True
```
```
In drivers/edac/wq.c (ffffffff81888be5)
Location: include/linux/workqueue.h:516
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_mod_work
```
```
In drivers/ras/cec.c (ffffffff818d00fb)
Location: include/linux/workqueue.h:516
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_mod_work
```
```
In net/core/link_watch.c (ffffffff8191f87f)
Location: include/linux/workqueue.h:516
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff82919287)
Location: include/linux/workqueue.h:516
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
```
```
In net/strparser/strparser.c (ffffffff81a5abbb)
Location: include/linux/workqueue.h:516
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/rfkill/input.c (ffffffff81a66460)
Location: include/linux/workqueue.h:516
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_global_op
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff81167c2a)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
```
```
In mm/backing-dev.c (ffffffff81249048)
Location: include/linux/workqueue.h:520
Inline: True
```
```
In fs/fs-writeback.c (ffffffff813154c6)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In block/genhd.c (ffffffff814fa6fc)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - block/genhd.c:disk_flush_events
```
```
In drivers/regulator/core.c (ffffffff8167d0ba)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/base/devcoredump.c (ffffffff81729375)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
```
```
In drivers/net/phy/phy.c (ffffffff817b7f15)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8183f4df)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8184c42f)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/power/supply/charger-manager.c (ffffffff818821ea)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffff81886019)
Location: include/linux/workqueue.h:520
Inline: True
```
```
In drivers/edac/wq.c (ffffffff818bab95)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_mod_work
```
```
In drivers/ras/cec.c (ffffffff819024eb)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_mod_work
```
```
In net/core/link_watch.c (ffffffff81951abf)
Location: include/linux/workqueue.h:520
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff829230f6)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
```
```
In net/strparser/strparser.c (ffffffff81a9180f)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/rfkill/input.c (ffffffff81a9cf80)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_global_op
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff811795ba)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
```
```
In mm/backing-dev.c (ffffffff81277198)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_shutdown
```
```
In fs/fs-writeback.c (ffffffff8134ed66)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/io_uring.c (ffffffff8137bb52)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - fs/io_uring.c:io_file_data_ref_zero
```
```
In block/genhd.c (ffffffff8155b6cc)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - block/genhd.c:disk_flush_events
```
```
In drivers/regulator/core.c (ffffffff8172e6a0)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/base/devcoredump.c (ffffffff817e5b85)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
```
```
In drivers/net/phy/phy.c (ffffffff8187f0a5)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/usb/host/xhci-ring.c (ffffffff819118ee)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8191efbf)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/power/supply/charger-manager.c (ffffffff8195074b)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:fullbatt_handler
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffff81954619)
Location: include/linux/workqueue.h:533
Inline: True
```
```
In drivers/edac/wq.c (ffffffff8198b3f5)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_mod_work
```
```
In drivers/ras/cec.c (ffffffff819d99f4)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
```
```
In net/core/link_watch.c (ffffffff81a2281f)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/ipv6/addrconf.c (ffffffff81b3a773)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/strparser/strparser.c (ffffffff81b8cd54)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/rfkill/input.c (ffffffff81b988b0)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_global_op
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff8117632a)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
```
```
In mm/backing-dev.c (ffffffff81281a88)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_shutdown
```
```
In fs/fs-writeback.c (ffffffff8135bbe6)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/io_uring.c (ffffffff81389de6)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - fs/io_uring.c:io_file_data_ref_zero
```
```
In block/genhd.c (ffffffff815779dc)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - block/genhd.c:disk_flush_events
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81639feb)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_irq_handler
```
```
In drivers/regulator/core.c (ffffffff8174b270)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/base/devcoredump.c (ffffffff817fa815)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
```
```
In drivers/net/phy/phy.c (ffffffff8188f092)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_error
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/usb/host/xhci-ring.c (ffffffff819192fe)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8192674a)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/power/supply/charger-manager.c (ffffffff81956952)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffff81959589)
Location: include/linux/workqueue.h:533
Inline: True
```
```
In drivers/edac/wq.c (ffffffff8198f013)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_mod_work
```
```
In drivers/ras/cec.c (ffffffff819d8d44)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
```
```
In net/core/link_watch.c (ffffffff81a22b7f)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/ipv6/addrconf.c (ffffffff81b49473)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
```
In net/strparser/strparser.c (ffffffff81b9c9a4)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/rfkill/input.c (ffffffff81ba8580)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_global_op
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff81176e8a)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
```
```
In mm/backing-dev.c (ffffffff81286938)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_shutdown
```
```
In fs/fs-writeback.c (ffffffff813627f6)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/io_uring.c (ffffffff81390c60)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - fs/io_uring.c:io_rsrc_node_ref_zero
```
```
In block/genhd.c (ffffffff8157f71c)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - block/genhd.c:disk_flush_events
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161dc3b)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_irq_handler
```
```
In drivers/regulator/core.c (ffffffff8172e980)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/base/devcoredump.c (ffffffff817df525)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
```
```
In drivers/net/phy/phy.c (ffffffff818719d2)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_error
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/usb/host/xhci-ring.c (ffffffff818fc14e)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81909e2a)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/power/supply/charger-manager.c (ffffffff8193a5a2)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffff8193dde9)
Location: include/linux/workqueue.h:533
Inline: True
```
```
In drivers/edac/wq.c (ffffffff81973663)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_mod_work
```
```
In drivers/ras/cec.c (ffffffff819beea4)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
```
```
In net/core/link_watch.c (ffffffff81a09eb6)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/ipv6/addrconf.c (ffffffff81b370a3)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
```
In net/ipv6/mcast.c (ffffffff81b5f46d)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/strparser/strparser.c (ffffffff81b8ba64)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/rfkill/input.c (ffffffff81b97710)
Location: include/linux/workqueue.h:533
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_global_op
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff8119e721)
Location: include/linux/workqueue.h:527
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
```
```
In mm/backing-dev.c (ffffffff812c5cb8)
Location: include/linux/workqueue.h:527
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_shutdown
```
```
In fs/fs-writeback.c (ffffffff813b0ff6)
Location: include/linux/workqueue.h:527
Inline: True
Inline callers:
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/io_uring.c (ffffffff813de61d)
Location: include/linux/workqueue.h:527
Inline: True
Inline callers:
  - fs/io_uring.c:io_rsrc_node_ref_zero
```
```
In block/disk-events.c (ffffffff815eef8c)
Location: include/linux/workqueue.h:527
Inline: True
Inline callers:
  - block/disk-events.c:disk_flush_events
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168d25b)
Location: include/linux/workqueue.h:527
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_irq_handler
```
```
In drivers/regulator/core.c (ffffffff817ae565)
Location: include/linux/workqueue.h:527
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/regulator/irq_helpers.c (ffffffff817b24da)
Location: include/linux/workqueue.h:527
Inline: True
Inline callers:
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
```
```
In drivers/base/devcoredump.c (ffffffff8186af85)
Location: include/linux/workqueue.h:527
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
```
```
In drivers/net/phy/phy.c (ffffffff81901fd2)
Location: include/linux/workqueue.h:527
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8199b03e)
Location: include/linux/workqueue.h:527
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff819aa69a)
Location: include/linux/workqueue.h:527
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/power/supply/charger-manager.c (ffffffff819ded42)
Location: include/linux/workqueue.h:527
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffff819e2699)
Location: include/linux/workqueue.h:527
Inline: True
```
```
In drivers/edac/wq.c (ffffffff81a1c363)
Location: include/linux/workqueue.h:527
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_mod_work
```
```
In drivers/ras/cec.c (ffffffff81a6e434)
Location: include/linux/workqueue.h:527
Inline: True
Inline callers:
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
```
```
In net/core/link_watch.c (ffffffff81abc3b6)
Location: include/linux/workqueue.h:527
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/ipv6/addrconf.c (ffffffff81bfd863)
Location: include/linux/workqueue.h:527
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
```
In net/ipv6/mcast.c (ffffffff81c26c2d)
Location: include/linux/workqueue.h:527
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/strparser/strparser.c (ffffffff81c57d04)
Location: include/linux/workqueue.h:527
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/rfkill/input.c (ffffffff81c64200)
Location: include/linux/workqueue.h:527
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_global_op
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff811cee61)
Location: include/linux/workqueue.h:528
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
```
```
In mm/backing-dev.c (ffffffff81322a48)
Location: include/linux/workqueue.h:528
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_shutdown
```
```
In fs/fs-writeback.c (ffffffff81435e95)
Location: include/linux/workqueue.h:528
Inline: True
Inline callers:
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:wb_queue_work
```
```
In block/disk-events.c (ffffffff8169f931)
Location: include/linux/workqueue.h:528
Inline: True
Inline callers:
  - block/disk-events.c:disk_flush_events
```
```
In io_uring/io_uring.c (ffffffff81e8f1f3)
Location: include/linux/workqueue.h:528
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_rsrc_node_ref_zero
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff817ac01b)
Location: include/linux/workqueue.h:528
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_irq_handler
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts
```
```
In drivers/regulator/core.c (ffffffff818e9573)
Location: include/linux/workqueue.h:528
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/regulator/irq_helpers.c (ffffffff818edf79)
Location: include/linux/workqueue.h:528
Inline: True
Inline callers:
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
```
```
In drivers/base/devcoredump.c (ffffffff819b3c95)
Location: include/linux/workqueue.h:528
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
```
```
In drivers/net/phy/phy.c (ffffffff81a52685)
Location: include/linux/workqueue.h:528
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81af868f)
Location: include/linux/workqueue.h:528
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81b0837a)
Location: include/linux/workqueue.h:528
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/power/supply/charger-manager.c (ffffffff81b437d8)
Location: include/linux/workqueue.h:528
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffff81b47d83)
Location: include/linux/workqueue.h:528
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:handle_thermal_trip
```
```
In drivers/edac/wq.c (ffffffff81b85403)
Location: include/linux/workqueue.h:528
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_mod_work
```
```
In drivers/ras/cec.c (ffffffff81bdf304)
Location: include/linux/workqueue.h:528
Inline: True
Inline callers:
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
```
```
In net/core/link_watch.c (ffffffff81c36e76)
Location: include/linux/workqueue.h:528
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/ipv6/addrconf.c (ffffffff834cdd5b)
Location: include/linux/workqueue.h:528
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
```
In net/ipv6/mcast.c (ffffffff81dc46a6)
Location: include/linux/workqueue.h:528
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/strparser/strparser.c (ffffffff81df93b5)
Location: include/linux/workqueue.h:528
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/rfkill/input.c (ffffffff81e06e7e)
Location: include/linux/workqueue.h:528
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_global_op
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811aff4a)
Location: include/linux/workqueue.h:529
Inline: True
Inline callers:
  - kernel/rcu/tree.c:schedule_delayed_monitor_work
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81212771)
Location: include/linux/workqueue.h:529
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
```
```
In mm/backing-dev.c (ffffffff813971e8)
Location: include/linux/workqueue.h:529
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_shutdown
```
```
In fs/fs-writeback.c (ffffffff814c3e55)
Location: include/linux/workqueue.h:529
Inline: True
Inline callers:
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In block/disk-events.c (ffffffff8175e2f1)
Location: include/linux/workqueue.h:529
Inline: True
Inline callers:
  - block/disk-events.c:disk_flush_events
```
```
In io_uring/rsrc.c (ffffffff817a0244)
Location: include/linux/workqueue.h:529
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_node_ref_zero
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c4f9b)
Location: include/linux/workqueue.h:529
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_irq_handler
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts
```
```
In drivers/regulator/core.c (ffffffff81a3f8d3)
Location: include/linux/workqueue.h:529
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/regulator/irq_helpers.c (ffffffff81a45aaf)
Location: include/linux/workqueue.h:529
Inline: True
Inline callers:
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
```
```
In drivers/base/devcoredump.c (ffffffff81b28c07)
Location: include/linux/workqueue.h:529
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
```
```
In drivers/net/phy/phy.c (ffffffff81bdbc85)
Location: include/linux/workqueue.h:529
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81c865c4)
Location: include/linux/workqueue.h:529
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81c982e5)
Location: include/linux/workqueue.h:529
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/power/supply/charger-manager.c (ffffffff81cda350)
Location: include/linux/workqueue.h:529
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffff81cdf3ae)
Location: include/linux/workqueue.h:529
Inline: True
```
```
In drivers/edac/wq.c (ffffffff81d24413)
Location: include/linux/workqueue.h:529
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_mod_work
```
```
In drivers/ras/cec.c (ffffffff81d8a8d4)
Location: include/linux/workqueue.h:529
Inline: True
Inline callers:
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
```
```
In net/core/link_watch.c (ffffffff81dea496)
Location: include/linux/workqueue.h:529
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/ipv6/addrconf.c (ffffffff83f10cf1)
Location: include/linux/workqueue.h:529
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
```
In net/ipv6/mcast.c (ffffffff81f95308)
Location: include/linux/workqueue.h:529
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/strparser/strparser.c (ffffffff81fcd97a)
Location: include/linux/workqueue.h:529
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/rfkill/input.c (ffffffff81fdc27e)
Location: include/linux/workqueue.h:529
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_global_op
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811c20e1)
Location: include/linux/workqueue.h:532
Inline: True
Inline callers:
  - kernel/rcu/tree.c:schedule_delayed_monitor_work
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81228081)
Location: include/linux/workqueue.h:532
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
```
```
In mm/backing-dev.c (ffffffff813ca178)
Location: include/linux/workqueue.h:532
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_shutdown
```
```
In fs/fs-writeback.c (ffffffff814f9245)
Location: include/linux/workqueue.h:532
Inline: True
Inline callers:
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In block/disk-events.c (ffffffff8179d1f1)
Location: include/linux/workqueue.h:532
Inline: True
Inline callers:
  - block/disk-events.c:disk_flush_events
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8190806b)
Location: include/linux/workqueue.h:532
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_irq_handler
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts
```
```
In drivers/regulator/core.c (ffffffff81a894a3)
Location: include/linux/workqueue.h:532
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/regulator/irq_helpers.c (ffffffff81a8fc5f)
Location: include/linux/workqueue.h:532
Inline: True
Inline callers:
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
```
```
In drivers/base/devcoredump.c (ffffffff81b78db7)
Location: include/linux/workqueue.h:532
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
```
```
In drivers/net/phy/phy.c (ffffffff81c32cf5)
Location: include/linux/workqueue.h:532
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_error
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81ced3f4)
Location: include/linux/workqueue.h:532
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81cff64b)
Location: include/linux/workqueue.h:532
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/power/supply/charger-manager.c (ffffffff81d425d0)
Location: include/linux/workqueue.h:532
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffff81d47570)
Location: include/linux/workqueue.h:532
Inline: True
```
```
In drivers/edac/wq.c (ffffffff81d8d623)
Location: include/linux/workqueue.h:532
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_mod_work
```
```
In drivers/ras/cec.c (ffffffff81df8ed4)
Location: include/linux/workqueue.h:532
Inline: True
Inline callers:
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
```
```
In net/core/link_watch.c (ffffffff81e5bc86)
Location: include/linux/workqueue.h:532
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/ipv6/addrconf.c (ffffffff83737341)
Location: include/linux/workqueue.h:532
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
```
In net/ipv6/mcast.c (ffffffff81ff5caf)
Location: include/linux/workqueue.h:532
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/strparser/strparser.c (ffffffff8204929b)
Location: include/linux/workqueue.h:532
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/rfkill/input.c (ffffffff82057f5e)
Location: include/linux/workqueue.h:532
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_global_op
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811d27a1)
Location: include/linux/workqueue.h:574
Inline: True
Inline callers:
  - kernel/rcu/tree.c:schedule_delayed_monitor_work
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8123fe81)
Location: include/linux/workqueue.h:574
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
```
```
In mm/backing-dev.c (ffffffff813f4b08)
Location: include/linux/workqueue.h:574
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_shutdown
```
```
In fs/fs-writeback.c (ffffffff8152daa5)
Location: include/linux/workqueue.h:574
Inline: True
Inline callers:
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In block/disk-events.c (ffffffff817e0c11)
Location: include/linux/workqueue.h:574
Inline: True
Inline callers:
  - block/disk-events.c:disk_flush_events
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8194f87b)
Location: include/linux/workqueue.h:574
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_irq_handler
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts
```
```
In drivers/regulator/core.c (ffffffff81adbb83)
Location: include/linux/workqueue.h:574
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/regulator/irq_helpers.c (ffffffff81ae24d4)
Location: include/linux/workqueue.h:574
Inline: True
Inline callers:
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
```
```
In drivers/base/devcoredump.c (ffffffff81bccc87)
Location: include/linux/workqueue.h:574
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
```
```
In drivers/gpu/drm/drm_probe_helper.c (ffffffff81cced50)
Location: include/linux/workqueue.h:574
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_probe_helper.c:drm_helper_probe_single_connector_modes
```
```
In drivers/gpu/drm/drm_self_refresh_helper.c (ffffffff81ccf82e)
Location: include/linux/workqueue.h:574
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_self_refresh_helper.c:drm_self_refresh_helper_alter_state
```
```
In drivers/net/phy/phy.c (ffffffff81ce7cc8)
Location: include/linux/workqueue.h:574
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:_phy_state_machine
  - drivers/net/phy/phy.c:_phy_state_machine
  - drivers/net/phy/phy.c:phy_error
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81da31bb)
Location: include/linux/workqueue.h:574
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81db474b)
Location: include/linux/workqueue.h:574
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/power/supply/charger-manager.c (ffffffff81df8f80)
Location: include/linux/workqueue.h:574
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffff81dfcafa)
Location: include/linux/workqueue.h:574
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_pm_notify
```
```
In drivers/edac/wq.c (ffffffff81e44ed3)
Location: include/linux/workqueue.h:574
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_mod_work
```
```
In drivers/ras/cec.c (ffffffff81eaf614)
Location: include/linux/workqueue.h:574
Inline: True
Inline callers:
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
```
```
In net/core/link_watch.c (ffffffff81f1b046)
Location: include/linux/workqueue.h:574
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/ipv6/addrconf.c (ffffffff8396b9f1)
Location: include/linux/workqueue.h:574
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
```
In net/ipv6/mcast.c (ffffffff820c38bf)
Location: include/linux/workqueue.h:574
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/strparser/strparser.c (ffffffff8211b61b)
Location: include/linux/workqueue.h:574
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/rfkill/input.c (ffffffff8212aa6e)
Location: include/linux/workqueue.h:574
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_global_op
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffff8000101da704)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
```
```
In mm/backing-dev.c (ffff8000102ddf64)
Location: include/linux/workqueue.h:520
Inline: True
```
```
In fs/fs-writeback.c (ffff8000103cb740)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In block/genhd.c (ffff8000105fc300)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - block/genhd.c:disk_flush_events
```
```
In drivers/regulator/core.c (ffff800010846c78)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/base/devcoredump.c (ffff80001091f05c)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
```
```
In drivers/net/phy/phy.c (ffff8000109d0698)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
```
```
In drivers/usb/host/xhci-ring.c (ffff800010a7d044)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8b684)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/power/supply/charger-manager.c (ffff800010acea6c)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffff800010ad309c)
Location: include/linux/workqueue.h:520
Inline: True
```
```
In drivers/edac/wq.c (ffff800010b13124)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_mod_work
```
```
In net/core/link_watch.c (ffff800010bf3690)
Location: include/linux/workqueue.h:520
Inline: True
```
```
In net/ipv6/addrconf.c (ffff8000114b3f64)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
```
```
In net/strparser/strparser.c (ffff800010d5f4a4)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/rfkill/input.c (ffff800010d6da98)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_global_op
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (c041cf7c)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
```
```
In mm/backing-dev.c (c05034f0)
Location: include/linux/workqueue.h:520
Inline: True
```
```
In fs/fs-writeback.c (c05a7b2c)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In block/genhd.c (c07a7314)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - block/genhd.c:disk_flush_events
```
```
In drivers/regulator/core.c (c0950424)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/base/devcoredump.c (c0a042f8)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
```
```
In drivers/net/phy/phy.c (c0ab88ac)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
```
```
In drivers/usb/host/xhci-ring.c (c0b511dc)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
```
In drivers/usb/host/xhci-dbgcap.c (c0b5e850)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/power/supply/charger-manager.c (c0baf0c0)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (c0bb3798)
Location: include/linux/workqueue.h:520
Inline: True
```
```
In drivers/edac/wq.c (c0bf10d0)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_mod_work
```
```
In net/core/link_watch.c (c0d0c03c)
Location: include/linux/workqueue.h:520
Inline: True
```
```
In net/ipv6/addrconf.c (c15b9210)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
```
```
In net/strparser/strparser.c (c0e5f0c4)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/rfkill/input.c (c0e6b5d0)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_global_op
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (c000000000247a84)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
```
```
In mm/backing-dev.c (c00000000039d984)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_shutdown
```
```
In fs/fs-writeback.c (c0000000004cd460)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In block/genhd.c (c000000000795830)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - block/genhd.c:disk_flush_events
```
```
In drivers/regulator/core.c (c0000000008e2d94)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/base/devcoredump.c (c0000000009c4270)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
```
```
In drivers/net/phy/phy.c (c000000000a8fa8c)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
```
```
In drivers/usb/host/xhci-ring.c (c000000000b55974)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
```
In drivers/usb/host/xhci-dbgcap.c (c000000000b67574)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/power/supply/charger-manager.c (c000000000bb1b50)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (c000000000bb7a20)
Location: include/linux/workqueue.h:520
Inline: True
```
```
In drivers/edac/wq.c (c000000000c07a0c)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_mod_work
```
```
In net/core/link_watch.c (c000000000cd8b2c)
Location: include/linux/workqueue.h:520
Inline: True
```
```
In net/ipv6/addrconf.c (c0000000013c58c8)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
```
```
In net/strparser/strparser.c (c000000000e99f5c)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/rfkill/input.c (c000000000eab650)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_global_op
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffe000152d04)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
```
```
In mm/backing-dev.c (ffffffe0001f62c0)
Location: include/linux/workqueue.h:520
Inline: True
```
```
In fs/fs-writeback.c (ffffffe000289550)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In block/genhd.c (ffffffe0004382aa)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - block/genhd.c:disk_flush_events
```
```
In drivers/regulator/core.c (ffffffe00052712e)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/base/devcoredump.c (ffffffe00059e09c)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
```
```
In drivers/net/phy/phy.c (ffffffe00061d318)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
```
```
In drivers/usb/host/xhci-ring.c (ffffffe000694b02)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffe00069fe52)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/power/supply/charger-manager.c (ffffffe0006cb686)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffe0006cf57c)
Location: include/linux/workqueue.h:520
Inline: True
```
```
In drivers/edac/wq.c (ffffffe0006ffb4a)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_mod_work
```
```
In net/core/link_watch.c (ffffffe00077504c)
Location: include/linux/workqueue.h:520
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffe000042dd0)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
```
```
In net/strparser/strparser.c (ffffffe000894a6c)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/rfkill/input.c (ffffffe00089f73c)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_global_op
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff8116024a)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
```
```
In mm/backing-dev.c (ffffffff81241698)
Location: include/linux/workqueue.h:520
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8130daa6)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In block/genhd.c (ffffffff814f2cdc)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - block/genhd.c:disk_flush_events
```
```
In drivers/regulator/core.c (ffffffff8164299a)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/base/devcoredump.c (ffffffff816ef155)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
```
```
In drivers/net/phy/phy.c (ffffffff8177c9e5)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817f788f)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
```
In drivers/thermal/thermal_core.c (ffffffff8182be99)
Location: include/linux/workqueue.h:520
Inline: True
```
```
In drivers/edac/wq.c (ffffffff81860a15)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_mod_work
```
```
In drivers/ras/cec.c (ffffffff818a191b)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_mod_work
```
```
In net/core/link_watch.c (ffffffff818f1a8f)
Location: include/linux/workqueue.h:520
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff82907dfa)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
```
```
In net/strparser/strparser.c (ffffffff81a30e9f)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/rfkill/input.c (ffffffff81a3c310)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_global_op
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff811534ba)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
```
```
In mm/backing-dev.c (ffffffff8123468e)
Location: include/linux/workqueue.h:520
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812fe6b6)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In block/genhd.c (ffffffff814e3206)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - block/genhd.c:disk_flush_events
```
```
In drivers/acpi/nfit/core.c (ffffffff815f48c2)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/acpi/nfit/core.c:scrub_show
```
```
In drivers/regulator/core.c (ffffffff81622f9a)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/net/phy/phy.c (ffffffff8175c795)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817bca2f)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817c997f)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/thermal/thermal_core.c (ffffffff817f3529)
Location: include/linux/workqueue.h:520
Inline: True
```
```
In drivers/edac/wq.c (ffffffff81827fe5)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_mod_work
```
```
In drivers/ras/cec.c (ffffffff8185d08b)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_mod_work
```
```
In net/core/link_watch.c (ffffffff818ab8cf)
Location: include/linux/workqueue.h:520
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff82900148)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
```
```
In net/strparser/strparser.c (ffffffff819ee08f)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/rfkill/input.c (ffffffff819f8f30)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_global_op
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff8115e01a)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
```
```
In mm/backing-dev.c (ffffffff8123f438)
Location: include/linux/workqueue.h:520
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8130b896)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In block/genhd.c (ffffffff814eed6c)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - block/genhd.c:disk_flush_events
```
```
In drivers/regulator/core.c (ffffffff81670efa)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/base/devcoredump.c (ffffffff8171c835)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
```
```
In drivers/net/phy/phy.c (ffffffff817acd95)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8183435f)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff818412af)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/power/supply/charger-manager.c (ffffffff8187769a)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffff8187b4c9)
Location: include/linux/workqueue.h:520
Inline: True
```
```
In drivers/edac/wq.c (ffffffff818b0045)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_mod_work
```
```
In drivers/ras/cec.c (ffffffff818f2f0b)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_mod_work
```
```
In net/core/link_watch.c (ffffffff81942abf)
Location: include/linux/workqueue.h:520
Inline: True
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199dce7)
Location: include/linux/workqueue.h:520
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8291d6f4)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
```
```
In net/strparser/strparser.c (ffffffff81a9ca4f)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/rfkill/input.c (ffffffff81aa81c0)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_global_op
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff8116b44a)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
```
```
In mm/backing-dev.c (ffffffff8124e7b2)
Location: include/linux/workqueue.h:520
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8131d0c6)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In block/genhd.c (ffffffff81507e13)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - block/genhd.c:disk_flush_events
```
```
In drivers/regulator/core.c (ffffffff8168b55a)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/base/devcoredump.c (ffffffff81737b95)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
```
```
In drivers/net/phy/phy.c (ffffffff817c6d25)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8184e668)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8185b7df)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/power/supply/charger-manager.c (ffffffff8189303a)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffff81896ec9)
Location: include/linux/workqueue.h:520
Inline: True
```
```
In drivers/edac/wq.c (ffffffff818cc2d5)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_mod_work
```
```
In drivers/ras/cec.c (ffffffff81913fab)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_mod_work
```
```
In net/core/link_watch.c (ffffffff819643bf)
Location: include/linux/workqueue.h:520
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff82924158)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
```
```
In net/strparser/strparser.c (ffffffff81aa8c2f)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/rfkill/input.c (ffffffff81ab46a0)
Location: include/linux/workqueue.h:520
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_global_op
```
</details>
</li>
</ul>

## Differences
