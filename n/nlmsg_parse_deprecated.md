# Function: <code>nlmsg_parse_deprecated</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818f39a3)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81910271)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff81918181)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/rtnetlink.c:valid_fdb_dump_legacy
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff8193a220)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/devlink.c (ffffffff819518a6)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (ffffffff8195ba9a)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff819601ba)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff8196397c)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/ipv4/route.c (ffffffff81975f45)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff819b98d8)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/ipmr.c (ffffffff819db607)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff81a0ebf8)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a119d7)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81a152b6)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81a67f7a)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
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
In net/core/net_namespace.c (ffffffff81925953)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff819428e1)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff8194a7a1)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/rtnetlink.c:valid_fdb_dump_legacy
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff8196d0e0)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/devlink.c (ffffffff819882e6)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (ffffffff81991f4a)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff8199729a)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff8199a4fc)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/ipv4/route.c (ffffffff819ac955)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff819f05d2)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/ipmr.c (ffffffff81a124e0)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff81a45938)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a485f6)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81a4be86)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81a9e8da)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
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
In net/core/net_namespace.c (ffffffff819f9aed)
Location: include/net/netlink.h:753
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81a129af)
Location: include/net/netlink.h:753
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff81a1e333)
Location: include/net/netlink.h:753
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81a412bd)
Location: include/net/netlink.h:753
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff81a6a314)
Location: include/net/netlink.h:753
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a6f5da)
Location: include/net/netlink.h:753
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff81a7345a)
Location: include/net/netlink.h:753
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/ipv4/route.c (ffffffff81a91cc9)
Location: include/net/netlink.h:753
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
```
```
In net/ipv4/devinet.c (ffffffff81ade540)
Location: include/net/netlink.h:753
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/ipmr.c (ffffffff81b01476)
Location: include/net/netlink.h:753
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
```
```
In net/ipv6/addrconf.c (ffffffff81b3c6ca)
Location: include/net/netlink.h:753
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b3f488)
Location: include/net/netlink.h:753
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81b413e9)
Location: include/net/netlink.h:753
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81b996c8)
Location: include/net/netlink.h:753
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
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
In net/core/net_namespace.c (ffffffff819f963d)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81a12cff)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff81a1e666)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81a43afe)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff81a72a44)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a77fda)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff81a7c05a)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/ipv4/route.c (ffffffff81a9bb59)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
```
```
In net/ipv4/devinet.c (ffffffff81aeb320)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/ipmr.c (ffffffff81b0f556)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
```
```
In net/ipv6/addrconf.c (ffffffff81b4b3da)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b4df36)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81b4fea9)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81ba9371)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
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
In net/core/net_namespace.c (ffffffff819df7a9)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff819fa196)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff81a053f6)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81a2887f)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff81a5b394)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a60e02)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff81a64c87)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/ipv4/route.c (ffffffff81a87072)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
```
```
In net/ipv4/devinet.c (ffffffff81ad804c)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/ipmr.c (ffffffff81afd23e)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
```
```
In net/ipv6/addrconf.c (ffffffff81b390fa)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b3b9e5)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81b3e4a2)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81b98501)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
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
In drivers/net/wwan/wwan_core.c (ffffffff8191aa70)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In net/core/net_namespace.c (ffffffff81a8fb89)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81aabf22)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff81ab7836)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81add61f)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff81b14554)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81b1a012)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff81b1df57)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/ipv4/route.c (ffffffff81b41832)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
```
```
In net/ipv4/devinet.c (ffffffff81b96eac)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/ipmr.c (ffffffff81bbea2e)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
```
```
In net/ipv6/addrconf.c (ffffffff81bff89a)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81c02271)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81c04d82)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81c65051)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
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
In drivers/net/wwan/wwan_core.c (ffffffff81a6fec2)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In net/core/net_namespace.c (ffffffff81c0593d)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81c2436f)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff81c31496)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81c5efaf)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff81c9b8fa)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81ca1210)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff81ca592f)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/ipv4/route.c (ffffffff81cce2d3)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
```
```
In net/ipv4/devinet.c (ffffffff81d28a55)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/ipmr.c (ffffffff81d52e69)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
```
```
In net/ipv6/addrconf.c (ffffffff81d991c0)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81d9c236)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81d9eae3)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81e07c6b)
Location: include/net/netlink.h:767
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
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
In drivers/net/wwan/wwan_core.c (ffffffff81c02d52)
Location: include/net/netlink.h:784
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In net/core/net_namespace.c (ffffffff81db520d)
Location: include/net/netlink.h:784
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81dd699f)
Location: include/net/netlink.h:784
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff81de4816)
Location: include/net/netlink.h:784
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81e1583f)
Location: include/net/netlink.h:784
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff81e57e1e)
Location: include/net/netlink.h:784
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81e5d280)
Location: include/net/netlink.h:784
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff81e639cf)
Location: include/net/netlink.h:784
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/ipv4/route.c (ffffffff81e8e2a3)
Location: include/net/netlink.h:784
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
```
```
In net/ipv4/devinet.c (ffffffff81ef04a5)
Location: include/net/netlink.h:784
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/ipmr.c (ffffffff81f1d7f9)
Location: include/net/netlink.h:784
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
```
```
In net/ipv6/addrconf.c (ffffffff81f67ee0)
Location: include/net/netlink.h:784
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81f6af06)
Location: include/net/netlink.h:784
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81f6daa3)
Location: include/net/netlink.h:784
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81fdd1bb)
Location: include/net/netlink.h:784
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
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
In drivers/net/wwan/wwan_core.c (ffffffff81c68402)
Location: include/net/netlink.h:785
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In net/core/net_namespace.c (ffffffff81e257dd)
Location: include/net/netlink.h:785
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81e477cf)
Location: include/net/netlink.h:785
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff81e51406)
Location: include/net/netlink.h:785
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_mdb_del
  - net/core/rtnetlink.c:rtnl_mdb_add
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81e8914f)
Location: include/net/netlink.h:785
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff81eb37be)
Location: include/net/netlink.h:785
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81eb9e30)
Location: include/net/netlink.h:785
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff81ebfa69)
Location: include/net/netlink.h:785
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/ipv4/route.c (ffffffff81eec9c8)
Location: include/net/netlink.h:785
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
```
```
In net/ipv4/devinet.c (ffffffff81f4fef5)
Location: include/net/netlink.h:785
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/ipmr.c (ffffffff81f7d2f9)
Location: include/net/netlink.h:785
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
```
```
In net/ipv6/addrconf.c (ffffffff81fc811d)
Location: include/net/netlink.h:785
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81fcaf36)
Location: include/net/netlink.h:785
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81fcdb58)
Location: include/net/netlink.h:785
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff8205928b)
Location: include/net/netlink.h:785
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
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
In net/core/net_namespace.c (ffffffff81ee373d)
Location: include/net/netlink.h:792
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81f0647f)
Location: include/net/netlink.h:792
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff81f11ba8)
Location: include/net/netlink.h:792
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_mdb_del
  - net/core/rtnetlink.c:rtnl_mdb_add
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81f4b15f)
Location: include/net/netlink.h:792
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff81f761ee)
Location: include/net/netlink.h:792
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81f7d0a0)
Location: include/net/netlink.h:792
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff81f82c19)
Location: include/net/netlink.h:792
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/ipv4/route.c (ffffffff81fb0a28)
Location: include/net/netlink.h:792
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
```
```
In net/ipv4/devinet.c (ffffffff820160a5)
Location: include/net/netlink.h:792
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/ipmr.c (ffffffff820439f9)
Location: include/net/netlink.h:792
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
```
```
In net/ipv6/addrconf.c (ffffffff8209582d)
Location: include/net/netlink.h:792
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff820986d6)
Location: include/net/netlink.h:792
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff8209b3a8)
Location: include/net/netlink.h:792
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff8212be0b)
Location: include/net/netlink.h:792
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
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
In net/core/net_namespace.c (ffff800010bc1cfc)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffff800010be682c)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffff800010bed6f8)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/rtnetlink.c:valid_fdb_dump_legacy
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffff800010c13894)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/devlink.c (ffff800010c2e290)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (ffff800010c3e534)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffff800010c44428)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffff800010c47724)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/ipv4/route.c (ffff800010c5caf8)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffff800010ca6438)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/ipmr.c (ffff800010ccb1d4)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffff800010d082d8)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffff800010d0b978)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffff800010d113f4)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffff800010d6f2d0)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
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
In net/core/net_namespace.c (c0cdd1d8)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (c0d00048)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (c0d05c70)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/rtnetlink.c:valid_fdb_dump_legacy
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_calcit
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (c0d2b270)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/devlink.c (c0d45528)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (c0d4ffa4)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (c0d54f84)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (c0d5851c)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/ipv4/route.c (c0d6c230)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (c0db2f0c)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/ipmr.c (c0dd6afc)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (c0e0eaa0)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (c0e1186c)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (c0e157f0)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (c0e6cf38)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
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
In net/core/net_namespace.c (c000000000c9b4e0)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (c000000000cc5fa0)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (c000000000ccfdf0)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/rtnetlink.c:valid_fdb_dump_legacy
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (c000000000d00c14)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/devlink.c (c000000000d28ea4)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (c000000000d3869c)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (c000000000d3f8f0)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (c000000000d445bc)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/ipv4/route.c (c000000000d5f070)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (c000000000dbac30)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/ipmr.c (c000000000dec340)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (c000000000e326e0)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (c000000000e361c0)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (c000000000e3a840)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (c000000000eae130)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
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
In net/core/net_namespace.c (ffffffe00074ed00)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffe000769da4)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffe000770438)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/rtnetlink.c:valid_fdb_dump_legacy
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffe00078f060)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/devlink.c (ffffffe0007a155e)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (ffffffe0007ae5a6)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffe0007b27ca)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffe0007b545c)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/ipv4/route.c (ffffffe0007c594c)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffe000801be2)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/ipmr.c (ffffffe0008213b8)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffe0008503d8)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffe0008529d4)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffe0008560d0)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffe0008a0ea2)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
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
In net/core/net_namespace.c (ffffffff818c5953)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff818e28b1)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff818ea771)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/rtnetlink.c:valid_fdb_dump_legacy
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff8190d0b0)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/devlink.c (ffffffff81928156)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (ffffffff81931dba)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff8193710a)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff8193a36c)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/ipv4/route.c (ffffffff8194c7c5)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff81990372)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/ipmr.c (ffffffff819b1df7)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff819e4fc8)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff819e7c86)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff819eb516)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81a3dc6a)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
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
In net/core/net_namespace.c (ffffffff8187f893)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff8189c6f1)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff818a45b1)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/rtnetlink.c:valid_fdb_dump_legacy
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff818c6e70)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/devlink.c (ffffffff818e1f06)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (ffffffff818eb8ba)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff818f0c0a)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff818f3e6c)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/ipv4/route.c (ffffffff819062b5)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff81949e32)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/ipmr.c (ffffffff8196e427)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff819a1d88)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff819a4a46)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff819a82d6)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff819fa85a)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
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
In net/core/net_namespace.c (ffffffff81916953)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff819338e1)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff8193b7a1)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/rtnetlink.c:valid_fdb_dump_legacy
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff8195e0e0)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/devlink.c (ffffffff819792e6)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (ffffffff81982f4a)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff8198829a)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff8198b4fc)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/ipv4/route.c (ffffffff819b6f95)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff819fac12)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/ipmr.c (ffffffff81a1c697)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff81a4fa48)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a52706)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81a55f96)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81aa9b1a)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
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
In net/core/net_namespace.c (ffffffff81937b63)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81955211)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff8195d021)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/rtnetlink.c:valid_fdb_dump_legacy
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81980330)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/devlink.c (ffffffff8199b7d6)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (ffffffff819a549a)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff819aa50a)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff819add6c)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/ipv4/route.c (ffffffff819c0815)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff81a04f62)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/ipmr.c (ffffffff81a275f0)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff81a5ba28)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a5e744)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81a61fc6)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81ab5e8a)
Location: include/net/netlink.h:701
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
</details>
</li>
</ul>

## Differences
