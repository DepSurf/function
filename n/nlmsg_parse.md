# Function: <code>nlmsg_parse</code>

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
In net/core/net_namespace.c (ffffffff81710066)
Location: include/net/netlink.h:368
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81727125)
Location: include/net/netlink.h:368
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff8172b037)
Location: include/net/netlink.h:368
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_calcit
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/fib_rules.c (ffffffff8173a3dc)
Location: include/net/netlink.h:368
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff81744a20)
Location: include/net/netlink.h:368
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
```
```
In net/sched/cls_api.c (ffffffff8174656c)
Location: include/net/netlink.h:368
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_tfilter
```
```
In net/sched/act_api.c (ffffffff81746f50)
Location: include/net/netlink.h:368
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff8174f5e9)
Location: include/net/netlink.h:368
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff817571f9)
Location: include/net/netlink.h:368
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff81790476)
Location: include/net/netlink.h:368
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv6/addrconf.c (ffffffff817cce66)
Location: include/net/netlink.h:368
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
```
In net/ipv6/addrlabel.c (ffffffff817d2c08)
Location: include/net/netlink.h:368
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff817d3f39)
Location: include/net/netlink.h:368
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/dcb/dcbnl.c (ffffffff81813dc7)
Location: include/net/netlink.h:368
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
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
In net/core/net_namespace.c (ffffffff81778326)
Location: include/net/netlink.h:379
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81790c2d)
Location: include/net/netlink.h:379
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff817971fe)
Location: include/net/netlink.h:379
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_calcit
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff817a6b90)
Location: include/net/netlink.h:379
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff817b18e2)
Location: include/net/netlink.h:379
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff817b357e)
Location: include/net/netlink.h:379
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_tfilter
```
```
In net/sched/act_api.c (ffffffff817b41a0)
Location: include/net/netlink.h:379
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff817bb5cc)
Location: include/net/netlink.h:379
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff817c3499)
Location: include/net/netlink.h:379
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff817fd8f6)
Location: include/net/netlink.h:379
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv6/addrconf.c (ffffffff8183d6c6)
Location: include/net/netlink.h:379
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81840896)
Location: include/net/netlink.h:379
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff818425d9)
Location: include/net/netlink.h:379
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81886ca7)
Location: include/net/netlink.h:379
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
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
In net/core/net_namespace.c (ffffffff817a4da6)
Location: include/net/netlink.h:379
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff817be2db)
Location: include/net/netlink.h:379
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff817c43f6)
Location: include/net/netlink.h:379
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_calcit
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff817d5660)
Location: include/net/netlink.h:379
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff817e1012)
Location: include/net/netlink.h:379
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff817e2e2e)
Location: include/net/netlink.h:379
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_tfilter
```
```
In net/sched/act_api.c (ffffffff817e3a50)
Location: include/net/netlink.h:379
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff817eafce)
Location: include/net/netlink.h:379
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff817f2a89)
Location: include/net/netlink.h:379
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff8182e856)
Location: include/net/netlink.h:379
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv6/addrconf.c (ffffffff8186f2d6)
Location: include/net/netlink.h:379
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81872516)
Location: include/net/netlink.h:379
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81874329)
Location: include/net/netlink.h:379
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff818bb517)
Location: include/net/netlink.h:379
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
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
In net/core/net_namespace.c (ffffffff817c2fb6)
Location: include/net/netlink.h:384
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff817dd5a2)
Location: include/net/netlink.h:384
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff817e2751)
Location: include/net/netlink.h:384
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_calcit
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff817f4ac9)
Location: include/net/netlink.h:384
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff81800521)
Location: include/net/netlink.h:384
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff8180230d)
Location: include/net/netlink.h:384
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_ctl_tfilter
```
```
In net/sched/act_api.c (ffffffff818033a0)
Location: include/net/netlink.h:384
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff8180af35)
Location: include/net/netlink.h:384
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff81813369)
Location: include/net/netlink.h:384
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff8184f996)
Location: include/net/netlink.h:384
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/ipmr.c (ffffffff8186aef9)
Location: include/net/netlink.h:384
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff818940b6)
Location: include/net/netlink.h:384
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff818972b6)
Location: include/net/netlink.h:384
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff8189915b)
Location: include/net/netlink.h:384
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff818e1f08)
Location: include/net/netlink.h:384
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
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
In net/core/net_namespace.c (ffffffff8183cb06)
Location: include/net/netlink.h:390
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81857922)
Location: include/net/netlink.h:390
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff8185d611)
Location: include/net/netlink.h:390
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff818702b3)
Location: include/net/netlink.h:390
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff8187e314)
Location: include/net/netlink.h:390
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff8188072b)
Location: include/net/netlink.h:390
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_ctl_tfilter
```
```
In net/sched/act_api.c (ffffffff818823fb)
Location: include/net/netlink.h:390
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff81889e85)
Location: include/net/netlink.h:390
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff818929b9)
Location: include/net/netlink.h:390
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff818cf5c6)
Location: include/net/netlink.h:390
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/ipmr.c (ffffffff818eb699)
Location: include/net/netlink.h:390
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff819154b6)
Location: include/net/netlink.h:390
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81917f56)
Location: include/net/netlink.h:390
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff8191d73b)
Location: include/net/netlink.h:390
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81967ca8)
Location: include/net/netlink.h:390
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
In net/core/net_namespace.c (ffffffff8188716f)
Location: include/net/netlink.h:390
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff818a2d37)
Location: include/net/netlink.h:390
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff818a919e)
Location: include/net/netlink.h:390
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff818c1987)
Location: include/net/netlink.h:390
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff818d0da8)
Location: include/net/netlink.h:390
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff818d34de)
Location: include/net/netlink.h:390
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff818d5f15)
Location: include/net/netlink.h:390
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff818ded2b)
Location: include/net/netlink.h:390
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff818e69d7)
Location: include/net/netlink.h:390
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff8192601f)
Location: include/net/netlink.h:390
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/ipmr.c (ffffffff819416f2)
Location: include/net/netlink.h:390
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff8196caaf)
Location: include/net/netlink.h:390
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff8196f79f)
Location: include/net/netlink.h:390
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81972534)
Location: include/net/netlink.h:390
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff819c14d8)
Location: include/net/netlink.h:390
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff819cafa2)
Location: include/net/netlink.h:390
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
In net/core/net_namespace.c (ffffffff818a83b3)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff818c40f9)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff818cb551)
Location: include/net/netlink.h:517
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
In net/core/fib_rules.c (ffffffff818ea7ab)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff818fc10a)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff818ff949)
Location: include/net/netlink.h:517
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
In net/sched/act_api.c (ffffffff81902719)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff8190b6eb)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff8191389e)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff81955042)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/ipmr.c (ffffffff81971d75)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff819a257f)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff819a53b2)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff819a80b0)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff819f8a28)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a03a62)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In net/ipv4/nexthop.c (ffffffff819d4640)
Location: include/net/netlink.h:682
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a0b1b0)
Location: include/net/netlink.h:682
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
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
In net/core/rtnetlink.c (ffffffff81a1ace1)
Location: include/net/netlink.h:734
Inline: True
```
```
In net/ethtool/netlink.c (ffffffff81a86055)
Location: include/net/netlink.h:734
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_parse
```
```
In net/ethtool/linkinfo.c (ffffffff81a88862)
Location: include/net/netlink.h:734
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
```
```
In net/ethtool/linkmodes.c (ffffffff81a8903b)
Location: include/net/netlink.h:734
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
```
```
In net/ethtool/debug.c (ffffffff81a895bd)
Location: include/net/netlink.h:734
Inline: True
Inline callers:
  - net/ethtool/debug.c:ethnl_set_debug
```
```
In net/ethtool/wol.c (ffffffff81a8999f)
Location: include/net/netlink.h:734
Inline: True
Inline callers:
  - net/ethtool/wol.c:ethnl_set_wol
```
```
In net/ethtool/features.c (ffffffff81a8a083)
Location: include/net/netlink.h:734
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
```
```
In net/ethtool/privflags.c (ffffffff81a8a635)
Location: include/net/netlink.h:734
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_set_privflags
```
```
In net/ethtool/rings.c (ffffffff81a8aae7)
Location: include/net/netlink.h:734
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
```
```
In net/ethtool/channels.c (ffffffff81a8b046)
Location: include/net/netlink.h:734
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
```
```
In net/ethtool/coalesce.c (ffffffff81a8ba06)
Location: include/net/netlink.h:734
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
```
```
In net/ethtool/pause.c (ffffffff81a8c0d9)
Location: include/net/netlink.h:734
Inline: True
Inline callers:
  - net/ethtool/pause.c:ethnl_set_pause
```
```
In net/ethtool/eee.c (ffffffff81a8c5de)
Location: include/net/netlink.h:734
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
```
```
In net/ethtool/cabletest.c (ffffffff81a8d7ca)
Location: include/net/netlink.h:734
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
```
```
In net/ipv4/nexthop.c (ffffffff81afbf56)
Location: include/net/netlink.h:734
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
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
In net/core/rtnetlink.c (ffffffff81a1af01)
Location: include/net/netlink.h:748
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81b097e6)
Location: include/net/netlink.h:748
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
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
In net/core/rtnetlink.c (ffffffff81a02791)
Location: include/net/netlink.h:748
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81af592d)
Location: include/net/netlink.h:748
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_req
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_to_nh_config
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
In net/core/rtnetlink.c (ffffffff81ab4d71)
Location: include/net/netlink.h:748
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81bb622d)
Location: include/net/netlink.h:748
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_req
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_to_nh_config
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
In net/core/rtnetlink.c (ffffffff81c33ced)
Location: include/net/netlink.h:748
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_stats_get_parse
  - net/core/rtnetlink.c:rtnl_fdb_del
```
```
In net/ipv4/nexthop.c (ffffffff81d49e27)
Location: include/net/netlink.h:748
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
In net/mctp/device.c (ffffffff81e38475)
Location: include/net/netlink.h:748
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_rtm_deladdr
  - net/mctp/device.c:mctp_rtm_newaddr
```
```
In net/mctp/route.c (ffffffff81e39676)
Location: include/net/netlink.h:748
Inline: True
```
```
In net/mctp/neigh.c (ffffffff81e3b535)
Location: include/net/netlink.h:748
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
In net/core/rtnetlink.c (ffffffff81de714d)
Location: include/net/netlink.h:764
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_stats_get_parse
  - net/core/rtnetlink.c:rtnl_fdb_del
```
```
In net/ipv4/nexthop.c (ffffffff81f13497)
Location: include/net/netlink.h:764
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
In net/ipv6/ip6mr.c (ffffffff81fad168)
Location: include/net/netlink.h:764
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
```
```
In net/mctp/device.c (ffffffff820116f5)
Location: include/net/netlink.h:764
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_rtm_deladdr
  - net/mctp/device.c:mctp_rtm_newaddr
```
```
In net/mctp/route.c (ffffffff82012726)
Location: include/net/netlink.h:764
Inline: True
```
```
In net/mctp/neigh.c (ffffffff82014c05)
Location: include/net/netlink.h:764
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
In net/core/rtnetlink.c (ffffffff81e5813d)
Location: include/net/netlink.h:765
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_stats_get_parse
  - net/core/rtnetlink.c:rtnl_fdb_del
```
```
In net/ipv4/nexthop.c (ffffffff81f73167)
Location: include/net/netlink.h:765
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
In net/ipv6/ip6mr.c (ffffffff8200d928)
Location: include/net/netlink.h:765
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
```
```
In net/mctp/device.c (ffffffff8208e4d5)
Location: include/net/netlink.h:765
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_rtm_deladdr
  - net/mctp/device.c:mctp_rtm_newaddr
```
```
In net/mctp/route.c (ffffffff8208f516)
Location: include/net/netlink.h:765
Inline: True
```
```
In net/mctp/neigh.c (ffffffff82091a25)
Location: include/net/netlink.h:765
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_delneigh
  - net/mctp/neigh.c:mctp_rtm_newneigh
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
In net/core/rtnetlink.c (ffffffff81f11bd4)
Location: include/net/netlink.h:772
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_mdb_del
  - net/core/rtnetlink.c:rtnl_mdb_get
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_stats_get_parse
  - net/core/rtnetlink.c:rtnl_fdb_del
```
```
In net/ipv4/nexthop.c (ffffffff82039227)
Location: include/net/netlink.h:772
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
In net/ipv6/ip6mr.c (ffffffff820dd3a8)
Location: include/net/netlink.h:772
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
```
```
In net/mctp/device.c (ffffffff821649c5)
Location: include/net/netlink.h:772
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_rtm_deladdr
  - net/mctp/device.c:mctp_rtm_newaddr
```
```
In net/mctp/route.c (ffffffff821659f6)
Location: include/net/netlink.h:772
Inline: True
```
```
In net/mctp/neigh.c (ffffffff82167fc5)
Location: include/net/netlink.h:772
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_delneigh
  - net/mctp/neigh.c:mctp_rtm_newneigh
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffff800010cc4794)
Location: include/net/netlink.h:682
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c0dd01d0)
Location: include/net/netlink.h:682
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c000000000de07c8)
Location: include/net/netlink.h:682
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffe000819c18)
Location: include/net/netlink.h:682
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819aaf50)
Location: include/net/netlink.h:682
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81964a10)
Location: include/net/netlink.h:682
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a157f0)
Location: include/net/netlink.h:682
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a20230)
Location: include/net/netlink.h:682
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
</details>
</li>
</ul>

## Differences
