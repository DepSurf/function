# Function: <code>nla_put_in6_addr</code>

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
In net/ipv4/tcp_metrics.c (ffffffff817811e7)
Location: include/net/netlink.h:982
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff817a42ed)
Location: include/net/netlink.h:982
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
```
```
In net/ipv6/addrconf.c (ffffffff817cc2ba)
Location: include/net/netlink.h:982
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
```
In net/ipv6/addrlabel.c (ffffffff817d2564)
Location: include/net/netlink.h:982
Inline: True
```
```
In net/ipv6/route.c (ffffffff817d86ed)
Location: include/net/netlink.h:982
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffff817dfa96)
Location: include/net/netlink.h:982
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffffffff817f92e2)
Location: include/net/netlink.h:982
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/ipv6/fib6_rules.c (ffffffff817fe2f0)
Location: include/net/netlink.h:982
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8180d941)
Location: include/net/netlink.h:982
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8180e8c7)
Location: include/net/netlink.h:982
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
In net/ipv4/tcp_metrics.c (ffffffff817ee6a7)
Location: include/net/netlink.h:1006
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81811f93)
Location: include/net/netlink.h:1006
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
```
```
In net/ipv6/addrconf.c (ffffffff818392b5)
Location: include/net/netlink.h:1006
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff81840024)
Location: include/net/netlink.h:1006
Inline: True
```
```
In net/ipv6/route.c (ffffffff818420ec)
Location: include/net/netlink.h:1006
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffff8184f1c1)
Location: include/net/netlink.h:1006
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffffffff81868b22)
Location: include/net/netlink.h:1006
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/ipv6/fib6_rules.c (ffffffff8186dc70)
Location: include/net/netlink.h:1006
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8187fdcf)
Location: include/net/netlink.h:1006
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81880f51)
Location: include/net/netlink.h:1006
Inline: True
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
In net/ipv4/tcp_metrics.c (ffffffff8181f0b7)
Location: include/net/netlink.h:1006
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818434a3)
Location: include/net/netlink.h:1006
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
```
```
In net/ipv6/addrconf.c (ffffffff8186acd5)
Location: include/net/netlink.h:1006
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff81871ca4)
Location: include/net/netlink.h:1006
Inline: True
```
```
In net/ipv6/route.c (ffffffff81873e3c)
Location: include/net/netlink.h:1006
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffff81881117)
Location: include/net/netlink.h:1006
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffffffff8189b972)
Location: include/net/netlink.h:1006
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/ipv6/fib6_rules.c (ffffffff818a0a50)
Location: include/net/netlink.h:1006
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818b467f)
Location: include/net/netlink.h:1006
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818b5801)
Location: include/net/netlink.h:1006
Inline: True
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
In net/ipv4/tcp_metrics.c (ffffffff8183fce7)
Location: include/net/netlink.h:1018
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81864cf3)
Location: include/net/netlink.h:1018
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
```
```
In net/ipv6/addrconf.c (ffffffff8188f219)
Location: include/net/netlink.h:1018
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff81896a24)
Location: include/net/netlink.h:1018
Inline: True
```
```
In net/ipv6/route.c (ffffffff81898f31)
Location: include/net/netlink.h:1018
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_nexthop_info
```
```
In net/ipv6/ndisc.c (ffffffff818a7153)
Location: include/net/netlink.h:1018
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffffffff818c1d2e)
Location: include/net/netlink.h:1018
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff818c7090)
Location: include/net/netlink.h:1018
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818db016)
Location: include/net/netlink.h:1018
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818dc149)
Location: include/net/netlink.h:1018
Inline: True
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
In net/ipv4/tcp_metrics.c (ffffffff818bf087)
Location: include/net/netlink.h:1061
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818e4e53)
Location: include/net/netlink.h:1061
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
```
```
In net/ipv6/addrconf.c (ffffffff81910869)
Location: include/net/netlink.h:1061
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff81917e88)
Location: include/net/netlink.h:1061
Inline: True
```
```
In net/ipv6/route.c (ffffffff8191a237)
Location: include/net/netlink.h:1061
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_nexthop_info
```
```
In net/ipv6/ndisc.c (ffffffff81929bb2)
Location: include/net/netlink.h:1061
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffffffff8194566e)
Location: include/net/netlink.h:1061
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff8194a5b0)
Location: include/net/netlink.h:1061
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81960bf6)
Location: include/net/netlink.h:1061
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81961d2c)
Location: include/net/netlink.h:1061
Inline: True
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
In net/ipv4/tcp_metrics.c (ffffffff81914c73)
Location: include/net/netlink.h:1061
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8193b72e)
Location: include/net/netlink.h:1061
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
```
```
In net/ipv6/addrconf.c (ffffffff8196873e)
Location: include/net/netlink.h:1061
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff8196f56a)
Location: include/net/netlink.h:1061
Inline: True
```
```
In net/ipv6/route.c (ffffffff81972319)
Location: include/net/netlink.h:1061
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_nexthop_info
```
```
In net/ipv6/ndisc.c (ffffffff81981d6f)
Location: include/net/netlink.h:1061
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffffffff8199d18e)
Location: include/net/netlink.h:1061
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff819a3409)
Location: include/net/netlink.h:1061
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_fill
  - net/ipv6/fib6_rules.c:fib6_rule_fill
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819ba3d2)
Location: include/net/netlink.h:1061
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819bb507)
Location: include/net/netlink.h:1061
Inline: True
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
In net/ipv4/tcp_metrics.c (ffffffff81943423)
Location: include/net/netlink.h:1204
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8196b41e)
Location: include/net/netlink.h:1204
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
```
```
In net/ipv6/addrconf.c (ffffffff8199d307)
Location: include/net/netlink.h:1204
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff819a50f7)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/ipv6/route.c (ffffffff819a7a71)
Location: include/net/netlink.h:1204
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_nexthop_info
```
```
In net/ipv6/ndisc.c (ffffffff819b8418)
Location: include/net/netlink.h:1204
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffffffff819d3ceb)
Location: include/net/netlink.h:1204
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff819d9f19)
Location: include/net/netlink.h:1204
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_fill
  - net/ipv6/fib6_rules.c:fib6_rule_fill
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f1d22)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f2787)
Location: include/net/netlink.h:1204
Inline: True
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
In net/ipv4/tcp_metrics.c (ffffffff819a79e3)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff819c7528)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819d20ee)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
```
```
In net/ipv4/nexthop.c (ffffffff819d38b9)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv6/addrconf.c (ffffffff81a09516)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff81a11597)
Location: include/net/netlink.h:1462
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a14157)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81a26e83)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffffffff81a41f67)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81a48ad9)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_fill
  - net/ipv6/fib6_rules.c:fib6_rule_fill
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a60724)
Location: include/net/netlink.h:1462
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a61ab5)
Location: include/net/netlink.h:1462
Inline: True
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
In net/ipv4/tcp_metrics.c (ffffffff819dea73)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff819fe0d8)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a08c5e)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
```
```
In net/ipv4/nexthop.c (ffffffff81a0a429)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv6/addrconf.c (ffffffff81a40206)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff81a481b7)
Location: include/net/netlink.h:1462
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a4ad47)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81a5d8e7)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffffffff81a78bc7)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81a7f6c9)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_fill
  - net/ipv6/fib6_rules.c:fib6_rule_fill
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a97354)
Location: include/net/netlink.h:1462
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a98692)
Location: include/net/netlink.h:1462
Inline: True
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
In net/ipv4/tcp_metrics.c (ffffffff81acba93)
Location: include/net/netlink.h:1514
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff81aecbef)
Location: include/net/netlink.h:1514
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af9d30)
Location: include/net/netlink.h:1514
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
```
```
In net/ipv4/nexthop.c (ffffffff81afb00d)
Location: include/net/netlink.h:1514
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv6/addrconf.c (ffffffff81b34442)
Location: include/net/netlink.h:1514
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifmcaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff81b3f057)
Location: include/net/netlink.h:1514
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b45246)
Location: include/net/netlink.h:1514
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81b53c02)
Location: include/net/netlink.h:1514
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/ip6mr.c (ffffffff81b745c8)
Location: include/net/netlink.h:1514
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/ipv6/fib6_rules.c (ffffffff81b7a299)
Location: include/net/netlink.h:1514
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_fill
  - net/ipv6/fib6_rules.c:fib6_rule_fill
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b93569)
Location: include/net/netlink.h:1514
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b93dbe)
Location: include/net/netlink.h:1514
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb30fc)
Location: include/net/netlink.h:1514
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
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
In net/ipv4/tcp_metrics.c (ffffffff81ad7a53)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff81af9fad)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b07480)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
```
```
In net/ipv4/nexthop.c (ffffffff81b086dd)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv6/addrconf.c (ffffffff81b44c92)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifmcaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff81b4dad7)
Location: include/net/netlink.h:1527
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b53be9)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81b621f2)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/ip6mr.c (ffffffff81b83338)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/ipv6/fib6_rules.c (ffffffff81b891e9)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_fill
  - net/ipv6/fib6_rules.c:fib6_rule_fill
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81ba31b9)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba3a22)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc758d)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
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
In net/ipv4/tcp_metrics.c (ffffffff81ac2bf3)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae56ed)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af2c30)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
```
```
In net/ipv4/nexthop.c (ffffffff81af702e)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv6/addrconf.c (ffffffff81b32f5e)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff81b3b567)
Location: include/net/netlink.h:1527
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b411ac)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81b50452)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/ip6mr.c (ffffffff81b71fb9)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/ipv6/fib6_rules.c (ffffffff81b78009)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_fill
  - net/ipv6/fib6_rules.c:fib6_rule_fill
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b922d9)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b92b41)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/mptcp/pm_netlink.c (ffffffff81bbb8c4)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
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
In net/ipv4/tcp_metrics.c (ffffffff81b80793)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba4aed)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb3140)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
```
```
In net/ipv4/nexthop.c (ffffffff81bb69c0)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv6/addrconf.c (ffffffff81bf91fe)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff81c01d87)
Location: include/net/netlink.h:1527
Inline: True
```
```
In net/ipv6/route.c (ffffffff81c08e82)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81c17702)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/ip6mr.c (ffffffff81c3c469)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/ipv6/fib6_rules.c (ffffffff81c42aa9)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_fill
  - net/ipv6/fib6_rules.c:fib6_rule_fill
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81c5ea79)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81c5f2e1)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/mptcp/pm_netlink.c (ffffffff81c8b504)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
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
In net/ipv4/tcp_metrics.c (ffffffff81d10b73)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3743f)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d46954)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
```
```
In net/ipv4/nexthop.c (ffffffff81d4a594)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv6/addrconf.c (ffffffff81d925ee)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff81d9bcf2)
Location: include/net/netlink.h:1527
Inline: True
```
```
In net/ipv6/route.c (ffffffff81da3719)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81db34c9)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/ip6mr.c (ffffffff81dda845)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/ipv6/fib6_rules.c (ffffffff81de1695)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_fill
  - net/ipv6/fib6_rules.c:fib6_rule_fill
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81deb6e5)
Location: include/net/netlink.h:1527
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81e00cac)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e016c2)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/mptcp/pm_netlink.c (ffffffff81e32a23)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
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
In net/ipv4/tcp_metrics.c (ffffffff81ed68f3)
Location: include/net/netlink.h:1576
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff81effc5f)
Location: include/net/netlink.h:1576
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0fd74)
Location: include/net/netlink.h:1576
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
```
```
In net/ipv4/nexthop.c (ffffffff81f13c34)
Location: include/net/netlink.h:1576
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv6/addrconf.c (ffffffff81f60d1e)
Location: include/net/netlink.h:1576
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff81f6a989)
Location: include/net/netlink.h:1576
Inline: True
```
```
In net/ipv6/route.c (ffffffff81f72b59)
Location: include/net/netlink.h:1576
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81f82e29)
Location: include/net/netlink.h:1576
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/ip6mr.c (ffffffff81fac565)
Location: include/net/netlink.h:1576
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/ipv6/fib6_rules.c (ffffffff81fb3b45)
Location: include/net/netlink.h:1576
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_fill
  - net/ipv6/fib6_rules.c:fib6_rule_fill
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbf335)
Location: include/net/netlink.h:1576
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81fd5afc)
Location: include/net/netlink.h:1576
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd6522)
Location: include/net/netlink.h:1576
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/mptcp/pm_netlink.c (ffffffff8200afba)
Location: include/net/netlink.h:1576
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
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
In net/ipv4/tcp_metrics.c (ffffffff81f35863)
Location: include/net/netlink.h:1577
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff81f5f6df)
Location: include/net/netlink.h:1577
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6fa64)
Location: include/net/netlink.h:1577
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
```
```
In net/ipv4/nexthop.c (ffffffff81f73904)
Location: include/net/netlink.h:1577
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv6/addrconf.c (ffffffff81fc0b9b)
Location: include/net/netlink.h:1577
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff81fca9bc)
Location: include/net/netlink.h:1577
Inline: True
```
```
In net/ipv6/route.c (ffffffff81fd2c4c)
Location: include/net/netlink.h:1577
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81fe3129)
Location: include/net/netlink.h:1577
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/ip6mr.c (ffffffff8200cd05)
Location: include/net/netlink.h:1577
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/ipv6/fib6_rules.c (ffffffff820142e5)
Location: include/net/netlink.h:1577
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_fill
  - net/ipv6/fib6_rules.c:fib6_rule_fill
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820202c5)
Location: include/net/netlink.h:1577
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff820517bb)
Location: include/net/netlink.h:1577
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff820521e2)
Location: include/net/netlink.h:1577
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/mptcp/pm_netlink.c (ffffffff820873ec)
Location: include/net/netlink.h:1577
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
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
In net/ipv4/tcp_metrics.c (ffffffff81ffb913)
Location: include/net/netlink.h:1653
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff82025caf)
Location: include/net/netlink.h:1653
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82036194)
Location: include/net/netlink.h:1653
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
```
```
In net/ipv4/nexthop.c (ffffffff8203a0f4)
Location: include/net/netlink.h:1653
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv6/addrconf.c (ffffffff8208e05b)
Location: include/net/netlink.h:1653
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff8209815c)
Location: include/net/netlink.h:1653
Inline: True
```
```
In net/ipv6/route.c (ffffffff820a055c)
Location: include/net/netlink.h:1653
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff820b1049)
Location: include/net/netlink.h:1653
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/ip6mr.c (ffffffff820dbcd5)
Location: include/net/netlink.h:1653
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/ipv6/fib6_rules.c (ffffffff820e3425)
Location: include/net/netlink.h:1653
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_fill
  - net/ipv6/fib6_rules.c:fib6_rule_fill
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820ef3f5)
Location: include/net/netlink.h:1653
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff82123f8b)
Location: include/net/netlink.h:1653
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff821249b4)
Location: include/net/netlink.h:1653
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/mptcp/pm_netlink.c (ffffffff8215cc30)
Location: include/net/netlink.h:1653
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
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
In net/ipv4/tcp_metrics.c (ffff800010c91c2c)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffff800010cb6250)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffff800010cc1fa4)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
```
```
In net/ipv4/nexthop.c (ffff800010cc392c)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv6/addrconf.c (ffff800010d01498)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffff800010d0b490)
Location: include/net/netlink.h:1462
Inline: True
```
```
In net/ipv6/route.c (ffff800010d0dd18)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffff800010d22b20)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffff800010d42360)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffff800010d4ac90)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_fill
  - net/ipv6/fib6_rules.c:fib6_rule_fill
```
```
In net/netlabel/netlabel_mgmt.c (ffff800010d66b20)
Location: include/net/netlink.h:1462
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d67e48)
Location: include/net/netlink.h:1462
Inline: True
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
In net/ipv4/tcp_metrics.c (c0da091c)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (c0dc1d58)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (c0dcd634)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
```
```
In net/ipv4/nexthop.c (c0dcf104)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv6/addrconf.c (c0e08fd8)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (c0e11470)
Location: include/net/netlink.h:1462
Inline: True
```
```
In net/ipv6/route.c (c0e14684)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (c0e270cc)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (c0e44c7c)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (c0e4bfb8)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_fill
  - net/ipv6/fib6_rules.c:fib6_rule_fill
```
```
In net/netlabel/netlabel_mgmt.c (c0e6521c)
Location: include/net/netlink.h:1462
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (c0e66500)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
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
In net/ipv4/tcp_metrics.c (c000000000da2240)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (c000000000dce1b0)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (c000000000ddd530)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
```
```
In net/ipv4/nexthop.c (c000000000ddf66c)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv6/addrconf.c (c000000000e2b44c)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (c000000000e35b1c)
Location: include/net/netlink.h:1462
Inline: True
```
```
In net/ipv6/route.c (c000000000e39c0c)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (c000000000e527f8)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (c000000000e77138)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (c000000000e80bf0)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_fill
  - net/ipv6/fib6_rules.c:fib6_rule_fill
```
```
In net/netlabel/netlabel_mgmt.c (c000000000ea2e50)
Location: include/net/netlink.h:1462
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (c000000000ea47e0)
Location: include/net/netlink.h:1462
Inline: True
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
In net/ipv4/tcp_metrics.c (ffffffe0007f1ce4)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffe00080d9da)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe0008174f0)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
```
```
In net/ipv4/nexthop.c (ffffffe000818b66)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv6/addrconf.c (ffffffe00084b36a)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffe0008526ee)
Location: include/net/netlink.h:1462
Inline: True
```
```
In net/ipv6/route.c (ffffffe0008559ca)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffe000864624)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffffffe00087d9ee)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffe000883dbe)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_fill
  - net/ipv6/fib6_rules.c:fib6_rule_fill
```
```
In net/netlabel/netlabel_mgmt.c (ffffffe00089a45e)
Location: include/net/netlink.h:1462
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089b2e8)
Location: include/net/netlink.h:1462
Inline: True
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
In net/ipv4/tcp_metrics.c (ffffffff8197e8e3)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff8199de78)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819a89fe)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
```
```
In net/ipv4/nexthop.c (ffffffff819aa1c9)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv6/addrconf.c (ffffffff819df896)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff819e7847)
Location: include/net/netlink.h:1462
Inline: True
```
```
In net/ipv6/route.c (ffffffff819ea3d7)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff819fcf77)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffffffff81a18257)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81a1ed59)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_fill
  - net/ipv6/fib6_rules.c:fib6_rule_fill
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a366e4)
Location: include/net/netlink.h:1462
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a37a22)
Location: include/net/netlink.h:1462
Inline: True
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
In drivers/net/vxlan.c (ffffffff8176dd33)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_fill_info
  - drivers/net/vxlan.c:vxlan_fill_info
  - drivers/net/vxlan.c:vxlan_fdb_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff819383a3)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff81957938)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819624be)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
```
```
In net/ipv4/nexthop.c (ffffffff81963c89)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv6/addrconf.c (ffffffff8199c656)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff819a4607)
Location: include/net/netlink.h:1462
Inline: True
```
```
In net/ipv6/route.c (ffffffff819a7197)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff819b9d37)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffffffff819d5017)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff819dbb19)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_fill
  - net/ipv6/fib6_rules.c:fib6_rule_fill
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f3304)
Location: include/net/netlink.h:1462
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f4642)
Location: include/net/netlink.h:1462
Inline: True
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
In net/netfilter/nf_conntrack_netlink.c (ffffffff819accee)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_tuples_ip
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_tuples_ip
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e90b3)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff81a08718)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1329e)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
```
```
In net/ipv4/nexthop.c (ffffffff81a14a69)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv6/addrconf.c (ffffffff81a4a316)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff81a522c7)
Location: include/net/netlink.h:1462
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a54e57)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81a679f7)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffffffff81a82cd7)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81a897d9)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_fill
  - net/ipv6/fib6_rules.c:fib6_rule_fill
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aa2594)
Location: include/net/netlink.h:1462
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aa38d2)
Location: include/net/netlink.h:1462
Inline: True
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
In net/ipv4/tcp_metrics.c (ffffffff819f2e13)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff81a12e59)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1dc6e)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
```
```
In net/ipv4/nexthop.c (ffffffff81a1f479)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv6/addrconf.c (ffffffff81a56256)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff81a5e2b7)
Location: include/net/netlink.h:1462
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a60e47)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81a73fe6)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffffffff81a8f5a7)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81a96439)
Location: include/net/netlink.h:1462
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_fill
  - net/ipv6/fib6_rules.c:fib6_rule_fill
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aae904)
Location: include/net/netlink.h:1462
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aafcf2)
Location: include/net/netlink.h:1462
Inline: True
```
</details>
</li>
</ul>

## Differences
