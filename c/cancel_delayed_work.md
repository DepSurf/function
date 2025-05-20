# Function: <code>cancel_delayed_work</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool cancel_delayed_work(struct delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81098980)
Location: kernel/workqueue.c:2893
Inline: False
Direct callers:
  - block/blk-core.c:blk_stop_queue
  - block/blk-mq.c:blk_mq_stop_hw_queue
  - block/blk-mq.c:blk_mq_stop_hw_queue
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/power/charger-manager.c:cm_suspend_prepare
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_cleanup
```
**Symbols:**

```
ffffffff81098980-ffffffff81098a45: cancel_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool cancel_delayed_work(struct delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109bf40)
Location: kernel/workqueue.c:2993
Inline: False
Direct callers:
  - block/blk-core.c:blk_stop_queue
  - block/blk-mq.c:blk_mq_stop_hw_queue
  - block/blk-mq.c:blk_mq_stop_hw_queue
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/power/charger-manager.c:cm_suspend_prepare
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
```
**Symbols:**

```
ffffffff8109bf40-ffffffff8109c009: cancel_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool cancel_delayed_work(struct delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a1050)
Location: kernel/workqueue.c:3032
Inline: False
Direct callers:
  - block/blk-core.c:blk_stop_queue
  - block/blk-mq.c:blk_mq_stop_hw_queue
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/net/phy/phy.c:phy_trigger_machine
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
```
**Symbols:**

```
ffffffff810a1050-ffffffff810a1065: cancel_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool cancel_delayed_work(struct delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109e590)
Location: kernel/workqueue.c:3031
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - block/blk-core.c:blk_stop_queue
  - block/blk-mq.c:blk_mq_delay_queue
  - block/blk-mq.c:blk_mq_stop_hw_queues
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/net/phy/phy.c:phy_trigger_machine
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/thermal/thermal_core.c:handle_thermal_trip
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/mmc/core/core.c:mmc_detect_card_removed
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
```
**Symbols:**

```
ffffffff8109e590-ffffffff8109e5a5: cancel_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool cancel_delayed_work(struct delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a4de0)
Location: kernel/workqueue.c:3045
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - block/blk-core.c:blk_stop_queue
  - block/blk-mq.c:blk_mq_delay_queue
  - block/blk-mq.c:blk_mq_stop_hw_queues
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/net/phy/phy.c:phy_trigger_machine
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/thermal/thermal_core.c:handle_thermal_trip
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/mmc/core/core.c:mmc_detect_card_removed
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:addrconf_del_dad_work
  - net/strparser/strparser.c:__strp_recv
```
**Symbols:**

```
ffffffff810a4de0-ffffffff810a4df5: cancel_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool cancel_delayed_work(struct delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ac580)
Location: kernel/workqueue.c:3119
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - block/blk-core.c:blk_stop_queue
  - block/blk-mq.c:blk_mq_stop_hw_queues
  - drivers/pci/hotplug/pciehp_core.c:release_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/net/phy/phy.c:phy_trigger_machine
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/mmc/core/core.c:mmc_detect_card_removed
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:addrconf_del_dad_work
  - net/strparser/strparser.c:__strp_recv
```
**Symbols:**

```
ffffffff810ac580-ffffffff810ac61d: cancel_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool cancel_delayed_work(struct delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b5460)
Location: kernel/workqueue.c:3142
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - block/blk-mq.c:blk_mq_stop_hw_queues
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_flush
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/mmc/core/core.c:mmc_detect_card_removed
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:addrconf_del_dad_work
  - net/strparser/strparser.c:__strp_recv
```
**Symbols:**

```
ffffffff810b5460-ffffffff810b54fd: cancel_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool cancel_delayed_work(struct delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bb280)
Location: kernel/workqueue.c:3242
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - block/blk-mq.c:blk_mq_stop_hw_queues
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_flush
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/mmc/core/core.c:mmc_detect_card_removed
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:addrconf_del_dad_work
  - net/strparser/strparser.c:__strp_recv
```
**Symbols:**

```
ffffffff810bb280-ffffffff810bb30e: cancel_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool cancel_delayed_work(struct delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c14e0)
Location: kernel/workqueue.c:3251
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - block/blk-mq.c:blk_mq_stop_hw_queues
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_flush
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/mmc/core/core.c:mmc_detect_card_removed
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:addrconf_del_dad_work
  - net/strparser/strparser.c:__strp_recv
```
**Symbols:**

```
ffffffff810c14e0-ffffffff810c157d: cancel_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool cancel_delayed_work(struct delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ca940)
Location: kernel/workqueue.c:3248
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - block/blk-mq.c:blk_mq_stop_hw_queues
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:handle_button_press_event
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/mmc/core/core.c:mmc_detect_card_removed
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/strparser/strparser.c:__strp_recv
```
**Symbols:**

```
ffffffff810ca940-ffffffff810ca9dc: cancel_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool cancel_delayed_work(struct delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c5a70)
Location: kernel/workqueue.c:3254
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - block/blk-mq.c:blk_mq_stop_hw_queues
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:handle_button_press_event
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/power/supply/charger-manager.c:charger_extcon_work
  - drivers/thermal/thermal_core.c:handle_thermal_trip
  - drivers/mmc/core/core.c:mmc_detect_card_removed
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/strparser/strparser.c:__strp_recv
```
**Symbols:**

```
ffffffff810c5a70-ffffffff810c5b0c: cancel_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool cancel_delayed_work(struct delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c73a0)
Location: kernel/workqueue.c:3255
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - block/blk-mq.c:blk_mq_stop_hw_queues
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:handle_button_press_event
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/power/supply/charger-manager.c:charger_extcon_work
  - drivers/mmc/core/core.c:mmc_detect_card_removed
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/strparser/strparser.c:__strp_recv
```
**Symbols:**

```
ffffffff810c73a0-ffffffff810c743f: cancel_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool cancel_delayed_work(struct delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810da0c0)
Location: kernel/workqueue.c:3294
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - block/blk-mq.c:blk_mq_stop_hw_queues
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:handle_button_press_event
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/power/supply/charger-manager.c:charger_extcon_work
  - drivers/mmc/core/core.c:mmc_detect_card_removed
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/strparser/strparser.c:__strp_recv
```
**Symbols:**

```
ffffffff810da0c0-ffffffff810da15f: cancel_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool cancel_delayed_work(struct delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810f1830)
Location: kernel/workqueue.c:3277
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - block/blk-mq.c:blk_mq_stop_hw_queues
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:handle_button_press_event
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/base/dd.c:deferred_probe_extend_timeout
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/power/supply/charger-manager.c:charger_extcon_work
  - drivers/thermal/thermal_core.c:handle_thermal_trip
  - drivers/mmc/core/core.c:mmc_detect_card_removed
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/strparser/strparser.c:__strp_recv
```
**Symbols:**

```
ffffffff810f1830-ffffffff810f18e2: cancel_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool cancel_delayed_work(struct delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff811148f0)
Location: kernel/workqueue.c:3284
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
  - block/blk-mq.c:blk_mq_stop_hw_queues
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:handle_button_press_event
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/base/dd.c:deferred_probe_extend_timeout
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/power/supply/charger-manager.c:charger_extcon_work
  - drivers/mmc/core/core.c:mmc_detect_card_removed
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/strparser/strparser.c:__strp_recv
```
**Symbols:**

```
ffffffff811148f0-ffffffff8111490d: cancel_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool cancel_delayed_work(struct delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81120880)
Location: kernel/workqueue.c:3600
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
  - block/blk-mq.c:blk_mq_stop_hw_queues
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:handle_button_press_event
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/base/dd.c:deferred_probe_extend_timeout
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/power/supply/charger-manager.c:charger_extcon_work
  - drivers/mmc/core/core.c:mmc_detect_card_removed
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/strparser/strparser.c:__strp_recv
```
**Symbols:**

```
ffffffff81120880-ffffffff8112089d: cancel_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool cancel_delayed_work(struct delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81129210)
Location: kernel/workqueue.c:3621
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
  - block/blk-mq.c:blk_mq_stop_hw_queues
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:handle_button_press_event
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/base/dd.c:deferred_probe_extend_timeout
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/power/supply/charger-manager.c:charger_extcon_work
  - drivers/thermal/thermal_core.c:thermal_pm_notify
  - drivers/mmc/core/core.c:mmc_detect_card_removed
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/strparser/strparser.c:__strp_recv
```
**Symbols:**

```
ffffffff81129210-ffffffff8112922d: cancel_delayed_work (STB_GLOBAL)
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
bool cancel_delayed_work(struct delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff80001011f758)
Location: kernel/workqueue.c:3251
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_stop_hw_queues
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/tty/serial/8250/8250_fsl.c:fsl8250_handle_irq
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_flush
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/mmc/core/core.c:mmc_detect_card_removed
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:addrconf_del_dad_work
  - net/strparser/strparser.c:__strp_recv
```
**Symbols:**

```
ffff80001011f758-ffff80001011f808: cancel_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool cancel_delayed_work(struct delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c03727cc)
Location: kernel/workqueue.c:3251
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_stop_hw_queues
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/tty/serial/8250/8250_fsl.c:fsl8250_handle_irq
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_flush
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - sound/soc/soc-pcm.c:soc_pcm_prepare
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:addrconf_del_dad_work
  - net/strparser/strparser.c:__strp_recv
```
**Symbols:**

```
c03727cc-c03728c4: cancel_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool cancel_delayed_work(struct delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c000000000166810)
Location: kernel/workqueue.c:3251
Inline: False
Direct callers:
  - arch/powerpc/platforms/pseries/vio.c:vio_cmo_balance
  - block/blk-mq.c:blk_mq_stop_hw_queues
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/tty/serial/8250/8250_fsl.c:fsl8250_handle_irq
  - drivers/scsi/scsi_transport_srp.c:srp_reconnect_rport
  - drivers/scsi/scsi_transport_srp.c:srp_reconnect_rport
  - drivers/scsi/scsi_transport_srp.c:store_reconnect_delay
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_flush
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/mmc/core/core.c:mmc_detect_card_removed
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/strparser/strparser.c:__strp_recv
```
**Symbols:**

```
c000000000166810-c000000000166910: cancel_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool cancel_delayed_work(struct delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d9b9e)
Location: kernel/workqueue.c:3251
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_stop_hw_queues
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_flush
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/mmc/core/core.c:mmc_detect_card_removed
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/strparser/strparser.c:__strp_recv
```
**Symbols:**

```
ffffffe0000d9b9e-ffffffe0000d9c22: cancel_delayed_work (STB_GLOBAL)
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
bool cancel_delayed_work(struct delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bb850)
Location: kernel/workqueue.c:3251
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - block/blk-mq.c:blk_mq_stop_hw_queues
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_flush
  - drivers/mmc/core/core.c:mmc_detect_card_removed
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:addrconf_del_dad_work
  - net/strparser/strparser.c:__strp_recv
```
**Symbols:**

```
ffffffff810bb850-ffffffff810bb8ed: cancel_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool cancel_delayed_work(struct delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810aa2f0)
Location: kernel/workqueue.c:3251
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - block/blk-mq.c:blk_mq_stop_hw_queues
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/scsi/scsi_transport_fc.c:fc_remote_port_rolechg
  - drivers/scsi/scsi_transport_fc.c:fc_remote_port_rolechg
  - drivers/scsi/scsi_transport_fc.c:fc_remote_port_add
  - drivers/scsi/scsi_transport_fc.c:fc_remote_port_add
  - drivers/scsi/scsi_transport_fc.c:fc_rport_final_delete
  - drivers/scsi/scsi_transport_fc.c:fc_rport_final_delete
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_flush
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:addrconf_del_dad_work
  - net/strparser/strparser.c:__strp_recv
```
**Symbols:**

```
ffffffff810aa2f0-ffffffff810aa385: cancel_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool cancel_delayed_work(struct delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810badb0)
Location: kernel/workqueue.c:3251
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - block/blk-mq.c:blk_mq_stop_hw_queues
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_flush
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/mmc/core/core.c:mmc_detect_card_removed
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:addrconf_del_dad_work
  - net/strparser/strparser.c:__strp_recv
```
**Symbols:**

```
ffffffff810badb0-ffffffff810bae4d: cancel_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool cancel_delayed_work(struct delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c4270)
Location: kernel/workqueue.c:3251
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - block/blk-mq.c:blk_mq_stop_hw_queues
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_flush
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/mmc/core/core.c:mmc_detect_card_removed
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:addrconf_del_dad_work
  - net/strparser/strparser.c:__strp_recv
```
**Symbols:**

```
ffffffff810c4270-ffffffff810c430d: cancel_delayed_work (STB_GLOBAL)
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
