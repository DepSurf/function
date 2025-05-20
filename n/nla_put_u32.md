# Function: <code>nla_put_u32</code>

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
In fs/quota/netlink.c (ffffffff81276749)
Location: include/net/netlink.h:801
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In net/core/neighbour.c (ffffffff817260e7)
Location: include/net/netlink.h:801
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neigh_fill_info
```
```
In net/core/rtnetlink.c (ffffffff8172d036)
Location: include/net/netlink.h:801
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/fib_rules.c (ffffffff81739d88)
Location: include/net/netlink.h:801
Inline: True
```
```
In net/sched/act_api.c (ffffffff8174851a)
Location: include/net/netlink.h:801
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff8174fc8c)
Location: include/net/netlink.h:801
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:genl_ctrl_event
```
```
In net/ipv4/route.c (ffffffff81753be2)
Location: include/net/netlink.h:801
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff8178128b)
Location: include/net/netlink.h:801
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81790aa4)
Location: include/net/netlink.h:801
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8179d900)
Location: include/net/netlink.h:801
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/fib_rules.c (ffffffff817a692d)
Location: include/net/netlink.h:801
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff817a8539)
Location: include/net/netlink.h:801
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff817cacc1)
Location: include/net/netlink.h:801
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff817d2588)
Location: include/net/netlink.h:801
Inline: True
```
```
In net/ipv6/route.c (ffffffff817d867c)
Location: include/net/netlink.h:801
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff817f9083)
Location: include/net/netlink.h:801
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8180d434)
Location: include/net/netlink.h:801
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8180fd45)
Location: include/net/netlink.h:801
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff818156e6)
Location: include/net/netlink.h:801
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
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
In fs/quota/netlink.c (ffffffff812a2f89)
Location: include/net/netlink.h:812
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In net/core/neighbour.c (ffffffff817907b8)
Location: include/net/netlink.h:812
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff817990d7)
Location: include/net/netlink.h:812
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/fib_rules.c (ffffffff817a6068)
Location: include/net/netlink.h:812
Inline: True
```
```
In net/sched/act_api.c (ffffffff817b5606)
Location: include/net/netlink.h:812
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff817bc42c)
Location: include/net/netlink.h:812
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff817bfcb2)
Location: include/net/netlink.h:812
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff817ee7d3)
Location: include/net/netlink.h:812
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff817fddd4)
Location: include/net/netlink.h:812
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8180b7ba)
Location: include/net/netlink.h:812
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/fib_rules.c (ffffffff8181461d)
Location: include/net/netlink.h:812
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff81815e7e)
Location: include/net/netlink.h:812
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81838831)
Location: include/net/netlink.h:812
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff81840048)
Location: include/net/netlink.h:812
Inline: True
```
```
In net/ipv6/route.c (ffffffff8184204d)
Location: include/net/netlink.h:812
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81868ade)
Location: include/net/netlink.h:812
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8187f825)
Location: include/net/netlink.h:812
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81882416)
Location: include/net/netlink.h:812
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81883416)
Location: include/net/netlink.h:812
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81888596)
Location: include/net/netlink.h:812
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
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
In fs/quota/netlink.c (ffffffff812b8969)
Location: include/net/netlink.h:812
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In net/core/neighbour.c (ffffffff817be068)
Location: include/net/netlink.h:812
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff817c6e87)
Location: include/net/netlink.h:812
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/fib_rules.c (ffffffff817d4b48)
Location: include/net/netlink.h:812
Inline: True
```
```
In net/sched/act_api.c (ffffffff817e5006)
Location: include/net/netlink.h:812
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff817ebd3c)
Location: include/net/netlink.h:812
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff817f2d9a)
Location: include/net/netlink.h:812
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181f1e3)
Location: include/net/netlink.h:812
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff8182ed34)
Location: include/net/netlink.h:812
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8183c8df)
Location: include/net/netlink.h:812
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/fib_rules.c (ffffffff81845d7d)
Location: include/net/netlink.h:812
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff8184762e)
Location: include/net/netlink.h:812
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff8186a361)
Location: include/net/netlink.h:812
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff81871cc8)
Location: include/net/netlink.h:812
Inline: True
```
```
In net/ipv6/route.c (ffffffff81873d9d)
Location: include/net/netlink.h:812
Inline: True
```
```
In net/ipv6/seg6.c (ffffffff81899897)
Location: include/net/netlink.h:812
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff8189b92e)
Location: include/net/netlink.h:812
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818b40d5)
Location: include/net/netlink.h:812
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818b6cc6)
Location: include/net/netlink.h:812
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818b7cb6)
Location: include/net/netlink.h:812
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff818bcdb6)
Location: include/net/netlink.h:812
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
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
In fs/quota/netlink.c (ffffffff812c5d39)
Location: include/net/netlink.h:824
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In net/core/neighbour.c (ffffffff817dcad1)
Location: include/net/netlink.h:824
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff817e5796)
Location: include/net/netlink.h:824
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/fib_rules.c (ffffffff817f3f1a)
Location: include/net/netlink.h:824
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81802204)
Location: include/net/netlink.h:824
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81804b70)
Location: include/net/netlink.h:824
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8180a595)
Location: include/net/netlink.h:824
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff8180bc93)
Location: include/net/netlink.h:824
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff81813780)
Location: include/net/netlink.h:824
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_metrics.c (ffffffff8183fda9)
Location: include/net/netlink.h:824
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81850200)
Location: include/net/netlink.h:824
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8185e045)
Location: include/net/netlink.h:824
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/fib_rules.c (ffffffff818678dd)
Location: include/net/netlink.h:824
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff8186a9e3)
Location: include/net/netlink.h:824
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:__ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff8188e8e3)
Location: include/net/netlink.h:824
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff81896a48)
Location: include/net/netlink.h:824
Inline: True
```
```
In net/ipv6/route.c (ffffffff81898bed)
Location: include/net/netlink.h:824
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_nexthop_info
```
```
In net/ipv6/seg6.c (ffffffff818bfa9f)
Location: include/net/netlink.h:824
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff818c1cf3)
Location: include/net/netlink.h:824
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:__ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818daa85)
Location: include/net/netlink.h:824
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818dd5a6)
Location: include/net/netlink.h:824
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818de5a6)
Location: include/net/netlink.h:824
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff818e37d5)
Location: include/net/netlink.h:824
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
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
In fs/quota/netlink.c (ffffffff812e9be9)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In net/core/neighbour.c (ffffffff818576a1)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81860830)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/fib_rules.c (ffffffff8186f67a)
Location: include/net/netlink.h:841
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81880460)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff8188391f)
Location: include/net/netlink.h:841
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818894b5)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff8188ac23)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff81892dda)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp.c (ffffffff818a6e45)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bf150)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff818cfe2d)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff818ddf50)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/fib_rules.c (ffffffff818e7a3d)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff818eb16b)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:__ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff8190ff2b)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff81917eb3)
Location: include/net/netlink.h:841
Inline: True
```
```
In net/ipv6/route.c (ffffffff81919eed)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_nexthop_info
```
```
In net/ipv6/seg6.c (ffffffff81942b6b)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff81945633)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:__ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_local.c (ffffffff8194ec96)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_fill_encap
  - net/ipv6/seg6_local.c:put_nla_oif
  - net/ipv6/seg6_local.c:put_nla_iif
  - net/ipv6/seg6_local.c:put_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81960665)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8196318e)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff8196419e)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff819695db)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
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
In fs/quota/netlink.c (ffffffff81316ae6)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/net/tun.c (ffffffff8173bdff)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/neighbour.c (ffffffff818a286f)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff818aa6e4)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/fib_rules.c (ffffffff818c0de1)
Location: include/net/netlink.h:841
Inline: True
```
```
In net/sched/sch_api.c (ffffffff818cfec5)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff818d31bf)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff818d7391)
Location: include/net/netlink.h:841
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818dcf71)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff818de252)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff818e6ee7)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp.c (ffffffff818fbf45)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_metrics.c (ffffffff81914d42)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81926302)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81934a73)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/fib_rules.c (ffffffff8193e59d)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff8194194e)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (ffffffff81944432)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff8196733b)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff8196f573)
Location: include/net/netlink.h:841
Inline: True
```
```
In net/ipv6/route.c (ffffffff8197200e)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_nexthop_info
```
```
In net/ipv6/seg6.c (ffffffff8199ba9d)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff8199d141)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_local.c (ffffffff819a7ff8)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_fill_encap
  - net/ipv6/seg6_local.c:put_nla_oif
  - net/ipv6/seg6_local.c:put_nla_iif
  - net/ipv6/seg6_local.c:put_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819b9e25)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819bc9e5)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819bda45)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff819c2df0)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff819cabb4)
Location: include/net/netlink.h:841
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In fs/quota/netlink.c (ffffffff8132da96)
Location: include/net/netlink.h:984
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/net/tun.c (ffffffff8175f73f)
Location: include/net/netlink.h:984
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/neighbour.c (ffffffff818c5a49)
Location: include/net/netlink.h:984
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff818d0581)
Location: include/net/netlink.h:984
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/fib_rules.c (ffffffff818e9bee)
Location: include/net/netlink.h:984
Inline: True
```
```
In net/sched/sch_api.c (ffffffff818fb12b)
Location: include/net/netlink.h:984
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff818feb1f)
Location: include/net/netlink.h:984
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81903764)
Location: include/net/netlink.h:984
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8190993e)
Location: include/net/netlink.h:984
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff8190ac12)
Location: include/net/netlink.h:984
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff81913dbc)
Location: include/net/netlink.h:984
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp.c (ffffffff81929eb7)
Location: include/net/netlink.h:984
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_metrics.c (ffffffff819434f2)
Location: include/net/netlink.h:984
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81955346)
Location: include/net/netlink.h:984
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff819643c0)
Location: include/net/netlink.h:984
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/fib_rules.c (ffffffff8196e43d)
Location: include/net/netlink.h:984
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff819711fd)
Location: include/net/netlink.h:984
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (ffffffff819746d2)
Location: include/net/netlink.h:984
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff8199c948)
Location: include/net/netlink.h:984
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff819a5100)
Location: include/net/netlink.h:984
Inline: True
```
```
In net/ipv6/route.c (ffffffff819a7766)
Location: include/net/netlink.h:984
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_nexthop_info
```
```
In net/ipv6/seg6.c (ffffffff819d266d)
Location: include/net/netlink.h:984
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff819d3c9e)
Location: include/net/netlink.h:984
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_local.c (ffffffff819deb58)
Location: include/net/netlink.h:984
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_fill_encap
  - net/ipv6/seg6_local.c:put_nla_oif
  - net/ipv6/seg6_local.c:put_nla_iif
  - net/ipv6/seg6_local.c:put_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f10f5)
Location: include/net/netlink.h:984
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f3c35)
Location: include/net/netlink.h:984
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f4be5)
Location: include/net/netlink.h:984
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff819fa350)
Location: include/net/netlink.h:984
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a04100)
Location: include/net/netlink.h:984
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In fs/quota/netlink.c (ffffffff813557d5)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/net/tun.c (ffffffff8179cf6f)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/neighbour.c (ffffffff81911a6b)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff8191d41b)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vf
```
```
In net/core/fib_rules.c (ffffffff8193963b)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/core/devlink.c (ffffffff8194ee5a)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_api.c (ffffffff8195ab3e)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff8195e51c)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81964905)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8196ab35)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff8196c002)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff81971093)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp.c (ffffffff8198d0cc)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a7ac3)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff819b9cd1)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff819c9e89)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/nexthop.c (ffffffff819d37ad)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/fib_rules.c (ffffffff819d7bed)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff819da985)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (ffffffff819de212)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81a08b22)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff81a115a0)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a13dbb)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81a4145a)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff81a41f1a)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_local.c (ffffffff81a4d6c8)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_fill_encap
  - net/ipv6/seg6_local.c:put_nla_oif
  - net/ipv6/seg6_local.c:put_nla_iif
  - net/ipv6/seg6_local.c:put_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a603b1)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a63085)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a64095)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81a698b0)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a733a0)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In fs/quota/netlink.c (ffffffff8136db15)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/net/tun.c (ffffffff817c0a0f)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/neighbour.c (ffffffff819440db)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff8194fa63)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vf
```
```
In net/core/fib_rules.c (ffffffff8196c508)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff8197570e)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (ffffffff81985bca)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_api.c (ffffffff81990fee)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81994dec)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff8199b465)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819a16df)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff819a29b2)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff819a7a92)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp.c (ffffffff819c3a6c)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_metrics.c (ffffffff819deb53)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff819f0861)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81a00a49)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/nexthop.c (ffffffff81a0a31d)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/fib_rules.c (ffffffff81a0e6dd)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff81a1186a)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (ffffffff81a152b2)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81a3f232)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff81a481c0)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a4a9ab)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81a780da)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff81a78b7a)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_local.c (ffffffff81a84298)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_fill_encap
  - net/ipv6/seg6_local.c:put_nla_oif
  - net/ipv6/seg6_local.c:put_nla_iif
  - net/ipv6/seg6_local.c:put_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a96fe1)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a99c46)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a9ac26)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81aa01ee)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81aa9b90)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In fs/quota/netlink.c (ffffffff813b5645)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/net/tun.c (ffffffff8188a1ef)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/neighbour.c (ffffffff81a1414d)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81a21281)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_vf_ports_fill
```
```
In net/core/fib_rules.c (ffffffff81a403b3)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81a4a9b4)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_entries_put
```
```
In net/core/devlink.c (ffffffff81a5f690)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_dpipe_header_put
  - net/core/devlink.c:devlink_dpipe_fields_put
  - net/core/devlink.c:devlink_dpipe_fields_put
  - net/core/devlink.c:devlink_dpipe_fields_put
  - net/core/devlink.c:devlink_dpipe_value_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
```
```
In net/core/bpf_sk_storage.c (ffffffff81a6129e)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81a68ffe)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a6db1c)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81a73365)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_del_walker
```
```
In net/netlink/af_netlink.c (ffffffff81a7b0a2)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81a7c9ce)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netlink/policy.c (ffffffff81a7da2e)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
```
```
In net/ethtool/netlink.c (ffffffff81a859ae)
Location: include/net/netlink.h:1294
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81a874f7)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81a8808f)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/linkmodes.c (ffffffff81a88b14)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
```
```
In net/ethtool/linkstate.c (ffffffff81a892a6)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/ethtool/linkstate.c:linkstate_fill_reply
  - net/ethtool/linkstate.c:linkstate_fill_reply
```
```
In net/ethtool/rings.c (ffffffff81a8a8a5)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
```
```
In net/ethtool/channels.c (ffffffff81a8adf5)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
```
```
In net/ethtool/coalesce.c (ffffffff81a8b558)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
```
```
In net/ethtool/eee.c (ffffffff81a8c3e1)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/ethtool/eee.c:eee_fill_reply
```
```
In net/ethtool/tsinfo.c (ffffffff81a8c933)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/ethtool/tsinfo.c:tsinfo_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81a8d1bc)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
```
```
In net/ipv4/route.c (ffffffff81a91206)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp.c (ffffffff81aaf1ee)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acbb73)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81ade7d1)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81aefbd4)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_multipath
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af9ad8)
Location: include/net/netlink.h:1294
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81afaf9b)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/fib_rules.c (ffffffff81aff5cd)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff81b02f70)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv4/ipmr_base.c (ffffffff81b062a2)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81b34eb2)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff81b3f060)
Location: include/net/netlink.h:1294
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b44f0b)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/ipv6/seg6.c:__seg6_hmac_fill_info
```
```
In net/ipv6/ip6mr.c (ffffffff81b74548)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/ipv6/seg6_local.c (ffffffff81b7f2f8)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_fill_encap
  - net/ipv6/seg6_local.c:put_nla_oif
  - net/ipv6/seg6_local.c:put_nla_iif
  - net/ipv6/seg6_local.c:put_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b92861)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b95496)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b963f6)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81b9bd21)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba5d90)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff81bb2ade)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb364a)
Location: include/net/netlink.h:1294
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
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
In fs/quota/netlink.c (ffffffff813c6e75)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/net/tun.c (ffffffff818982ef)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In drivers/thermal/thermal_netlink.c (ffffffff8195f0ee)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:__thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_gov
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:__thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_gov_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_state_update
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_state_update
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_delete
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_up
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_up
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_create
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/neighbour.c (ffffffff81a143f5)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81a1f80e)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_vf_ports_fill
```
```
In net/core/fib_rules.c (ffffffff81a430b3)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81a505f4)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_entries_put
```
```
In net/core/devlink.c (ffffffff81a67e80)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_dpipe_header_put
  - net/core/devlink.c:devlink_dpipe_fields_put
  - net/core/devlink.c:devlink_dpipe_fields_put
  - net/core/devlink.c:devlink_dpipe_fields_put
  - net/core/devlink.c:devlink_dpipe_value_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/core/bpf_sk_storage.c (ffffffff81a69b8e)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81a71733)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a740e3)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_qevent_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81a7bf43)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:tcf_action_dump_terse
```
```
In net/netlink/af_netlink.c (ffffffff81a83f38)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81a8589d)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netlink/policy.c (ffffffff81a87133)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81a8f326)
Location: include/net/netlink.h:1307
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81a90e77)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81a91a3f)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/linkmodes.c (ffffffff81a923f4)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
```
```
In net/ethtool/linkstate.c (ffffffff81a92b94)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/linkstate.c:linkstate_fill_reply
  - net/ethtool/linkstate.c:linkstate_fill_reply
```
```
In net/ethtool/rings.c (ffffffff81a940b5)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
```
```
In net/ethtool/channels.c (ffffffff81a94585)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
```
```
In net/ethtool/coalesce.c (ffffffff81a94c28)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
```
```
In net/ethtool/eee.c (ffffffff81a95b71)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/eee.c:eee_fill_reply
```
```
In net/ethtool/tsinfo.c (ffffffff81a96043)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/tsinfo.c:tsinfo_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81a968fc)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
```
```
In net/ethtool/tunnels.c (ffffffff81a97315)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ipv4/route.c (ffffffff81a9b063)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp.c (ffffffff81aba2a3)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad7b33)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81aeb5b1)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81afcb14)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_multipath
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b07228)
Location: include/net/netlink.h:1307
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81b0866b)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/fib_rules.c (ffffffff81b0d63d)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff81b100c0)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv4/ipmr_base.c (ffffffff81b14492)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81b43ad7)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff81b4dae0)
Location: include/net/netlink.h:1307
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b5388b)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv6/seg6.c:__seg6_hmac_fill_info
```
```
In net/ipv6/ip6mr.c (ffffffff81b832b8)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/ipv6/seg6_local.c (ffffffff81b8e2e8)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_fill_encap
  - net/ipv6/seg6_local.c:put_nla_oif
  - net/ipv6/seg6_local.c:put_nla_iif
  - net/ipv6/seg6_local.c:put_nla_vrftable
  - net/ipv6/seg6_local.c:put_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81ba24b1)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ba5106)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ba6066)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81baba31)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81bb5270)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff81bc6f0e)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc7d2f)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
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
In fs/quota/netlink.c (ffffffff813cdf05)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/net/tun.c (ffffffff8187abbf)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In drivers/thermal/thermal_netlink.c (ffffffff8194264e)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:__thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_gov
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:__thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_gov_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_state_update
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_state_update
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_delete
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_up
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_up
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_create
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/neighbour.c (ffffffff819fad85)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81a068da)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vf
```
```
In net/core/fib_rules.c (ffffffff81a27e13)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81a34eec)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/devlink.c (ffffffff81a42ecc)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_dpipe_value_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/core/bpf_sk_storage.c (ffffffff81a525fe)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81a5a0f3)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a5cc33)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_qevent_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81a64b73)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:tcf_action_dump_terse
```
```
In net/netlink/af_netlink.c (ffffffff81a6d06b)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81a6f23d)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netlink/policy.c (ffffffff81a7020a)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81a78a26)
Location: include/net/netlink.h:1307
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81a7a679)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81a7b477)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/linkmodes.c (ffffffff81a7bc28)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
```
```
In net/ethtool/linkstate.c (ffffffff81a7c5a4)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/linkstate.c:linkstate_fill_reply
  - net/ethtool/linkstate.c:linkstate_fill_reply
```
```
In net/ethtool/rings.c (ffffffff81a7dac5)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
```
```
In net/ethtool/channels.c (ffffffff81a7df95)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
```
```
In net/ethtool/coalesce.c (ffffffff81a7e688)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
```
```
In net/ethtool/eee.c (ffffffff81a7f601)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/eee.c:eee_fill_reply
```
```
In net/ethtool/tsinfo.c (ffffffff81a7fac3)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/tsinfo.c:tsinfo_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81a803cc)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
```
```
In net/ethtool/tunnels.c (ffffffff81a80c80)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81a8150d)
Location: include/net/netlink.h:1307
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81a82191)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_stats
```
```
In net/ipv4/route.c (ffffffff81a86483)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp.c (ffffffff81aa5528)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac2cd3)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81ad6c21)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae8536)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af2807)
Location: include/net/netlink.h:1307
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81af6fb7)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/fib_rules.c (ffffffff81afb40d)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff81b0099a)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv4/ipmr_base.c (ffffffff81b02292)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81b31737)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff81b3b570)
Location: include/net/netlink.h:1307
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b40e4f)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81b6fa0a)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff81b71f3b)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/ipv6/seg6_local.c (ffffffff81b7d228)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_fill_encap
  - net/ipv6/seg6_local.c:put_nla_oif
  - net/ipv6/seg6_local.c:put_nla_iif
  - net/ipv6/seg6_local.c:put_nla_vrftable
  - net/ipv6/seg6_local.c:put_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b91591)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b94245)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b951d5)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81b9abd1)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba4270)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff81bb7c3e)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81bbba68)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
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
In fs/quota/netlink.c (ffffffff8141f235)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/net/tun.c (ffffffff8190c0bf)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In drivers/net/wwan/wwan_core.c (ffffffff8191a9f7)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_fill_info
```
```
In drivers/thermal/thermal_netlink.c (ffffffff819e6f8e)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:__thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_gov
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:__thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_gov_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_state_update
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_state_update
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_delete
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_up
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_up
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_create
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/neighbour.c (ffffffff81aac9c5)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81ab8d28)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vf
```
```
In net/core/fib_rules.c (ffffffff81adcbb3)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81aeaabc)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/devlink.c (ffffffff81af933c)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_dpipe_value_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/core/bpf_sk_storage.c (ffffffff81b0b06e)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81b131c6)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81b15de3)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_qevent_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81b1de43)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:tcf_action_dump_terse
```
```
In net/netlink/af_netlink.c (ffffffff81b266e4)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81b27fdd)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netlink/policy.c (ffffffff81b2995a)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81b32bf6)
Location: include/net/netlink.h:1307
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81b34a89)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81b3589b)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/linkmodes.c (ffffffff81b35f99)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
```
```
In net/ethtool/linkstate.c (ffffffff81b368fa)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/linkstate.c:linkstate_fill_reply
  - net/ethtool/linkstate.c:linkstate_fill_reply
```
```
In net/ethtool/rings.c (ffffffff81b37c95)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
```
```
In net/ethtool/channels.c (ffffffff81b38115)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
```
```
In net/ethtool/coalesce.c (ffffffff81b38785)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:coalesce_put_u32
```
```
In net/ethtool/eee.c (ffffffff81b39511)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/eee.c:eee_fill_reply
```
```
In net/ethtool/tsinfo.c (ffffffff81b398d3)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/tsinfo.c:tsinfo_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81b3a19c)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
```
```
In net/ethtool/tunnels.c (ffffffff81b3a9c0)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81b3b28d)
Location: include/net/netlink.h:1307
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81b3bd51)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_stats
```
```
In net/ethtool/phc_vclocks.c (ffffffff81b3c837)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/phc_vclocks.c:phc_vclocks_fill_reply
```
```
In net/ipv4/route.c (ffffffff81b40bc3)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp.c (ffffffff81b61878)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b80884)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81b95661)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba828a)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb2d17)
Location: include/net/netlink.h:1307
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81bb6949)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/fib_rules.c (ffffffff81bbc84d)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff81bbef25)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv4/ipmr_base.c (ffffffff81bc4146)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81bf77d7)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff81c01d90)
Location: include/net/netlink.h:1307
Inline: True
```
```
In net/ipv6/route.c (ffffffff81c08b1f)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81c37b5a)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ioam6.c (ffffffff81c3937b)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/ipv6/ip6mr.c (ffffffff81c3c3eb)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/ipv6/seg6_local.c (ffffffff81c483c8)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_fill_encap
  - net/ipv6/seg6_local.c:put_nla_oif
  - net/ipv6/seg6_local.c:put_nla_iif
  - net/ipv6/seg6_local.c:put_nla_vrftable
  - net/ipv6/seg6_local.c:put_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81c5dd31)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81c609e5)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81c61a05)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81c667da)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81c71e00)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff81c8718e)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81c8b6a8)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
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
In fs/quota/netlink.c (ffffffff81497076)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/net/tun.c (ffffffff81a5fabe)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81a6fe4a)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_fill_info
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81b4c5be)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:__thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_gov
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:__thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_gov_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_state_update
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_state_update
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_delete
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_delete
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_delete
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_up
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_up
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_up
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_create
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/neighbour.c (ffffffff81c25959)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81c31f85)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/fib_rules.c (ffffffff81c5e135)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81c6d2c0)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/devlink.c (ffffffff81c7c23d)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_dpipe_value_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/core/bpf_sk_storage.c (ffffffff81c9173f)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81c99df9)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81c9d3c3)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_qevent_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81ca6d2e)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_terse
```
```
In net/netlink/af_netlink.c (ffffffff81caf355)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81cb0f9f)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netlink/policy.c (ffffffff81cb2b45)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81cbe7a0)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_fill_reply_header
```
```
In net/ethtool/bitset.c (ffffffff81cc0033)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81cc1260)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/linkmodes.c (ffffffff81cc1889)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
```
```
In net/ethtool/linkstate.c (ffffffff81cc2256)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/linkstate.c:linkstate_fill_reply
  - net/ethtool/linkstate.c:linkstate_fill_reply
```
```
In net/ethtool/rings.c (ffffffff81cc37ca)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
```
```
In net/ethtool/channels.c (ffffffff81cc3e85)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
```
```
In net/ethtool/coalesce.c (ffffffff81cc4575)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:coalesce_put_u32
```
```
In net/ethtool/eee.c (ffffffff81cc5321)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/eee.c:eee_fill_reply
```
```
In net/ethtool/tsinfo.c (ffffffff81cc5725)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/tsinfo.c:tsinfo_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81cc6090)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
```
```
In net/ethtool/tunnels.c (ffffffff81cc6932)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81cc71be)
Location: include/net/netlink.h:1307
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81cc7fa2)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stats_put_rmon_hist
```
```
In net/ethtool/phc_vclocks.c (ffffffff81cc8867)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ethtool/phc_vclocks.c:phc_vclocks_fill_reply
```
```
In net/ipv4/route.c (ffffffff81ccd698)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp.c (ffffffff81cf02b3)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d10c54)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81d27390)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3ae1a)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d46690)
Location: include/net/netlink.h:1307
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81d4a527)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/fib_rules.c (ffffffff81d50e1d)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff81d53c91)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv4/ipmr_base.c (ffffffff81d58fdd)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81d90c80)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff81d9bcfb)
Location: include/net/netlink.h:1307
Inline: True
```
```
In net/ipv6/route.c (ffffffff81da360d)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81dd571c)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ioam6.c (ffffffff81dd6c29)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/ipv6/ip6mr.c (ffffffff81dda7af)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/ipv6/seg6_local.c (ffffffff81de78e8)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_fill_encap
  - net/ipv6/seg6_local.c:put_nla_oif
  - net/ipv6/seg6_local.c:put_nla_iif
  - net/ipv6/seg6_local.c:put_nla_vrftable
  - net/ipv6/seg6_local.c:put_nla_table
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81deb698)
Location: include/net/netlink.h:1307
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81dffff5)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81e02ed9)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81e03ff9)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81e096c2)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81e15988)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff81e2d9c3)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81e32c52)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
```
```
In net/mctp/device.c (ffffffff81e37dc6)
Location: include/net/netlink.h:1307
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_fill_link_af
```
```
In net/mctp/route.c (ffffffff81e392eb)
Location: include/net/netlink.h:1307
Inline: True
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
In fs/quota/netlink.c (ffffffff8152b086)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/net/tun.c (ffffffff81beafae)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c02cda)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_fill_info
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81ce421e)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:__thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_gov
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:__thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_gov_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_state_update
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_state_update
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_delete
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_delete
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_delete
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_up
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_up
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_up
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_create
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/neighbour.c (ffffffff81dd7b99)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81de5355)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/fib_rules.c (ffffffff81e14955)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81e24ec0)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/devlink.c (ffffffff81e40b0d)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_dpipe_value_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_nl_port_handle_fill
```
```
In net/core/bpf_sk_storage.c (ffffffff81e4ccdf)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81e56176)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81e598c3)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_qevent_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81e6326e)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_terse
```
```
In net/netlink/af_netlink.c (ffffffff81e68fb6)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack_tlv_fill
  - net/netlink/af_netlink.c:netlink_ack_tlv_fill
  - net/netlink/af_netlink.c:netlink_ack_tlv_fill
```
```
In net/netlink/genetlink.c (ffffffff81e6ef24)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netlink/policy.c (ffffffff81e70b95)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81e7d290)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_fill_reply_header
```
```
In net/ethtool/bitset.c (ffffffff81e7ec43)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81e7ffa0)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/linkmodes.c (ffffffff81e80619)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
```
```
In net/ethtool/rss.c (ffffffff81e8103a)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/ethtool/rss.c:rss_fill_reply
```
```
In net/ethtool/linkstate.c (ffffffff81e81355)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/ethtool/linkstate.c:linkstate_fill_reply
  - net/ethtool/linkstate.c:linkstate_fill_reply
  - net/ethtool/linkstate.c:linkstate_fill_reply
```
```
In net/ethtool/rings.c (ffffffff81e82b4a)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
```
```
In net/ethtool/channels.c (ffffffff81e83245)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
```
```
In net/ethtool/coalesce.c (ffffffff81e83a25)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:coalesce_put_u32
```
```
In net/ethtool/eee.c (ffffffff81e84841)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/ethtool/eee.c:eee_fill_reply
```
```
In net/ethtool/tsinfo.c (ffffffff81e84c85)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/ethtool/tsinfo.c:tsinfo_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81e85680)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
```
```
In net/ethtool/tunnels.c (ffffffff81e85f82)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81e8683e)
Location: include/net/netlink.h:1356
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81e876c2)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stats_put_rmon_hist
```
```
In net/ethtool/phc_vclocks.c (ffffffff81e88027)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/ethtool/phc_vclocks.c:phc_vclocks_fill_reply
```
```
In net/ethtool/pse-pd.c (ffffffff81e884e7)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/ethtool/pse-pd.c:pse_fill_reply
  - net/ethtool/pse-pd.c:pse_fill_reply
```
```
In net/ipv4/route.c (ffffffff81e8d7e8)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp.c (ffffffff81eb35e3)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed69d4)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81eeecbb)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81f0378a)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0fa90)
Location: include/net/netlink.h:1356
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81f13bc7)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/fib_rules.c (ffffffff81f1ac2d)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff81f1de75)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv4/ipmr_base.c (ffffffff81f235de)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81f5f3a0)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff81f6a992)
Location: include/net/netlink.h:1356
Inline: True
```
```
In net/ipv6/route.c (ffffffff81f72a4d)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81fa6eac)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ioam6.c (ffffffff81fa85c9)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/ipv6/ip6mr.c (ffffffff81fac4cf)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/ipv6/seg6_local.c (ffffffff81fba8a8)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_fill_encap
  - net/ipv6/seg6_local.c:put_nla_flavors
  - net/ipv6/seg6_local.c:put_nla_oif
  - net/ipv6/seg6_local.c:put_nla_iif
  - net/ipv6/seg6_local.c:put_nla_vrftable
  - net/ipv6/seg6_local.c:put_nla_table
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbf2e8)
Location: include/net/netlink.h:1356
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81fd4e15)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81fd7e19)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81fd8fb9)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81fdeb02)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81fec928)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff82005f53)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff8200b6b2)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
```
```
In net/mctp/device.c (ffffffff82010fd6)
Location: include/net/netlink.h:1356
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_fill_link_af
```
```
In net/mctp/route.c (ffffffff820125ab)
Location: include/net/netlink.h:1356
Inline: True
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
In fs/quota/netlink.c (ffffffff81563416)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/net/tun.c (ffffffff81c433ee)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c6838a)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_fill_info
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81d4c84e)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:__thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_gov
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:__thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_gov_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_state_update
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_state_update
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_delete
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_delete
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_delete
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_up
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_up
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_up
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_create
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/neighbour.c (ffffffff81e489a9)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81e56d71)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_port_fill
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/netdev-genl.c (ffffffff81e7ce3f)
Location: include/net/netlink.h:1357
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81e8826a)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81e9a400)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/bpf_sk_storage.c (ffffffff81ea83ff)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81eb253d)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81eb5303)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_qevent_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81ebf2fe)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_terse
```
```
In net/netlink/af_netlink.c (ffffffff81ec4e26)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack_tlv_fill
  - net/netlink/af_netlink.c:netlink_ack_tlv_fill
  - net/netlink/af_netlink.c:netlink_ack_tlv_fill
```
```
In net/netlink/genetlink.c (ffffffff81ecb034)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netlink/policy.c (ffffffff81eccc87)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81ed9850)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_fill_reply_header
```
```
In net/ethtool/bitset.c (ffffffff81edb236)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81edc6db)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/linkmodes.c (ffffffff81edce09)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
```
```
In net/ethtool/rss.c (ffffffff81edd74a)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ethtool/rss.c:rss_fill_reply
```
```
In net/ethtool/linkstate.c (ffffffff81edda65)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ethtool/linkstate.c:linkstate_fill_reply
  - net/ethtool/linkstate.c:linkstate_fill_reply
  - net/ethtool/linkstate.c:linkstate_fill_reply
```
```
In net/ethtool/rings.c (ffffffff81edf36b)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
```
```
In net/ethtool/channels.c (ffffffff81edfa15)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
```
```
In net/ethtool/coalesce.c (ffffffff81ee07b5)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:coalesce_put_u32
```
```
In net/ethtool/pause.c (ffffffff81ee0fbe)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/eee.c (ffffffff81ee1221)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ethtool/eee.c:eee_fill_reply
```
```
In net/ethtool/tsinfo.c (ffffffff81ee15b5)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ethtool/tsinfo.c:tsinfo_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81ee1fac)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
```
```
In net/ethtool/tunnels.c (ffffffff81ee28d5)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81ee328e)
Location: include/net/netlink.h:1357
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81ee4312)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_fill_reply
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stats_put_rmon_hist
```
```
In net/ethtool/phc_vclocks.c (ffffffff81ee5107)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ethtool/phc_vclocks.c:phc_vclocks_fill_reply
```
```
In net/ethtool/mm.c (ffffffff81ee58f9)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
```
```
In net/ethtool/pse-pd.c (ffffffff81ee6097)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ethtool/pse-pd.c:pse_fill_reply
  - net/ethtool/pse-pd.c:pse_fill_reply
```
```
In net/ethtool/plca.c (ffffffff81ee62e6)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ethtool/plca.c:plca_get_cfg_fill_reply
  - net/ethtool/plca.c:plca_get_cfg_fill_reply
  - net/ethtool/plca.c:plca_get_cfg_fill_reply
  - net/ethtool/plca.c:plca_get_cfg_fill_reply
  - net/ethtool/plca.c:plca_get_cfg_fill_reply
```
```
In net/ipv4/route.c (ffffffff81eebf0a)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp.c (ffffffff81f11d03)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f35925)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81f4e67b)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81f6316a)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6f780)
Location: include/net/netlink.h:1357
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81f73897)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/fib_rules.c (ffffffff81f7a8ad)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff81f7d965)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv4/ipmr_base.c (ffffffff81f8312e)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81fbf0ce)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff81fca9c5)
Location: include/net/netlink.h:1357
Inline: True
```
```
In net/ipv6/route.c (ffffffff81fd2b40)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff8200770c)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ioam6.c (ffffffff82008f59)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/ipv6/ip6mr.c (ffffffff8200cc6f)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/ipv6/seg6_local.c (ffffffff8201afe8)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_fill_encap
  - net/ipv6/seg6_local.c:put_nla_flavors
  - net/ipv6/seg6_local.c:put_nla_oif
  - net/ipv6/seg6_local.c:put_nla_iif
  - net/ipv6/seg6_local.c:put_nla_vrftable
  - net/ipv6/seg6_local.c:put_nla_table
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020278)
Location: include/net/netlink.h:1357
Inline: True
```
```
In net/devlink/leftover.c (ffffffff820376d1)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_trap_policer_fill
  - net/devlink/leftover.c:devlink_nl_trap_group_fill
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
  - net/devlink/leftover.c:devlink_nl_region_notify_build
  - net/devlink/leftover.c:devlink_nl_region_notify_build
  - net/devlink/leftover.c:devlink_nl_param_value_fill_one
  - net/devlink/leftover.c:devlink_dpipe_value_put
  - net/devlink/leftover.c:devlink_dpipe_action_put
  - net/devlink/leftover.c:devlink_dpipe_action_put
  - net/devlink/leftover.c:devlink_dpipe_action_put
  - net/devlink/leftover.c:devlink_dpipe_action_put
  - net/devlink/leftover.c:devlink_dpipe_match_put
  - net/devlink/leftover.c:devlink_dpipe_match_put
  - net/devlink/leftover.c:devlink_dpipe_match_put
  - net/devlink/leftover.c:devlink_dpipe_match_put
  - net/devlink/leftover.c:devlink_nl_port_fill
  - net/devlink/leftover.c:devlink_nl_port_fill
  - net/devlink/leftover.c:devlink_nl_port_fill
  - net/devlink/leftover.c:devlink_nl_port_attrs_put
  - net/devlink/leftover.c:devlink_nl_port_attrs_put
  - net/devlink/leftover.c:devlink_nl_port_attrs_put
  - net/devlink/leftover.c:devlink_nl_port_attrs_put
  - net/devlink/leftover.c:devlink_nl_port_attrs_put
  - net/devlink/leftover.c:devlink_nl_port_attrs_put
  - net/devlink/leftover.c:devlink_nl_port_attrs_put
  - net/devlink/leftover.c:devlink_nl_port_attrs_put
  - net/devlink/leftover.c:devlink_nl_port_handle_fill
```
```
In net/devlink/dev.c (ffffffff8204314e)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_reload_stats_put
```
```
In net/devlink/health.c (ffffffff820472b9)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_fmsg_prepare_skb
  - net/devlink/health.c:devlink_nl_health_reporter_fill
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff82050ab5)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82053b05)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff82054c85)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff8205ad33)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff82068bc5)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff820822c9)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff82087b42)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
```
```
In net/mctp/device.c (ffffffff8208dd96)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_fill_link_af
```
```
In net/mctp/route.c (ffffffff8208f39b)
Location: include/net/netlink.h:1357
Inline: True
```
```
In net/handshake/netlink.c (ffffffff8209250e)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_genl_notify
```
```
In net/handshake/tlshd.c (ffffffff82093eb7)
Location: include/net/netlink.h:1357
Inline: True
Inline callers:
  - net/handshake/tlshd.c:tls_handshake_accept
  - net/handshake/tlshd.c:tls_handshake_accept
  - net/handshake/tlshd.c:tls_handshake_accept
  - net/handshake/tlshd.c:tls_handshake_accept
  - net/handshake/tlshd.c:tls_handshake_accept
  - net/handshake/tlshd.c:tls_handshake_accept
  - net/handshake/tlshd.c:tls_handshake_accept
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
In fs/quota/netlink.c (ffffffff81599b06)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/net/netkit.c (ffffffff81ce50e8)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_fill_info
  - drivers/net/netkit.c:netkit_fill_info
  - drivers/net/netkit.c:netkit_fill_info
```
```
In drivers/net/tun.c (ffffffff81cf861e)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81e0352e)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:__thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_gov
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:__thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_gov_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_state_update
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_state_update
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_delete
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_up
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_up
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_trip_up
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_create
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In drivers/dpll/dpll_netlink.c (ffffffff81ebb8c4)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - drivers/dpll/dpll_netlink.c:dpll_nl_device_get_dumpit
  - drivers/dpll/dpll_netlink.c:dpll_nl_device_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_nl_device_id_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_nl_pin_id_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_device_event_send
  - drivers/dpll/dpll_netlink.c:dpll_cmd_pin_get_one
  - drivers/dpll/dpll_netlink.c:dpll_cmd_pin_get_one
  - drivers/dpll/dpll_netlink.c:dpll_cmd_pin_get_one
  - drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_dplls
  - drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_dplls
  - drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_dplls
  - drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_dplls
  - drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_parents
  - drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_parents
  - drivers/dpll/dpll_netlink.c:dpll_netdev_add_pin_handle
```
```
In net/core/neighbour.c (ffffffff81f07569)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81f160c6)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_port_fill
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/netdev-genl.c (ffffffff81f3d1ab)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/core/netdev-genl.c:netdev_nl_queue_fill_one
  - net/core/netdev-genl.c:netdev_nl_queue_fill_one
  - net/core/netdev-genl.c:netdev_nl_queue_fill_one
  - net/core/netdev-genl.c:netdev_nl_queue_fill_one
  - net/core/netdev-genl.c:netdev_nl_napi_fill_one
  - net/core/netdev-genl.c:netdev_nl_napi_fill_one
  - net/core/netdev-genl.c:netdev_nl_napi_fill_one
  - net/core/netdev-genl.c:netdev_nl_napi_fill_one
  - net/core/netdev-genl.c:netdev_nl_dev_fill
  - net/core/netdev-genl.c:netdev_nl_dev_fill
```
```
In net/core/page_pool_user.c (ffffffff81f45245)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/core/page_pool_user.c:page_pool_nl_fill
  - net/core/page_pool_user.c:page_pool_nl_fill
  - net/core/page_pool_user.c:page_pool_nl_fill
  - net/core/page_pool_user.c:page_pool_nl_fill
  - net/core/page_pool_user.c:page_pool_nl_fill
  - net/core/page_pool_user.c:page_pool_nl_fill
  - net/core/page_pool_user.c:page_pool_nl_stats_fill
  - net/core/page_pool_user.c:page_pool_nl_stats_fill
  - net/core/page_pool_user.c:page_pool_nl_stats_fill
  - net/core/page_pool_user.c:page_pool_nl_stats_fill
  - net/core/page_pool_user.c:page_pool_nl_stats_fill
  - net/core/page_pool_user.c:page_pool_nl_stats_fill
  - net/core/page_pool_user.c:page_pool_nl_stats_fill
  - net/core/page_pool_user.c:page_pool_nl_stats_fill
  - net/core/page_pool_user.c:page_pool_nl_stats_fill
  - net/core/page_pool_user.c:page_pool_nl_stats_fill
  - net/core/page_pool_user.c:page_pool_nl_stats_fill
  - net/core/page_pool_user.c:page_pool_nl_stats_fill
  - net/core/page_pool_user.c:page_pool_nl_stats_fill
```
```
In net/core/fib_rules.c (ffffffff81f4a27a)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81f5cb30)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6aebf)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81f74fed)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81f77fb3)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_qevent_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81f8247e)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_terse
```
```
In net/netlink/af_netlink.c (ffffffff81f881f6)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack_tlv_fill
  - net/netlink/af_netlink.c:netlink_ack_tlv_fill
  - net/netlink/af_netlink.c:netlink_ack_tlv_fill
```
```
In net/netlink/genetlink.c (ffffffff81f8e524)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netlink/policy.c (ffffffff81f90479)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81f9d710)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_fill_reply_header
```
```
In net/ethtool/bitset.c (ffffffff81f9eff6)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81fa04ab)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/linkmodes.c (ffffffff81fa0bd9)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
```
```
In net/ethtool/rss.c (ffffffff81fa1529)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ethtool/rss.c:rss_fill_reply
  - net/ethtool/rss.c:rss_fill_reply
```
```
In net/ethtool/linkstate.c (ffffffff81fa1895)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ethtool/linkstate.c:linkstate_fill_reply
  - net/ethtool/linkstate.c:linkstate_fill_reply
  - net/ethtool/linkstate.c:linkstate_fill_reply
```
```
In net/ethtool/rings.c (ffffffff81fa31eb)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
```
```
In net/ethtool/channels.c (ffffffff81fa38b5)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
  - net/ethtool/channels.c:channels_fill_reply
```
```
In net/ethtool/coalesce.c (ffffffff81fa4645)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:coalesce_put_u32
```
```
In net/ethtool/pause.c (ffffffff81fa4e4e)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/eee.c (ffffffff81fa50b1)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ethtool/eee.c:eee_fill_reply
```
```
In net/ethtool/tsinfo.c (ffffffff81fa5445)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ethtool/tsinfo.c:tsinfo_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81fa5e3c)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
```
```
In net/ethtool/tunnels.c (ffffffff81fa6765)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81fa706e)
Location: include/net/netlink.h:1401
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81fa80f2)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_fill_reply
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stats_put_rmon_hist
```
```
In net/ethtool/phc_vclocks.c (ffffffff81fa8ee7)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ethtool/phc_vclocks.c:phc_vclocks_fill_reply
```
```
In net/ethtool/mm.c (ffffffff81fa96d9)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
```
```
In net/ethtool/pse-pd.c (ffffffff81fa9e67)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ethtool/pse-pd.c:pse_fill_reply
  - net/ethtool/pse-pd.c:pse_fill_reply
```
```
In net/ethtool/plca.c (ffffffff81faa096)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ethtool/plca.c:plca_get_cfg_fill_reply
  - net/ethtool/plca.c:plca_get_cfg_fill_reply
  - net/ethtool/plca.c:plca_get_cfg_fill_reply
  - net/ethtool/plca.c:plca_get_cfg_fill_reply
  - net/ethtool/plca.c:plca_get_cfg_fill_reply
```
```
In net/ipv4/route.c (ffffffff81faff5a)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp.c (ffffffff81fd5fa3)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffb9d5)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff820147bc)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8202973a)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82035eb0)
Location: include/net/netlink.h:1401
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff8203a087)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/fib_rules.c (ffffffff82040fad)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff820441a5)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv4/ipmr_base.c (ffffffff820497ae)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff8208c566)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff82098165)
Location: include/net/netlink.h:1401
Inline: True
```
```
In net/ipv6/route.c (ffffffff820a0450)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff820d659c)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ioam6.c (ffffffff820d7ec9)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/ipv6/ip6mr.c (ffffffff820dbc3f)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/ipv6/seg6_local.c (ffffffff820e9fa8)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_fill_encap
  - net/ipv6/seg6_local.c:put_nla_flavors
  - net/ipv6/seg6_local.c:put_nla_oif
  - net/ipv6/seg6_local.c:put_nla_iif
  - net/ipv6/seg6_local.c:put_nla_vrftable
  - net/ipv6/seg6_local.c:put_nla_table
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820ef3a8)
Location: include/net/netlink.h:1401
Inline: True
```
```
In net/devlink/dev.c (ffffffff8210259e)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_reload_stats_put
```
```
In net/devlink/port.c (ffffffff82106865)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_nl_port_fill
  - net/devlink/port.c:devlink_nl_port_fill
  - net/devlink/port.c:devlink_nl_port_fill
  - net/devlink/port.c:devlink_nl_port_attrs_put
  - net/devlink/port.c:devlink_nl_port_attrs_put
  - net/devlink/port.c:devlink_nl_port_attrs_put
  - net/devlink/port.c:devlink_nl_port_attrs_put
  - net/devlink/port.c:devlink_nl_port_attrs_put
  - net/devlink/port.c:devlink_nl_port_attrs_put
  - net/devlink/port.c:devlink_nl_port_attrs_put
  - net/devlink/port.c:devlink_nl_port_attrs_put
  - net/devlink/port.c:devlink_nl_port_handle_fill
```
```
In net/devlink/sb.c (ffffffff821087f0)
Location: include/net/netlink.h:1401
Inline: True
```
```
In net/devlink/dpipe.c (ffffffff8210a68a)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/devlink/dpipe.c:devlink_dpipe_value_put
  - net/devlink/dpipe.c:devlink_dpipe_action_put
  - net/devlink/dpipe.c:devlink_dpipe_action_put
  - net/devlink/dpipe.c:devlink_dpipe_action_put
  - net/devlink/dpipe.c:devlink_dpipe_action_put
  - net/devlink/dpipe.c:devlink_dpipe_match_put
  - net/devlink/dpipe.c:devlink_dpipe_match_put
  - net/devlink/dpipe.c:devlink_dpipe_match_put
  - net/devlink/dpipe.c:devlink_dpipe_match_put
```
```
In net/devlink/param.c (ffffffff8210dbc8)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/devlink/param.c:devlink_nl_param_value_fill_one
```
```
In net/devlink/region.c (ffffffff821112a8)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/devlink/region.c:devlink_nl_region_read_dumpit
  - net/devlink/region.c:devlink_nl_region_notify_build
  - net/devlink/region.c:devlink_nl_region_notify_build
```
```
In net/devlink/health.c (ffffffff821131e9)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_fmsg_prepare_skb
  - net/devlink/health.c:devlink_nl_health_reporter_fill
```
```
In net/devlink/trap.c (ffffffff82114b01)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_nl_trap_policer_fill
  - net/devlink/trap.c:devlink_nl_trap_group_fill
```
```
In net/devlink/rate.c (ffffffff82118913)
Location: include/net/netlink.h:1401
Inline: True
```
```
In net/devlink/linecard.c (ffffffff8211994b)
Location: include/net/netlink.h:1401
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff82123165)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff821262e5)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff82127565)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff8212dca6)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff8213be45)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff821578ed)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff8215d37a)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_limits_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_limits_doit
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
```
```
In net/mctp/device.c (ffffffff82164256)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_fill_link_af
```
```
In net/mctp/route.c (ffffffff8216587b)
Location: include/net/netlink.h:1401
Inline: True
```
```
In net/handshake/netlink.c (ffffffff82168dee)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_genl_notify
```
```
In net/handshake/tlshd.c (ffffffff8216a7f9)
Location: include/net/netlink.h:1401
Inline: True
Inline callers:
  - net/handshake/tlshd.c:tls_handshake_accept
  - net/handshake/tlshd.c:tls_handshake_accept
  - net/handshake/tlshd.c:tls_handshake_accept
  - net/handshake/tlshd.c:tls_handshake_accept
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
In fs/quota/netlink.c (ffff80001043759c)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/net/tun.c (ffff8000109daf54)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/neighbour.c (ffff800010be3f84)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffff800010bf1758)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vf
```
```
In net/core/fib_rules.c (ffff800010c12df8)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/core/drop_monitor.c (ffff800010c1b748)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (ffff800010c2e1d0)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_api.c (ffff800010c3d4a0)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffff800010c4195c)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/sched/act_api.c (ffff800010c485dc)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/netlink/af_netlink.c (ffff800010c4fd10)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffff800010c51c70)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffff800010c57340)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp.c (ffff800010c76600)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_metrics.c (ffff800010c91cf0)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffff800010ca6ab8)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffff800010cb9228)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/nexthop.c (ffff800010cc382c)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/fib_rules.c (ffff800010cc83d4)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffff800010cc9f48)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (ffff800010cd0a30)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffff800010d02728)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffff800010d0b49c)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/ipv6/route.c (ffff800010d0daa4)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffff800010d4167c)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffff800010d42318)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_local.c (ffff800010d50178)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_fill_encap
  - net/ipv6/seg6_local.c:put_nla_oif
  - net/ipv6/seg6_local.c:put_nla_iif
  - net/ipv6/seg6_local.c:put_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (ffff800010d665ac)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
```
```
In net/netlabel/netlabel_cipso_v4.c (ffff800010d696c4)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffff800010d6a80c)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffff800010d717d4)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
```
```
In net/ncsi/ncsi-netlink.c (ffff800010d7d860)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In fs/quota/netlink.c (c05ff1d8)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/net/tun.c (c0ac2194)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/neighbour.c (c0cfe404)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (c0d09f1c)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vf
```
```
In net/core/fib_rules.c (c0d2a6d4)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (c0d33950)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (c0d451d0)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_api.c (c0d4ef94)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (c0d537a4)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (c0d59620)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/netlink/af_netlink.c (c0d5ff00)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (c0d61350)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (c0d66fc8)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp.c (c0d84d20)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_metrics.c (c0da09f8)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (c0db31d0)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (c0dc47bc)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/nexthop.c (c0dceffc)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/fib_rules.c (c0dd3900)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (c0dd5eec)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (c0ddad80)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (c0e08530)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (c0e1147c)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/ipv6/route.c (c0e14334)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (c0e44064)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (c0e44c38)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_local.c (c0e50dcc)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_fill_encap
  - net/ipv6/seg6_local.c:put_nla_oif
  - net/ipv6/seg6_local.c:put_nla_iif
  - net/ipv6/seg6_local.c:put_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (c0e64de4)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_protocols_cb
```
```
In net/netlabel/netlabel_cipso_v4.c (c0e67cb0)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (c0e68d90)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (c0e6e7ac)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
```
```
In net/ncsi/ncsi-netlink.c (c0e783b0)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In fs/quota/netlink.c (c0000000005499a4)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/net/tun.c (c000000000a9d828)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/neighbour.c (c000000000cc7344)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (c000000000cd62b0)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vf
```
```
In net/core/fib_rules.c (c000000000cffd60)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/core/drop_monitor.c (c000000000d0c684)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (c000000000d24544)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_api.c (c000000000d36d70)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (c000000000d3d620)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (c000000000d45abc)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/netlink/af_netlink.c (c000000000d4e8a0)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (c000000000d5075c)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (c000000000d588ec)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp.c (c000000000d7e17c)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_metrics.c (c000000000da2350)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (c000000000dbaf68)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (c000000000dd1f1c)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/nexthop.c (c000000000ddf48c)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/fib_rules.c (c000000000de5610)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (c000000000de93a0)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (c000000000deeb98)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (c000000000e29fc4)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (c000000000e35b2c)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/ipv6/route.c (c000000000e398ac)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (c000000000e75ee8)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (c000000000e770ec)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_local.c (c000000000e87be0)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_fill_encap
  - net/ipv6/seg6_local.c:put_nla_oif
  - net/ipv6/seg6_local.c:put_nla_iif
  - net/ipv6/seg6_local.c:put_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (c000000000ea2724)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
```
```
In net/netlabel/netlabel_cipso_v4.c (c000000000ea64f8)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (c000000000ea7b78)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (c000000000eb0390)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
```
```
In net/ncsi/ncsi-netlink.c (c000000000ebd334)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In fs/quota/netlink.c (ffffffe0002d17e2)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/net/tun.c (ffffffe000625f46)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/neighbour.c (ffffffe00076a940)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffe0007734b6)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vf
```
```
In net/core/fib_rules.c (ffffffe00078e7e8)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/core/drop_monitor.c (ffffffe000795d3a)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (ffffffe00079feb6)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_api.c (ffffffe0007ad920)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffe0007b130a)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffe0007b6024)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffe0007bb87c)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffe0007bcd4a)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffe0007c168e)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp.c (ffffffe0007d9780)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f1d90)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffe000801e46)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffe00080fe00)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/nexthop.c (ffffffe000818a9a)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/fib_rules.c (ffffffe00081c76e)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffe00081f426)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (ffffffe00082255e)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffe00084ab38)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffe000852702)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/ipv6/route.c (ffffffe000855748)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffe00087cd56)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffe00087d9b0)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_local.c (ffffffe00088871a)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_fill_encap
  - net/ipv6/seg6_local.c:put_nla_oif
  - net/ipv6/seg6_local.c:put_nla_iif
  - net/ipv6/seg6_local.c:put_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (ffffffe00089a0a6)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffe00089c622)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffe00089d3d2)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffe0008a215a)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffe0008ab096)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In fs/quota/netlink.c (ffffffff813660f5)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/net/tun.c (ffffffff817854df)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/neighbour.c (ffffffff818e40ab)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff818efa33)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vf
```
```
In net/core/fib_rules.c (ffffffff8190c4d8)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff819156de)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (ffffffff81925a3a)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_api.c (ffffffff81930e5e)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81934c5c)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff8193b2d5)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8194154f)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff81942822)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff81947902)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp.c (ffffffff819638dc)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197e9c3)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81990601)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff819a07e9)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/nexthop.c (ffffffff819aa0bd)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/fib_rules.c (ffffffff819ae47d)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff819b118d)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (ffffffff819b4942)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff819de8c2)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff819e7850)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/ipv6/route.c (ffffffff819ea03b)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81a1776a)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff81a1820a)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_local.c (ffffffff81a23928)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_fill_encap
  - net/ipv6/seg6_local.c:put_nla_oif
  - net/ipv6/seg6_local.c:put_nla_iif
  - net/ipv6/seg6_local.c:put_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a36371)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a38fd6)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a39fb6)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81a3f57e)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a48f20)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In fs/quota/netlink.c (ffffffff81356d95)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/net/tun.c (ffffffff81764e2f)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In drivers/net/vxlan.c (ffffffff8176d7df)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_fill_info
  - drivers/net/vxlan.c:vxlan_fill_info
  - drivers/net/vxlan.c:vxlan_fill_info
  - drivers/net/vxlan.c:vxlan_fill_info
  - drivers/net/vxlan.c:vxlan_fdb_info
  - drivers/net/vxlan.c:vxlan_fdb_info
  - drivers/net/vxlan.c:vxlan_fdb_info
```
```
In net/core/neighbour.c (ffffffff8189deeb)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff818a9873)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vf
```
```
In net/core/fib_rules.c (ffffffff818c6298)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff818cf48e)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (ffffffff818df7ea)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_api.c (ffffffff818ea95e)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff818ee75c)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff818f4dd5)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818fb03f)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff818fc312)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff819013f2)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp.c (ffffffff8191d3cc)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_metrics.c (ffffffff81938483)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff8194a0c1)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8195a2a9)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/nexthop.c (ffffffff81963b7d)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/fib_rules.c (ffffffff8196aaad)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff8196d7bd)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (ffffffff81970f72)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff8199b682)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff819a4610)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/ipv6/route.c (ffffffff819a6dfb)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff819d452a)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff819d4fca)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_local.c (ffffffff819e06e8)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_fill_encap
  - net/ipv6/seg6_local.c:put_nla_oif
  - net/ipv6/seg6_local.c:put_nla_iif
  - net/ipv6/seg6_local.c:put_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f2f91)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f5bf6)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f6bd6)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff819fc16e)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a05b10)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In fs/quota/netlink.c (ffffffff81363bc5)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/net/tun.c (ffffffff817b588f)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/neighbour.c (ffffffff819350db)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81940a63)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vf
```
```
In net/core/fib_rules.c (ffffffff8195d508)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff8196670e)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (ffffffff81976bca)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_api.c (ffffffff81981fee)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81985dec)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff8198c465)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819926df)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff819939b2)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff819b20d2)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp.c (ffffffff819ce0ac)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e9193)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff819faea1)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0b089)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/nexthop.c (ffffffff81a1495d)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/fib_rules.c (ffffffff81a18d1d)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff81a1ba2d)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (ffffffff81a1f1e2)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81a49342)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff81a522d0)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a54abb)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81a821ea)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff81a82c8a)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_local.c (ffffffff81a8e3a8)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_fill_encap
  - net/ipv6/seg6_local.c:put_nla_oif
  - net/ipv6/seg6_local.c:put_nla_iif
  - net/ipv6/seg6_local.c:put_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aa2221)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81aa4e86)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81aa5e66)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81aab42e)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ab4dd0)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In fs/quota/netlink.c (ffffffff81377275)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/net/tun.c (ffffffff817cfc2f)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/neighbour.c (ffffffff819567eb)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81962373)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vf
```
```
In net/core/fib_rules.c (ffffffff8197f758)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff8198899e)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (ffffffff819990ba)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_api.c (ffffffff819a452e)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff819a8dec)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff819aecf5)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819b51cf)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff819b64a2)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff819bb792)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp.c (ffffffff819d7c3c)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f2ef3)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81a051f2)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81a15869)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/nexthop.c (ffffffff81a1f36d)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/fib_rules.c (ffffffff81a2379d)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_fill
```
```
In net/ipv4/ipmr.c (ffffffff81a2697a)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (ffffffff81a2a6b2)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81a55262)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/addrlabel.c (ffffffff81a5e2c0)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a60aab)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81a8eafa)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff81a8f55a)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_local.c (ffffffff81a9b118)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_fill_encap
  - net/ipv6/seg6_local.c:put_nla_oif
  - net/ipv6/seg6_local.c:put_nla_iif
  - net/ipv6/seg6_local.c:put_nla_table
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aae591)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ab1206)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ab2206)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81ab779e)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ac1170)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
</details>
</li>
</ul>

## Differences
