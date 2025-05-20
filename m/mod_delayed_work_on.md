# Function: <code>mod_delayed_work_on</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool mod_delayed_work_on(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810988e0)
Location: kernel/workqueue.c:1529
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_pidlist_stop
  - kernel/cgroup.c:css_free_work_fn
  - mm/backing-dev.c:wb_shutdown
  - fs/fs-writeback.c:wb_wakeup
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:dirtytime_interval_handler
  - block/blk-core.c:blk_run_queue_async
  - block/genhd.c:disk_flush_events
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/power/charger-manager.c:_setup_polling
  - drivers/power/charger-manager.c:cm_notify_event
  - net/core/dst.c:__dst_free
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_init
  - net/rfkill/input.c:rfkill_schedule_global_op
```
**Symbols:**

```
ffffffff810988e0-ffffffff81098971: mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool mod_delayed_work_on(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109bea0)
Location: kernel/workqueue.c:1585
Inline: False
Direct callers:
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_pidlist_stop
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
  - block/blk-core.c:blk_run_queue_async
  - block/genhd.c:disk_flush_events
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/power/charger-manager.c:cm_notify_event
  - drivers/power/charger-manager.c:_setup_polling
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - net/core/dst.c:__dst_free
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
  - net/rfkill/input.c:rfkill_schedule_global_op
```
**Symbols:**

```
ffffffff8109bea0-ffffffff8109bf31: mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool mod_delayed_work_on(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a0ee0)
Location: kernel/workqueue.c:1587
Inline: False
Direct callers:
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_pidlist_stop
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
  - block/blk-core.c:blk_run_queue_async
  - block/genhd.c:disk_flush_events
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
  - drivers/power/supply/charger-manager.c:cm_notify_event
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - net/core/dst.c:__dst_free
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
  - net/rfkill/input.c:rfkill_schedule_global_op
```
**Symbols:**

```
ffffffff810a0ee0-ffffffff810a0f71: mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool mod_delayed_work_on(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109e450)
Location: kernel/workqueue.c:1586
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - mm/backing-dev.c:wb_shutdown
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
  - block/blk-core.c:kblockd_mod_delayed_work_on
  - block/blk-core.c:blk_run_queue_async
  - block/genhd.c:disk_flush_events
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/edac/wq.c:edac_mod_work
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
  - net/rfkill/input.c:rfkill_schedule_global_op
```
**Symbols:**

```
ffffffff8109e450-ffffffff8109e4e1: mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool mod_delayed_work_on(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a4ca0)
Location: kernel/workqueue.c:1587
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - mm/backing-dev.c:wb_shutdown
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
  - block/blk-core.c:kblockd_mod_delayed_work_on
  - block/blk-core.c:blk_run_queue_async
  - block/genhd.c:disk_flush_events
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/edac/wq.c:edac_mod_work
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/rfkill/input.c:rfkill_schedule_global_op
```
**Symbols:**

```
ffffffff810a4ca0-ffffffff810a4d31: mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool mod_delayed_work_on(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ac790)
Location: kernel/workqueue.c:1585
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
  - block/blk-core.c:kblockd_mod_delayed_work_on
  - block/blk-core.c:blk_run_queue_async
  - block/genhd.c:disk_flush_events
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/edac/wq.c:edac_mod_work
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/rfkill/input.c:rfkill_schedule_global_op
```
**Symbols:**

```
ffffffff810ac790-ffffffff810ac821: mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool mod_delayed_work_on(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b56a0)
Location: kernel/workqueue.c:1605
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
  - block/blk-core.c:kblockd_mod_delayed_work_on
  - block/genhd.c:disk_flush_events
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/edac/wq.c:edac_mod_work
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/rfkill/input.c:rfkill_schedule_global_op
```
**Symbols:**

```
ffffffff810b56a0-ffffffff810b5731: mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool mod_delayed_work_on(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bb590)
Location: kernel/workqueue.c:1701
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
  - block/blk-core.c:kblockd_mod_delayed_work_on
  - block/genhd.c:disk_flush_events
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/edac/wq.c:edac_mod_work
  - drivers/ras/cec.c:cec_mod_work
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/rfkill/input.c:rfkill_schedule_global_op
```
**Symbols:**

```
ffffffff810bb590-ffffffff810bb621: mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool mod_delayed_work_on(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c1800)
Location: kernel/workqueue.c:1704
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
  - block/blk-core.c:kblockd_mod_delayed_work_on
  - block/genhd.c:disk_flush_events
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/edac/wq.c:edac_mod_work
  - drivers/ras/cec.c:cec_mod_work
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/rfkill/input.c:rfkill_schedule_global_op
```
**Symbols:**

```
ffffffff810c1800-ffffffff810c1891: mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool mod_delayed_work_on(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ca6d0)
Location: kernel/workqueue.c:1701
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - mm/backing-dev.c:wb_shutdown
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:wb_queue_work
  - fs/io_uring.c:io_file_data_ref_zero
  - block/blk-core.c:kblockd_mod_delayed_work_on
  - block/genhd.c:disk_flush_events
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/power/supply/charger-manager.c:fullbatt_handler
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/edac/wq.c:edac_mod_work
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
  - net/core/link_watch.c:linkwatch_schedule_work
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/rfkill/input.c:rfkill_schedule_global_op
```
**Symbols:**

```
ffffffff810ca6d0-ffffffff810ca761: mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool mod_delayed_work_on(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c5800)
Location: kernel/workqueue.c:1707
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - mm/backing-dev.c:wb_shutdown
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:wb_queue_work
  - fs/io_uring.c:io_file_data_ref_zero
  - block/blk-core.c:kblockd_mod_delayed_work_on
  - block/genhd.c:disk_flush_events
  - drivers/gpio/gpiolib-cdev.c:debounce_irq_handler
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
  - drivers/xen/events/events_base.c:lateeoi_list_add
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_error
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/edac/wq.c:edac_mod_work
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
  - net/core/link_watch.c:linkwatch_schedule_work
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/rfkill/input.c:rfkill_schedule_global_op
```
**Symbols:**

```
ffffffff810c5800-ffffffff810c5891: mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool mod_delayed_work_on(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c7120)
Location: kernel/workqueue.c:1708
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - mm/backing-dev.c:wb_shutdown
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:wb_queue_work
  - fs/io_uring.c:io_rsrc_node_ref_zero
  - block/blk-core.c:kblockd_mod_delayed_work_on
  - block/genhd.c:disk_flush_events
  - drivers/gpio/gpiolib-cdev.c:debounce_irq_handler
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_error
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/edac/wq.c:edac_mod_work
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
  - net/core/link_watch.c:linkwatch_schedule_work
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/rfkill/input.c:rfkill_schedule_global_op
```
**Symbols:**

```
ffffffff810c7120-ffffffff810c71b5: mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool mod_delayed_work_on(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810d9e40)
Location: kernel/workqueue.c:1738
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - mm/backing-dev.c:wb_shutdown
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:wb_queue_work
  - fs/io_uring.c:io_rsrc_node_ref_zero
  - block/blk-core.c:kblockd_mod_delayed_work_on
  - block/disk-events.c:disk_flush_events
  - drivers/gpio/gpiolib-cdev.c:debounce_irq_handler
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/edac/wq.c:edac_mod_work
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
  - net/core/link_watch.c:linkwatch_schedule_work
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/rfkill/input.c:rfkill_schedule_global_op
```
**Symbols:**

```
ffffffff810d9e40-ffffffff810d9ed5: mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool mod_delayed_work_on(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810f1d30)
Location: kernel/workqueue.c:1728
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - mm/backing-dev.c:wb_shutdown
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:wb_queue_work
  - block/blk-core.c:kblockd_mod_delayed_work_on
  - block/disk-events.c:disk_flush_events
  - io_uring/io_uring.c:io_rsrc_node_ref_zero
  - drivers/gpio/gpiolib-cdev.c:debounce_irq_handler
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/thermal/thermal_core.c:handle_thermal_trip
  - drivers/edac/wq.c:edac_mod_work
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
  - net/core/link_watch.c:linkwatch_schedule_work
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/rfkill/input.c:rfkill_schedule_global_op
```
**Symbols:**

```
ffffffff810f1d30-ffffffff810f1dd8: mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool mod_delayed_work_on(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff811154b0)
Location: kernel/workqueue.c:1728
Inline: False
Direct callers:
  - kernel/rcu/tree.c:schedule_delayed_monitor_work
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - mm/backing-dev.c:wb_shutdown
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
  - block/blk-core.c:kblockd_mod_delayed_work_on
  - block/disk-events.c:disk_flush_events
  - io_uring/rsrc.c:io_rsrc_node_ref_zero
  - drivers/gpio/gpiolib-cdev.c:debounce_irq_handler
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/edac/wq.c:edac_mod_work
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
  - net/core/link_watch.c:linkwatch_schedule_work
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/rfkill/input.c:rfkill_schedule_global_op
```
**Symbols:**

```
ffffffff811154b0-ffffffff81115558: mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool mod_delayed_work_on(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81121480)
Location: kernel/workqueue.c:1930
Inline: False
Direct callers:
  - kernel/rcu/tree.c:schedule_delayed_monitor_work
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - mm/backing-dev.c:wb_shutdown
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
  - block/blk-core.c:kblockd_mod_delayed_work_on
  - block/disk-events.c:disk_flush_events
  - drivers/gpio/gpiolib-cdev.c:debounce_irq_handler
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_error
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/edac/wq.c:edac_mod_work
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
  - net/core/link_watch.c:linkwatch_schedule_work
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/rfkill/input.c:rfkill_schedule_global_op
```
**Symbols:**

```
ffffffff81121480-ffffffff81121528: mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool mod_delayed_work_on(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8112bbd0)
Location: kernel/workqueue.c:2016
Inline: False
Direct callers:
  - kernel/rcu/tree.c:schedule_delayed_monitor_work
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - mm/backing-dev.c:wb_shutdown
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
  - block/blk-core.c:kblockd_mod_delayed_work_on
  - block/disk-events.c:disk_flush_events
  - drivers/gpio/gpiolib-cdev.c:debounce_irq_handler
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/gpu/drm/drm_probe_helper.c:drm_helper_probe_single_connector_modes
  - drivers/gpu/drm/drm_self_refresh_helper.c:drm_self_refresh_helper_alter_state
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:_phy_state_machine
  - drivers/net/phy/phy.c:_phy_state_machine
  - drivers/net/phy/phy.c:phy_error
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/thermal/thermal_core.c:thermal_pm_notify
  - drivers/edac/wq.c:edac_mod_work
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
  - net/core/link_watch.c:linkwatch_schedule_work
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/rfkill/input.c:rfkill_schedule_global_op
```
**Symbols:**

```
ffffffff8112bbd0-ffffffff8112bc78: mod_delayed_work_on (STB_GLOBAL)
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
bool mod_delayed_work_on(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff80001011fd50)
Location: kernel/workqueue.c:1704
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
  - block/blk-core.c:kblockd_mod_delayed_work_on
  - block/genhd.c:disk_flush_events
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/edac/wq.c:edac_mod_work
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/rfkill/input.c:rfkill_schedule_global_op
```
**Symbols:**

```
ffff80001011fd50-ffff80001011fe00: mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool mod_delayed_work_on(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0372c38)
Location: kernel/workqueue.c:1704
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
  - block/blk-core.c:kblockd_mod_delayed_work_on
  - block/genhd.c:disk_flush_events
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/edac/wq.c:edac_mod_work
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/rfkill/input.c:rfkill_schedule_global_op
```
**Symbols:**

```
c0372c38-c0372ce0: mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool mod_delayed_work_on(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c000000000166730)
Location: kernel/workqueue.c:1704
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - mm/backing-dev.c:wb_shutdown
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
  - block/blk-core.c:kblockd_mod_delayed_work_on
  - block/genhd.c:disk_flush_events
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/edac/wq.c:edac_mod_work
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/rfkill/input.c:rfkill_schedule_global_op
```
**Symbols:**

```
c000000000166730-c00000000016680c: mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool mod_delayed_work_on(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d9984)
Location: kernel/workqueue.c:1704
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
  - block/blk-core.c:kblockd_mod_delayed_work_on
  - block/genhd.c:disk_flush_events
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/edac/wq.c:edac_mod_work
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/rfkill/input.c:rfkill_schedule_global_op
```
**Symbols:**

```
ffffffe0000d9984-ffffffe0000d99f8: mod_delayed_work_on (STB_GLOBAL)
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
bool mod_delayed_work_on(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bbb70)
Location: kernel/workqueue.c:1704
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
  - block/blk-core.c:kblockd_mod_delayed_work_on
  - block/genhd.c:disk_flush_events
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
  - drivers/edac/wq.c:edac_mod_work
  - drivers/ras/cec.c:cec_mod_work
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/rfkill/input.c:rfkill_schedule_global_op
```
**Symbols:**

```
ffffffff810bbb70-ffffffff810bbc01: mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool mod_delayed_work_on(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810aa5d0)
Location: kernel/workqueue.c:1704
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
  - block/blk-core.c:kblockd_mod_delayed_work_on
  - block/genhd.c:disk_flush_events
  - drivers/acpi/nfit/core.c:scrub_show
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/edac/wq.c:edac_mod_work
  - drivers/ras/cec.c:cec_mod_work
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/rfkill/input.c:rfkill_schedule_global_op
```
**Symbols:**

```
ffffffff810aa5d0-ffffffff810aa65a: mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool mod_delayed_work_on(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bb0d0)
Location: kernel/workqueue.c:1704
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
  - block/blk-core.c:kblockd_mod_delayed_work_on
  - block/genhd.c:disk_flush_events
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/edac/wq.c:edac_mod_work
  - drivers/ras/cec.c:cec_mod_work
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/rfkill/input.c:rfkill_schedule_global_op
```
**Symbols:**

```
ffffffff810bb0d0-ffffffff810bb161: mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool mod_delayed_work_on(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c4000)
Location: kernel/workqueue.c:1704
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
  - block/blk-core.c:kblockd_mod_delayed_work_on
  - block/genhd.c:disk_flush_events
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/edac/wq.c:edac_mod_work
  - drivers/ras/cec.c:cec_mod_work
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/rfkill/input.c:rfkill_schedule_global_op
```
**Symbols:**

```
ffffffff810c4000-ffffffff810c4091: mod_delayed_work_on (STB_GLOBAL)
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
