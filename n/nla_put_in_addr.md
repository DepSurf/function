# Function: <code>nla_put_in_addr</code>

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
In net/ipv4/route.c (ffffffff81753c5d)
Location: include/net/netlink.h:969
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff8178140f)
Location: include/net/netlink.h:969
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81790b72)
Location: include/net/netlink.h:969
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8179daa7)
Location: include/net/netlink.h:969
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/fib_rules.c (ffffffff817a6957)
Location: include/net/netlink.h:969
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff817a878a)
Location: include/net/netlink.h:969
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8180d78f)
Location: include/net/netlink.h:969
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8180e855)
Location: include/net/netlink.h:969
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
In net/ipv4/route.c (ffffffff817bfd2a)
Location: include/net/netlink.h:993
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff817ee8d4)
Location: include/net/netlink.h:993
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff817fdea2)
Location: include/net/netlink.h:993
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8180b798)
Location: include/net/netlink.h:993
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818120b3)
Location: include/net/netlink.h:993
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/fib_rules.c (ffffffff81814647)
Location: include/net/netlink.h:993
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff81815eba)
Location: include/net/netlink.h:993
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8187fbe4)
Location: include/net/netlink.h:993
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81880ee2)
Location: include/net/netlink.h:993
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
In net/ipv4/route.c (ffffffff817f2e37)
Location: include/net/netlink.h:993
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181f2e4)
Location: include/net/netlink.h:993
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff8182ee02)
Location: include/net/netlink.h:993
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8183c8b9)
Location: include/net/netlink.h:993
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818435c3)
Location: include/net/netlink.h:993
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/fib_rules.c (ffffffff81845da7)
Location: include/net/netlink.h:993
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff8184766a)
Location: include/net/netlink.h:993
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818b4494)
Location: include/net/netlink.h:993
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818b5792)
Location: include/net/netlink.h:993
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
In net/ipv4/route.c (ffffffff81813814)
Location: include/net/netlink.h:1005
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_metrics.c (ffffffff8183fe9d)
Location: include/net/netlink.h:1005
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff818502d0)
Location: include/net/netlink.h:1005
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8185e01f)
Location: include/net/netlink.h:1005
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81864e13)
Location: include/net/netlink.h:1005
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/fib_rules.c (ffffffff81867907)
Location: include/net/netlink.h:1005
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff8186a26a)
Location: include/net/netlink.h:1005
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818daeb5)
Location: include/net/netlink.h:1005
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818dc081)
Location: include/net/netlink.h:1005
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
In net/ipv4/route.c (ffffffff81892e6e)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bf240)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff818cff00)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff818dde82)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818e4f6e)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/fib_rules.c (ffffffff818e7a61)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff818ea9ea)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81960a95)
Location: include/net/netlink.h:1046
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81961c5d)
Location: include/net/netlink.h:1046
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
In net/ipv4/route.c (ffffffff818e6f3d)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_metrics.c (ffffffff81914ecb)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81926455)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff819349fd)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8193b84e)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/fib_rules.c (ffffffff8193e5c1)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff819411bb)
Location: include/net/netlink.h:1046
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819ba237)
Location: include/net/netlink.h:1046
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819bb406)
Location: include/net/netlink.h:1046
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
In net/ipv4/route.c (ffffffff81913e12)
Location: include/net/netlink.h:1189
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_metrics.c (ffffffff8194367b)
Location: include/net/netlink.h:1189
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81955424)
Location: include/net/netlink.h:1189
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8196434a)
Location: include/net/netlink.h:1189
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8196b53e)
Location: include/net/netlink.h:1189
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/fib_rules.c (ffffffff8196e461)
Location: include/net/netlink.h:1189
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff81971848)
Location: include/net/netlink.h:1189
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f1b87)
Location: include/net/netlink.h:1189
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f2686)
Location: include/net/netlink.h:1189
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
In net/ipv4/route.c (ffffffff819710db)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a7c3b)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff819b9daf)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff819c9fd0)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819d21fe)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/fib_rules.c (ffffffff819d7c11)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff819dafb4)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a608d4)
Location: include/net/netlink.h:1447
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a619bf)
Location: include/net/netlink.h:1447
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
In net/ipv4/route.c (ffffffff819a7add)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff819deccb)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff819f093f)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81a00b90)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a08d6e)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/fib_rules.c (ffffffff81a0e701)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff81a11e94)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a97504)
Location: include/net/netlink.h:1447
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a98593)
Location: include/net/netlink.h:1447
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
In net/ipv4/route.c (ffffffff81a91251)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acbced)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81ade96c)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81aefcca)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af9bee)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/fib_rules.c (ffffffff81aff5f1)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff81b020a8)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b93426)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b93cbf)
Location: include/net/netlink.h:1499
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb30ce)
Location: include/net/netlink.h:1499
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
In net/ipv4/route.c (ffffffff81a9b0ab)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad7cad)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81aeb764)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81afcc0a)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b0733e)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/fib_rules.c (ffffffff81b0d661)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff81b10421)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81ba3076)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba38fc)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc755f)
Location: include/net/netlink.h:1512
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
In net/ipv4/route.c (ffffffff81a864cb)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac2e29)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81ad6dcc)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae84d9)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af2aee)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/fib_rules.c (ffffffff81afb431)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff81afe030)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b92196)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b92a1c)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/mptcp/pm_netlink.c (ffffffff81bbb851)
Location: include/net/netlink.h:1512
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
In net/ipv4/route.c (ffffffff81b40c0b)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b809e6)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81b9580c)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba845e)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb2ffe)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/fib_rules.c (ffffffff81bbc871)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff81bbf2c0)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81c5e936)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81c5f1bc)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/mptcp/pm_netlink.c (ffffffff81c8b491)
Location: include/net/netlink.h:1512
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
In net/ipv4/route.c (ffffffff81ccd6e8)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d10de2)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81d274b3)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3ae5d)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d46804)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/fib_rules.c (ffffffff81d50e41)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff81d54050)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81e00b66)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e0158c)
Location: include/net/netlink.h:1512
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/mptcp/pm_netlink.c (ffffffff81e32a90)
Location: include/net/netlink.h:1512
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
In net/ipv4/route.c (ffffffff81e8d835)
Location: include/net/netlink.h:1561
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed6b62)
Location: include/net/netlink.h:1561
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81eeee30)
Location: include/net/netlink.h:1561
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81f037cd)
Location: include/net/netlink.h:1561
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0fc14)
Location: include/net/netlink.h:1561
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/fib_rules.c (ffffffff81f1ac51)
Location: include/net/netlink.h:1561
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff81f1e220)
Location: include/net/netlink.h:1561
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81fd59b6)
Location: include/net/netlink.h:1561
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd63ec)
Location: include/net/netlink.h:1561
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/mptcp/pm_netlink.c (ffffffff8200b029)
Location: include/net/netlink.h:1561
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
In net/ipv4/route.c (ffffffff81eebf5b)
Location: include/net/netlink.h:1562
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f35b0a)
Location: include/net/netlink.h:1562
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81f4e7f0)
Location: include/net/netlink.h:1562
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81f631ad)
Location: include/net/netlink.h:1562
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6f904)
Location: include/net/netlink.h:1562
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/fib_rules.c (ffffffff81f7a8d1)
Location: include/net/netlink.h:1562
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff81f7dd10)
Location: include/net/netlink.h:1562
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff820515ba)
Location: include/net/netlink.h:1562
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff820520ac)
Location: include/net/netlink.h:1562
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/mptcp/pm_netlink.c (ffffffff8208745b)
Location: include/net/netlink.h:1562
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
In net/ipv4/route.c (ffffffff81faffab)
Location: include/net/netlink.h:1638
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffbbba)
Location: include/net/netlink.h:1638
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff82014933)
Location: include/net/netlink.h:1638
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8202977d)
Location: include/net/netlink.h:1638
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82036034)
Location: include/net/netlink.h:1638
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/fib_rules.c (ffffffff82040fd1)
Location: include/net/netlink.h:1638
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff82044550)
Location: include/net/netlink.h:1638
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff82123d8a)
Location: include/net/netlink.h:1638
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82124888)
Location: include/net/netlink.h:1638
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/mptcp/pm_netlink.c (ffffffff8215cc7d)
Location: include/net/netlink.h:1638
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
In net/ipv4/route.c (ffff800010c5739c)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffff800010c91e58)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffff800010ca6b8c)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffff800010cb9148)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffff800010cc20c0)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/fib_rules.c (ffff800010cc83f8)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffff800010cca8a8)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/netlabel/netlabel_mgmt.c (ffff800010d669cc)
Location: include/net/netlink.h:1447
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d67d40)
Location: include/net/netlink.h:1447
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
In net/ipv4/route.c (c0d67028)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (c0da0b28)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (c0db328c)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (c0dc48fc)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (c0dcd760)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/fib_rules.c (c0dd38a4)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (c0dd64a0)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/netlabel/netlabel_mgmt.c (c0e65048)
Location: include/net/netlink.h:1447
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (c0e664b0)
Location: include/net/netlink.h:1447
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
In net/ipv4/route.c (c000000000d5893c)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (c000000000da2530)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (c000000000dbb18c)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (c000000000dd1df0)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (c000000000ddd690)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/fib_rules.c (c000000000de5650)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (c000000000de9a88)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/netlabel/netlabel_mgmt.c (c000000000ea2c64)
Location: include/net/netlink.h:1447
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (c000000000ea4660)
Location: include/net/netlink.h:1447
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
In net/ipv4/route.c (ffffffe0007c16e6)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f1eae)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffe000801ed8)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffe00080ff12)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe0008175be)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/fib_rules.c (ffffffe00081c78c)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffe00081f892)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/netlabel/netlabel_mgmt.c (ffffffe00089a380)
Location: include/net/netlink.h:1447
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089b206)
Location: include/net/netlink.h:1447
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
In net/ipv4/route.c (ffffffff8194794d)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197eb3b)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff819906df)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff819a0930)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819a8b0e)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/fib_rules.c (ffffffff819ae4a1)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff819b17b4)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a36894)
Location: include/net/netlink.h:1447
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a37923)
Location: include/net/netlink.h:1447
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
In drivers/net/vxlan.c (ffffffff8176d818)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_fill_info
  - drivers/net/vxlan.c:vxlan_fill_info
  - drivers/net/vxlan.c:vxlan_fdb_info
```
```
In net/ipv4/route.c (ffffffff8190143d)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff819385fb)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff8194a19f)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8195a3f0)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819625ce)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/fib_rules.c (ffffffff8196aad1)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff8196dde4)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f34b4)
Location: include/net/netlink.h:1447
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f4543)
Location: include/net/netlink.h:1447
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
In net/netfilter/nf_conntrack_netlink.c (ffffffff819acd29)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_tuples_ip
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_tuples_ip
```
```
In net/ipv4/route.c (ffffffff819b211d)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e930b)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff819faf7f)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0b1d0)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a133ae)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/fib_rules.c (ffffffff81a18d41)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff81a1c054)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aa2744)
Location: include/net/netlink.h:1447
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aa37d3)
Location: include/net/netlink.h:1447
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
In net/ipv4/route.c (ffffffff819bb7dd)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f306b)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81a052d2)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81a159b0)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1dd7e)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/fib_rules.c (ffffffff81a237c1)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff81a26fa4)
Location: include/net/netlink.h:1447
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aaeab4)
Location: include/net/netlink.h:1447
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aafbf3)
Location: include/net/netlink.h:1447
Inline: True
```
</details>
</li>
</ul>

## Differences
