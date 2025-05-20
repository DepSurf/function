# Function: <code>nlmsg_attrdata</code>

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
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:311
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:311
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/net/netlink.h:311
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:311
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:311
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:311
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:311
Inline: True
```
```
In net/netlink/genetlink.c (0)
Location: include/net/netlink.h:311
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:311
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:311
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff81799db4)
Location: include/net/netlink.h:311
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:311
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:311
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:311
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:311
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
In net/core/net_namespace.c (ffffffff81778367)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81790f54)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81794746)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_calcit
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff817a6bb1)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff817b1914)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff817b357e)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_tfilter
```
```
In net/sched/act_api.c (ffffffff817b41cd)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff817bb5ed)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff817c34dd)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff817fd937)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff818079e2)
Location: include/net/netlink.h:322
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff818177a7)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/addrconf.c (ffffffff8183d707)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff818408d7)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81842625)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81886cd9)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/switchdev/switchdev.c (ffffffff8188ad17)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_bridge_dellink
  - net/switchdev/switchdev.c:switchdev_port_bridge_setlink
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
In net/core/net_namespace.c (ffffffff817a4de7)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff817be7f0)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff817c1fc6)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_calcit
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff817d5681)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff817e1044)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff817e2e2e)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_tfilter
```
```
In net/sched/act_api.c (ffffffff817e3a7d)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff817eafef)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff817f2ad4)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff8182e897)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff81838a82)
Location: include/net/netlink.h:322
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81849017)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/addrconf.c (ffffffff8186f317)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81872557)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81874375)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff818bb549)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/switchdev/switchdev.c (ffffffff818bf0e5)
Location: include/net/netlink.h:322
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_bridge_dellink
  - net/switchdev/switchdev.c:switchdev_port_bridge_setlink
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
In net/core/net_namespace.c (ffffffff817c2fde)
Location: include/net/netlink.h:326
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff817ddac1)
Location: include/net/netlink.h:326
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff817e0746)
Location: include/net/netlink.h:326
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_calcit
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff817f4b0e)
Location: include/net/netlink.h:326
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff8180052c)
Location: include/net/netlink.h:326
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff8180231a)
Location: include/net/netlink.h:326
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_ctl_tfilter
```
```
In net/sched/act_api.c (ffffffff818033ba)
Location: include/net/netlink.h:326
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff8180af5c)
Location: include/net/netlink.h:326
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff818133cf)
Location: include/net/netlink.h:326
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff8184f9be)
Location: include/net/netlink.h:326
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff81859d3c)
Location: include/net/netlink.h:326
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/ipmr.c (ffffffff8186c6db)
Location: include/net/netlink.h:326
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff818940de)
Location: include/net/netlink.h:326
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff818972de)
Location: include/net/netlink.h:326
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81899183)
Location: include/net/netlink.h:326
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff818e1f13)
Location: include/net/netlink.h:326
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/switchdev/switchdev.c (ffffffff818e5a20)
Location: include/net/netlink.h:326
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_bridge_dellink
  - net/switchdev/switchdev.c:switchdev_port_bridge_setlink
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
In net/core/net_namespace.c (ffffffff8183cb2e)
Location: include/net/netlink.h:332
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81857e41)
Location: include/net/netlink.h:332
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff8185afc9)
Location: include/net/netlink.h:332
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff818702fd)
Location: include/net/netlink.h:332
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff8187e31f)
Location: include/net/netlink.h:332
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81880738)
Location: include/net/netlink.h:332
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_ctl_tfilter
```
```
In net/sched/act_api.c (ffffffff81882418)
Location: include/net/netlink.h:332
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff81889eac)
Location: include/net/netlink.h:332
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff81892a1f)
Location: include/net/netlink.h:332
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff818cf5ee)
Location: include/net/netlink.h:332
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff818d9c3c)
Location: include/net/netlink.h:332
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/ipmr.c (ffffffff818ecfbb)
Location: include/net/netlink.h:332
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff819154de)
Location: include/net/netlink.h:332
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81917f7e)
Location: include/net/netlink.h:332
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff8191d763)
Location: include/net/netlink.h:332
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81967cb3)
Location: include/net/netlink.h:332
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
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
In net/core/net_namespace.c (ffffffff8188717b)
Location: include/net/netlink.h:332
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff818a2d3c)
Location: include/net/netlink.h:332
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff818a6880)
Location: include/net/netlink.h:332
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff818c1990)
Location: include/net/netlink.h:332
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff818d0db3)
Location: include/net/netlink.h:332
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff818d350b)
Location: include/net/netlink.h:332
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff818d5f24)
Location: include/net/netlink.h:332
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff818ded4b)
Location: include/net/netlink.h:332
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff818e69e3)
Location: include/net/netlink.h:332
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff81926031)
Location: include/net/netlink.h:332
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff819306d1)
Location: include/net/netlink.h:332
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/ipmr.c (ffffffff81942f32)
Location: include/net/netlink.h:332
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff8196cac1)
Location: include/net/netlink.h:332
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff8196f7b1)
Location: include/net/netlink.h:332
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81972540)
Location: include/net/netlink.h:332
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff819c14e3)
Location: include/net/netlink.h:332
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff819cafc2)
Location: include/net/netlink.h:332
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In net/core/net_namespace.c (ffffffff818a83c8)
Location: include/net/netlink.h:459
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff818c4061)
Location: include/net/netlink.h:459
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff818ca0e0)
Location: include/net/netlink.h:459
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:valid_fdb_dump_legacy
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff818ea7d1)
Location: include/net/netlink.h:459
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff818fc115)
Location: include/net/netlink.h:459
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff818ff97b)
Location: include/net/netlink.h:459
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
In net/sched/act_api.c (ffffffff81902728)
Location: include/net/netlink.h:459
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff8190b70b)
Location: include/net/netlink.h:459
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff819138aa)
Location: include/net/netlink.h:459
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff81955051)
Location: include/net/netlink.h:459
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff819603ce)
Location: include/net/netlink.h:459
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/ipmr.c (ffffffff81973002)
Location: include/net/netlink.h:459
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff819a25a0)
Location: include/net/netlink.h:459
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff819a53c1)
Location: include/net/netlink.h:459
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff819a80c5)
Location: include/net/netlink.h:459
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff819f8a33)
Location: include/net/netlink.h:459
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a03a82)
Location: include/net/netlink.h:459
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/taskstats.c (ffffffff81188dcf)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_pre_doit
```
```
In net/core/net_namespace.c (ffffffff818f39ac)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff819101d1)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff819170b0)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:valid_fdb_dump_legacy
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff8193a229)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/devlink.c (ffffffff819518d3)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (ffffffff8195baa5)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff819601e4)
Location: include/net/netlink.h:520
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
In net/sched/act_api.c (ffffffff81963990)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff8196c5fa)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff81975ea0)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff819b98e1)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff819c4f6d)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (ffffffff819d4657)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff819dcb12)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff81a0ec01)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a1188f)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81a151f4)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81a67f87)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a72d2d)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/taskstats.c (ffffffff81194d0f)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_pre_doit
```
```
In net/core/net_namespace.c (ffffffff8192595c)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81942841)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff819496f0)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:valid_fdb_dump_legacy
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff8196d0e9)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/devlink.c (ffffffff81988313)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (ffffffff81991f55)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff819972c4)
Location: include/net/netlink.h:520
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
In net/sched/act_api.c (ffffffff8199a510)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff819a2faa)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff819ac8b0)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff819f05db)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff819fbb0d)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (ffffffff81a0b1c7)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff81a13b02)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff81a458a7)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a484af)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81a4bdc4)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81a9e8e7)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81aa950d)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/taskstats.c (ffffffff811aa06f)
Location: include/net/netlink.h:572
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_pre_doit
```
```
In net/core/net_namespace.c (ffffffff819f9af6)
Location: include/net/netlink.h:572
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81a12921)
Location: include/net/netlink.h:572
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81a19a80)
Location: include/net/netlink.h:572
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81a412c6)
Location: include/net/netlink.h:572
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff81a6a321)
Location: include/net/netlink.h:572
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a6f604)
Location: include/net/netlink.h:572
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
In net/sched/act_api.c (ffffffff81a7346e)
Location: include/net/netlink.h:572
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff81a7c5c3)
Location: include/net/netlink.h:572
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
```
```
In net/ethtool/netlink.c (ffffffff81a8605a)
Location: include/net/netlink.h:572
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_parse
```
```
In net/ethtool/linkinfo.c (ffffffff81a88875)
Location: include/net/netlink.h:572
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
```
```
In net/ethtool/linkmodes.c (ffffffff81a89046)
Location: include/net/netlink.h:572
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
```
```
In net/ethtool/debug.c (ffffffff81a895cc)
Location: include/net/netlink.h:572
Inline: True
Inline callers:
  - net/ethtool/debug.c:ethnl_set_debug
```
```
In net/ethtool/wol.c (ffffffff81a899b2)
Location: include/net/netlink.h:572
Inline: True
Inline callers:
  - net/ethtool/wol.c:ethnl_set_wol
```
```
In net/ethtool/features.c (ffffffff81a8a096)
Location: include/net/netlink.h:572
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
```
```
In net/ethtool/privflags.c (ffffffff81a8a648)
Location: include/net/netlink.h:572
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_set_privflags
```
```
In net/ethtool/rings.c (ffffffff81a8aaf6)
Location: include/net/netlink.h:572
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
```
```
In net/ethtool/channels.c (ffffffff81a8b055)
Location: include/net/netlink.h:572
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
```
```
In net/ethtool/coalesce.c (ffffffff81a8ba15)
Location: include/net/netlink.h:572
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
```
```
In net/ethtool/pause.c (ffffffff81a8c0ef)
Location: include/net/netlink.h:572
Inline: True
Inline callers:
  - net/ethtool/pause.c:ethnl_set_pause
```
```
In net/ethtool/eee.c (ffffffff81a8c5f4)
Location: include/net/netlink.h:572
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
```
```
In net/ethtool/cabletest.c (ffffffff81a8d7d5)
Location: include/net/netlink.h:572
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
```
```
In net/ipv4/route.c (ffffffff81a91c04)
Location: include/net/netlink.h:572
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
```
```
In net/ipv4/devinet.c (ffffffff81ade549)
Location: include/net/netlink.h:572
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae9e24)
Location: include/net/netlink.h:572
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (ffffffff81afbf6b)
Location: include/net/netlink.h:572
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff81b013bc)
Location: include/net/netlink.h:572
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
```
```
In net/ipv6/addrconf.c (ffffffff81b3c638)
Location: include/net/netlink.h:572
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b3f33d)
Location: include/net/netlink.h:572
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81b41324)
Location: include/net/netlink.h:572
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81b996d5)
Location: include/net/netlink.h:572
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba587d)
Location: include/net/netlink.h:572
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In net/core/net_namespace.c (ffffffff819f9646)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81a12c71)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81a19c70)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81a43b07)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff81a72a51)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a78004)
Location: include/net/netlink.h:587
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
In net/sched/act_api.c (ffffffff81a7c06e)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff81a85101)
Location: include/net/netlink.h:587
Inline: True
```
```
In net/ipv4/route.c (ffffffff81a9ba94)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
```
```
In net/ipv4/devinet.c (ffffffff81aeb329)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff81af6c84)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (ffffffff81b097fb)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff81b0f49c)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
```
```
In net/ipv6/addrconf.c (ffffffff81b4b348)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b4ddcd)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81b4fde4)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81ba937e)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81bb4d4d)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In net/core/net_namespace.c (ffffffff819df7b2)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff819fa105)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81a00c70)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81a28888)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff81a5b3a1)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a60e0b)
Location: include/net/netlink.h:587
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
In net/sched/act_api.c (ffffffff81a64c9f)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff81a6e0e1)
Location: include/net/netlink.h:587
Inline: True
```
```
In net/ipv4/route.c (ffffffff81a86fd4)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
```
```
In net/ipv4/devinet.c (ffffffff81ad8055)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae23d4)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (ffffffff81af5943)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_req
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff81afd19c)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
```
```
In net/ipv6/addrconf.c (ffffffff81b38ed8)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b3b86d)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81b3e404)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81b9850e)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba3d2d)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In drivers/net/wwan/wwan_core.c (ffffffff8191aa79)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In net/core/net_namespace.c (ffffffff81a8fb92)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81aabe81)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81ab3030)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81add628)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff81b14561)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81b1a01b)
Location: include/net/netlink.h:587
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
In net/sched/act_api.c (ffffffff81b1df6f)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff81b27761)
Location: include/net/netlink.h:587
Inline: True
```
```
In net/ipv4/route.c (ffffffff81b41794)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
```
```
In net/ipv4/devinet.c (ffffffff81b96eb5)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba1ba4)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (ffffffff81bb6243)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_req
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff81bbe98c)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
```
```
In net/ipv6/addrconf.c (ffffffff81bff678)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_valid_dump_ifaddr_req
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81c020fd)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81c04ce4)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81c6505e)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81c7168d)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In drivers/net/wwan/wwan_core.c (ffffffff81a6fecb)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In net/core/net_namespace.c (ffffffff81c05946)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81c242c0)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81c33cf8)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_stats_get_parse
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81c5efba)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff81c9b907)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81ca1219)
Location: include/net/netlink.h:587
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
In net/sched/act_api.c (ffffffff81ca5947)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff81cb0707)
Location: include/net/netlink.h:587
Inline: True
```
```
In net/ipv4/route.c (ffffffff81cce20e)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
```
```
In net/ipv4/devinet.c (ffffffff81d28a5e)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff81d3428a)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (ffffffff81d49e3c)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_req
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff81d52da8)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
```
```
In net/ipv6/addrconf.c (ffffffff81d990f8)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81d9c095)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81d9ea1e)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81e07c76)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81e15243)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mctp/device.c (ffffffff81e38489)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_rtm_deladdr
  - net/mctp/device.c:mctp_rtm_newaddr
```
```
In net/mctp/route.c (ffffffff81e3968e)
Location: include/net/netlink.h:587
Inline: True
```
```
In net/mctp/neigh.c (ffffffff81e3b549)
Location: include/net/netlink.h:587
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_delneigh
  - net/mctp/neigh.c:mctp_rtm_newneigh
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
In drivers/net/wwan/wwan_core.c (ffffffff81c02d5b)
Location: include/net/netlink.h:602
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In net/core/net_namespace.c (ffffffff81db5216)
Location: include/net/netlink.h:602
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81dd68f0)
Location: include/net/netlink.h:602
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81de7158)
Location: include/net/netlink.h:602
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_stats_get_parse
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81e1584a)
Location: include/net/netlink.h:602
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff81e57e3c)
Location: include/net/netlink.h:602
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81e5d289)
Location: include/net/netlink.h:602
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
In net/sched/act_api.c (ffffffff81e639e7)
Location: include/net/netlink.h:602
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff81e6e4e7)
Location: include/net/netlink.h:602
Inline: True
```
```
In net/ipv4/route.c (ffffffff81e8e1de)
Location: include/net/netlink.h:602
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
```
```
In net/ipv4/devinet.c (ffffffff81ef04ae)
Location: include/net/netlink.h:602
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff81efc75a)
Location: include/net/netlink.h:602
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (ffffffff81f134ac)
Location: include/net/netlink.h:602
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_req
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff81f1d738)
Location: include/net/netlink.h:602
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
```
```
In net/ipv6/addrconf.c (ffffffff81f67e18)
Location: include/net/netlink.h:602
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81f6ad65)
Location: include/net/netlink.h:602
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81f6d9de)
Location: include/net/netlink.h:602
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/ip6mr.c (ffffffff81fad192)
Location: include/net/netlink.h:602
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
```
```
In net/dcb/dcbnl.c (ffffffff81fdd1c6)
Location: include/net/netlink.h:602
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81fec1a3)
Location: include/net/netlink.h:602
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mctp/device.c (ffffffff82011709)
Location: include/net/netlink.h:602
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_rtm_deladdr
  - net/mctp/device.c:mctp_rtm_newaddr
```
```
In net/mctp/route.c (ffffffff8201273e)
Location: include/net/netlink.h:602
Inline: True
```
```
In net/mctp/neigh.c (ffffffff82014c19)
Location: include/net/netlink.h:602
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_delneigh
  - net/mctp/neigh.c:mctp_rtm_newneigh
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
In drivers/net/wwan/wwan_core.c (ffffffff81c6840b)
Location: include/net/netlink.h:603
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In net/core/net_namespace.c (ffffffff81e257e6)
Location: include/net/netlink.h:603
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81e47720)
Location: include/net/netlink.h:603
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81e51418)
Location: include/net/netlink.h:603
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_mdb_del
  - net/core/rtnetlink.c:rtnl_mdb_add
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_stats_get_parse
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81e8915a)
Location: include/net/netlink.h:603
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff81eb37d6)
Location: include/net/netlink.h:603
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81eb9e39)
Location: include/net/netlink.h:603
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
In net/sched/act_api.c (ffffffff81ebfa7f)
Location: include/net/netlink.h:603
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff81eca607)
Location: include/net/netlink.h:603
Inline: True
```
```
In net/ipv4/route.c (ffffffff81eec91e)
Location: include/net/netlink.h:603
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
```
```
In net/ipv4/devinet.c (ffffffff81f4fefe)
Location: include/net/netlink.h:603
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5c18a)
Location: include/net/netlink.h:603
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (ffffffff81f7317c)
Location: include/net/netlink.h:603
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_req
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff81f7d238)
Location: include/net/netlink.h:603
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
```
```
In net/ipv6/addrconf.c (ffffffff81fc7f08)
Location: include/net/netlink.h:603
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81fcad95)
Location: include/net/netlink.h:603
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81fcdaae)
Location: include/net/netlink.h:603
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/ip6mr.c (ffffffff8200d952)
Location: include/net/netlink.h:603
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
```
```
In net/dcb/dcbnl.c (ffffffff82059296)
Location: include/net/netlink.h:603
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff82068443)
Location: include/net/netlink.h:603
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mctp/device.c (ffffffff8208e4e9)
Location: include/net/netlink.h:603
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_rtm_deladdr
  - net/mctp/device.c:mctp_rtm_newaddr
```
```
In net/mctp/route.c (ffffffff8208f52e)
Location: include/net/netlink.h:603
Inline: True
```
```
In net/mctp/neigh.c (ffffffff82091a39)
Location: include/net/netlink.h:603
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_delneigh
  - net/mctp/neigh.c:mctp_rtm_newneigh
```
```
In net/handshake/tlshd.c (ffffffff82093cf6)
Location: include/net/netlink.h:603
Inline: True
Inline callers:
  - net/handshake/tlshd.c:tls_handshake_done
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
In net/core/net_namespace.c (ffffffff81ee3746)
Location: include/net/netlink.h:610
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81f063d0)
Location: include/net/netlink.h:610
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81f11bb1)
Location: include/net/netlink.h:610
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_mdb_del
  - net/core/rtnetlink.c:rtnl_mdb_del
  - net/core/rtnetlink.c:rtnl_mdb_add
  - net/core/rtnetlink.c:rtnl_mdb_get
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_stats_get_parse
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81f4b16a)
Location: include/net/netlink.h:610
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff81f76206)
Location: include/net/netlink.h:610
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81f7d0a9)
Location: include/net/netlink.h:610
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
In net/sched/act_api.c (ffffffff81f82c2f)
Location: include/net/netlink.h:610
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff81f8cfc7)
Location: include/net/netlink.h:610
Inline: True
```
```
In net/ipv4/route.c (ffffffff81fb097e)
Location: include/net/netlink.h:610
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
```
```
In net/ipv4/devinet.c (ffffffff820160ae)
Location: include/net/netlink.h:610
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff820226ea)
Location: include/net/netlink.h:610
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (ffffffff8203923c)
Location: include/net/netlink.h:610
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_req
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff82043938)
Location: include/net/netlink.h:610
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
```
```
In net/ipv6/addrconf.c (ffffffff82095634)
Location: include/net/netlink.h:610
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff82098535)
Location: include/net/netlink.h:610
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff8209b2fe)
Location: include/net/netlink.h:610
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/ip6mr.c (ffffffff820dd3d2)
Location: include/net/netlink.h:610
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
```
```
In net/dcb/dcbnl.c (ffffffff8212be16)
Location: include/net/netlink.h:610
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff8213b6c3)
Location: include/net/netlink.h:610
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mctp/device.c (ffffffff821649d9)
Location: include/net/netlink.h:610
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_rtm_deladdr
  - net/mctp/device.c:mctp_rtm_newaddr
```
```
In net/mctp/route.c (ffffffff82165a0e)
Location: include/net/netlink.h:610
Inline: True
```
```
In net/mctp/neigh.c (ffffffff82167fd9)
Location: include/net/netlink.h:610
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_delneigh
  - net/mctp/neigh.c:mctp_rtm_newneigh
```
```
In net/handshake/tlshd.c (ffffffff8216a618)
Location: include/net/netlink.h:610
Inline: True
Inline callers:
  - net/handshake/tlshd.c:tls_handshake_done
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
In kernel/taskstats.c (ffff80001020d1e4)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_pre_doit
```
```
In net/core/net_namespace.c (ffff800010bc1d04)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffff800010be6830)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffff800010beb220)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:valid_fdb_dump_legacy
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffff800010c1389c)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/devlink.c (ffff800010c2e298)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (ffff800010c3e540)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffff800010c44450)
Location: include/net/netlink.h:520
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
In net/sched/act_api.c (ffff800010c47730)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffff800010c511c0)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffff800010c5ca48)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffff800010ca6440)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffff800010cb3b54)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (ffff800010cc47a4)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffff800010cce15c)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffff800010d08228)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffff800010d0b81c)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffff800010d11350)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffff800010d6f2dc)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffff800010d7cf88)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/taskstats.c (c044bb7c)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_pre_doit
```
```
In net/core/net_namespace.c (c0cdc854)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (c0d00194)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (c0d03f18)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:valid_fdb_dump_legacy
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_calcit
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (c0d2b278)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/devlink.c (c0d45540)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (c0d4ffb0)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (c0d54fa4)
Location: include/net/netlink.h:520
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
In net/sched/act_api.c (c0d58520)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (c0d619e8)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (c0d6c110)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (c0db2f14)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (c0dbee38)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (c0dd01d4)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (c0dd9254)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (c0e0ea18)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (c0e11700)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (c0e156b4)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (c0e6cf44)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (c0e77d8c)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/taskstats.c (c00000000028af40)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_pre_doit
```
```
In net/core/net_namespace.c (c000000000c9b4e8)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (c000000000cc5fa4)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (c000000000cce638)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:valid_fdb_dump_legacy
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (c000000000d00c1c)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/devlink.c (c000000000d28eb0)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (c000000000d386a8)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (c000000000d3f928)
Location: include/net/netlink.h:520
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
In net/sched/act_api.c (c000000000d445c4)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (c000000000d51a18)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (c000000000d5ef98)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (c000000000dbac38)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (c000000000dcacc0)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (c000000000de07d0)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (c000000000deacc0)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (c000000000e32624)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (c000000000e35fd8)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (c000000000e3a734)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (c000000000eae13c)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (c000000000ebcae0)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/taskstats.c (ffffffe00016e322)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_pre_doit
```
```
In net/core/net_namespace.c (ffffffe00074ed62)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffe000769db2)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffe00076ebd0)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:valid_fdb_dump_legacy
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffe00078f06a)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/devlink.c (ffffffe0007a156e)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (ffffffe0007ae5b0)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffe0007b27f6)
Location: include/net/netlink.h:520
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
In net/sched/act_api.c (ffffffe0007b5474)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffe0007bc4e8)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffe0007c58c6)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffe000801c50)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffe00080bac8)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (ffffffe000819c2a)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffe0008204ee)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffe000850368)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffe0008528cc)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffe00085604e)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffe0008a0eaa)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffe0008aabe8)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/taskstats.c (ffffffff8118d32f)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_pre_doit
```
```
In net/core/net_namespace.c (ffffffff818c595c)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff818e2811)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff818e96c0)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:valid_fdb_dump_legacy
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff8190d0b9)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/devlink.c (ffffffff81928183)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (ffffffff81931dc5)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81937134)
Location: include/net/netlink.h:520
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
In net/sched/act_api.c (ffffffff8193a380)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff81942e1a)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff8194c720)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff8199037b)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff8199b8ad)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (ffffffff819aaf67)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff819b3302)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff819e4f37)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff819e7b3f)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff819eb454)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81a3dc77)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a4889d)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/taskstats.c (ffffffff8118044f)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_pre_doit
```
```
In net/core/net_namespace.c (ffffffff8187f89c)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff8189c651)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff818a3500)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:valid_fdb_dump_legacy
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff818c6e79)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/devlink.c (ffffffff818e1f33)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (ffffffff818eb8c5)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff818f0c34)
Location: include/net/netlink.h:520
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
In net/sched/act_api.c (ffffffff818f3e80)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff818fc90a)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff81906210)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff81949e3b)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff8195536d)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (ffffffff81964a27)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff8196f932)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff819a1cf7)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff819a48ff)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff819a8214)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff819fa867)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a0548d)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/taskstats.c (ffffffff8118b0ff)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_pre_doit
```
```
In net/core/net_namespace.c (ffffffff8191695c)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81933841)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff8193a6f0)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:valid_fdb_dump_legacy
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff8195e0e9)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/devlink.c (ffffffff81979313)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (ffffffff81982f55)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff819882c4)
Location: include/net/netlink.h:520
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
In net/sched/act_api.c (ffffffff8198b510)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff81993faa)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff819b6ef0)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff819fac1b)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff81a0614d)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (ffffffff81a15807)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff81a1dba2)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff81a4f9b7)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a525bf)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81a55ed4)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81aa9b27)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ab474d)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/taskstats.c (ffffffff81198a6f)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_pre_doit
```
```
In net/core/net_namespace.c (ffffffff81937b6c)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81955171)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff8195bf20)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:valid_fdb_dump_legacy
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81980339)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/devlink.c (ffffffff8199b803)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (ffffffff819a54a5)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff819aa534)
Location: include/net/netlink.h:520
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
In net/sched/act_api.c (ffffffff819add80)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff819b6aaa)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff819c0770)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff81a04f6b)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff81a107bd)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (ffffffff81a20247)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff81a28df2)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff81a5b997)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a5e5bf)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81a61f04)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81ab5e97)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ac0aed)
Location: include/net/netlink.h:520
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
</details>
</li>
</ul>

## Differences
