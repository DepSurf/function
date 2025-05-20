# Function: <code>nla_get_in6_addr</code>

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
In net/ipv4/tcp_metrics.c (ffffffff81780ed6)
Location: include/net/netlink.h:1161
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff817a4699)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
```
```
In net/ipv6/route.c (ffffffff817d4040)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:ip6_route_multipath_add
```
```
In net/ipv6/fib6_rules.c (ffffffff817fe18a)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
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
In net/ipv4/tcp_metrics.c (ffffffff817ee3a6)
Location: include/net/netlink.h:1185
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81812339)
Location: include/net/netlink.h:1185
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
```
```
In net/ipv6/route.c (ffffffff81844e07)
Location: include/net/netlink.h:1185
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/fib6_rules.c (ffffffff8186daeb)
Location: include/net/netlink.h:1185
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
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
In net/ipv4/tcp_metrics.c (ffffffff8181eda6)
Location: include/net/netlink.h:1185
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81843849)
Location: include/net/netlink.h:1185
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
```
```
In net/ipv6/route.c (ffffffff81876b77)
Location: include/net/netlink.h:1185
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/fib6_rules.c (ffffffff818a08cb)
Location: include/net/netlink.h:1185
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
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
In net/ipv4/tcp_metrics.c (ffffffff8183f9d5)
Location: include/net/netlink.h:1197
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818650a7)
Location: include/net/netlink.h:1197
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
```
```
In net/ipv6/route.c (ffffffff8189e84f)
Location: include/net/netlink.h:1197
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/fib6_rules.c (ffffffff818c6f70)
Location: include/net/netlink.h:1197
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
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
In net/ipv4/tcp_metrics.c (ffffffff818bed75)
Location: include/net/netlink.h:1240
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818e5207)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
```
```
In net/ipv6/route.c (ffffffff81920e0d)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/fib6_rules.c (ffffffff8194a48d)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
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
In net/ipv4/tcp_metrics.c (ffffffff81914976)
Location: include/net/netlink.h:1240
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8193badc)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
```
```
In net/ipv6/route.c (ffffffff8197921b)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/fib6_rules.c (ffffffff819a3552)
Location: include/net/netlink.h:1240
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
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
In net/ipv4/tcp_metrics.c (ffffffff81943126)
Location: include/net/netlink.h:1383
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8196b7cc)
Location: include/net/netlink.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
```
```
In net/ipv6/route.c (ffffffff819aedf7)
Location: include/net/netlink.h:1383
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/fib6_rules.c (ffffffff819da062)
Location: include/net/netlink.h:1383
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
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
In net/ipv4/tcp_metrics.c (ffffffff819a76e6)
Location: include/net/netlink.h:1641
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819d237a)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
```
```
In net/ipv4/nexthop.c (ffffffff819d443e)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff81a1cd84)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/fib6_rules.c (ffffffff81a48d36)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
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
In net/ipv4/tcp_metrics.c (ffffffff819de766)
Location: include/net/netlink.h:1641
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a08eea)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
```
```
In net/ipv4/nexthop.c (ffffffff81a0afae)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff81a53a39)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/fib6_rules.c (ffffffff81a7f926)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
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
In net/ipv4/tcp_metrics.c (ffffffff81acb7c2)
Location: include/net/netlink.h:1708
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af9485)
Location: include/net/netlink.h:1708
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
```
```
In net/ipv4/nexthop.c (ffffffff81afb7f2)
Location: include/net/netlink.h:1708
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff81b4b140)
Location: include/net/netlink.h:1708
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/fib6_rules.c (ffffffff81b7a4f0)
Location: include/net/netlink.h:1708
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb3267)
Location: include/net/netlink.h:1708
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_addr
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
In net/ipv4/tcp_metrics.c (ffffffff81ad7782)
Location: include/net/netlink.h:1721
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b060f5)
Location: include/net/netlink.h:1721
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
```
```
In net/ipv4/nexthop.c (ffffffff81b08ec2)
Location: include/net/netlink.h:1721
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff81b59ddf)
Location: include/net/netlink.h:1721
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/fib6_rules.c (ffffffff81b89440)
Location: include/net/netlink.h:1721
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc7713)
Location: include/net/netlink.h:1721
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_addr
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
In net/ipv4/tcp_metrics.c (ffffffff81ac2854)
Location: include/net/netlink.h:1721
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af1952)
Location: include/net/netlink.h:1721
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
```
```
In net/ipv4/nexthop.c (ffffffff81af55ed)
Location: include/net/netlink.h:1721
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff81b47e58)
Location: include/net/netlink.h:1721
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/fib6_rules.c (ffffffff81b78264)
Location: include/net/netlink.h:1721
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb8be6)
Location: include/net/netlink.h:1721
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_addr
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
In net/ipv4/tcp_metrics.c (ffffffff81b806f4)
Location: include/net/netlink.h:1721
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb1e62)
Location: include/net/netlink.h:1721
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
```
```
In net/ipv4/nexthop.c (ffffffff81bb5eed)
Location: include/net/netlink.h:1721
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff81c0a042)
Location: include/net/netlink.h:1721
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/fib6_rules.c (ffffffff81c42d04)
Location: include/net/netlink.h:1721
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
```
In net/mptcp/pm_netlink.c (ffffffff81c881b6)
Location: include/net/netlink.h:1721
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_addr
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
In net/ipv4/tcp_metrics.c (ffffffff81d10abc)
Location: include/net/netlink.h:1721
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d4559c)
Location: include/net/netlink.h:1721
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
```
```
In net/ipv4/nexthop.c (ffffffff81d49765)
Location: include/net/netlink.h:1721
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff81da4574)
Location: include/net/netlink.h:1721
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/fib6_rules.c (ffffffff81de19c4)
Location: include/net/netlink.h:1721
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81deb8a3)
Location: include/net/netlink.h:1721
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
```
In net/mptcp/pm_netlink.c (ffffffff81e2eaa1)
Location: include/net/netlink.h:1721
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr
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
In net/ipv4/tcp_metrics.c (ffffffff81ed682c)
Location: include/net/netlink.h:1770
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0e93c)
Location: include/net/netlink.h:1770
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
```
```
In net/ipv4/nexthop.c (ffffffff81f12da5)
Location: include/net/netlink.h:1770
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff81f739e4)
Location: include/net/netlink.h:1770
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/ip6mr.c (ffffffff81fad215)
Location: include/net/netlink.h:1770
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
```
```
In net/ipv6/fib6_rules.c (ffffffff81fb3ea4)
Location: include/net/netlink.h:1770
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbf503)
Location: include/net/netlink.h:1770
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
```
In net/mptcp/pm_netlink.c (ffffffff82006c31)
Location: include/net/netlink.h:1770
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr
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
In net/ipv4/tcp_metrics.c (ffffffff81f3579c)
Location: include/net/netlink.h:1771
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6e5fc)
Location: include/net/netlink.h:1771
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
```
```
In net/ipv4/nexthop.c (ffffffff81f72a6c)
Location: include/net/netlink.h:1771
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff81fd3ac4)
Location: include/net/netlink.h:1771
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/ip6mr.c (ffffffff8200d9d5)
Location: include/net/netlink.h:1771
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
```
```
In net/ipv6/fib6_rules.c (ffffffff82014644)
Location: include/net/netlink.h:1771
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020493)
Location: include/net/netlink.h:1771
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
```
In net/mptcp/pm_netlink.c (ffffffff82082fd1)
Location: include/net/netlink.h:1771
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr
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
In net/ipv4/tcp_metrics.c (ffffffff81ffb84c)
Location: include/net/netlink.h:1869
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82034d1f)
Location: include/net/netlink.h:1869
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
```
```
In net/ipv4/nexthop.c (ffffffff82038c0f)
Location: include/net/netlink.h:1869
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff820a13d5)
Location: include/net/netlink.h:1869
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/ip6mr.c (ffffffff820dd455)
Location: include/net/netlink.h:1869
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
```
```
In net/ipv6/fib6_rules.c (ffffffff820e3784)
Location: include/net/netlink.h:1869
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820ef5c6)
Location: include/net/netlink.h:1869
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
```
In net/mptcp/pm_netlink.c (ffffffff8215864f)
Location: include/net/netlink.h:1869
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr
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
In net/ipv4/tcp_metrics.c (ffff800010c91aa4)
Location: include/net/netlink.h:1641
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffff800010cc222c)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
```
```
In net/ipv4/nexthop.c (ffff800010cc454c)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffff800010d17c08)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/fib6_rules.c (ffff800010d4add4)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
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
In net/ipv4/tcp_metrics.c (c0da05b4)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:__parse_nl_addr
```
```
In net/ipv4/ip_tunnel_core.c (c0dcd8f0)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
```
```
In net/ipv4/nexthop.c (c0dcff68)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (c0e1d788)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/fib6_rules.c (c0e4c11c)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
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
In net/ipv4/tcp_metrics.c (c000000000da1d20)
Location: include/net/netlink.h:1641
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (c000000000ddd85c)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
```
```
In net/ipv4/nexthop.c (c000000000de056c)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (c000000000e4576c)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/fib6_rules.c (c000000000e80fcc)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
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
In net/ipv4/tcp_metrics.c (ffffffe0007f19be)
Location: include/net/netlink.h:1641
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe0008176e0)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
```
```
In net/ipv4/nexthop.c (ffffffe000819aa2)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffe00085cb60)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/fib6_rules.c (ffffffe000883eb2)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
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
In net/ipv4/tcp_metrics.c (ffffffff8197e5d6)
Location: include/net/netlink.h:1641
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819a8c8a)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
```
```
In net/ipv4/nexthop.c (ffffffff819aad4e)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff819f30c9)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/fib6_rules.c (ffffffff81a1efb6)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
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
In drivers/net/vxlan.c (ffffffff8176ee93)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_nl2conf
  - drivers/net/vxlan.c:vxlan_nl2conf
  - drivers/net/vxlan.c:vxlan_fdb_parse
```
```
In net/ipv4/tcp_metrics.c (ffffffff81938096)
Location: include/net/netlink.h:1641
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8196274a)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
```
```
In net/ipv4/nexthop.c (ffffffff8196480e)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff819afe89)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/fib6_rules.c (ffffffff819dbd76)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
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
In net/netfilter/nf_conntrack_netlink.c (ffffffff819ad12f)
Location: include/net/netlink.h:1641
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e8da6)
Location: include/net/netlink.h:1641
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1352a)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
```
```
In net/ipv4/nexthop.c (ffffffff81a155ee)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff81a5db49)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/fib6_rules.c (ffffffff81a89a36)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
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
In net/ipv4/tcp_metrics.c (ffffffff819f2b06)
Location: include/net/netlink.h:1641
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1defa)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
```
```
In net/ipv4/nexthop.c (ffffffff81a2002e)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff81a69f59)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/fib6_rules.c (ffffffff81a96696)
Location: include/net/netlink.h:1641
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
</details>
</li>
</ul>

## Differences
