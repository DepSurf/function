# Function: <code>nlmsg_trim</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void nlmsg_trim(struct sk_buff *skb, const void *mark);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8113e847)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/net_namespace.c (ffffffff8170fe58)
Location: include/net/netlink.h:520
Inline: True
```
```
In net/core/neighbour.c (ffffffff817263d6)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_dump_info
```
```
In net/core/rtnetlink.c (ffffffff8172a100)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
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
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/fib_rules.c (ffffffff81739ee4)
Location: include/net/netlink.h:520
Inline: True
```
```
In net/core/lwtunnel.c (ffffffff8173e33d)
Location: include/net/netlink.h:520
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81743955)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81745d3f)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81747906)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump
```
```
In net/netlink/genetlink.c (ffffffff8174fc10)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:genl_ctrl_event
```
```
In net/ipv4/route.c (ffffffff81753e7d)
Location: include/net/netlink.h:520
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff817814d9)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff81790355)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8179dac8)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff817a8679)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff817cb926)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/addrlabel.c (ffffffff817d25d8)
Location: include/net/netlink.h:520
Inline: True
```
```
In net/ipv6/route.c (ffffffff817d8707)
Location: include/net/netlink.h:520
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff817f91ce)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff81809c24)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8180db6e)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8180e876)
Location: include/net/netlink.h:520
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8180fd62)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/dcb/dcbnl.c (ffffffff81813c53)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getcap
```
**Symbols:**

```
ffffffff8172a100-ffffffff8172a14d: nlmsg_trim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void nlmsg_trim(struct sk_buff *skb, const void *mark);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff81146e7c)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/net_namespace.c (ffffffff81777798)
Location: include/net/netlink.h:531
Inline: True
```
```
In net/core/neighbour.c (ffffffff81790fbe)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81799075)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
Direct callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/fib_rules.c (ffffffff817a61e9)
Location: include/net/netlink.h:531
Inline: True
```
```
In net/core/lwtunnel.c (ffffffff817aaca9)
Location: include/net/netlink.h:531
Inline: True
```
```
In net/sched/sch_api.c (ffffffff817b07e1)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff817b2c93)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff817b4c88)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/netlink/genetlink.c (ffffffff817bc55d)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff817bff41)
Location: include/net/netlink.h:531
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff817eedb9)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff817fdec3)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8180b60f)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff81815f71)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff8183894e)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/addrlabel.c (ffffffff81840098)
Location: include/net/netlink.h:531
Inline: True
```
```
In net/ipv6/route.c (ffffffff81842109)
Location: include/net/netlink.h:531
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81868bc3)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff8187b724)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8188004f)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81880f00)
Location: include/net/netlink.h:531
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81882430)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81883430)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/dcb/dcbnl.c (ffffffff81888972)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/switchdev/switchdev.c (ffffffff8188ae6b)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_fdb_dump_cb
```
**Symbols:**

```
ffffffff81793b40-ffffffff81793b8d: nlmsg_trim (STB_LOCAL)
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
In kernel/taskstats.c (ffffffff81150ccc)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/net_namespace.c (ffffffff817a4818)
Location: include/net/netlink.h:531
Inline: True
```
```
In net/core/neighbour.c (ffffffff817be862)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff817c6e25)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/fib_rules.c (ffffffff817d4d42)
Location: include/net/netlink.h:531
Inline: True
```
```
In net/core/lwtunnel.c (ffffffff817d9a49)
Location: include/net/netlink.h:531
Inline: True
```
```
In net/sched/sch_api.c (ffffffff817dff21)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff817e2512)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff817e4548)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/netlink/genetlink.c (ffffffff817ebe6d)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff817f3100)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181f7c9)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff8182ee23)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8183c728)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff81847721)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff8186a47e)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/addrlabel.c (ffffffff81871d18)
Location: include/net/netlink.h:531
Inline: True
```
```
In net/ipv6/route.c (ffffffff81873e59)
Location: include/net/netlink.h:531
Inline: True
```
```
In net/ipv6/seg6.c (ffffffff81899951)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff8189ba13)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff818affe4)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818b48ff)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818b57b0)
Location: include/net/netlink.h:531
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818b6ce0)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818b7cd0)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/dcb/dcbnl.c (ffffffff818bd192)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/switchdev/switchdev.c (ffffffff818bf23b)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_fdb_dump_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void nlmsg_trim(struct sk_buff *skb, const void *mark);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff811532ce)
Location: include/net/netlink.h:540
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/net_namespace.c (ffffffff817c2958)
Location: include/net/netlink.h:540
Inline: True
```
```
In net/core/neighbour.c (ffffffff817ddb5d)
Location: include/net/netlink.h:540
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff817e5736)
Location: include/net/netlink.h:540
Inline: True
Inline callers:
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
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
Direct callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/fib_rules.c (ffffffff817f40da)
Location: include/net/netlink.h:540
Inline: True
```
```
In net/core/lwtunnel.c (ffffffff817f8c6e)
Location: include/net/netlink.h:540
Inline: True
```
```
In net/sched/sch_api.c (ffffffff817ff56c)
Location: include/net/netlink.h:540
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81801cfa)
Location: include/net/netlink.h:540
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81803f78)
Location: include/net/netlink.h:540
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/netlink/genetlink.c (ffffffff8180bdd1)
Location: include/net/netlink.h:540
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff81813ac1)
Location: include/net/netlink.h:540
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_metrics.c (ffffffff8184019b)
Location: include/net/netlink.h:540
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff8184f31e)
Location: include/net/netlink.h:540
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8185de7b)
Location: include/net/netlink.h:540
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff8186aa08)
Location: include/net/netlink.h:540
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:__ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff8188e9d4)
Location: include/net/netlink.h:540
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81896a98)
Location: include/net/netlink.h:540
Inline: True
```
```
In net/ipv6/route.c (ffffffff81898e5f)
Location: include/net/netlink.h:540
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff818bfb5e)
Location: include/net/netlink.h:540
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff818c1dd8)
Location: include/net/netlink.h:540
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:__ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff818d69c2)
Location: include/net/netlink.h:540
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818db282)
Location: include/net/netlink.h:540
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818dc09f)
Location: include/net/netlink.h:540
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818dd5c4)
Location: include/net/netlink.h:540
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818de5c4)
Location: include/net/netlink.h:540
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/dcb/dcbnl.c (ffffffff818e3b49)
Location: include/net/netlink.h:540
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/switchdev/switchdev.c (ffffffff818e5b52)
Location: include/net/netlink.h:540
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_fdb_dump_cb
```
**Symbols:**

```
ffffffff817dfbb0-ffffffff817dfbd5: nlmsg_trim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void nlmsg_trim(struct sk_buff *skb, const void *mark);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8115face)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/net_namespace.c (ffffffff8183c298)
Location: include/net/netlink.h:546
Inline: True
```
```
In net/core/neighbour.c (ffffffff81857edd)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff818607d6)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
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
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
Direct callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/fib_rules.c (ffffffff8186f83f)
Location: include/net/netlink.h:546
Inline: True
```
```
In net/core/lwtunnel.c (ffffffff81876551)
Location: include/net/netlink.h:546
Inline: True
```
```
In net/sched/sch_api.c (ffffffff8187d2e2)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff8187fd6a)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff8188263c)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/netlink/genetlink.c (ffffffff8188ad61)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff81893124)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bf53b)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff818cef4e)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff818ddeab)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff818eb193)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:__ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81910024)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81917f07)
Location: include/net/netlink.h:546
Inline: True
```
```
In net/ipv6/route.c (ffffffff8191a165)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81942c2e)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81945718)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:__ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff8195c592)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81960e62)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81961c82)
Location: include/net/netlink.h:546
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819631b4)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819641c4)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/dcb/dcbnl.c (ffffffff8196995f)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
**Symbols:**

```
ffffffff8185a480-ffffffff8185a4a5: nlmsg_trim (STB_LOCAL)
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
In kernel/taskstats.c (ffffffff8116ea1e)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/net_namespace.c (ffffffff81886cf8)
Location: include/net/netlink.h:546
Inline: True
```
```
In net/core/neighbour.c (ffffffff818a308e)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff818aa686)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/fib_rules.c (ffffffff818c102a)
Location: include/net/netlink.h:546
Inline: True
```
```
In net/core/lwtunnel.c (ffffffff818c7c65)
Location: include/net/netlink.h:546
Inline: True
```
```
In net/sched/sch_api.c (ffffffff818cf8fe)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff818d5064)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff818d6133)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/netlink/genetlink.c (ffffffff818de38b)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff818e731d)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_metrics.c (ffffffff81915131)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81925d15)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81934a26)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff81941978)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (ffffffff819445e1)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81967434)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff8196f5c7)
Location: include/net/netlink.h:546
Inline: True
```
```
In net/ipv6/route.c (ffffffff8197229a)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff8199bb44)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff8199d208)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff819b5db2)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819ba67a)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819bb45f)
Location: include/net/netlink.h:546
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819bca04)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819bda64)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/dcb/dcbnl.c (ffffffff819c36e4)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff819cb14d)
Location: include/net/netlink.h:546
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
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
In kernel/taskstats.c (ffffffff8117c4ee)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
```
```
In net/core/net_namespace.c (ffffffff818a741f)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff818c5ad1)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff818d0523)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/fib_rules.c (ffffffff818e9e37)
Location: include/net/netlink.h:689
Inline: True
```
```
In net/core/lwtunnel.c (ffffffff818f0dc5)
Location: include/net/netlink.h:689
Inline: True
```
```
In net/sched/sch_api.c (ffffffff818fac98)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff818fdf2e)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff8190292b)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/netlink/genetlink.c (ffffffff8190ad4b)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff819141d3)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_metrics.c (ffffffff81943aee)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81954cb2)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81964373)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff81971227)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (ffffffff81974881)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff8199ca41)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff819a5154)
Location: include/net/netlink.h:689
Inline: True
```
```
In net/ipv6/route.c (ffffffff819a79f2)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff819d2714)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff819d3d65)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff819ed06f)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f1eba)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f26df)
Location: include/net/netlink.h:689
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f3c54)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f4c04)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/dcb/dcbnl.c (ffffffff819fa6f4)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a03c19)
Location: include/net/netlink.h:689
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
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
In kernel/taskstats.c (ffffffff81189398)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
```
```
In net/core/net_namespace.c (ffffffff818f24bf)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81911af2)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff8191d3d1)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/fib_rules.c (ffffffff81939899)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/core/lwtunnel.c (ffffffff81942770)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/core/devlink.c (ffffffff81951a72)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/sched/sch_api.c (ffffffff8195a558)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff8195d8c3)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81963b91)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/netlink/genetlink.c (ffffffff8196c144)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff819712bd)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a848f)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff819b8c22)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff819c9ea6)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff819da9af)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (ffffffff819de3c2)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81a08c1c)
Location: include/net/netlink.h:923
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
In net/ipv6/addrlabel.c (ffffffff81a115f4)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a14071)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81a41553)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff81a41fe4)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81a5c25d)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a611b5)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a61a60)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a630aa)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a640ba)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/dcb/dcbnl.c (ffffffff81a69c68)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a72ef2)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In kernel/taskstats.c (ffffffff811952ce)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
```
```
In net/core/net_namespace.c (ffffffff8192440f)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81944162)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff8194fa04)
Location: include/net/netlink.h:923
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
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/fib_rules.c (ffffffff8196c766)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff819765b5)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwtunnel.c (ffffffff81977695)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/core/devlink.c (ffffffff81983b9d)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/sched/sch_api.c (ffffffff819909f8)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81993e80)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff8199a711)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/netlink/genetlink.c (ffffffff819a2af4)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff819a7cda)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff819df15f)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff819ef922)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81a00a66)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff81a1189e)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (ffffffff81a15462)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81a3f32c)
Location: include/net/netlink.h:923
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
In net/ipv6/addrlabel.c (ffffffff81a48214)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a4ac61)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81a781d3)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff81a78c44)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81a92e89)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a97dda)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a985ed)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a99c65)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a9ac45)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/dcb/dcbnl.c (ffffffff81aa0b18)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81aa96d2)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In kernel/taskstats.c (ffffffff811aa853)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
```
```
In net/core/net_namespace.c (ffffffff819f80df)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81a141e9)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81a21222)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_link_af
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_vf_ports_fill
  - net/core/rtnetlink.c:rtnl_vf_ports_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_slave_info_fill
```
```
In net/core/fib_rules.c (ffffffff81a4061a)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81a4b342)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_stats_put
  - net/core/drop_monitor.c:net_dm_stats_put
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_entries_put
  - net/core/drop_monitor.c:net_dm_hw_entries_put
```
```
In net/core/lwtunnel.c (ffffffff81a4c45b)
Location: include/net/netlink.h:975
Inline: True
```
```
In net/core/devlink.c (ffffffff81a5f73d)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_trap_policer_stats_put
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_metadata_put
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_dpipe_header_put
  - net/core/devlink.c:devlink_dpipe_header_put
  - net/core/devlink.c:devlink_dpipe_fields_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/core/bpf_sk_storage.c (ffffffff81a61964)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put_all
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81a68b38)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a718d0)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81a7366f)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_terse
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:tcf_dump_walker
```
```
In net/netlink/genetlink.c (ffffffff81a7c6f0)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netlink/policy.c (ffffffff81a7da82)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
```
```
In net/ethtool/netlink.c (ffffffff81a85a2f)
Location: include/net/netlink.h:975
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81a875b3)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81a881d0)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81a8d26e)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
```
```
In net/ipv4/route.c (ffffffff81a91444)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acbf6f)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81addd6a)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81aefbf5)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af99be)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_erspan
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_geneve
```
```
In net/ipv4/nexthop.c (ffffffff81afaf2c)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81b04c5e)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv4/ipmr_base.c (ffffffff81b06452)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81b34fac)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifmcaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b3f0b4)
Location: include/net/netlink.h:975
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b451c5)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81b721a3)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff81b7456e)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff81b8e199)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b936fa)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b93d19)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b954b5)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b96415)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/dcb/dcbnl.c (ffffffff81b9c0d6)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba5ac2)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff81bb2af4)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb393c)
Location: include/net/netlink.h:975
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
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
In kernel/taskstats.c (ffffffff811a7e03)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
```
```
In drivers/thermal/thermal_netlink.c (ffffffff8195f791)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/net_namespace.c (ffffffff819f7b3f)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81a14491)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81a1f7af)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_link_af
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_vf_ports_fill
  - net/core/rtnetlink.c:rtnl_vf_ports_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_slave_info_fill
```
```
In net/core/fib_rules.c (ffffffff81a4331a)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81a50f72)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_stats_put
  - net/core/drop_monitor.c:net_dm_stats_put
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_entries_put
  - net/core/drop_monitor.c:net_dm_hw_entries_put
```
```
In net/core/lwtunnel.c (ffffffff81a5213e)
Location: include/net/netlink.h:988
Inline: True
```
```
In net/core/devlink.c (ffffffff81a67f2d)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_trap_policer_stats_put
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_metadata_put
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_dpipe_header_put
  - net/core/devlink.c:devlink_dpipe_header_put
  - net/core/devlink.c:devlink_dpipe_fields_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_function_attrs_put
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/core/bpf_sk_storage.c (ffffffff81a6a24e)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put_all
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81a7125a)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a7a350)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81a7c26f)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:tcf_dump_walker
  - net/sched/act_api.c:tcf_action_dump_terse
```
```
In net/netlink/genetlink.c (ffffffff81a85acb)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netlink/policy.c (ffffffff81a87423)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81a8f3bc)
Location: include/net/netlink.h:988
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81a90f2e)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81a91b5e)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/pause.c (ffffffff81a95618)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_put_stats
```
```
In net/ethtool/cabletest.c (ffffffff81a969ae)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
```
```
In net/ethtool/tunnels.c (ffffffff81a978af)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ipv4/route.c (ffffffff81a9b2c5)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad7f39)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81aeab4a)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81afcb35)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b0710e)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_erspan
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_geneve
```
```
In net/ipv4/nexthop.c (ffffffff81b085fc)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81b12dce)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv4/ipmr_base.c (ffffffff81b14642)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81b43bd1)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifmcaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b4db34)
Location: include/net/netlink.h:988
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b53b68)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81b80f03)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff81b832de)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff81b9de42)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81ba334a)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba395f)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ba5125)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ba6085)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/dcb/dcbnl.c (ffffffff81babde6)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81bb4f98)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff81bc6f29)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc7bd1)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
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
In kernel/taskstats.c (ffffffff811a8723)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81942cf5)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/net_namespace.c (ffffffff819ddcbf)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff819fae21)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81a0687f)
Location: include/net/netlink.h:988
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
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
```
```
In net/core/fib_rules.c (ffffffff81a2807a)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81a35edf)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81a37a53)
Location: include/net/netlink.h:988
Inline: True
```
```
In net/core/devlink.c (ffffffff81a4302f)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/core/bpf_sk_storage.c (ffffffff81a529ad)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81a59a2a)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a5f180)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81a64ea0)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:tcf_dump_walker
  - net/sched/act_api.c:tcf_action_dump_terse
```
```
In net/netlink/genetlink.c (ffffffff81a6f46e)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netlink/policy.c (ffffffff81a704f3)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81a78d3d)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/ethtool/bitset.c (ffffffff81a7a72c)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81a7b6ff)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/pause.c (ffffffff81a7f195)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81a80477)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
```
```
In net/ethtool/tunnels.c (ffffffff81a8130e)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81a815e6)
Location: include/net/netlink.h:988
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81a82219)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
```
```
In net/ipv4/route.c (ffffffff81a866e5)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac30a9)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81ad628a)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae837a)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af2917)
Location: include/net/netlink.h:988
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81af6f45)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff81b009c4)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv4/ipmr_base.c (ffffffff81b0243e)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81b31831)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b3b5c4)
Location: include/net/netlink.h:988
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b4112d)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81b6fb03)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff81b71f60)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/ipv6/seg6_local.c (ffffffff81b7d41d)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/wireless/wext-core.c (ffffffff81b8cf42)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b9246a)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b92a7f)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b9426a)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b951fa)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/dcb/dcbnl.c (ffffffff81b9af86)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba3f74)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff81bb7c59)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb9327)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
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
In kernel/taskstats.c (ffffffff811d2123)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
```
```
In drivers/thermal/thermal_netlink.c (ffffffff819e77c6)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/net_namespace.c (ffffffff81a8df52)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81aaca61)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81ab8cdf)
Location: include/net/netlink.h:988
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
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
```
```
In net/core/fib_rules.c (ffffffff81adce1a)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81aebad1)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81aed87e)
Location: include/net/netlink.h:988
Inline: True
```
```
In net/core/devlink.c (ffffffff81af949f)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_function_attrs_put
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/core/bpf_sk_storage.c (ffffffff81b0b41d)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81b12aea)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81b18040)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81b1e170)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:tcf_dump_walker
  - net/sched/act_api.c:tcf_action_dump_terse
```
```
In net/netlink/genetlink.c (ffffffff81b2820e)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netlink/policy.c (ffffffff81b29c43)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81b32f0d)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/ethtool/bitset.c (ffffffff81b34b3c)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81b35ae8)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/pause.c (ffffffff81b391f5)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81b3a247)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
```
```
In net/ethtool/tunnels.c (ffffffff81b3b05e)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81b3b366)
Location: include/net/netlink.h:988
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81b3bdd9)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
```
```
In net/ipv4/route.c (ffffffff81b40e25)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b80c92)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81b94fba)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba82ab)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb2e27)
Location: include/net/netlink.h:988
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81bb68bb)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff81bc2016)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv4/ipmr_base.c (ffffffff81bc4328)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81bf78d1)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81c01de4)
Location: include/net/netlink.h:988
Inline: True
```
```
In net/ipv6/route.c (ffffffff81c08e03)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81c37c53)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ioam6.c (ffffffff81c3945c)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/ipv6/ip6mr.c (ffffffff81c3c410)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/ipv6/seg6_local.c (ffffffff81c485de)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/wireless/wext-core.c (ffffffff81c592e2)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81c5ec0a)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81c5f21f)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81c60a0a)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81c61a2a)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/dcb/dcbnl.c (ffffffff81c669f4)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81c718d4)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff81c871a9)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81c88797)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void nlmsg_trim(struct sk_buff *skb, const void *mark);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff81206966)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81b4d090)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/net_namespace.c (ffffffff81c03bc7)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81c25a76)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81c3321b)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
Direct callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
```
```
In net/core/fib_rules.c (ffffffff81c5e466)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81c6e412)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81c7015a)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_fill_encap
```
```
In net/core/devlink.c (ffffffff81c7c3b7)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_function_attrs_put
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/core/bpf_sk_storage.c (ffffffff81c917ec)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81c9b0b6)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81ca25ce)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81ca5b65)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_dump_walker
  - net/sched/act_api.c:tcf_action_dump_terse
```
```
In net/netlink/genetlink.c (ffffffff81cb11fe)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netlink/policy.c (ffffffff81cb2e5b)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81cbeac7)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_fill_reply_header
```
```
In net/ethtool/bitset.c (ffffffff81cc00ec)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81cc1311)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/pause.c (ffffffff81cc4ff5)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81cc613c)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
```
```
In net/ethtool/tunnels.c (ffffffff81cc6fc5)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81cc729a)
Location: include/net/netlink.h:988
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81cc8031)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stat_put
```
```
In net/ipv4/route.c (ffffffff81ccd95a)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d110a4)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81d26c1b)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3ae3b)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d44a20)
Location: include/net/netlink.h:988
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81d4a5fb)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff81d5636c)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv4/ipmr_base.c (ffffffff81d591d7)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81d90d7c)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81d9bd38)
Location: include/net/netlink.h:988
Inline: True
```
```
In net/ipv6/route.c (ffffffff81da38c7)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81dd581c)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ioam6.c (ffffffff81dd6d19)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/ipv6/ip6mr.c (ffffffff81dda7d2)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/ipv6/seg6_local.c (ffffffff81de7b13)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/wireless/wext-core.c (ffffffff81dfaa4f)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81e00e4c)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e015f6)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81e02efe)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81e0401e)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/dcb/dcbnl.c (ffffffff81e09958)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81e15467)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff81e2d9dd)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81e2f2d0)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
```
```
In net/mctp/device.c (ffffffff81e37fe2)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_fill_addrinfo
```
```
In net/mctp/route.c (ffffffff81e39347)
Location: include/net/netlink.h:988
Inline: True
```
```
In net/mctp/neigh.c (ffffffff81e3b4b9)
Location: include/net/netlink.h:988
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_getneigh
```
**Symbols:**

```
ffffffff81c2ab10-ffffffff81c2ab47: nlmsg_trim (STB_LOCAL)
ffffffff81d44a20-ffffffff81d44a57: nlmsg_trim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void nlmsg_trim(struct sk_buff *skb, const void *mark);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8124e9d6)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81ce4d90)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/net_namespace.c (ffffffff81db3277)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81dd7cb6)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81de663b)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
Direct callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
```
```
In net/core/fib_rules.c (ffffffff81e14b8a)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81e2609b)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81e280ca)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_fill_encap
```
```
In net/core/devlink.c (ffffffff81e40c87)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_cmd_selftests_run
  - net/core/devlink.c:devlink_nl_cmd_selftests_run
  - net/core/devlink.c:devlink_nl_selftests_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/core/bpf_sk_storage.c (ffffffff81e4cda1)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81e57546)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81e5efee)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81e63c1a)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_dump_walker
  - net/sched/act_api.c:tcf_action_dump_terse
```
```
In net/netlink/genetlink.c (ffffffff81e6f1d0)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netlink/policy.c (ffffffff81e70efb)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81e7d5e7)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_fill_reply_header
```
```
In net/ethtool/bitset.c (ffffffff81e7ecfc)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81e80051)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/pause.c (ffffffff81e844f5)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81e8572c)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
```
```
In net/ethtool/tunnels.c (ffffffff81e86615)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81e8691a)
Location: include/net/netlink.h:1037
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81e87751)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stat_put
```
```
In net/ipv4/route.c (ffffffff81e8dad7)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed6e34)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81eee5bb)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81f037ab)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0dbd0)
Location: include/net/netlink.h:1037
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81f13c9b)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff81f203cc)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv4/ipmr_base.c (ffffffff81f237e1)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81f5f49c)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81f6a9cf)
Location: include/net/netlink.h:1037
Inline: True
```
```
In net/ipv6/route.c (ffffffff81f72d07)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81fa6fac)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ioam6.c (ffffffff81fa86b9)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/ipv6/ip6mr.c (ffffffff81fac4f2)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/ipv6/seg6_local.c (ffffffff81fbc00e)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_flavors
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/wireless/wext-core.c (ffffffff81fcf1f7)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81fd5cac)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd6456)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81fd7e3e)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81fd8fde)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/dcb/dcbnl.c (ffffffff81fdeda8)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81fec3c7)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff82005f6d)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff820079ca)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
```
```
In net/mctp/device.c (ffffffff82011212)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_fill_addrinfo
```
```
In net/mctp/route.c (ffffffff82012607)
Location: include/net/netlink.h:1037
Inline: True
```
```
In net/mctp/neigh.c (ffffffff82014b79)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_getneigh
```
**Symbols:**

```
ffffffff81ddd8b0-ffffffff81ddd8e7: nlmsg_trim (STB_LOCAL)
ffffffff81f0dbd0-ffffffff81f0dc07: nlmsg_trim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void nlmsg_trim(struct sk_buff *skb, const void *mark);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff81265d86)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81d4d360)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/net_namespace.c (ffffffff81e23847)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81e48a82)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81e5760d)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_port_fill
  - net/core/rtnetlink.c:rtnl_port_fill
  - net/core/rtnetlink.c:rtnl_port_fill
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
Direct callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
```
```
In net/core/netdev-genl.c (ffffffff81e7ced6)
Location: include/net/netlink.h:1038
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81e8849a)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81e9b63b)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81e9d706)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_fill_encap
```
```
In net/core/bpf_sk_storage.c (ffffffff81ea84c6)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81eb35b5)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81eb76fe)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81ebfcb0)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_dump_walker
  - net/sched/act_api.c:tcf_action_dump_terse
```
```
In net/netlink/genetlink.c (ffffffff81ecb2e0)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netlink/policy.c (ffffffff81ecd01b)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81ed9ba7)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_fill_reply_header
```
```
In net/ethtool/bitset.c (ffffffff81edb2ef)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81edc78a)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/pause.c (ffffffff81ee108b)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81ee205c)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
```
```
In net/ethtool/tunnels.c (ffffffff81ee2ff7)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81ee336a)
Location: include/net/netlink.h:1038
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81ee43a1)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stat_put
```
```
In net/ethtool/mm.c (ffffffff81ee5b3c)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/ethtool/mm.c:mm_fill_reply
```
```
In net/ipv4/route.c (ffffffff81eec209)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f35ddf)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81f4df79)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81f6318b)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6d880)
Location: include/net/netlink.h:1038
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81f7396b)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff81f7fecc)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv4/ipmr_base.c (ffffffff81f8332e)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81fbf1ca)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81fcaa02)
Location: include/net/netlink.h:1038
Inline: True
```
```
In net/ipv6/route.c (ffffffff81fd2dfd)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff8200780c)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ioam6.c (ffffffff82009049)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/ipv6/ip6mr.c (ffffffff8200cc92)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/ipv6/seg6_local.c (ffffffff8201c90e)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_flavors
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/devlink/leftover.c (ffffffff8203784b)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_trap_policer_fill
  - net/devlink/leftover.c:devlink_nl_trap_policer_fill
  - net/devlink/leftover.c:devlink_nl_trap_group_fill
  - net/devlink/leftover.c:devlink_nl_trap_group_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
  - net/devlink/leftover.c:devlink_nl_region_notify_build
  - net/devlink/leftover.c:devlink_nl_param_value_fill_one
  - net/devlink/leftover.c:devlink_dpipe_entry_put
  - net/devlink/leftover.c:devlink_dpipe_entry_put
  - net/devlink/leftover.c:devlink_dpipe_entry_put
  - net/devlink/leftover.c:devlink_dpipe_entry_put
  - net/devlink/leftover.c:devlink_dpipe_entry_put
  - net/devlink/leftover.c:devlink_dpipe_table_put
  - net/devlink/leftover.c:devlink_dpipe_table_put
  - net/devlink/leftover.c:devlink_dpipe_action_put
  - net/devlink/leftover.c:devlink_dpipe_match_put
  - net/devlink/leftover.c:devlink_nl_port_fill
  - net/devlink/leftover.c:devlink_nl_port_fill
```
```
In net/devlink/dev.c (ffffffff82045aaa)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_cmd_selftests_run
  - net/devlink/dev.c:devlink_nl_cmd_selftests_run
  - net/devlink/dev.c:devlink_nl_selftests_fill
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/dev.c:devlink_info_version_put
  - net/devlink/dev.c:devlink_nl_cmd_reload
  - net/devlink/dev.c:devlink_nl_fill
  - net/devlink/dev.c:devlink_nl_fill
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
```
```
In net/devlink/health.c (ffffffff8204842b)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
```
```
In net/wireless/wext-core.c (ffffffff8204ae22)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8205196c)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82052116)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82053b2e)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff82054cae)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/dcb/dcbnl.c (ffffffff8205b017)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff82068667)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff820822e4)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff82083d0b)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
```
```
In net/mctp/device.c (ffffffff8208dfd2)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_fill_addrinfo
```
```
In net/mctp/route.c (ffffffff8208f3f7)
Location: include/net/netlink.h:1038
Inline: True
```
```
In net/mctp/neigh.c (ffffffff82091999)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_getneigh
```
```
In net/handshake/netlink.c (ffffffff8209259d)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_genl_notify
```
```
In net/handshake/tlshd.c (ffffffff820941b4)
Location: include/net/netlink.h:1038
Inline: True
Inline callers:
  - net/handshake/tlshd.c:tls_handshake_accept
  - net/handshake/tlshd.c:tls_handshake_accept
```
**Symbols:**

```
ffffffff81e4e600-ffffffff81e4e637: nlmsg_trim (STB_LOCAL)
ffffffff81f6d880-ffffffff81f6d8b7: nlmsg_trim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void nlmsg_trim(struct sk_buff *skb, const void *mark);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8127fc46)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81e03e50)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In drivers/dpll/dpll_netlink.c (ffffffff81ebb9b6)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - drivers/dpll/dpll_netlink.c:dpll_nl_device_get_dumpit
  - drivers/dpll/dpll_netlink.c:dpll_nl_pin_get_dumpit
  - drivers/dpll/dpll_netlink.c:dpll_pin_event_send
  - drivers/dpll/dpll_netlink.c:dpll_device_event_send
  - drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_parents
  - drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_freq
```
```
In net/core/net_namespace.c (ffffffff81ee17a7)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81f07642)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81f16963)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_port_fill
  - net/core/rtnetlink.c:rtnl_port_fill
  - net/core/rtnetlink.c:rtnl_port_fill
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
Direct callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
```
```
In net/core/netdev-genl.c (ffffffff81f3d2aa)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/core/netdev-genl.c:netdev_nl_queue_fill_one
  - net/core/netdev-genl.c:netdev_nl_napi_fill_one
  - net/core/netdev-genl.c:netdev_nl_dev_fill
  - net/core/netdev-genl.c:netdev_nl_dev_fill
```
```
In net/core/page_pool_user.c (ffffffff81f453a0)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/core/page_pool_user.c:page_pool_nl_fill
  - net/core/page_pool_user.c:page_pool_nl_stats_fill
  - net/core/page_pool_user.c:page_pool_nl_stats_fill
```
```
In net/core/fib_rules.c (ffffffff81f4a4aa)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81f5ddab)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81f5fe86)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_fill_encap
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6af86)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81f760c5)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81f7a4ae)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81f82e60)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_dump_walker
  - net/sched/act_api.c:tcf_action_dump_terse
```
```
In net/netlink/genetlink.c (ffffffff81f8e7d0)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netlink/policy.c (ffffffff81f9084b)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81f9d9e3)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_fill_reply_header
```
```
In net/ethtool/bitset.c (ffffffff81f9f0af)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81fa055a)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/pause.c (ffffffff81fa4f1b)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81fa5eec)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
```
```
In net/ethtool/tunnels.c (ffffffff81fa6e24)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81fa714a)
Location: include/net/netlink.h:1059
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81fa8181)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stat_put
```
```
In net/ethtool/mm.c (ffffffff81fa991c)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/ethtool/mm.c:mm_fill_reply
```
```
In net/ipv4/route.c (ffffffff81fb0259)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffbe8f)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff820140a9)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8202975b)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82033fd0)
Location: include/net/netlink.h:1059
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff8203a15b)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff8204654c)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv4/ipmr_base.c (ffffffff820499ae)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff8208c662)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff820981a2)
Location: include/net/netlink.h:1059
Inline: True
```
```
In net/ipv6/route.c (ffffffff820a070d)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff820d669c)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ioam6.c (ffffffff820d7fb9)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/ipv6/ip6mr.c (ffffffff820dbc62)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/ipv6/seg6_local.c (ffffffff820eb73e)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_flavors
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/devlink/netlink.c (ffffffff82101792)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/devlink/netlink.c:devlink_nl_put_nested_handle
```
```
In net/devlink/dev.c (ffffffff821053ed)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_selftests_run_doit
  - net/devlink/dev.c:devlink_nl_selftests_run_doit
  - net/devlink/dev.c:devlink_nl_selftests_fill
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/dev.c:devlink_info_version_put
  - net/devlink/dev.c:devlink_nl_reload_doit
  - net/devlink/dev.c:devlink_nl_fill
  - net/devlink/dev.c:devlink_nl_fill
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
```
```
In net/devlink/port.c (ffffffff82106a83)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_nl_port_fill
  - net/devlink/port.c:devlink_nl_port_function_attrs_put
```
```
In net/devlink/sb.c (ffffffff82108993)
Location: include/net/netlink.h:1059
Inline: True
```
```
In net/devlink/dpipe.c (ffffffff8210b82a)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_table_put
  - net/devlink/dpipe.c:devlink_dpipe_table_put
  - net/devlink/dpipe.c:devlink_dpipe_action_put
  - net/devlink/dpipe.c:devlink_dpipe_match_put
```
```
In net/devlink/resource.c (ffffffff8210c6ca)
Location: include/net/netlink.h:1059
Inline: True
```
```
In net/devlink/param.c (ffffffff8210dbf1)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/devlink/param.c:devlink_nl_param_value_fill_one
```
```
In net/devlink/region.c (ffffffff82111492)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/devlink/region.c:devlink_nl_region_read_dumpit
  - net/devlink/region.c:devlink_nl_region_read_dumpit
  - net/devlink/region.c:devlink_nl_region_notify_build
```
```
In net/devlink/health.c (ffffffff82114597)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_health_reporter_dump_get_dumpit
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
```
```
In net/devlink/trap.c (ffffffff82114c7b)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_nl_trap_policer_fill
  - net/devlink/trap.c:devlink_nl_trap_policer_fill
  - net/devlink/trap.c:devlink_nl_trap_group_fill
  - net/devlink/trap.c:devlink_nl_trap_group_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
```
```
In net/devlink/rate.c (ffffffff82118a07)
Location: include/net/netlink.h:1059
Inline: True
```
```
In net/devlink/linecard.c (ffffffff82119a47)
Location: include/net/netlink.h:1059
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff8211d2a6)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8212413c)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8212495d)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8212630e)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff8212758e)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/dcb/dcbnl.c (ffffffff8212df8a)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_getapptrust
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff8213b8e7)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff8215791c)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff8215c06b)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_addr_dumpit
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
```
```
In net/mctp/device.c (ffffffff82164492)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_fill_addrinfo
```
```
In net/mctp/route.c (ffffffff821658d7)
Location: include/net/netlink.h:1059
Inline: True
```
```
In net/mctp/neigh.c (ffffffff82167f39)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_getneigh
```
```
In net/handshake/netlink.c (ffffffff82168e83)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_genl_notify
```
```
In net/handshake/tlshd.c (ffffffff8216aad4)
Location: include/net/netlink.h:1059
Inline: True
Inline callers:
  - net/handshake/tlshd.c:tls_handshake_accept
  - net/handshake/tlshd.c:tls_handshake_accept
```
**Symbols:**

```
ffffffff81f0d360-ffffffff81f0d397: nlmsg_trim (STB_LOCAL)
ffffffff82033fd0-ffffffff82034007: nlmsg_trim (STB_LOCAL)
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
In kernel/taskstats.c (ffff80001020d59c)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
```
```
In net/core/net_namespace.c (ffff800010bbfd60)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffff800010be4048)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffff800010bf16f4)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/fib_rules.c (ffff800010c12fb8)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/core/drop_monitor.c (ffff800010c1ca88)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwtunnel.c (ffff800010c1e1dc)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/core/devlink.c (ffff800010c2c1d4)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/sched/sch_api.c (ffff800010c3cc64)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffff800010c40370)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffff800010c47910)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/netlink/genetlink.c (ffff800010c51dcc)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffff800010c575a8)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffff800010c924cc)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffff800010ca5798)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffff800010cb9248)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffff800010cc9f7c)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (ffff800010cd0bd8)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffff800010d02808)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffff800010d0b500)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/ipv6/route.c (ffff800010d0dc90)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffff800010d41760)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffff800010d423bc)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffff800010d60ca0)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffff800010d673b4)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d67da0)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffff800010d696ec)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffff800010d6a834)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/dcb/dcbnl.c (ffff800010d71b60)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffff800010d7d128)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
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
In kernel/taskstats.c (c044bf5c)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
```
```
In net/core/net_namespace.c (c0cdb85c)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (c0cfe4e8)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (c0d09ec0)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/fib_rules.c (c0d2a968)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (c0d34a18)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwtunnel.c (c0d35d48)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/core/devlink.c (c0d42760)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/sched/sch_api.c (c0d4e9dc)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (c0d522a0)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (c0d586fc)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/netlink/genetlink.c (c0d61484)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (c0d671f8)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (c0da0c34)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (c0db20f4)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (c0dc47dc)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (c0dd5f1c)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (c0ddaf58)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (c0e08630)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (c0e114d0)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/ipv6/route.c (c0e145b4)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (c0e44154)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (c0e44cfc)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (c0e60630)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (c0e65bc4)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_protocols_cb
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (c0e66610)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/netlabel/netlabel_cipso_v4.c (c0e67cd8)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (c0e68db8)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/dcb/dcbnl.c (c0e6efa8)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (c0e77f24)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
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
In kernel/taskstats.c (c00000000028b580)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/net_namespace.c (c000000000c991f8)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (c000000000cc74e0)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (c000000000cd627c)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/fib_rules.c (c000000000d00040)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/core/drop_monitor.c (c000000000d0dab4)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwtunnel.c (c000000000d0f94c)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/core/devlink.c (c000000000d22d40)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/sched/sch_api.c (c000000000d37dc0)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (c000000000d3b04c)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (c000000000d44848)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/netlink/genetlink.c (c000000000d508fc)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (c000000000d58bb0)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (c000000000da2b90)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (c000000000db9780)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (c000000000dd1f40)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (c000000000de93ec)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (c000000000deee20)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (c000000000e2a140)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (c000000000e35be0)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/ipv6/route.c (c000000000e39b60)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (c000000000e76010)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (c000000000e77230)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (c000000000e9c050)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (c000000000ea3140)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (c000000000ea46d0)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (c000000000ea6528)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (c000000000ea7ba8)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/dcb/dcbnl.c (c000000000eb08c8)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (c000000000ebcd38)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In kernel/taskstats.c (ffffffe00016e640)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/net_namespace.c (ffffffe00074d61e)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffe00076aa02)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffe00077346a)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/fib_rules.c (ffffffe00078e988)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/core/drop_monitor.c (ffffffe000796964)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwtunnel.c (ffffffe000797bb2)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/core/devlink.c (ffffffe0007a37aa)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/sched/sch_api.c (ffffffe0007ad4aa)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffe0007afde0)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffe0007b5610)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/netlink/genetlink.c (ffffffe0007bce42)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffe0007c1844)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f2290)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffe000801048)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffe00080fe18)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffe00081f45a)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (ffffffe0008226c0)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffe00084abf2)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffe000852744)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/ipv6/route.c (ffffffe000855926)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffe00087ce24)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffe00087da44)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffe00089601c)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffe00089ac24)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089b256)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffe00089c644)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffe00089d3f4)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/dcb/dcbnl.c (ffffffe0008a273c)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffe0008aad24)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
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
In kernel/taskstats.c (ffffffff8118d8ee)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
```
```
In net/core/net_namespace.c (ffffffff818c440f)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff818e4132)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff818ef9d4)
Location: include/net/netlink.h:923
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
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/fib_rules.c (ffffffff8190c736)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81916585)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwtunnel.c (ffffffff81917505)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/core/devlink.c (ffffffff81923a0d)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/sched/sch_api.c (ffffffff81930868)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81933cf0)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff8193a581)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/netlink/genetlink.c (ffffffff81942964)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff81947b4a)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197efcf)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff8198f6c2)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff819a0806)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff819b11b7)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (ffffffff819b4af2)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff819de9bc)
Location: include/net/netlink.h:923
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
In net/ipv6/addrlabel.c (ffffffff819e78a4)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/ipv6/route.c (ffffffff819ea2f1)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81a17863)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff81a182d4)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81a32519)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a3716a)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a3797d)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a38ff5)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a39fd5)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/dcb/dcbnl.c (ffffffff81a3fea8)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a48a62)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In kernel/taskstats.c (ffffffff81180a0e)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
```
```
In drivers/net/vxlan.c (ffffffff8176cf60)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_fdb_info
```
```
In net/core/net_namespace.c (ffffffff8187e34f)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff8189df72)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff818a9814)
Location: include/net/netlink.h:923
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
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/fib_rules.c (ffffffff818c64f6)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff818d0335)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwtunnel.c (ffffffff818d12b5)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/core/devlink.c (ffffffff818dd7bd)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/sched/sch_api.c (ffffffff818ea368)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff818ed7f0)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff818f4081)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/netlink/genetlink.c (ffffffff818fc454)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff8190163a)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81938a8f)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81949182)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8195a2c6)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff8196d7e7)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (ffffffff81971122)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff8199b77c)
Location: include/net/netlink.h:923
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
In net/ipv6/addrlabel.c (ffffffff819a4664)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/ipv6/route.c (ffffffff819a70b1)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff819d4623)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff819d5094)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff819ef709)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f3d8a)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f459d)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f5c15)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f6bf5)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/dcb/dcbnl.c (ffffffff819fca98)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a05652)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In kernel/taskstats.c (ffffffff8118b6be)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
```
```
In net/core/net_namespace.c (ffffffff8191540f)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81935162)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81940a04)
Location: include/net/netlink.h:923
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
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/fib_rules.c (ffffffff8195d766)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff819675b5)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwtunnel.c (ffffffff81968695)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/core/devlink.c (ffffffff81974b9d)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/sched/sch_api.c (ffffffff819819f8)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81984e80)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff8198b711)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/netlink/genetlink.c (ffffffff81993af4)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819ae7d9)
Location: include/net/netlink.h:923
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
In net/ipv4/route.c (ffffffff819b231a)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e979f)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff819f9f62)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0b0a6)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff81a1ba57)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (ffffffff81a1f392)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81a4943c)
Location: include/net/netlink.h:923
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
In net/ipv6/addrlabel.c (ffffffff81a52324)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a54d71)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81a822e3)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff81a82d54)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81a9e0c9)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aa301a)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aa382d)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81aa4ea5)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81aa5e85)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/dcb/dcbnl.c (ffffffff81aabd58)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ab4912)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In kernel/taskstats.c (ffffffff8119902e)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
```
```
In net/core/net_namespace.c (ffffffff819365ef)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81956872)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81962314)
Location: include/net/netlink.h:923
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
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/fib_rules.c (ffffffff8197f9b6)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81989845)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwtunnel.c (ffffffff8198aa4f)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/core/devlink.c (ffffffff8199708d)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/sched/sch_api.c (ffffffff819a3f52)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff819a7670)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff819adf81)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/netlink/genetlink.c (ffffffff819b65ee)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff819bb9da)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f352f)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81a04272)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81a15886)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff81a269ae)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (ffffffff81a2a862)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81a5535c)
Location: include/net/netlink.h:923
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
In net/ipv6/addrlabel.c (ffffffff81a5e314)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a60d61)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81a8ebf3)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff81a8f624)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81aaa2c9)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aaf38a)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aafc4d)
Location: include/net/netlink.h:923
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ab1225)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ab2225)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/dcb/dcbnl.c (ffffffff81ab80c8)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ac0cb2)
Location: include/net/netlink.h:923
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
