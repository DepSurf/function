# Function: <code>genlmsg_multicast_netns_filtered</code>

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
In fs/quota/netlink.c (ffffffff81599c89)
Location: include/net/genetlink.h:470
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff81a0348b)
Location: include/net/genetlink.h:470
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/regulator/event.c (ffffffff81ae262d)
Location: include/net/genetlink.h:470
Inline: True
Inline callers:
  - drivers/regulator/event.c:reg_generate_netlink_event
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81e03fba)
Location: include/net/genetlink.h:470
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In drivers/dpll/dpll_netlink.c (ffffffff81eb9db9)
Location: include/net/genetlink.h:470
Inline: True
Inline callers:
  - drivers/dpll/dpll_netlink.c:dpll_pin_event_send
  - drivers/dpll/dpll_netlink.c:dpll_device_event_send
```
```
In net/core/netdev-genl.c (ffffffff81f3d75f)
Location: include/net/genetlink.h:470
Inline: True
Inline callers:
  - net/core/netdev-genl.c:netdev_genl_dev_notify
```
```
In net/core/page_pool_user.c (ffffffff81f45599)
Location: include/net/genetlink.h:470
Inline: True
Inline callers:
  - net/core/page_pool_user.c:netdev_nl_page_pool_event
```
```
In net/core/drop_monitor.c (ffffffff81f5d46d)
Location: include/net/genetlink.h:470
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
```
```
In net/netlink/genetlink.c (ffffffff81f8f709)
Location: include/net/genetlink.h:470
Inline: True
```
```
In net/ethtool/netlink.c (ffffffff81f9dfd3)
Location: include/net/genetlink.h:470
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_multicast
```
```
In net/devlink/dev.c (ffffffff82103238)
Location: include/net/genetlink.h:470
Inline: True
```
```
In net/devlink/port.c (ffffffff82106d55)
Location: include/net/genetlink.h:470
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_port_notify
```
```
In net/devlink/param.c (ffffffff8210e465)
Location: include/net/genetlink.h:470
Inline: True
```
```
In net/devlink/region.c (ffffffff8210fe4f)
Location: include/net/genetlink.h:470
Inline: True
Inline callers:
  - net/devlink/region.c:devlink_nl_region_notify
```
```
In net/devlink/health.c (ffffffff82113b11)
Location: include/net/genetlink.h:470
Inline: True
```
```
In net/devlink/trap.c (ffffffff82114ef5)
Location: include/net/genetlink.h:470
Inline: True
```
```
In net/devlink/rate.c (ffffffff82118bd8)
Location: include/net/genetlink.h:470
Inline: True
Inline callers:
  - net/devlink/rate.c:devlink_rate_notify
```
```
In net/devlink/linecard.c (ffffffff82119d74)
Location: include/net/genetlink.h:470
Inline: True
Inline callers:
  - net/devlink/linecard.c:devlink_linecard_notify
```
```
In net/mptcp/pm_netlink.c (ffffffff821588b5)
Location: include/net/genetlink.h:470
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_mcast_send
```
```
In net/handshake/netlink.c (ffffffff82168e2a)
Location: include/net/genetlink.h:470
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
