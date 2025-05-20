# Function: <code>netdev_name</code>

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
In lib/dynamic_debug.c (ffffffff814152de)
Location: include/linux/netdevice.h:3955
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff81718c5c)
Location: include/linux/netdevice.h:3955
Inline: True
Inline callers:
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:register_netdevice
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
In lib/dynamic_debug.c (ffffffff8145cfde)
Location: include/linux/netdevice.h:4249
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff817873ce)
Location: include/linux/netdevice.h:4249
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
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
In lib/dynamic_debug.c (ffffffff8147bade)
Location: include/linux/netdevice.h:4203
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff817b498e)
Location: include/linux/netdevice.h:4203
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (ffffffff81484ecc)
Location: include/linux/netdevice.h:4261
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff817d3739)
Location: include/linux/netdevice.h:4261
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:skb_warn_bad_offload
```
**Symbols:**

```
ffffffff817ca910-ffffffff817ca936: netdev_name.part.82 (STB_LOCAL)
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
In lib/dynamic_debug.c (ffffffff814c0f18)
Location: include/linux/netdevice.h:4295
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff8184da00)
Location: include/linux/netdevice.h:4295
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
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
In lib/dynamic_debug.c (ffffffff814f0e8f)
Location: include/linux/netdevice.h:4402
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff81898965)
Location: include/linux/netdevice.h:4402
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
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
In lib/dynamic_debug.c (ffffffff8150584f)
Location: include/linux/netdevice.h:4644
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff818badc5)
Location: include/linux/netdevice.h:4644
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
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
In lib/dynamic_debug.c (ffffffff81533886)
Location: include/linux/netdevice.h:4670
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff81906726)
Location: include/linux/netdevice.h:4670
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
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
In lib/dynamic_debug.c (ffffffff815546c6)
Location: include/linux/netdevice.h:4683
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff81938cd9)
Location: include/linux/netdevice.h:4683
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const char *netdev_name(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff815ddab6)
Location: include/linux/netdevice.h:4876
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff81a0decc)
Location: include/linux/netdevice.h:4876
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_sync_lower_features
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
```
```
In net/ethtool/netlink.c (ffffffff81a858bf)
Location: include/linux/netdevice.h:4876
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethtool_notify
```
```
In net/ethtool/privflags.c (ffffffff81a8a45f)
Location: include/linux/netdevice.h:4876
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_get_priv_flags_info
```
**Symbols:**

```
ffffffff81a0e88d-ffffffff81a0e8bd: netdev_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const char *netdev_name(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff815fb7a6)
Location: include/linux/netdevice.h:5077
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff81a0ecac)
Location: include/linux/netdevice.h:5077
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_sync_lower_features
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
```
```
In net/sched/sch_frag.c (ffffffff81a6fa41)
Location: include/linux/netdevice.h:5077
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/ethtool/netlink.c (ffffffff81a8f22f)
Location: include/linux/netdevice.h:5077
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethtool_notify
```
```
In net/ethtool/privflags.c (ffffffff81a93cbf)
Location: include/linux/netdevice.h:5077
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_get_priv_flags_info
```
**Symbols:**

```
ffffffff81c30b81-ffffffff81c30bb1: netdev_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const char *netdev_name(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff815de423)
Location: include/linux/netdevice.h:5208
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff819f5a58)
Location: include/linux/netdevice.h:5208
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
```
```
In net/sched/sch_frag.c (ffffffff81a5832f)
Location: include/linux/netdevice.h:5208
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/ethtool/netlink.c (ffffffff81a7892f)
Location: include/linux/netdevice.h:5208
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethtool_notify
```
```
In net/ethtool/privflags.c (ffffffff81a7d6be)
Location: include/linux/netdevice.h:5208
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_get_priv_flags_info
```
**Symbols:**

```
ffffffff81c22e67-ffffffff81c22e97: netdev_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const char *netdev_name(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff81649ea2)
Location: include/linux/netdevice.h:5256
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff81aa7437)
Location: include/linux/netdevice.h:5256
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
```
```
In net/sched/sch_frag.c (ffffffff81b11311)
Location: include/linux/netdevice.h:5256
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/ethtool/netlink.c (ffffffff81b32acc)
Location: include/linux/netdevice.h:5256
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethtool_notify
```
```
In net/ethtool/privflags.c (ffffffff81b3790a)
Location: include/linux/netdevice.h:5256
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_get_priv_flags_info
```
**Symbols:**

```
ffffffff81d35718-ffffffff81d35748: netdev_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const char *netdev_name(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff8175f5ba)
Location: include/linux/netdevice.h:5076
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff81c1fb21)
Location: include/linux/netdevice.h:5076
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
```
```
In net/core/dev_addr_lists.c (ffffffff81f031fc)
Location: include/linux/netdevice.h:5076
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_addr_check
```
```
In net/sched/sch_frag.c (ffffffff81c983a2)
Location: include/linux/netdevice.h:5076
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/ethtool/netlink.c (ffffffff81cbe08d)
Location: include/linux/netdevice.h:5076
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethtool_notify
```
```
In net/ethtool/privflags.c (ffffffff81cc338f)
Location: include/linux/netdevice.h:5076
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_get_priv_flags_info
```
**Symbols:**

```
ffffffff81f01ceb-ffffffff81f01d2b: netdev_name (STB_LOCAL)
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
In lib/dynamic_debug.c (ffffffff8188d174)
Location: include/linux/netdevice.h:5120
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c (ffffffff81bf35a3)
Location: include/linux/netdevice.h:5120
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_port_debugfs
```
```
In net/core/dev.c (ffffffff81dc3552)
Location: include/linux/netdevice.h:5120
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
```
```
In net/core/dev_addr_lists.c (ffffffff81dd354d)
Location: include/linux/netdevice.h:5120
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_addr_check
```
```
In net/sched/sch_frag.c (ffffffff81e542f0)
Location: include/linux/netdevice.h:5120
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/ethtool/netlink.c (ffffffff81e7cafd)
Location: include/linux/netdevice.h:5120
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethtool_notify
```
```
In net/ethtool/privflags.c (ffffffff81e826cf)
Location: include/linux/netdevice.h:5120
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_get_priv_flags_info
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
In lib/dynamic_debug.c (ffffffff818cf6e4)
Location: include/linux/netdevice.h:5164
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c (ffffffff81c568e3)
Location: include/linux/netdevice.h:5164
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_port_debugfs
```
```
In net/core/dev.c (ffffffff81e329f2)
Location: include/linux/netdevice.h:5164
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
```
```
In net/core/dev_addr_lists.c (ffffffff81e4410d)
Location: include/linux/netdevice.h:5164
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_addr_check
```
```
In net/sched/sch_frag.c (ffffffff81eafb91)
Location: include/linux/netdevice.h:5164
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/ethtool/netlink.c (ffffffff81ed8ebd)
Location: include/linux/netdevice.h:5164
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethtool_notify
```
```
In net/ethtool/privflags.c (ffffffff81ededbf)
Location: include/linux/netdevice.h:5164
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_get_priv_flags_info
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
In lib/dynamic_debug.c (ffffffff8192157c)
Location: include/linux/netdevice.h:5245
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c (ffffffff81d0d077)
Location: include/linux/netdevice.h:5245
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_port_debugfs
```
```
In net/core/dev.c (ffffffff81ef0df2)
Location: include/linux/netdevice.h:5245
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
```
```
In net/core/dev_addr_lists.c (ffffffff81f02d5d)
Location: include/linux/netdevice.h:5245
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_addr_check
```
```
In net/sched/sch_frag.c (ffffffff81f725ff)
Location: include/linux/netdevice.h:5245
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/ethtool/netlink.c (ffffffff81f9cd61)
Location: include/linux/netdevice.h:5245
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethtool_notify
```
```
In net/ethtool/privflags.c (ffffffff81fa2bf3)
Location: include/linux/netdevice.h:5245
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_get_priv_flags_info
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
In lib/dynamic_debug.c (ffff800010660e68)
Location: include/linux/netdevice.h:4683
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffff800010bd8460)
Location: include/linux/netdevice.h:4683
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
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
In lib/dynamic_debug.c (c0809ed4)
Location: include/linux/netdevice.h:4683
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (c0cf2d94)
Location: include/linux/netdevice.h:4683
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
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
In lib/dynamic_debug.c (c0000000008130ac)
Location: include/linux/netdevice.h:4683
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (c000000000cb7e5c)
Location: include/linux/netdevice.h:4683
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
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
In lib/dynamic_debug.c (ffffffe00048da56)
Location: include/linux/netdevice.h:4683
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffe00076122a)
Location: include/linux/netdevice.h:4683
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
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
In lib/dynamic_debug.c (ffffffff8154cca6)
Location: include/linux/netdevice.h:4683
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff818d8ca9)
Location: include/linux/netdevice.h:4683
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
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
In lib/dynamic_debug.c (ffffffff8153cf86)
Location: include/linux/netdevice.h:4683
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff81892ae9)
Location: include/linux/netdevice.h:4683
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
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
In lib/dynamic_debug.c (ffffffff815489e6)
Location: include/linux/netdevice.h:4683
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff81929cd9)
Location: include/linux/netdevice.h:4683
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
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
In lib/dynamic_debug.c (ffffffff81562836)
Location: include/linux/netdevice.h:4683
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff8194b3a4)
Location: include/linux/netdevice.h:4683
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_disable_lro
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
