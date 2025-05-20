# Function: <code>nla_nest_start</code>

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
In kernel/taskstats.c (ffffffff8113e7bb)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff81726086)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff8172cfb6)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
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
```
```
In net/core/lwtunnel.c (ffffffff8173e2a9)
Location: include/net/netlink.h:1176
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81743c14)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81745c94)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff81747262)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump
```
```
In net/sched/ematch.c (ffffffff817495b6)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (ffffffff8174fd56)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
```
```
In net/ipv4/tcp_metrics.c (ffffffff817812ac)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff8179d9b8)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff817a855b)
Location: include/net/netlink.h:1176
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff817cb8a1)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/ip6mr.c (ffffffff817f90a5)
Location: include/net/netlink.h:1176
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8180d6f1)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8180feee)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff81812bf0)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getcap
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
In kernel/taskstats.c (ffffffff81146deb)
Location: include/net/netlink.h:1200
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff8178fb36)
Location: include/net/netlink.h:1200
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff817991a7)
Location: include/net/netlink.h:1200
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
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/lwtunnel.c (ffffffff817aac19)
Location: include/net/netlink.h:1200
Inline: True
```
```
In net/sched/sch_api.c (ffffffff817b0bfb)
Location: include/net/netlink.h:1200
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff817b2b6e)
Location: include/net/netlink.h:1200
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff817b4bbf)
Location: include/net/netlink.h:1200
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffffffff817b6526)
Location: include/net/netlink.h:1200
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (ffffffff817bc3bd)
Location: include/net/netlink.h:1200
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff817ee772)
Location: include/net/netlink.h:1200
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff8180b4fa)
Location: include/net/netlink.h:1200
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff81815c3a)
Location: include/net/netlink.h:1200
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff818388ca)
Location: include/net/netlink.h:1200
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/ip6mr.c (ffffffff81868891)
Location: include/net/netlink.h:1200
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8187fb45)
Location: include/net/netlink.h:1200
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818825be)
Location: include/net/netlink.h:1200
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff818888f8)
Location: include/net/netlink.h:1200
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
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
In kernel/taskstats.c (ffffffff81150c3b)
Location: include/net/netlink.h:1210
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff817bd3e6)
Location: include/net/netlink.h:1210
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff817c6f57)
Location: include/net/netlink.h:1210
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
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/lwtunnel.c (ffffffff817d99b9)
Location: include/net/netlink.h:1210
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff817da1ee)
Location: include/net/netlink.h:1210
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_fill_lwt_prog
```
```
In net/sched/sch_api.c (ffffffff817e033b)
Location: include/net/netlink.h:1210
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff817e23ee)
Location: include/net/netlink.h:1210
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff817e447f)
Location: include/net/netlink.h:1210
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffffffff817e5fb6)
Location: include/net/netlink.h:1210
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (ffffffff817ebccd)
Location: include/net/netlink.h:1210
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181f182)
Location: include/net/netlink.h:1210
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff8183c60a)
Location: include/net/netlink.h:1210
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff818473ea)
Location: include/net/netlink.h:1210
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8186a3fa)
Location: include/net/netlink.h:1210
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/ip6mr.c (ffffffff8189b6e1)
Location: include/net/netlink.h:1210
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818b43f5)
Location: include/net/netlink.h:1210
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818b6e6e)
Location: include/net/netlink.h:1210
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff818bd118)
Location: include/net/netlink.h:1210
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
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
In kernel/taskstats.c (ffffffff8115323b)
Location: include/net/netlink.h:1222
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff817dbb16)
Location: include/net/netlink.h:1222
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff817e584e)
Location: include/net/netlink.h:1222
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
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/lwtunnel.c (ffffffff817f8c15)
Location: include/net/netlink.h:1222
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff817f93f6)
Location: include/net/netlink.h:1222
Inline: True
```
```
In net/sched/sch_api.c (ffffffff817ff7d4)
Location: include/net/netlink.h:1222
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81801d47)
Location: include/net/netlink.h:1222
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff81803eb7)
Location: include/net/netlink.h:1222
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffffffff81805a46)
Location: include/net/netlink.h:1222
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (ffffffff8180bc2d)
Location: include/net/netlink.h:1222
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff8183fd58)
Location: include/net/netlink.h:1222
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff8185dd61)
Location: include/net/netlink.h:1222
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff8186a9a8)
Location: include/net/netlink.h:1222
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:__ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff8188e953)
Location: include/net/netlink.h:1222
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/route.c (ffffffff81898dde)
Location: include/net/netlink.h:1222
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ip6mr.c (ffffffff818c1abf)
Location: include/net/netlink.h:1222
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__ip6mr_fill_mroute
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818dae17)
Location: include/net/netlink.h:1222
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818dd72d)
Location: include/net/netlink.h:1222
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff818e3adb)
Location: include/net/netlink.h:1222
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
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
In kernel/taskstats.c (ffffffff8115fa3b)
Location: include/net/netlink.h:1277
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff818565b6)
Location: include/net/netlink.h:1277
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff818608ee)
Location: include/net/netlink.h:1277
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
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/lwtunnel.c (ffffffff818764f5)
Location: include/net/netlink.h:1277
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81876d06)
Location: include/net/netlink.h:1277
Inline: True
```
```
In net/sched/sch_api.c (ffffffff8187d578)
Location: include/net/netlink.h:1277
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff8187fdb7)
Location: include/net/netlink.h:1277
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff81882547)
Location: include/net/netlink.h:1277
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffffffff81884766)
Location: include/net/netlink.h:1277
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (ffffffff8188abbd)
Location: include/net/netlink.h:1277
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bf0f9)
Location: include/net/netlink.h:1277
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff818ddd91)
Location: include/net/netlink.h:1277
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff818eb136)
Location: include/net/netlink.h:1277
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:__ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff8190ffa3)
Location: include/net/netlink.h:1277
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/route.c (ffffffff8191a0e4)
Location: include/net/netlink.h:1277
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ip6mr.c (ffffffff819453ff)
Location: include/net/netlink.h:1277
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__ip6mr_fill_mroute
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819609f7)
Location: include/net/netlink.h:1277
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8196331d)
Location: include/net/netlink.h:1277
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff819698eb)
Location: include/net/netlink.h:1277
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
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
In kernel/taskstats.c (ffffffff8116e9ab)
Location: include/net/netlink.h:1277
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff818a1f40)
Location: include/net/netlink.h:1277
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff818aa7be)
Location: include/net/netlink.h:1277
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
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/lwtunnel.c (ffffffff818c7c1f)
Location: include/net/netlink.h:1277
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff818c8165)
Location: include/net/netlink.h:1277
Inline: True
```
```
In net/sched/sch_api.c (ffffffff818cfd1b)
Location: include/net/netlink.h:1277
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff818d4f7b)
Location: include/net/netlink.h:1277
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff818d603e)
Location: include/net/netlink.h:1277
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffffffff818d831f)
Location: include/net/netlink.h:1277
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (ffffffff818de1ec)
Location: include/net/netlink.h:1277
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81914ce9)
Location: include/net/netlink.h:1277
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff8193490d)
Location: include/net/netlink.h:1277
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff8194190d)
Location: include/net/netlink.h:1277
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (ffffffff81944464)
Location: include/net/netlink.h:1277
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff819673b3)
Location: include/net/netlink.h:1277
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/route.c (ffffffff81972220)
Location: include/net/netlink.h:1277
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6_local.c (ffffffff819a861f)
Location: include/net/netlink.h:1277
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819ba192)
Location: include/net/netlink.h:1277
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819bcb6b)
Location: include/net/netlink.h:1277
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff819c366b)
Location: include/net/netlink.h:1277
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff819cb095)
Location: include/net/netlink.h:1277
Inline: True
Inline callers:
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
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8117c47b)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff818c5120)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff818d065b)
Location: include/net/netlink.h:1420
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
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/lwtunnel.c (ffffffff818f0d7f)
Location: include/net/netlink.h:1420
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff818f12d5)
Location: include/net/netlink.h:1420
Inline: True
```
```
In net/sched/sch_api.c (ffffffff818faf84)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff818fdee1)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff8190283c)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffffffff81904b0f)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (ffffffff8190abac)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81943499)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff8196425a)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff819711be)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (ffffffff81974704)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff8199c9c0)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/route.c (ffffffff819a7978)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6_local.c (ffffffff819df16f)
Location: include/net/netlink.h:1420
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f1ae2)
Location: include/net/netlink.h:1420
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f3dbd)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff819fa67b)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a03b58)
Location: include/net/netlink.h:1420
Inline: True
Inline callers:
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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8191d5b9)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
In net/core/rtnetlink.c (ffffffff8194fc05)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/drop_monitor.c (ffffffff81976433)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (ffffffff81983a9d)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
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
In net/core/rtnetlink.c (ffffffff81a21423)
Location: include/net/netlink.h:1770
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/drop_monitor.c (ffffffff81a4a182)
Location: include/net/netlink.h:1770
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_stats_put
  - net/core/drop_monitor.c:net_dm_stats_put
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_entries_put
  - net/core/drop_monitor.c:net_dm_hw_entries_put
```
```
In net/core/devlink.c (ffffffff81a5f556)
Location: include/net/netlink.h:1770
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_policer_stats_put
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_metadata_put
```
```
In net/core/bpf_sk_storage.c (ffffffff81a61817)
Location: include/net/netlink.h:1770
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put_all
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/netlink/genetlink.c (ffffffff81a7c6ac)
Location: include/net/netlink.h:1770
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
```
```
In net/netlink/policy.c (ffffffff81a7d9ae)
Location: include/net/netlink.h:1770
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
```
```
In net/ethtool/netlink.c (ffffffff81a859a0)
Location: include/net/netlink.h:1770
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81a874d5)
Location: include/net/netlink.h:1770
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81a87fcb)
Location: include/net/netlink.h:1770
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81a8d191)
Location: include/net/netlink.h:1770
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb2fb0)
Location: include/net/netlink.h:1770
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
In drivers/thermal/thermal_netlink.c (ffffffff8195f45d)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
```
```
In net/core/rtnetlink.c (ffffffff81a1f9b1)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/drop_monitor.c (ffffffff81a50df2)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_stats_put
  - net/core/drop_monitor.c:net_dm_stats_put
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_entries_put
  - net/core/drop_monitor.c:net_dm_hw_entries_put
```
```
In net/core/devlink.c (ffffffff81a67d46)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_policer_stats_put
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_metadata_put
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/core/bpf_sk_storage.c (ffffffff81a6a0f7)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put_all
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/netlink/genetlink.c (ffffffff81a85a9f)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
```
```
In net/netlink/policy.c (ffffffff81a873ed)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81a8f310)
Location: include/net/netlink.h:1783
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81a90e41)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81a9197b)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/pause.c (ffffffff81a9556d)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_put_stats
```
```
In net/ethtool/cabletest.c (ffffffff81a968d1)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ethtool/tunnels.c (ffffffff81a972ff)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc7440)
Location: include/net/netlink.h:1783
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
In drivers/thermal/thermal_netlink.c (ffffffff819429bd)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
```
```
In net/core/rtnetlink.c (ffffffff81a06a79)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/drop_monitor.c (ffffffff81a35d59)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/devlink.c (ffffffff81a42f84)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/core/bpf_sk_storage.c (ffffffff81a5273c)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/netlink/genetlink.c (ffffffff81a6f443)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
```
```
In net/netlink/policy.c (ffffffff81a704bd)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81a78a10)
Location: include/net/netlink.h:1783
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81a7a64e)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81a7b3ac)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/pause.c (ffffffff81a7f0ec)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81a803a1)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ethtool/tunnels.c (ffffffff81a80c6a)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81a81532)
Location: include/net/netlink.h:1783
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81a8217b)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
```
```
In net/ipv4/nexthop.c (ffffffff81af6c38)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv6/seg6_local.c (ffffffff81b7d2f4)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb88b0)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
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
In drivers/net/wwan/wwan_core.c (ffffffff8191a985)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In drivers/thermal/thermal_netlink.c (ffffffff819e73bd)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
```
```
In net/core/rtnetlink.c (ffffffff81ab8ec7)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/drop_monitor.c (ffffffff81aeb93a)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/devlink.c (ffffffff81af93f4)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/core/bpf_sk_storage.c (ffffffff81b0b1ac)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/netlink/genetlink.c (ffffffff81b281e3)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
```
```
In net/netlink/policy.c (ffffffff81b29c0d)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81b32be0)
Location: include/net/netlink.h:1783
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81b34a5e)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81b357bc)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/pause.c (ffffffff81b3914c)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81b3a171)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ethtool/tunnels.c (ffffffff81b3a9aa)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81b3b2b2)
Location: include/net/netlink.h:1783
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81b3bd3b)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
```
```
In net/ipv4/nexthop.c (ffffffff81bb6568)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv6/seg6_local.c (ffffffff81c484a4)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/mptcp/pm_netlink.c (ffffffff81c87e80)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
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
In drivers/net/wwan/wwan_core.c (ffffffff81a6fddc)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81b4cb8d)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
```
```
In net/core/rtnetlink.c (ffffffff81c33012)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/drop_monitor.c (ffffffff81c6e276)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/devlink.c (ffffffff81c7c300)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/core/bpf_sk_storage.c (ffffffff81c91725)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/netlink/genetlink.c (ffffffff81cb11d7)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
```
```
In net/netlink/policy.c (ffffffff81cb2e2d)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81cbe772)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_fill_reply_header
```
```
In net/ethtool/bitset.c (ffffffff81cc0008)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81cc118c)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/pause.c (ffffffff81cc4f4e)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81cc6061)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ethtool/tunnels.c (ffffffff81cc691c)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81cc71e2)
Location: include/net/netlink.h:1783
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81cc7f8c)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stat_put
```
```
In net/ipv4/nexthop.c (ffffffff81d4a188)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv6/seg6_local.c (ffffffff81de79d5)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/mptcp/pm_netlink.c (ffffffff81e2e780)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
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
In drivers/net/wwan/wwan_core.c (ffffffff81c02c6c)
Location: include/net/netlink.h:1832
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81ce484d)
Location: include/net/netlink.h:1832
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
```
```
In net/core/rtnetlink.c (ffffffff81de6432)
Location: include/net/netlink.h:1832
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/drop_monitor.c (ffffffff81e25efc)
Location: include/net/netlink.h:1832
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/devlink.c (ffffffff81e40bd0)
Location: include/net/netlink.h:1832
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_selftests_run
  - net/core/devlink.c:devlink_nl_selftests_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/core/bpf_sk_storage.c (ffffffff81e4ccc5)
Location: include/net/netlink.h:1832
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/netlink/genetlink.c (ffffffff81e6f1a9)
Location: include/net/netlink.h:1832
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
```
```
In net/netlink/policy.c (ffffffff81e70ecd)
Location: include/net/netlink.h:1832
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81e7d262)
Location: include/net/netlink.h:1832
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_fill_reply_header
```
```
In net/ethtool/bitset.c (ffffffff81e7ec18)
Location: include/net/netlink.h:1832
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81e7fecc)
Location: include/net/netlink.h:1832
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/pause.c (ffffffff81e8444e)
Location: include/net/netlink.h:1832
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81e85651)
Location: include/net/netlink.h:1832
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ethtool/tunnels.c (ffffffff81e85f6c)
Location: include/net/netlink.h:1832
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81e86862)
Location: include/net/netlink.h:1832
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81e876ac)
Location: include/net/netlink.h:1832
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stat_put
```
```
In net/ipv4/nexthop.c (ffffffff81f13818)
Location: include/net/netlink.h:1832
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv6/seg6_local.c (ffffffff81fbbf3d)
Location: include/net/netlink.h:1832
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_flavors
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/dcb/dcbnl.c (ffffffff81fdf6ee)
Location: include/net/netlink.h:1832
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/mptcp/pm_netlink.c (ffffffff82006900)
Location: include/net/netlink.h:1832
Inline: True
Inline callers:
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
In drivers/net/wwan/wwan_core.c (ffffffff81c6831c)
Location: include/net/netlink.h:1833
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81d4ce1d)
Location: include/net/netlink.h:1833
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
```
```
In net/core/rtnetlink.c (ffffffff81e57408)
Location: include/net/netlink.h:1833
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/drop_monitor.c (ffffffff81e9b49c)
Location: include/net/netlink.h:1833
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/bpf_sk_storage.c (ffffffff81ea83e5)
Location: include/net/netlink.h:1833
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/netlink/genetlink.c (ffffffff81ecb2b9)
Location: include/net/netlink.h:1833
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
```
```
In net/netlink/policy.c (ffffffff81eccfed)
Location: include/net/netlink.h:1833
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81ed9822)
Location: include/net/netlink.h:1833
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_fill_reply_header
```
```
In net/ethtool/bitset.c (ffffffff81edb20b)
Location: include/net/netlink.h:1833
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81edc5fc)
Location: include/net/netlink.h:1833
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/pause.c (ffffffff81ee0fe4)
Location: include/net/netlink.h:1833
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81ee1f81)
Location: include/net/netlink.h:1833
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ethtool/tunnels.c (ffffffff81ee28bf)
Location: include/net/netlink.h:1833
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81ee32b2)
Location: include/net/netlink.h:1833
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81ee42fc)
Location: include/net/netlink.h:1833
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stat_put
```
```
In net/ethtool/mm.c (ffffffff81ee59cd)
Location: include/net/netlink.h:1833
Inline: True
Inline callers:
  - net/ethtool/mm.c:mm_fill_reply
```
```
In net/ipv4/nexthop.c (ffffffff81f734e8)
Location: include/net/netlink.h:1833
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv6/seg6_local.c (ffffffff8201c83d)
Location: include/net/netlink.h:1833
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_flavors
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/devlink/leftover.c (ffffffff82037794)
Location: include/net/netlink.h:1833
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_trap_policer_fill
  - net/devlink/leftover.c:devlink_nl_trap_group_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
```
```
In net/devlink/dev.c (ffffffff82045985)
Location: include/net/netlink.h:1833
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_cmd_selftests_run
  - net/devlink/dev.c:devlink_nl_selftests_fill
  - net/devlink/dev.c:devlink_nl_fill
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
```
```
In net/dcb/dcbnl.c (ffffffff8205be64)
Location: include/net/netlink.h:1833
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/mptcp/pm_netlink.c (ffffffff82082ca0)
Location: include/net/netlink.h:1833
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
```
```
In net/handshake/tlshd.c (ffffffff82093f7f)
Location: include/net/netlink.h:1833
Inline: True
Inline callers:
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
In drivers/thermal/thermal_netlink.c (ffffffff81e03a3d)
Location: include/net/netlink.h:1931
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
```
```
In drivers/dpll/dpll_netlink.c (ffffffff81eb8d53)
Location: include/net/netlink.h:1931
Inline: True
Inline callers:
  - drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_dplls
  - drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_parents
  - drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_freq
```
```
In net/core/rtnetlink.c (ffffffff81f16761)
Location: include/net/netlink.h:1931
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/page_pool_user.c (ffffffff81f458a1)
Location: include/net/netlink.h:1931
Inline: True
Inline callers:
  - net/core/page_pool_user.c:page_pool_nl_stats_fill
```
```
In net/core/drop_monitor.c (ffffffff81f5dc0c)
Location: include/net/netlink.h:1931
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6aea5)
Location: include/net/netlink.h:1931
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/netlink/genetlink.c (ffffffff81f8e7a9)
Location: include/net/netlink.h:1931
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
```
```
In net/netlink/policy.c (ffffffff81f9081d)
Location: include/net/netlink.h:1931
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81f9d6e2)
Location: include/net/netlink.h:1931
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_fill_reply_header
```
```
In net/ethtool/bitset.c (ffffffff81f9efcb)
Location: include/net/netlink.h:1931
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81fa03cc)
Location: include/net/netlink.h:1931
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/pause.c (ffffffff81fa4e74)
Location: include/net/netlink.h:1931
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81fa5e11)
Location: include/net/netlink.h:1931
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ethtool/tunnels.c (ffffffff81fa674f)
Location: include/net/netlink.h:1931
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81fa7092)
Location: include/net/netlink.h:1931
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81fa80dc)
Location: include/net/netlink.h:1931
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stat_put
```
```
In net/ethtool/mm.c (ffffffff81fa97ad)
Location: include/net/netlink.h:1931
Inline: True
Inline callers:
  - net/ethtool/mm.c:mm_fill_reply
```
```
In net/ipv4/nexthop.c (ffffffff82039cd8)
Location: include/net/netlink.h:1931
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv6/seg6_local.c (ffffffff820eb66d)
Location: include/net/netlink.h:1931
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_flavors
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/devlink/netlink.c (ffffffff82101685)
Location: include/net/netlink.h:1931
Inline: True
Inline callers:
  - net/devlink/netlink.c:devlink_nl_put_nested_handle
```
```
In net/devlink/dev.c (ffffffff821052c8)
Location: include/net/netlink.h:1931
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_selftests_run_doit
  - net/devlink/dev.c:devlink_nl_selftests_fill
  - net/devlink/dev.c:devlink_nl_fill
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
```
```
In net/devlink/trap.c (ffffffff82114bc4)
Location: include/net/netlink.h:1931
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_nl_trap_policer_fill
  - net/devlink/trap.c:devlink_nl_trap_group_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
```
```
In net/devlink/linecard.c (ffffffff821199d4)
Location: include/net/netlink.h:1931
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff8212f3c9)
Location: include/net/netlink.h:1931
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_getapptrust
```
```
In net/mptcp/pm_netlink.c (ffffffff82158310)
Location: include/net/netlink.h:1931
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
```
```
In net/handshake/tlshd.c (ffffffff8216a89f)
Location: include/net/netlink.h:1931
Inline: True
Inline callers:
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
In net/core/rtnetlink.c (ffff800010bf18cc)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/drop_monitor.c (ffff800010c1c90c)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (ffff800010c2c0fc)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
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
In net/core/rtnetlink.c (c0d0a0b0)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/drop_monitor.c (c0d34818)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (c0d42c84)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
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
In net/core/rtnetlink.c (c000000000cd6488)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/drop_monitor.c (c000000000d0d8e0)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (c000000000d22c14)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
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
In net/core/rtnetlink.c (ffffffe0007735ce)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/drop_monitor.c (ffffffe00079681e)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (ffffffe0007a36ee)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
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
In net/core/rtnetlink.c (ffffffff818efbd5)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/drop_monitor.c (ffffffff81916403)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (ffffffff8192390d)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
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
In drivers/net/vxlan.c (ffffffff8176d8ac)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_fill_info
```
```
In net/core/rtnetlink.c (ffffffff818a9a15)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/drop_monitor.c (ffffffff818d01b3)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (ffffffff818dd6bd)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
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
In net/core/rtnetlink.c (ffffffff81940c05)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/drop_monitor.c (ffffffff81967433)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (ffffffff81974a9d)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff8199a550)
Location: include/net/netlink.h:1703
Inline: True
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199c542)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:__build_packet_message
```
```
In net/netfilter/nf_conntrack_proto_tcp.c (ffffffff819a51eb)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_tcp.c:tcp_to_nlattr
```
```
In net/netfilter/nf_conntrack_proto_dccp.c (ffffffff819a9a95)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_dccp.c:dccp_to_nlattr
```
```
In net/netfilter/nf_conntrack_proto_sctp.c (ffffffff819aa685)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_sctp.c:sctp_to_nlattr
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819af9d0)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_dump_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_dump_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_dump_tuple
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_glue_build
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_glue_build
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_glue_build
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_conntrack_event
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_conntrack_event
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_fill_info
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_fill_info
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_ct_synproxy
  - net/netfilter/nf_conntrack_netlink.c:dump_ct_seq_adj
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_timestamp
  - net/netfilter/nf_conntrack_netlink.c:dump_counters
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_helpinfo
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_protoinfo
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_tuples_ip
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
In net/core/rtnetlink.c (ffffffff81962515)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/drop_monitor.c (ffffffff819896c3)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (ffffffff81996f8d)
Location: include/net/netlink.h:1703
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
```
</details>
</li>
</ul>

## Differences
