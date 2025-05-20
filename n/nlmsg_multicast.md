# Function: <code>nlmsg_multicast</code>

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
In kernel/audit.c (ffffffff81121231)
Location: include/net/netlink.h:558
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_end
```
```
In fs/quota/netlink.c (ffffffff81276889)
Location: include/net/netlink.h:558
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff8148985a)
Location: include/net/netlink.h:558
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff8168594d)
Location: include/net/netlink.h:558
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock_diag.c (ffffffff81733262)
Location: include/net/netlink.h:558
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/netlink/af_netlink.c (ffffffff8174ee7a)
Location: include/net/netlink.h:558
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff8174fa82)
Location: include/net/netlink.h:558
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
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
In kernel/audit.c (ffffffff81129171)
Location: include/net/netlink.h:569
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_end
```
```
In fs/quota/netlink.c (ffffffff812a30d5)
Location: include/net/netlink.h:569
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff814d8650)
Location: include/net/netlink.h:569
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff816e6e31)
Location: include/net/netlink.h:569
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock_diag.c (ffffffff8179ec86)
Location: include/net/netlink.h:569
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/netlink/af_netlink.c (ffffffff817bae4a)
Location: include/net/netlink.h:569
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff817bba42)
Location: include/net/netlink.h:569
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
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
In kernel/audit.c (ffffffff81132bc5)
Location: include/net/netlink.h:569
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In fs/quota/netlink.c (ffffffff812b8ab5)
Location: include/net/netlink.h:569
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff814fad38)
Location: include/net/netlink.h:569
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff81716281)
Location: include/net/netlink.h:569
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock_diag.c (ffffffff817cd656)
Location: include/net/netlink.h:569
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/netlink/af_netlink.c (ffffffff817ea7ea)
Location: include/net/netlink.h:569
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff817eb382)
Location: include/net/netlink.h:569
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
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
In kernel/audit.c (ffffffff81133c18)
Location: include/net/netlink.h:578
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In fs/quota/netlink.c (ffffffff812c5e81)
Location: include/net/netlink.h:578
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff8150a249)
Location: include/net/netlink.h:578
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff8172e081)
Location: include/net/netlink.h:578
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock_diag.c (ffffffff817ec9cf)
Location: include/net/netlink.h:578
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/netlink/af_netlink.c (ffffffff8180a74a)
Location: include/net/netlink.h:578
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff8180b392)
Location: include/net/netlink.h:578
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
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
In kernel/audit.c (ffffffff811409c8)
Location: include/net/netlink.h:584
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In fs/quota/netlink.c (ffffffff812e9d31)
Location: include/net/netlink.h:584
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff8154c749)
Location: include/net/netlink.h:584
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff8179f6b1)
Location: include/net/netlink.h:584
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock_diag.c (ffffffff81868bb2)
Location: include/net/netlink.h:584
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/netlink/af_netlink.c (ffffffff81889682)
Location: include/net/netlink.h:584
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff8188a30a)
Location: include/net/netlink.h:584
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
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
In kernel/audit.c (ffffffff8114f314)
Location: include/net/netlink.h:584
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In fs/quota/netlink.c (ffffffff81316c35)
Location: include/net/netlink.h:584
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff81582e89)
Location: include/net/netlink.h:584
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff817e6c91)
Location: include/net/netlink.h:584
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock_diag.c (ffffffff818b8a43)
Location: include/net/netlink.h:584
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/netlink/af_netlink.c (ffffffff818dd112)
Location: include/net/netlink.h:584
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff818dd93e)
Location: include/net/netlink.h:584
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
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
In kernel/audit.c (ffffffff8115bff1)
Location: include/net/netlink.h:727
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In fs/quota/netlink.c (ffffffff8132dbe5)
Location: include/net/netlink.h:727
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff8159afb9)
Location: include/net/netlink.h:727
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff81813041)
Location: include/net/netlink.h:727
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock_diag.c (ffffffff818df693)
Location: include/net/netlink.h:727
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/netlink/af_netlink.c (ffffffff81909ac8)
Location: include/net/netlink.h:727
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff8190a2fe)
Location: include/net/netlink.h:727
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
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
In kernel/audit.c (ffffffff811686a4)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In fs/quota/netlink.c (ffffffff81355924)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff815cc634)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff818550e2)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock_diag.c (ffffffff8192dd14)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/devlink.c (ffffffff8194a589)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/netlink/af_netlink.c (ffffffff8196adc5)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff8196b707)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
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
In kernel/audit.c (ffffffff81174544)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In fs/quota/netlink.c (ffffffff8136dc64)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff815ed8b4)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff81886b42)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock_diag.c (ffffffff8195ff68)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/drop_monitor.c (ffffffff81975ebf)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
```
```
In net/core/devlink.c (ffffffff81983ebf)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/netlink/af_netlink.c (ffffffff819a1865)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff819a20b7)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
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
In kernel/audit.c (ffffffff81186464)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In fs/quota/netlink.c (ffffffff813b5794)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff81699434)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In net/core/sock_diag.c (ffffffff81a33838)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/drop_monitor.c (ffffffff81a4ab7a)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report
  - net/core/drop_monitor.c:net_dm_packet_report
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
```
```
In net/core/devlink.c (ffffffff81a5fa93)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_policer_notify
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/netlink/af_netlink.c (ffffffff81a7b209)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff81a7ba99)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_mcast
  - net/netlink/genetlink.c:genlmsg_mcast
```
```
In net/ethtool/netlink.c (ffffffff81a86639)
Location: include/net/netlink.h:1013
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_multicast
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
In kernel/audit.c (ffffffff811837ea)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In fs/quota/netlink.c (ffffffff813c6fc3)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff816b6551)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_netlink.c (ffffffff8195f896)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/sock_diag.c (ffffffff81a35ba8)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/drop_monitor.c (ffffffff81a507b9)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report
  - net/core/drop_monitor.c:net_dm_packet_report
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
```
```
In net/core/devlink.c (ffffffff81a68282)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_policer_notify
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/netlink/af_netlink.c (ffffffff81a84089)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff81a84959)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_mcast
  - net/netlink/genetlink.c:genlmsg_mcast
```
```
In net/ethtool/netlink.c (ffffffff81a8ff48)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_multicast
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
In kernel/audit.c (ffffffff8118485a)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In fs/quota/netlink.c (ffffffff813ce053)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff81698601)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81942df6)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/sock_diag.c (ffffffff81a1ccf8)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/drop_monitor.c (ffffffff81a35752)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
```
```
In net/core/devlink.c (ffffffff81a43382)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_policer_notify
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/netlink/af_netlink.c (ffffffff81a6d1cd)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff81a6da63)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
```
```
In net/ethtool/netlink.c (ffffffff81a79678)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_multicast
```
```
In net/mptcp/pm_netlink.c (ffffffff81bbba10)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
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
In kernel/audit.c (ffffffff811acb6a)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In fs/quota/netlink.c (ffffffff8141f383)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff8170e381)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_netlink.c (ffffffff819e7624)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/sock_diag.c (ffffffff81ad0562)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/drop_monitor.c (ffffffff81aeb322)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
```
```
In net/core/devlink.c (ffffffff81af9862)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_policer_notify
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_rate_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/netlink/af_netlink.c (ffffffff81b2683e)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff81b27173)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
```
```
In net/ethtool/netlink.c (ffffffff81b339f8)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_multicast
```
```
In net/mptcp/pm_netlink.c (ffffffff81c8b650)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
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
In kernel/audit.c (ffffffff811de675)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In fs/quota/netlink.c (ffffffff814971c4)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff8183cd51)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81b4ce37)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/sock_diag.c (ffffffff81c4de11)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/drop_monitor.c (ffffffff81c6db81)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
```
```
In net/core/devlink.c (ffffffff81c7f149)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:devlink_linecard_notify
  - net/core/devlink.c:devlink_rate_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/netlink/af_netlink.c (ffffffff81caf53f)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff81cb00ad)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
```
```
In net/ethtool/netlink.c (ffffffff81cbf108)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_multicast
```
```
In net/mptcp/pm_netlink.c (ffffffff81e32c00)
Location: include/net/netlink.h:1026
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
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
In kernel/audit.c (ffffffff81224205)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In fs/quota/netlink.c (ffffffff8152b21f)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff819727a1)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81ce4b17)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/sock_diag.c (ffffffff81e02f11)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/drop_monitor.c (ffffffff81e257f1)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
```
```
In net/core/devlink.c (ffffffff81e37fa9)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_linecard_notify
  - net/core/devlink.c:devlink_rate_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/netlink/af_netlink.c (ffffffff81e6cb4f)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff81e6de3d)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
```
```
In net/ethtool/netlink.c (ffffffff81e7dc98)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_multicast
```
```
In net/mptcp/pm_netlink.c (ffffffff8200b660)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
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
In kernel/audit.c (ffffffff8123a7e5)
Location: include/net/netlink.h:1076
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In fs/quota/netlink.c (ffffffff815635af)
Location: include/net/netlink.h:1076
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff819b8e71)
Location: include/net/netlink.h:1076
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81d4d0e7)
Location: include/net/netlink.h:1076
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/sock_diag.c (ffffffff81e7547a)
Location: include/net/netlink.h:1076
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/netdev-genl.c (ffffffff81e7cfc5)
Location: include/net/netlink.h:1076
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81e9ad31)
Location: include/net/netlink.h:1076
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
```
```
In net/netlink/af_netlink.c (ffffffff81ec8baf)
Location: include/net/netlink.h:1076
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff81ec9f5d)
Location: include/net/netlink.h:1076
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
```
```
In net/ethtool/netlink.c (ffffffff81eda258)
Location: include/net/netlink.h:1076
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_multicast
```
```
In net/devlink/leftover.c (ffffffff8203910a)
Location: include/net/netlink.h:1076
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_region_notify
  - net/devlink/leftover.c:devlink_linecard_notify
  - net/devlink/leftover.c:devlink_rate_notify
  - net/devlink/leftover.c:devlink_port_notify
```
```
In net/devlink/dev.c (ffffffff82044423)
Location: include/net/netlink.h:1076
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_notify
```
```
In net/devlink/health.c (ffffffff82047aca)
Location: include/net/netlink.h:1076
Inline: True
```
```
In net/mptcp/pm_netlink.c (ffffffff82087af0)
Location: include/net/netlink.h:1076
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
```
```
In net/handshake/netlink.c (ffffffff8209256a)
Location: include/net/netlink.h:1076
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_genl_notify
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
In kernel/audit.c (ffffffff812544cf)
Location: include/net/netlink.h:1127
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In net/core/sock_diag.c (ffffffff81f34d21)
Location: include/net/netlink.h:1127
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/netlink/af_netlink.c (ffffffff81f8be2f)
Location: include/net/netlink.h:1127
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff81f8d731)
Location: include/net/netlink.h:1127
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
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
In kernel/audit.c (ffff8000101e8f1c)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In fs/quota/netlink.c (ffff8000104376b0)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffff800010778d54)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffff800010ad3940)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock_diag.c (ffff800010c03798)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/drop_monitor.c (ffff800010c1c32c)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
```
```
In net/core/devlink.c (ffff800010c2c508)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/netlink/af_netlink.c (ffff800010c4fe9c)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffff800010c50d6c)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
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
In kernel/audit.c (c0428f2c)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In fs/quota/netlink.c (c05ff31c)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/thermal/thermal_core.c (c0bb4508)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock_diag.c (c0d1cb38)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/drop_monitor.c (c0d3418c)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
```
```
In net/core/devlink.c (c0d43090)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/netlink/af_netlink.c (c0d600c8)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (c0d609fc)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
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
In kernel/audit.c (c000000000259aa8)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In fs/quota/netlink.c (c000000000549b08)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/thermal/thermal_core.c (c000000000bb8c5c)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock_diag.c (c000000000cecf00)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/drop_monitor.c (c000000000d0d100)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
```
```
In net/core/devlink.c (c000000000d231e4)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/netlink/af_netlink.c (c000000000d4eadc)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (c000000000d4fa88)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
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
In kernel/audit.c (ffffffe00015de0c)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In fs/quota/netlink.c (ffffffe0002d18e0)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/thermal/thermal_core.c (ffffffe0006cff3e)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock_diag.c (ffffffe000782808)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/drop_monitor.c (ffffffe0007963b8)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
```
```
In net/core/devlink.c (ffffffe0007a3a32)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/netlink/af_netlink.c (ffffffe0007bb9b6)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffe0007bc1a4)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
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
In kernel/audit.c (ffffffff8116cb64)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In fs/quota/netlink.c (ffffffff81366244)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff815dca04)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff8182c9c2)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock_diag.c (ffffffff818fff38)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/drop_monitor.c (ffffffff81915e8f)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
```
```
In net/core/devlink.c (ffffffff81923d2f)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/netlink/af_netlink.c (ffffffff819416d5)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff81941f27)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
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
In kernel/audit.c (ffffffff8115fd04)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In fs/quota/netlink.c (ffffffff81356ee4)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff815c8044)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/scsi/scsi_transport_fc.c (ffffffff8170f840)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - drivers/scsi/scsi_transport_fc.c:fc_host_post_fc_event
```
```
In drivers/thermal/thermal_core.c (ffffffff817f4052)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock_diag.c (ffffffff818b9d68)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/drop_monitor.c (ffffffff818cfc3f)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
```
```
In net/core/devlink.c (ffffffff818ddadf)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/netlink/af_netlink.c (ffffffff818fb1c5)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff818fba17)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
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
In kernel/audit.c (ffffffff8116a934)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In fs/quota/netlink.c (ffffffff81363d14)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff815e1b94)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff8187bff2)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock_diag.c (ffffffff81950f68)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/drop_monitor.c (ffffffff81966ebf)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
```
```
In net/core/devlink.c (ffffffff81974ebf)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/netlink/af_netlink.c (ffffffff81992865)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff819930b7)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
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
In kernel/audit.c (ffffffff811780f0)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In fs/quota/netlink.c (ffffffff813773c4)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff815fba54)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff81897a22)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock_diag.c (ffffffff819728a8)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/drop_monitor.c (ffffffff8198914f)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
```
```
In net/core/devlink.c (ffffffff819973af)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/netlink/af_netlink.c (ffffffff819b5355)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff819b5ba7)
Location: include/net/netlink.h:961
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genl_ctrl_event
```
</details>
</li>
</ul>

## Differences
