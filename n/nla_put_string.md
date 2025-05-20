# Function: <code>nla_put_string</code>

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
In net/core/neighbour.c (ffffffff817264e6)
Location: include/net/netlink.h:933
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff8172d0db)
Location: include/net/netlink.h:933
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/fib_rules.c (ffffffff81739f0f)
Location: include/net/netlink.h:933
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81743856)
Location: include/net/netlink.h:933
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff8174605e)
Location: include/net/netlink.h:933
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff817480be)
Location: include/net/netlink.h:933
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/netlink/genetlink.c (ffffffff8174fbf1)
Location: include/net/netlink.h:933
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
```
```
In net/ipv4/devinet.c (ffffffff81790bbc)
Location: include/net/netlink.h:933
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff817cb7b9)
Location: include/net/netlink.h:933
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/wireless/wext-core.c (ffffffff81809bf1)
Location: include/net/netlink.h:933
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8180d693)
Location: include/net/netlink.h:933
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8180e81a)
Location: include/net/netlink.h:933
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff818141d8)
Location: include/net/netlink.h:933
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
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
In net/core/neighbour.c (ffffffff817904c8)
Location: include/net/netlink.h:955
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff8179904a)
Location: include/net/netlink.h:955
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/fib_rules.c (ffffffff817a6213)
Location: include/net/netlink.h:955
Inline: True
```
```
In net/sched/sch_api.c (ffffffff817b06f9)
Location: include/net/netlink.h:955
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff817b306e)
Location: include/net/netlink.h:955
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff817b524d)
Location: include/net/netlink.h:955
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/netlink/genetlink.c (ffffffff817bc376)
Location: include/net/netlink.h:955
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/devinet.c (ffffffff817fdeec)
Location: include/net/netlink.h:955
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff818387e9)
Location: include/net/netlink.h:955
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/wireless/wext-core.c (ffffffff8187b6f1)
Location: include/net/netlink.h:955
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8187fa93)
Location: include/net/netlink.h:955
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81880ea9)
Location: include/net/netlink.h:955
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81887098)
Location: include/net/netlink.h:955
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
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
In net/core/neighbour.c (ffffffff817bdd78)
Location: include/net/netlink.h:955
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff817c6dfa)
Location: include/net/netlink.h:955
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/fib_rules.c (ffffffff817d4d80)
Location: include/net/netlink.h:955
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff817da228)
Location: include/net/netlink.h:955
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_fill_lwt_prog
```
```
In net/sched/sch_api.c (ffffffff817dfe39)
Location: include/net/netlink.h:955
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff817e28ee)
Location: include/net/netlink.h:955
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff817e4c1d)
Location: include/net/netlink.h:955
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/netlink/genetlink.c (ffffffff817ebc86)
Location: include/net/netlink.h:955
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/devinet.c (ffffffff8182ee4c)
Location: include/net/netlink.h:955
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff8186a319)
Location: include/net/netlink.h:955
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/wireless/wext-core.c (ffffffff818affb1)
Location: include/net/netlink.h:955
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818b4343)
Location: include/net/netlink.h:955
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818b5759)
Location: include/net/netlink.h:955
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff818bb908)
Location: include/net/netlink.h:955
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
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
In net/core/neighbour.c (ffffffff817dc844)
Location: include/net/netlink.h:967
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff817e570b)
Location: include/net/netlink.h:967
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/fib_rules.c (ffffffff817f4127)
Location: include/net/netlink.h:967
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff817f942d)
Location: include/net/netlink.h:967
Inline: True
```
```
In net/sched/sch_api.c (ffffffff817ff489)
Location: include/net/netlink.h:967
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff818021d8)
Location: include/net/netlink.h:967
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff8180481d)
Location: include/net/netlink.h:967
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/netlink/af_netlink.c (ffffffff8180a3c6)
Location: include/net/netlink.h:967
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff8180bbd7)
Location: include/net/netlink.h:967
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/devinet.c (ffffffff8185031b)
Location: include/net/netlink.h:967
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff8188e89b)
Location: include/net/netlink.h:967
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/wireless/wext-core.c (ffffffff818d698f)
Location: include/net/netlink.h:967
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818dacf3)
Location: include/net/netlink.h:967
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818dc0fc)
Location: include/net/netlink.h:967
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff818e2308)
Location: include/net/netlink.h:967
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
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
In net/core/neighbour.c (ffffffff81857422)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff818607ab)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:nla_put_ifalias
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/fib_rules.c (ffffffff8186f88c)
Location: include/net/netlink.h:1008
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81876d3d)
Location: include/net/netlink.h:1008
Inline: True
```
```
In net/sched/sch_api.c (ffffffff8187d1f9)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81880433)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff8188352d)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/netlink/af_netlink.c (ffffffff81889403)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff8188ab67)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/devinet.c (ffffffff818cff4b)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff8190feeb)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/wireless/wext-core.c (ffffffff8195c55f)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819608d3)
Location: include/net/netlink.h:1008
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81961cdf)
Location: include/net/netlink.h:1008
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff819680c8)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
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
In net/core/neighbour.c (ffffffff818a3250)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff818aa66a)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:nla_put_ifalias
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/fib_rules.c (ffffffff818c1072)
Location: include/net/netlink.h:1008
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff818c819d)
Location: include/net/netlink.h:1008
Inline: True
```
```
In net/sched/sch_api.c (ffffffff818cf815)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff818d319c)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff818d6f6d)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/netlink/af_netlink.c (ffffffff818dcddc)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff818de196)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/devinet.c (ffffffff819263e4)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff8196730a)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/seg6_local.c (ffffffff819a8680)
Location: include/net/netlink.h:1008
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff819b5d8c)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819ba093)
Location: include/net/netlink.h:1008
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819bb4c0)
Location: include/net/netlink.h:1008
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff819c1835)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/ncsi/ncsi-netlink.c (ffffffff819cad05)
Location: include/net/netlink.h:1008
Inline: True
Inline callers:
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
In net/core/neighbour.c (ffffffff818c62d6)
Location: include/net/netlink.h:1151
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff818d0507)
Location: include/net/netlink.h:1151
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:nla_put_ifalias
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/fib_rules.c (ffffffff818e9e7f)
Location: include/net/netlink.h:1151
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff818f130d)
Location: include/net/netlink.h:1151
Inline: True
```
```
In net/sched/sch_api.c (ffffffff818fabb2)
Location: include/net/netlink.h:1151
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff818feb49)
Location: include/net/netlink.h:1151
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff819032fd)
Location: include/net/netlink.h:1151
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/netlink/af_netlink.c (ffffffff819097b2)
Location: include/net/netlink.h:1151
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff8190ab56)
Location: include/net/netlink.h:1151
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/devinet.c (ffffffff8195546f)
Location: include/net/netlink.h:1151
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff8199c917)
Location: include/net/netlink.h:1151
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/seg6_local.c (ffffffff819df1d0)
Location: include/net/netlink.h:1151
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff819ed049)
Location: include/net/netlink.h:1151
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f19e3)
Location: include/net/netlink.h:1151
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f2740)
Location: include/net/netlink.h:1151
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff819f8d95)
Location: include/net/netlink.h:1151
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a037c4)
Location: include/net/netlink.h:1151
Inline: True
Inline callers:
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
In net/core/neighbour.c (ffffffff81912344)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff8191d3b5)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:nla_put_ifalias
```
```
In net/core/fib_rules.c (ffffffff819398e2)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81942fad)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/core/devlink.c (ffffffff8194ee35)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_info_serial_number_put
  - net/core/devlink.c:devlink_info_driver_name_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_api.c (ffffffff8195a46e)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff8195e547)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff8196447d)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/netlink/af_netlink.c (ffffffff8196aac2)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff8196bf4d)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/devinet.c (ffffffff819b9dfa)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81a08af3)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/seg6_local.c (ffffffff81a4dd42)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff81a5c236)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a610b0)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a61a25)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81a682e5)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a72a29)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
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
In net/core/neighbour.c (ffffffff819449b4)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff8194f9e8)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:nla_put_ifalias
```
```
In net/core/fib_rules.c (ffffffff8196c7af)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81975d5f)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwt_bpf.c (ffffffff81977f5d)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/core/devlink.c (ffffffff819839f9)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_info_serial_number_put
  - net/core/devlink.c:devlink_info_driver_name_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_api.c (ffffffff8199090e)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81994e17)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff8199afdd)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/netlink/af_netlink.c (ffffffff819a1552)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff819a28fd)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/devinet.c (ffffffff819f098a)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81a3f203)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/seg6_local.c (ffffffff81a84912)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff81a92e62)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a97ce0)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a9864e)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81a9ec45)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81aa91e9)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
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
In net/core/neighbour.c (ffffffff81a13c86)
Location: include/net/netlink.h:1461
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff81a21206)
Location: include/net/netlink.h:1461
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:nla_put_ifalias
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_slave_info_fill
```
```
In net/core/fib_rules.c (ffffffff81a4065c)
Location: include/net/netlink.h:1461
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81a4a8f1)
Location: include/net/netlink.h:1461
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_entries_put
```
```
In net/core/lwt_bpf.c (ffffffff81a4c6cd)
Location: include/net/netlink.h:1461
Inline: True
```
```
In net/core/devlink.c (ffffffff81a5b1b0)
Location: include/net/netlink.h:1461
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_info_serial_number_put
  - net/core/devlink.c:devlink_info_driver_name_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_dpipe_header_put
  - net/core/devlink.c:devlink_dpipe_fields_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_put_handle
  - net/core/devlink.c:devlink_nl_put_handle
```
```
In net/sched/sch_api.c (ffffffff81a68a4e)
Location: include/net/netlink.h:1461
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a6db47)
Location: include/net/netlink.h:1461
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81a7426d)
Location: include/net/netlink.h:1461
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_terse
  - net/sched/act_api.c:tcf_del_walker
```
```
In net/netlink/af_netlink.c (ffffffff81a7af37)
Location: include/net/netlink.h:1461
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff81a7cb39)
Location: include/net/netlink.h:1461
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81a859d2)
Location: include/net/netlink.h:1461
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81ade8b9)
Location: include/net/netlink.h:1461
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81b34e83)
Location: include/net/netlink.h:1461
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/seg6_local.c (ffffffff81b7f8e5)
Location: include/net/netlink.h:1461
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff81b8e172)
Location: include/net/netlink.h:1461
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b93243)
Location: include/net/netlink.h:1461
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b93d7a)
Location: include/net/netlink.h:1461
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/dcb/dcbnl.c (ffffffff81b9aec5)
Location: include/net/netlink.h:1461
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba491b)
Location: include/net/netlink.h:1461
Inline: True
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
In drivers/thermal/thermal_netlink.c (ffffffff8195f9e7)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:__thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_gov
  - drivers/thermal/thermal_netlink.c:__thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_gov_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_create
```
```
In net/core/neighbour.c (ffffffff81a13fa6)
Location: include/net/netlink.h:1474
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff81a1f783)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:nla_put_ifalias
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_slave_info_fill
```
```
In net/core/fib_rules.c (ffffffff81a43497)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81a50532)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_entries_put
```
```
In net/core/lwt_bpf.c (ffffffff81a5234d)
Location: include/net/netlink.h:1474
Inline: True
```
```
In net/core/devlink.c (ffffffff81a6272a)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_info_board_serial_number_put
  - net/core/devlink.c:devlink_info_serial_number_put
  - net/core/devlink.c:devlink_info_driver_name_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_dpipe_header_put
  - net/core/devlink.c:devlink_dpipe_fields_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_put_handle
  - net/core/devlink.c:devlink_nl_put_handle
```
```
In net/sched/sch_api.c (ffffffff81a71163)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a76507)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81a7be3a)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:tcf_action_dump_terse
```
```
In net/netlink/af_netlink.c (ffffffff81a83cfb)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81a85d78)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81a8f34a)
Location: include/net/netlink.h:1474
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81aeb699)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81b43a98)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/seg6_local.c (ffffffff81b8e995)
Location: include/net/netlink.h:1474
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff81b9de0b)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81ba2e93)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba39ce)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/dcb/dcbnl.c (ffffffff81baabda)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81bb3dbb)
Location: include/net/netlink.h:1474
Inline: True
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
In drivers/thermal/thermal_netlink.c (ffffffff81942f48)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:__thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_gov
  - drivers/thermal/thermal_netlink.c:__thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_gov_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_create
```
```
In net/core/neighbour.c (ffffffff819fbc58)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81a06853)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:nla_put_ifalias
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
```
```
In net/core/fib_rules.c (ffffffff81a281f5)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81a35452)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/lwt_bpf.c (ffffffff81a37b2d)
Location: include/net/netlink.h:1474
Inline: True
```
```
In net/core/devlink.c (ffffffff81a44eba)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_info_board_serial_number_put
  - net/core/devlink.c:devlink_info_serial_number_put
  - net/core/devlink.c:devlink_info_driver_name_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_put_handle
  - net/core/devlink.c:devlink_nl_put_handle
```
```
In net/sched/sch_api.c (ffffffff81a59933)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a5e407)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81a64a76)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:tcf_action_dump_terse
```
```
In net/netlink/af_netlink.c (ffffffff81a6ceba)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81a6ea6a)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81a78a4a)
Location: include/net/netlink.h:1474
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81ad6d03)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81b316f8)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/seg6_local.c (ffffffff81b7db92)
Location: include/net/netlink.h:1474
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff81b8cf0b)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b91fb3)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b92aed)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/dcb/dcbnl.c (ffffffff81b99d6a)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba2d9b)
Location: include/net/netlink.h:1474
Inline: True
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
In drivers/net/wwan/wwan_core.c (ffffffff8191a962)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In drivers/thermal/thermal_netlink.c (ffffffff819e7918)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:__thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_gov
  - drivers/thermal/thermal_netlink.c:__thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_gov_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_create
```
```
In net/core/neighbour.c (ffffffff81aad517)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81ab8cb3)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:nla_put_ifalias
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
```
```
In net/core/fib_rules.c (ffffffff81adcf95)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81aeb022)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/lwt_bpf.c (ffffffff81aed97d)
Location: include/net/netlink.h:1474
Inline: True
```
```
In net/core/devlink.c (ffffffff81afde0a)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_info_board_serial_number_put
  - net/core/devlink.c:devlink_info_serial_number_put
  - net/core/devlink.c:devlink_info_driver_name_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_put_handle
  - net/core/devlink.c:devlink_nl_put_handle
```
```
In net/sched/sch_api.c (ffffffff81b129f3)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81b175e7)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81b1dd46)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:tcf_action_dump_terse
```
```
In net/netlink/af_netlink.c (ffffffff81b2653a)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81b284aa)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81b32c1a)
Location: include/net/netlink.h:1474
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81b95743)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81bf7798)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/seg6_local.c (ffffffff81c49332)
Location: include/net/netlink.h:1474
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff81c592ab)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81c5e753)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81c5f28d)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/dcb/dcbnl.c (ffffffff81c673da)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81c708eb)
Location: include/net/netlink.h:1474
Inline: True
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
In drivers/net/wwan/wwan_core.c (ffffffff81a6fdae)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81b4d1f7)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:__thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_gov
  - drivers/thermal/thermal_netlink.c:__thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_gov_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_create
```
```
In net/core/neighbour.c (ffffffff81c2525b)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81c31eff)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:nla_put_ifalias
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
```
```
In net/core/fib_rules.c (ffffffff81c5e392)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81c6d872)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/lwt_bpf.c (ffffffff81c7083d)
Location: include/net/netlink.h:1474
Inline: True
```
```
In net/core/devlink.c (ffffffff81c8131b)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_info_board_serial_number_put
  - net/core/devlink.c:devlink_info_serial_number_put
  - net/core/devlink.c:devlink_info_driver_name_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_put_handle
  - net/core/devlink.c:devlink_nl_put_handle
```
```
In net/sched/sch_api.c (ffffffff81c9afb1)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81c9f398)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81ca6b9a)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_terse
```
```
In net/netlink/af_netlink.c (ffffffff81caf0ab)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81cb16d3)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81cbe7c4)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_fill_reply_header
```
```
In net/ipv4/devinet.c (ffffffff81d2754a)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81d90c3f)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/seg6_local.c (ffffffff81de8ac2)
Location: include/net/netlink.h:1474
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff81dfaa07)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81e00973)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e01672)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/dcb/dcbnl.c (ffffffff81e0a9ce)
Location: include/net/netlink.h:1474
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81e144fb)
Location: include/net/netlink.h:1474
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
In drivers/net/wwan/wwan_core.c (ffffffff81c02c3e)
Location: include/net/netlink.h:1523
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81ce4f27)
Location: include/net/netlink.h:1523
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:__thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_gov
  - drivers/thermal/thermal_netlink.c:__thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_gov_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_create
```
```
In net/core/neighbour.c (ffffffff81dd785b)
Location: include/net/netlink.h:1523
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81de52cf)
Location: include/net/netlink.h:1523
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:nla_put_ifalias
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
```
```
In net/core/fib_rules.c (ffffffff81e14bc8)
Location: include/net/netlink.h:1523
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81e254d2)
Location: include/net/netlink.h:1523
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/lwt_bpf.c (ffffffff81e2883d)
Location: include/net/netlink.h:1523
Inline: True
```
```
In net/core/devlink.c (ffffffff81e3955b)
Location: include/net/netlink.h:1523
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_info_board_serial_number_put
  - net/core/devlink.c:devlink_info_serial_number_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_put_handle
  - net/core/devlink.c:devlink_nl_put_handle
```
```
In net/sched/sch_api.c (ffffffff81e57441)
Location: include/net/netlink.h:1523
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81e5b5c8)
Location: include/net/netlink.h:1523
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81e630aa)
Location: include/net/netlink.h:1523
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_terse
```
```
In net/netlink/af_netlink.c (ffffffff81e68ebc)
Location: include/net/netlink.h:1523
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack_tlv_fill
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81e6f501)
Location: include/net/netlink.h:1523
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81e7d2b4)
Location: include/net/netlink.h:1523
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_fill_reply_header
```
```
In net/ipv4/devinet.c (ffffffff81eeeeb7)
Location: include/net/netlink.h:1523
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81f5f35f)
Location: include/net/netlink.h:1523
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/seg6_local.c (ffffffff81fbc1f5)
Location: include/net/netlink.h:1523
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff81fcf1b7)
Location: include/net/netlink.h:1523
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81fd57c3)
Location: include/net/netlink.h:1523
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd64d2)
Location: include/net/netlink.h:1523
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/dcb/dcbnl.c (ffffffff81fe026e)
Location: include/net/netlink.h:1523
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81feb30b)
Location: include/net/netlink.h:1523
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
In drivers/net/wwan/wwan_core.c (ffffffff81c682ee)
Location: include/net/netlink.h:1524
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81d4d4f7)
Location: include/net/netlink.h:1524
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:__thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_gov
  - drivers/thermal/thermal_netlink.c:__thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_gov_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_create
```
```
In net/core/neighbour.c (ffffffff81e4866d)
Location: include/net/netlink.h:1524
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81e56ceb)
Location: include/net/netlink.h:1524
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:nla_put_ifalias
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
```
```
In net/core/fib_rules.c (ffffffff81e884d8)
Location: include/net/netlink.h:1524
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81e9aa12)
Location: include/net/netlink.h:1524
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/lwt_bpf.c (ffffffff81e9de5d)
Location: include/net/netlink.h:1524
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81eb346c)
Location: include/net/netlink.h:1524
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81eb7cf0)
Location: include/net/netlink.h:1524
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81ebf13a)
Location: include/net/netlink.h:1524
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_terse
```
```
In net/netlink/af_netlink.c (ffffffff81ec4d2c)
Location: include/net/netlink.h:1524
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack_tlv_fill
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81ecb981)
Location: include/net/netlink.h:1524
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81ed9874)
Location: include/net/netlink.h:1524
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_fill_reply_header
```
```
In net/ipv4/devinet.c (ffffffff81f4e877)
Location: include/net/netlink.h:1524
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81fbf08d)
Location: include/net/netlink.h:1524
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/seg6_local.c (ffffffff8201caf5)
Location: include/net/netlink.h:1524
Inline: True
```
```
In net/devlink/leftover.c (ffffffff82037661)
Location: include/net/netlink.h:1524
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_trap_policer_fill
  - net/devlink/leftover.c:devlink_nl_trap_policer_fill
  - net/devlink/leftover.c:devlink_nl_trap_group_fill
  - net/devlink/leftover.c:devlink_nl_trap_group_fill
  - net/devlink/leftover.c:devlink_nl_trap_group_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
  - net/devlink/leftover.c:devlink_nl_region_notify_build
  - net/devlink/leftover.c:devlink_nl_param_value_fill_one
  - net/devlink/leftover.c:devlink_dpipe_table_put
  - net/devlink/leftover.c:devlink_nl_port_fill
  - net/devlink/leftover.c:devlink_nl_port_fill
  - net/devlink/leftover.c:devlink_nl_port_handle_fill
  - net/devlink/leftover.c:devlink_nl_port_handle_fill
```
```
In net/devlink/dev.c (ffffffff8204592b)
Location: include/net/netlink.h:1524
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_cmd_selftests_run
  - net/devlink/dev.c:devlink_nl_cmd_selftests_run
  - net/devlink/dev.c:devlink_nl_selftests_fill
  - net/devlink/dev.c:devlink_nl_selftests_fill
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/dev.c:devlink_info_version_put
  - net/devlink/dev.c:devlink_info_version_put
  - net/devlink/dev.c:devlink_info_board_serial_number_put
  - net/devlink/dev.c:devlink_info_serial_number_put
  - net/devlink/dev.c:devlink_nl_cmd_reload
  - net/devlink/dev.c:devlink_nl_cmd_reload
  - net/devlink/dev.c:devlink_nl_fill
  - net/devlink/dev.c:devlink_nl_fill
```
```
In net/devlink/health.c (ffffffff82047276)
Location: include/net/netlink.h:1524
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_fmsg_prepare_skb
  - net/devlink/health.c:devlink_fmsg_prepare_skb
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
```
```
In net/wireless/wext-core.c (ffffffff8204ade2)
Location: include/net/netlink.h:1524
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff82051463)
Location: include/net/netlink.h:1524
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82052192)
Location: include/net/netlink.h:1524
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/dcb/dcbnl.c (ffffffff8205c61e)
Location: include/net/netlink.h:1524
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/ncsi/ncsi-netlink.c (ffffffff820675bb)
Location: include/net/netlink.h:1524
Inline: True
```
```
In net/handshake/tlshd.c (ffffffff82093f06)
Location: include/net/netlink.h:1524
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
In drivers/thermal/thermal_netlink.c (ffffffff81e041f7)
Location: include/net/netlink.h:1600
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:__thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_gov
  - drivers/thermal/thermal_netlink.c:__thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_gov_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cdev_add
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_tz_create
```
```
In drivers/dpll/dpll_netlink.c (ffffffff81eb99ad)
Location: include/net/netlink.h:1600
Inline: True
Inline callers:
  - drivers/dpll/dpll_netlink.c:dpll_cmd_pin_get_one
  - drivers/dpll/dpll_netlink.c:dpll_cmd_pin_get_one
  - drivers/dpll/dpll_netlink.c:dpll_cmd_pin_get_one
  - drivers/dpll/dpll_netlink.c:dpll_cmd_pin_get_one
```
```
In net/core/neighbour.c (ffffffff81f0722d)
Location: include/net/netlink.h:1600
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81f16041)
Location: include/net/netlink.h:1600
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:nla_put_ifalias
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
```
```
In net/core/fib_rules.c (ffffffff81f4a4e8)
Location: include/net/netlink.h:1600
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81f5d152)
Location: include/net/netlink.h:1600
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/lwt_bpf.c (ffffffff81f605dd)
Location: include/net/netlink.h:1600
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81f75f7c)
Location: include/net/netlink.h:1600
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81f7ad00)
Location: include/net/netlink.h:1600
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81f822ba)
Location: include/net/netlink.h:1600
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_terse
```
```
In net/netlink/af_netlink.c (ffffffff81f880fc)
Location: include/net/netlink.h:1600
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack_tlv_fill
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81f8eea7)
Location: include/net/netlink.h:1600
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81f9d73c)
Location: include/net/netlink.h:1600
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_fill_reply_header
```
```
In net/ipv4/devinet.c (ffffffff820149ba)
Location: include/net/netlink.h:1600
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff8208c525)
Location: include/net/netlink.h:1600
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/seg6_local.c (ffffffff820ebad5)
Location: include/net/netlink.h:1600
Inline: True
```
```
In net/devlink/netlink.c (ffffffff821016a9)
Location: include/net/netlink.h:1600
Inline: True
Inline callers:
  - net/devlink/netlink.c:devlink_nl_put_nested_handle
  - net/devlink/netlink.c:devlink_nl_put_nested_handle
```
```
In net/devlink/dev.c (ffffffff8210526e)
Location: include/net/netlink.h:1600
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_selftests_run_doit
  - net/devlink/dev.c:devlink_nl_selftests_run_doit
  - net/devlink/dev.c:devlink_nl_selftests_fill
  - net/devlink/dev.c:devlink_nl_selftests_fill
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/dev.c:devlink_info_version_put
  - net/devlink/dev.c:devlink_info_version_put
  - net/devlink/dev.c:devlink_info_board_serial_number_put
  - net/devlink/dev.c:devlink_info_serial_number_put
  - net/devlink/dev.c:devlink_nl_reload_doit
  - net/devlink/dev.c:devlink_nl_reload_doit
  - net/devlink/dev.c:devlink_nl_fill
  - net/devlink/dev.c:devlink_nl_fill
```
```
In net/devlink/port.c (ffffffff821068f0)
Location: include/net/netlink.h:1600
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_nl_port_fill
  - net/devlink/port.c:devlink_nl_port_fill
  - net/devlink/port.c:devlink_nl_port_fill
  - net/devlink/port.c:devlink_nl_port_fill
  - net/devlink/port.c:devlink_nl_port_handle_fill
  - net/devlink/port.c:devlink_nl_port_handle_fill
```
```
In net/devlink/sb.c (ffffffff8210867d)
Location: include/net/netlink.h:1600
Inline: True
Inline callers:
  - net/devlink/sb.c:devlink_nl_put_handle
  - net/devlink/sb.c:devlink_nl_put_handle
```
```
In net/devlink/dpipe.c (ffffffff8210b953)
Location: include/net/netlink.h:1600
Inline: True
Inline callers:
  - net/devlink/dpipe.c:devlink_dpipe_table_put
```
```
In net/devlink/resource.c (ffffffff8210c42c)
Location: include/net/netlink.h:1600
Inline: True
```
```
In net/devlink/param.c (ffffffff8210dc15)
Location: include/net/netlink.h:1600
Inline: True
Inline callers:
  - net/devlink/param.c:devlink_nl_param_value_fill_one
```
```
In net/devlink/region.c (ffffffff82111216)
Location: include/net/netlink.h:1600
Inline: True
Inline callers:
  - net/devlink/region.c:devlink_nl_region_read_dumpit
  - net/devlink/region.c:devlink_nl_region_read_dumpit
  - net/devlink/region.c:devlink_nl_region_read_dumpit
  - net/devlink/region.c:devlink_nl_region_notify_build
  - net/devlink/region.c:devlink_nl_region_notify_build
  - net/devlink/region.c:devlink_nl_region_notify_build
```
```
In net/devlink/health.c (ffffffff821131a6)
Location: include/net/netlink.h:1600
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_fmsg_prepare_skb
  - net/devlink/health.c:devlink_fmsg_prepare_skb
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
```
```
In net/devlink/trap.c (ffffffff82114a91)
Location: include/net/netlink.h:1600
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_nl_trap_policer_fill
  - net/devlink/trap.c:devlink_nl_trap_policer_fill
  - net/devlink/trap.c:devlink_nl_trap_group_fill
  - net/devlink/trap.c:devlink_nl_trap_group_fill
  - net/devlink/trap.c:devlink_nl_trap_group_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
```
```
In net/devlink/rate.c (ffffffff82118823)
Location: include/net/netlink.h:1600
Inline: True
```
```
In net/devlink/linecard.c (ffffffff821198f2)
Location: include/net/netlink.h:1600
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff8211d266)
Location: include/net/netlink.h:1600
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff82123c33)
Location: include/net/netlink.h:1600
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82124907)
Location: include/net/netlink.h:1600
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/dcb/dcbnl.c (ffffffff8212e465)
Location: include/net/netlink.h:1600
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/ncsi/ncsi-netlink.c (ffffffff8213a83d)
Location: include/net/netlink.h:1600
Inline: True
```
```
In net/handshake/tlshd.c (ffffffff8216a826)
Location: include/net/netlink.h:1600
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
In net/core/neighbour.c (ffff800010be7b84)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffff800010bf16d4)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:nla_put_ifalias
```
```
In net/core/fib_rules.c (ffff800010c12ffc)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/core/drop_monitor.c (ffff800010c1c1fc)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwt_bpf.c (ffff800010c1e7ec)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/core/devlink.c (ffff800010c2c044)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_info_serial_number_put
  - net/core/devlink.c:devlink_info_driver_name_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_api.c (ffff800010c3cb90)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffff800010c41980)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/sched/act_api.c (ffff800010c481a0)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/netlink/af_netlink.c (ffff800010c4fbd4)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffff800010c51bc4)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/devinet.c (ffff800010ca6bd0)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffff800010d02700)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/seg6_local.c (ffff800010d50960)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/wireless/wext-core.c (ffff800010d60c54)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffff800010d672a0)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d67e00)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/dcb/dcbnl.c (ffff800010d6f648)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/ncsi/ncsi-netlink.c (ffff800010d7cc68)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
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
In net/core/neighbour.c (c0d00748)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (c0d09ea0)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:nla_put_ifalias
```
```
In net/core/fib_rules.c (c0d2a990)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (c0d34038)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwt_bpf.c (c0d36834)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/core/devlink.c (c0d426ec)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_info_serial_number_put
  - net/core/devlink.c:devlink_info_driver_name_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_put_handle
  - net/core/devlink.c:devlink_nl_put_handle
```
```
In net/sched/sch_api.c (c0d4e8f8)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (c0d537c4)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (c0d591dc)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/netlink/af_netlink.c (c0d5fd90)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (c0d612ac)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/devinet.c (c0db32d0)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (c0e08504)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/seg6_local.c (c0e514c0)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/wireless/wext-core.c (c0e60520)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (c0e658a8)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (c0e665cc)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/dcb/dcbnl.c (c0e6d7bc)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/ncsi/ncsi-netlink.c (c0e77ad4)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
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
In net/core/neighbour.c (c000000000cc9c94)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (c000000000cd6244)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:nla_put_ifalias
```
```
In net/core/fib_rules.c (c000000000d000a4)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/core/drop_monitor.c (c000000000d0cf64)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwt_bpf.c (c000000000d10880)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/core/devlink.c (c000000000d22b10)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_info_serial_number_put
  - net/core/devlink.c:devlink_info_driver_name_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_put_handle
  - net/core/devlink.c:devlink_nl_put_handle
```
```
In net/sched/sch_api.c (c000000000d37c84)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (c000000000d3d650)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (c000000000d45438)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/netlink/af_netlink.c (c000000000d4e6a8)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (c000000000d50674)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/devinet.c (c000000000dbb0a4)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (c000000000e29f88)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/seg6_local.c (c000000000e88660)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/wireless/wext-core.c (c000000000e9bfcc)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (c000000000ea2fd8)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (c000000000ea475c)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/dcb/dcbnl.c (c000000000eae5fc)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/ncsi/ncsi-netlink.c (c000000000ebc634)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
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
In net/core/neighbour.c (ffffffe00076c422)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffe00077344c)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:nla_put_ifalias
```
```
In net/core/fib_rules.c (ffffffe00078e9c8)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/core/drop_monitor.c (ffffffe0007962a4)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwt_bpf.c (ffffffe000798470)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/core/devlink.c (ffffffe0007a365c)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_info_serial_number_put
  - net/core/devlink.c:devlink_info_driver_name_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_put_handle
  - net/core/devlink.c:devlink_nl_put_handle
```
```
In net/sched/sch_api.c (ffffffe0007ad40c)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffe0007b132a)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffe0007b5c94)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/netlink/af_netlink.c (ffffffe0007bb778)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffe0007bccc4)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/devinet.c (ffffffe000801f10)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffe00084ab14)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/seg6_local.c (ffffffe000888d7c)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/wireless/wext-core.c (ffffffe000895efa)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffe00089aa7a)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089b29a)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffe0008a10fe)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/ncsi/ncsi-netlink.c (ffffffe0008aa9c8)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
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
In net/core/neighbour.c (ffffffff818e4984)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff818ef9b8)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:nla_put_ifalias
```
```
In net/core/fib_rules.c (ffffffff8190c77f)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81915d2f)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwt_bpf.c (ffffffff81917dcd)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/core/devlink.c (ffffffff81923869)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_info_serial_number_put
  - net/core/devlink.c:devlink_info_driver_name_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_api.c (ffffffff8193077e)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81934c87)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff8193ae4d)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/netlink/af_netlink.c (ffffffff819413c2)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff8194276d)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/devinet.c (ffffffff8199072a)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff819de893)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/seg6_local.c (ffffffff81a23fa2)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff81a324f2)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a37070)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a379de)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81a3dfd5)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a48579)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
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
In net/core/neighbour.c (ffffffff8189e7c4)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff818a97f8)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:nla_put_ifalias
```
```
In net/core/fib_rules.c (ffffffff818c653f)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff818cfadf)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwt_bpf.c (ffffffff818d1b7d)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/core/devlink.c (ffffffff818dd619)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_info_serial_number_put
  - net/core/devlink.c:devlink_info_driver_name_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_api.c (ffffffff818ea27e)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff818ee787)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff818f494d)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/netlink/af_netlink.c (ffffffff818faeb2)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff818fc25d)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/devinet.c (ffffffff8194a1ea)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff8199b653)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/seg6_local.c (ffffffff819e0d62)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff819ef6e2)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f3c90)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f45fe)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff819fabc5)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a05169)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
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
In net/core/neighbour.c (ffffffff819359b4)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff819409e8)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:nla_put_ifalias
```
```
In net/core/fib_rules.c (ffffffff8195d7af)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81966d5f)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwt_bpf.c (ffffffff81968f5d)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/core/devlink.c (ffffffff819749f9)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_info_serial_number_put
  - net/core/devlink.c:devlink_info_driver_name_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_api.c (ffffffff8198190e)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81985e17)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff8198bfdd)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/netlink/af_netlink.c (ffffffff81992552)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff819938fd)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819afc66)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_dump_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_dump_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_helpinfo
```
```
In net/ipv4/devinet.c (ffffffff819fafca)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81a49313)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/seg6_local.c (ffffffff81a8ea22)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff81a9e0a2)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aa2f20)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aa388e)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81aa9e85)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ab4429)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
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
In net/core/neighbour.c (ffffffff819570c4)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff819622f8)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:nla_put_ifalias
```
```
In net/core/fib_rules.c (ffffffff8197f9ff)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81988fef)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/lwt_bpf.c (ffffffff8198b33d)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/core/devlink.c (ffffffff81996ee9)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_info_serial_number_put
  - net/core/devlink.c:devlink_info_driver_name_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_api.c (ffffffff819a3e68)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff819a8e17)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff819ae84d)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/netlink/af_netlink.c (ffffffff819b5042)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff819b63ed)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81a0531d)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81a55233)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/seg6_local.c (ffffffff81a9b792)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff81aaa2a2)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aaf290)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aafcae)
Location: include/net/netlink.h:1409
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81ab61f5)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ac07c9)
Location: include/net/netlink.h:1409
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
</details>
</li>
</ul>

## Differences
