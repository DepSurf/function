# Function: <code>nla_put_flag</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff819caeca)
Location: include/net/netlink.h:1019
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff81a03989)
Location: include/net/netlink.h:1162
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In net/core/devlink.c (ffffffff8194ecbc)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
```
```
In net/ipv4/nexthop.c (ffffffff819d38c4)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a72b71)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In net/core/devlink.c (ffffffff81983b87)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
```
```
In net/ipv4/nexthop.c (ffffffff81a0a434)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81aa9331)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In net/core/devlink.c (ffffffff81a5b252)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_metadata_put
  - net/core/devlink.c:devlink_trap_metadata_put
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
```
```
In net/ethtool/bitset.c (ffffffff81a87597)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ipv4/nexthop.c (ffffffff81afae53)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba4d1a)
Location: include/net/netlink.h:1472
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In net/core/devlink.c (ffffffff81a627ce)
Location: include/net/netlink.h:1485
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_metadata_put
  - net/core/devlink.c:devlink_trap_metadata_put
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
```
```
In net/ethtool/bitset.c (ffffffff81a90f12)
Location: include/net/netlink.h:1485
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ipv4/nexthop.c (ffffffff81b08523)
Location: include/net/netlink.h:1485
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81bb41da)
Location: include/net/netlink.h:1485
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In net/core/devlink.c (ffffffff81a44f58)
Location: include/net/netlink.h:1485
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
```
```
In net/ethtool/bitset.c (ffffffff81a7a713)
Location: include/net/netlink.h:1485
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ipv4/nexthop.c (ffffffff81af6e4b)
Location: include/net/netlink.h:1485
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba31b0)
Location: include/net/netlink.h:1485
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In net/core/devlink.c (ffffffff81afdf5f)
Location: include/net/netlink.h:1485
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
```
```
In net/ethtool/bitset.c (ffffffff81b34b23)
Location: include/net/netlink.h:1485
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ipv4/nexthop.c (ffffffff81bb679c)
Location: include/net/netlink.h:1485
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81c715a1)
Location: include/net/netlink.h:1485
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In net/core/devlink.c (ffffffff81c81493)
Location: include/net/netlink.h:1485
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
```
```
In net/ethtool/bitset.c (ffffffff81cc00d3)
Location: include/net/netlink.h:1485
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ipv4/nexthop.c (ffffffff81d4a3f6)
Location: include/net/netlink.h:1485
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81e15176)
Location: include/net/netlink.h:1485
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In net/core/devlink.c (ffffffff81e396d3)
Location: include/net/netlink.h:1534
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_selftests_fill
```
```
In net/ethtool/bitset.c (ffffffff81e7ece3)
Location: include/net/netlink.h:1534
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ipv4/nexthop.c (ffffffff81f13a96)
Location: include/net/netlink.h:1534
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81fec0b6)
Location: include/net/netlink.h:1534
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In net/ethtool/bitset.c (ffffffff81edb2d6)
Location: include/net/netlink.h:1535
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ipv4/nexthop.c (ffffffff81f73766)
Location: include/net/netlink.h:1535
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/devlink/leftover.c (ffffffff8203bfdb)
Location: include/net/netlink.h:1535
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_trap_group_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_nl_param_value_fill_one
```
```
In net/devlink/dev.c (ffffffff82043731)
Location: include/net/netlink.h:1535
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_selftests_fill
```
```
In net/devlink/health.c (ffffffff82047117)
Location: include/net/netlink.h:1535
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_fmsg_prepare_skb
```
```
In net/ncsi/ncsi-netlink.c (ffffffff82068356)
Location: include/net/netlink.h:1535
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In net/ethtool/bitset.c (ffffffff81f9f096)
Location: include/net/netlink.h:1611
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ipv4/nexthop.c (ffffffff82039f56)
Location: include/net/netlink.h:1611
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/devlink/dev.c (ffffffff82102b71)
Location: include/net/netlink.h:1611
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_selftests_fill
```
```
In net/devlink/param.c (ffffffff8210db53)
Location: include/net/netlink.h:1611
Inline: True
Inline callers:
  - net/devlink/param.c:devlink_nl_param_value_fill_one
```
```
In net/devlink/health.c (ffffffff82113047)
Location: include/net/netlink.h:1611
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_fmsg_prepare_skb
```
```
In net/devlink/trap.c (ffffffff8211552b)
Location: include/net/netlink.h:1611
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_nl_trap_group_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
```
```
In net/ncsi/ncsi-netlink.c (ffffffff8213b5d6)
Location: include/net/netlink.h:1611
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In net/core/devlink.c (ffff800010c2c1bc)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
```
```
In net/ipv4/nexthop.c (ffff800010cc3948)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ncsi/ncsi-netlink.c (ffff800010d7cdac)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In net/core/devlink.c (c0d42748)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
```
```
In net/ipv4/nexthop.c (c0dcf124)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ncsi/ncsi-netlink.c (c0e77c48)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In net/core/devlink.c (c000000000d22d20)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
```
```
In net/ipv4/nexthop.c (c000000000ddf690)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ncsi/ncsi-netlink.c (c000000000ebc7e0)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In net/core/devlink.c (ffffffe0007a3798)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
```
```
In net/ipv4/nexthop.c (ffffffe000818b7c)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ncsi/ncsi-netlink.c (ffffffe0008aab38)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In net/core/devlink.c (ffffffff819239f7)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
```
```
In net/ipv4/nexthop.c (ffffffff819aa1d4)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a486c1)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In drivers/net/vxlan.c (ffffffff8176dcfc)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_fill_info
  - drivers/net/vxlan.c:vxlan_fill_info
  - drivers/net/vxlan.c:vxlan_fill_info
```
```
In net/core/devlink.c (ffffffff818dd7a7)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
```
```
In net/ipv4/nexthop.c (ffffffff81963c94)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a052b1)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In net/core/devlink.c (ffffffff81974b87)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
```
```
In net/ipv4/nexthop.c (ffffffff81a14a74)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ab4571)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In net/core/devlink.c (ffffffff81997077)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
```
```
In net/ipv4/nexthop.c (ffffffff81a1f484)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ac0911)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
</details>
</li>
</ul>

## Differences
