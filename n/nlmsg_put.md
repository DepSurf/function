# Function: <code>nlmsg_put</code>

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
In kernel/audit.c (ffffffff811217ea)
Location: include/net/netlink.h:446
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff8134cb54)
Location: include/net/netlink.h:446
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/connector/connector.c (ffffffff81541dde)
Location: include/net/netlink.h:446
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In net/core/net_namespace.c (ffffffff8170fdc4)
Location: include/net/netlink.h:446
Inline: True
```
```
In net/core/neighbour.c (ffffffff81726456)
Location: include/net/netlink.h:446
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_dump_info
```
```
In net/core/rtnetlink.c (ffffffff8172d1b8)
Location: include/net/netlink.h:446
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/fib_rules.c (ffffffff81739d3d)
Location: include/net/netlink.h:446
Inline: True
```
```
In net/sched/sch_api.c (ffffffff817437c0)
Location: include/net/netlink.h:446
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81745fd9)
Location: include/net/netlink.h:446
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81747203)
Location: include/net/netlink.h:446
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tc_dump_action
```
```
In net/netlink/af_netlink.c (ffffffff8174c352)
Location: include/net/netlink.h:446
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff8174f276)
Location: include/net/netlink.h:446
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff81753b63)
Location: include/net/netlink.h:446
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81790229)
Location: include/net/netlink.h:446
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8179d886)
Location: include/net/netlink.h:446
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff817a86f8)
Location: include/net/netlink.h:446
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff817cb74b)
Location: include/net/netlink.h:446
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/addrlabel.c (ffffffff817d2503)
Location: include/net/netlink.h:446
Inline: True
```
```
In net/ipv6/route.c (ffffffff817d85fb)
Location: include/net/netlink.h:446
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffff817df9ef)
Location: include/net/netlink.h:446
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffffffff817f9248)
Location: include/net/netlink.h:446
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff81809b7e)
Location: include/net/netlink.h:446
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff81813d07)
Location: include/net/netlink.h:446
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
In kernel/audit.c (ffffffff8112977d)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff81382af4)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/connector/connector.c (ffffffff81593726)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In net/core/net_namespace.c (ffffffff81777704)
Location: include/net/netlink.h:457
Inline: True
```
```
In net/core/neighbour.c (ffffffff81790d65)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81798fcf)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff817a601d)
Location: include/net/netlink.h:457
Inline: True
```
```
In net/sched/sch_api.c (ffffffff817b0661)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff817b2fe9)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff817b4b60)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff817b808e)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff817bb256)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff817bfc33)
Location: include/net/netlink.h:457
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff817fdcd5)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8180b3d6)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff81815e28)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff8183877b)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/addrlabel.c (ffffffff8183ffc3)
Location: include/net/netlink.h:457
Inline: True
```
```
In net/ipv6/route.c (ffffffff81841fcc)
Location: include/net/netlink.h:457
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffff8184f11a)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffffffff81868a88)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff8187b67e)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff81886be7)
Location: include/net/netlink.h:457
Inline: True
```
```
In net/switchdev/switchdev.c (ffffffff8188ad78)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_fdb_dump_cb
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
In kernel/audit.c (ffffffff811338cc)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff81399574)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/connector/connector.c (ffffffff815c0fe6)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In net/core/net_namespace.c (ffffffff817a4784)
Location: include/net/netlink.h:457
Inline: True
```
```
In net/core/neighbour.c (ffffffff817be661)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff817c6d7f)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff817d4afd)
Location: include/net/netlink.h:457
Inline: True
```
```
In net/sched/sch_api.c (ffffffff817dfda1)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff817e2869)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff817e4420)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff817e7b6e)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff817eadc6)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff817f2d3b)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff8182ec35)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8183c4e6)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff818475d8)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff8186a2ab)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/addrlabel.c (ffffffff81871c43)
Location: include/net/netlink.h:457
Inline: True
```
```
In net/ipv6/route.c (ffffffff81873d1c)
Location: include/net/netlink.h:457
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffff81881070)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffffffff8189b8d8)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff818aff3e)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff818bb457)
Location: include/net/netlink.h:457
Inline: True
```
```
In net/switchdev/switchdev.c (ffffffff818bf148)
Location: include/net/netlink.h:457
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_fdb_dump_cb
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
In kernel/audit.c (ffffffff81134db4)
Location: include/net/netlink.h:466
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff813af9e8)
Location: include/net/netlink.h:466
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/connector/connector.c (ffffffff815d6b2d)
Location: include/net/netlink.h:466
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In net/core/net_namespace.c (ffffffff817c28c4)
Location: include/net/netlink.h:466
Inline: True
```
```
In net/core/neighbour.c (ffffffff817dd6f5)
Location: include/net/netlink.h:466
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff817e568f)
Location: include/net/netlink.h:466
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff817f3eb6)
Location: include/net/netlink.h:466
Inline: True
```
```
In net/sched/sch_api.c (ffffffff817ff3fd)
Location: include/net/netlink.h:466
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81802158)
Location: include/net/netlink.h:466
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81803e62)
Location: include/net/netlink.h:466
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff8180786c)
Location: include/net/netlink.h:466
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff8180ad26)
Location: include/net/netlink.h:466
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff8181372c)
Location: include/net/netlink.h:466
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff8184f1e9)
Location: include/net/netlink.h:466
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8185dc26)
Location: include/net/netlink.h:466
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff8186a94b)
Location: include/net/netlink.h:466
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff8188e81c)
Location: include/net/netlink.h:466
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff818969c3)
Location: include/net/netlink.h:466
Inline: True
```
```
In net/ipv6/route.c (ffffffff81898b46)
Location: include/net/netlink.h:466
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff818a70a6)
Location: include/net/netlink.h:466
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffffffff818c1c89)
Location: include/net/netlink.h:466
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff818d691e)
Location: include/net/netlink.h:466
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff818e1e47)
Location: include/net/netlink.h:466
Inline: True
```
```
In net/switchdev/switchdev.c (ffffffff818e5a88)
Location: include/net/netlink.h:466
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_fdb_dump_cb
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
In kernel/audit.c (ffffffff81141b04)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff813d5a98)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/connector/connector.c (ffffffff8163d90d)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In net/core/net_namespace.c (ffffffff8183c204)
Location: include/net/netlink.h:472
Inline: True
```
```
In net/core/neighbour.c (ffffffff81857a75)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff8186072f)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff8186f616)
Location: include/net/netlink.h:472
Inline: True
```
```
In net/sched/sch_api.c (ffffffff8187d16d)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81880387)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff8188249d)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff818863f6)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff81889c76)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff81892d86)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff818cee19)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff818ddc56)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff818eb0cb)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff8190fe6c)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81917e33)
Location: include/net/netlink.h:472
Inline: True
```
```
In net/ipv6/route.c (ffffffff81919e46)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81929b05)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffffffff819455c9)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff8195c4ee)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff81967be7)
Location: include/net/netlink.h:472
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
In kernel/audit.c (ffffffff81150493)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff814060b8)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/connector/connector.c (ffffffff81678f18)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In net/core/net_namespace.c (ffffffff81886c64)
Location: include/net/netlink.h:472
Inline: True
```
```
In net/core/neighbour.c (ffffffff818a2bee)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff818aa5ea)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff818c0d70)
Location: include/net/netlink.h:472
Inline: True
```
```
In net/sched/sch_api.c (ffffffff818cf78d)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff818d3118)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff818d5fc9)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
```
```
In net/netlink/af_netlink.c (ffffffff818d9c82)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff818dd74a)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff818e6e5f)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff81925bd5)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff819347c0)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff819418ad)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81967291)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff8196f4f3)
Location: include/net/netlink.h:472
Inline: True
```
```
In net/ipv6/route.c (ffffffff81971f6e)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81981ca4)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffffffff8199d0ce)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff819b5d05)
Location: include/net/netlink.h:472
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff819c1406)
Location: include/net/netlink.h:472
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
In kernel/audit.c (ffffffff8115d153)
Location: include/net/netlink.h:615
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff81421c08)
Location: include/net/netlink.h:615
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/connector/connector.c (ffffffff81697ff5)
Location: include/net/netlink.h:615
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In net/core/net_namespace.c (ffffffff818a7365)
Location: include/net/netlink.h:615
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff818c5890)
Location: include/net/netlink.h:615
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff818d0487)
Location: include/net/netlink.h:615
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff818e9b7d)
Location: include/net/netlink.h:615
Inline: True
```
```
In net/sched/sch_api.c (ffffffff818fab2d)
Location: include/net/netlink.h:615
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff818feaab)
Location: include/net/netlink.h:615
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff819027c7)
Location: include/net/netlink.h:615
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (ffffffff81906734)
Location: include/net/netlink.h:615
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff8190a107)
Location: include/net/netlink.h:615
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff81913d3b)
Location: include/net/netlink.h:615
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff81954b6c)
Location: include/net/netlink.h:615
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8196410d)
Location: include/net/netlink.h:615
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff81971159)
Location: include/net/netlink.h:615
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff8199c89e)
Location: include/net/netlink.h:615
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff819a5083)
Location: include/net/netlink.h:615
Inline: True
```
```
In net/ipv6/route.c (ffffffff819a76bb)
Location: include/net/netlink.h:615
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff819b8350)
Location: include/net/netlink.h:615
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffffffff819d3c2b)
Location: include/net/netlink.h:615
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff819ecfc5)
Location: include/net/netlink.h:615
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff819f8966)
Location: include/net/netlink.h:615
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a04252)
Location: include/net/netlink.h:615
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
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
In kernel/audit.c (ffffffff81169882)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff8144f7d4)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/connector/connector.c (ffffffff816d0b6f)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In net/core/net_namespace.c (ffffffff818f2405)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff819118e0)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff8191d337)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff819395d5)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/core/devlink.c (ffffffff8194f09e)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
```
In net/sched/sch_api.c (ffffffff8195a3e0)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff8195e49e)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81963a2a)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (ffffffff819679da)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff8196b50b)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff81970fff)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (ffffffff819b8adc)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff819c9cc9)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff819d36d9)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff819da8d9)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81a08a7e)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a11523)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a13d10)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81a26da0)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffffffff81a41eab)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81a5c1a5)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff81a67c27)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a734f4)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
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
In kernel/audit.c (ffffffff81175722)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff81469644)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/connector/connector.c (ffffffff816f498f)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In net/core/net_namespace.c (ffffffff81924355)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81943f50)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff8194f966)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff8196c495)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/core/devlink.c (ffffffff81985e0e)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
```
In net/sched/sch_api.c (ffffffff81990880)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81994d6e)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff8199a5aa)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (ffffffff8199e46a)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff819a1ebb)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff819a79ff)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (ffffffff819ef7dc)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81a00889)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81a0a249)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81a1178c)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81a3f18e)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a48143)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a4a900)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81a5d806)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffffffff81a78b0b)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81a92dd5)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff81a9e587)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81aa9ce4)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
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
In kernel/audit.c (ffffffff8118658b)
Location: include/net/netlink.h:901
Inline: True
Inline callers:
  - kernel/audit.c:audit_buffer_alloc
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff814bd807)
Location: include/net/netlink.h:901
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/connector/connector.c (ffffffff817acfbf)
Location: include/net/netlink.h:901
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In net/core/net_namespace.c (ffffffff819f8025)
Location: include/net/netlink.h:901
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81a13fc0)
Location: include/net/netlink.h:901
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
```
```
In net/core/rtnetlink.c (ffffffff81a21184)
Location: include/net/netlink.h:901
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81a4033d)
Location: include/net/netlink.h:901
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/devlink.c (ffffffff81a54860)
Location: include/net/netlink.h:901
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
```
```
In net/sched/sch_api.c (ffffffff81a689c0)
Location: include/net/netlink.h:901
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a6da9e)
Location: include/net/netlink.h:901
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81a73508)
Location: include/net/netlink.h:901
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff81a7804a)
Location: include/net/netlink.h:901
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff81a7b6db)
Location: include/net/netlink.h:901
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff81a9116a)
Location: include/net/netlink.h:901
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81addc1c)
Location: include/net/netlink.h:901
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81aef9fb)
Location: include/net/netlink.h:901
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81afada9)
Location: include/net/netlink.h:901
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81b04a24)
Location: include/net/netlink.h:901
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81b34e0e)
Location: include/net/netlink.h:901
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifmcaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b3efe3)
Location: include/net/netlink.h:901
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b44e5c)
Location: include/net/netlink.h:901
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81b53b1b)
Location: include/net/netlink.h:901
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/ip6mr.c (ffffffff81b744d6)
Location: include/net/netlink.h:901
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff81b8e0e5)
Location: include/net/netlink.h:901
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff81b99607)
Location: include/net/netlink.h:901
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba5ee4)
Location: include/net/netlink.h:901
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
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
In kernel/audit.c (ffffffff8118367b)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - kernel/audit.c:audit_buffer_alloc
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff814db267)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/connector/connector.c (ffffffff817c1b4f)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In net/core/net_namespace.c (ffffffff819f7a85)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81a142e0)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
```
```
In net/core/rtnetlink.c (ffffffff81a1f703)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81a4303d)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/devlink.c (ffffffff81a5b7b9)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
```
```
In net/sched/sch_api.c (ffffffff81a710d0)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a7645e)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81a7c108)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff81a8046b)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81a85728)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_prep
```
```
In net/ipv4/route.c (ffffffff81a9afcf)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81aea9fc)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81afc93b)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81b08479)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81b12b94)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81b43a1e)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifmcaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b4da63)
Location: include/net/netlink.h:914
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b537dc)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81b6210b)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/ip6mr.c (ffffffff81b83246)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff81b9dd75)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff81ba92b7)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81bb53c4)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
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
In kernel/audit.c (ffffffff8118602d)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff814e1bee)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/connector/connector.c (ffffffff817a506f)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In net/core/net_namespace.c (ffffffff819ddc05)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff819fac70)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81a067d3)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81a27d9d)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/devlink.c (ffffffff81a49bbd)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
```
```
In net/sched/sch_api.c (ffffffff81a598a0)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a5e35e)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81a64d39)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff81a693b9)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81a6e7e8)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_prep
```
```
In net/ipv4/route.c (ffffffff81a863ef)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81ad613c)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae813a)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81af6da5)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81b008f2)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81b3167e)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b3b4f3)
Location: include/net/netlink.h:914
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b40da0)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81b5036b)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/ip6mr.c (ffffffff81b71ec9)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff81b8ce75)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff81b98447)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba43c4)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
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
In kernel/audit.c (ffffffff811ae41d)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff8153abee)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/connector/connector.c (ffffffff818309ef)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/wwan/wwan_core.c (ffffffff8191a913)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In net/core/net_namespace.c (ffffffff81a8de87)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81aac8b0)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81ab8c33)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81adcb3d)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/devlink.c (ffffffff81af8748)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
```
```
In net/sched/sch_api.c (ffffffff81b12960)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81b1753e)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81b1e009)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff81b22969)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81b27e68)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_prep
```
```
In net/ipv4/route.c (ffffffff81b40b2f)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81b94e6c)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba806f)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81bb66d5)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81bc1dd1)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81bf771e)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81c01d13)
Location: include/net/netlink.h:914
Inline: True
```
```
In net/ipv6/route.c (ffffffff81c08a70)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81c1761b)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/ip6mr.c (ffffffff81c3c379)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff81c59215)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff81c64f97)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81c71f54)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
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
In kernel/audit.c (ffffffff811df651)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff815d232f)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/connector/connector.c (ffffffff81971d80)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81a6fd60)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In net/core/net_namespace.c (ffffffff81c03ae7)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81c25810)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81c31e74)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81c5e089)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/devlink.c (ffffffff81c84472)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
```
```
In net/sched/sch_api.c (ffffffff81c9af1a)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81c9f2ee)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81ca59ec)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff81cab509)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81cafbb2)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff81ccd5d0)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81d26ace)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3aa5d)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81d4a30d)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81d56116)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81d90b8b)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81d9bc53)
Location: include/net/netlink.h:914
Inline: True
```
```
In net/ipv6/route.c (ffffffff81da3521)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81db340b)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/ip6mr.c (ffffffff81dda73c)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff81dfa975)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff81e07b86)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81e15ade)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
```
```
In net/mctp/device.c (ffffffff81e37f03)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_fill_addrinfo
```
```
In net/mctp/route.c (ffffffff81e391c5)
Location: include/net/netlink.h:914
Inline: True
```
```
In net/mctp/neigh.c (ffffffff81e3b3aa)
Location: include/net/netlink.h:914
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_getneigh
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
In kernel/audit.c (ffffffff81225331)
Location: include/net/netlink.h:942
Inline: True
Inline callers:
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff816801ef)
Location: include/net/netlink.h:942
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/connector/connector.c (ffffffff81add000)
Location: include/net/netlink.h:942
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c02bf0)
Location: include/net/netlink.h:942
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In net/core/net_namespace.c (ffffffff81db3197)
Location: include/net/netlink.h:942
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81dd7a50)
Location: include/net/netlink.h:942
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81de5244)
Location: include/net/netlink.h:942
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81e148a9)
Location: include/net/netlink.h:942
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/devlink.c (ffffffff81e3ca02)
Location: include/net/netlink.h:942
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
```
```
In net/sched/sch_api.c (ffffffff81e573aa)
Location: include/net/netlink.h:942
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81e5b51e)
Location: include/net/netlink.h:942
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81e63a8c)
Location: include/net/netlink.h:942
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff81e6c75f)
Location: include/net/netlink.h:942
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81e6d8d2)
Location: include/net/netlink.h:942
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff81e8d720)
Location: include/net/netlink.h:942
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81eee46e)
Location: include/net/netlink.h:942
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81f033cd)
Location: include/net/netlink.h:942
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81f139ad)
Location: include/net/netlink.h:942
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81f20176)
Location: include/net/netlink.h:942
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81f5f2ab)
Location: include/net/netlink.h:942
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81f6a8e3)
Location: include/net/netlink.h:942
Inline: True
```
```
In net/ipv6/route.c (ffffffff81f72961)
Location: include/net/netlink.h:942
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81f82d6b)
Location: include/net/netlink.h:942
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/ip6mr.c (ffffffff81fac45c)
Location: include/net/netlink.h:942
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff81fcf125)
Location: include/net/netlink.h:942
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff81fdd0c6)
Location: include/net/netlink.h:942
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81feca8e)
Location: include/net/netlink.h:942
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
```
```
In net/mctp/device.c (ffffffff82011133)
Location: include/net/netlink.h:942
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_fill_addrinfo
```
```
In net/mctp/route.c (ffffffff82012485)
Location: include/net/netlink.h:942
Inline: True
```
```
In net/mctp/neigh.c (ffffffff82014a6a)
Location: include/net/netlink.h:942
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_getneigh
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
In kernel/audit.c (ffffffff8123b901)
Location: include/net/netlink.h:943
Inline: True
Inline callers:
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff816b82cf)
Location: include/net/netlink.h:943
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/connector/connector.c (ffffffff81b2b270)
Location: include/net/netlink.h:943
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c682a0)
Location: include/net/netlink.h:943
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In net/core/net_namespace.c (ffffffff81e23767)
Location: include/net/netlink.h:943
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81e48860)
Location: include/net/netlink.h:943
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81e56c64)
Location: include/net/netlink.h:943
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81e881bd)
Location: include/net/netlink.h:943
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/sched/sch_api.c (ffffffff81eb33d5)
Location: include/net/netlink.h:943
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81eb7c45)
Location: include/net/netlink.h:943
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81ebfb22)
Location: include/net/netlink.h:943
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff81ec87bf)
Location: include/net/netlink.h:943
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81ec99e2)
Location: include/net/netlink.h:943
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff81eebe40)
Location: include/net/netlink.h:943
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81f4de2b)
Location: include/net/netlink.h:943
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81f62dad)
Location: include/net/netlink.h:943
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81f7367d)
Location: include/net/netlink.h:943
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81f7fc76)
Location: include/net/netlink.h:943
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81fbefde)
Location: include/net/netlink.h:943
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81fca917)
Location: include/net/netlink.h:943
Inline: True
```
```
In net/ipv6/route.c (ffffffff81fd2a51)
Location: include/net/netlink.h:943
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81fe306b)
Location: include/net/netlink.h:943
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/ip6mr.c (ffffffff8200cbfc)
Location: include/net/netlink.h:943
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/devlink/leftover.c (ffffffff82033c43)
Location: include/net/netlink.h:943
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_cmd_dpipe_entries_get
```
```
In net/devlink/health.c (ffffffff82047465)
Location: include/net/netlink.h:943
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff8204ad55)
Location: include/net/netlink.h:943
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff82059196)
Location: include/net/netlink.h:943
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff82068d2e)
Location: include/net/netlink.h:943
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
```
```
In net/mctp/device.c (ffffffff8208def3)
Location: include/net/netlink.h:943
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_fill_addrinfo
```
```
In net/mctp/route.c (ffffffff8208f275)
Location: include/net/netlink.h:943
Inline: True
```
```
In net/mctp/neigh.c (ffffffff8209188a)
Location: include/net/netlink.h:943
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_getneigh
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
In kernel/audit.c (ffffffff812557c1)
Location: include/net/netlink.h:950
Inline: True
Inline callers:
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff816f4cff)
Location: include/net/netlink.h:950
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/connector/connector.c (ffffffff81b82604)
Location: include/net/netlink.h:950
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In net/core/net_namespace.c (ffffffff81ee16c7)
Location: include/net/netlink.h:950
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81f07420)
Location: include/net/netlink.h:950
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81f15fb7)
Location: include/net/netlink.h:950
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81f4a1cd)
Location: include/net/netlink.h:950
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/sched/sch_api.c (ffffffff81f75ee5)
Location: include/net/netlink.h:950
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81f7ac55)
Location: include/net/netlink.h:950
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81f82cd2)
Location: include/net/netlink.h:950
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff81f8bacc)
Location: include/net/netlink.h:950
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81f8cab5)
Location: include/net/netlink.h:950
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff81fafe90)
Location: include/net/netlink.h:950
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (ffffffff82013f5b)
Location: include/net/netlink.h:950
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8202937d)
Location: include/net/netlink.h:950
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff82039e6d)
Location: include/net/netlink.h:950
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff820462f6)
Location: include/net/netlink.h:950
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff8208c46e)
Location: include/net/netlink.h:950
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff820980b7)
Location: include/net/netlink.h:950
Inline: True
```
```
In net/ipv6/route.c (ffffffff820a0361)
Location: include/net/netlink.h:950
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff820b0f8b)
Location: include/net/netlink.h:950
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/ip6mr.c (ffffffff820dbbcc)
Location: include/net/netlink.h:950
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/devlink/dpipe.c (ffffffff8210bfe3)
Location: include/net/netlink.h:950
Inline: True
Inline callers:
  - net/devlink/dpipe.c:devlink_nl_dpipe_entries_get_doit
```
```
In net/devlink/resource.c (ffffffff8210c8f7)
Location: include/net/netlink.h:950
Inline: True
```
```
In net/devlink/health.c (ffffffff821133a0)
Location: include/net/netlink.h:950
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff8211d1d5)
Location: include/net/netlink.h:950
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff8212bd16)
Location: include/net/netlink.h:950
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff8213bfae)
Location: include/net/netlink.h:950
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
```
```
In net/mctp/device.c (ffffffff821643b3)
Location: include/net/netlink.h:950
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_fill_addrinfo
```
```
In net/mctp/route.c (ffffffff82165755)
Location: include/net/netlink.h:950
Inline: True
```
```
In net/mctp/neigh.c (ffffffff82167e2a)
Location: include/net/netlink.h:950
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_getneigh
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
In kernel/audit.c (ffff8000101ea564)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffff800010557ad0)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/connector/connector.c (ffff8000108ddd64)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffff800010be3df4)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffff800010bf1678)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffff800010c12d58)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
```
In net/sched/sch_api.c (ffff800010c3cb28)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffff800010c418f8)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/sched/act_api.c (ffff800010c477b8)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (ffff800010c4ba78)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffff800010c50b0c)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffff800010c572d8)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (ffff800010ca5680)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffff800010cb8ec0)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffff800010cc375c)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffff800010cc9ecc)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffff800010d02670)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffff800010d0b434)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/ipv6/route.c (ffff800010d0da18)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffff800010d22a98)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffff800010d42288)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffff800010d60bf8)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffff800010d6ef74)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffff800010d7d9b8)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
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
In kernel/audit.c (c042a2c0)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (c070c9f8)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/connector/connector.c (c09ccdd8)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In net/core/net_namespace.c (c0cdb7a4)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (c0cfe310)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (c0d09e28)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (c0d2a668)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/devlink.c (c0d45424)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
```
In net/sched/sch_api.c (c0d4e880)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (c0d53714)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (c0d585b8)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (c0d5c340)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (c0d607b8)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (c0d66f44)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (c0db1fb0)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (c0dc45f0)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (c0dcef24)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (c0dd5e20)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (c0e08494)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (c0e11400)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/ipv6/route.c (c0e14274)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (c0e27040)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (c0e44bd4)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (c0e60420)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/dcb/dcbnl.c (c0e6cc38)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (c0e784ec)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
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
In kernel/audit.c (c00000000025b77c)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (c0000000006b5a14)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/connector/connector.c (c000000000971580)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In net/core/net_namespace.c (c000000000c990dc)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (c000000000cc721c)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (c000000000cd6158)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (c000000000cffce0)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/core/devlink.c (c000000000d2489c)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
```
In net/sched/sch_api.c (c000000000d37c10)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (c000000000d3d5a4)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (c000000000d44690)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (c000000000d49bec)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (c000000000d4f768)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (c000000000d5882c)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (c000000000db9510)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (c000000000dd1a9c)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (c000000000ddf3bc)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (c000000000de9308)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (c000000000e29ef8)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (c000000000e35a88)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/ipv6/route.c (c000000000e397d8)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (c000000000e52768)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (c000000000e77070)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (c000000000e9bf3c)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (c000000000eac2b8)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-netlink.c (c000000000ebd4f0)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
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
In kernel/audit.c (ffffffe00015efa8)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffe0003af41e)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/connector/connector.c (ffffffe000574312)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In net/core/net_namespace.c (ffffffe00074d58a)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffe00076a854)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffe0007733f4)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffe00078e79c)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/core/devlink.c (ffffffe0007a0088)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
```
In net/sched/sch_api.c (ffffffe0007ad3b6)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffe0007b12b2)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffe0007b54e6)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (ffffffe0007b8f9a)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffe0007bbfc6)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffe0007c1634)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (ffffffe000800f4a)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffe00080fca4)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffe0008189fa)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffe00081f3b0)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffe00084aab6)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffe0008526a0)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/ipv6/route.c (ffffffe0008556ce)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffe00086459e)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffffffe00087d976)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffe000895e58)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/dcb/dcbnl.c (ffffffe0008a0c12)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffe0008ab1d4)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
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
In kernel/audit.c (ffffffff8116dd42)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff81461c24)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/connector/connector.c (ffffffff816ba17f)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In net/core/net_namespace.c (ffffffff818c4355)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff818e3f20)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff818ef936)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff8190c465)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/core/devlink.c (ffffffff81925c7e)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
```
In net/sched/sch_api.c (ffffffff819306f0)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81934bde)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff8193a41a)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (ffffffff8193e2da)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff81941d2b)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff8194786f)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (ffffffff8198f57c)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff819a0629)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff819a9fe9)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff819b10e9)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff819de81e)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff819e77d3)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/ipv6/route.c (ffffffff819e9f90)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff819fce96)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffffffff81a1819b)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81a32465)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff81a3d917)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a49074)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
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
In kernel/audit.c (ffffffff81160ee2)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff81452654)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/connector/connector.c (ffffffff81697dbf)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/scsi/scsi_transport_fc.c (ffffffff8170f7a8)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - drivers/scsi/scsi_transport_fc.c:fc_host_post_fc_event
```
```
In drivers/net/vxlan.c (ffffffff8176cd18)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_fdb_info
```
```
In net/core/net_namespace.c (ffffffff8187e295)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff8189dd60)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff818a9776)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff818c6225)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/core/devlink.c (ffffffff818dfa2e)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
```
In net/sched/sch_api.c (ffffffff818ea1f0)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff818ee6de)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff818f3f1a)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (ffffffff818f7dda)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff818fb81b)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff8190135f)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (ffffffff8194903c)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8195a0e9)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81963aa9)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff8196d719)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff8199b5de)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff819a4593)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/ipv6/route.c (ffffffff819a6d50)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff819b9c56)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffffffff819d4f5b)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff819ef655)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff819fa507)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a05c64)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
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
In kernel/audit.c (ffffffff8116bb12)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff8145dcc4)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/connector/connector.c (ffffffff816e864f)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In net/core/net_namespace.c (ffffffff81915355)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81934f50)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81940966)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff8195d495)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/core/devlink.c (ffffffff81976e0e)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
```
In net/sched/sch_api.c (ffffffff81981880)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81985d6e)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff8198b5aa)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (ffffffff8198f46a)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff81992ebb)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff81999d82)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199bd14)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:__build_packet_message
  - net/netfilter/nfnetlink_log.c:__nfulnl_send
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819ae6bc)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_stat_cpu_dump
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_expect_event
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_stat_ct
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_ct_stat_cpu_dump
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_conntrack_event
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_fill_info
```
```
In net/ipv4/route.c (ffffffff819b203f)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (ffffffff819f9e1c)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0aec9)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81a14889)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81a1b989)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81a4929e)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a52253)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a54a10)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81a67916)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffffffff81a82c1b)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81a9e015)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff81aa97c7)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ab4f24)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
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
In kernel/audit.c (ffffffff811792d2)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In security/selinux/netlink.c (ffffffff81475464)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/connector/connector.c (ffffffff81702d4f)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In net/core/net_namespace.c (ffffffff81936535)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81956660)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81962276)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff8197f6e5)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/core/devlink.c (ffffffff819992fe)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
```
In net/sched/sch_api.c (ffffffff819a3ded)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff819a8d6e)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff819ade1a)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (ffffffff819b1d4a)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff819b59ab)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_put
```
```
In net/ipv4/route.c (ffffffff819bb6ff)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81a0412c)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81a156a9)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81a1f299)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81a2689c)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81a551be)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a5e243)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a60a00)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81a73f05)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffffffff81a8f4eb)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81aaa215)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/dcb/dcbnl.c (ffffffff81ab5b37)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ac12c4)
Location: include/net/netlink.h:849
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
```
</details>
</li>
</ul>

## Differences
