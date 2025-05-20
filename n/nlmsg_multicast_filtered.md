# Function: <code>nlmsg_multicast_filtered</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
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
Location: include/net/netlink.h:1101
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In fs/quota/netlink.c (ffffffff81599ca7)
Location: include/net/netlink.h:1101
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff81a034a9)
Location: include/net/netlink.h:1101
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/regulator/event.c (ffffffff81ae264b)
Location: include/net/netlink.h:1101
Inline: True
Inline callers:
  - drivers/regulator/event.c:reg_generate_netlink_event
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81e03fe1)
Location: include/net/netlink.h:1101
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In drivers/dpll/dpll_netlink.c (ffffffff81eb9ddb)
Location: include/net/netlink.h:1101
Inline: True
Inline callers:
  - drivers/dpll/dpll_netlink.c:dpll_pin_event_send
  - drivers/dpll/dpll_netlink.c:dpll_device_event_send
```
```
In net/core/sock_diag.c (ffffffff81f34d21)
Location: include/net/netlink.h:1101
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/netdev-genl.c (ffffffff81f3d776)
Location: include/net/netlink.h:1101
Inline: True
Inline callers:
  - net/core/netdev-genl.c:netdev_genl_dev_notify
```
```
In net/core/page_pool_user.c (ffffffff81f455c0)
Location: include/net/netlink.h:1101
Inline: True
Inline callers:
  - net/core/page_pool_user.c:netdev_nl_page_pool_event
```
```
In net/core/drop_monitor.c (ffffffff81f5d48f)
Location: include/net/netlink.h:1101
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
```
```
In net/netlink/af_netlink.c (ffffffff81f8be2f)
Location: include/net/netlink.h:1101
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
```
```
In net/netlink/genetlink.c (ffffffff81f8d731)
Location: include/net/netlink.h:1101
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
```
```
In net/ethtool/netlink.c (ffffffff81f9dfe8)
Location: include/net/netlink.h:1101
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_multicast
```
```
In net/devlink/dev.c (ffffffff8210324e)
Location: include/net/netlink.h:1101
Inline: True
```
```
In net/devlink/port.c (ffffffff82106d6b)
Location: include/net/netlink.h:1101
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_port_notify
```
```
In net/devlink/param.c (ffffffff8210e47b)
Location: include/net/netlink.h:1101
Inline: True
```
```
In net/devlink/region.c (ffffffff8210fe65)
Location: include/net/netlink.h:1101
Inline: True
Inline callers:
  - net/devlink/region.c:devlink_nl_region_notify
```
```
In net/devlink/health.c (ffffffff82113b27)
Location: include/net/netlink.h:1101
Inline: True
```
```
In net/devlink/trap.c (ffffffff82114f0b)
Location: include/net/netlink.h:1101
Inline: True
```
```
In net/devlink/rate.c (ffffffff82118bee)
Location: include/net/netlink.h:1101
Inline: True
Inline callers:
  - net/devlink/rate.c:devlink_rate_notify
```
```
In net/devlink/linecard.c (ffffffff82119d8a)
Location: include/net/netlink.h:1101
Inline: True
Inline callers:
  - net/devlink/linecard.c:devlink_linecard_notify
```
```
In net/mptcp/pm_netlink.c (ffffffff821588d7)
Location: include/net/netlink.h:1101
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_mcast_send
```
```
In net/handshake/netlink.c (ffffffff82168e4a)
Location: include/net/netlink.h:1101
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_genl_notify
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
