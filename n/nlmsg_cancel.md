# Function: <code>nlmsg_cancel</code>

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
In net/core/net_namespace.c (ffffffff8170fe58)
Location: include/net/netlink.h:536
Inline: True
```
```
In net/core/neighbour.c (ffffffff817267aa)
Location: include/net/netlink.h:536
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_dump_info
```
```
In net/core/rtnetlink.c (ffffffff8172d299)
Location: include/net/netlink.h:536
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/fib_rules.c (ffffffff81739ee4)
Location: include/net/netlink.h:536
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff8174fc10)
Location: include/net/netlink.h:536
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:genl_ctrl_event
```
```
In net/ipv4/route.c (ffffffff81753e7d)
Location: include/net/netlink.h:536
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff817818f9)
Location: include/net/netlink.h:536
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff81790355)
Location: include/net/netlink.h:536
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8179dac8)
Location: include/net/netlink.h:536
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff817a8841)
Location: include/net/netlink.h:536
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff817cb926)
Location: include/net/netlink.h:536
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/addrlabel.c (ffffffff817d25d8)
Location: include/net/netlink.h:536
Inline: True
```
```
In net/ipv6/route.c (ffffffff817d8707)
Location: include/net/netlink.h:536
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff817f9383)
Location: include/net/netlink.h:536
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff81809c24)
Location: include/net/netlink.h:536
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8180db6e)
Location: include/net/netlink.h:536
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8180e876)
Location: include/net/netlink.h:536
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8180fd62)
Location: include/net/netlink.h:536
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
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
In net/core/net_namespace.c (ffffffff81777798)
Location: include/net/netlink.h:547
Inline: True
```
```
In net/core/neighbour.c (ffffffff81790fbe)
Location: include/net/netlink.h:547
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81799075)
Location: include/net/netlink.h:547
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff817a61e9)
Location: include/net/netlink.h:547
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff817bc55d)
Location: include/net/netlink.h:547
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff817bff41)
Location: include/net/netlink.h:547
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff817eedb9)
Location: include/net/netlink.h:547
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff817fdec3)
Location: include/net/netlink.h:547
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8180b60f)
Location: include/net/netlink.h:547
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff81815f71)
Location: include/net/netlink.h:547
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff8183894e)
Location: include/net/netlink.h:547
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/addrlabel.c (ffffffff81840098)
Location: include/net/netlink.h:547
Inline: True
```
```
In net/ipv6/route.c (ffffffff81842109)
Location: include/net/netlink.h:547
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81868bc3)
Location: include/net/netlink.h:547
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff8187b724)
Location: include/net/netlink.h:547
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8188004f)
Location: include/net/netlink.h:547
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81880f00)
Location: include/net/netlink.h:547
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81882430)
Location: include/net/netlink.h:547
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81883430)
Location: include/net/netlink.h:547
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/switchdev/switchdev.c (ffffffff8188ae6b)
Location: include/net/netlink.h:547
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
In net/core/net_namespace.c (ffffffff817a4818)
Location: include/net/netlink.h:547
Inline: True
```
```
In net/core/neighbour.c (ffffffff817be862)
Location: include/net/netlink.h:547
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff817c6e25)
Location: include/net/netlink.h:547
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff817d4d42)
Location: include/net/netlink.h:547
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff817ebe6d)
Location: include/net/netlink.h:547
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff817f3100)
Location: include/net/netlink.h:547
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181f7c9)
Location: include/net/netlink.h:547
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff8182ee23)
Location: include/net/netlink.h:547
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8183c728)
Location: include/net/netlink.h:547
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff81847721)
Location: include/net/netlink.h:547
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff8186a47e)
Location: include/net/netlink.h:547
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/addrlabel.c (ffffffff81871d18)
Location: include/net/netlink.h:547
Inline: True
```
```
In net/ipv6/route.c (ffffffff81873e59)
Location: include/net/netlink.h:547
Inline: True
```
```
In net/ipv6/seg6.c (ffffffff81899951)
Location: include/net/netlink.h:547
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff8189ba13)
Location: include/net/netlink.h:547
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff818affe4)
Location: include/net/netlink.h:547
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818b48ff)
Location: include/net/netlink.h:547
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818b57b0)
Location: include/net/netlink.h:547
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818b6ce0)
Location: include/net/netlink.h:547
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818b7cd0)
Location: include/net/netlink.h:547
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/switchdev/switchdev.c (ffffffff818bf23b)
Location: include/net/netlink.h:547
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
In net/core/net_namespace.c (ffffffff817c2958)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/core/neighbour.c (ffffffff817ddb5d)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff817e5736)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff817f40da)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff8180bdd1)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff81813ac1)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_metrics.c (ffffffff8184019b)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff8184f31e)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8185de7b)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff8186aa08)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff8188e9d4)
Location: include/net/netlink.h:556
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
Location: include/net/netlink.h:556
Inline: True
```
```
In net/ipv6/route.c (ffffffff81898e5f)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff818bfb5e)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff818c1dd8)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff818d69c2)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818db282)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818dc09f)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818dd5c4)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818de5c4)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/switchdev/switchdev.c (ffffffff818e5b52)
Location: include/net/netlink.h:556
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
In net/core/net_namespace.c (ffffffff8183c298)
Location: include/net/netlink.h:562
Inline: True
```
```
In net/core/neighbour.c (ffffffff81857edd)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff818607d6)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff8186f83f)
Location: include/net/netlink.h:562
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff8188ad61)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff81893124)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bf53b)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff818cef4e)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff818ddeab)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff818eb193)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81910024)
Location: include/net/netlink.h:562
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
Location: include/net/netlink.h:562
Inline: True
```
```
In net/ipv6/route.c (ffffffff8191a165)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81942c2e)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81945718)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff8195c592)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81960e62)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81961c82)
Location: include/net/netlink.h:562
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819631b4)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819641c4)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
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
In net/core/net_namespace.c (ffffffff81886cf8)
Location: include/net/netlink.h:562
Inline: True
```
```
In net/core/neighbour.c (ffffffff818a308e)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff818aa686)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff818c102a)
Location: include/net/netlink.h:562
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff818de38b)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff818e731d)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_metrics.c (ffffffff81915131)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff81925d15)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81934a26)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff81941978)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81967434)
Location: include/net/netlink.h:562
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
Location: include/net/netlink.h:562
Inline: True
```
```
In net/ipv6/route.c (ffffffff8197229a)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff8199bb44)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff8199d208)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff819b5db2)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819ba67a)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819bb45f)
Location: include/net/netlink.h:562
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819bca04)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819bda64)
Location: include/net/netlink.h:562
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffff819cb17a)
Location: include/net/netlink.h:562
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
In net/core/net_namespace.c (ffffffff818a741f)
Location: include/net/netlink.h:705
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff818c5ad1)
Location: include/net/netlink.h:705
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff818d0523)
Location: include/net/netlink.h:705
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff818e9e37)
Location: include/net/netlink.h:705
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff8190ad4b)
Location: include/net/netlink.h:705
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff819141d3)
Location: include/net/netlink.h:705
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_metrics.c (ffffffff81943aee)
Location: include/net/netlink.h:705
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff81954cb2)
Location: include/net/netlink.h:705
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81964373)
Location: include/net/netlink.h:705
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff81971227)
Location: include/net/netlink.h:705
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff8199ca41)
Location: include/net/netlink.h:705
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
Location: include/net/netlink.h:705
Inline: True
```
```
In net/ipv6/route.c (ffffffff819a79f2)
Location: include/net/netlink.h:705
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff819d2714)
Location: include/net/netlink.h:705
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff819d3d65)
Location: include/net/netlink.h:705
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff819ed06f)
Location: include/net/netlink.h:705
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f1eba)
Location: include/net/netlink.h:705
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f26df)
Location: include/net/netlink.h:705
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f3c54)
Location: include/net/netlink.h:705
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f4c04)
Location: include/net/netlink.h:705
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a03c4c)
Location: include/net/netlink.h:705
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
In net/core/net_namespace.c (ffffffff818f24bf)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81911af2)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff8191d3d1)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81939899)
Location: include/net/netlink.h:939
Inline: True
```
```
In net/core/devlink.c (ffffffff81951a72)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff8196c144)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff819712bd)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a848f)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff819b8c22)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff819c9ea6)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff819da9af)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81a08c1c)
Location: include/net/netlink.h:939
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
Location: include/net/netlink.h:939
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a14071)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81a41553)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff81a41fe4)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81a5c25d)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a611b5)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a61a60)
Location: include/net/netlink.h:939
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a630aa)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a640ba)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a72ef2)
Location: include/net/netlink.h:939
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
In net/core/net_namespace.c (ffffffff8192440f)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81944162)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff8194fa04)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff8196c766)
Location: include/net/netlink.h:939
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff819765d0)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (ffffffff81983b60)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff819a2af4)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff819a7cda)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff819df15f)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff819ef922)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81a00a66)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff81a1189e)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81a3f32c)
Location: include/net/netlink.h:939
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
Location: include/net/netlink.h:939
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a4ac61)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81a781d3)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff81a78c44)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81a92e89)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a97dda)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a985ed)
Location: include/net/netlink.h:939
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a99c65)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a9ac45)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81aa96d2)
Location: include/net/netlink.h:939
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
In net/core/net_namespace.c (ffffffff819f80df)
Location: include/net/netlink.h:991
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81a141e9)
Location: include/net/netlink.h:991
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
```
```
In net/core/rtnetlink.c (ffffffff81a21222)
Location: include/net/netlink.h:991
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81a4061a)
Location: include/net/netlink.h:991
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81a4b342)
Location: include/net/netlink.h:991
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (ffffffff81a5f73d)
Location: include/net/netlink.h:991
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff81a7c6f0)
Location: include/net/netlink.h:991
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81a85b87)
Location: include/net/netlink.h:991
Inline: True
```
```
In net/ipv4/route.c (ffffffff81a91444)
Location: include/net/netlink.h:991
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acbf6f)
Location: include/net/netlink.h:991
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff81addd6a)
Location: include/net/netlink.h:991
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81aefbf5)
Location: include/net/netlink.h:991
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81afaf2c)
Location: include/net/netlink.h:991
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81b04c5e)
Location: include/net/netlink.h:991
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81b34fac)
Location: include/net/netlink.h:991
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
Location: include/net/netlink.h:991
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b451c5)
Location: include/net/netlink.h:991
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81b721a3)
Location: include/net/netlink.h:991
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff81b7456e)
Location: include/net/netlink.h:991
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff81b8e199)
Location: include/net/netlink.h:991
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b936fa)
Location: include/net/netlink.h:991
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b93d19)
Location: include/net/netlink.h:991
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b954b5)
Location: include/net/netlink.h:991
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b96415)
Location: include/net/netlink.h:991
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba5ac2)
Location: include/net/netlink.h:991
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb393c)
Location: include/net/netlink.h:991
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
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
In drivers/thermal/thermal_netlink.c (ffffffff8195f791)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/net_namespace.c (ffffffff819f7b3f)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81a14491)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
```
```
In net/core/rtnetlink.c (ffffffff81a1f7af)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81a4331a)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81a50f72)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (ffffffff81a67f2d)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff81a85acb)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81a8f517)
Location: include/net/netlink.h:1004
Inline: True
```
```
In net/ethtool/tunnels.c (ffffffff81a978af)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
```
In net/ipv4/route.c (ffffffff81a9b2c5)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad7f39)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff81aeab4a)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81afcb35)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81b085fc)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81b12dce)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81b43bd1)
Location: include/net/netlink.h:1004
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
Location: include/net/netlink.h:1004
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b53b68)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81b80f03)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff81b832de)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff81b9de42)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81ba334a)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba395f)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ba5125)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ba6085)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81bb4f98)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc7bd1)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
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
In drivers/thermal/thermal_netlink.c (ffffffff81942cf5)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/net_namespace.c (ffffffff819ddcbf)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff819fae21)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81a0687f)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81a2807a)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81a35efc)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/devlink.c (ffffffff81a42f55)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff81a6f46e)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81a78d3d)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/ethtool/tunnels.c (ffffffff81a8130e)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
```
In net/ipv4/route.c (ffffffff81a866e5)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac30a9)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff81ad628a)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae837a)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81af6f45)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81b009c4)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81b31831)
Location: include/net/netlink.h:1004
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
Location: include/net/netlink.h:1004
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b4112d)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81b6fb03)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff81b71f60)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff81b8cf42)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b9246a)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b92a7f)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b9426a)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b951fa)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba3f74)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb9327)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
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
In drivers/thermal/thermal_netlink.c (ffffffff819e77c6)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/net_namespace.c (ffffffff81a8df52)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81aaca61)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81ab8cdf)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81adce1a)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81aebaf2)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/devlink.c (ffffffff81af93c5)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff81b2820e)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81b32f0d)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/ethtool/tunnels.c (ffffffff81b3b05e)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
```
In net/ipv4/route.c (ffffffff81b40e25)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b80c92)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff81b94fba)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba82ab)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81bb68bb)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81bc2016)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81bf78d1)
Location: include/net/netlink.h:1004
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
Location: include/net/netlink.h:1004
Inline: True
```
```
In net/ipv6/route.c (ffffffff81c08e03)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81c37c53)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ioam6.c (ffffffff81c3945c)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/ipv6/ip6mr.c (ffffffff81c3c410)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff81c592e2)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81c5ec0a)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81c5f21f)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81c60a0a)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81c61a2a)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81c718d4)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81c88797)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
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
In drivers/thermal/thermal_netlink.c (ffffffff81b4d090)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/net_namespace.c (ffffffff81c03bc7)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81c25a76)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81c31f2b)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81c5e466)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81c6e433)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/devlink.c (ffffffff81c7c2d5)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff81cb11fe)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81cbeac7)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/ethtool/tunnels.c (ffffffff81cc6fc5)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
```
In net/ipv4/route.c (ffffffff81ccd95a)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d110a4)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff81d26c1b)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3ae3b)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81d4a5fb)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81d5636c)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81d90d7c)
Location: include/net/netlink.h:1004
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
Location: include/net/netlink.h:1004
Inline: True
```
```
In net/ipv6/route.c (ffffffff81da38c7)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81dd581c)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ioam6.c (ffffffff81dd6d19)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/ipv6/ip6mr.c (ffffffff81dda7d2)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff81dfaa4f)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81e00e4c)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e015f6)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81e02efe)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81e0401e)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81e15467)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81e2f2d0)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
```
```
In net/mctp/device.c (ffffffff81e37fe2)
Location: include/net/netlink.h:1004
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_fill_addrinfo
```
```
In net/mctp/route.c (ffffffff81e39347)
Location: include/net/netlink.h:1004
Inline: True
```
```
In net/mctp/neigh.c (ffffffff81e3b4b9)
Location: include/net/netlink.h:1004
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
In drivers/thermal/thermal_netlink.c (ffffffff81ce4d90)
Location: include/net/netlink.h:1053
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/net_namespace.c (ffffffff81db3277)
Location: include/net/netlink.h:1053
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81dd7cb6)
Location: include/net/netlink.h:1053
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81de52fb)
Location: include/net/netlink.h:1053
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81e14b8a)
Location: include/net/netlink.h:1053
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81e260bc)
Location: include/net/netlink.h:1053
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/core/devlink.c (ffffffff81e40ba5)
Location: include/net/netlink.h:1053
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_cmd_selftests_run
  - net/core/devlink.c:devlink_nl_selftests_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff81e6f1d0)
Location: include/net/netlink.h:1053
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81e7d5e7)
Location: include/net/netlink.h:1053
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/ethtool/tunnels.c (ffffffff81e86615)
Location: include/net/netlink.h:1053
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
```
In net/ipv4/route.c (ffffffff81e8dad7)
Location: include/net/netlink.h:1053
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed6e34)
Location: include/net/netlink.h:1053
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff81eee5bb)
Location: include/net/netlink.h:1053
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81f037ab)
Location: include/net/netlink.h:1053
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81f13c9b)
Location: include/net/netlink.h:1053
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81f203cc)
Location: include/net/netlink.h:1053
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81f5f49c)
Location: include/net/netlink.h:1053
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
Location: include/net/netlink.h:1053
Inline: True
```
```
In net/ipv6/route.c (ffffffff81f72d07)
Location: include/net/netlink.h:1053
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81fa6fac)
Location: include/net/netlink.h:1053
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ioam6.c (ffffffff81fa86b9)
Location: include/net/netlink.h:1053
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/ipv6/ip6mr.c (ffffffff81fac4f2)
Location: include/net/netlink.h:1053
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff81fcf1f7)
Location: include/net/netlink.h:1053
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81fd5cac)
Location: include/net/netlink.h:1053
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd6456)
Location: include/net/netlink.h:1053
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81fd7e3e)
Location: include/net/netlink.h:1053
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81fd8fde)
Location: include/net/netlink.h:1053
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81fec3c7)
Location: include/net/netlink.h:1053
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff820079ca)
Location: include/net/netlink.h:1053
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
```
```
In net/mctp/device.c (ffffffff82011212)
Location: include/net/netlink.h:1053
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_fill_addrinfo
```
```
In net/mctp/route.c (ffffffff82012607)
Location: include/net/netlink.h:1053
Inline: True
```
```
In net/mctp/neigh.c (ffffffff82014b79)
Location: include/net/netlink.h:1053
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
In drivers/thermal/thermal_netlink.c (ffffffff81d4d360)
Location: include/net/netlink.h:1054
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/net_namespace.c (ffffffff81e23847)
Location: include/net/netlink.h:1054
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81e48a82)
Location: include/net/netlink.h:1054
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81e56d17)
Location: include/net/netlink.h:1054
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/netdev-genl.c (ffffffff81e7ced6)
Location: include/net/netlink.h:1054
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81e8849a)
Location: include/net/netlink.h:1054
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81e9b65c)
Location: include/net/netlink.h:1054
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/netlink/genetlink.c (ffffffff81ecb2e0)
Location: include/net/netlink.h:1054
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81ed9ba7)
Location: include/net/netlink.h:1054
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/ethtool/tunnels.c (ffffffff81ee2ff7)
Location: include/net/netlink.h:1054
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
```
In net/ipv4/route.c (ffffffff81eec209)
Location: include/net/netlink.h:1054
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f35ddf)
Location: include/net/netlink.h:1054
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff81f4df79)
Location: include/net/netlink.h:1054
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81f6318b)
Location: include/net/netlink.h:1054
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81f7396b)
Location: include/net/netlink.h:1054
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81f7fecc)
Location: include/net/netlink.h:1054
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81fbf1ca)
Location: include/net/netlink.h:1054
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
Location: include/net/netlink.h:1054
Inline: True
```
```
In net/ipv6/route.c (ffffffff81fd2dfd)
Location: include/net/netlink.h:1054
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff8200780c)
Location: include/net/netlink.h:1054
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ioam6.c (ffffffff82009049)
Location: include/net/netlink.h:1054
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/ipv6/ip6mr.c (ffffffff8200cc92)
Location: include/net/netlink.h:1054
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/devlink/leftover.c (ffffffff82037769)
Location: include/net/netlink.h:1054
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_trap_policer_fill
  - net/devlink/leftover.c:devlink_nl_trap_group_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
  - net/devlink/leftover.c:devlink_nl_region_notify_build
  - net/devlink/leftover.c:devlink_nl_port_fill
```
```
In net/devlink/dev.c (ffffffff82045ac8)
Location: include/net/netlink.h:1054
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_cmd_selftests_run
  - net/devlink/dev.c:devlink_nl_selftests_fill
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/dev.c:devlink_nl_cmd_reload
  - net/devlink/dev.c:devlink_nl_fill
```
```
In net/devlink/health.c (ffffffff8204842b)
Location: include/net/netlink.h:1054
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/devlink/health.c:devlink_nl_health_reporter_fill
```
```
In net/wireless/wext-core.c (ffffffff8204ae22)
Location: include/net/netlink.h:1054
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8205196c)
Location: include/net/netlink.h:1054
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82052116)
Location: include/net/netlink.h:1054
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82053b2e)
Location: include/net/netlink.h:1054
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff82054cae)
Location: include/net/netlink.h:1054
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffff82068667)
Location: include/net/netlink.h:1054
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff82083d0b)
Location: include/net/netlink.h:1054
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
```
```
In net/mctp/device.c (ffffffff8208dfd2)
Location: include/net/netlink.h:1054
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_fill_addrinfo
```
```
In net/mctp/route.c (ffffffff8208f3f7)
Location: include/net/netlink.h:1054
Inline: True
```
```
In net/mctp/neigh.c (ffffffff82091999)
Location: include/net/netlink.h:1054
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_getneigh
```
```
In net/handshake/netlink.c (ffffffff8209259d)
Location: include/net/netlink.h:1054
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_genl_notify
```
```
In net/handshake/tlshd.c (ffffffff82094071)
Location: include/net/netlink.h:1054
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
In drivers/thermal/thermal_netlink.c (ffffffff81e03e50)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In drivers/dpll/dpll_netlink.c (ffffffff81ebb9b6)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - drivers/dpll/dpll_netlink.c:dpll_nl_device_get_dumpit
  - drivers/dpll/dpll_netlink.c:dpll_nl_pin_get_dumpit
  - drivers/dpll/dpll_netlink.c:dpll_pin_event_send
  - drivers/dpll/dpll_netlink.c:dpll_device_event_send
```
```
In net/core/net_namespace.c (ffffffff81ee17a7)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81f07642)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81f1606d)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/netdev-genl.c (ffffffff81f3d2aa)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/core/netdev-genl.c:netdev_nl_queue_fill_one
  - net/core/netdev-genl.c:netdev_nl_napi_fill_one
  - net/core/netdev-genl.c:netdev_nl_dev_fill
  - net/core/netdev-genl.c:netdev_nl_dev_fill
```
```
In net/core/page_pool_user.c (ffffffff81f453a0)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/core/page_pool_user.c:page_pool_nl_fill
  - net/core/page_pool_user.c:page_pool_nl_stats_fill
```
```
In net/core/fib_rules.c (ffffffff81f4a4aa)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81f5ddcc)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
```
```
In net/netlink/genetlink.c (ffffffff81f8e7d0)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81f9d9e3)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/ethtool/tunnels.c (ffffffff81fa6e24)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
```
In net/ipv4/route.c (ffffffff81fb0259)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffbe8f)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff820140a9)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8202975b)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff8203a15b)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff8204654c)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff8208c662)
Location: include/net/netlink.h:1075
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
Location: include/net/netlink.h:1075
Inline: True
```
```
In net/ipv6/route.c (ffffffff820a070d)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff820d669c)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ioam6.c (ffffffff820d7fb9)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/ipv6/ip6mr.c (ffffffff820dbc62)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/devlink/dev.c (ffffffff8210540b)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_selftests_run_doit
  - net/devlink/dev.c:devlink_nl_selftests_fill
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/dev.c:devlink_nl_reload_doit
  - net/devlink/dev.c:devlink_nl_fill
```
```
In net/devlink/port.c (ffffffff82106a83)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_nl_port_fill
```
```
In net/devlink/sb.c (ffffffff82108993)
Location: include/net/netlink.h:1075
Inline: True
```
```
In net/devlink/param.c (ffffffff8210e162)
Location: include/net/netlink.h:1075
Inline: True
```
```
In net/devlink/region.c (ffffffff82111690)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/devlink/region.c:devlink_nl_region_read_dumpit
  - net/devlink/region.c:devlink_nl_region_notify_build
```
```
In net/devlink/health.c (ffffffff82114597)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_health_reporter_dump_get_dumpit
  - net/devlink/health.c:devlink_nl_health_reporter_fill
```
```
In net/devlink/trap.c (ffffffff82114b99)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_nl_trap_policer_fill
  - net/devlink/trap.c:devlink_nl_trap_group_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
```
```
In net/devlink/rate.c (ffffffff82118a07)
Location: include/net/netlink.h:1075
Inline: True
```
```
In net/devlink/linecard.c (ffffffff82119a6d)
Location: include/net/netlink.h:1075
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff8211d2a6)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8212413c)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8212495d)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8212630e)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff8212758e)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffff8213b8e7)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff8215c06b)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_addr_dumpit
```
```
In net/mctp/device.c (ffffffff82164492)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_fill_addrinfo
```
```
In net/mctp/route.c (ffffffff821658d7)
Location: include/net/netlink.h:1075
Inline: True
```
```
In net/mctp/neigh.c (ffffffff82167f39)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_getneigh
```
```
In net/handshake/netlink.c (ffffffff82168e83)
Location: include/net/netlink.h:1075
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_genl_notify
```
```
In net/handshake/tlshd.c (ffffffff8216a991)
Location: include/net/netlink.h:1075
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
In net/core/net_namespace.c (ffff800010bbfd60)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffff800010be4048)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffff800010bf16f4)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffff800010c12fb8)
Location: include/net/netlink.h:939
Inline: True
```
```
In net/core/drop_monitor.c (ffff800010c1caa0)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (ffff800010c2c198)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffff800010c51dcc)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffff800010c575a8)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffff800010c924cc)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffff800010ca5798)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffff800010cb9248)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffff800010cc9f7c)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffff800010d02808)
Location: include/net/netlink.h:939
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
Location: include/net/netlink.h:939
Inline: True
```
```
In net/ipv6/route.c (ffff800010d0dc90)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffff800010d41760)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffff800010d423bc)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffff800010d60ca0)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffff800010d673b4)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d67da0)
Location: include/net/netlink.h:939
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffff800010d696ec)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffff800010d6a834)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffff800010d7d148)
Location: include/net/netlink.h:939
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
In net/core/net_namespace.c (c0cdb85c)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (c0cfe4e8)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (c0d09ec0)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (c0d2a968)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (c0d34a30)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (c0d42760)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (c0d61484)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (c0d671f8)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (c0db20f4)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (c0dc47dc)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (c0dd5f1c)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (c0e08630)
Location: include/net/netlink.h:939
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
Location: include/net/netlink.h:939
Inline: True
```
```
In net/ipv6/route.c (c0e145b4)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (c0e44154)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (c0e44cfc)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (c0e60630)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (c0e65bc4)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_protocols_cb
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (c0e66610)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
```
```
In net/netlabel/netlabel_cipso_v4.c (c0e67cd8)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (c0e68db8)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (c0e77f24)
Location: include/net/netlink.h:939
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
In net/core/net_namespace.c (c000000000c991f8)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (c000000000cc74e0)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (c000000000cd627c)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (c000000000d00040)
Location: include/net/netlink.h:939
Inline: True
```
```
In net/core/drop_monitor.c (c000000000d0dae0)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (c000000000d22ce0)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (c000000000d508fc)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (c000000000d58bb0)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (c000000000da2b90)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (c000000000db9780)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (c000000000dd1f40)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (c000000000de93ec)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (c000000000e2a140)
Location: include/net/netlink.h:939
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
Location: include/net/netlink.h:939
Inline: True
```
```
In net/ipv6/route.c (c000000000e39b60)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (c000000000e76010)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (c000000000e77230)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (c000000000e9c050)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (c000000000ea3140)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (c000000000ea46d0)
Location: include/net/netlink.h:939
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (c000000000ea6528)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (c000000000ea7ba8)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (c000000000ebcd38)
Location: include/net/netlink.h:939
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
In net/core/net_namespace.c (ffffffe00074d61e)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffe00076aa02)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffe00077346a)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffe00078e988)
Location: include/net/netlink.h:939
Inline: True
```
```
In net/core/drop_monitor.c (ffffffe000796978)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (ffffffe0007a377a)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffe0007bce42)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffe0007c1844)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f2290)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffe000801048)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffe00080fe18)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffe00081f45a)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffe00084abf2)
Location: include/net/netlink.h:939
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
Location: include/net/netlink.h:939
Inline: True
```
```
In net/ipv6/route.c (ffffffe000855926)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffe00087ce24)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffe00087da44)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffe00089601c)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffe00089ac24)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089b256)
Location: include/net/netlink.h:939
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffe00089c644)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffe00089d3f4)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffe0008aad3a)
Location: include/net/netlink.h:939
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
In net/core/net_namespace.c (ffffffff818c440f)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff818e4132)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff818ef9d4)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff8190c736)
Location: include/net/netlink.h:939
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff819165a0)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (ffffffff819239d0)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff81942964)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff81947b4a)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197efcf)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff8198f6c2)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff819a0806)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff819b11b7)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff819de9bc)
Location: include/net/netlink.h:939
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
Location: include/net/netlink.h:939
Inline: True
```
```
In net/ipv6/route.c (ffffffff819ea2f1)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81a17863)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff81a182d4)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81a32519)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a3716a)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a3797d)
Location: include/net/netlink.h:939
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a38ff5)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a39fd5)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a48a62)
Location: include/net/netlink.h:939
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
In drivers/net/vxlan.c (ffffffff8176cf60)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_fdb_info
```
```
In net/core/net_namespace.c (ffffffff8187e34f)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff8189df72)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff818a9814)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff818c64f6)
Location: include/net/netlink.h:939
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff818d0350)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (ffffffff818dd780)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff818fc454)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff8190163a)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81938a8f)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff81949182)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8195a2c6)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff8196d7e7)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff8199b77c)
Location: include/net/netlink.h:939
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
Location: include/net/netlink.h:939
Inline: True
```
```
In net/ipv6/route.c (ffffffff819a70b1)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff819d4623)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff819d5094)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff819ef709)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f3d8a)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f459d)
Location: include/net/netlink.h:939
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f5c15)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f6bf5)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a05652)
Location: include/net/netlink.h:939
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
In net/core/net_namespace.c (ffffffff8191540f)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81935162)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81940a04)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff8195d766)
Location: include/net/netlink.h:939
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff819675d0)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (ffffffff81974b60)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff81993af4)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819ae7d9)
Location: include/net/netlink.h:939
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
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e979f)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff819f9f62)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0b0a6)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff81a1ba57)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81a4943c)
Location: include/net/netlink.h:939
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
Location: include/net/netlink.h:939
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a54d71)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81a822e3)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff81a82d54)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81a9e0c9)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aa301a)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aa382d)
Location: include/net/netlink.h:939
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81aa4ea5)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81aa5e85)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ab4912)
Location: include/net/netlink.h:939
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
In net/core/net_namespace.c (ffffffff819365ef)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81956872)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81962314)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff8197f9b6)
Location: include/net/netlink.h:939
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81989860)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
```
In net/core/devlink.c (ffffffff81997050)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/genetlink.c (ffffffff819b65ee)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff819bb9da)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f352f)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff81a04272)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81a15886)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff81a269ae)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81a5535c)
Location: include/net/netlink.h:939
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
Location: include/net/netlink.h:939
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a60d61)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81a8ebf3)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff81a8f624)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81aaa2c9)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aaf38a)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aafc4d)
Location: include/net/netlink.h:939
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ab1225)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ab2225)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ac0cb2)
Location: include/net/netlink.h:939
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
</details>
</li>
</ul>

## Differences
