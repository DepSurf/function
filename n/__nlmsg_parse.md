# Function: <code>__nlmsg_parse</code>

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
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff819101d1)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff8191828e)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
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
In net/core/fib_rules.c (ffffffff8193a220)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/devlink.c (ffffffff819518a6)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (ffffffff8195ba9a)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff819601ba)
Location: include/net/netlink.h:655
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
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff8196c49e)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff81975e95)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff819b98d8)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff819c4f62)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/nexthop.c (ffffffff819d4640)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff819db563)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff81a0ebf8)
Location: include/net/netlink.h:655
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
In net/ipv6/addrlabel.c (ffffffff81a11884)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81a151e8)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81a67f7a)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a72d12)
Location: include/net/netlink.h:655
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
In net/core/net_namespace.c (ffffffff81925953)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81942841)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff8194a8ae)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
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
In net/core/fib_rules.c (ffffffff8196d0e0)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/devlink.c (ffffffff819882e6)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (ffffffff81991f4a)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff8199729a)
Location: include/net/netlink.h:655
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
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff819a2e4e)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff819ac8a5)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff819f05d2)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff819fbb02)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/nexthop.c (ffffffff81a0b1b0)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff81a12438)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff81a4589c)
Location: include/net/netlink.h:655
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
In net/ipv6/addrlabel.c (ffffffff81a484a4)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81a4bdb8)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81a9e8da)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81aa94f2)
Location: include/net/netlink.h:655
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
In net/core/net_namespace.c (ffffffff819f9aed)
Location: include/net/netlink.h:707
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81a12921)
Location: include/net/netlink.h:707
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff81a1b0ea)
Location: include/net/netlink.h:707
Inline: True
Inline callers:
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
In net/core/fib_rules.c (ffffffff81a412bd)
Location: include/net/netlink.h:707
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff81a6a314)
Location: include/net/netlink.h:707
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a6f5da)
Location: include/net/netlink.h:707
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
Location: include/net/netlink.h:707
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff81a7c592)
Location: include/net/netlink.h:707
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
```
```
In net/ethtool/netlink.c (ffffffff81a86055)
Location: include/net/netlink.h:707
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_parse
```
```
In net/ethtool/linkinfo.c (ffffffff81a88862)
Location: include/net/netlink.h:707
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
```
```
In net/ethtool/linkmodes.c (ffffffff81a8903b)
Location: include/net/netlink.h:707
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
```
```
In net/ethtool/debug.c (ffffffff81a895bd)
Location: include/net/netlink.h:707
Inline: True
Inline callers:
  - net/ethtool/debug.c:ethnl_set_debug
```
```
In net/ethtool/wol.c (ffffffff81a8999f)
Location: include/net/netlink.h:707
Inline: True
Inline callers:
  - net/ethtool/wol.c:ethnl_set_wol
```
```
In net/ethtool/features.c (ffffffff81a8a083)
Location: include/net/netlink.h:707
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
```
```
In net/ethtool/privflags.c (ffffffff81a8a635)
Location: include/net/netlink.h:707
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_set_privflags
```
```
In net/ethtool/rings.c (ffffffff81a8aae7)
Location: include/net/netlink.h:707
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
```
```
In net/ethtool/channels.c (ffffffff81a8b046)
Location: include/net/netlink.h:707
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
```
```
In net/ethtool/coalesce.c (ffffffff81a8ba06)
Location: include/net/netlink.h:707
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
```
```
In net/ethtool/pause.c (ffffffff81a8c0d9)
Location: include/net/netlink.h:707
Inline: True
Inline callers:
  - net/ethtool/pause.c:ethnl_set_pause
```
```
In net/ethtool/eee.c (ffffffff81a8c5de)
Location: include/net/netlink.h:707
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
```
```
In net/ethtool/cabletest.c (ffffffff81a8d7ca)
Location: include/net/netlink.h:707
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
```
```
In net/ipv4/route.c (ffffffff81a91bf9)
Location: include/net/netlink.h:707
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
```
```
In net/ipv4/devinet.c (ffffffff81ade540)
Location: include/net/netlink.h:707
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae9e19)
Location: include/net/netlink.h:707
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/nexthop.c (ffffffff81afbf56)
Location: include/net/netlink.h:707
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff81b013b1)
Location: include/net/netlink.h:707
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
```
```
In net/ipv6/addrconf.c (ffffffff81b3c62c)
Location: include/net/netlink.h:707
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
In net/ipv6/addrlabel.c (ffffffff81b3f332)
Location: include/net/netlink.h:707
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81b41319)
Location: include/net/netlink.h:707
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81b996c8)
Location: include/net/netlink.h:707
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba5862)
Location: include/net/netlink.h:707
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
In net/core/net_namespace.c (ffffffff819f963d)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81a12c71)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff81a1b27a)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
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
In net/core/fib_rules.c (ffffffff81a43afe)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff81a72a44)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a77fda)
Location: include/net/netlink.h:722
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
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff81a850ef)
Location: include/net/netlink.h:722
Inline: True
```
```
In net/ipv4/route.c (ffffffff81a9ba89)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
```
```
In net/ipv4/devinet.c (ffffffff81aeb320)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff81af6c79)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/nexthop.c (ffffffff81b097e6)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff81b0f491)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
```
```
In net/ipv6/addrconf.c (ffffffff81b4b33c)
Location: include/net/netlink.h:722
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
In net/ipv6/addrlabel.c (ffffffff81b4ddc2)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81b4fdd9)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81ba9371)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81bb4d32)
Location: include/net/netlink.h:722
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
In net/core/net_namespace.c (ffffffff819df7a9)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff819fa105)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff81a053f6)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81a2887f)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff81a5b394)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a60e02)
Location: include/net/netlink.h:722
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
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff81a6e0cf)
Location: include/net/netlink.h:722
Inline: True
```
```
In net/ipv4/route.c (ffffffff81a86fc9)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
```
```
In net/ipv4/devinet.c (ffffffff81ad804c)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae23c9)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/nexthop.c (ffffffff81af592d)
Location: include/net/netlink.h:722
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
In net/ipv4/ipmr.c (ffffffff81afd191)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
```
```
In net/ipv6/addrconf.c (ffffffff81b38ecc)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b3b862)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81b3e3f9)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81b98501)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba3d12)
Location: include/net/netlink.h:722
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
In drivers/net/wwan/wwan_core.c (ffffffff8191aa70)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In net/core/net_namespace.c (ffffffff81a8fb89)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81aabe81)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff81ab7836)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81add61f)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff81b14554)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81b1a012)
Location: include/net/netlink.h:722
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
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff81b2774f)
Location: include/net/netlink.h:722
Inline: True
```
```
In net/ipv4/route.c (ffffffff81b41789)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
```
```
In net/ipv4/devinet.c (ffffffff81b96eac)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba1b99)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/nexthop.c (ffffffff81bb622d)
Location: include/net/netlink.h:722
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
In net/ipv4/ipmr.c (ffffffff81bbe981)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
```
```
In net/ipv6/addrconf.c (ffffffff81bff66c)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_valid_dump_ifaddr_req
  - net/ipv6/addrconf.c:inet6_valid_dump_ifaddr_req
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81c020f2)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81c04cd9)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81c65051)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81c71672)
Location: include/net/netlink.h:722
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
In drivers/net/wwan/wwan_core.c (ffffffff81a6fec2)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In net/core/net_namespace.c (ffffffff81c0593d)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81c242c0)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff81c33ced)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_stats_get_parse
  - net/core/rtnetlink.c:rtnl_stats_get_parse
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81c5efaf)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff81c9b8fa)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81ca1210)
Location: include/net/netlink.h:722
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
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff81cb06f1)
Location: include/net/netlink.h:722
Inline: True
```
```
In net/ipv4/route.c (ffffffff81cce201)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
```
```
In net/ipv4/devinet.c (ffffffff81d28a55)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff81d3427f)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/nexthop.c (ffffffff81d49e27)
Location: include/net/netlink.h:722
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
In net/ipv4/ipmr.c (ffffffff81d52d9b)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
```
```
In net/ipv6/addrconf.c (ffffffff81d990ed)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81d9c08a)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81d9ea11)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81e07c6b)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81e15224)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mctp/device.c (ffffffff81e38475)
Location: include/net/netlink.h:722
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_rtm_deladdr
  - net/mctp/device.c:mctp_rtm_newaddr
```
```
In net/mctp/route.c (ffffffff81e39676)
Location: include/net/netlink.h:722
Inline: True
```
```
In net/mctp/neigh.c (ffffffff81e3b535)
Location: include/net/netlink.h:722
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
In drivers/net/wwan/wwan_core.c (ffffffff81c02d52)
Location: include/net/netlink.h:737
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In net/core/net_namespace.c (ffffffff81db520d)
Location: include/net/netlink.h:737
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81dd68f0)
Location: include/net/netlink.h:737
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff81de714d)
Location: include/net/netlink.h:737
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_stats_get_parse
  - net/core/rtnetlink.c:rtnl_stats_get_parse
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81e1583f)
Location: include/net/netlink.h:737
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff81e57e1e)
Location: include/net/netlink.h:737
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81e5d280)
Location: include/net/netlink.h:737
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
Location: include/net/netlink.h:737
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff81e6e4d1)
Location: include/net/netlink.h:737
Inline: True
```
```
In net/ipv4/route.c (ffffffff81e8e1d1)
Location: include/net/netlink.h:737
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
```
```
In net/ipv4/devinet.c (ffffffff81ef04a5)
Location: include/net/netlink.h:737
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff81efc74f)
Location: include/net/netlink.h:737
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/nexthop.c (ffffffff81f13497)
Location: include/net/netlink.h:737
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
In net/ipv4/ipmr.c (ffffffff81f1d72b)
Location: include/net/netlink.h:737
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
```
```
In net/ipv6/addrconf.c (ffffffff81f67e0d)
Location: include/net/netlink.h:737
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81f6ad5a)
Location: include/net/netlink.h:737
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81f6d9d1)
Location: include/net/netlink.h:737
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/ip6mr.c (ffffffff81fad168)
Location: include/net/netlink.h:737
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
```
```
In net/dcb/dcbnl.c (ffffffff81fdd1bb)
Location: include/net/netlink.h:737
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81fec184)
Location: include/net/netlink.h:737
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mctp/device.c (ffffffff820116f5)
Location: include/net/netlink.h:737
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_rtm_deladdr
  - net/mctp/device.c:mctp_rtm_newaddr
```
```
In net/mctp/route.c (ffffffff82012726)
Location: include/net/netlink.h:737
Inline: True
```
```
In net/mctp/neigh.c (ffffffff82014c05)
Location: include/net/netlink.h:737
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
In drivers/net/wwan/wwan_core.c (ffffffff81c68402)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In net/core/net_namespace.c (ffffffff81e257dd)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81e47720)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff81e51406)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_mdb_del
  - net/core/rtnetlink.c:rtnl_mdb_del
  - net/core/rtnetlink.c:rtnl_mdb_add
  - net/core/rtnetlink.c:rtnl_mdb_add
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_stats_get_parse
  - net/core/rtnetlink.c:rtnl_stats_get_parse
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81e8914f)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff81eb37be)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81eb9e30)
Location: include/net/netlink.h:738
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
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff81eca5f1)
Location: include/net/netlink.h:738
Inline: True
```
```
In net/ipv4/route.c (ffffffff81eec911)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
```
```
In net/ipv4/devinet.c (ffffffff81f4fef5)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5c17f)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/nexthop.c (ffffffff81f73167)
Location: include/net/netlink.h:738
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
In net/ipv4/ipmr.c (ffffffff81f7d22b)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
```
```
In net/ipv6/addrconf.c (ffffffff81fc7efd)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81fcad8a)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81fcdaa1)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/ip6mr.c (ffffffff8200d928)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
```
```
In net/dcb/dcbnl.c (ffffffff8205928b)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff82068424)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mctp/device.c (ffffffff8208e4d5)
Location: include/net/netlink.h:738
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_rtm_deladdr
  - net/mctp/device.c:mctp_rtm_newaddr
```
```
In net/mctp/route.c (ffffffff8208f516)
Location: include/net/netlink.h:738
Inline: True
```
```
In net/mctp/neigh.c (ffffffff82091a25)
Location: include/net/netlink.h:738
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
In net/core/net_namespace.c (ffffffff81ee373d)
Location: include/net/netlink.h:745
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81f063d0)
Location: include/net/netlink.h:745
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff81f11ba8)
Location: include/net/netlink.h:745
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_mdb_del
  - net/core/rtnetlink.c:rtnl_mdb_del
  - net/core/rtnetlink.c:rtnl_mdb_del
  - net/core/rtnetlink.c:rtnl_mdb_add
  - net/core/rtnetlink.c:rtnl_mdb_add
  - net/core/rtnetlink.c:rtnl_mdb_get
  - net/core/rtnetlink.c:rtnl_mdb_get
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_stats_get_parse
  - net/core/rtnetlink.c:rtnl_stats_get_parse
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81f4b15f)
Location: include/net/netlink.h:745
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff81f761ee)
Location: include/net/netlink.h:745
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81f7d0a0)
Location: include/net/netlink.h:745
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
Location: include/net/netlink.h:745
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff81f8cfb1)
Location: include/net/netlink.h:745
Inline: True
```
```
In net/ipv4/route.c (ffffffff81fb0971)
Location: include/net/netlink.h:745
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
```
```
In net/ipv4/devinet.c (ffffffff820160a5)
Location: include/net/netlink.h:745
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff820226df)
Location: include/net/netlink.h:745
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/nexthop.c (ffffffff82039227)
Location: include/net/netlink.h:745
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
In net/ipv4/ipmr.c (ffffffff8204392b)
Location: include/net/netlink.h:745
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
```
```
In net/ipv6/addrconf.c (ffffffff82095629)
Location: include/net/netlink.h:745
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff8209852a)
Location: include/net/netlink.h:745
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff8209b2f1)
Location: include/net/netlink.h:745
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/ip6mr.c (ffffffff820dd3a8)
Location: include/net/netlink.h:745
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
```
```
In net/dcb/dcbnl.c (ffffffff8212be0b)
Location: include/net/netlink.h:745
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff8213b6a4)
Location: include/net/netlink.h:745
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mctp/device.c (ffffffff821649c5)
Location: include/net/netlink.h:745
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_rtm_deladdr
  - net/mctp/device.c:mctp_rtm_newaddr
```
```
In net/mctp/route.c (ffffffff821659f6)
Location: include/net/netlink.h:745
Inline: True
```
```
In net/mctp/neigh.c (ffffffff82167fc5)
Location: include/net/netlink.h:745
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffff800010bc1cfc)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffff800010be682c)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffff800010bed7f4)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
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
In net/core/fib_rules.c (ffff800010c13894)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/devlink.c (ffff800010c2e290)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (ffff800010c3e534)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffff800010c44428)
Location: include/net/netlink.h:655
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
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffff800010c51050)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffff800010c5ca3c)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffff800010ca6438)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffff800010cb3b48)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/nexthop.c (ffff800010cc4794)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffff800010ccb118)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffff800010d0821c)
Location: include/net/netlink.h:655
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
In net/ipv6/addrlabel.c (ffff800010d0b810)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffff800010d11344)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffff800010d6f2d0)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffff800010d7cf78)
Location: include/net/netlink.h:655
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
In net/core/net_namespace.c (c0cdc84c)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (c0d00194)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (c0d05d68)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
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
In net/core/fib_rules.c (c0d2b270)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/devlink.c (c0d45528)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (c0d4ffa4)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (c0d54f84)
Location: include/net/netlink.h:655
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
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (c0d61874)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (c0d6c104)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (c0db2f0c)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (c0dbee2c)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/nexthop.c (c0dd01d0)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (c0dd6a54)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (c0e0ea0c)
Location: include/net/netlink.h:655
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
In net/ipv6/addrlabel.c (c0e116f4)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (c0e156a8)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (c0e6cf38)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (c0e77d7c)
Location: include/net/netlink.h:655
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
In net/core/net_namespace.c (c000000000c9b4e0)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (c000000000cc5fa0)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (c000000000cd02f0)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
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
In net/core/fib_rules.c (c000000000d00c14)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/devlink.c (c000000000d28ea4)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (c000000000d3869c)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (c000000000d3f8f0)
Location: include/net/netlink.h:655
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
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (c000000000d51864)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (c000000000d5ef8c)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (c000000000dbac30)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (c000000000dcacb4)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/nexthop.c (c000000000de07c8)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (c000000000dec280)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (c000000000e32618)
Location: include/net/netlink.h:655
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
In net/ipv6/addrlabel.c (c000000000e35fcc)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (c000000000e3a728)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (c000000000eae130)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (c000000000ebcacc)
Location: include/net/netlink.h:655
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
In net/core/net_namespace.c (ffffffe00074ed00)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffe000769da4)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffe000770504)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
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
In net/core/fib_rules.c (ffffffe00078f060)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/devlink.c (ffffffe0007a155e)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (ffffffe0007ae5a6)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffe0007b27ca)
Location: include/net/netlink.h:655
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
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffe0007bc3ea)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffe0007c58c0)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffe000801be2)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffe00080ba9a)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/nexthop.c (ffffffe000819c18)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffe000821332)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffe000850360)
Location: include/net/netlink.h:655
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
In net/ipv6/addrlabel.c (ffffffe0008528c6)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffe000856046)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffe0008a0ea2)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffe0008aabde)
Location: include/net/netlink.h:655
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
In net/core/net_namespace.c (ffffffff818c5953)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff818e2811)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff818ea87e)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
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
In net/core/fib_rules.c (ffffffff8190d0b0)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/devlink.c (ffffffff81928156)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (ffffffff81931dba)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff8193710a)
Location: include/net/netlink.h:655
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
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff81942cbe)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff8194c715)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff81990372)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff8199b8a2)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/nexthop.c (ffffffff819aaf50)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff819b1d53)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff819e4f2c)
Location: include/net/netlink.h:655
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
In net/ipv6/addrlabel.c (ffffffff819e7b34)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff819eb448)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81a3dc6a)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a48882)
Location: include/net/netlink.h:655
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
In net/core/net_namespace.c (ffffffff8187f893)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff8189c651)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff818a46be)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
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
In net/core/fib_rules.c (ffffffff818c6e70)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/devlink.c (ffffffff818e1f06)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (ffffffff818eb8ba)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff818f0c0a)
Location: include/net/netlink.h:655
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
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff818fc7ae)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff81906205)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff81949e32)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff81955362)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/nexthop.c (ffffffff81964a10)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff8196e383)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff819a1cec)
Location: include/net/netlink.h:655
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
In net/ipv6/addrlabel.c (ffffffff819a48f4)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff819a8208)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff819fa85a)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a05472)
Location: include/net/netlink.h:655
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
In net/core/net_namespace.c (ffffffff81916953)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81933841)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff8193b8ae)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
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
In net/core/fib_rules.c (ffffffff8195e0e0)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/devlink.c (ffffffff819792e6)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (ffffffff81982f4a)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff8198829a)
Location: include/net/netlink.h:655
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
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff81993e4e)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff819b6ee5)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff819fac12)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff81a06142)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/nexthop.c (ffffffff81a157f0)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff81a1c5f3)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff81a4f9ac)
Location: include/net/netlink.h:655
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
In net/ipv6/addrlabel.c (ffffffff81a525b4)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81a55ec8)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81aa9b1a)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ab4732)
Location: include/net/netlink.h:655
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
In net/core/net_namespace.c (ffffffff81937b63)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81955171)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neigh_valid_dump_req
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
```
```
In net/core/rtnetlink.c (ffffffff8195d12e)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
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
In net/core/fib_rules.c (ffffffff81980330)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/devlink.c (ffffffff8199b7d6)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (ffffffff819a549a)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff819aa50a)
Location: include/net/netlink.h:655
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
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/genetlink.c (ffffffff819b694e)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff819c0765)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff81a04f62)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/fib_frontend.c (ffffffff81a107b2)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/nexthop.c (ffffffff81a20230)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:nh_valid_get_del_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff81a27548)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff81a5b98c)
Location: include/net/netlink.h:655
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
In net/ipv6/addrlabel.c (ffffffff81a5e5b4)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81a61ef8)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/dcb/dcbnl.c (ffffffff81ab5e8a)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ac0ad2)
Location: include/net/netlink.h:655
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
</details>
</li>
</ul>

## Differences
