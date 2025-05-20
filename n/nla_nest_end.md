# Function: <code>nla_nest_end</code>

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
In kernel/taskstats.c (ffffffff8113e823)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff817263b9)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff8172d06c)
Location: include/net/netlink.h:1196
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
In net/core/lwtunnel.c (ffffffff8173e2ff)
Location: include/net/netlink.h:1196
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81743c74)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81745cd4)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff817472e9)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump
```
```
In net/sched/ematch.c (ffffffff817497a7)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (ffffffff8174fe39)
Location: include/net/netlink.h:1196
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
In net/ipv4/tcp_metrics.c (ffffffff81781348)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff8179db14)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff817a8605)
Location: include/net/netlink.h:1196
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff817cb8de)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/ip6mr.c (ffffffff817f915a)
Location: include/net/netlink.h:1196
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8180d7fe)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8180ff5f)
Location: include/net/netlink.h:1196
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff81812d2e)
Location: include/net/netlink.h:1196
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
In kernel/taskstats.c (ffffffff81146e58)
Location: include/net/netlink.h:1220
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff8178fea0)
Location: include/net/netlink.h:1220
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81799247)
Location: include/net/netlink.h:1220
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
In net/core/lwtunnel.c (ffffffff817aac6c)
Location: include/net/netlink.h:1220
Inline: True
```
```
In net/sched/sch_api.c (ffffffff817b0c57)
Location: include/net/netlink.h:1220
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff817b2beb)
Location: include/net/netlink.h:1220
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff817b4c18)
Location: include/net/netlink.h:1220
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffffffff817b6716)
Location: include/net/netlink.h:1220
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (ffffffff817bc470)
Location: include/net/netlink.h:1220
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
In net/ipv4/tcp_metrics.c (ffffffff817ee80e)
Location: include/net/netlink.h:1220
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff8180b67e)
Location: include/net/netlink.h:1220
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff81815ce4)
Location: include/net/netlink.h:1220
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81838906)
Location: include/net/netlink.h:1220
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/ip6mr.c (ffffffff8186893f)
Location: include/net/netlink.h:1220
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8187fc52)
Location: include/net/netlink.h:1220
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8188262f)
Location: include/net/netlink.h:1220
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff818889ce)
Location: include/net/netlink.h:1220
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
In kernel/taskstats.c (ffffffff81150ca8)
Location: include/net/netlink.h:1230
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff817bd750)
Location: include/net/netlink.h:1230
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff817c6ff7)
Location: include/net/netlink.h:1230
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
In net/core/lwtunnel.c (ffffffff817d9a0c)
Location: include/net/netlink.h:1230
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff817da247)
Location: include/net/netlink.h:1230
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_fill_lwt_prog
```
```
In net/sched/sch_api.c (ffffffff817e0397)
Location: include/net/netlink.h:1230
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff817e246a)
Location: include/net/netlink.h:1230
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff817e44d8)
Location: include/net/netlink.h:1230
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffffffff817e61a6)
Location: include/net/netlink.h:1230
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (ffffffff817ebd80)
Location: include/net/netlink.h:1230
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
In net/ipv4/tcp_metrics.c (ffffffff8181f21e)
Location: include/net/netlink.h:1230
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff8183c797)
Location: include/net/netlink.h:1230
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff81847494)
Location: include/net/netlink.h:1230
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8186a436)
Location: include/net/netlink.h:1230
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/ip6mr.c (ffffffff8189b78f)
Location: include/net/netlink.h:1230
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818b4502)
Location: include/net/netlink.h:1230
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818b6edf)
Location: include/net/netlink.h:1230
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff818bd1ee)
Location: include/net/netlink.h:1230
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
In kernel/taskstats.c (ffffffff8115329d)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff817dbe7d)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff817e58ed)
Location: include/net/netlink.h:1242
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
In net/core/lwtunnel.c (ffffffff817f8ca0)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff817f944c)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/sched/sch_api.c (ffffffff817ff822)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81801dbb)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff81803f0f)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffffffff81805c37)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (ffffffff8180bcdb)
Location: include/net/netlink.h:1242
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
In net/ipv4/tcp_metrics.c (ffffffff8183fde0)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff8185dea2)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff8186ae4c)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:__ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff8188e98c)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/route.c (ffffffff818990b4)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ip6mr.c (ffffffff818c1b70)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__ip6mr_fill_mroute
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818daf23)
Location: include/net/netlink.h:1242
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818dd797)
Location: include/net/netlink.h:1242
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff818e3b9c)
Location: include/net/netlink.h:1242
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
In kernel/taskstats.c (ffffffff8115fa9d)
Location: include/net/netlink.h:1297
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff81856916)
Location: include/net/netlink.h:1297
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81860990)
Location: include/net/netlink.h:1297
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
In net/core/lwtunnel.c (ffffffff81876583)
Location: include/net/netlink.h:1297
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81876d5c)
Location: include/net/netlink.h:1297
Inline: True
```
```
In net/sched/sch_api.c (ffffffff8187d5c6)
Location: include/net/netlink.h:1297
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff8187fe2b)
Location: include/net/netlink.h:1297
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff818825a6)
Location: include/net/netlink.h:1297
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffffffff8188495a)
Location: include/net/netlink.h:1297
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (ffffffff8188ac6b)
Location: include/net/netlink.h:1297
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
In net/ipv4/tcp_metrics.c (ffffffff818bf186)
Location: include/net/netlink.h:1297
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff818dded2)
Location: include/net/netlink.h:1297
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff818eb5f7)
Location: include/net/netlink.h:1297
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:__ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff8190ffdc)
Location: include/net/netlink.h:1297
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/route.c (ffffffff8191a3ba)
Location: include/net/netlink.h:1297
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ip6mr.c (ffffffff819454b0)
Location: include/net/netlink.h:1297
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__ip6mr_fill_mroute
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81960b03)
Location: include/net/netlink.h:1297
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81963387)
Location: include/net/netlink.h:1297
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff819699b6)
Location: include/net/netlink.h:1297
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
In kernel/taskstats.c (ffffffff8116e9ed)
Location: include/net/netlink.h:1297
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff818a2266)
Location: include/net/netlink.h:1297
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff818aa866)
Location: include/net/netlink.h:1297
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
In net/core/lwtunnel.c (ffffffff818c7c97)
Location: include/net/netlink.h:1297
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff818c81bc)
Location: include/net/netlink.h:1297
Inline: True
```
```
In net/sched/sch_api.c (ffffffff818cfd5d)
Location: include/net/netlink.h:1297
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff818d4fd7)
Location: include/net/netlink.h:1297
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff818d609f)
Location: include/net/netlink.h:1297
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffffffff818d84d7)
Location: include/net/netlink.h:1297
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (ffffffff818de29a)
Location: include/net/netlink.h:1297
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
In net/ipv4/tcp_metrics.c (ffffffff81914d79)
Location: include/net/netlink.h:1297
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff81934bbb)
Location: include/net/netlink.h:1297
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff81941d00)
Location: include/net/netlink.h:1297
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (ffffffff8194450d)
Location: include/net/netlink.h:1297
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff819673ec)
Location: include/net/netlink.h:1297
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/route.c (ffffffff819724ce)
Location: include/net/netlink.h:1297
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6_local.c (ffffffff819a869f)
Location: include/net/netlink.h:1297
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819ba2a6)
Location: include/net/netlink.h:1297
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819bcbd7)
Location: include/net/netlink.h:1297
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff819c373b)
Location: include/net/netlink.h:1297
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
In net/ncsi/ncsi-netlink.c (ffffffff819cb0df)
Location: include/net/netlink.h:1297
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
In kernel/taskstats.c (ffffffff8117c4bd)
Location: include/net/netlink.h:1440
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff818c5446)
Location: include/net/netlink.h:1440
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff818d0703)
Location: include/net/netlink.h:1440
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
In net/core/lwtunnel.c (ffffffff818f0df7)
Location: include/net/netlink.h:1440
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff818f132c)
Location: include/net/netlink.h:1440
Inline: True
```
```
In net/sched/sch_api.c (ffffffff818fafd2)
Location: include/net/netlink.h:1440
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff818fdea7)
Location: include/net/netlink.h:1440
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff8190289d)
Location: include/net/netlink.h:1440
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffffffff81904cc7)
Location: include/net/netlink.h:1440
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (ffffffff8190ac5a)
Location: include/net/netlink.h:1440
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
In net/ipv4/tcp_metrics.c (ffffffff81943529)
Location: include/net/netlink.h:1440
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff81964508)
Location: include/net/netlink.h:1440
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff819714fd)
Location: include/net/netlink.h:1440
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (ffffffff819747ad)
Location: include/net/netlink.h:1440
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff8199c9f9)
Location: include/net/netlink.h:1440
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/route.c (ffffffff819a7c26)
Location: include/net/netlink.h:1440
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6_local.c (ffffffff819df1ef)
Location: include/net/netlink.h:1440
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f1bf6)
Location: include/net/netlink.h:1440
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f3e29)
Location: include/net/netlink.h:1440
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff819fa74b)
Location: include/net/netlink.h:1440
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
In net/ncsi/ncsi-netlink.c (ffffffff81a03bab)
Location: include/net/netlink.h:1440
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
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8118935f)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff8191149e)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff8191d597)
Location: include/net/netlink.h:1718
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
```
```
In net/core/lwtunnel.c (ffffffff8194279e)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81942fcc)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/core/devlink.c (ffffffff8194ecdf)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
```
```
In net/sched/sch_api.c (ffffffff8195a9d0)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff8195d8a0)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff81963b02)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffffffff81965f1a)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (ffffffff8196c049)
Location: include/net/netlink.h:1718
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
In net/ipv4/tcp_metrics.c (ffffffff819a7aef)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff819ca067)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff819dac80)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (ffffffff819de2ed)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81a08bd1)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/route.c (ffffffff81a1440c)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6_local.c (ffffffff81a4dd61)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a6078f)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a63287)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff81a69cc1)
Location: include/net/netlink.h:1718
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
In net/ncsi/ncsi-netlink.c (ffffffff81a72e82)
Location: include/net/netlink.h:1718
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
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8119529c)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff81943538)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff8194fbe5)
Location: include/net/netlink.h:1718
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
```
```
In net/core/drop_monitor.c (ffffffff81976496)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwtunnel.c (ffffffff819776c7)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81977f7c)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/core/devlink.c (ffffffff81983ae7)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
```
```
In net/sched/sch_api.c (ffffffff81990e80)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81993e59)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff8199a682)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffffffff8199c9aa)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (ffffffff819a29f9)
Location: include/net/netlink.h:1718
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
In net/ipv4/tcp_metrics.c (ffffffff819deb7f)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff81a00c27)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff81a11b29)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (ffffffff81a1538d)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81a3f2e1)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/route.c (ffffffff81a4affc)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6_local.c (ffffffff81a84931)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a973bf)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a99e37)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff81aa0b6b)
Location: include/net/netlink.h:1718
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
In net/ncsi/ncsi-netlink.c (ffffffff81aa9662)
Location: include/net/netlink.h:1718
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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff811aa821)
Location: include/net/netlink.h:1785
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff81a13b78)
Location: include/net/netlink.h:1785
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81a21403)
Location: include/net/netlink.h:1785
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_link_af
  - net/core/rtnetlink.c:rtnl_fill_link_af
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vf
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
In net/core/drop_monitor.c (ffffffff81a4a1d4)
Location: include/net/netlink.h:1785
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_stats_put
  - net/core/drop_monitor.c:net_dm_stats_put
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_entries_put
  - net/core/drop_monitor.c:net_dm_hw_entries_put
```
```
In net/core/lwtunnel.c (ffffffff81a4c49f)
Location: include/net/netlink.h:1785
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81a4c6ec)
Location: include/net/netlink.h:1785
Inline: True
```
```
In net/core/devlink.c (ffffffff81a5f5a8)
Location: include/net/netlink.h:1785
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_policer_stats_put
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_metadata_put
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_dpipe_header_put
  - net/core/devlink.c:devlink_dpipe_header_put
  - net/core/devlink.c:devlink_dpipe_fields_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
```
```
In net/core/bpf_sk_storage.c (ffffffff81a618e1)
Location: include/net/netlink.h:1785
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put_all
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81a68e90)
Location: include/net/netlink.h:1785
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a718a7)
Location: include/net/netlink.h:1785
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff81a735e0)
Location: include/net/netlink.h:1785
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:tcf_dump_walker
```
```
In net/sched/ematch.c (ffffffff81a75b26)
Location: include/net/netlink.h:1785
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (ffffffff81a7c750)
Location: include/net/netlink.h:1785
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netlink/policy.c (ffffffff81a7dccc)
Location: include/net/netlink.h:1785
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
```
```
In net/ethtool/netlink.c (ffffffff81a859f4)
Location: include/net/netlink.h:1785
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81a8745f)
Location: include/net/netlink.h:1785
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81a880ed)
Location: include/net/netlink.h:1785
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81a8d229)
Location: include/net/netlink.h:1785
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acbb9f)
Location: include/net/netlink.h:1785
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff81aed381)
Location: include/net/netlink.h:1785
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_add_multipath
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af98fb)
Location: include/net/netlink.h:1785
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_erspan
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_geneve
```
```
In net/ipv4/ipmr.c (ffffffff81b04b38)
Location: include/net/netlink.h:1785
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_vif
```
```
In net/ipv4/ipmr_base.c (ffffffff81b0637d)
Location: include/net/netlink.h:1785
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81b34f61)
Location: include/net/netlink.h:1785
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/route.c (ffffffff81b45551)
Location: include/net/netlink.h:1785
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6_local.c (ffffffff81b7f904)
Location: include/net/netlink.h:1785
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b93491)
Location: include/net/netlink.h:1785
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b958b7)
Location: include/net/netlink.h:1785
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff81b9c129)
Location: include/net/netlink.h:1785
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
In net/ncsi/ncsi-netlink.c (ffffffff81ba5a24)
Location: include/net/netlink.h:1785
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff81bb2c8e)
Location: include/net/netlink.h:1785
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb3053)
Location: include/net/netlink.h:1785
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
In kernel/taskstats.c (ffffffff811a7dd1)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In drivers/thermal/thermal_netlink.c (ffffffff8195f491)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
```
```
In net/core/neighbour.c (ffffffff81a13e98)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81a1f98f)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_link_af
  - net/core/rtnetlink.c:rtnl_fill_link_af
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vf
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
In net/core/drop_monitor.c (ffffffff81a50e44)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_stats_put
  - net/core/drop_monitor.c:net_dm_stats_put
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_entries_put
  - net/core/drop_monitor.c:net_dm_hw_entries_put
```
```
In net/core/lwtunnel.c (ffffffff81a520e1)
Location: include/net/netlink.h:1798
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81a5236c)
Location: include/net/netlink.h:1798
Inline: True
```
```
In net/core/devlink.c (ffffffff81a67d98)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_policer_stats_put
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_metadata_put
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_dpipe_header_put
  - net/core/devlink.c:devlink_dpipe_header_put
  - net/core/devlink.c:devlink_dpipe_fields_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_function_attrs_put
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/core/bpf_sk_storage.c (ffffffff81a6a1c6)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put_all
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81a715c5)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a7a327)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff81a7c1e0)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:tcf_dump_walker
```
```
In net/sched/ematch.c (ffffffff81a7e8d6)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (ffffffff81a85a52)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netlink/policy.c (ffffffff81a87454)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81a8f381)
Location: include/net/netlink.h:1798
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81a90de4)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81a91a8c)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/pause.c (ffffffff81a955df)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_put_stats
```
```
In net/ethtool/cabletest.c (ffffffff81a96969)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
```
```
In net/ethtool/tunnels.c (ffffffff81a973d5)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad7b5f)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff81afa4f1)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_add_multipath
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b0704b)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_erspan
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_geneve
```
```
In net/ipv4/ipmr.c (ffffffff81b12ca8)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_vif
```
```
In net/ipv4/ipmr_base.c (ffffffff81b1456d)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81b43b86)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/route.c (ffffffff81b53ef4)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6_local.c (ffffffff81b8e9b4)
Location: include/net/netlink.h:1798
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81ba30e1)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ba550c)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff81babe39)
Location: include/net/netlink.h:1798
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
In net/ncsi/ncsi-netlink.c (ffffffff81bb4efa)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff81bc70c2)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc74e4)
Location: include/net/netlink.h:1798
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
In kernel/taskstats.c (ffffffff811a86f1)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In drivers/thermal/thermal_netlink.c (ffffffff819429f1)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
```
```
In net/core/neighbour.c (ffffffff819fa708)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81a06a57)
Location: include/net/netlink.h:1798
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
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
```
```
In net/core/drop_monitor.c (ffffffff81a35db4)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81a37a16)
Location: include/net/netlink.h:1798
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81a37b4c)
Location: include/net/netlink.h:1798
Inline: True
```
```
In net/core/devlink.c (ffffffff81a42fd6)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/core/bpf_sk_storage.c (ffffffff81a52802)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81a59f85)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a5f157)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff81a64e11)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:tcf_dump_walker
```
```
In net/sched/ematch.c (ffffffff81a67736)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (ffffffff81a6f3f6)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netlink/policy.c (ffffffff81a70523)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81a78a7e)
Location: include/net/netlink.h:1798
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81a7a5e1)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81a7b4d4)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/pause.c (ffffffff81a7f17a)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81a80436)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
```
```
In net/ethtool/tunnels.c (ffffffff81a80d40)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81a815cc)
Location: include/net/netlink.h:1798
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81a821e0)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac2cff)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae84bc)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af27b2)
Location: include/net/netlink.h:1798
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81af6d16)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff81b00b26)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_vif
```
```
In net/ipv4/ipmr_base.c (ffffffff81b0236d)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81b317e6)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/route.c (ffffffff81b414c9)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6_local.c (ffffffff81b7d3dc)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b92201)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b94667)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff81b9afd6)
Location: include/net/netlink.h:1798
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
In net/ncsi/ncsi-netlink.c (ffffffff81ba3ed6)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff81bb7df1)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb897e)
Location: include/net/netlink.h:1798
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
In kernel/taskstats.c (ffffffff811d20f1)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In drivers/net/wwan/wwan_core.c (ffffffff8191aa26)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In drivers/thermal/thermal_netlink.c (ffffffff819e73f1)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
```
```
In net/core/neighbour.c (ffffffff81aabd78)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81ab8ea5)
Location: include/net/netlink.h:1798
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
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
```
```
In net/core/drop_monitor.c (ffffffff81aeb995)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81aed841)
Location: include/net/netlink.h:1798
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81aed99c)
Location: include/net/netlink.h:1798
Inline: True
```
```
In net/core/devlink.c (ffffffff81af9446)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_function_attrs_put
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/core/bpf_sk_storage.c (ffffffff81b0b272)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81b13055)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81b18017)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff81b1e0e1)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:tcf_dump_walker
```
```
In net/sched/ematch.c (ffffffff81b20c16)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (ffffffff81b28196)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netlink/policy.c (ffffffff81b29c73)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81b32c4e)
Location: include/net/netlink.h:1798
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81b349f1)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81b357ef)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/pause.c (ffffffff81b391da)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81b3a206)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
```
```
In net/ethtool/tunnels.c (ffffffff81b3aa80)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81b3b34c)
Location: include/net/netlink.h:1798
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81b3bda0)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b808b0)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba83fe)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb2cc2)
Location: include/net/netlink.h:1798
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81bb6646)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff81bc1ee5)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_vif
```
```
In net/ipv4/ipmr_base.c (ffffffff81bc424f)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81bf7886)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/route.c (ffffffff81c0916d)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6_local.c (ffffffff81c4859d)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81c5e9a1)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81c60e60)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff81c66a48)
Location: include/net/netlink.h:1798
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
In net/ncsi/ncsi-netlink.c (ffffffff81c71836)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff81c87347)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81c87f4e)
Location: include/net/netlink.h:1798
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
In kernel/taskstats.c (ffffffff81206936)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81a6fe7e)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81b4cbbf)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
```
```
In net/core/neighbour.c (ffffffff81c24add)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81c330d8)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
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
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
```
```
In net/core/drop_monitor.c (ffffffff81c6e2cf)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81c701af)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_fill_encap
```
```
In net/core/lwt_bpf.c (ffffffff81c7085c)
Location: include/net/netlink.h:1798
Inline: True
```
```
In net/core/devlink.c (ffffffff81c7c350)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_function_attrs_put
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/core/bpf_sk_storage.c (ffffffff81c917a0)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81c99cba)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81ca25b4)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff81ca5ac2)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_dump_walker
```
```
In net/sched/ematch.c (ffffffff81ca95a4)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (ffffffff81cb1182)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netlink/policy.c (ffffffff81cb2e97)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81cbe7f8)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_fill_reply_header
```
```
In net/ethtool/bitset.c (ffffffff81cbffa0)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81cc11be)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/pause.c (ffffffff81cc4fdc)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81cc60f6)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
```
```
In net/ethtool/tunnels.c (ffffffff81cc69f2)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81cc727e)
Location: include/net/netlink.h:1798
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81cc7fef)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stat_put
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d10c8b)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3ad68)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d464ca)
Location: include/net/netlink.h:1798
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81d4a273)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff81d5622a)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_vif
```
```
In net/ipv4/ipmr_base.c (ffffffff81d590e8)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81d90d31)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/route.c (ffffffff81da3c0b)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6_local.c (ffffffff81de7acc)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81e00bd4)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81e033d7)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff81e0993c)
Location: include/net/netlink.h:1798
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
In net/ncsi/ncsi-netlink.c (ffffffff81e153d3)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff81e2db88)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81e2e85e)
Location: include/net/netlink.h:1798
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
```
```
In net/mctp/route.c (ffffffff81e392ce)
Location: include/net/netlink.h:1798
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
In kernel/taskstats.c (ffffffff8124e9a6)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c02d0e)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81ce487f)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
```
```
In net/core/neighbour.c (ffffffff81dd6e06)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81de64f8)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
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
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
```
```
In net/core/drop_monitor.c (ffffffff81e25f55)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81e2811f)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_fill_encap
```
```
In net/core/lwt_bpf.c (ffffffff81e2885c)
Location: include/net/netlink.h:1847
Inline: True
```
```
In net/core/devlink.c (ffffffff81e40c20)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_cmd_selftests_run
  - net/core/devlink.c:devlink_nl_selftests_fill
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/core/bpf_sk_storage.c (ffffffff81e4cd50)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81e55ff0)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81e5efd4)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff81e63b77)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_dump_walker
```
```
In net/sched/ematch.c (ffffffff81e664e4)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (ffffffff81e6f15c)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netlink/policy.c (ffffffff81e70f37)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81e7d2e4)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_fill_reply_header
```
```
In net/ethtool/bitset.c (ffffffff81e7ebb0)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81e7fefe)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/pause.c (ffffffff81e844dc)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81e856e6)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
```
```
In net/ethtool/tunnels.c (ffffffff81e8604b)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81e868fe)
Location: include/net/netlink.h:1847
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81e8770f)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stat_put
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed6a0b)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff81f036d8)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f8ca)
Location: include/net/netlink.h:1847
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81f13903)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff81f2028a)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_vif
```
```
In net/ipv4/ipmr_base.c (ffffffff81f236ed)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81f5f451)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/route.c (ffffffff81f7304b)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6_local.c (ffffffff81fbbf82)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_flavors
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81fd5a24)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81fd8357)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff81fded8c)
Location: include/net/netlink.h:1847
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
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81fec333)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff82006118)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff820069de)
Location: include/net/netlink.h:1847
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
```
```
In net/mctp/route.c (ffffffff8201258e)
Location: include/net/netlink.h:1847
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
In kernel/taskstats.c (ffffffff81265d56)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c683be)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81d4ce4f)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
```
```
In net/core/neighbour.c (ffffffff81e47c36)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81e574ce)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnl_port_fill
  - net/core/rtnetlink.c:rtnl_port_fill
  - net/core/rtnetlink.c:rtnl_port_fill
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
```
```
In net/core/drop_monitor.c (ffffffff81e9b4f5)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81e9d733)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_fill_encap
```
```
In net/core/lwt_bpf.c (ffffffff81e9de7c)
Location: include/net/netlink.h:1848
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff81ea8470)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81eb237b)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81eb76e4)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff81ebfc0d)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_dump_walker
```
```
In net/sched/ematch.c (ffffffff81ec2414)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (ffffffff81ecb26c)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netlink/policy.c (ffffffff81ecd057)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81ed98a4)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_fill_reply_header
```
```
In net/ethtool/bitset.c (ffffffff81edb1a0)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81edc62e)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/pause.c (ffffffff81ee1072)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81ee2016)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
```
```
In net/ethtool/tunnels.c (ffffffff81ee299e)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81ee334e)
Location: include/net/netlink.h:1848
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81ee435f)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stat_put
```
```
In net/ethtool/mm.c (ffffffff81ee5b23)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/ethtool/mm.c:mm_fill_reply
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f35a41)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff81f630b8)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6f5ba)
Location: include/net/netlink.h:1848
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81f735d3)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff81f7fd8a)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_vif
```
```
In net/ipv4/ipmr_base.c (ffffffff81f8323a)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81fbf17f)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/route.c (ffffffff81fd3141)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6_local.c (ffffffff8201c882)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_flavors
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/devlink/leftover.c (ffffffff820377e4)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_trap_policer_fill
  - net/devlink/leftover.c:devlink_nl_trap_group_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
  - net/devlink/leftover.c:devlink_nl_param_value_fill_one
  - net/devlink/leftover.c:devlink_dpipe_entry_ctx_close
  - net/devlink/leftover.c:devlink_dpipe_entry_put
  - net/devlink/leftover.c:devlink_dpipe_entry_put
  - net/devlink/leftover.c:devlink_dpipe_entry_put
  - net/devlink/leftover.c:devlink_dpipe_entry_put
  - net/devlink/leftover.c:devlink_dpipe_entry_put
  - net/devlink/leftover.c:devlink_dpipe_table_put
  - net/devlink/leftover.c:devlink_dpipe_table_put
  - net/devlink/leftover.c:devlink_dpipe_table_put
  - net/devlink/leftover.c:devlink_dpipe_action_put
  - net/devlink/leftover.c:devlink_dpipe_match_put
  - net/devlink/leftover.c:devlink_nl_port_fill
```
```
In net/devlink/dev.c (ffffffff820459c2)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_cmd_selftests_run
  - net/devlink/dev.c:devlink_nl_selftests_fill
  - net/devlink/dev.c:devlink_info_version_put
  - net/devlink/dev.c:devlink_nl_fill
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
```
```
In net/devlink/health.c (ffffffff82047139)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_fmsg_prepare_skb
  - net/devlink/health.c:devlink_nl_health_reporter_fill
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff82051630)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82054027)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff8205afd7)
Location: include/net/netlink.h:1848
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
In net/ncsi/ncsi-netlink.c (ffffffff820685d3)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff8208249c)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff82082d7e)
Location: include/net/netlink.h:1848
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
```
```
In net/mctp/route.c (ffffffff8208f37e)
Location: include/net/netlink.h:1848
Inline: True
```
```
In net/handshake/tlshd.c (ffffffff82093ff9)
Location: include/net/netlink.h:1848
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
In kernel/taskstats.c (ffffffff8127fc16)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81e03a6f)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
```
```
In drivers/dpll/dpll_netlink.c (ffffffff81eb8e0f)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_dplls
  - drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_dplls
  - drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_parents
  - drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_freq
```
```
In net/core/neighbour.c (ffffffff81f068e6)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81f16827)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnl_port_fill
  - net/core/rtnetlink.c:rtnl_port_fill
  - net/core/rtnetlink.c:rtnl_port_fill
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
```
```
In net/core/page_pool_user.c (ffffffff81f45930)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/core/page_pool_user.c:page_pool_nl_stats_fill
```
```
In net/core/drop_monitor.c (ffffffff81f5dc65)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81f5feb3)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_fill_encap
```
```
In net/core/lwt_bpf.c (ffffffff81f605fc)
Location: include/net/netlink.h:1946
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6af30)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81f74e2b)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81f7a494)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff81f82dbd)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_dump_walker
```
```
In net/sched/ematch.c (ffffffff81f85764)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (ffffffff81f8e75c)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netlink/policy.c (ffffffff81f90887)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/ethtool/netlink.c (ffffffff81f9d76c)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_fill_reply_header
```
```
In net/ethtool/bitset.c (ffffffff81f9ef60)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81fa03fe)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/pause.c (ffffffff81fa4f02)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81fa5ea6)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
```
```
In net/ethtool/tunnels.c (ffffffff81fa682e)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81fa712e)
Location: include/net/netlink.h:1946
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81fa813f)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stat_put
```
```
In net/ethtool/mm.c (ffffffff81fa9903)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/ethtool/mm.c:mm_fill_reply
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffbaf1)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff82029688)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82035cea)
Location: include/net/netlink.h:1946
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff82039dc3)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff8204640a)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_vif
```
```
In net/ipv4/ipmr_base.c (ffffffff820498ba)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff8208c617)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/route.c (ffffffff820a0a51)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6_local.c (ffffffff820eb6b2)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_flavors
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/devlink/netlink.c (ffffffff82101749)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/devlink/netlink.c:devlink_nl_put_nested_handle
```
```
In net/devlink/dev.c (ffffffff82105305)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_selftests_run_doit
  - net/devlink/dev.c:devlink_nl_selftests_fill
  - net/devlink/dev.c:devlink_info_version_put
  - net/devlink/dev.c:devlink_nl_fill
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
```
```
In net/devlink/port.c (ffffffff821066ac)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_nl_port_function_attrs_put
```
```
In net/devlink/dpipe.c (ffffffff8210a48d)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/devlink/dpipe.c:devlink_dpipe_entry_ctx_close
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_table_put
  - net/devlink/dpipe.c:devlink_dpipe_table_put
  - net/devlink/dpipe.c:devlink_dpipe_table_put
  - net/devlink/dpipe.c:devlink_dpipe_action_put
  - net/devlink/dpipe.c:devlink_dpipe_match_put
```
```
In net/devlink/resource.c (ffffffff8210c66e)
Location: include/net/netlink.h:1946
Inline: True
```
```
In net/devlink/param.c (ffffffff8210db6c)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/devlink/param.c:devlink_nl_param_value_fill_one
```
```
In net/devlink/region.c (ffffffff821113da)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/devlink/region.c:devlink_nl_region_read_dumpit
  - net/devlink/region.c:devlink_nl_region_read_dumpit
```
```
In net/devlink/health.c (ffffffff82113069)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_fmsg_prepare_skb
  - net/devlink/health.c:devlink_nl_health_reporter_fill
```
```
In net/devlink/trap.c (ffffffff82114c14)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_nl_trap_policer_fill
  - net/devlink/trap.c:devlink_nl_trap_group_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
```
```
In net/devlink/linecard.c (ffffffff82119a93)
Location: include/net/netlink.h:1946
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff82123e00)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82126807)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff8212df4a)
Location: include/net/netlink.h:1946
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
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_getapptrust
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff8213b853)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff82157afa)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff821583ee)
Location: include/net/netlink.h:1946
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
```
```
In net/mctp/route.c (ffffffff8216585e)
Location: include/net/netlink.h:1946
Inline: True
```
```
In net/handshake/tlshd.c (ffffffff8216a919)
Location: include/net/netlink.h:1946
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
In kernel/taskstats.c (ffff80001020d550)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffff800010be2e0c)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffff800010bf18a8)
Location: include/net/netlink.h:1718
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
```
```
In net/core/drop_monitor.c (ffff800010c1c95c)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwtunnel.c (ffff800010c1e204)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/core/lwt_bpf.c (ffff800010c1e80c)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/core/devlink.c (ffff800010c2c118)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
```
```
In net/sched/sch_api.c (ffff800010c3d390)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffff800010c4034c)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffff800010c47870)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffff800010c49c78)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (ffff800010c51cac)
Location: include/net/netlink.h:1718
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
In net/ipv4/tcp_metrics.c (ffff800010c91d20)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffff800010cb91d8)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffff800010cca1b4)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (ffff800010cd0afc)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffff800010d027c8)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/route.c (ffff800010d0e01c)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6_local.c (ffff800010d50980)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffff800010d66a38)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffff800010d698cc)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffff800010d71bbc)
Location: include/net/netlink.h:1718
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
In net/ncsi/ncsi-netlink.c (ffff800010d7d0bc)
Location: include/net/netlink.h:1718
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
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (c044bf40)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (c0cfde10)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (c0d0a098)
Location: include/net/netlink.h:1718
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
```
```
In net/core/drop_monitor.c (c0d34874)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwtunnel.c (c0d35d6c)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/core/lwt_bpf.c (c0d36858)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/core/devlink.c (c0d42ca8)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
```
```
In net/sched/sch_api.c (c0d4ee68)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (c0d5228c)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (c0d58684)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (c0d5aa0c)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (c0d61398)
Location: include/net/netlink.h:1718
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
In net/ipv4/tcp_metrics.c (c0da0a4c)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (c0dc48ec)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (c0dd6194)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (c0ddae6c)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (c0e085dc)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/route.c (c0e1494c)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6_local.c (c0e514e4)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (c0e650bc)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (c0e67ec0)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (c0e6eff8)
Location: include/net/netlink.h:1718
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
In net/ncsi/ncsi-netlink.c (c0e77ed0)
Location: include/net/netlink.h:1718
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
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (c00000000028b510)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (c000000000cc6c4c)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (c000000000cd6460)
Location: include/net/netlink.h:1718
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
```
```
In net/core/drop_monitor.c (c000000000d0d948)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwtunnel.c (c000000000d0f9a0)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/core/lwt_bpf.c (c000000000d108b4)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/core/devlink.c (c000000000d22c3c)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
```
```
In net/sched/sch_api.c (c000000000d36bf4)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (c000000000d3b030)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (c000000000d44770)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (c000000000d4775c)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (c000000000d507b4)
Location: include/net/netlink.h:1718
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
In net/ipv4/tcp_metrics.c (c000000000da2394)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (c000000000dd1eb0)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (c000000000de96bc)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (c000000000deecbc)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (c000000000e2a084)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/route.c (c000000000e3a050)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6_local.c (c000000000e88694)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (c000000000ea2ce4)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (c000000000ea677c)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (c000000000eb0950)
Location: include/net/netlink.h:1718
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
In net/ncsi/ncsi-netlink.c (c000000000ebcc74)
Location: include/net/netlink.h:1718
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
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffe00016e60a)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffe00076a46a)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffe0007735c6)
Location: include/net/netlink.h:1718
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
```
```
In net/core/drop_monitor.c (ffffffe000796866)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwtunnel.c (ffffffe000797bd2)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffe00079848e)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/core/devlink.c (ffffffe0007a3720)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
```
```
In net/sched/sch_api.c (ffffffe0007ad834)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffe0007afd82)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffe0007b557e)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffffffe0007b72dc)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (ffffffe0007bcd80)
Location: include/net/netlink.h:1718
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
In net/ipv4/tcp_metrics.c (ffffffe0007f1db8)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffe00080fee2)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffe00081f656)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (ffffffe00082260c)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffe00084abbe)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/route.c (ffffffe000855c00)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6_local.c (ffffffe000888d9a)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffe00089a3dc)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffe00089c7ba)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffe0008a277a)
Location: include/net/netlink.h:1718
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
In net/ncsi/ncsi-netlink.c (ffffffe0008aacd6)
Location: include/net/netlink.h:1718
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
In kernel/taskstats.c (ffffffff8118d8bc)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff818e3508)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff818efbb5)
Location: include/net/netlink.h:1718
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
```
```
In net/core/drop_monitor.c (ffffffff81916466)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwtunnel.c (ffffffff81917537)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81917dec)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/core/devlink.c (ffffffff81923957)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
```
```
In net/sched/sch_api.c (ffffffff81930cf0)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81933cc9)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff8193a4f2)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffffffff8193c81a)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (ffffffff81942869)
Location: include/net/netlink.h:1718
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
In net/ipv4/tcp_metrics.c (ffffffff8197e9ef)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff819a09c7)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff819b1488)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (ffffffff819b4a1d)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff819de971)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/route.c (ffffffff819ea68c)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6_local.c (ffffffff81a23fc1)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a3674f)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a391c7)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff81a3fefb)
Location: include/net/netlink.h:1718
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
In net/ncsi/ncsi-netlink.c (ffffffff81a489f2)
Location: include/net/netlink.h:1718
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
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff811809dc)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In drivers/net/vxlan.c (ffffffff8176d954)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_fill_info
```
```
In net/core/neighbour.c (ffffffff8189d348)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff818a99f5)
Location: include/net/netlink.h:1718
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
```
```
In net/core/drop_monitor.c (ffffffff818d0216)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwtunnel.c (ffffffff818d12e7)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff818d1b9c)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/core/devlink.c (ffffffff818dd707)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
```
```
In net/sched/sch_api.c (ffffffff818ea7f0)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff818ed7c9)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff818f3ff2)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffffffff818f631a)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (ffffffff818fc359)
Location: include/net/netlink.h:1718
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
In net/ipv4/tcp_metrics.c (ffffffff819384af)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff8195a487)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff8196dab8)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (ffffffff8197104d)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff8199b731)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/route.c (ffffffff819a744c)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6_local.c (ffffffff819e0d81)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f336f)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f5de7)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff819fcaeb)
Location: include/net/netlink.h:1718
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
In net/ncsi/ncsi-netlink.c (ffffffff81a055e2)
Location: include/net/netlink.h:1718
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
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8118b68c)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff81934538)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81940be5)
Location: include/net/netlink.h:1718
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
```
```
In net/core/drop_monitor.c (ffffffff81967496)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwtunnel.c (ffffffff819686c7)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81968f7c)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/core/devlink.c (ffffffff81974ae7)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
```
```
In net/sched/sch_api.c (ffffffff81981e80)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81984e59)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff8198b682)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffffffff8198d9aa)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (ffffffff819939f9)
Location: include/net/netlink.h:1718
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
In net/netfilter/nfnetlink_queue.c (ffffffff8199a5d4)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199c5d5)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:__build_packet_message
```
```
In net/netfilter/nf_conntrack_proto_tcp.c (ffffffff819a52f0)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_tcp.c:tcp_to_nlattr
```
```
In net/netfilter/nf_conntrack_proto_dccp.c (ffffffff819a9b47)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_dccp.c:dccp_to_nlattr
```
```
In net/netfilter/nf_conntrack_proto_sctp.c (ffffffff819aa733)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_sctp.c:sctp_to_nlattr
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819afa03)
Location: include/net/netlink.h:1718
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
```
In net/ipv4/tcp_metrics.c (ffffffff819e91bf)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0b267)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff81a1bd28)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (ffffffff81a1f2bd)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81a493f1)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/route.c (ffffffff81a5510c)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6_local.c (ffffffff81a8ea41)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aa25ff)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81aa5077)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff81aabdab)
Location: include/net/netlink.h:1718
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
In net/ncsi/ncsi-netlink.c (ffffffff81ab48a2)
Location: include/net/netlink.h:1718
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
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff81198ffc)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In net/core/neighbour.c (ffffffff81955c48)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff819624f5)
Location: include/net/netlink.h:1718
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
```
```
In net/core/drop_monitor.c (ffffffff81989726)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwtunnel.c (ffffffff8198aa7c)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff8198b35c)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/core/devlink.c (ffffffff81996fd7)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
```
```
In net/sched/sch_api.c (ffffffff819a43c0)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff819a7649)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffffffff819adef2)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffffffff819b02da)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (ffffffff819b64e9)
Location: include/net/netlink.h:1718
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
In net/ipv4/tcp_metrics.c (ffffffff819f2f1f)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/fib_semantics.c (ffffffff81a15a47)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff81a26c39)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv4/ipmr_base.c (ffffffff81a2a78d)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81a55311)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/route.c (ffffffff81a610fc)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6_local.c (ffffffff81a9b7b1)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aae96f)
Location: include/net/netlink.h:1718
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ab1400)
Location: include/net/netlink.h:1718
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff81ab811b)
Location: include/net/netlink.h:1718
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
In net/ncsi/ncsi-netlink.c (ffffffff81ac0c42)
Location: include/net/netlink.h:1718
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
</ul>

## Differences
