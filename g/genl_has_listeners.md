# Function: <code>genl_has_listeners</code>

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
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bbb924)
Location: include/net/genetlink.h:434
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
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81c8b564)
Location: include/net/genetlink.h:434
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
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81e32b05)
Location: include/net/genetlink.h:434
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_userspace_pm_active
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff8200b565)
Location: include/net/genetlink.h:516
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_userspace_pm_active
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
In net/core/netdev-genl.c (ffffffff81e7cf42)
Location: include/net/genetlink.h:516
Inline: True
```
```
In net/mptcp/pm_netlink.c (ffffffff820879f5)
Location: include/net/genetlink.h:516
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_userspace_pm_active
```
```
In net/handshake/netlink.c (ffffffff820924a1)
Location: include/net/genetlink.h:516
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
In drivers/thermal/thermal_netlink.c (ffffffff81e03ed5)
Location: include/net/genetlink.h:621
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/netdev-genl.c (ffffffff81f3d6b4)
Location: include/net/genetlink.h:621
Inline: True
Inline callers:
  - net/core/netdev-genl.c:netdev_genl_dev_notify
```
```
In net/core/page_pool_user.c (ffffffff81f454f7)
Location: include/net/genetlink.h:621
Inline: True
Inline callers:
  - net/core/page_pool_user.c:netdev_nl_page_pool_event
```
```
In net/devlink/dev.c (ffffffff82103306)
Location: include/net/genetlink.h:621
Inline: True
```
```
In net/devlink/port.c (ffffffff82106c92)
Location: include/net/genetlink.h:621
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_port_notify
```
```
In net/devlink/param.c (ffffffff8210e3ac)
Location: include/net/genetlink.h:621
Inline: True
```
```
In net/devlink/region.c (ffffffff8210fdbb)
Location: include/net/genetlink.h:621
Inline: True
Inline callers:
  - net/devlink/region.c:devlink_nl_region_notify
```
```
In net/devlink/health.c (ffffffff82113a14)
Location: include/net/genetlink.h:621
Inline: True
```
```
In net/devlink/trap.c (ffffffff82114e3c)
Location: include/net/genetlink.h:621
Inline: True
```
```
In net/devlink/rate.c (ffffffff82118b22)
Location: include/net/genetlink.h:621
Inline: True
Inline callers:
  - net/devlink/rate.c:devlink_rate_notify
```
```
In net/devlink/linecard.c (ffffffff82119cba)
Location: include/net/genetlink.h:621
Inline: True
Inline callers:
  - net/devlink/linecard.c:devlink_linecard_notify
```
```
In net/mptcp/pm_netlink.c (ffffffff8215d255)
Location: include/net/genetlink.h:621
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_userspace_pm_active
```
```
In net/handshake/netlink.c (ffffffff82168d81)
Location: include/net/genetlink.h:621
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
