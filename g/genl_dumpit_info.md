# Function: <code>genl_dumpit_info</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a57171)
Location: include/net/genetlink.h:131
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
```
```
In net/netlink/genetlink.c (ffffffff81a7b8c5)
Location: include/net/genetlink.h:131
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_parallel_done
  - net/netlink/genetlink.c:genl_lock_done
  - net/netlink/genetlink.c:genl_lock_dumpit
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
In drivers/thermal/thermal_netlink.c (ffffffff8195f5ee)
Location: include/net/genetlink.h:176
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
```
```
In net/core/devlink.c (ffffffff81a5e901)
Location: include/net/genetlink.h:176
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/netlink/genetlink.c (ffffffff81a84795)
Location: include/net/genetlink.h:176
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_parallel_done
  - net/netlink/genetlink.c:genl_lock_done
  - net/netlink/genetlink.c:genl_lock_dumpit
```
```
In net/ethtool/netlink.c (ffffffff81a8f9d5)
Location: include/net/genetlink.h:176
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_start
```
```
In net/ethtool/tunnels.c (ffffffff81a97635)
Location: include/net/genetlink.h:176
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_start
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
In drivers/thermal/thermal_netlink.c (ffffffff81942b4e)
Location: include/net/genetlink.h:177
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
```
```
In net/core/devlink.c (ffffffff81a496d7)
Location: include/net/genetlink.h:177
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/netlink/genetlink.c (ffffffff81a6d885)
Location: include/net/genetlink.h:177
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_parallel_done
  - net/netlink/genetlink.c:genl_lock_done
  - net/netlink/genetlink.c:genl_lock_dumpit
```
```
In net/ethtool/netlink.c (ffffffff81a79105)
Location: include/net/genetlink.h:177
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_start
```
```
In net/ethtool/tunnels.c (ffffffff81a81095)
Location: include/net/genetlink.h:177
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_start
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
In drivers/thermal/thermal_netlink.c (ffffffff819e74a0)
Location: include/net/genetlink.h:177
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
```
```
In net/core/devlink.c (ffffffff81afbd47)
Location: include/net/genetlink.h:177
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/netlink/genetlink.c (ffffffff81b26f95)
Location: include/net/genetlink.h:177
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_parallel_done
  - net/netlink/genetlink.c:genl_lock_done
  - net/netlink/genetlink.c:genl_lock_dumpit
```
```
In net/ethtool/netlink.c (ffffffff81b333a5)
Location: include/net/genetlink.h:177
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_start
```
```
In net/ethtool/tunnels.c (ffffffff81b3ade5)
Location: include/net/genetlink.h:177
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_start
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
In drivers/thermal/thermal_netlink.c (ffffffff81b4cc90)
Location: include/net/genetlink.h:177
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
```
```
In net/core/devlink.c (ffffffff81c87376)
Location: include/net/genetlink.h:177
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/netlink/genetlink.c (ffffffff81cafec5)
Location: include/net/genetlink.h:177
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_parallel_done
  - net/netlink/genetlink.c:genl_lock_done
  - net/netlink/genetlink.c:genl_lock_dumpit
```
```
In net/ethtool/netlink.c (ffffffff81cbe595)
Location: include/net/genetlink.h:177
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_start
```
```
In net/ethtool/tunnels.c (ffffffff81cc6d75)
Location: include/net/genetlink.h:177
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_start
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
In drivers/thermal/thermal_netlink.c (ffffffff81ce4960)
Location: include/net/genetlink.h:258
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
```
```
In net/core/devlink.c (ffffffff81e433c4)
Location: include/net/genetlink.h:258
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/netlink/genetlink.c (ffffffff81e6d0f5)
Location: include/net/genetlink.h:258
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_parallel_done
  - net/netlink/genetlink.c:genl_lock_done
  - net/netlink/genetlink.c:genl_lock_dumpit
```
```
In net/ethtool/netlink.c (ffffffff81e7d075)
Location: include/net/genetlink.h:258
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_start
```
```
In net/ethtool/tunnels.c (ffffffff81e863b5)
Location: include/net/genetlink.h:258
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_start
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
In drivers/thermal/thermal_netlink.c (ffffffff81d4cf30)
Location: include/net/genetlink.h:258
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
```
```
In net/netlink/genetlink.c (ffffffff81ec9205)
Location: include/net/genetlink.h:258
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_parallel_done
  - net/netlink/genetlink.c:genl_lock_done
  - net/netlink/genetlink.c:genl_lock_dumpit
```
```
In net/ethtool/netlink.c (ffffffff81ed9655)
Location: include/net/genetlink.h:258
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_start
```
```
In net/ethtool/tunnels.c (ffffffff81ee2d95)
Location: include/net/genetlink.h:258
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_start
```
```
In net/devlink/leftover.c (ffffffff82036a44)
Location: include/net/genetlink.h:258
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/devlink/netlink.c (ffffffff82042975)
Location: include/net/genetlink.h:258
Inline: True
Inline callers:
  - net/devlink/netlink.c:devlink_nl_instance_iter_dumpit
```
```
In net/devlink/health.c (0)
Location: include/net/genetlink.h:258
Inline: True
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
In drivers/thermal/thermal_netlink.c (ffffffff81e03c30)
Location: include/net/genetlink.h:276
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
```
```
In net/core/netdev-genl.c (ffffffff81f3e17c)
Location: include/net/genetlink.h:276
Inline: True
Inline callers:
  - net/core/netdev-genl.c:netdev_nl_queue_get_dumpit
  - net/core/netdev-genl.c:netdev_nl_napi_get_dumpit
  - net/core/netdev-genl.c:netdev_nl_dev_get_dumpit
```
```
In net/core/page_pool_user.c (ffffffff81f44f55)
Location: include/net/genetlink.h:276
Inline: True
Inline callers:
  - net/core/page_pool_user.c:netdev_nl_page_pool_get_dump
```
```
In net/netlink/genetlink.c (0)
Location: include/net/genetlink.h:276
Inline: True
```
```
In net/ethtool/netlink.c (ffffffff81f9d535)
Location: include/net/genetlink.h:276
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_start
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/ethtool/tunnels.c (ffffffff81fa6c25)
Location: include/net/genetlink.h:276
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_start
```
```
In net/devlink/netlink.c (ffffffff82101c75)
Location: include/net/genetlink.h:276
Inline: True
Inline callers:
  - net/devlink/netlink.c:devlink_nl_dumpit
```
```
In net/devlink/region.c (0)
Location: include/net/genetlink.h:276
Inline: True
```
```
In net/devlink/health.c (0)
Location: include/net/genetlink.h:276
Inline: True
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
