# Function: <code>ipv4_is_local_multicast</code>

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
In net/ipv4/route.c (0)
Location: include/linux/in.h:52
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/in.h:52
Inline: True
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
In net/ipv4/route.c (ffffffff817c2ba2)
Location: include/linux/in.h:52
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
```
```
In net/ipv4/igmp.c (ffffffff81804a83)
Location: include/linux/in.h:52
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:add_grec
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
In net/ipv4/route.c (ffffffff817f300c)
Location: include/linux/in.h:52
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
```
```
In net/ipv4/igmp.c (ffffffff81835a53)
Location: include/linux/in.h:52
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:add_grec
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
In net/ipv4/route.c (ffffffff818139ab)
Location: include/linux/in.h:52
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/igmp.c (ffffffff81856f0f)
Location: include/linux/in.h:52
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:add_grec
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
In net/ipv4/route.c (ffffffff8189300e)
Location: include/linux/in.h:52
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/igmp.c (ffffffff818d6dbf)
Location: include/linux/in.h:52
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:add_grec
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
In net/ipv4/route.c (ffffffff818e72ad)
Location: include/linux/in.h:52
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/igmp.c (ffffffff8192d772)
Location: include/linux/in.h:52
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:add_grec
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
In net/ipv4/route.c (ffffffff81914165)
Location: include/linux/in.h:52
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/igmp.c (ffffffff8195cc12)
Location: include/linux/in.h:52
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:add_grec
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
In net/ipv4/route.c (ffffffff81971399)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/igmp.c (ffffffff819c1912)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:add_grec
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
In net/ipv4/route.c (ffffffff819a7db5)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/igmp.c (ffffffff819f84b2)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:add_grec
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
In net/ipv4/route.c (ffffffff81a9151e)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/igmp.c (ffffffff81ae5f40)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_rejoin_groups
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:add_grec
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
In net/ipv4/route.c (ffffffff81a9b3a1)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/igmp.c (ffffffff81af2e10)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_rejoin_groups
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:add_grec
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
In net/ipv4/route.c (ffffffff81a867bf)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/igmp.c (ffffffff81ade692)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:add_grec
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
In net/ipv4/route.c (ffffffff81b40eff)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/igmp.c (ffffffff81b9db62)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:add_grec
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
In net/ipv4/route.c (ffffffff81ccd8b6)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/igmp.c (ffffffff81d2fd0e)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:add_grec
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
In net/ipv4/route.c (ffffffff81e8da8b)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/igmp.c (ffffffff81ef7dfe)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:add_grec
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
In net/core/rtnetlink.c (ffffffff81e4e84d)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_validate_mdb_entry
```
```
In net/ipv4/route.c (ffffffff81eec1bd)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/igmp.c (ffffffff81f5788e)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:add_grec
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
In net/core/rtnetlink.c (ffffffff81f0d5ad)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_validate_mdb_entry
```
```
In net/ipv4/route.c (ffffffff81fb020d)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/igmp.c (ffffffff8201dd1e)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:add_grec
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
In net/ipv4/route.c (ffff800010c574e4)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/igmp.c (ffff800010cb00c8)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:add_grec
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
In net/ipv4/route.c (c0d671a4)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/igmp.c (c0dbba84)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:add_grec
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
In net/ipv4/route.c (c000000000d58b6c)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/igmp.c (c000000000dc6104)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:add_grec
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
In net/ipv4/route.c (ffffffe0007c1810)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/igmp.c (ffffffe000809124)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:add_grec
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
In net/ipv4/route.c (ffffffff81947c25)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/igmp.c (ffffffff81998252)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:add_grec
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
In net/ipv4/route.c (ffffffff81901715)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/igmp.c (ffffffff81951d12)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:add_grec
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
In net/ipv4/route.c (ffffffff819b23f5)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/igmp.c (ffffffff81a02af2)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:add_grec
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
In net/ipv4/route.c (ffffffff819bbab5)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/igmp.c (ffffffff81a0d022)
Location: include/linux/in.h:48
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:add_grec
```
</details>
</li>
</ul>

## Differences
